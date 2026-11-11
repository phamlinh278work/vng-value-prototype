# VNG Value – bộ dựng màn hình (dùng chung cho mọi agent)

## Kết nối
- Chỉ dùng công cụ `mcp__reqwise-figma__*` (nạp bằng ToolSearch: `select:mcp__reqwise-figma__figma_write,mcp__reqwise-figma__figma_read,mcp__reqwise-figma__figma_docs`). Không dùng open-pencil hay plugin figma khác.
- Mọi lệnh truyền `file: "VNG Value"`, `page: "Màn hình"`.
- `figma_write` KHÔNG phải Figma Plugin API. Đọc `figma_docs({section:"api", level:"cheat"})` một lần trước khi viết. Hàm không lưu được qua các lần gọi, nên dán lại các helper bên dưới vào đầu mỗi lần gọi.
- Cảnh báo "No userflow on this page. ASK THE USER…" : bỏ qua, người dùng đã quyết định vẽ màn hình ngay (luồng nghiệp vụ đã có ở page Roadmap).
- Khi một lệnh lỗi: đọc `error.hint`, chỉ gửi lại phần chưa chạy. Không tạo frame thử nghiệm.

## Hai màn mẫu đã duyệt (xem để bắt chước, KHÔNG sửa trừ khi được giao)
- `1:8024` Hợp đồng / Danh sách / 1440
- `1:8292` Hợp đồng / Thêm mới / 1440
Chụp xem: `figma_read({op:"screenshot", file:"VNG Value", page:"Màn hình", params:{nodeId:"1:8024", scale:0.5}})`.

## Quy tắc thiết kế
- Desktop 1440. Màn danh sách cao 1024. Màn form/chi tiết dài thì bỏ `height` để khung tự cao theo nội dung (đã có `minHeight: 1024`).
- Màu chỉ dùng token: `$color/light/bg-subtle` (nền trang), `$color/light/surface` (thẻ), `$color/light/border`, `$color/light/text`, `$color/light/text-muted`, `$color/light/text-subtle`, `$color/light/primary`, `$color/light/primary-subtle`, `$color/light/primary-ink`, `$color/light/error`, `$color/light/error-subtle`, `$color/light/info-subtle`, `$color/light/warning-subtle`, `$color/light/success-subtle`. Không viết mã hex.
- Chữ chỉ dùng text style: `Heading/H4` (tiêu đề trang), `Title/Small` (tiêu đề thẻ), `Label/Large` (nhãn trường), `Body/Medium`, `Body/Small`, `Caption/Regular`. Không viết fontSize.
- Khoảng cách chỉ dùng 4 8 12 16 24 32. Mọi frame có con đều có `layoutMode`. Không đặt x/y bên trong màn hình.
- Bo góc: `tokens: { cornerRadius: "radius/lg" }`.
- Mỗi màn chỉ một nút `primary`.
- Đây là thiết kế MỚI. Giữ đúng tên trường và nghiệp vụ, nhưng không sao chép bố cục phần mềm cũ.
- Toàn bộ chữ trên giao diện là tiếng Việt có dấu đầy đủ.
- Dữ liệu mẫu phải là dữ liệu bịa hợp lý. KHÔNG chép tên khách hàng, nhân viên, số điện thoại, CCCD thật từ tài liệu. Số hợp đồng theo dạng `VYYMM####`, số chứng thư dạng `076/2026/4104`.

## Component có sẵn (dùng bằng tên)
- Khung: `App/Sidebar` (variant `Selected`: hop-dong | lich-hen | khach-hang | doi-tac | tai-san | tsss | mau-dinh-gia | yeu-to | chung-thu | bieu-mau | bao-cao), `App/Topbar` (props `Title`, `Unit`, `Year`).
- Bảng: `App/Table/HeaderCell` (prop `Label`), `App/Table/Cell` (variant `Kind`: default | muted | strong; prop `Text`).
- Nút: `Molecule/Action/Button` (Variant: primary | secondary | ghost | danger; Size: sm | md | lg; State; prop `Label`). `Molecule/Action/IconButton`.
- Nhập liệu: `Molecule/Input/TextField` (State: default | focus | error | disabled; Size: md | lg; props `Label text`, `Value`, `Helper text`; boolean `Label`, `Helper`), `Molecule/Input/Select` (State; prop `Value`), `Molecule/Input/Date` (prop `Value`), `Molecule/Input/TextArea` (prop `Value`), `Molecule/Input/Checkbox` (Checked: off | on; prop `Label`), `Molecule/Input/Radio`, `Molecule/Input/Switch`, `Molecule/Input/SearchField` (prop `Value`), `Molecule/Input/Dropzone` (props `Title`, `Body`).
- Trạng thái: `Atom/Status/Badge` (Tone: neutral | success | warning | error | info; Size: sm | md; prop `Label`), `Atom/Status/Tag`, `Atom/Status/Dot`.
- Khác: `Molecule/Display/TabItem` (Selected: off | on; prop `Label`), `Molecule/Display/Pagination` (Page: 1 | 2 | 3), `Atom/Divider` (Orientation), `Molecule/Feedback/EmptyState` (props `Title`, `Body`), `Molecule/Feedback/Alert` (Tone; props `Title`, `Body`), `Atom/Feedback/Skeleton` (Variant: line | block), `Organism/Overlay/Dialog` (Tone: default | danger; props `Title`, `Body`), `Atom/Avatar`, `Atom/Icon` (variant `Name`: Search | Plus | Close | Check | ChevronDown | ChevronRight | Edit | Trash | Filter | Calendar | Info | Alert | Eye | Back | More…).
- KHÔNG sửa các component này. Nếu thiếu, ghép từ component có sẵn. Chỉ tạo component mới khi một khối lặp lại nhiều lần trong phần việc của bạn; đặt tên có tiền tố nhóm được giao (ví dụ `App/DinhGia/…`) và tạo ở page `DS · System`.

## Màu trạng thái thống nhất
| Trạng thái | Tone |
| --- | --- |
| Chưa duyệt, Chưa xác nhận, Chưa xem, Đang xem – chờ bổ sung hồ sơ, Chưa in, Chưa đóng dấu, Chưa bàn giao | warning |
| Đã duyệt, Đã xác nhận | info |
| Hoàn thành, Đã chấm đạt, Đã in, Đã đóng dấu, Đã bàn giao, Đang sử dụng | success |
| Đã chấm không đạt | error |
| Đã hủy, Không sử dụng | neutral |

## Helper (dán vào đầu mỗi lần gọi figma_write)
```js
const T = (name, characters, textStyle = "Body/Medium", fill = "$color/light/text", extra = {}) => ({ type: "TEXT", name, characters, textStyle, fill, ...extra });
const btn = (label, variant = "secondary", size = "md") => ({ type: "INSTANCE", component: "Molecule/Action/Button", variant: { Variant: variant, Size: size, State: "default" }, props: { Label: label } });
const badge = (label, tone) => ({ type: "INSTANCE", component: "Atom/Status/Badge", variant: { Tone: tone, Size: "sm" }, props: { Label: label } });
const sel = (value, w = 200) => ({ type: "INSTANCE", component: "Molecule/Input/Select", variant: { State: "default" }, props: { Value: value }, width: w });
const search = (placeholder, w = 320) => ({ type: "INSTANCE", component: "Molecule/Input/SearchField", variant: { State: "default" }, props: { Value: placeholder }, width: w });
const row = (name, children, extra = {}) => ({ type: "FRAME", name, layoutMode: "HORIZONTAL", itemSpacing: 12, counterAxisAlignItems: "CENTER", layoutSizingHorizontal: "FILL", ...extra, children });
const col = (name, children, extra = {}) => ({ type: "FRAME", name, layoutMode: "VERTICAL", itemSpacing: 16, layoutSizingHorizontal: "FILL", ...extra, children });
// Khung ứng dụng. Bỏ `height` cho màn dài (form, chi tiết).
const shell = (name, selected, title, content, height) => ({ type: "FRAME", name, width: 1440, ...(height ? { height } : {}), minHeight: 1024, layoutMode: "HORIZONTAL", itemSpacing: 0, fill: "$color/light/bg-subtle", clipsContent: true, children: [
  { type: "INSTANCE", component: "App/Sidebar", variant: { Selected: selected }, layoutSizingVertical: "FILL" },
  { type: "FRAME", name: "Main", layoutMode: "VERTICAL", itemSpacing: 0, layoutGrow: 1, ...(height ? { layoutSizingVertical: "FILL" } : {}), children: [
    { type: "INSTANCE", component: "App/Topbar", props: { Title: title }, layoutSizingHorizontal: "FILL" },
    { type: "FRAME", name: "Content", layoutMode: "VERTICAL", padding: 24, itemSpacing: 16, layoutSizingHorizontal: "FILL", ...(height ? { layoutGrow: 1 } : {}), children: content } ] } ] });
const pageHeader = (title, actions = []) => row("Page header", [T("Page title", title, "Heading/H4", "$color/light/text", { layoutGrow: 1 }), ...actions]);
// Bảng. cols: [{label, w?, kind?}] — đúng MỘT cột không có w (cột đó giãn). Vùng nội dung rộng 1152px.
// Giá trị ô: chuỗi, hoặc { badge: [nhãn, tone] }.
const cellOf = (c, v) => { const size = c.w ? { width: c.w } : { layoutGrow: 1 };
  if (v && v.badge) return { type: "FRAME", name: "Cell " + c.label, layoutMode: "HORIZONTAL", height: 48, padding: { horizontal: 12 }, itemSpacing: 0, counterAxisAlignItems: "CENTER", fill: "$color/light/surface", ...size, children: [badge(v.badge[0], v.badge[1])] };
  return { type: "INSTANCE", component: "App/Table/Cell", variant: { Kind: c.kind || "default" }, props: { Text: String(v) }, ...size }; };
const table = (cols, rows, name = "Table card") => ({ type: "FRAME", name, layoutMode: "VERTICAL", itemSpacing: 0, layoutSizingHorizontal: "FILL", fill: "$color/light/surface", stroke: "$color/light/border", strokeWeight: 1, clipsContent: true, tokens: { cornerRadius: "radius/lg" }, children: [
  { type: "FRAME", name: "Header row", layoutMode: "HORIZONTAL", itemSpacing: 0, layoutSizingHorizontal: "FILL", children: cols.map(c => ({ type: "INSTANCE", component: "App/Table/HeaderCell", props: { Label: c.label }, ...(c.w ? { width: c.w } : { layoutGrow: 1 }) })) },
  ...rows.flatMap((r, i) => [ { type: "INSTANCE", component: "Atom/Divider", variant: { Orientation: "horizontal" }, layoutSizingHorizontal: "FILL" },
    { type: "FRAME", name: "Row " + (i + 1), layoutMode: "HORIZONTAL", itemSpacing: 0, layoutSizingHorizontal: "FILL", children: cols.map((c, j) => cellOf(c, r[j])) } ]) ] });
const tableFooter = (text) => row("Table footer", [T("Count", text, "Body/Small", "$color/light/text-muted", { layoutGrow: 1 }), { type: "INSTANCE", component: "Molecule/Display/Pagination", variant: { Page: "1" } }]);
// Trường nhập. o: { req, helper, state }
const field = (label, value, o = {}) => ({ type: "INSTANCE", component: "Molecule/Input/TextField", variant: { State: o.state || "default", Size: "md" }, props: { "Label text": label + (o.req ? " *" : ""), Value: value, "Helper text": o.helper || "", Helper: !!o.helper }, layoutSizingHorizontal: "FILL" });
const ro = (label, value) => field(label, value, { state: "disabled" }); // trường chỉ đọc / tự tính
const labeled = (label, inst, req) => ({ type: "FRAME", name: "Field " + label, layoutMode: "VERTICAL", itemSpacing: 4, layoutSizingHorizontal: "FILL", children: [T("Label", label + (req ? " *" : ""), "Label/Large"), { ...inst, layoutSizingHorizontal: "FILL" }] });
const fsel = (label, value, o = {}) => labeled(label, { type: "INSTANCE", component: "Molecule/Input/Select", variant: { State: o.state || "default" }, props: { Value: value } }, o.req);
const fdate = (label, value, o = {}) => labeled(label, { type: "INSTANCE", component: "Molecule/Input/Date", variant: { State: "default" }, props: { Value: value } }, o.req);
const farea = (label, value, o = {}) => labeled(label, { type: "INSTANCE", component: "Molecule/Input/TextArea", variant: { State: o.state || "default" }, props: { Value: value } }, o.req);
const check = (label, on = false) => ({ type: "INSTANCE", component: "Molecule/Input/Checkbox", variant: { Checked: on ? "on" : "off", State: "default" }, props: { Label: label } });
const grid = (n, children) => ({ type: "FRAME", name: "Field grid", layoutMode: "GRID", gridColumnCount: n, gridColumnGap: 16, gridRowGap: 16, layoutSizingHorizontal: "FILL", children });
const card = (title, children) => ({ type: "FRAME", name: "Card " + title, layoutMode: "VERTICAL", padding: 24, itemSpacing: 16, layoutSizingHorizontal: "FILL", fill: "$color/light/surface", stroke: "$color/light/border", strokeWeight: 1, tokens: { cornerRadius: "radius/lg" }, children: [T("Card title", title, "Title/Small"), ...children] });
const tabs = (labels, selected = 0) => ({ type: "FRAME", name: "Tabs", layoutMode: "HORIZONTAL", itemSpacing: 4, layoutSizingHorizontal: "FILL", children: labels.map((l, i) => ({ type: "INSTANCE", component: "Molecule/Display/TabItem", variant: { Selected: i === selected ? "on" : "off" }, props: { Label: l } })) });
// Cặp nhãn – giá trị chỉ đọc cho màn chi tiết
const kv = (label, value) => ({ type: "FRAME", name: "KV " + label, layoutMode: "VERTICAL", itemSpacing: 4, layoutSizingHorizontal: "FILL", children: [T("Key", label, "Caption/Regular", "$color/light/text-muted"), T("Val", value, "Body/Medium")] });
// Modal: là một frame riêng (không vẽ đè lên màn hình). w thường 560 / 720 / 960.
const modal = (name, title, w, children, footer = []) => ({ type: "FRAME", name, width: w, layoutMode: "VERTICAL", itemSpacing: 0, fill: "$color/light/surface", stroke: "$color/light/border", strokeWeight: 1, effectStyle: "elevation/4", clipsContent: true, tokens: { cornerRadius: "radius/lg" }, children: [
  { type: "FRAME", name: "Modal header", layoutMode: "HORIZONTAL", padding: { horizontal: 24, vertical: 16 }, itemSpacing: 12, counterAxisAlignItems: "CENTER", layoutSizingHorizontal: "FILL", children: [T("Modal title", title, "Title/Medium", "$color/light/text", { layoutGrow: 1 })] },
  { type: "INSTANCE", component: "Atom/Divider", variant: { Orientation: "horizontal" }, layoutSizingHorizontal: "FILL" },
  { type: "FRAME", name: "Modal body", layoutMode: "VERTICAL", padding: 24, itemSpacing: 16, layoutSizingHorizontal: "FILL", children },
  { type: "INSTANCE", component: "Atom/Divider", variant: { Orientation: "horizontal" }, layoutSizingHorizontal: "FILL" },
  { type: "FRAME", name: "Modal footer", layoutMode: "HORIZONTAL", padding: { horizontal: 24, vertical: 16 }, itemSpacing: 12, primaryAxisAlignItems: "MAX", counterAxisAlignItems: "CENTER", layoutSizingHorizontal: "FILL", children: footer } ] });
```

Ví dụ màn danh sách:
```js
const s = await figma.create(shell("Hợp đồng / Danh sách / 1440", "hop-dong", "Hợp đồng", [
  pageHeader("Hợp đồng", [btn("Xuất Excel"), btn("Thêm hợp đồng", "primary")]),
  row("Toolbar", [search("Tìm số hợp đồng, khách hàng"), sel("Kỳ: 3 tháng gần nhất", 220), sel("Trạng thái: Tất cả")]),
  table(cols, rows), tableFooter("Hiển thị 1–8 trong 46 hợp đồng") ], 1024));
const id = s.id || s; const a = await figma.layoutAudit(id); return { id, issues: a.summary.issues };
```

## Lưu ý đã gặp
- Trong lưới 4 cột, giá trị của Select nên ngắn (dưới ~28 ký tự).
- `figma.create` trả về `{id, …}`. Lấy `s.id || s`.
- Bảng có nhiều hơn 8 cột thì giảm số cột, đưa thông tin phụ sang màn chi tiết.
- Trạng thái (state) của một màn: `figma.clone(id)` rồi chỉ sửa phần khác, hoặc vẽ lại bằng helper với dữ liệu khác.
- Gợi ý (styleHints) được chấp nhận, không cần sửa: "rows repeat one structure as plain frames", "Atom/Status/Badge … label is 4px from the edge", "Text uses N different text styles", "Content is only 0px from the container edge" của Table card. Mọi dòng trong `summary.issues` thì PHẢI sửa.

## Đặt tên và sắp xếp
- Tên khung: `<Phân hệ> / <Màn> / 1440`; trạng thái: `<Phân hệ> / <Màn> / 1440 / <Trạng thái>`.
- Khi vẽ xong một phân hệ, gọi MỘT lần cho phân hệ đó:
```js
await figma.arrangeScreens({ section: "Hợp đồng", groups: [ { title: "Màn hình", screens: [
  { id: listId, name: "Hợp đồng / Danh sách", states: [{ id: emptyId, name: "Trống" }], modals: [{ id: filterId, name: "Bộ lọc" }] },
  { id: formId, name: "Hợp đồng / Thêm mới", states: [{ id: errId, name: "Lỗi" }] } ] } ] });
```
- Không di chuyển, đổi tên, xóa bất cứ thứ gì không phải do bạn tạo.

## Kiểm tra trước khi báo cáo
1. `figma.layoutAudit(id)` cho từng khung: `summary.issues` phải rỗng.
2. Chụp ảnh từng phân hệ (một ảnh section, scale nhỏ) và tự nhìn lại: chữ có bị cắt, ô có tràn, có trống bất thường không.
3. Lệnh cuối: `return await figma.screenReport([<mọi id>], { lang: "vi" })`.

## Báo cáo trả về (ngắn gọn)
- Bảng: tên khung, id, loại (màn / trạng thái / modal).
- Những gì bạn TỰ ĐẶT RA vì tài liệu không có (ví dụ câu báo lỗi, cột thêm, nút thêm), ghi rõ từng mục.
- Lỗi còn lại chưa sửa được.
- Dán nguyên `card` của screenReport.
