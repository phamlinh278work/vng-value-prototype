<!-- design-kit:generated — do not edit by hand; regenerate with generate_design_md -->
<!-- dsfp:01km9wyf vars:527 text:24 paint:0 effect:5 components:58 -->

# VNG Value Design System

Extraction scope: Entire document
Current page when extracted: Roadmap
Pages discovered: Page 1, Roadmap, DS · System

## Overview
VNG Value exposes 57 component set(s), 1 standalone component(s), and 248 set variant node(s), plus 527 variables across 1 collection(s) and 32 local styles.

**Key Characteristics To Confirm:**
- Primary brand colors: see the Colors section. Confirm semantic roles from screenshots before assigning brand meaning.
- Type system: see Typography. Numeric/display roles must be inferred from text style names and actual UI usage.
- Theme model: inspect color collection modes and page usage; do not assume light/dark behavior unless variables or screens show it.
- Component reuse: components below list exact property keys where Figma exposes them.

## Extraction Coverage
- Pages scanned: 3
- Local components returned: 306/306
- Screens summarized: 18/18
- Instances inspected: 130/130
- Component anatomy depth: 2; screen evidence depth: 4
- Screen evidence: included; component usage: included

> Evidence labels: IDs, keys, properties, values, counts, and geometry are direct Figma facts. Pattern summaries are observations from the scanned nodes. Product meaning, UX intent, and breakpoint semantics remain unknown unless explicitly named or described in Figma.

## Colors
### Variable Colors
#### roadmap
- **color-canvas** (`{roadmap/color-canvas}`): Mode 1: #fcfcfd
- **color-surface** (`{roadmap/color-surface}`): Mode 1: #ffffff
- **color-ink** (`{roadmap/color-ink}`): Mode 1: #1c2024
- **color-ink-muted** (`{roadmap/color-ink-muted}`): Mode 1: #60646c
- **color-border** (`{roadmap/color-border}`): Mode 1: #e2e8f0
- **color-on-primary** (`{roadmap/color-on-primary}`): Mode 1: #ffffff
- **color-current** (`{roadmap/color-current}`): Mode 1: #2563eb
- **color-current-soft** (`{roadmap/color-current-soft}`): Mode 1: #eef4ff
- **color-current-line** (`{roadmap/color-current-line}`): Mode 1: #c7d7fe
- **color-added** (`{roadmap/color-added}`): Mode 1: #d97706
- **color-added-soft** (`{roadmap/color-added-soft}`): Mode 1: #fff6e5
- **color-added-line** (`{roadmap/color-added-line}`): Mode 1: #f8d49a
- **color-market** (`{roadmap/color-market}`): Mode 1: #16a34a
- **color-market-soft** (`{roadmap/color-market-soft}`): Mode 1: #ecfdf3
- **color-market-line** (`{roadmap/color-market-line}`): Mode 1: #a7e8c3
- **color-tag-soft** (`{roadmap/color-tag-soft}`): Mode 1: #dbe6fe
- **color-tag-ink** (`{roadmap/color-tag-ink}`): Mode 1: #1d4ed8
#### color
- **50** (`{color/primary/50}`): Mode 1: #fff3ed
- **100** (`{color/primary/100}`): Mode 1: #ffe3d7
- **200** (`{color/primary/200}`): Mode 1: #ffccb6
- **300** (`{color/primary/300}`): Mode 1: #ffb28f
- **400** (`{color/primary/400}`): Mode 1: #f69061
- **500** (`{color/primary/500}`): Mode 1: #da6c36
- **600** (`{color/primary/600}`): Mode 1: #be541a
- **700** (`{color/primary/700}`): Mode 1: #a04002
- **800** (`{color/primary/800}`): Mode 1: #823200
- **900** (`{color/primary/900}`): Mode 1: #6b2801
- **0** (`{color/neutral/0}`): Mode 1: #ffffff
- **50** (`{color/neutral/50}`): Mode 1: #fdf9f8
- **100** (`{color/neutral/100}`): Mode 1: #fcf2ee
- **200** (`{color/neutral/200}`): Mode 1: #efe5e1
- **300** (`{color/neutral/300}`): Mode 1: #dcd2ce
- **400** (`{color/neutral/400}`): Mode 1: #a89f9b
- **500** (`{color/neutral/500}`): Mode 1: #7a716e
- **600** (`{color/neutral/600}`): Mode 1: #58504d
- **700** (`{color/neutral/700}`): Mode 1: #463e3b
- **800** (`{color/neutral/800}`): Mode 1: #2b2421
- **900** (`{color/neutral/900}`): Mode 1: #1c1613
- **950** (`{color/neutral/950}`): Mode 1: #0c0a09
- **50** (`{color/success/50}`): Mode 1: #eafbec
- **100** (`{color/success/100}`): Mode 1: #d3f4d8
- **200** (`{color/success/200}`): Mode 1: #b2e9bb
- **300** (`{color/success/300}`): Mode 1: #8cdd9c
- **400** (`{color/success/400}`): Mode 1: #5ec977
- **500** (`{color/success/500}`): Mode 1: #16a34a
- **600** (`{color/success/600}`): Mode 1: #00913e
- **700** (`{color/success/700}`): Mode 1: #007631
- **800** (`{color/success/800}`): Mode 1: #005f26
- **900** (`{color/success/900}`): Mode 1: #004e1e
- **50** (`{color/warning/50}`): Mode 1: #fef4e5
- **100** (`{color/warning/100}`): Mode 1: #f9e7cc
- **200** (`{color/warning/200}`): Mode 1: #f2d5a6
- **300** (`{color/warning/300}`): Mode 1: #e9c07c
- **400** (`{color/warning/400}`): Mode 1: #d8a548
- **500** (`{color/warning/500}`): Mode 1: #c08800
- **600** (`{color/warning/600}`): Mode 1: #9d6f00
- **700** (`{color/warning/700}`): Mode 1: #805900
- **800** (`{color/warning/800}`): Mode 1: #674700
- **900** (`{color/warning/900}`): Mode 1: #553a00
- **50** (`{color/error/50}`): Mode 1: #fff2f3
- **100** (`{color/error/100}`): Mode 1: #ffe1e5
- **200** (`{color/error/200}`): Mode 1: #ffc9d0
- **300** (`{color/error/300}`): Mode 1: #ffacb9
- **400** (`{color/error/400}`): Mode 1: #ff8199
- **500** (`{color/error/500}`): Mode 1: #f74274
- **600** (`{color/error/600}`): Mode 1: #d9205d
- **700** (`{color/error/700}`): Mode 1: #b50048
- **800** (`{color/error/800}`): Mode 1: #930039
- **900** (`{color/error/900}`): Mode 1: #7a002e
- **50** (`{color/info/50}`): Mode 1: #f1f6ff
- **100** (`{color/info/100}`): Mode 1: #dfeaff
- **200** (`{color/info/200}`): Mode 1: #c6daff
- **300** (`{color/info/300}`): Mode 1: #a9c7ff
- **400** (`{color/info/400}`): Mode 1: #83adff
- **500** (`{color/info/500}`): Mode 1: #538cff
- **600** (`{color/info/600}`): Mode 1: #2563eb
- **700** (`{color/info/700}`): Mode 1: #1d55d1
- **800** (`{color/info/800}`): Mode 1: #1443ab
- **900** (`{color/info/900}`): Mode 1: #10378d
- **bg** (`{color/light/bg}`): Mode 1: #ffffff
- **bg-subtle** (`{color/light/bg-subtle}`): Mode 1: #fdf9f8
- **surface** (`{color/light/surface}`): Mode 1: #ffffff
- **surface-raised** (`{color/light/surface-raised}`): Mode 1: #ffffff
- **surface-sunken** (`{color/light/surface-sunken}`): Mode 1: #fcf2ee
- **surface-hover** (`{color/light/surface-hover}`): Mode 1: #fdf9f8
- **surface-pressed** (`{color/light/surface-pressed}`): Mode 1: #fcf2ee
- **border** (`{color/light/border}`): Mode 1: #efe5e1
- **border-strong** (`{color/light/border-strong}`): Mode 1: #7a716e
- **border-input** (`{color/light/border-input}`): Mode 1: #7a716e
- **text** (`{color/light/text}`): Mode 1: #1c1613
- **text-muted** (`{color/light/text-muted}`): Mode 1: #58504d
- **text-subtle** (`{color/light/text-subtle}`): Mode 1: #7a716e
- **text-inverse** (`{color/light/text-inverse}`): Mode 1: #ffffff
- **primary** (`{color/light/primary}`): Mode 1: #be541a
- **primary-hover** (`{color/light/primary-hover}`): Mode 1: #a04002
- **primary-pressed** (`{color/light/primary-pressed}`): Mode 1: #823200
- **primary-subtle** (`{color/light/primary-subtle}`): Mode 1: #fff3ed
- **success** (`{color/light/success}`): Mode 1: #00913e
- **success-subtle** (`{color/light/success-subtle}`): Mode 1: #eafbec
- **warning** (`{color/light/warning}`): Mode 1: #c08800
- **warning-subtle** (`{color/light/warning-subtle}`): Mode 1: #fef4e5
- **error** (`{color/light/error}`): Mode 1: #d9205d
- **error-hover** (`{color/light/error-hover}`): Mode 1: #b50048
- **error-pressed** (`{color/light/error-pressed}`): Mode 1: #930039
- **error-subtle** (`{color/light/error-subtle}`): Mode 1: #fff2f3
- **info** (`{color/light/info}`): Mode 1: #2563eb
- **info-subtle** (`{color/light/info-subtle}`): Mode 1: #f1f6ff
- **secondary** (`{color/light/secondary}`): Mode 1: #be541a
- **secondary-subtle** (`{color/light/secondary-subtle}`): Mode 1: #fff3ed
- **accent** (`{color/light/accent}`): Mode 1: #be541a
- **accent-subtle** (`{color/light/accent-subtle}`): Mode 1: #fff3ed
- **focus** (`{color/light/focus}`): Mode 1: #da6c36
- **overlay** (`{color/light/overlay}`): Mode 1: #1c1613
- **on-primary** (`{color/light/on-primary}`): Mode 1: #ffffff
- **on-success** (`{color/light/on-success}`): Mode 1: #0c0a09
- **on-warning** (`{color/light/on-warning}`): Mode 1: #0c0a09
- **on-error** (`{color/light/on-error}`): Mode 1: #ffffff
- **on-info** (`{color/light/on-info}`): Mode 1: #ffffff
- **on-secondary** (`{color/light/on-secondary}`): Mode 1: #ffffff
- **on-accent** (`{color/light/on-accent}`): Mode 1: #ffffff
- **primary-ink** (`{color/light/primary-ink}`): Mode 1: #a04002
- **success-ink** (`{color/light/success-ink}`): Mode 1: #007631
- **warning-ink** (`{color/light/warning-ink}`): Mode 1: #805900
- **error-ink** (`{color/light/error-ink}`): Mode 1: #b50048
- **info-ink** (`{color/light/info-ink}`): Mode 1: #2563eb
- **secondary-ink** (`{color/light/secondary-ink}`): Mode 1: #a04002
- **accent-ink** (`{color/light/accent-ink}`): Mode 1: #a04002
- **50** (`{color/primary-alpha/50}`): Mode 1: #ff550012
- **100** (`{color/primary-alpha/100}`): Mode 1: #ff4c0028
- **200** (`{color/primary-alpha/200}`): Mode 1: #ff4d0049
- **300** (`{color/primary-alpha/300}`): Mode 1: #ff500070
- **400** (`{color/primary-alpha/400}`): Mode 1: #f04c009e
- **500** (`{color/primary-alpha/500}`): Mode 1: #d04500c9
- **600** (`{color/primary-alpha/600}`): Mode 1: #b74100e5
- **700** (`{color/primary-alpha/700}`): Mode 1: #9f3e00fd
- **800** (`{color/primary-alpha/800}`): Mode 1: #823200
- **900** (`{color/primary-alpha/900}`): Mode 1: #6a2700fe
- **50** (`{color/neutral-alpha/50}`): Mode 1: #b6240007
- **100** (`{color/neutral-alpha/100}`): Mode 1: #d23c0011
- **200** (`{color/neutral-alpha/200}`): Mode 1: #7722001e
- **300** (`{color/neutral-alpha/300}`): Mode 1: #49150031
- **400** (`{color/neutral-alpha/400}`): Mode 1: #210a0064
- **500** (`{color/neutral-alpha/500}`): Mode 1: #15050091
- **600** (`{color/neutral-alpha/600}`): Mode 1: #100400b2
- **700** (`{color/neutral-alpha/700}`): Mode 1: #0e0400c4
- **800** (`{color/neutral-alpha/800}`): Mode 1: #0b0300de
- **900** (`{color/neutral-alpha/900}`): Mode 1: #0a0300ec
- **950** (`{color/neutral-alpha/950}`): Mode 1: #030100f6
- **black-5** (`{color/scrim/black-5}`): Mode 1: #0000000d
- **white-5** (`{color/scrim/white-5}`): Mode 1: #ffffff0d
- **black-10** (`{color/scrim/black-10}`): Mode 1: #0000001a
- **white-10** (`{color/scrim/white-10}`): Mode 1: #ffffff1a
- **black-20** (`{color/scrim/black-20}`): Mode 1: #00000033
- **white-20** (`{color/scrim/white-20}`): Mode 1: #ffffff33
- **black-40** (`{color/scrim/black-40}`): Mode 1: #00000066
- **white-40** (`{color/scrim/white-40}`): Mode 1: #ffffff66
- **black-60** (`{color/scrim/black-60}`): Mode 1: #00000099
- **white-60** (`{color/scrim/white-60}`): Mode 1: #ffffff99
- **black-80** (`{color/scrim/black-80}`): Mode 1: #000000cc
- **white-80** (`{color/scrim/white-80}`): Mode 1: #ffffffcc
- **50** (`{color/palette/tomato/50}`): Mode 1: #fff2ef
- **100** (`{color/palette/tomato/100}`): Mode 1: #ffe3dc
- **200** (`{color/palette/tomato/200}`): Mode 1: #ffcbbf
- **300** (`{color/palette/tomato/300}`): Mode 1: #ffb09e
- **400** (`{color/palette/tomato/400}`): Mode 1: #ff876e
- **500** (`{color/palette/tomato/500}`): Mode 1: #e54d2e
- **600** (`{color/palette/tomato/600}`): Mode 1: #d13b1b
- **700** (`{color/palette/tomato/700}`): Mode 1: #b02604
- **800** (`{color/palette/tomato/800}`): Mode 1: #901b00
- **900** (`{color/palette/tomato/900}`): Mode 1: #771602
- **50** (`{color/palette/red/50}`): Mode 1: #fff2f1
- **100** (`{color/palette/red/100}`): Mode 1: #ffe2e0
- **200** (`{color/palette/red/200}`): Mode 1: #ffcac7
- **300** (`{color/palette/red/300}`): Mode 1: #ffaeaa
- **400** (`{color/palette/red/400}`): Mode 1: #ff8581
- **500** (`{color/palette/red/500}`): Mode 1: #e5484d
- **600** (`{color/palette/red/600}`): Mode 1: #d1363e
- **700** (`{color/palette/red/700}`): Mode 1: #b0212d
- **800** (`{color/palette/red/800}`): Mode 1: #901722
- **900** (`{color/palette/red/900}`): Mode 1: #77131b
- **50** (`{color/palette/ruby/50}`): Mode 1: #fff2f3
- **100** (`{color/palette/ruby/100}`): Mode 1: #ffe2e3
- **200** (`{color/palette/ruby/200}`): Mode 1: #ffc9cd
- **300** (`{color/palette/ruby/300}`): Mode 1: #ffadb5
- **400** (`{color/palette/ruby/400}`): Mode 1: #ff8293
- **500** (`{color/palette/ruby/500}`): Mode 1: #e54666
- **600** (`{color/palette/ruby/600}`): Mode 1: #d03357
- **700** (`{color/palette/ruby/700}`): Mode 1: #af1d43
- **800** (`{color/palette/ruby/800}`): Mode 1: #8f1435
- **900** (`{color/palette/ruby/900}`): Mode 1: #76102b
- **50** (`{color/palette/crimson/50}`): Mode 1: #fff1f5
- **100** (`{color/palette/crimson/100}`): Mode 1: #ffe1e8
- **200** (`{color/palette/crimson/200}`): Mode 1: #ffc8d6
- **300** (`{color/palette/crimson/300}`): Mode 1: #ffaac2
- **400** (`{color/palette/crimson/400}`): Mode 1: #ff7ea8
- **500** (`{color/palette/crimson/500}`): Mode 1: #e93d82
- **600** (`{color/palette/crimson/600}`): Mode 1: #d22570
- **700** (`{color/palette/crimson/700}`): Mode 1: #b1085a
- **800** (`{color/palette/crimson/800}`): Mode 1: #900248
- **900** (`{color/palette/crimson/900}`): Mode 1: #77043b
- **50** (`{color/palette/pink/50}`): Mode 1: #fff1f8
- **100** (`{color/palette/pink/100}`): Mode 1: #ffe0ef
- **200** (`{color/palette/pink/200}`): Mode 1: #ffc6e4
- **300** (`{color/palette/pink/300}`): Mode 1: #ffa7d7
- **400** (`{color/palette/pink/400}`): Mode 1: #ff77c7
- **500** (`{color/palette/pink/500}`): Mode 1: #d6409f
- **600** (`{color/palette/pink/600}`): Mode 1: #c63191
- **700** (`{color/palette/pink/700}`): Mode 1: #a61b78
- **800** (`{color/palette/pink/800}`): Mode 1: #871261
- **900** (`{color/palette/pink/900}`): Mode 1: #700f50
- **50** (`{color/palette/plum/50}`): Mode 1: #fdf1ff
- **100** (`{color/palette/plum/100}`): Mode 1: #fbdfff
- **200** (`{color/palette/plum/200}`): Mode 1: #f7c5ff
- **300** (`{color/palette/plum/300}`): Mode 1: #f0a9fa
- **400** (`{color/palette/plum/400}`): Mode 1: #e086ee
- **500** (`{color/palette/plum/500}`): Mode 1: #c562d5
- **600** (`{color/palette/plum/600}`): Mode 1: #ab4aba
- **700** (`{color/palette/plum/700}`): Mode 1: #8d349b
- **800** (`{color/palette/plum/800}`): Mode 1: #72287e
- **900** (`{color/palette/plum/900}`): Mode 1: #5e2068
- **50** (`{color/palette/purple/50}`): Mode 1: #f8f3ff
- **100** (`{color/palette/purple/100}`): Mode 1: #f0e4ff
- **200** (`{color/palette/purple/200}`): Mode 1: #e4ceff
- **300** (`{color/palette/purple/300}`): Mode 1: #d8b5ff
- **400** (`{color/palette/purple/400}`): Mode 1: #c891ff
- **500** (`{color/palette/purple/500}`): Mode 1: #ae6ee9
- **600** (`{color/palette/purple/600}`): Mode 1: #8e4ec6
- **700** (`{color/palette/purple/700}`): Mode 1: #7a3fac
- **800** (`{color/palette/purple/800}`): Mode 1: #62318d
- **900** (`{color/palette/purple/900}`): Mode 1: #512874
- **50** (`{color/palette/violet/50}`): Mode 1: #f5f4ff
- **100** (`{color/palette/violet/100}`): Mode 1: #e8e7ff
- **200** (`{color/palette/violet/200}`): Mode 1: #d6d4ff
- **300** (`{color/palette/violet/300}`): Mode 1: #c3beff
- **400** (`{color/palette/violet/400}`): Mode 1: #aba0ff
- **500** (`{color/palette/violet/500}`): Mode 1: #8f7af8
- **600** (`{color/palette/violet/600}`): Mode 1: #6e56cf
- **700** (`{color/palette/violet/700}`): Mode 1: #614ab9
- **800** (`{color/palette/violet/800}`): Mode 1: #4d3b97
- **900** (`{color/palette/violet/900}`): Mode 1: #3f307d
- **50** (`{color/palette/iris/50}`): Mode 1: #f3f5ff
- **100** (`{color/palette/iris/100}`): Mode 1: #e5e8ff
- **200** (`{color/palette/iris/200}`): Mode 1: #d0d6ff
- **300** (`{color/palette/iris/300}`): Mode 1: #b9c2ff
- **400** (`{color/palette/iris/400}`): Mode 1: #9ca5ff
- **500** (`{color/palette/iris/500}`): Mode 1: #7b80ff
- **600** (`{color/palette/iris/600}`): Mode 1: #5b5bd6
- **700** (`{color/palette/iris/700}`): Mode 1: #504fbf
- **800** (`{color/palette/iris/800}`): Mode 1: #3f3f9d
- **900** (`{color/palette/iris/900}`): Mode 1: #343381
- **50** (`{color/palette/indigo/50}`): Mode 1: #f1f5ff
- **100** (`{color/palette/indigo/100}`): Mode 1: #e1eaff
- **200** (`{color/palette/indigo/200}`): Mode 1: #c9d9ff
- **300** (`{color/palette/indigo/300}`): Mode 1: #aec6ff
- **400** (`{color/palette/indigo/400}`): Mode 1: #8aabff
- **500** (`{color/palette/indigo/500}`): Mode 1: #6089ff
- **600** (`{color/palette/indigo/600}`): Mode 1: #3e63dd
- **700** (`{color/palette/indigo/700}`): Mode 1: #3456c5
- **800** (`{color/palette/indigo/800}`): Mode 1: #2844a1
- **900** (`{color/palette/indigo/900}`): Mode 1: #213885
- **50** (`{color/palette/blue/50}`): Mode 1: #eff6ff
- **100** (`{color/palette/blue/100}`): Mode 1: #dbecff
- **200** (`{color/palette/blue/200}`): Mode 1: #bedcff
- **300** (`{color/palette/blue/300}`): Mode 1: #9dcbff
- **400** (`{color/palette/blue/400}`): Mode 1: #6db3ff
- **500** (`{color/palette/blue/500}`): Mode 1: #0090ff
- **600** (`{color/palette/blue/600}`): Mode 1: #0079d8
- **700** (`{color/palette/blue/700}`): Mode 1: #0062b1
- **800** (`{color/palette/blue/800}`): Mode 1: #004f90
- **900** (`{color/palette/blue/900}`): Mode 1: #004078
- **50** (`{color/palette/cyan/50}`): Mode 1: #e8f9ff
- **100** (`{color/palette/cyan/100}`): Mode 1: #d0f0fc
- **200** (`{color/palette/cyan/200}`): Mode 1: #ade3f6
- **300** (`{color/palette/cyan/300}`): Mode 1: #85d4ef
- **400** (`{color/palette/cyan/400}`): Mode 1: #51bee0
- **500** (`{color/palette/cyan/500}`): Mode 1: #00a2c7
- **600** (`{color/palette/cyan/600}`): Mode 1: #0085a4
- **700** (`{color/palette/cyan/700}`): Mode 1: #006d86
- **800** (`{color/palette/cyan/800}`): Mode 1: #00576c
- **900** (`{color/palette/cyan/900}`): Mode 1: #00485a
- **50** (`{color/palette/teal/50}`): Mode 1: #e9faf6
- **100** (`{color/palette/teal/100}`): Mode 1: #d2f2eb
- **200** (`{color/palette/teal/200}`): Mode 1: #b0e6dc
- **300** (`{color/palette/teal/300}`): Mode 1: #89d8ca
- **400** (`{color/palette/teal/400}`): Mode 1: #58c4b3
- **500** (`{color/palette/teal/500}`): Mode 1: #12a594
- **600** (`{color/palette/teal/600}`): Mode 1: #008c7d
- **700** (`{color/palette/teal/700}`): Mode 1: #007265
- **800** (`{color/palette/teal/800}`): Mode 1: #005b51
- **900** (`{color/palette/teal/900}`): Mode 1: #004b43
- **50** (`{color/palette/jade/50}`): Mode 1: #eafaf4
- **100** (`{color/palette/jade/100}`): Mode 1: #d4f2e7
- **200** (`{color/palette/jade/200}`): Mode 1: #b4e6d4
- **300** (`{color/palette/jade/300}`): Mode 1: #8fd8bf
- **400** (`{color/palette/jade/400}`): Mode 1: #62c4a5
- **500** (`{color/palette/jade/500}`): Mode 1: #29a383
- **600** (`{color/palette/jade/600}`): Mode 1: #008d6f
- **700** (`{color/palette/jade/700}`): Mode 1: #00735a
- **800** (`{color/palette/jade/800}`): Mode 1: #005c48
- **900** (`{color/palette/jade/900}`): Mode 1: #004c3b
- **50** (`{color/palette/green/50}`): Mode 1: #eafaf0
- **100** (`{color/palette/green/100}`): Mode 1: #d5f2e0
- **200** (`{color/palette/green/200}`): Mode 1: #b5e7c8
- **300** (`{color/palette/green/300}`): Mode 1: #91daaf
- **400** (`{color/palette/green/400}`): Mode 1: #66c591
- **500** (`{color/palette/green/500}`): Mode 1: #30a46c
- **600** (`{color/palette/green/600}`): Mode 1: #0e8f59
- **700** (`{color/palette/green/700}`): Mode 1: #007547
- **800** (`{color/palette/green/800}`): Mode 1: #005e38
- **900** (`{color/palette/green/900}`): Mode 1: #004d2d
- **50** (`{color/palette/grass/50}`): Mode 1: #ecfaed
- **100** (`{color/palette/grass/100}`): Mode 1: #d7f2d9
- **200** (`{color/palette/grass/200}`): Mode 1: #bae7be
- **300** (`{color/palette/grass/300}`): Mode 1: #98daa0
- **400** (`{color/palette/grass/400}`): Mode 1: #71c57d
- **500** (`{color/palette/grass/500}`): Mode 1: #46a758
- **600** (`{color/palette/grass/600}`): Mode 1: #2b8e41
- **700** (`{color/palette/grass/700}`): Mode 1: #16752f
- **800** (`{color/palette/grass/800}`): Mode 1: #0d5e24
- **900** (`{color/palette/grass/900}`): Mode 1: #0b4e1d
- **50** (`{color/palette/bronze/50}`): Mode 1: #faf4f1
- **100** (`{color/palette/bronze/100}`): Mode 1: #f2e7e2
- **200** (`{color/palette/bronze/200}`): Mode 1: #e7d5cd
- **300** (`{color/palette/bronze/300}`): Mode 1: #dac1b6
- **400** (`{color/palette/bronze/400}`): Mode 1: #c6a79a
- **500** (`{color/palette/bronze/500}`): Mode 1: #a18072
- **600** (`{color/palette/bronze/600}`): Mode 1: #907063
- **700** (`{color/palette/bronze/700}`): Mode 1: #775a4e
- **800** (`{color/palette/bronze/800}`): Mode 1: #60483e
- **900** (`{color/palette/bronze/900}`): Mode 1: #4f3b32
- **50** (`{color/palette/gold/50}`): Mode 1: #f8f5f0
- **100** (`{color/palette/gold/100}`): Mode 1: #efe9df
- **200** (`{color/palette/gold/200}`): Mode 1: #e2d7c8
- **300** (`{color/palette/gold/300}`): Mode 1: #d4c4ae
- **400** (`{color/palette/gold/400}`): Mode 1: #beac90
- **500** (`{color/palette/gold/500}`): Mode 1: #978365
- **600** (`{color/palette/gold/600}`): Mode 1: #887558
- **700** (`{color/palette/gold/700}`): Mode 1: #705f44
- **800** (`{color/palette/gold/800}`): Mode 1: #5a4c36
- **900** (`{color/palette/gold/900}`): Mode 1: #4a3e2c
- **50** (`{color/palette/brown/50}`): Mode 1: #fcf4ed
- **100** (`{color/palette/brown/100}`): Mode 1: #f6e7da
- **200** (`{color/palette/brown/200}`): Mode 1: #edd4c0
- **300** (`{color/palette/brown/300}`): Mode 1: #e2bfa3
- **400** (`{color/palette/brown/400}`): Mode 1: #d0a581
- **500** (`{color/palette/brown/500}`): Mode 1: #ad7f58
- **600** (`{color/palette/brown/600}`): Mode 1: #9a6d47
- **700** (`{color/palette/brown/700}`): Mode 1: #7f5835
- **800** (`{color/palette/brown/800}`): Mode 1: #674629
- **900** (`{color/palette/brown/900}`): Mode 1: #553921
- **50** (`{color/palette/orange/50}`): Mode 1: #fff3ed
- **100** (`{color/palette/orange/100}`): Mode 1: #ffe3d7
- **200** (`{color/palette/orange/200}`): Mode 1: #ffccb6
- **300** (`{color/palette/orange/300}`): Mode 1: #ffb28f
- **400** (`{color/palette/orange/400}`): Mode 1: #ff8a52
- **500** (`{color/palette/orange/500}`): Mode 1: #f76b15
- **600** (`{color/palette/orange/600}`): Mode 1: #c35000
- **700** (`{color/palette/orange/700}`): Mode 1: #9f4000
- **800** (`{color/palette/orange/800}`): Mode 1: #813200
- **900** (`{color/palette/orange/900}`): Mode 1: #6b2800
- **50** (`{color/palette/amber/50}`): Mode 1: #fff4df
- **100** (`{color/palette/amber/100}`): Mode 1: #ffe7b8
- **200** (`{color/palette/amber/200}`): Mode 1: #fcd381
- **300** (`{color/palette/amber/300}`): Mode 1: #ffc53d
- **400** (`{color/palette/amber/400}`): Mode 1: #dca400
- **500** (`{color/palette/amber/500}`): Mode 1: #b88900
- **600** (`{color/palette/amber/600}`): Mode 1: #997100
- **700** (`{color/palette/amber/700}`): Mode 1: #7c5c00
- **800** (`{color/palette/amber/800}`): Mode 1: #644900
- **900** (`{color/palette/amber/900}`): Mode 1: #533c00
- **50** (`{color/palette/yellow/50}`): Mode 1: #fff8c3
- **100** (`{color/palette/yellow/100}`): Mode 1: #ffe629
- **200** (`{color/palette/yellow/200}`): Mode 1: #f4db00
- **300** (`{color/palette/yellow/300}`): Mode 1: #e0c800
- **400** (`{color/palette/yellow/400}`): Mode 1: #c5b000
- **500** (`{color/palette/yellow/500}`): Mode 1: #a49300
- **600** (`{color/palette/yellow/600}`): Mode 1: #887900
- **700** (`{color/palette/yellow/700}`): Mode 1: #6f6200
- **800** (`{color/palette/yellow/800}`): Mode 1: #594f00
- **900** (`{color/palette/yellow/900}`): Mode 1: #494100
- **50** (`{color/palette/lime/50}`): Mode 1: #ecfdd4
- **100** (`{color/palette/lime/100}`): Mode 1: #d8f7aa
- **200** (`{color/palette/lime/200}`): Mode 1: #bdee63
- **300** (`{color/palette/lime/300}`): Mode 1: #a4dd00
- **400** (`{color/palette/lime/400}`): Mode 1: #90c300
- **500** (`{color/palette/lime/500}`): Mode 1: #78a200
- **600** (`{color/palette/lime/600}`): Mode 1: #638600
- **700** (`{color/palette/lime/700}`): Mode 1: #506d00
- **800** (`{color/palette/lime/800}`): Mode 1: #3f5800
- **900** (`{color/palette/lime/900}`): Mode 1: #334800
- **50** (`{color/palette/mint/50}`): Mode 1: #e0fdf5
- **100** (`{color/palette/mint/100}`): Mode 1: #c0f8ea
- **200** (`{color/palette/mint/200}`): Mode 1: #86ead4
- **300** (`{color/palette/mint/300}`): Mode 1: #36e4c7
- **400** (`{color/palette/mint/400}`): Mode 1: #00caae
- **500** (`{color/palette/mint/500}`): Mode 1: #00a992
- **600** (`{color/palette/mint/600}`): Mode 1: #008c78
- **700** (`{color/palette/mint/700}`): Mode 1: #007261
- **800** (`{color/palette/mint/800}`): Mode 1: #005c4e
- **900** (`{color/palette/mint/900}`): Mode 1: #004b40
- **50** (`{color/palette/sky/50}`): Mode 1: #e7f9ff
- **100** (`{color/palette/sky/100}`): Mode 1: #c8f2ff
- **200** (`{color/palette/sky/200}`): Mode 1: #7ce2fe
- **300** (`{color/palette/sky/300}`): Mode 1: #45dbff
- **400** (`{color/palette/sky/400}`): Mode 1: #00c2e7
- **500** (`{color/palette/sky/500}`): Mode 1: #00a2c1
- **600** (`{color/palette/sky/600}`): Mode 1: #0086a0
- **700** (`{color/palette/sky/700}`): Mode 1: #006d83
- **800** (`{color/palette/sky/800}`): Mode 1: #00586a
- **900** (`{color/palette/sky/900}`): Mode 1: #004857
- **50** (`{color/palette/gray/50}`): Mode 1: #f5f5f5
- **100** (`{color/palette/gray/100}`): Mode 1: #eaeaea
- **200** (`{color/palette/gray/200}`): Mode 1: #d9d9d9
- **300** (`{color/palette/gray/300}`): Mode 1: #c6c6c6
- **400** (`{color/palette/gray/400}`): Mode 1: #aeaeae
- **500** (`{color/palette/gray/500}`): Mode 1: #8d8d8d
- **600** (`{color/palette/gray/600}`): Mode 1: #787878
- **700** (`{color/palette/gray/700}`): Mode 1: #616161
- **800** (`{color/palette/gray/800}`): Mode 1: #4e4e4e
- **900** (`{color/palette/gray/900}`): Mode 1: #404040
- **50** (`{color/palette/mauve/50}`): Mode 1: #f5f5f7
- **100** (`{color/palette/mauve/100}`): Mode 1: #eae9ed
- **200** (`{color/palette/mauve/200}`): Mode 1: #d9d8df
- **300** (`{color/palette/mauve/300}`): Mode 1: #c7c5cf
- **400** (`{color/palette/mauve/400}`): Mode 1: #afadb9
- **500** (`{color/palette/mauve/500}`): Mode 1: #8e8c99
- **600** (`{color/palette/mauve/600}`): Mode 1: #787683
- **700** (`{color/palette/mauve/700}`): Mode 1: #62606b
- **800** (`{color/palette/mauve/800}`): Mode 1: #4e4d56
- **900** (`{color/palette/mauve/900}`): Mode 1: #403f47
- **50** (`{color/palette/slate/50}`): Mode 1: #f5f5f7
- **100** (`{color/palette/slate/100}`): Mode 1: #e9e9ed
- **200** (`{color/palette/slate/200}`): Mode 1: #d7d9df
- **300** (`{color/palette/slate/300}`): Mode 1: #c5c6ce
- **400** (`{color/palette/slate/400}`): Mode 1: #acaeb8
- **500** (`{color/palette/slate/500}`): Mode 1: #8b8d98
- **600** (`{color/palette/slate/600}`): Mode 1: #767882
- **700** (`{color/palette/slate/700}`): Mode 1: #5f616a
- **800** (`{color/palette/slate/800}`): Mode 1: #4c4e56
- **900** (`{color/palette/slate/900}`): Mode 1: #3e4046
- **50** (`{color/palette/sage/50}`): Mode 1: #f4f6f5
- **100** (`{color/palette/sage/100}`): Mode 1: #e8eae9
- **200** (`{color/palette/sage/200}`): Mode 1: #d6dad9
- **300** (`{color/palette/sage/300}`): Mode 1: #c2c8c6
- **400** (`{color/palette/sage/400}`): Mode 1: #a9b0ae
- **500** (`{color/palette/sage/500}`): Mode 1: #868e8b
- **600** (`{color/palette/sage/600}`): Mode 1: #737a77
- **700** (`{color/palette/sage/700}`): Mode 1: #5c6361
- **800** (`{color/palette/sage/800}`): Mode 1: #4a504d
- **900** (`{color/palette/sage/900}`): Mode 1: #3c413f
- **50** (`{color/palette/olive/50}`): Mode 1: #f5f6f4
- **100** (`{color/palette/olive/100}`): Mode 1: #e9eae8
- **200** (`{color/palette/olive/200}`): Mode 1: #d7dad6
- **300** (`{color/palette/olive/300}`): Mode 1: #c4c8c3
- **400** (`{color/palette/olive/400}`): Mode 1: #abb0aa
- **500** (`{color/palette/olive/500}`): Mode 1: #898e87
- **600** (`{color/palette/olive/600}`): Mode 1: #757a73
- **700** (`{color/palette/olive/700}`): Mode 1: #5f635d
- **800** (`{color/palette/olive/800}`): Mode 1: #4c4f4a
- **900** (`{color/palette/olive/900}`): Mode 1: #3e413d
- **50** (`{color/palette/sand/50}`): Mode 1: #f5f5f4
- **100** (`{color/palette/sand/100}`): Mode 1: #eaeae8
- **200** (`{color/palette/sand/200}`): Mode 1: #d9d9d5
- **300** (`{color/palette/sand/300}`): Mode 1: #c7c7c2
- **400** (`{color/palette/sand/400}`): Mode 1: #afafa8
- **500** (`{color/palette/sand/500}`): Mode 1: #8d8d86
- **600** (`{color/palette/sand/600}`): Mode 1: #797972
- **700** (`{color/palette/sand/700}`): Mode 1: #62625c
- **800** (`{color/palette/sand/800}`): Mode 1: #4e4e49
- **900** (`{color/palette/sand/900}`): Mode 1: #40403c

## Typography
| Token | Family | Style | Size | Line Height | Letter Spacing | Use |
|---|---|---:|---:|---:|---:|---|
| `{typography.title}` | Inter | Bold | 32 | {"unit":"PIXELS","value":38} | {"unit":"PERCENT","value":-1} | Section headings |
| `{typography.subheading}` | Inter | Semi Bold | 20 | {"unit":"PIXELS","value":28} | {"unit":"PERCENT","value":0} | Section headings |
| `{typography.label}` | Inter | Medium | 14 | {"unit":"PIXELS","value":20} | {"unit":"PERCENT","value":0} | Labels and metadata |
| `{typography.caption}` | Inter | Semi Bold | 12 | {"unit":"PIXELS","value":16} | {"unit":"PERCENT","value":0} | Labels and metadata |
| `{typography.display.large}` | IBM Plex Sans | Bold | 56 | {"unit":"PIXELS","value":64} | {"unit":"PIXELS","value":-1.5} | 56/64 · 700 |
| `{typography.display.medium}` | IBM Plex Sans | Bold | 48 | {"unit":"PIXELS","value":56} | {"unit":"PIXELS","value":-1} | 48/56 · 700 |
| `{typography.display.small}` | IBM Plex Sans | Bold | 40 | {"unit":"PIXELS","value":48} | {"unit":"PIXELS","value":-0.5} | 40/48 · 700 |
| `{typography.heading.h1}` | IBM Plex Sans | Bold | 32 | {"unit":"PIXELS","value":40} | {"unit":"PIXELS","value":-0.5} | 32/40 · 700 |
| `{typography.heading.h2}` | IBM Plex Sans | SemiBold | 28 | {"unit":"PIXELS","value":36} | {"unit":"PIXELS","value":-0.25} | 28/36 · 600 |
| `{typography.heading.h3}` | IBM Plex Sans | SemiBold | 24 | {"unit":"PIXELS","value":32} | {"unit":"PIXELS","value":0} | 24/32 · 600 |
| `{typography.heading.h4}` | IBM Plex Sans | SemiBold | 20 | {"unit":"PIXELS","value":28} | {"unit":"PIXELS","value":0} | 20/28 · 600 |
| `{typography.heading.h5}` | IBM Plex Sans | SemiBold | 18 | {"unit":"PIXELS","value":24} | {"unit":"PIXELS","value":0} | 18/24 · 600 |
| `{typography.heading.h6}` | IBM Plex Sans | SemiBold | 16 | {"unit":"PIXELS","value":24} | {"unit":"PIXELS","value":0} | 16/24 · 600 |
| `{typography.title.large}` | IBM Plex Sans | Medium | 20 | {"unit":"PIXELS","value":28} | {"unit":"PIXELS","value":0} | 20/28 · 500 |
| `{typography.title.medium}` | IBM Plex Sans | Medium | 18 | {"unit":"PIXELS","value":24} | {"unit":"PIXELS","value":0} | 18/24 · 500 |
| `{typography.title.small}` | IBM Plex Sans | Medium | 16 | {"unit":"PIXELS","value":24} | {"unit":"PIXELS","value":0} | 16/24 · 500 |
| `{typography.body.large}` | IBM Plex Sans | Regular | 16 | {"unit":"PIXELS","value":24} | {"unit":"PIXELS","value":0} | 16/24 · 400 |
| `{typography.body.medium}` | IBM Plex Sans | Regular | 14 | {"unit":"PIXELS","value":20} | {"unit":"PIXELS","value":0} | 14/20 · 400 |
| `{typography.body.small}` | IBM Plex Sans | Regular | 12 | {"unit":"PIXELS","value":16} | {"unit":"PIXELS","value":0.10000000149011612} | 12/16 · 400 |
| `{typography.label.large}` | IBM Plex Sans | Medium | 14 | {"unit":"PIXELS","value":20} | {"unit":"PIXELS","value":0.10000000149011612} | 14/20 · 500 |
| `{typography.label.medium}` | IBM Plex Sans | Medium | 12 | {"unit":"PIXELS","value":16} | {"unit":"PIXELS","value":0.25} | 12/16 · 500 |
| `{typography.label.small}` | IBM Plex Sans | Medium | 10 | {"unit":"PIXELS","value":16} | {"unit":"PIXELS","value":0.5} | 10/16 · 500 |
| `{typography.caption.regular}` | IBM Plex Sans | Regular | 12 | {"unit":"PIXELS","value":16} | {"unit":"PIXELS","value":0.25} | 12/16 · 400 |
| `{typography.caption.small}` | IBM Plex Sans | Regular | 10 | {"unit":"PIXELS","value":16} | {"unit":"PIXELS","value":0.4000000059604645} | 10/16 · 400 |

### Typography Principles
- Use the named text styles above before hardcoding font values.
- If multiple number/table styles exist, reserve them for prices, counts, totals, metrics and dense tabular data.
- If a font is unavailable locally, check `get_fonts` before substituting; keep size/line-height close to the extracted style.

## Layout
### Spacing & Size Tokens
- `{spacing/2}`: Mode 1: 2
- `{spacing/4}`: Mode 1: 4
- `{spacing/8}`: Mode 1: 8
- `{spacing/12}`: Mode 1: 12
- `{spacing/16}`: Mode 1: 16
- `{spacing/20}`: Mode 1: 20
- `{spacing/24}`: Mode 1: 24
- `{spacing/32}`: Mode 1: 32
- `{spacing/40}`: Mode 1: 40
- `{spacing/48}`: Mode 1: 48
- `{spacing/64}`: Mode 1: 64
- `{spacing/80}`: Mode 1: 80
- `{spacing/96}`: Mode 1: 96
- `{size/control/sm}`: Mode 1: 32
- `{size/control/md}`: Mode 1: 44
- `{size/control/lg}`: Mode 1: 56
- `{size/icon/sm}`: Mode 1: 16
- `{size/icon/md}`: Mode 1: 20
- `{size/icon/lg}`: Mode 1: 24
### Grid Styles
- `grid/laptop`: [{"pattern":"COLUMNS","visible":true,"color":{"r":1,"g":0.20000000298023224,"b":0.20000000298023224,"a":0.10000000149011612},"gutterSize":24,"alignment":"STRETCH","count":12,"offset":32,"boundVariables":{}}]
- `grid/web`: [{"pattern":"COLUMNS","visible":true,"color":{"r":1,"g":0.20000000298023224,"b":0.20000000298023224,"a":0.10000000149011612},"gutterSize":24,"alignment":"STRETCH","count":12,"offset":32,"boundVariables":{}}]
- `grid/wide`: [{"pattern":"COLUMNS","visible":true,"color":{"r":1,"g":0.20000000298023224,"b":0.20000000298023224,"a":0.10000000149011612},"gutterSize":32,"alignment":"STRETCH","count":12,"offset":64,"boundVariables":{}}]
### Component Layout Patterns
- `Feature chip`: layoutMode=NONE, clipsContent=true
- `Version badge`: layoutMode=HORIZONTAL, itemSpacing=8, padding={"left":12,"right":12,"top":4,"bottom":4}, primaryAxisSizingMode=AUTO, counterAxisSizingMode=AUTO, primaryAxisAlignItems=MIN, counterAxisAlignItems=MIN, clipsContent=false
- `Atom/Icon`: layoutMode=NONE, clipsContent=true
- `Atom/Status/Badge`: layoutMode=NONE, clipsContent=true
- `Atom/Status/Dot`: layoutMode=NONE, clipsContent=true
- `Atom/Status/Chip`: layoutMode=NONE, clipsContent=true
- `Atom/Divider`: layoutMode=NONE, clipsContent=true
- `Atom/Avatar`: layoutMode=NONE, clipsContent=true
- `Atom/Feedback/Progress`: layoutMode=NONE, clipsContent=true
- `Atom/Feedback/Spinner`: layoutMode=NONE, clipsContent=true
- `Atom/Feedback/Skeleton`: layoutMode=NONE, clipsContent=true
- `Atom/Status/Tag`: layoutMode=NONE, clipsContent=true
- `Atom/Feedback/Tooltip`: layoutMode=NONE, clipsContent=true
- `Atom/Feedback/Kbd`: layoutMode=NONE, clipsContent=true
- `Atom/Feedback/Trend`: layoutMode=NONE, clipsContent=true
- `Molecule/Action/Button`: layoutMode=NONE, clipsContent=true
- `Molecule/Input/TextField`: layoutMode=NONE, clipsContent=true
- `Molecule/Display/Card`: layoutMode=NONE, clipsContent=true
- `Molecule/Feedback/Alert`: layoutMode=NONE, clipsContent=true
- `Molecule/Action/IconButton`: layoutMode=NONE, clipsContent=true
- `Molecule/Action/Segmented`: layoutMode=NONE, clipsContent=true
- `Molecule/Input/Checkbox`: layoutMode=NONE, clipsContent=true
- `Molecule/Input/Radio`: layoutMode=NONE, clipsContent=true
- `Molecule/Input/Switch`: layoutMode=NONE, clipsContent=true
- `Molecule/Input/SearchField`: layoutMode=NONE, clipsContent=true
- `Molecule/Input/Select`: layoutMode=NONE, clipsContent=true
- `Molecule/Input/TextArea`: layoutMode=NONE, clipsContent=true
- `Molecule/Display/ListItem`: layoutMode=NONE, clipsContent=true
- `Molecule/Display/TabItem`: layoutMode=NONE, clipsContent=true
- `Molecule/Display/StatTile`: layoutMode=NONE, clipsContent=true
- `Molecule/Feedback/Toast`: layoutMode=NONE, clipsContent=true
- `Molecule/Feedback/EmptyState`: layoutMode=NONE, clipsContent=true
- `Molecule/Input/Slider`: layoutMode=NONE, clipsContent=true
- `Molecule/Input/Stepper`: layoutMode=NONE, clipsContent=true
- `Molecule/Input/OTP`: layoutMode=NONE, clipsContent=true
- `Molecule/Display/AccordionItem`: layoutMode=NONE, clipsContent=true
- `Molecule/Display/MenuItem`: layoutMode=NONE, clipsContent=true
- `Molecule/Display/Breadcrumb`: layoutMode=NONE, clipsContent=true
- `Molecule/Display/Pagination`: layoutMode=NONE, clipsContent=true
- `Molecule/Feedback/LoadingBlock`: layoutMode=NONE, clipsContent=true
- `Molecule/Input/Date`: layoutMode=NONE, clipsContent=true
- `Molecule/Input/Combobox`: layoutMode=NONE, clipsContent=true
- `Molecule/Input/Dropzone`: layoutMode=NONE, clipsContent=true
- `Molecule/Feedback/ToastStack`: layoutMode=NONE, clipsContent=true
- `Molecule/Input/SearchFilter`: layoutMode=NONE, clipsContent=true
- `Organism/Overlay/Dialog`: layoutMode=NONE, clipsContent=true
- `Organism/Navigation/Tabs`: layoutMode=NONE, clipsContent=true
- `Organism/Page/FormSection`: layoutMode=NONE, clipsContent=true
- `Organism/Navigation/Sidebar`: layoutMode=NONE, clipsContent=true
- `Organism/Page/SettingsGroup`: layoutMode=NONE, clipsContent=true
- `Organism/Page/ListSection`: layoutMode=NONE, clipsContent=true
- `Organism/Navigation/Header`: layoutMode=NONE, clipsContent=true
- `Organism/Navigation/Footer`: layoutMode=NONE, clipsContent=true
- `Organism/Overlay/Drawer`: layoutMode=NONE, clipsContent=true
- `Organism/Page/SkeletonPage`: layoutMode=NONE, clipsContent=true
- `Organism/Page/EmptyPage`: layoutMode=NONE, clipsContent=true
- `Organism/Display/DataTable`: layoutMode=NONE, clipsContent=true
- `Organism/Overlay/CommandPalette`: layoutMode=NONE, clipsContent=true

## Observed Layout & Visual Patterns
These are frequency observations, not automatically approved design tokens:
- Screen widths: 1200px (×10), 416px (×3), 1232px (×1), 1345px (×1), 1667px (×1), 1680px (×1), 1702px (×1)
- Auto-layout gaps: 4px (×212), 8px (×95), 12px (×67), 16px (×48), 0px (×44), 32px (×14), 24px (×12), 6px (×10), 2px (×7)
- Padding values: 0px (×1436), 12px (×218), 16px (×202), 24px (×60), 64px (×40), 8px (×38), 4px (×28), 2px (×4), 40px (×4), 48px (×4), 6px (×2)
- Corner radii: 0px (×494), 4px (×163), 2px (×157), 10px (×22), 9999px (×21), 8px (×10), 16px (×9), 12px (×5), 24px (×1)
- Font sizes: 12px (×236), 10px (×230), 14px (×115), 11px (×27), 16px (×26), 20px (×10), 28px (×10), 13px (×9), 18px (×8), 24px (×5), 32px (×2), 48px (×2), 40px (×1), 56px (×1)
- Solid fills: #1c1613 (×201), #ffffff (×200), #58504d (×176), #7a716e (×175), #22242a (×65), #fff3ed (×39), #60646c (×22), #6b7280 (×21), #a04002 (×21), #be541a (×21), #fcf2ee (×13), #1c2024 (×8), #2563eb (×7), #f4f5f7 (×6), #fafbfc (×6), #00913e (×5)

## Elevation & Depth
| Style | Effects | Variables |
|---|---|---|
| `elevation/1` | [{"type":"DROP_SHADOW","visible":true,"radius":1,"boundVariables":{},"color":{"r":0.05882352963089943,"g":0.09019608050584793,"b":0.16470588743686676,"a":0.0313725508749485},"offset":{"x":0,"y":1},"spread":0,"blendMode":"NORMAL","showShadowBehindNode":true},{"type":"DROP_SHADOW","visible":true,"radius":2,"boundVariables":{},"color":{"r":0.05882352963089943,"g":0.09019608050584793,"b":0.16470588743686676,"a":0.062745101749897},"offset":{"x":0,"y":1},"spread":0,"blendMode":"NORMAL","showShadowBehindNode":true}] | - |
| `elevation/2` | [{"type":"DROP_SHADOW","visible":true,"radius":2,"boundVariables":{},"color":{"r":0.05882352963089943,"g":0.09019608050584793,"b":0.16470588743686676,"a":0.03529411926865578},"offset":{"x":0,"y":1},"spread":0,"blendMode":"NORMAL","showShadowBehindNode":true},{"type":"DROP_SHADOW","visible":true,"radius":4,"boundVariables":{},"color":{"r":0.05882352963089943,"g":0.09019608050584793,"b":0.16470588743686676,"a":0.062745101749897},"offset":{"x":0,"y":2},"spread":-1,"blendMode":"NORMAL","showShadowBehindNode":true}] | - |
| `elevation/3` | [{"type":"DROP_SHADOW","visible":true,"radius":2,"boundVariables":{},"color":{"r":0.05882352963089943,"g":0.09019608050584793,"b":0.16470588743686676,"a":0.03529411926865578},"offset":{"x":0,"y":1},"spread":0,"blendMode":"NORMAL","showShadowBehindNode":true},{"type":"DROP_SHADOW","visible":true,"radius":8,"boundVariables":{},"color":{"r":0.05882352963089943,"g":0.09019608050584793,"b":0.16470588743686676,"a":0.07450980693101883},"offset":{"x":0,"y":4},"spread":-2,"blendMode":"NORMAL","showShadowBehindNode":true}] | - |
| `elevation/4` | [{"type":"DROP_SHADOW","visible":true,"radius":3,"boundVariables":{},"color":{"r":0.05882352963089943,"g":0.09019608050584793,"b":0.16470588743686676,"a":0.03529411926865578},"offset":{"x":0,"y":2},"spread":-1,"blendMode":"NORMAL","showShadowBehindNode":true},{"type":"DROP_SHADOW","visible":true,"radius":12,"boundVariables":{},"color":{"r":0.05882352963089943,"g":0.09019608050584793,"b":0.16470588743686676,"a":0.08627451211214066},"offset":{"x":0,"y":6},"spread":-3,"blendMode":"NORMAL","showShadowBehindNode":true}] | - |
| `elevation/5` | [{"type":"DROP_SHADOW","visible":true,"radius":4,"boundVariables":{},"color":{"r":0.05882352963089943,"g":0.09019608050584793,"b":0.16470588743686676,"a":0.04313725605607033},"offset":{"x":0,"y":3},"spread":-1,"blendMode":"NORMAL","showShadowBehindNode":true},{"type":"DROP_SHADOW","visible":true,"radius":20,"boundVariables":{},"color":{"r":0.05882352963089943,"g":0.09019608050584793,"b":0.16470588743686676,"a":0.10980392247438431},"offset":{"x":0,"y":10},"spread":-4,"blendMode":"NORMAL","showShadowBehindNode":true}] | - |

## Shapes
### Radius Tokens
- `{roadmap/radius-sm}`: Mode 1: 8
- `{roadmap/radius-lg}`: Mode 1: 16
- `{roadmap/radius-pill}`: Mode 1: 9999
- `{radius/none}`: Mode 1: 0
- `{radius/xs}`: Mode 1: 2
- `{radius/sm}`: Mode 1: 2
- `{radius/md}`: Mode 1: 4
- `{radius/lg}`: Mode 1: 4
- `{radius/xl}`: Mode 1: 8
- `{radius/2xl}`: Mode 1: 8
- `{radius/3xl}`: Mode 1: 12
- `{radius/full}`: Mode 1: 9999
- `{radius/button}`: Mode 1: 4
### Observed Component Radii
- `Feature chip`: cornerRadius=5, topLeftRadius=5, topRightRadius=5, bottomRightRadius=5, bottomLeftRadius=5
- `Version badge`: cornerRadius=9999, topLeftRadius=9999, topRightRadius=9999, bottomRightRadius=9999, bottomLeftRadius=9999
- `Atom/Icon`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Atom/Status/Badge`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Atom/Status/Dot`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Atom/Status/Chip`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Atom/Divider`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Atom/Avatar`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Atom/Feedback/Progress`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Atom/Feedback/Spinner`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Atom/Feedback/Skeleton`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Atom/Status/Tag`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Atom/Feedback/Tooltip`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Atom/Feedback/Kbd`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Atom/Feedback/Trend`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Molecule/Action/Button`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Molecule/Input/TextField`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Molecule/Display/Card`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Molecule/Feedback/Alert`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Molecule/Action/IconButton`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Molecule/Action/Segmented`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Molecule/Input/Checkbox`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Molecule/Input/Radio`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Molecule/Input/Switch`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Molecule/Input/SearchField`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Molecule/Input/Select`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Molecule/Input/TextArea`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Molecule/Display/ListItem`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Molecule/Display/TabItem`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Molecule/Display/StatTile`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Molecule/Feedback/Toast`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Molecule/Feedback/EmptyState`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Molecule/Input/Slider`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Molecule/Input/Stepper`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Molecule/Input/OTP`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Molecule/Display/AccordionItem`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Molecule/Display/MenuItem`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Molecule/Display/Breadcrumb`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Molecule/Display/Pagination`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Molecule/Feedback/LoadingBlock`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Molecule/Input/Date`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Molecule/Input/Combobox`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Molecule/Input/Dropzone`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Molecule/Feedback/ToastStack`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Molecule/Input/SearchFilter`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Organism/Overlay/Dialog`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Organism/Navigation/Tabs`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Organism/Page/FormSection`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Organism/Navigation/Sidebar`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Organism/Page/SettingsGroup`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Organism/Page/ListSection`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Organism/Navigation/Header`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Organism/Navigation/Footer`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Organism/Overlay/Drawer`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Organism/Page/SkeletonPage`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Organism/Page/EmptyPage`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Organism/Display/DataTable`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- `Organism/Overlay/CommandPalette`: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4

## Agent Rules
- Reuse listed components before drawing equivalent new UI.
- Use component properties and variants when available; use layer overrides only as a fallback.
- Use variables/styles by name instead of hardcoded values when a matching token exists.
- Treat node IDs as bindings to this exact Figma file. After duplicating/migrating a file, resolve by component key/name and refresh IDs before writing.
- Treat frequency observations as candidates, not semantic tokens, unless a matching Figma variable/style or explicit description confirms them.
- After creating or modifying UI, run `layout_audit` on the changed frame.
- Treat this file as source-grounded. Fill narrative gaps only after reading screenshots, selected nodes, or additional Figma pages.

## Variables
### Reqwise Tokens (Mode 1)
- `roadmap/color-canvas` (COLOR) = Mode 1: #fcfcfd
- `roadmap/color-surface` (COLOR) = Mode 1: #ffffff
- `roadmap/color-ink` (COLOR) = Mode 1: #1c2024
- `roadmap/color-ink-muted` (COLOR) = Mode 1: #60646c
- `roadmap/color-border` (COLOR) = Mode 1: #e2e8f0
- `roadmap/color-on-primary` (COLOR) = Mode 1: #ffffff
- `roadmap/color-current` (COLOR) = Mode 1: #2563eb
- `roadmap/color-current-soft` (COLOR) = Mode 1: #eef4ff
- `roadmap/color-current-line` (COLOR) = Mode 1: #c7d7fe
- `roadmap/color-added` (COLOR) = Mode 1: #d97706
- `roadmap/color-added-soft` (COLOR) = Mode 1: #fff6e5
- `roadmap/color-added-line` (COLOR) = Mode 1: #f8d49a
- `roadmap/color-market` (COLOR) = Mode 1: #16a34a
- `roadmap/color-market-soft` (COLOR) = Mode 1: #ecfdf3
- `roadmap/color-market-line` (COLOR) = Mode 1: #a7e8c3
- `roadmap/color-tag-soft` (COLOR) = Mode 1: #dbe6fe
- `roadmap/color-tag-ink` (COLOR) = Mode 1: #1d4ed8
- `roadmap/radius-sm` (FLOAT) = Mode 1: 8
- `roadmap/radius-lg` (FLOAT) = Mode 1: 16
- `roadmap/radius-pill` (FLOAT) = Mode 1: 9999
- `color/primary/50` (COLOR) = Mode 1: #fff3ed
- `color/primary/100` (COLOR) = Mode 1: #ffe3d7
- `color/primary/200` (COLOR) = Mode 1: #ffccb6
- `color/primary/300` (COLOR) = Mode 1: #ffb28f
- `color/primary/400` (COLOR) = Mode 1: #f69061
- `color/primary/500` (COLOR) = Mode 1: #da6c36
- `color/primary/600` (COLOR) = Mode 1: #be541a
- `color/primary/700` (COLOR) = Mode 1: #a04002
- `color/primary/800` (COLOR) = Mode 1: #823200
- `color/primary/900` (COLOR) = Mode 1: #6b2801
- `color/neutral/0` (COLOR) = Mode 1: #ffffff
- `color/neutral/50` (COLOR) = Mode 1: #fdf9f8
- `color/neutral/100` (COLOR) = Mode 1: #fcf2ee
- `color/neutral/200` (COLOR) = Mode 1: #efe5e1
- `color/neutral/300` (COLOR) = Mode 1: #dcd2ce
- `color/neutral/400` (COLOR) = Mode 1: #a89f9b
- `color/neutral/500` (COLOR) = Mode 1: #7a716e
- `color/neutral/600` (COLOR) = Mode 1: #58504d
- `color/neutral/700` (COLOR) = Mode 1: #463e3b
- `color/neutral/800` (COLOR) = Mode 1: #2b2421
- `color/neutral/900` (COLOR) = Mode 1: #1c1613
- `color/neutral/950` (COLOR) = Mode 1: #0c0a09
- `color/success/50` (COLOR) = Mode 1: #eafbec
- `color/success/100` (COLOR) = Mode 1: #d3f4d8
- `color/success/200` (COLOR) = Mode 1: #b2e9bb
- `color/success/300` (COLOR) = Mode 1: #8cdd9c
- `color/success/400` (COLOR) = Mode 1: #5ec977
- `color/success/500` (COLOR) = Mode 1: #16a34a
- `color/success/600` (COLOR) = Mode 1: #00913e
- `color/success/700` (COLOR) = Mode 1: #007631
- `color/success/800` (COLOR) = Mode 1: #005f26
- `color/success/900` (COLOR) = Mode 1: #004e1e
- `color/warning/50` (COLOR) = Mode 1: #fef4e5
- `color/warning/100` (COLOR) = Mode 1: #f9e7cc
- `color/warning/200` (COLOR) = Mode 1: #f2d5a6
- `color/warning/300` (COLOR) = Mode 1: #e9c07c
- `color/warning/400` (COLOR) = Mode 1: #d8a548
- `color/warning/500` (COLOR) = Mode 1: #c08800
- `color/warning/600` (COLOR) = Mode 1: #9d6f00
- `color/warning/700` (COLOR) = Mode 1: #805900
- `color/warning/800` (COLOR) = Mode 1: #674700
- `color/warning/900` (COLOR) = Mode 1: #553a00
- `color/error/50` (COLOR) = Mode 1: #fff2f3
- `color/error/100` (COLOR) = Mode 1: #ffe1e5
- `color/error/200` (COLOR) = Mode 1: #ffc9d0
- `color/error/300` (COLOR) = Mode 1: #ffacb9
- `color/error/400` (COLOR) = Mode 1: #ff8199
- `color/error/500` (COLOR) = Mode 1: #f74274
- `color/error/600` (COLOR) = Mode 1: #d9205d
- `color/error/700` (COLOR) = Mode 1: #b50048
- `color/error/800` (COLOR) = Mode 1: #930039
- `color/error/900` (COLOR) = Mode 1: #7a002e
- `color/info/50` (COLOR) = Mode 1: #f1f6ff
- `color/info/100` (COLOR) = Mode 1: #dfeaff
- `color/info/200` (COLOR) = Mode 1: #c6daff
- `color/info/300` (COLOR) = Mode 1: #a9c7ff
- `color/info/400` (COLOR) = Mode 1: #83adff
- `color/info/500` (COLOR) = Mode 1: #538cff
- `color/info/600` (COLOR) = Mode 1: #2563eb
- `color/info/700` (COLOR) = Mode 1: #1d55d1
- `color/info/800` (COLOR) = Mode 1: #1443ab
- `color/info/900` (COLOR) = Mode 1: #10378d
- `color/light/bg` (COLOR) = Mode 1: #ffffff
- `color/light/bg-subtle` (COLOR) = Mode 1: #fdf9f8
- `color/light/surface` (COLOR) = Mode 1: #ffffff
- `color/light/surface-raised` (COLOR) = Mode 1: #ffffff
- `color/light/surface-sunken` (COLOR) = Mode 1: #fcf2ee
- `color/light/surface-hover` (COLOR) = Mode 1: #fdf9f8
- `color/light/surface-pressed` (COLOR) = Mode 1: #fcf2ee
- `color/light/border` (COLOR) = Mode 1: #efe5e1
- `color/light/border-strong` (COLOR) = Mode 1: #7a716e
- `color/light/border-input` (COLOR) = Mode 1: #7a716e
- `color/light/text` (COLOR) = Mode 1: #1c1613
- `color/light/text-muted` (COLOR) = Mode 1: #58504d
- `color/light/text-subtle` (COLOR) = Mode 1: #7a716e
- `color/light/text-inverse` (COLOR) = Mode 1: #ffffff
- `color/light/primary` (COLOR) = Mode 1: #be541a
- `color/light/primary-hover` (COLOR) = Mode 1: #a04002
- `color/light/primary-pressed` (COLOR) = Mode 1: #823200
- `color/light/primary-subtle` (COLOR) = Mode 1: #fff3ed
- `color/light/success` (COLOR) = Mode 1: #00913e
- `color/light/success-subtle` (COLOR) = Mode 1: #eafbec
- `color/light/warning` (COLOR) = Mode 1: #c08800
- `color/light/warning-subtle` (COLOR) = Mode 1: #fef4e5
- `color/light/error` (COLOR) = Mode 1: #d9205d
- `color/light/error-hover` (COLOR) = Mode 1: #b50048
- `color/light/error-pressed` (COLOR) = Mode 1: #930039
- `color/light/error-subtle` (COLOR) = Mode 1: #fff2f3
- `color/light/info` (COLOR) = Mode 1: #2563eb
- `color/light/info-subtle` (COLOR) = Mode 1: #f1f6ff
- `color/light/secondary` (COLOR) = Mode 1: #be541a
- `color/light/secondary-subtle` (COLOR) = Mode 1: #fff3ed
- `color/light/accent` (COLOR) = Mode 1: #be541a
- `color/light/accent-subtle` (COLOR) = Mode 1: #fff3ed
- `color/light/focus` (COLOR) = Mode 1: #da6c36
- `color/light/overlay` (COLOR) = Mode 1: #1c1613
- `color/light/on-primary` (COLOR) = Mode 1: #ffffff
- `color/light/on-success` (COLOR) = Mode 1: #0c0a09
- `color/light/on-warning` (COLOR) = Mode 1: #0c0a09
- `color/light/on-error` (COLOR) = Mode 1: #ffffff
- `color/light/on-info` (COLOR) = Mode 1: #ffffff
- `color/light/on-secondary` (COLOR) = Mode 1: #ffffff
- `color/light/on-accent` (COLOR) = Mode 1: #ffffff
- `color/light/primary-ink` (COLOR) = Mode 1: #a04002
- `color/light/success-ink` (COLOR) = Mode 1: #007631
- `color/light/warning-ink` (COLOR) = Mode 1: #805900
- `color/light/error-ink` (COLOR) = Mode 1: #b50048
- `color/light/info-ink` (COLOR) = Mode 1: #2563eb
- `color/light/secondary-ink` (COLOR) = Mode 1: #a04002
- `color/light/accent-ink` (COLOR) = Mode 1: #a04002
- `color/primary-alpha/50` (COLOR) = Mode 1: #ff550012
- `color/primary-alpha/100` (COLOR) = Mode 1: #ff4c0028
- `color/primary-alpha/200` (COLOR) = Mode 1: #ff4d0049
- `color/primary-alpha/300` (COLOR) = Mode 1: #ff500070
- `color/primary-alpha/400` (COLOR) = Mode 1: #f04c009e
- `color/primary-alpha/500` (COLOR) = Mode 1: #d04500c9
- `color/primary-alpha/600` (COLOR) = Mode 1: #b74100e5
- `color/primary-alpha/700` (COLOR) = Mode 1: #9f3e00fd
- `color/primary-alpha/800` (COLOR) = Mode 1: #823200
- `color/primary-alpha/900` (COLOR) = Mode 1: #6a2700fe
- `color/neutral-alpha/50` (COLOR) = Mode 1: #b6240007
- `color/neutral-alpha/100` (COLOR) = Mode 1: #d23c0011
- `color/neutral-alpha/200` (COLOR) = Mode 1: #7722001e
- `color/neutral-alpha/300` (COLOR) = Mode 1: #49150031
- `color/neutral-alpha/400` (COLOR) = Mode 1: #210a0064
- `color/neutral-alpha/500` (COLOR) = Mode 1: #15050091
- `color/neutral-alpha/600` (COLOR) = Mode 1: #100400b2
- `color/neutral-alpha/700` (COLOR) = Mode 1: #0e0400c4
- `color/neutral-alpha/800` (COLOR) = Mode 1: #0b0300de
- `color/neutral-alpha/900` (COLOR) = Mode 1: #0a0300ec
- `color/neutral-alpha/950` (COLOR) = Mode 1: #030100f6
- `color/scrim/black-5` (COLOR) = Mode 1: #0000000d
- `color/scrim/white-5` (COLOR) = Mode 1: #ffffff0d
- `color/scrim/black-10` (COLOR) = Mode 1: #0000001a
- `color/scrim/white-10` (COLOR) = Mode 1: #ffffff1a
- `color/scrim/black-20` (COLOR) = Mode 1: #00000033
- `color/scrim/white-20` (COLOR) = Mode 1: #ffffff33
- `color/scrim/black-40` (COLOR) = Mode 1: #00000066
- `color/scrim/white-40` (COLOR) = Mode 1: #ffffff66
- `color/scrim/black-60` (COLOR) = Mode 1: #00000099
- `color/scrim/white-60` (COLOR) = Mode 1: #ffffff99
- `color/scrim/black-80` (COLOR) = Mode 1: #000000cc
- `color/scrim/white-80` (COLOR) = Mode 1: #ffffffcc
- `color/palette/tomato/50` (COLOR) = Mode 1: #fff2ef
- `color/palette/tomato/100` (COLOR) = Mode 1: #ffe3dc
- `color/palette/tomato/200` (COLOR) = Mode 1: #ffcbbf
- `color/palette/tomato/300` (COLOR) = Mode 1: #ffb09e
- `color/palette/tomato/400` (COLOR) = Mode 1: #ff876e
- `color/palette/tomato/500` (COLOR) = Mode 1: #e54d2e
- `color/palette/tomato/600` (COLOR) = Mode 1: #d13b1b
- `color/palette/tomato/700` (COLOR) = Mode 1: #b02604
- `color/palette/tomato/800` (COLOR) = Mode 1: #901b00
- `color/palette/tomato/900` (COLOR) = Mode 1: #771602
- `color/palette/red/50` (COLOR) = Mode 1: #fff2f1
- `color/palette/red/100` (COLOR) = Mode 1: #ffe2e0
- `color/palette/red/200` (COLOR) = Mode 1: #ffcac7
- `color/palette/red/300` (COLOR) = Mode 1: #ffaeaa
- `color/palette/red/400` (COLOR) = Mode 1: #ff8581
- `color/palette/red/500` (COLOR) = Mode 1: #e5484d
- `color/palette/red/600` (COLOR) = Mode 1: #d1363e
- `color/palette/red/700` (COLOR) = Mode 1: #b0212d
- `color/palette/red/800` (COLOR) = Mode 1: #901722
- `color/palette/red/900` (COLOR) = Mode 1: #77131b
- `color/palette/ruby/50` (COLOR) = Mode 1: #fff2f3
- `color/palette/ruby/100` (COLOR) = Mode 1: #ffe2e3
- `color/palette/ruby/200` (COLOR) = Mode 1: #ffc9cd
- `color/palette/ruby/300` (COLOR) = Mode 1: #ffadb5
- `color/palette/ruby/400` (COLOR) = Mode 1: #ff8293
- `color/palette/ruby/500` (COLOR) = Mode 1: #e54666
- `color/palette/ruby/600` (COLOR) = Mode 1: #d03357
- `color/palette/ruby/700` (COLOR) = Mode 1: #af1d43
- `color/palette/ruby/800` (COLOR) = Mode 1: #8f1435
- `color/palette/ruby/900` (COLOR) = Mode 1: #76102b
- `color/palette/crimson/50` (COLOR) = Mode 1: #fff1f5
- `color/palette/crimson/100` (COLOR) = Mode 1: #ffe1e8
- `color/palette/crimson/200` (COLOR) = Mode 1: #ffc8d6
- `color/palette/crimson/300` (COLOR) = Mode 1: #ffaac2
- `color/palette/crimson/400` (COLOR) = Mode 1: #ff7ea8
- `color/palette/crimson/500` (COLOR) = Mode 1: #e93d82
- `color/palette/crimson/600` (COLOR) = Mode 1: #d22570
- `color/palette/crimson/700` (COLOR) = Mode 1: #b1085a
- `color/palette/crimson/800` (COLOR) = Mode 1: #900248
- `color/palette/crimson/900` (COLOR) = Mode 1: #77043b
- `color/palette/pink/50` (COLOR) = Mode 1: #fff1f8
- `color/palette/pink/100` (COLOR) = Mode 1: #ffe0ef
- `color/palette/pink/200` (COLOR) = Mode 1: #ffc6e4
- `color/palette/pink/300` (COLOR) = Mode 1: #ffa7d7
- `color/palette/pink/400` (COLOR) = Mode 1: #ff77c7
- `color/palette/pink/500` (COLOR) = Mode 1: #d6409f
- `color/palette/pink/600` (COLOR) = Mode 1: #c63191
- `color/palette/pink/700` (COLOR) = Mode 1: #a61b78
- `color/palette/pink/800` (COLOR) = Mode 1: #871261
- `color/palette/pink/900` (COLOR) = Mode 1: #700f50
- `color/palette/plum/50` (COLOR) = Mode 1: #fdf1ff
- `color/palette/plum/100` (COLOR) = Mode 1: #fbdfff
- `color/palette/plum/200` (COLOR) = Mode 1: #f7c5ff
- `color/palette/plum/300` (COLOR) = Mode 1: #f0a9fa
- `color/palette/plum/400` (COLOR) = Mode 1: #e086ee
- `color/palette/plum/500` (COLOR) = Mode 1: #c562d5
- `color/palette/plum/600` (COLOR) = Mode 1: #ab4aba
- `color/palette/plum/700` (COLOR) = Mode 1: #8d349b
- `color/palette/plum/800` (COLOR) = Mode 1: #72287e
- `color/palette/plum/900` (COLOR) = Mode 1: #5e2068
- `color/palette/purple/50` (COLOR) = Mode 1: #f8f3ff
- `color/palette/purple/100` (COLOR) = Mode 1: #f0e4ff
- `color/palette/purple/200` (COLOR) = Mode 1: #e4ceff
- `color/palette/purple/300` (COLOR) = Mode 1: #d8b5ff
- `color/palette/purple/400` (COLOR) = Mode 1: #c891ff
- `color/palette/purple/500` (COLOR) = Mode 1: #ae6ee9
- `color/palette/purple/600` (COLOR) = Mode 1: #8e4ec6
- `color/palette/purple/700` (COLOR) = Mode 1: #7a3fac
- `color/palette/purple/800` (COLOR) = Mode 1: #62318d
- `color/palette/purple/900` (COLOR) = Mode 1: #512874
- `color/palette/violet/50` (COLOR) = Mode 1: #f5f4ff
- `color/palette/violet/100` (COLOR) = Mode 1: #e8e7ff
- `color/palette/violet/200` (COLOR) = Mode 1: #d6d4ff
- `color/palette/violet/300` (COLOR) = Mode 1: #c3beff
- `color/palette/violet/400` (COLOR) = Mode 1: #aba0ff
- `color/palette/violet/500` (COLOR) = Mode 1: #8f7af8
- `color/palette/violet/600` (COLOR) = Mode 1: #6e56cf
- `color/palette/violet/700` (COLOR) = Mode 1: #614ab9
- `color/palette/violet/800` (COLOR) = Mode 1: #4d3b97
- `color/palette/violet/900` (COLOR) = Mode 1: #3f307d
- `color/palette/iris/50` (COLOR) = Mode 1: #f3f5ff
- `color/palette/iris/100` (COLOR) = Mode 1: #e5e8ff
- `color/palette/iris/200` (COLOR) = Mode 1: #d0d6ff
- `color/palette/iris/300` (COLOR) = Mode 1: #b9c2ff
- `color/palette/iris/400` (COLOR) = Mode 1: #9ca5ff
- `color/palette/iris/500` (COLOR) = Mode 1: #7b80ff
- `color/palette/iris/600` (COLOR) = Mode 1: #5b5bd6
- `color/palette/iris/700` (COLOR) = Mode 1: #504fbf
- `color/palette/iris/800` (COLOR) = Mode 1: #3f3f9d
- `color/palette/iris/900` (COLOR) = Mode 1: #343381
- `color/palette/indigo/50` (COLOR) = Mode 1: #f1f5ff
- `color/palette/indigo/100` (COLOR) = Mode 1: #e1eaff
- `color/palette/indigo/200` (COLOR) = Mode 1: #c9d9ff
- `color/palette/indigo/300` (COLOR) = Mode 1: #aec6ff
- `color/palette/indigo/400` (COLOR) = Mode 1: #8aabff
- `color/palette/indigo/500` (COLOR) = Mode 1: #6089ff
- `color/palette/indigo/600` (COLOR) = Mode 1: #3e63dd
- `color/palette/indigo/700` (COLOR) = Mode 1: #3456c5
- `color/palette/indigo/800` (COLOR) = Mode 1: #2844a1
- `color/palette/indigo/900` (COLOR) = Mode 1: #213885
- `color/palette/blue/50` (COLOR) = Mode 1: #eff6ff
- `color/palette/blue/100` (COLOR) = Mode 1: #dbecff
- `color/palette/blue/200` (COLOR) = Mode 1: #bedcff
- `color/palette/blue/300` (COLOR) = Mode 1: #9dcbff
- `color/palette/blue/400` (COLOR) = Mode 1: #6db3ff
- `color/palette/blue/500` (COLOR) = Mode 1: #0090ff
- `color/palette/blue/600` (COLOR) = Mode 1: #0079d8
- `color/palette/blue/700` (COLOR) = Mode 1: #0062b1
- `color/palette/blue/800` (COLOR) = Mode 1: #004f90
- `color/palette/blue/900` (COLOR) = Mode 1: #004078
- `color/palette/cyan/50` (COLOR) = Mode 1: #e8f9ff
- `color/palette/cyan/100` (COLOR) = Mode 1: #d0f0fc
- `color/palette/cyan/200` (COLOR) = Mode 1: #ade3f6
- `color/palette/cyan/300` (COLOR) = Mode 1: #85d4ef
- `color/palette/cyan/400` (COLOR) = Mode 1: #51bee0
- `color/palette/cyan/500` (COLOR) = Mode 1: #00a2c7
- `color/palette/cyan/600` (COLOR) = Mode 1: #0085a4
- `color/palette/cyan/700` (COLOR) = Mode 1: #006d86
- `color/palette/cyan/800` (COLOR) = Mode 1: #00576c
- `color/palette/cyan/900` (COLOR) = Mode 1: #00485a
- `color/palette/teal/50` (COLOR) = Mode 1: #e9faf6
- `color/palette/teal/100` (COLOR) = Mode 1: #d2f2eb
- `color/palette/teal/200` (COLOR) = Mode 1: #b0e6dc
- `color/palette/teal/300` (COLOR) = Mode 1: #89d8ca
- `color/palette/teal/400` (COLOR) = Mode 1: #58c4b3
- `color/palette/teal/500` (COLOR) = Mode 1: #12a594
- `color/palette/teal/600` (COLOR) = Mode 1: #008c7d
- `color/palette/teal/700` (COLOR) = Mode 1: #007265
- `color/palette/teal/800` (COLOR) = Mode 1: #005b51
- `color/palette/teal/900` (COLOR) = Mode 1: #004b43
- `color/palette/jade/50` (COLOR) = Mode 1: #eafaf4
- `color/palette/jade/100` (COLOR) = Mode 1: #d4f2e7
- `color/palette/jade/200` (COLOR) = Mode 1: #b4e6d4
- `color/palette/jade/300` (COLOR) = Mode 1: #8fd8bf
- `color/palette/jade/400` (COLOR) = Mode 1: #62c4a5
- `color/palette/jade/500` (COLOR) = Mode 1: #29a383
- `color/palette/jade/600` (COLOR) = Mode 1: #008d6f
- `color/palette/jade/700` (COLOR) = Mode 1: #00735a
- `color/palette/jade/800` (COLOR) = Mode 1: #005c48
- `color/palette/jade/900` (COLOR) = Mode 1: #004c3b
- `color/palette/green/50` (COLOR) = Mode 1: #eafaf0
- `color/palette/green/100` (COLOR) = Mode 1: #d5f2e0
- `color/palette/green/200` (COLOR) = Mode 1: #b5e7c8
- `color/palette/green/300` (COLOR) = Mode 1: #91daaf
- `color/palette/green/400` (COLOR) = Mode 1: #66c591
- `color/palette/green/500` (COLOR) = Mode 1: #30a46c
- `color/palette/green/600` (COLOR) = Mode 1: #0e8f59
- `color/palette/green/700` (COLOR) = Mode 1: #007547
- `color/palette/green/800` (COLOR) = Mode 1: #005e38
- `color/palette/green/900` (COLOR) = Mode 1: #004d2d
- `color/palette/grass/50` (COLOR) = Mode 1: #ecfaed
- `color/palette/grass/100` (COLOR) = Mode 1: #d7f2d9
- `color/palette/grass/200` (COLOR) = Mode 1: #bae7be
- `color/palette/grass/300` (COLOR) = Mode 1: #98daa0
- `color/palette/grass/400` (COLOR) = Mode 1: #71c57d
- `color/palette/grass/500` (COLOR) = Mode 1: #46a758
- `color/palette/grass/600` (COLOR) = Mode 1: #2b8e41
- `color/palette/grass/700` (COLOR) = Mode 1: #16752f
- `color/palette/grass/800` (COLOR) = Mode 1: #0d5e24
- `color/palette/grass/900` (COLOR) = Mode 1: #0b4e1d
- `color/palette/bronze/50` (COLOR) = Mode 1: #faf4f1
- `color/palette/bronze/100` (COLOR) = Mode 1: #f2e7e2
- `color/palette/bronze/200` (COLOR) = Mode 1: #e7d5cd
- `color/palette/bronze/300` (COLOR) = Mode 1: #dac1b6
- `color/palette/bronze/400` (COLOR) = Mode 1: #c6a79a
- `color/palette/bronze/500` (COLOR) = Mode 1: #a18072
- `color/palette/bronze/600` (COLOR) = Mode 1: #907063
- `color/palette/bronze/700` (COLOR) = Mode 1: #775a4e
- `color/palette/bronze/800` (COLOR) = Mode 1: #60483e
- `color/palette/bronze/900` (COLOR) = Mode 1: #4f3b32
- `color/palette/gold/50` (COLOR) = Mode 1: #f8f5f0
- `color/palette/gold/100` (COLOR) = Mode 1: #efe9df
- `color/palette/gold/200` (COLOR) = Mode 1: #e2d7c8
- `color/palette/gold/300` (COLOR) = Mode 1: #d4c4ae
- `color/palette/gold/400` (COLOR) = Mode 1: #beac90
- `color/palette/gold/500` (COLOR) = Mode 1: #978365
- `color/palette/gold/600` (COLOR) = Mode 1: #887558
- `color/palette/gold/700` (COLOR) = Mode 1: #705f44
- `color/palette/gold/800` (COLOR) = Mode 1: #5a4c36
- `color/palette/gold/900` (COLOR) = Mode 1: #4a3e2c
- `color/palette/brown/50` (COLOR) = Mode 1: #fcf4ed
- `color/palette/brown/100` (COLOR) = Mode 1: #f6e7da
- `color/palette/brown/200` (COLOR) = Mode 1: #edd4c0
- `color/palette/brown/300` (COLOR) = Mode 1: #e2bfa3
- `color/palette/brown/400` (COLOR) = Mode 1: #d0a581
- `color/palette/brown/500` (COLOR) = Mode 1: #ad7f58
- `color/palette/brown/600` (COLOR) = Mode 1: #9a6d47
- `color/palette/brown/700` (COLOR) = Mode 1: #7f5835
- `color/palette/brown/800` (COLOR) = Mode 1: #674629
- `color/palette/brown/900` (COLOR) = Mode 1: #553921
- `color/palette/orange/50` (COLOR) = Mode 1: #fff3ed
- `color/palette/orange/100` (COLOR) = Mode 1: #ffe3d7
- `color/palette/orange/200` (COLOR) = Mode 1: #ffccb6
- `color/palette/orange/300` (COLOR) = Mode 1: #ffb28f
- `color/palette/orange/400` (COLOR) = Mode 1: #ff8a52
- `color/palette/orange/500` (COLOR) = Mode 1: #f76b15
- `color/palette/orange/600` (COLOR) = Mode 1: #c35000
- `color/palette/orange/700` (COLOR) = Mode 1: #9f4000
- `color/palette/orange/800` (COLOR) = Mode 1: #813200
- `color/palette/orange/900` (COLOR) = Mode 1: #6b2800
- `color/palette/amber/50` (COLOR) = Mode 1: #fff4df
- `color/palette/amber/100` (COLOR) = Mode 1: #ffe7b8
- `color/palette/amber/200` (COLOR) = Mode 1: #fcd381
- `color/palette/amber/300` (COLOR) = Mode 1: #ffc53d
- `color/palette/amber/400` (COLOR) = Mode 1: #dca400
- `color/palette/amber/500` (COLOR) = Mode 1: #b88900
- `color/palette/amber/600` (COLOR) = Mode 1: #997100
- `color/palette/amber/700` (COLOR) = Mode 1: #7c5c00
- `color/palette/amber/800` (COLOR) = Mode 1: #644900
- `color/palette/amber/900` (COLOR) = Mode 1: #533c00
- `color/palette/yellow/50` (COLOR) = Mode 1: #fff8c3
- `color/palette/yellow/100` (COLOR) = Mode 1: #ffe629
- `color/palette/yellow/200` (COLOR) = Mode 1: #f4db00
- `color/palette/yellow/300` (COLOR) = Mode 1: #e0c800
- `color/palette/yellow/400` (COLOR) = Mode 1: #c5b000
- `color/palette/yellow/500` (COLOR) = Mode 1: #a49300
- `color/palette/yellow/600` (COLOR) = Mode 1: #887900
- `color/palette/yellow/700` (COLOR) = Mode 1: #6f6200
- `color/palette/yellow/800` (COLOR) = Mode 1: #594f00
- `color/palette/yellow/900` (COLOR) = Mode 1: #494100
- `color/palette/lime/50` (COLOR) = Mode 1: #ecfdd4
- `color/palette/lime/100` (COLOR) = Mode 1: #d8f7aa
- `color/palette/lime/200` (COLOR) = Mode 1: #bdee63
- `color/palette/lime/300` (COLOR) = Mode 1: #a4dd00
- `color/palette/lime/400` (COLOR) = Mode 1: #90c300
- `color/palette/lime/500` (COLOR) = Mode 1: #78a200
- `color/palette/lime/600` (COLOR) = Mode 1: #638600
- `color/palette/lime/700` (COLOR) = Mode 1: #506d00
- `color/palette/lime/800` (COLOR) = Mode 1: #3f5800
- `color/palette/lime/900` (COLOR) = Mode 1: #334800
- `color/palette/mint/50` (COLOR) = Mode 1: #e0fdf5
- `color/palette/mint/100` (COLOR) = Mode 1: #c0f8ea
- `color/palette/mint/200` (COLOR) = Mode 1: #86ead4
- `color/palette/mint/300` (COLOR) = Mode 1: #36e4c7
- `color/palette/mint/400` (COLOR) = Mode 1: #00caae
- `color/palette/mint/500` (COLOR) = Mode 1: #00a992
- `color/palette/mint/600` (COLOR) = Mode 1: #008c78
- `color/palette/mint/700` (COLOR) = Mode 1: #007261
- `color/palette/mint/800` (COLOR) = Mode 1: #005c4e
- `color/palette/mint/900` (COLOR) = Mode 1: #004b40
- `color/palette/sky/50` (COLOR) = Mode 1: #e7f9ff
- `color/palette/sky/100` (COLOR) = Mode 1: #c8f2ff
- `color/palette/sky/200` (COLOR) = Mode 1: #7ce2fe
- `color/palette/sky/300` (COLOR) = Mode 1: #45dbff
- `color/palette/sky/400` (COLOR) = Mode 1: #00c2e7
- `color/palette/sky/500` (COLOR) = Mode 1: #00a2c1
- `color/palette/sky/600` (COLOR) = Mode 1: #0086a0
- `color/palette/sky/700` (COLOR) = Mode 1: #006d83
- `color/palette/sky/800` (COLOR) = Mode 1: #00586a
- `color/palette/sky/900` (COLOR) = Mode 1: #004857
- `color/palette/gray/50` (COLOR) = Mode 1: #f5f5f5
- `color/palette/gray/100` (COLOR) = Mode 1: #eaeaea
- `color/palette/gray/200` (COLOR) = Mode 1: #d9d9d9
- `color/palette/gray/300` (COLOR) = Mode 1: #c6c6c6
- `color/palette/gray/400` (COLOR) = Mode 1: #aeaeae
- `color/palette/gray/500` (COLOR) = Mode 1: #8d8d8d
- `color/palette/gray/600` (COLOR) = Mode 1: #787878
- `color/palette/gray/700` (COLOR) = Mode 1: #616161
- `color/palette/gray/800` (COLOR) = Mode 1: #4e4e4e
- `color/palette/gray/900` (COLOR) = Mode 1: #404040
- `color/palette/mauve/50` (COLOR) = Mode 1: #f5f5f7
- `color/palette/mauve/100` (COLOR) = Mode 1: #eae9ed
- `color/palette/mauve/200` (COLOR) = Mode 1: #d9d8df
- `color/palette/mauve/300` (COLOR) = Mode 1: #c7c5cf
- `color/palette/mauve/400` (COLOR) = Mode 1: #afadb9
- `color/palette/mauve/500` (COLOR) = Mode 1: #8e8c99
- `color/palette/mauve/600` (COLOR) = Mode 1: #787683
- `color/palette/mauve/700` (COLOR) = Mode 1: #62606b
- `color/palette/mauve/800` (COLOR) = Mode 1: #4e4d56
- `color/palette/mauve/900` (COLOR) = Mode 1: #403f47
- `color/palette/slate/50` (COLOR) = Mode 1: #f5f5f7
- `color/palette/slate/100` (COLOR) = Mode 1: #e9e9ed
- `color/palette/slate/200` (COLOR) = Mode 1: #d7d9df
- `color/palette/slate/300` (COLOR) = Mode 1: #c5c6ce
- `color/palette/slate/400` (COLOR) = Mode 1: #acaeb8
- `color/palette/slate/500` (COLOR) = Mode 1: #8b8d98
- `color/palette/slate/600` (COLOR) = Mode 1: #767882
- `color/palette/slate/700` (COLOR) = Mode 1: #5f616a
- `color/palette/slate/800` (COLOR) = Mode 1: #4c4e56
- `color/palette/slate/900` (COLOR) = Mode 1: #3e4046
- `color/palette/sage/50` (COLOR) = Mode 1: #f4f6f5
- `color/palette/sage/100` (COLOR) = Mode 1: #e8eae9
- `color/palette/sage/200` (COLOR) = Mode 1: #d6dad9
- `color/palette/sage/300` (COLOR) = Mode 1: #c2c8c6
- `color/palette/sage/400` (COLOR) = Mode 1: #a9b0ae
- `color/palette/sage/500` (COLOR) = Mode 1: #868e8b
- `color/palette/sage/600` (COLOR) = Mode 1: #737a77
- `color/palette/sage/700` (COLOR) = Mode 1: #5c6361
- `color/palette/sage/800` (COLOR) = Mode 1: #4a504d
- `color/palette/sage/900` (COLOR) = Mode 1: #3c413f
- `color/palette/olive/50` (COLOR) = Mode 1: #f5f6f4
- `color/palette/olive/100` (COLOR) = Mode 1: #e9eae8
- `color/palette/olive/200` (COLOR) = Mode 1: #d7dad6
- `color/palette/olive/300` (COLOR) = Mode 1: #c4c8c3
- `color/palette/olive/400` (COLOR) = Mode 1: #abb0aa
- `color/palette/olive/500` (COLOR) = Mode 1: #898e87
- `color/palette/olive/600` (COLOR) = Mode 1: #757a73
- `color/palette/olive/700` (COLOR) = Mode 1: #5f635d
- `color/palette/olive/800` (COLOR) = Mode 1: #4c4f4a
- `color/palette/olive/900` (COLOR) = Mode 1: #3e413d
- `color/palette/sand/50` (COLOR) = Mode 1: #f5f5f4
- `color/palette/sand/100` (COLOR) = Mode 1: #eaeae8
- `color/palette/sand/200` (COLOR) = Mode 1: #d9d9d5
- `color/palette/sand/300` (COLOR) = Mode 1: #c7c7c2
- `color/palette/sand/400` (COLOR) = Mode 1: #afafa8
- `color/palette/sand/500` (COLOR) = Mode 1: #8d8d86
- `color/palette/sand/600` (COLOR) = Mode 1: #797972
- `color/palette/sand/700` (COLOR) = Mode 1: #62625c
- `color/palette/sand/800` (COLOR) = Mode 1: #4e4e49
- `color/palette/sand/900` (COLOR) = Mode 1: #40403c
- `spacing/2` (FLOAT) = Mode 1: 2
- `spacing/4` (FLOAT) = Mode 1: 4
- `spacing/8` (FLOAT) = Mode 1: 8
- `spacing/12` (FLOAT) = Mode 1: 12
- `spacing/16` (FLOAT) = Mode 1: 16
- `spacing/20` (FLOAT) = Mode 1: 20
- `spacing/24` (FLOAT) = Mode 1: 24
- `spacing/32` (FLOAT) = Mode 1: 32
- `spacing/40` (FLOAT) = Mode 1: 40
- `spacing/48` (FLOAT) = Mode 1: 48
- `spacing/64` (FLOAT) = Mode 1: 64
- `spacing/80` (FLOAT) = Mode 1: 80
- `spacing/96` (FLOAT) = Mode 1: 96
- `radius/none` (FLOAT) = Mode 1: 0
- `radius/xs` (FLOAT) = Mode 1: 2
- `radius/sm` (FLOAT) = Mode 1: 2
- `radius/md` (FLOAT) = Mode 1: 4
- `radius/lg` (FLOAT) = Mode 1: 4
- `radius/xl` (FLOAT) = Mode 1: 8
- `radius/2xl` (FLOAT) = Mode 1: 8
- `radius/3xl` (FLOAT) = Mode 1: 12
- `radius/full` (FLOAT) = Mode 1: 9999
- `radius/button` (FLOAT) = Mode 1: 4
- `breakpoint/sm` (FLOAT) = Mode 1: 640
- `breakpoint/md` (FLOAT) = Mode 1: 768
- `breakpoint/lg` (FLOAT) = Mode 1: 1024
- `breakpoint/xl` (FLOAT) = Mode 1: 1280
- `breakpoint/2xl` (FLOAT) = Mode 1: 1536
- `size/control/sm` (FLOAT) = Mode 1: 32
- `size/control/md` (FLOAT) = Mode 1: 44
- `size/control/lg` (FLOAT) = Mode 1: 56
- `size/icon/sm` (FLOAT) = Mode 1: 16
- `size/icon/md` (FLOAT) = Mode 1: 20
- `size/icon/lg` (FLOAT) = Mode 1: 24
- `opacity/0` (FLOAT) = Mode 1: 0
- `opacity/5` (FLOAT) = Mode 1: 0.05000000074505806
- `opacity/10` (FLOAT) = Mode 1: 0.10000000149011612
- `opacity/20` (FLOAT) = Mode 1: 0.20000000298023224
- `opacity/40` (FLOAT) = Mode 1: 0.4000000059604645
- `opacity/60` (FLOAT) = Mode 1: 0.6000000238418579
- `opacity/80` (FLOAT) = Mode 1: 0.800000011920929
- `opacity/100` (FLOAT) = Mode 1: 1
- `opacity/disabled` (FLOAT) = Mode 1: 0.4000000059604645
- `opacity/hover` (FLOAT) = Mode 1: 0.07999999821186066
- `opacity/pressed` (FLOAT) = Mode 1: 0.11999999731779099
- `opacity/backdrop` (FLOAT) = Mode 1: 0.5
- `z/base` (FLOAT) = Mode 1: 0
- `z/dropdown` (FLOAT) = Mode 1: 1000
- `z/sticky` (FLOAT) = Mode 1: 1100
- `z/overlay` (FLOAT) = Mode 1: 1300
- `z/modal` (FLOAT) = Mode 1: 1400
- `z/popover` (FLOAT) = Mode 1: 1500
- `z/toast` (FLOAT) = Mode 1: 1700
- `z/tooltip` (FLOAT) = Mode 1: 1800

## Styles
### Text
- `title` - font={"family":"Inter","style":"Bold","variationSettings":{"slnt":0,"wght":700}} 32
- `subheading` - font={"family":"Inter","style":"Semi Bold","variationSettings":{"slnt":0,"wght":600}} 20
- `label` - font={"family":"Inter","style":"Medium","variationSettings":{"slnt":0,"wght":500}} 14
- `caption` - font={"family":"Inter","style":"Semi Bold","variationSettings":{"slnt":0,"wght":600}} 12
- `Display/Large` - font={"family":"IBM Plex Sans","style":"Bold","variationSettings":{"wdth":100,"wght":700}} 56
- `Display/Medium` - font={"family":"IBM Plex Sans","style":"Bold","variationSettings":{"wdth":100,"wght":700}} 48
- `Display/Small` - font={"family":"IBM Plex Sans","style":"Bold","variationSettings":{"wdth":100,"wght":700}} 40
- `Heading/H1` - font={"family":"IBM Plex Sans","style":"Bold","variationSettings":{"wdth":100,"wght":700}} 32
- `Heading/H2` - font={"family":"IBM Plex Sans","style":"SemiBold","variationSettings":{"wdth":100,"wght":600}} 28
- `Heading/H3` - font={"family":"IBM Plex Sans","style":"SemiBold","variationSettings":{"wdth":100,"wght":600}} 24
- `Heading/H4` - font={"family":"IBM Plex Sans","style":"SemiBold","variationSettings":{"wdth":100,"wght":600}} 20
- `Heading/H5` - font={"family":"IBM Plex Sans","style":"SemiBold","variationSettings":{"wdth":100,"wght":600}} 18
- `Heading/H6` - font={"family":"IBM Plex Sans","style":"SemiBold","variationSettings":{"wdth":100,"wght":600}} 16
- `Title/Large` - font={"family":"IBM Plex Sans","style":"Medium","variationSettings":{"wdth":100,"wght":500}} 20
- `Title/Medium` - font={"family":"IBM Plex Sans","style":"Medium","variationSettings":{"wdth":100,"wght":500}} 18
- `Title/Small` - font={"family":"IBM Plex Sans","style":"Medium","variationSettings":{"wdth":100,"wght":500}} 16
- `Body/Large` - font={"family":"IBM Plex Sans","style":"Regular","variationSettings":{"wdth":100,"wght":400}} 16
- `Body/Medium` - font={"family":"IBM Plex Sans","style":"Regular","variationSettings":{"wdth":100,"wght":400}} 14
- `Body/Small` - font={"family":"IBM Plex Sans","style":"Regular","variationSettings":{"wdth":100,"wght":400}} 12
- `Label/Large` - font={"family":"IBM Plex Sans","style":"Medium","variationSettings":{"wdth":100,"wght":500}} 14
- `Label/Medium` - font={"family":"IBM Plex Sans","style":"Medium","variationSettings":{"wdth":100,"wght":500}} 12
- `Label/Small` - font={"family":"IBM Plex Sans","style":"Medium","variationSettings":{"wdth":100,"wght":500}} 10
- `Caption/Regular` - font={"family":"IBM Plex Sans","style":"Regular","variationSettings":{"wdth":100,"wght":400}} 12
- `Caption/Small` - font={"family":"IBM Plex Sans","style":"Regular","variationSettings":{"wdth":100,"wght":400}} 10
### Effect
- `elevation/1` - effects=[{"type":"DROP_SHADOW","visible":true,"radius":1,"boundVariables":{},"color":{"r":0.05882352963089943,"g":0.09019608050584793,"b":0.16470588743686676,"a":0.0313725508749485},"offset":{"x":0,"y":1},"spread":0,"blendMode":"NORMAL","showShadowBehindNode":true},{"type":"DROP_SHADOW","visible":true,"radius":2,"boundVariables":{},"color":{"r":0.05882352963089943,"g":0.09019608050584793,"b":0.16470588743686676,"a":0.062745101749897},"offset":{"x":0,"y":1},"spread":0,"blendMode":"NORMAL","showShadowBehindNode":true}]
- `elevation/2` - effects=[{"type":"DROP_SHADOW","visible":true,"radius":2,"boundVariables":{},"color":{"r":0.05882352963089943,"g":0.09019608050584793,"b":0.16470588743686676,"a":0.03529411926865578},"offset":{"x":0,"y":1},"spread":0,"blendMode":"NORMAL","showShadowBehindNode":true},{"type":"DROP_SHADOW","visible":true,"radius":4,"boundVariables":{},"color":{"r":0.05882352963089943,"g":0.09019608050584793,"b":0.16470588743686676,"a":0.062745101749897},"offset":{"x":0,"y":2},"spread":-1,"blendMode":"NORMAL","showShadowBehindNode":true}]
- `elevation/3` - effects=[{"type":"DROP_SHADOW","visible":true,"radius":2,"boundVariables":{},"color":{"r":0.05882352963089943,"g":0.09019608050584793,"b":0.16470588743686676,"a":0.03529411926865578},"offset":{"x":0,"y":1},"spread":0,"blendMode":"NORMAL","showShadowBehindNode":true},{"type":"DROP_SHADOW","visible":true,"radius":8,"boundVariables":{},"color":{"r":0.05882352963089943,"g":0.09019608050584793,"b":0.16470588743686676,"a":0.07450980693101883},"offset":{"x":0,"y":4},"spread":-2,"blendMode":"NORMAL","showShadowBehindNode":true}]
- `elevation/4` - effects=[{"type":"DROP_SHADOW","visible":true,"radius":3,"boundVariables":{},"color":{"r":0.05882352963089943,"g":0.09019608050584793,"b":0.16470588743686676,"a":0.03529411926865578},"offset":{"x":0,"y":2},"spread":-1,"blendMode":"NORMAL","showShadowBehindNode":true},{"type":"DROP_SHADOW","visible":true,"radius":12,"boundVariables":{},"color":{"r":0.05882352963089943,"g":0.09019608050584793,"b":0.16470588743686676,"a":0.08627451211214066},"offset":{"x":0,"y":6},"spread":-3,"blendMode":"NORMAL","showShadowBehindNode":true}]
- `elevation/5` - effects=[{"type":"DROP_SHADOW","visible":true,"radius":4,"boundVariables":{},"color":{"r":0.05882352963089943,"g":0.09019608050584793,"b":0.16470588743686676,"a":0.04313725605607033},"offset":{"x":0,"y":3},"spread":-1,"blendMode":"NORMAL","showShadowBehindNode":true},{"type":"DROP_SHADOW","visible":true,"radius":20,"boundVariables":{},"color":{"r":0.05882352963089943,"g":0.09019608050584793,"b":0.16470588743686676,"a":0.10980392247438431},"offset":{"x":0,"y":10},"spread":-4,"blendMode":"NORMAL","showShadowBehindNode":true}]
### Grid
- `grid/laptop` - grids=[{"pattern":"COLUMNS","visible":true,"color":{"r":1,"g":0.20000000298023224,"b":0.20000000298023224,"a":0.10000000149011612},"gutterSize":24,"alignment":"STRETCH","count":12,"offset":32,"boundVariables":{}}]
- `grid/web` - grids=[{"pattern":"COLUMNS","visible":true,"color":{"r":1,"g":0.20000000298023224,"b":0.20000000298023224,"a":0.10000000149011612},"gutterSize":24,"alignment":"STRETCH","count":12,"offset":32,"boundVariables":{}}]
- `grid/wide` - grids=[{"pattern":"COLUMNS","visible":true,"color":{"r":1,"g":0.20000000298023224,"b":0.20000000298023224,"a":0.10000000149011612},"gutterSize":32,"alignment":"STRETCH","count":12,"offset":64,"boundVariables":{}}]

## Components
### Feature chip
- Type: COMPONENT_SET (Roadmap/Feature chip)
- Figma node ID: `1:48`
- Figma component key: `77b026bbd05954a0c1a7e2d85dd367dd47c27414`
- Source page: Roadmap
- Default variant ID: `1:28`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=5, topLeftRadius=5, topRightRadius=5, bottomRightRadius=5, bottomLeftRadius=5
- Component properties:
  - `Label#1:0`: TEXT default=Tên tính năng
  - `Kind`: VARIANT default=Hiện có options=Hiện có, Bổ sung MVP, Thị trường, Dời sang V2
- Variants:
  - Kind=Hiện có — id `1:28`, key `879356c4d8264372266fe01b09f9019ffbb5d3f4` (Kind=Hiện có)
  - Kind=Bổ sung MVP — id `1:33`, key `17234d281654ced2e8aaaf0d3d54af9f8f3c3a7d` (Kind=Bổ sung MVP)
  - Kind=Thị trường — id `1:38`, key `4de16a4b06227e0f43ce1a36630b94cad201b369` (Kind=Thị trường)
  - Kind=Dời sang V2 — id `1:43`, key `c097963d9db647a0abd3b129b4e1ea554425a5df` (Kind=Dời sang V2)
- Text layers:
  - `Feature chip/Kind=Hiện có/Label`: "Tên tính năng" refs=characters=Label#1:0 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Feature chip/Kind=Bổ sung MVP/Label`: "Tên tính năng" refs=characters=Label#1:0 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Feature chip/Kind=Thị trường/Label`: "Tên tính năng" refs=characters=Label#1:0 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Feature chip/Kind=Dời sang V2/Label`: "Tên tính năng" refs=characters=Label#1:0 constraints={"horizontal":"MIN","vertical":"MIN"}
- Usage:
  - Find it with figma.findComponent("Feature chip").
  - Instantiate the set/default variant with figma.instantiate("1:48", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Label#1:0`, `Kind`.
- Observed instances: 61
- Used on pages: Roadmap
- Used in screens: Roadmap / Roadmap / VNG Value
- Observed property values:
  - `Label#1:0`: Tính năng hiện có, Bổ sung vào MVP (pháp lý, làm lại hệ thống), Đề xuất theo thị trường, Tính năng hiện có, dời theo chốt họp 09/11, Hợp đồng kinh doanh, Lịch hẹn, Khách hàng, Đối tác, Tài sản thẩm định, Bảng tính phương pháp so sánh, Thông báo kết quả sơ bộ, Tài sản so sánh (TSSS)
  - `Kind`: Hiện có, Bổ sung MVP, Thị trường, Dời sang V2
- Instantiate:
```js
await figma.instantiate("1:48", {
  parentId: screen.id,
  props: {
    "Label#1:0": "Tên tính năng",
    "Kind": "Hiện có"
  },
});
```

### Version badge
- Type: COMPONENT (Roadmap/Version badge)
- Figma node ID: `1:49`
- Figma component key: `697a1b018fbc0c7df2e189c20f261cc183c91aa2`
- Source page: Roadmap
- Layout: layoutMode=HORIZONTAL, itemSpacing=8, padding={"left":12,"right":12,"top":4,"bottom":4}, primaryAxisSizingMode=AUTO, counterAxisSizingMode=AUTO, primaryAxisAlignItems=MIN, counterAxisAlignItems=MIN, clipsContent=false
- Shape: cornerRadius=9999, topLeftRadius=9999, topRightRadius=9999, bottomRightRadius=9999, bottomLeftRadius=9999
- Component properties:
  - `Label#1:5`: TEXT default=MVP
- Text layers:
  - `Version badge/Label`: "MVP" refs=characters=Label#1:5 constraints={"horizontal":"MIN","vertical":"MIN"}
- Usage:
  - Find it with figma.findComponent("Version badge").
  - Instantiate with figma.instantiate("1:49", { parentId, props, overrides }).
  - Set component properties with exact keys: `Label#1:5`.
- Observed instances: 3
- Used on pages: Roadmap
- Used in screens: Roadmap / Roadmap / VNG Value
- Observed property values:
  - `Label#1:5`: MVP, V2, V3
- Instantiate:
```js
await figma.instantiate("1:49", {
  parentId: screen.id,
  props: {
    "Label#1:5": "MVP"
  },
});
```

### Atom/Icon
- Type: COMPONENT_SET (DS · System/Atom/Icon)
- Figma node ID: `1:1951`
- Figma component key: `7c4b041ca54b99140060acd5eecd1adb93f535d3`
- Source page: DS · System
- Default variant ID: `1:1851`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Name`: VARIANT default=Search options=Search, Plus, Minus, Close, Check, ChevronDown, ChevronRight, ChevronLeft, Home, User, Menu, Settings, Bell, Mail, More, Trash, Edit, Filter, Calendar, Activity, Info, Alert, Eye, Back
- Variants:
  - Name=Search — id `1:1851`, key `456ce133723661d563175b8d142137696da86fb6` (Name=Search)
  - Name=Plus — id `1:1855`, key `0c217a62e06f44db026d15a4e7a0e08488eabb4b` (Name=Plus)
  - Name=Minus — id `1:1859`, key `5d6443987a9a4ed82156980459aa6a0a60dff070` (Name=Minus)
  - Name=Close — id `1:1862`, key `9743dac9e3782d55d5ce77f6de92b0c9bd2c6f9b` (Name=Close)
  - Name=Check — id `1:1866`, key `2059682a332766f506f2054dd7a169712b6cfcb3` (Name=Check)
  - Name=ChevronDown — id `1:1869`, key `023405347c749ae92fd1a6de3f5f264b58ba50fb` (Name=ChevronDown)
  - Name=ChevronRight — id `1:1872`, key `df612f71dc861e20de68ae91e730e13839e29d8f` (Name=ChevronRight)
  - Name=ChevronLeft — id `1:1875`, key `602ad5fd13c53ad4892e05de749b4d219d9dcf53` (Name=ChevronLeft)
  - Name=Home — id `1:1878`, key `72a17731e236691387b17855b5d62e17ad3cc33e` (Name=Home)
  - Name=User — id `1:1882`, key `61f58f9e7bfedafb6da6608d8ec69e83e6e18d87` (Name=User)
  - Name=Menu — id `1:1886`, key `fac8498ad7ae95c1e55aa351bc58b0ec96d6addd` (Name=Menu)
  - Name=Settings — id `1:1891`, key `3c9721247796d5137bfd01c54b26844642080796` (Name=Settings)
  - Name=Bell — id `1:1895`, key `11216f766923eca7252fbb2968b6f165bdc0f466` (Name=Bell)
  - Name=Mail — id `1:1899`, key `f1aaa5066d987e780ae3348564a3457b7011a89c` (Name=Mail)
  - Name=More — id `1:1903`, key `2b8709fd7a4d948b0504082329e216cd23a92de0` (Name=More)
  - Name=Trash — id `1:1908`, key `996e11d92048c7aa684b26a45e5ddb0298a17e72` (Name=Trash)
  - Name=Edit — id `1:1915`, key `5d84703eaa31c9a268990b6c4867820ce8eba771` (Name=Edit)
  - Name=Filter — id `1:1919`, key `deb69009d18a2245f2b6451289e43f795703f8e1` (Name=Filter)
  - Name=Calendar — id `1:1924`, key `390d57973b562981775476eb7e30ad2effa03139` (Name=Calendar)
  - Name=Activity — id `1:1930`, key `bb5e3b3b7499b0af433a17c480fa89087baef0ee` (Name=Activity)
  - Name=Info — id `1:1933`, key `c1a32069be6e964f2587c1358d47ca18e4159546` (Name=Info)
  - Name=Alert — id `1:1938`, key `7304b7749a078104cf0cde6185408a15c277de9b` (Name=Alert)
  - Name=Eye — id `1:1943`, key `bdec251c5d87a68deebf96bb498264e46de07837` (Name=Eye)
  - Name=Back — id `1:1947`, key `11033ab9ef108776b5f3f7bc3ea6d66520e869f1` (Name=Back)
- Usage:
  - Find it with figma.findComponent("Atom/Icon").
  - Instantiate the set/default variant with figma.instantiate("1:1951", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Name`.
- Observed instances: 1
- Used on pages: DS · System
- Used in screens: DS · System / Doc/Atoms
- Observed property values:
  - `Name`: Search
- Instantiate:
```js
await figma.instantiate("1:1951", {
  parentId: screen.id,
  props: {
    "Name": "Search"
  },
});
```

### Atom/Status/Badge
- Type: COMPONENT_SET (DS · System/Atom/Status/Badge)
- Figma node ID: `1:1972`
- Figma component key: `3f815dbd8017a579695e540e0fc55e955476e7fc`
- Source page: DS · System
- Default variant ID: `1:1952`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Label#1:6`: TEXT default=Label
  - `Tone`: VARIANT default=neutral options=neutral, success, warning, error, info
  - `Size`: VARIANT default=sm options=sm, md
- Variants:
  - Tone=neutral, Size=sm — id `1:1952`, key `2106181874ad2ffc7d2a5f01b4ba65a29e9d3b2a` (Tone=neutral, Size=sm)
  - Tone=neutral, Size=md — id `1:1954`, key `251b0b636998260a1a016c34916858502f6f69c2` (Tone=neutral, Size=md)
  - Tone=success, Size=sm — id `1:1956`, key `360463762d6ced431706de863890403c40e9d2a2` (Tone=success, Size=sm)
  - Tone=success, Size=md — id `1:1958`, key `d16d05ac40227ffc6ce267f32e7be3aff351b8f8` (Tone=success, Size=md)
  - Tone=warning, Size=sm — id `1:1960`, key `3e456865f12853cfc158865113ede771cb4c9933` (Tone=warning, Size=sm)
  - Tone=warning, Size=md — id `1:1962`, key `ef70595e8a36f7a173cd95a70e7bc728bd50ec68` (Tone=warning, Size=md)
  - Tone=error, Size=sm — id `1:1964`, key `45422a596ae9bde8e74013f0af9303b5fb4ee783` (Tone=error, Size=sm)
  - Tone=error, Size=md — id `1:1966`, key `4288e2e465f07381ac67d84c3ec8bce3ec749fdf` (Tone=error, Size=md)
  - Tone=info, Size=sm — id `1:1968`, key `ff712a35eaab35a0db323c64b096ca4ca6cf1329` (Tone=info, Size=sm)
  - Tone=info, Size=md — id `1:1970`, key `e4652a1bddf5442b9d4347e7ecbde4b37c71d49c` (Tone=info, Size=md)
- Text layers:
  - `Atom/Status/Badge/Tone=neutral, Size=sm/Label`: "Label" refs=characters=Label#1:6 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Atom/Status/Badge/Tone=neutral, Size=md/Label`: "Label" refs=characters=Label#1:6 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Atom/Status/Badge/Tone=success, Size=sm/Label`: "Label" refs=characters=Label#1:6 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Atom/Status/Badge/Tone=success, Size=md/Label`: "Label" refs=characters=Label#1:6 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Atom/Status/Badge/Tone=warning, Size=sm/Label`: "Label" refs=characters=Label#1:6 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Atom/Status/Badge/Tone=warning, Size=md/Label`: "Label" refs=characters=Label#1:6 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Atom/Status/Badge/Tone=error, Size=sm/Label`: "Label" refs=characters=Label#1:6 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Atom/Status/Badge/Tone=error, Size=md/Label`: "Label" refs=characters=Label#1:6 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Atom/Status/Badge/Tone=info, Size=sm/Label`: "Label" refs=characters=Label#1:6 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Atom/Status/Badge/Tone=info, Size=md/Label`: "Label" refs=characters=Label#1:6 constraints={"horizontal":"MIN","vertical":"MIN"}
- Usage:
  - Find it with figma.findComponent("Atom/Status/Badge").
  - Instantiate the set/default variant with figma.instantiate("1:1972", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Label#1:6`, `Tone`, `Size`.
- Observed instances: 1
- Used on pages: DS · System
- Used in screens: DS · System / Doc/Atoms
- Observed property values:
  - `Label#1:6`: Label
  - `Tone`: neutral
  - `Size`: sm
- Instantiate:
```js
await figma.instantiate("1:1972", {
  parentId: screen.id,
  props: {
    "Label#1:6": "Label",
    "Tone": "neutral",
    "Size": "sm"
  },
});
```

### Atom/Status/Dot
- Type: COMPONENT_SET (DS · System/Atom/Status/Dot)
- Figma node ID: `1:1978`
- Figma component key: `4d27affbdaba9b347114e124cb1edaf0fd77d509`
- Source page: DS · System
- Default variant ID: `1:1973`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Tone`: VARIANT default=neutral options=neutral, success, warning, error, info
- Variants:
  - Tone=neutral — id `1:1973`, key `0e5386fd2ebf2e0d3bbdd845fc87ad10fb9c12de` (Tone=neutral)
  - Tone=success — id `1:1974`, key `9bd07afdac626044184f1d48f7c2f1723becc816` (Tone=success)
  - Tone=warning — id `1:1975`, key `694a20b4d77472c4ebd74a6b15a60372f71711cf` (Tone=warning)
  - Tone=error — id `1:1976`, key `22d11caabc054c6d5088375cb864cd13c7608da0` (Tone=error)
  - Tone=info — id `1:1977`, key `9b9b0a33a92d3c2fe91e90b3469dc5e6ae743262` (Tone=info)
- Usage:
  - Find it with figma.findComponent("Atom/Status/Dot").
  - Instantiate the set/default variant with figma.instantiate("1:1978", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Tone`.
- Observed instances: 1
- Used on pages: DS · System
- Used in screens: DS · System / Doc/Atoms
- Observed property values:
  - `Tone`: neutral
- Instantiate:
```js
await figma.instantiate("1:1978", {
  parentId: screen.id,
  props: {
    "Tone": "neutral"
  },
});
```

### Atom/Status/Chip
- Type: COMPONENT_SET (DS · System/Atom/Status/Chip)
- Figma node ID: `1:2009`
- Figma component key: `de271250d298e1b1b6e2c10129426ea706aa72c1`
- Source page: DS · System
- Default variant ID: `1:1979`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Label#1:17`: TEXT default=Neutral
  - `Tone`: VARIANT default=neutral options=neutral, success, warning, error, info
  - `Selected`: VARIANT default=off options=off, on
- Variants:
  - Tone=neutral, Selected=off — id `1:1979`, key `20c2ea8f631fc5099538db76c239a3b68bb28be7` (Tone=neutral, Selected=off)
  - Tone=neutral, Selected=on — id `1:1982`, key `490d4f53a0642b00aa9db9dceb2e001a7fe5975b` (Tone=neutral, Selected=on)
  - Tone=success, Selected=off — id `1:1985`, key `a018c1504a110e1fe3a264a7cb900bdd19517731` (Tone=success, Selected=off)
  - Tone=success, Selected=on — id `1:1988`, key `a33783b7d43feb325817902c8ae588f2c5c50c57` (Tone=success, Selected=on)
  - Tone=warning, Selected=off — id `1:1991`, key `41766ace37b0639a2d2764f7462ba19f54237b6a` (Tone=warning, Selected=off)
  - Tone=warning, Selected=on — id `1:1994`, key `2e6129b1449250165f8d099ee1cbe796becf9162` (Tone=warning, Selected=on)
  - Tone=error, Selected=off — id `1:1997`, key `58e17a61a7da220334d2011fbd63bb4d810ba9a0` (Tone=error, Selected=off)
  - Tone=error, Selected=on — id `1:2000`, key `2091a0c01572d0017693e096428cd989f9d1a5cf` (Tone=error, Selected=on)
  - Tone=info, Selected=off — id `1:2003`, key `e35b9afbbdb6450ee4666b19dfb9f3182ffc9036` (Tone=info, Selected=off)
  - Tone=info, Selected=on — id `1:2006`, key `60ce928d47f14b9aca7f4148a13f6caa4afe4893` (Tone=info, Selected=on)
- Text layers:
  - `Atom/Status/Chip/Tone=neutral, Selected=off/Label`: "Neutral" refs=characters=Label#1:17 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Atom/Status/Chip/Tone=neutral, Selected=on/Label`: "Neutral" refs=characters=Label#1:17 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Atom/Status/Chip/Tone=success, Selected=off/Label`: "Neutral" refs=characters=Label#1:17 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Atom/Status/Chip/Tone=success, Selected=on/Label`: "Neutral" refs=characters=Label#1:17 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Atom/Status/Chip/Tone=warning, Selected=off/Label`: "Neutral" refs=characters=Label#1:17 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Atom/Status/Chip/Tone=warning, Selected=on/Label`: "Neutral" refs=characters=Label#1:17 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Atom/Status/Chip/Tone=error, Selected=off/Label`: "Neutral" refs=characters=Label#1:17 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Atom/Status/Chip/Tone=error, Selected=on/Label`: "Neutral" refs=characters=Label#1:17 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Atom/Status/Chip/Tone=info, Selected=off/Label`: "Neutral" refs=characters=Label#1:17 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Atom/Status/Chip/Tone=info, Selected=on/Label`: "Neutral" refs=characters=Label#1:17 constraints={"horizontal":"MIN","vertical":"MIN"}
- Usage:
  - Find it with figma.findComponent("Atom/Status/Chip").
  - Instantiate the set/default variant with figma.instantiate("1:2009", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Label#1:17`, `Tone`, `Selected`.
- Observed instances: 1
- Used on pages: DS · System
- Used in screens: DS · System / Doc/Atoms
- Observed property values:
  - `Label#1:17`: Neutral
  - `Tone`: neutral
  - `Selected`: off
- Instantiate:
```js
await figma.instantiate("1:2009", {
  parentId: screen.id,
  props: {
    "Label#1:17": "Neutral",
    "Tone": "neutral",
    "Selected": "off"
  },
});
```

### Atom/Divider
- Type: COMPONENT_SET (DS · System/Atom/Divider)
- Figma node ID: `1:2012`
- Figma component key: `d1b24ed443ea8999dd5920c5ba059f32b3545bb9`
- Source page: DS · System
- Default variant ID: `1:2010`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Orientation`: VARIANT default=horizontal options=horizontal, vertical
- Variants:
  - Orientation=horizontal — id `1:2010`, key `7a7a0cf3fc18f4222d66ed22c5d0fa6f99c23ee2` (Orientation=horizontal)
  - Orientation=vertical — id `1:2011`, key `681821da8a41cb1aae9acac8ffd0c2e5adf05fe6` (Orientation=vertical)
- Usage:
  - Find it with figma.findComponent("Atom/Divider").
  - Instantiate the set/default variant with figma.instantiate("1:2012", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Orientation`.
- Observed instances: 1
- Used on pages: DS · System
- Used in screens: DS · System / Doc/Atoms
- Observed property values:
  - `Orientation`: horizontal
- Instantiate:
```js
await figma.instantiate("1:2012", {
  parentId: screen.id,
  props: {
    "Orientation": "horizontal"
  },
});
```

### Atom/Avatar
- Type: COMPONENT_SET (DS · System/Atom/Avatar)
- Figma node ID: `1:2025`
- Figma component key: `eb421306d0855ebec3dc510b332db9e3f98f3ffb`
- Source page: DS · System
- Default variant ID: `1:2013`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Initials#1:28`: TEXT default=AB
  - `Size`: VARIANT default=sm options=sm, md, lg
  - `Type`: VARIANT default=initials options=initials, dot
- Variants:
  - Size=sm, Type=initials — id `1:2013`, key `6ad8077d7487952effafa871707866b4db81de16` (Size=sm, Type=initials)
  - Size=sm, Type=dot — id `1:2015`, key `d158d6bea2d8c00c11cad5d608b34ec49e2fe0b5` (Size=sm, Type=dot)
  - Size=md, Type=initials — id `1:2017`, key `5375154fa3c9ae30fe6c367330f955c6797d4a97` (Size=md, Type=initials)
  - Size=md, Type=dot — id `1:2019`, key `98dee94719038a3921a3cc094a8e84a3c6f43b00` (Size=md, Type=dot)
  - Size=lg, Type=initials — id `1:2021`, key `08e3437484f72db228ba16b26863ce25fb2493ee` (Size=lg, Type=initials)
  - Size=lg, Type=dot — id `1:2023`, key `148cf43da54a7ee80480feb51d2ae369c424f1aa` (Size=lg, Type=dot)
- Text layers:
  - `Atom/Avatar/Size=sm, Type=initials/Initials`: "AB" refs=characters=Initials#1:28 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Atom/Avatar/Size=md, Type=initials/Initials`: "AB" refs=characters=Initials#1:28 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Atom/Avatar/Size=lg, Type=initials/Initials`: "AB" refs=characters=Initials#1:28 constraints={"horizontal":"MIN","vertical":"MIN"}
- Usage:
  - Find it with figma.findComponent("Atom/Avatar").
  - Instantiate the set/default variant with figma.instantiate("1:2025", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Initials#1:28`, `Size`, `Type`.
- Observed instances: 7
- Used on pages: DS · System
- Used in screens: DS · System / Molecule/Display/ListItem, DS · System / Organism/Page/ListSection, DS · System / Organism/Navigation/Header, DS · System / Doc/Atoms, DS · System / Doc/Molecules
- Observed property values:
  - `Initials#1:28`: AB
  - `Size`: sm
  - `Type`: initials
- Instantiate:
```js
await figma.instantiate("1:2025", {
  parentId: screen.id,
  props: {
    "Initials#1:28": "AB",
    "Size": "sm",
    "Type": "initials"
  },
});
```

### Atom/Feedback/Progress
- Type: COMPONENT_SET (DS · System/Atom/Feedback/Progress)
- Figma node ID: `1:2032`
- Figma component key: `6a504ccf1fa05dccd9650a0c7623c33ef3a97707`
- Source page: DS · System
- Default variant ID: `1:2026`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Value`: VARIANT default=25 options=25, 50, 100
- Variants:
  - Value=25 — id `1:2026`, key `3432b5028e44ae6c68a74c8d018f69ec061f1a84` (Value=25)
  - Value=50 — id `1:2028`, key `e3ab20d1d3c80147f497bd75142a3b0a163abd2d` (Value=50)
  - Value=100 — id `1:2030`, key `faa3b3d7f2b07d41fcdfca7584f8440ccd12e024` (Value=100)
- Usage:
  - Find it with figma.findComponent("Atom/Feedback/Progress").
  - Instantiate the set/default variant with figma.instantiate("1:2032", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Value`.
- Observed instances: 1
- Used on pages: DS · System
- Used in screens: DS · System / Doc/Atoms
- Observed property values:
  - `Value`: 25
- Instantiate:
```js
await figma.instantiate("1:2032", {
  parentId: screen.id,
  props: {
    "Value": "25"
  },
});
```

### Atom/Feedback/Spinner
- Type: COMPONENT_SET (DS · System/Atom/Feedback/Spinner)
- Figma node ID: `1:2037`
- Figma component key: `cbe518a12bc2336ed2f228f3c5a1c458b3cf1b17`
- Source page: DS · System
- Default variant ID: `1:2033`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Size`: VARIANT default=sm options=sm, md
- Variants:
  - Size=sm — id `1:2033`, key `a5a523055a56604ff6449573c5a4779ba2675c3a` (Size=sm)
  - Size=md — id `1:2035`, key `8a84fd382526f150980a1d9046ac4cd128c9e254` (Size=md)
- Usage:
  - Find it with figma.findComponent("Atom/Feedback/Spinner").
  - Instantiate the set/default variant with figma.instantiate("1:2037", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Size`.
- Observed instances: 2
- Used on pages: DS · System
- Used in screens: DS · System / Molecule/Feedback/LoadingBlock, DS · System / Doc/Atoms
- Observed property values:
  - `Size`: md, sm
- Instantiate:
```js
await figma.instantiate("1:2037", {
  parentId: screen.id,
  props: {
    "Size": "sm"
  },
});
```

### Atom/Feedback/Skeleton
- Type: COMPONENT_SET (DS · System/Atom/Feedback/Skeleton)
- Figma node ID: `1:2047`
- Figma component key: `91c4a681e171160f785153e09cbccdc545fb5990`
- Source page: DS · System
- Default variant ID: `1:2038`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Variant`: VARIANT default=line options=line, block
- Variants:
  - Variant=line — id `1:2038`, key `19a715271a0e5c109cefdf2fcd44dace073cdd6a` (Variant=line)
  - Variant=block — id `1:2042`, key `ce74fc74628ce3abdab87cadf682cb40bc8bfcce` (Variant=block)
- Usage:
  - Find it with figma.findComponent("Atom/Feedback/Skeleton").
  - Instantiate the set/default variant with figma.instantiate("1:2047", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Variant`.
- Observed instances: 3
- Used on pages: DS · System
- Used in screens: DS · System / Organism/Page/SkeletonPage, DS · System / Doc/Atoms
- Observed property values:
  - `Variant`: block, line
- Instantiate:
```js
await figma.instantiate("1:2047", {
  parentId: screen.id,
  props: {
    "Variant": "line"
  },
});
```

### Atom/Status/Tag
- Type: COMPONENT_SET (DS · System/Atom/Status/Tag)
- Figma node ID: `1:2058`
- Figma component key: `29a391e729c604cf3e20809e4d321c4a0666d8cc`
- Source page: DS · System
- Default variant ID: `1:2048`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Label#1:35`: TEXT default=Neutral
  - `Tone`: VARIANT default=neutral options=neutral, success, warning, error, info
- Variants:
  - Tone=neutral — id `1:2048`, key `47044aa47b9b797e8e148b7ccacca32dd2a38ffa` (Tone=neutral)
  - Tone=success — id `1:2050`, key `9b680850949b7555224bf502db3b12eae4211625` (Tone=success)
  - Tone=warning — id `1:2052`, key `a50947963fc014bfe893d95530664213dc6ea3ae` (Tone=warning)
  - Tone=error — id `1:2054`, key `ef7aa5ca34d139a8f93a623cce58cd3e531cb76e` (Tone=error)
  - Tone=info — id `1:2056`, key `f29d240d7c1c07bfc6f4cafcb36966327a84b5be` (Tone=info)
- Text layers:
  - `Atom/Status/Tag/Tone=neutral/Label`: "Neutral" refs=characters=Label#1:35 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Atom/Status/Tag/Tone=success/Label`: "Neutral" refs=characters=Label#1:35 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Atom/Status/Tag/Tone=warning/Label`: "Neutral" refs=characters=Label#1:35 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Atom/Status/Tag/Tone=error/Label`: "Neutral" refs=characters=Label#1:35 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Atom/Status/Tag/Tone=info/Label`: "Neutral" refs=characters=Label#1:35 constraints={"horizontal":"MIN","vertical":"MIN"}
- Usage:
  - Find it with figma.findComponent("Atom/Status/Tag").
  - Instantiate the set/default variant with figma.instantiate("1:2058", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Label#1:35`, `Tone`.
- Observed instances: 1
- Used on pages: DS · System
- Used in screens: DS · System / Doc/Atoms
- Observed property values:
  - `Label#1:35`: Neutral
  - `Tone`: neutral
- Instantiate:
```js
await figma.instantiate("1:2058", {
  parentId: screen.id,
  props: {
    "Label#1:35": "Neutral",
    "Tone": "neutral"
  },
});
```

### Atom/Feedback/Tooltip
- Type: COMPONENT_SET (DS · System/Atom/Feedback/Tooltip)
- Figma node ID: `1:2063`
- Figma component key: `e8e1ffe0a426a5efc2fbcc1f37ad14ccd69bf3d8`
- Source page: DS · System
- Default variant ID: `1:2059`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Label#1:41`: TEXT default=Copied
  - `Variant`: VARIANT default=Default options=Default
- Variants:
  - Variant=Default — id `1:2059`, key `9dc2b6e132e10d0ca0a6e9a2593f0cbb795e4b0b` (Variant=Default)
- Usage:
  - Find it with figma.findComponent("Atom/Feedback/Tooltip").
  - Instantiate the set/default variant with figma.instantiate("1:2063", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Label#1:41`, `Variant`.
- Instantiate:
```js
await figma.instantiate("1:2063", {
  parentId: screen.id,
  props: {
    "Label#1:41": "Copied",
    "Variant": "Default"
  },
});
```

### Atom/Feedback/Kbd
- Type: COMPONENT_SET (DS · System/Atom/Feedback/Kbd)
- Figma node ID: `1:2066`
- Figma component key: `782fc04f16804b74d3f57e2fcdf59a40c5a60c5a`
- Source page: DS · System
- Default variant ID: `1:2064`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Key#1:43`: TEXT default=⌘K
  - `Variant`: VARIANT default=Default options=Default
- Variants:
  - Variant=Default — id `1:2064`, key `064047166f5c05313e8cb39dd2d94fec7bb6724e` (Variant=Default)
- Text layers:
  - `Atom/Feedback/Kbd/Variant=Default/Key`: "⌘K" refs=characters=Key#1:43 constraints={"horizontal":"MIN","vertical":"MIN"}
- Usage:
  - Find it with figma.findComponent("Atom/Feedback/Kbd").
  - Instantiate the set/default variant with figma.instantiate("1:2066", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Key#1:43`, `Variant`.
- Instantiate:
```js
await figma.instantiate("1:2066", {
  parentId: screen.id,
  props: {
    "Key#1:43": "⌘K",
    "Variant": "Default"
  },
});
```

### Atom/Feedback/Trend
- Type: COMPONENT_SET (DS · System/Atom/Feedback/Trend)
- Figma node ID: `1:2079`
- Figma component key: `3b2b2f2fa5f8f2910261ada65f2d81d0a4721ca3`
- Source page: DS · System
- Default variant ID: `1:2067`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Delta#1:45`: TEXT default=+12%
  - `Direction`: VARIANT default=up options=up, down
- Variants:
  - Direction=up — id `1:2067`, key `10ad8a91099ca8eeb527a287fb3df943d2a970d9` (Direction=up)
  - Direction=down — id `1:2073`, key `794b5f3150aceacad4968f0491dd88e7e5842fdf` (Direction=down)
- Text layers:
  - `Atom/Feedback/Trend/Direction=up/Delta`: "+12%" refs=characters=Delta#1:45 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Atom/Feedback/Trend/Direction=down/Delta`: "+12%" refs=characters=Delta#1:45 constraints={"horizontal":"MIN","vertical":"MIN"}
- Usage:
  - Find it with figma.findComponent("Atom/Feedback/Trend").
  - Instantiate the set/default variant with figma.instantiate("1:2079", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Delta#1:45`, `Direction`.
- Observed instances: 1
- Used on pages: DS · System
- Used in screens: DS · System / Doc/Atoms
- Observed property values:
  - `Delta#1:45`: +12%
  - `Direction`: up
- Instantiate:
```js
await figma.instantiate("1:2079", {
  parentId: screen.id,
  props: {
    "Delta#1:45": "+12%",
    "Direction": "up"
  },
});
```

### Molecule/Action/Button
- Type: COMPONENT_SET (DS · System/Molecule/Action/Button)
- Figma node ID: `1:2176`
- Figma component key: `ad42078363dd2dbfcbfe160f3dc56793e021d134`
- Source page: DS · System
- Default variant ID: `1:2080`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Label#1:48`: TEXT default=Button
  - `Variant`: VARIANT default=primary options=primary, secondary, ghost, danger
  - `Size`: VARIANT default=sm options=sm, md, lg
  - `State`: VARIANT default=default options=default, hover, pressed, disabled
- Variants:
  - Variant=primary, Size=sm, State=default — id `1:2080`, key `d606345661b0a14a295ffb6a2c53c4b564087683` (Variant=primary, Size=sm, State=default)
  - Variant=primary, Size=sm, State=hover — id `1:2082`, key `5cdb7cc071dd4112af4f9de9a4440c8cadc11e11` (Variant=primary, Size=sm, State=hover)
  - Variant=primary, Size=sm, State=pressed — id `1:2084`, key `854bd1866dbc406b37a23ac44048999bfe502ffb` (Variant=primary, Size=sm, State=pressed)
  - Variant=primary, Size=sm, State=disabled — id `1:2086`, key `9de201687dcd1d730a4b12e1bb89d0adec3e9e22` (Variant=primary, Size=sm, State=disabled)
  - Variant=primary, Size=md, State=default — id `1:2088`, key `6315a3b600df2abd6970f23b9f096146e16c1ca0` (Variant=primary, Size=md, State=default)
  - Variant=primary, Size=md, State=hover — id `1:2090`, key `bcf48adcd761e8b3392b106700cb003be97da1f4` (Variant=primary, Size=md, State=hover)
  - Variant=primary, Size=md, State=pressed — id `1:2092`, key `10770f08a86f8bfc88096ea8f0be9aa40c34f47a` (Variant=primary, Size=md, State=pressed)
  - Variant=primary, Size=md, State=disabled — id `1:2094`, key `bc18707270e01957f51b36910333847f284687f0` (Variant=primary, Size=md, State=disabled)
  - Variant=primary, Size=lg, State=default — id `1:2096`, key `2f81ffaa42b84339b5a858a54bd0b1a8167ecba5` (Variant=primary, Size=lg, State=default)
  - Variant=primary, Size=lg, State=hover — id `1:2098`, key `25127630a3f582b017c44e38266c9c5505334707` (Variant=primary, Size=lg, State=hover)
  - Variant=primary, Size=lg, State=pressed — id `1:2100`, key `bf2cb961ea0dbfc50e7659e670c1e36075d41dfc` (Variant=primary, Size=lg, State=pressed)
  - Variant=primary, Size=lg, State=disabled — id `1:2102`, key `4fc9581959fc10023173e22cea803bdf3c7ac845` (Variant=primary, Size=lg, State=disabled)
  - Variant=secondary, Size=sm, State=default — id `1:2104`, key `8a2e51841e28ebd16cb56a4c6bbf9f3d93e8cb67` (Variant=secondary, Size=sm, State=default)
  - Variant=secondary, Size=sm, State=hover — id `1:2106`, key `a971813b26e7acf3d30fcfa6bbd08f72623e551f` (Variant=secondary, Size=sm, State=hover)
  - Variant=secondary, Size=sm, State=pressed — id `1:2108`, key `513c0fc118bc03427ab5f61d07543aba7c725cde` (Variant=secondary, Size=sm, State=pressed)
  - Variant=secondary, Size=sm, State=disabled — id `1:2110`, key `49f5eef72ff946c5996f24af28503ed33d9459db` (Variant=secondary, Size=sm, State=disabled)
  - Variant=secondary, Size=md, State=default — id `1:2112`, key `a2f802f1754f9318851a74c3c5967ba1221f1764` (Variant=secondary, Size=md, State=default)
  - Variant=secondary, Size=md, State=hover — id `1:2114`, key `f0af3f79872d281d9fda7d73e995c9e78d660b25` (Variant=secondary, Size=md, State=hover)
  - Variant=secondary, Size=md, State=pressed — id `1:2116`, key `45b374fb8ba0a45fbac241274156cef0791dd3c5` (Variant=secondary, Size=md, State=pressed)
  - Variant=secondary, Size=md, State=disabled — id `1:2118`, key `68dc98bc3f2fedb6b9f06f5afe7d2026c4a644e8` (Variant=secondary, Size=md, State=disabled)
  - Variant=secondary, Size=lg, State=default — id `1:2120`, key `0bcf8c31b3e7f7ea745ec70d87218cd110b89fe7` (Variant=secondary, Size=lg, State=default)
  - Variant=secondary, Size=lg, State=hover — id `1:2122`, key `067f9342cadfc31b41dce15c9fc6a26227394015` (Variant=secondary, Size=lg, State=hover)
  - Variant=secondary, Size=lg, State=pressed — id `1:2124`, key `579957d0a83724e433dc05aefd0e971a35be00b6` (Variant=secondary, Size=lg, State=pressed)
  - Variant=secondary, Size=lg, State=disabled — id `1:2126`, key `517dd6857e49eef0f9b5808055d292dcf74af632` (Variant=secondary, Size=lg, State=disabled)
  - Variant=ghost, Size=sm, State=default — id `1:2128`, key `cf4257724d93f15f7c883b199461b19d9c3ea9e4` (Variant=ghost, Size=sm, State=default)
  - Variant=ghost, Size=sm, State=hover — id `1:2130`, key `a09da4cc6c2244585218a98cbc5ba699f05e3ec5` (Variant=ghost, Size=sm, State=hover)
  - Variant=ghost, Size=sm, State=pressed — id `1:2132`, key `adf1ab8e4302bc3d020cb72460186b5592ce5d3f` (Variant=ghost, Size=sm, State=pressed)
  - Variant=ghost, Size=sm, State=disabled — id `1:2134`, key `d63fe09dd71e5edd1d55674a9169652479f02270` (Variant=ghost, Size=sm, State=disabled)
  - Variant=ghost, Size=md, State=default — id `1:2136`, key `7aa682c852e23e9d13a4ab5d85761656e099fc6a` (Variant=ghost, Size=md, State=default)
  - Variant=ghost, Size=md, State=hover — id `1:2138`, key `a220de7d3b89ce8913e1bd6d2e0ada1a3a8a4a01` (Variant=ghost, Size=md, State=hover)
  - Variant=ghost, Size=md, State=pressed — id `1:2140`, key `4b7d9b149dffa73749c5eb20f1d5471e2a3ad6a1` (Variant=ghost, Size=md, State=pressed)
  - Variant=ghost, Size=md, State=disabled — id `1:2142`, key `1c406a8772ff71438845b9ea6bd6bfe222c4c8d1` (Variant=ghost, Size=md, State=disabled)
  - Variant=ghost, Size=lg, State=default — id `1:2144`, key `32c4f98c1463fa824594322fbd73c3d317d99dfe` (Variant=ghost, Size=lg, State=default)
  - Variant=ghost, Size=lg, State=hover — id `1:2146`, key `903bec9983c024858c8d0b7b7e01cfa8ef3ad29f` (Variant=ghost, Size=lg, State=hover)
  - Variant=ghost, Size=lg, State=pressed — id `1:2148`, key `e98d94edf7ae2ce50a0cde3d22713c1b38ea277b` (Variant=ghost, Size=lg, State=pressed)
  - Variant=ghost, Size=lg, State=disabled — id `1:2150`, key `f4888c54b6b8d6d1caeaa58caa7e467c587d17c0` (Variant=ghost, Size=lg, State=disabled)
  - Variant=danger, Size=sm, State=default — id `1:2152`, key `9a55759dfdf641007e8b788367fb034c6572148c` (Variant=danger, Size=sm, State=default)
  - Variant=danger, Size=sm, State=hover — id `1:2154`, key `82b29a2904cf1d1de5bbf11e7e5cef41b2eb174c` (Variant=danger, Size=sm, State=hover)
  - Variant=danger, Size=sm, State=pressed — id `1:2156`, key `b3b11de2b54a25cc43cd2d719ccf89c1bdcc2359` (Variant=danger, Size=sm, State=pressed)
  - Variant=danger, Size=sm, State=disabled — id `1:2158`, key `93d3071ac35aaef1e72616f7db9e45c87e9eba21` (Variant=danger, Size=sm, State=disabled)
  - Variant=danger, Size=md, State=default — id `1:2160`, key `b9c634a6dfb9bc807434995bd6dadf62f8282ec8` (Variant=danger, Size=md, State=default)
  - Variant=danger, Size=md, State=hover — id `1:2162`, key `fbd8d8b04e5cecf0b99366fbe4e6aaeb642159e0` (Variant=danger, Size=md, State=hover)
  - Variant=danger, Size=md, State=pressed — id `1:2164`, key `bf50ab5fbb73b2e95856ced72b4782b52cb8bfc8` (Variant=danger, Size=md, State=pressed)
  - Variant=danger, Size=md, State=disabled — id `1:2166`, key `04441d8eb72bc8a2fdfd31f4885f8c325e3991ac` (Variant=danger, Size=md, State=disabled)
  - Variant=danger, Size=lg, State=default — id `1:2168`, key `c785bd32f825831daf828eeb115bf99dad7f9cc2` (Variant=danger, Size=lg, State=default)
  - Variant=danger, Size=lg, State=hover — id `1:2170`, key `a657d0dd473b3d9ac06eaba6eb26fcf03b18ae31` (Variant=danger, Size=lg, State=hover)
  - Variant=danger, Size=lg, State=pressed — id `1:2172`, key `61d64956def9865c588b36b77dd4a365510c0708` (Variant=danger, Size=lg, State=pressed)
  - Variant=danger, Size=lg, State=disabled — id `1:2174`, key `0a54da1821fb2620d0fc454c0ea164d0435af1d4` (Variant=danger, Size=lg, State=disabled)
- Text layers:
  - `Molecule/Action/Button/Variant=primary, Size=sm, State=default/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=primary, Size=sm, State=hover/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=primary, Size=sm, State=pressed/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=primary, Size=sm, State=disabled/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=primary, Size=md, State=default/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=primary, Size=md, State=hover/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=primary, Size=md, State=pressed/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=primary, Size=md, State=disabled/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=primary, Size=lg, State=default/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=primary, Size=lg, State=hover/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=primary, Size=lg, State=pressed/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=primary, Size=lg, State=disabled/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=secondary, Size=sm, State=default/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=secondary, Size=sm, State=hover/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=secondary, Size=sm, State=pressed/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=secondary, Size=sm, State=disabled/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=secondary, Size=md, State=default/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=secondary, Size=md, State=hover/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=secondary, Size=md, State=pressed/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=secondary, Size=md, State=disabled/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=secondary, Size=lg, State=default/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=secondary, Size=lg, State=hover/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=secondary, Size=lg, State=pressed/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=secondary, Size=lg, State=disabled/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=ghost, Size=sm, State=default/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=ghost, Size=sm, State=hover/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=ghost, Size=sm, State=pressed/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=ghost, Size=sm, State=disabled/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=ghost, Size=md, State=default/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=ghost, Size=md, State=hover/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=ghost, Size=md, State=pressed/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=ghost, Size=md, State=disabled/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=ghost, Size=lg, State=default/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=ghost, Size=lg, State=hover/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=ghost, Size=lg, State=pressed/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=ghost, Size=lg, State=disabled/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=danger, Size=sm, State=default/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=danger, Size=sm, State=hover/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=danger, Size=sm, State=pressed/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=danger, Size=sm, State=disabled/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=danger, Size=md, State=default/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=danger, Size=md, State=hover/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=danger, Size=md, State=pressed/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=danger, Size=md, State=disabled/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=danger, Size=lg, State=default/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=danger, Size=lg, State=hover/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=danger, Size=lg, State=pressed/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Action/Button/Variant=danger, Size=lg, State=disabled/Label`: "Button" refs=characters=Label#1:48 constraints={"horizontal":"MIN","vertical":"MIN"}
- Usage:
  - Find it with figma.findComponent("Molecule/Action/Button").
  - Instantiate the set/default variant with figma.instantiate("1:2176", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Label#1:48`, `Variant`, `Size`, `State`.
- Observed instances: 9
- Used on pages: DS · System
- Used in screens: DS · System / Molecule/Feedback/EmptyState, DS · System / Organism/Overlay/Dialog, DS · System / Organism/Page/EmptyPage, DS · System / Doc/Molecules, DS · System / Doc/Organisms
- Observed property values:
  - `Label#1:48`: Button
  - `Variant`: primary, ghost, danger
  - `Size`: md, sm
  - `State`: default
- Instantiate:
```js
await figma.instantiate("1:2176", {
  parentId: screen.id,
  props: {
    "Label#1:48": "Button",
    "Variant": "primary",
    "Size": "sm",
    "State": "default"
  },
});
```

### Molecule/Input/TextField
- Type: COMPONENT_SET (DS · System/Molecule/Input/TextField)
- Figma node ID: `1:2217`
- Figma component key: `f8bd9319b78dc9ee54bf24c0718a19a6afca8d4b`
- Source page: DS · System
- Default variant ID: `1:2177`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Label#1:97`: BOOLEAN default=true
  - `Helper#1:106`: BOOLEAN default=true
  - `Label text#1:115`: TEXT default=Label
  - `Value#1:124`: TEXT default=Enter text...
  - `Helper text#1:133`: TEXT default=Helper text
  - `State`: VARIANT default=default options=default, focus, error, disabled
  - `Size`: VARIANT default=md options=md, lg
- Variants:
  - State=default, Size=md — id `1:2177`, key `6bbe2750c321574afdd83e6b4e8d07dbad0be8a6` (State=default, Size=md)
  - State=default, Size=lg — id `1:2182`, key `aacafea5564c58b456b627953c58c674d5132cf1` (State=default, Size=lg)
  - State=focus, Size=md — id `1:2187`, key `a098cded66bef739d9839ed1e9729d042605ef4e` (State=focus, Size=md)
  - State=focus, Size=lg — id `1:2192`, key `08b4d60579e0d6d11d94114ea447480b45a12caf` (State=focus, Size=lg)
  - State=error, Size=md — id `1:2197`, key `eda62e5df810d3f0dae9bfca2a246a3f12f7e5fe` (State=error, Size=md)
  - State=error, Size=lg — id `1:2202`, key `a3288c71dcdf16cf164f21cb744c4f40a0283a18` (State=error, Size=lg)
  - State=disabled, Size=md — id `1:2207`, key `5ceb662dc3bfa069fe65552cd75a494415095e96` (State=disabled, Size=md)
  - State=disabled, Size=lg — id `1:2212`, key `e4737719af49e11dd914cd3138bfabbea482dc38` (State=disabled, Size=lg)
- Text layers:
  - `Molecule/Input/TextField/State=default, Size=md/Label`: "Label" refs=visible=Label#1:97, characters=Label text#1:115 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/TextField/State=default, Size=md/Helper`: "Helper text" refs=visible=Helper#1:106, characters=Helper text#1:133 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/TextField/State=default, Size=lg/Label`: "Label" refs=visible=Label#1:97, characters=Label text#1:115 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/TextField/State=default, Size=lg/Helper`: "Helper text" refs=visible=Helper#1:106, characters=Helper text#1:133 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/TextField/State=focus, Size=md/Label`: "Label" refs=visible=Label#1:97, characters=Label text#1:115 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/TextField/State=focus, Size=md/Helper`: "Helper text" refs=visible=Helper#1:106, characters=Helper text#1:133 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/TextField/State=focus, Size=lg/Label`: "Label" refs=visible=Label#1:97, characters=Label text#1:115 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/TextField/State=focus, Size=lg/Helper`: "Helper text" refs=visible=Helper#1:106, characters=Helper text#1:133 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/TextField/State=error, Size=md/Label`: "Label" refs=visible=Label#1:97, characters=Label text#1:115 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/TextField/State=error, Size=md/Helper`: "Helper text" refs=visible=Helper#1:106, characters=Helper text#1:133 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/TextField/State=error, Size=lg/Label`: "Label" refs=visible=Label#1:97, characters=Label text#1:115 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/TextField/State=error, Size=lg/Helper`: "Helper text" refs=visible=Helper#1:106, characters=Helper text#1:133 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/TextField/State=disabled, Size=md/Label`: "Label" refs=visible=Label#1:97, characters=Label text#1:115 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/TextField/State=disabled, Size=md/Helper`: "Helper text" refs=visible=Helper#1:106, characters=Helper text#1:133 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/TextField/State=disabled, Size=lg/Label`: "Label" refs=visible=Label#1:97, characters=Label text#1:115 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/TextField/State=disabled, Size=lg/Helper`: "Helper text" refs=visible=Helper#1:106, characters=Helper text#1:133 constraints={"horizontal":"MIN","vertical":"MIN"}
- Usage:
  - Find it with figma.findComponent("Molecule/Input/TextField").
  - Instantiate the set/default variant with figma.instantiate("1:2217", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Label#1:97`, `Helper#1:106`, `Label text#1:115`, `Value#1:124`, `Helper text#1:133`, `State`, `Size`.
- Observed instances: 3
- Used on pages: DS · System
- Used in screens: DS · System / Organism/Page/FormSection, DS · System / Doc/Molecules
- Observed property values:
  - `Helper text#1:133`: Helper text
  - `Label text#1:115`: Label
  - `Helper#1:106`: true
  - `Value#1:124`: Enter text...
  - `Label#1:97`: true
  - `State`: default
  - `Size`: md
- Instantiate:
```js
await figma.instantiate("1:2217", {
  parentId: screen.id,
  props: {
    "Label#1:97": true,
    "Helper#1:106": true,
    "Label text#1:115": "Label",
    "Value#1:124": "Enter text...",
    "Helper text#1:133": "Helper text",
    "State": "default",
    "Size": "md"
  },
});
```

### Molecule/Display/Card
- Type: COMPONENT_SET (DS · System/Molecule/Display/Card)
- Figma node ID: `1:2227`
- Figma component key: `b967fd3aa160b9dd26f8f335588ac135f41126ec`
- Source page: DS · System
- Default variant ID: `1:2218`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Title#1:142`: TEXT default=Card Title
  - `Body#1:146`: TEXT default=Card description text goes here with supporting details.
  - `Variant`: VARIANT default=elevated options=elevated, outlined, filled
- Variants:
  - Variant=elevated — id `1:2218`, key `a8b5d8a22c39b073756c0e84d9c1acfbcf0431df` (Variant=elevated)
  - Variant=outlined — id `1:2221`, key `73d082064a7802cc049e2b3d34791161626fbbe7` (Variant=outlined)
  - Variant=filled — id `1:2224`, key `9595c024e6de06027d37662ab12216b0909d302f` (Variant=filled)
- Text layers:
  - `Molecule/Display/Card/Variant=elevated/Title`: "Card Title" refs=characters=Title#1:142 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Display/Card/Variant=elevated/Body`: "Card description text goes here with supporting details." refs=characters=Body#1:146 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Display/Card/Variant=outlined/Title`: "Card Title" refs=characters=Title#1:142 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Display/Card/Variant=outlined/Body`: "Card description text goes here with supporting details." refs=characters=Body#1:146 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Display/Card/Variant=filled/Title`: "Card Title" refs=characters=Title#1:142 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Display/Card/Variant=filled/Body`: "Card description text goes here with supporting details." refs=characters=Body#1:146 constraints={"horizontal":"MIN","vertical":"MIN"}
- Usage:
  - Find it with figma.findComponent("Molecule/Display/Card").
  - Instantiate the set/default variant with figma.instantiate("1:2227", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Title#1:142`, `Body#1:146`, `Variant`.
- Observed instances: 1
- Used on pages: DS · System
- Used in screens: DS · System / Doc/Molecules
- Observed property values:
  - `Body#1:146`: Card description text goes here with supporting details.
  - `Title#1:142`: Card Title
  - `Variant`: outlined
- Instantiate:
```js
await figma.instantiate("1:2227", {
  parentId: screen.id,
  props: {
    "Title#1:142": "Card Title",
    "Body#1:146": "Card description text goes here with supporting details.",
    "Variant": "elevated"
  },
});
```

### Molecule/Feedback/Alert
- Type: COMPONENT_SET (DS · System/Molecule/Feedback/Alert)
- Figma node ID: `1:2252`
- Figma component key: `1cb28c1669a7a161912f49c8fd5c937ad5ea1eeb`
- Source page: DS · System
- Default variant ID: `1:2228`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Title#1:150`: TEXT default=Alert title
  - `Body#1:155`: TEXT default=Supporting message explaining what happened.
  - `Tone`: VARIANT default=info options=info, success, warning, error
- Variants:
  - Tone=info — id `1:2228`, key `98214eff712e4579e53c5649b8b72bc653ea1b30` (Tone=info)
  - Tone=success — id `1:2234`, key `ad1638c0051bcb308e90339da7fb5e2d6eb41096` (Tone=success)
  - Tone=warning — id `1:2240`, key `ac31ca9ca0f650e64b7d96b259d27c669b0c2008` (Tone=warning)
  - Tone=error — id `1:2246`, key `9fd42b7cd5fc90a2a45cf3cc80633c8acb2040bd` (Tone=error)
- Usage:
  - Find it with figma.findComponent("Molecule/Feedback/Alert").
  - Instantiate the set/default variant with figma.instantiate("1:2252", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Title#1:150`, `Body#1:155`, `Tone`.
- Observed instances: 1
- Used on pages: DS · System
- Used in screens: DS · System / Doc/Molecules
- Observed property values:
  - `Body#1:155`: Supporting message explaining what happened.
  - `Title#1:150`: Alert title
  - `Tone`: info
- Instantiate:
```js
await figma.instantiate("1:2252", {
  parentId: screen.id,
  props: {
    "Title#1:150": "Alert title",
    "Body#1:155": "Supporting message explaining what happened.",
    "Tone": "info"
  },
});
```

### Molecule/Action/IconButton
- Type: COMPONENT_SET (DS · System/Molecule/Action/IconButton)
- Figma node ID: `1:2373`
- Figma component key: `3f31a29d77035dc6dfc61bd7e9282ae6e8760d22`
- Source page: DS · System
- Default variant ID: `1:2253`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Variant`: VARIANT default=primary options=primary, secondary, ghost
  - `Size`: VARIANT default=md options=md, lg
  - `State`: VARIANT default=default options=default, hover, pressed, disabled
- Variants:
  - Variant=primary, Size=md, State=default — id `1:2253`, key `761a6688f120f952f8c4534c8fb6a0dc24a9d1bf` (Variant=primary, Size=md, State=default)
  - Variant=primary, Size=md, State=hover — id `1:2258`, key `c0f9b62ae683e03eec3521f61c65d205cc4161b1` (Variant=primary, Size=md, State=hover)
  - Variant=primary, Size=md, State=pressed — id `1:2263`, key `e6931e8260a5746181677d65af7e29e8ce70a982` (Variant=primary, Size=md, State=pressed)
  - Variant=primary, Size=md, State=disabled — id `1:2268`, key `c2b5234e2d39fea100a2edf48a5301e1f6c91034` (Variant=primary, Size=md, State=disabled)
  - Variant=primary, Size=lg, State=default — id `1:2273`, key `973816c55647b859a7dd4cbccf7274600e1b25e9` (Variant=primary, Size=lg, State=default)
  - Variant=primary, Size=lg, State=hover — id `1:2278`, key `d3105c4d0476f2b1b5cfe87f5345622361e2a301` (Variant=primary, Size=lg, State=hover)
  - Variant=primary, Size=lg, State=pressed — id `1:2283`, key `ba4e1779a56764b7b43e6ad046e8db39a26728a8` (Variant=primary, Size=lg, State=pressed)
  - Variant=primary, Size=lg, State=disabled — id `1:2288`, key `690162e054f8d906d888edea5c819aa6aa7278f6` (Variant=primary, Size=lg, State=disabled)
  - Variant=secondary, Size=md, State=default — id `1:2293`, key `f12b1f5ff70002210133819dc060c2e1fe786565` (Variant=secondary, Size=md, State=default)
  - Variant=secondary, Size=md, State=hover — id `1:2298`, key `df49a7686193344c5071c559487618de20343092` (Variant=secondary, Size=md, State=hover)
  - Variant=secondary, Size=md, State=pressed — id `1:2303`, key `f3881340852ac4dcc34666c9738c8af56394e886` (Variant=secondary, Size=md, State=pressed)
  - Variant=secondary, Size=md, State=disabled — id `1:2308`, key `99cfe90b41475714965de1dfb5792f321b409b94` (Variant=secondary, Size=md, State=disabled)
  - Variant=secondary, Size=lg, State=default — id `1:2313`, key `617de3e4e50c1e9e27c30411821d8af26034fc1a` (Variant=secondary, Size=lg, State=default)
  - Variant=secondary, Size=lg, State=hover — id `1:2318`, key `001ede523b98f792f2c28cf78659c92845e64c13` (Variant=secondary, Size=lg, State=hover)
  - Variant=secondary, Size=lg, State=pressed — id `1:2323`, key `b9ce91ed9b976f946c3bd6cfe19a1073dfd3066f` (Variant=secondary, Size=lg, State=pressed)
  - Variant=secondary, Size=lg, State=disabled — id `1:2328`, key `0fb0263ee47daa3549c7c43c97491caf4b07a855` (Variant=secondary, Size=lg, State=disabled)
  - Variant=ghost, Size=md, State=default — id `1:2333`, key `3d2d4e54ba72e21437d9a9119662652a26512c1d` (Variant=ghost, Size=md, State=default)
  - Variant=ghost, Size=md, State=hover — id `1:2338`, key `5331d59910f563ff88048a97a2fb06ac19ed422c` (Variant=ghost, Size=md, State=hover)
  - Variant=ghost, Size=md, State=pressed — id `1:2343`, key `6d10eb35a30b74981a7dd5f74cef6f852a4d057d` (Variant=ghost, Size=md, State=pressed)
  - Variant=ghost, Size=md, State=disabled — id `1:2348`, key `4a94e5ce062885f31a8507815b72ec5f88c06b83` (Variant=ghost, Size=md, State=disabled)
  - Variant=ghost, Size=lg, State=default — id `1:2353`, key `0efa7e5ddc15dd25e7a952cb85bc8ddf6575856d` (Variant=ghost, Size=lg, State=default)
  - Variant=ghost, Size=lg, State=hover — id `1:2358`, key `943ef902124646b9807ad3a387430744009ad836` (Variant=ghost, Size=lg, State=hover)
  - Variant=ghost, Size=lg, State=pressed — id `1:2363`, key `2bd15d6c13b0dfb6631698611afc466d8f9a397b` (Variant=ghost, Size=lg, State=pressed)
  - Variant=ghost, Size=lg, State=disabled — id `1:2368`, key `1b8eaa7b61d4fc018165064a3528c497b54d0753` (Variant=ghost, Size=lg, State=disabled)
- Usage:
  - Find it with figma.findComponent("Molecule/Action/IconButton").
  - Instantiate the set/default variant with figma.instantiate("1:2373", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Variant`, `Size`, `State`.
- Observed instances: 1
- Used on pages: DS · System
- Used in screens: DS · System / Doc/Molecules
- Observed property values:
  - `Variant`: primary
  - `Size`: md
  - `State`: default
- Instantiate:
```js
await figma.instantiate("1:2373", {
  parentId: screen.id,
  props: {
    "Variant": "primary",
    "Size": "md",
    "State": "default"
  },
});
```

### Molecule/Action/Segmented
- Type: COMPONENT_SET (DS · System/Molecule/Action/Segmented)
- Figma node ID: `1:2395`
- Figma component key: `ef950003b7a2293dfe9b9f5fe050eeb9718b810d`
- Source page: DS · System
- Default variant ID: `1:2374`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Label 1#1:160`: TEXT default=Day
  - `Label 2#1:164`: TEXT default=Week
  - `Label 3#1:168`: TEXT default=Month
  - `Selected`: VARIANT default=day options=day, week, month
- Variants:
  - Selected=day — id `1:2374`, key `b103185e2aaf407a6375f4de60bcd7c4a46e2f8f` (Selected=day)
  - Selected=week — id `1:2381`, key `9c3d4261164e3dfdc3d1bfadd550d060266a197a` (Selected=week)
  - Selected=month — id `1:2388`, key `7379d41f12a54a87206423cea56a0f00ae666adb` (Selected=month)
- Usage:
  - Find it with figma.findComponent("Molecule/Action/Segmented").
  - Instantiate the set/default variant with figma.instantiate("1:2395", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Label 1#1:160`, `Label 2#1:164`, `Label 3#1:168`, `Selected`.
- Observed instances: 1
- Used on pages: DS · System
- Used in screens: DS · System / Doc/Molecules
- Observed property values:
  - `Label 3#1:168`: Month
  - `Label 2#1:164`: Week
  - `Label 1#1:160`: Day
  - `Selected`: day
- Instantiate:
```js
await figma.instantiate("1:2395", {
  parentId: screen.id,
  props: {
    "Label 1#1:160": "Day",
    "Label 2#1:164": "Week",
    "Label 3#1:168": "Month",
    "Selected": "day"
  },
});
```

### Molecule/Input/Checkbox
- Type: COMPONENT_SET (DS · System/Molecule/Input/Checkbox)
- Figma node ID: `1:2410`
- Figma component key: `b87221db75ead4ad4c12ce015e1a9706b9c6e164`
- Source page: DS · System
- Default variant ID: `1:2396`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Label#1:172`: TEXT default=Remember me
  - `Checked`: VARIANT default=off options=off, on
  - `State`: VARIANT default=default options=default, disabled
- Variants:
  - Checked=off, State=default — id `1:2396`, key `109560c5769d99cb1f19055bd0a4667001f56dda` (Checked=off, State=default)
  - Checked=off, State=disabled — id `1:2399`, key `9eb2327ee76e6dea0d618ca87462eebfd82f2ce8` (Checked=off, State=disabled)
  - Checked=on, State=default — id `1:2402`, key `2c62cd0e113fc97280df64ed2e5007f1e15522e9` (Checked=on, State=default)
  - Checked=on, State=disabled — id `1:2406`, key `3dfe9a2e32c0779b916ee7a989c3ff2f2ceba8ca` (Checked=on, State=disabled)
- Text layers:
  - `Molecule/Input/Checkbox/Checked=off, State=default/Label`: "Remember me" refs=characters=Label#1:172 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/Checkbox/Checked=off, State=disabled/Label`: "Remember me" refs=characters=Label#1:172 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/Checkbox/Checked=on, State=default/Label`: "Remember me" refs=characters=Label#1:172 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/Checkbox/Checked=on, State=disabled/Label`: "Remember me" refs=characters=Label#1:172 constraints={"horizontal":"MIN","vertical":"MIN"}
- Usage:
  - Find it with figma.findComponent("Molecule/Input/Checkbox").
  - Instantiate the set/default variant with figma.instantiate("1:2410", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Label#1:172`, `Checked`, `State`.
- Observed instances: 2
- Used on pages: DS · System
- Used in screens: DS · System / Organism/Page/SettingsGroup, DS · System / Doc/Molecules
- Observed property values:
  - `Label#1:172`: Remember me
  - `Checked`: off
  - `State`: default
- Instantiate:
```js
await figma.instantiate("1:2410", {
  parentId: screen.id,
  props: {
    "Label#1:172": "Remember me",
    "Checked": "off",
    "State": "default"
  },
});
```

### Molecule/Input/Radio
- Type: COMPONENT_SET (DS · System/Molecule/Input/Radio)
- Figma node ID: `1:2425`
- Figma component key: `7bd07ed4eac226b813618db92944a57849c889d9`
- Source page: DS · System
- Default variant ID: `1:2411`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Label#1:177`: TEXT default=Email me
  - `Selected`: VARIANT default=off options=off, on
  - `State`: VARIANT default=default options=default, disabled
- Variants:
  - Selected=off, State=default — id `1:2411`, key `60abb269d345facfcf5420261cbde71237a05bf8` (Selected=off, State=default)
  - Selected=off, State=disabled — id `1:2414`, key `451ca40194f4cfbf88ff0a945718cb1056bafbd4` (Selected=off, State=disabled)
  - Selected=on, State=default — id `1:2417`, key `5bd0d39d1b64b1f9b8c9bf8444e93750c75c74d6` (Selected=on, State=default)
  - Selected=on, State=disabled — id `1:2421`, key `c59d3e347fd5f27ae0ab1160f43b801e1ee65a0e` (Selected=on, State=disabled)
- Text layers:
  - `Molecule/Input/Radio/Selected=off, State=default/Label`: "Email me" refs=characters=Label#1:177 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/Radio/Selected=off, State=disabled/Label`: "Email me" refs=characters=Label#1:177 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/Radio/Selected=on, State=default/Label`: "Email me" refs=characters=Label#1:177 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/Radio/Selected=on, State=disabled/Label`: "Email me" refs=characters=Label#1:177 constraints={"horizontal":"MIN","vertical":"MIN"}
- Usage:
  - Find it with figma.findComponent("Molecule/Input/Radio").
  - Instantiate the set/default variant with figma.instantiate("1:2425", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Label#1:177`, `Selected`, `State`.
- Observed instances: 1
- Used on pages: DS · System
- Used in screens: DS · System / Doc/Molecules
- Observed property values:
  - `Label#1:177`: Email me
  - `Selected`: off
  - `State`: default
- Instantiate:
```js
await figma.instantiate("1:2425", {
  parentId: screen.id,
  props: {
    "Label#1:177": "Email me",
    "Selected": "off",
    "State": "default"
  },
});
```

### Molecule/Input/Switch
- Type: COMPONENT_SET (DS · System/Molecule/Input/Switch)
- Figma node ID: `1:2442`
- Figma component key: `cd05032c21f55c34e8b5b32be23d8699573d11c4`
- Source page: DS · System
- Default variant ID: `1:2426`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Label#1:182`: TEXT default=Notifications
  - `Checked`: VARIANT default=off options=off, on
  - `State`: VARIANT default=default options=default, disabled
- Variants:
  - Checked=off, State=default — id `1:2426`, key `d6e3b85edbec47a424daafe5fe3a44f365661ab5` (Checked=off, State=default)
  - Checked=off, State=disabled — id `1:2430`, key `e8fe77443cf5c534998d9fbfe2f4c4c23fa38d61` (Checked=off, State=disabled)
  - Checked=on, State=default — id `1:2434`, key `c7329896fcb933f87cf8f62e2bcd60f10c9f0ff9` (Checked=on, State=default)
  - Checked=on, State=disabled — id `1:2438`, key `5e33cdc235e05255282e21b573655fd5fed32170` (Checked=on, State=disabled)
- Text layers:
  - `Molecule/Input/Switch/Checked=off, State=default/Label`: "Notifications" refs=characters=Label#1:182 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/Switch/Checked=off, State=disabled/Label`: "Notifications" refs=characters=Label#1:182 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/Switch/Checked=on, State=default/Label`: "Notifications" refs=characters=Label#1:182 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/Switch/Checked=on, State=disabled/Label`: "Notifications" refs=characters=Label#1:182 constraints={"horizontal":"MIN","vertical":"MIN"}
- Usage:
  - Find it with figma.findComponent("Molecule/Input/Switch").
  - Instantiate the set/default variant with figma.instantiate("1:2442", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Label#1:182`, `Checked`, `State`.
- Observed instances: 2
- Used on pages: DS · System
- Used in screens: DS · System / Organism/Page/SettingsGroup, DS · System / Doc/Molecules
- Observed property values:
  - `Label#1:182`: Notifications
  - `Checked`: on, off
  - `State`: default
- Instantiate:
```js
await figma.instantiate("1:2442", {
  parentId: screen.id,
  props: {
    "Label#1:182": "Notifications",
    "Checked": "off",
    "State": "default"
  },
});
```

### Molecule/Input/SearchField
- Type: COMPONENT_SET (DS · System/Molecule/Input/SearchField)
- Figma node ID: `1:2458`
- Figma component key: `6926bbd9e81ab8ac6feb6903590047e1e5ec7d71`
- Source page: DS · System
- Default variant ID: `1:2443`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Value#1:187`: TEXT default=Search…
  - `State`: VARIANT default=default options=default, focus, disabled
- Variants:
  - State=default — id `1:2443`, key `9d51f61d239b2577c666f43f7246dd38c312fb14` (State=default)
  - State=focus — id `1:2448`, key `37f2470226a04c75652a6ebf6564a90de06ec8ef` (State=focus)
  - State=disabled — id `1:2453`, key `9a190f284502ec1e7fb751761a92b39a8137c460` (State=disabled)
- Text layers:
  - `Molecule/Input/SearchField/State=default/Value`: "Search…" refs=characters=Value#1:187 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/SearchField/State=focus/Value`: "Search…" refs=characters=Value#1:187 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/SearchField/State=disabled/Value`: "Search…" refs=characters=Value#1:187 constraints={"horizontal":"MIN","vertical":"MIN"}
- Usage:
  - Find it with figma.findComponent("Molecule/Input/SearchField").
  - Instantiate the set/default variant with figma.instantiate("1:2458", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Value#1:187`, `State`.
- Observed instances: 2
- Used on pages: DS · System
- Used in screens: DS · System / Molecule/Input/SearchFilter, DS · System / Doc/Molecules
- Observed property values:
  - `Value#1:187`: Search…
  - `State`: default
- Instantiate:
```js
await figma.instantiate("1:2458", {
  parentId: screen.id,
  props: {
    "Value#1:187": "Search…",
    "State": "default"
  },
});
```

### Molecule/Input/Select
- Type: COMPONENT_SET (DS · System/Molecule/Input/Select)
- Figma node ID: `1:2475`
- Figma component key: `54c3345b45cb305f83593d29964b673d462792c2`
- Source page: DS · System
- Default variant ID: `1:2459`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Value#1:191`: TEXT default=Select…
  - `State`: VARIANT default=default options=default, focus, error, disabled
- Variants:
  - State=default — id `1:2459`, key `2d2845670f1d71a5cc258b841520afe1b20caeaf` (State=default)
  - State=focus — id `1:2463`, key `45545666a35c76f22bad54755df69c8485578ca8` (State=focus)
  - State=error — id `1:2467`, key `a6f38559e9273797a435eb0cca88251a8e074332` (State=error)
  - State=disabled — id `1:2471`, key `9063ed0395f4363de09f1c9a383b70af28a5c332` (State=disabled)
- Text layers:
  - `Molecule/Input/Select/State=default/Value`: "Select…" refs=characters=Value#1:191 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/Select/State=focus/Value`: "Select…" refs=characters=Value#1:191 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/Select/State=error/Value`: "Select…" refs=characters=Value#1:191 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/Select/State=disabled/Value`: "Select…" refs=characters=Value#1:191 constraints={"horizontal":"MIN","vertical":"MIN"}
- Usage:
  - Find it with figma.findComponent("Molecule/Input/Select").
  - Instantiate the set/default variant with figma.instantiate("1:2475", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Value#1:191`, `State`.
- Observed instances: 1
- Used on pages: DS · System
- Used in screens: DS · System / Doc/Molecules
- Observed property values:
  - `Value#1:191`: Select…
  - `State`: default
- Instantiate:
```js
await figma.instantiate("1:2475", {
  parentId: screen.id,
  props: {
    "Value#1:191": "Select…",
    "State": "default"
  },
});
```

### Molecule/Input/TextArea
- Type: COMPONENT_SET (DS · System/Molecule/Input/TextArea)
- Figma node ID: `1:2484`
- Figma component key: `75397a3990c33b99770539a0bf3cefe43c2d41b9`
- Source page: DS · System
- Default variant ID: `1:2476`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Value#1:196`: TEXT default=Write a longer note…
  - `State`: VARIANT default=default options=default, focus, error, disabled
- Variants:
  - State=default — id `1:2476`, key `c50acf0a7c0a6602579e902214acc4440d969fd9` (State=default)
  - State=focus — id `1:2478`, key `73c2570e0aa52acf7f7f7501ba2c5be7203a77a7` (State=focus)
  - State=error — id `1:2480`, key `0c304f3bd2ceccc728b7e91cdd1fa2267742397e` (State=error)
  - State=disabled — id `1:2482`, key `c6bafd7e2c71e036dcbb320c31d54a4c479b981d` (State=disabled)
- Text layers:
  - `Molecule/Input/TextArea/State=default/Value`: "Write a longer note…" refs=characters=Value#1:196 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/TextArea/State=focus/Value`: "Write a longer note…" refs=characters=Value#1:196 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/TextArea/State=error/Value`: "Write a longer note…" refs=characters=Value#1:196 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/TextArea/State=disabled/Value`: "Write a longer note…" refs=characters=Value#1:196 constraints={"horizontal":"MIN","vertical":"MIN"}
- Usage:
  - Find it with figma.findComponent("Molecule/Input/TextArea").
  - Instantiate the set/default variant with figma.instantiate("1:2484", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Value#1:196`, `State`.
- Observed instances: 1
- Used on pages: DS · System
- Used in screens: DS · System / Doc/Molecules
- Observed property values:
  - `Value#1:196`: Write a longer note…
  - `State`: default
- Instantiate:
```js
await figma.instantiate("1:2484", {
  parentId: screen.id,
  props: {
    "Value#1:196": "Write a longer note…",
    "State": "default"
  },
});
```

### Molecule/Display/ListItem
- Type: COMPONENT_SET (DS · System/Molecule/Display/ListItem)
- Figma node ID: `1:2501`
- Figma component key: `673aebb4f850f4123ca5e6d17154101a57633094`
- Source page: DS · System
- Default variant ID: `1:2485`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Title#1:201`: TEXT default=Alex Nguyen
  - `Subtitle#1:204`: TEXT default=Last active today
  - `Chevron#1:207`: TEXT default=›
  - `State`: VARIANT default=default options=default, selected
- Variants:
  - State=default — id `1:2485`, key `05bf2f7ff4c0c32fd91f861a55821ef48e485968` (State=default)
  - State=selected — id `1:2493`, key `3cafd1d727884bb16f2862794bf0692d62f2544c` (State=selected)
- Text layers:
  - `Molecule/Display/ListItem/State=default/Chevron`: "›" refs=characters=Chevron#1:207 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Display/ListItem/State=selected/Chevron`: "›" refs=characters=Chevron#1:207 constraints={"horizontal":"MIN","vertical":"MIN"}
- Usage:
  - Find it with figma.findComponent("Molecule/Display/ListItem").
  - Instantiate the set/default variant with figma.instantiate("1:2501", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Title#1:201`, `Subtitle#1:204`, `Chevron#1:207`, `State`.
- Observed instances: 3
- Used on pages: DS · System
- Used in screens: DS · System / Organism/Page/ListSection, DS · System / Doc/Molecules
- Observed property values:
  - `Chevron#1:207`: ›
  - `Subtitle#1:204`: Last active today
  - `Title#1:201`: Alex Nguyen
  - `State`: default, selected
- Instantiate:
```js
await figma.instantiate("1:2501", {
  parentId: screen.id,
  props: {
    "Title#1:201": "Alex Nguyen",
    "Subtitle#1:204": "Last active today",
    "Chevron#1:207": "›",
    "State": "default"
  },
});
```

### Molecule/Display/TabItem
- Type: COMPONENT_SET (DS · System/Molecule/Display/TabItem)
- Figma node ID: `1:2508`
- Figma component key: `5f351c65aabe60f7803498bb344b1bb06720060c`
- Source page: DS · System
- Default variant ID: `1:2502`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Label#1:210`: TEXT default=Overview
  - `Selected`: VARIANT default=off options=off, on
- Variants:
  - Selected=off — id `1:2502`, key `3f911faffe0839807ade9fbaae29bbbbf8dcfa07` (Selected=off)
  - Selected=on — id `1:2505`, key `2a57c36682a93e7b42b51e95f70df5bcca8f73e1` (Selected=on)
- Text layers:
  - `Molecule/Display/TabItem/Selected=off/Label`: "Overview" refs=characters=Label#1:210 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Display/TabItem/Selected=on/Label`: "Overview" refs=characters=Label#1:210 constraints={"horizontal":"MIN","vertical":"MIN"}
- Usage:
  - Find it with figma.findComponent("Molecule/Display/TabItem").
  - Instantiate the set/default variant with figma.instantiate("1:2508", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Label#1:210`, `Selected`.
- Observed instances: 1
- Used on pages: DS · System
- Used in screens: DS · System / Doc/Molecules
- Observed property values:
  - `Label#1:210`: Overview
  - `Selected`: off
- Instantiate:
```js
await figma.instantiate("1:2508", {
  parentId: screen.id,
  props: {
    "Label#1:210": "Overview",
    "Selected": "off"
  },
});
```

### Molecule/Display/StatTile
- Type: COMPONENT_SET (DS · System/Molecule/Display/StatTile)
- Figma node ID: `1:2512`
- Figma component key: `e0d22bafd9d0dfaa42091d6fb46c14990aecfd22`
- Source page: DS · System
- Default variant ID: `1:2509`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Label#1:213`: TEXT default=Active students
  - `Value#1:215`: TEXT default=1,248
  - `Variant`: VARIANT default=Default options=Default
- Variants:
  - Variant=Default — id `1:2509`, key `04d73104cc4a94abfb717573ae2bb23b5fbb4fdb` (Variant=Default)
- Text layers:
  - `Molecule/Display/StatTile/Variant=Default/Label`: "Active students" refs=characters=Label#1:213 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Display/StatTile/Variant=Default/Value`: "1,248" refs=characters=Value#1:215 constraints={"horizontal":"MIN","vertical":"MIN"}
- Usage:
  - Find it with figma.findComponent("Molecule/Display/StatTile").
  - Instantiate the set/default variant with figma.instantiate("1:2512", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Label#1:213`, `Value#1:215`, `Variant`.
- Instantiate:
```js
await figma.instantiate("1:2512", {
  parentId: screen.id,
  props: {
    "Label#1:213": "Active students",
    "Value#1:215": "1,248",
    "Variant": "Default"
  },
});
```

### Molecule/Feedback/Toast
- Type: COMPONENT_SET (DS · System/Molecule/Feedback/Toast)
- Figma node ID: `1:2529`
- Figma component key: `2503f95c1dc14d058750c3c6744e68c0ee554fdd`
- Source page: DS · System
- Default variant ID: `1:2513`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Title#1:217`: TEXT default=Heads up
  - `Dismiss#1:222`: TEXT default=×
  - `Tone`: VARIANT default=info options=info, success, warning, error
- Variants:
  - Tone=info — id `1:2513`, key `8694945055cc83674cbf2def443e1073a2a21de1` (Tone=info)
  - Tone=success — id `1:2517`, key `5bd4fd2339d01d82c1c417b1e8e0a71932be5f1c` (Tone=success)
  - Tone=warning — id `1:2521`, key `141ff491f715678ff0e4300c3cd6244725a06be9` (Tone=warning)
  - Tone=error — id `1:2525`, key `593784447c1afc673d3888dca7e0549e077c3cb5` (Tone=error)
- Text layers:
  - `Molecule/Feedback/Toast/Tone=info/Title`: "Heads up" refs=characters=Title#1:217 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Feedback/Toast/Tone=info/Dismiss`: "×" refs=characters=Dismiss#1:222 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Feedback/Toast/Tone=success/Title`: "Heads up" refs=characters=Title#1:217 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Feedback/Toast/Tone=success/Dismiss`: "×" refs=characters=Dismiss#1:222 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Feedback/Toast/Tone=warning/Title`: "Heads up" refs=characters=Title#1:217 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Feedback/Toast/Tone=warning/Dismiss`: "×" refs=characters=Dismiss#1:222 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Feedback/Toast/Tone=error/Title`: "Heads up" refs=characters=Title#1:217 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Feedback/Toast/Tone=error/Dismiss`: "×" refs=characters=Dismiss#1:222 constraints={"horizontal":"MIN","vertical":"MIN"}
- Usage:
  - Find it with figma.findComponent("Molecule/Feedback/Toast").
  - Instantiate the set/default variant with figma.instantiate("1:2529", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Title#1:217`, `Dismiss#1:222`, `Tone`.
- Observed instances: 3
- Used on pages: DS · System
- Used in screens: DS · System / Molecule/Feedback/ToastStack, DS · System / Doc/Molecules
- Observed property values:
  - `Dismiss#1:222`: ×
  - `Title#1:217`: Heads up
  - `Tone`: success, info
- Instantiate:
```js
await figma.instantiate("1:2529", {
  parentId: screen.id,
  props: {
    "Title#1:217": "Heads up",
    "Dismiss#1:222": "×",
    "Tone": "info"
  },
});
```

### Molecule/Feedback/EmptyState
- Type: COMPONENT_SET (DS · System/Molecule/Feedback/EmptyState)
- Figma node ID: `1:2540`
- Figma component key: `41126b14e49b5535ddb6b9b1ea63b7de8ee7e606`
- Source page: DS · System
- Default variant ID: `1:2530`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Title#1:227`: TEXT default=Nothing here yet
  - `Body#1:229`: TEXT default=Create the first item to see it in this list.
  - `Variant`: VARIANT default=Default options=Default
- Variants:
  - Variant=Default — id `1:2530`, key `bdfc1864f71bc2591a1c10b64cda4dd790f1c92e` (Variant=Default)
- Usage:
  - Find it with figma.findComponent("Molecule/Feedback/EmptyState").
  - Instantiate the set/default variant with figma.instantiate("1:2540", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Title#1:227`, `Body#1:229`, `Variant`.
- Observed instances: 1
- Used on pages: DS · System
- Used in screens: DS · System / Organism/Page/EmptyPage
- Observed property values:
  - `Body#1:229`: Create the first item to see it in this list.
  - `Title#1:227`: Nothing here yet
  - `Variant`: Default
- Instantiate:
```js
await figma.instantiate("1:2540", {
  parentId: screen.id,
  props: {
    "Title#1:227": "Nothing here yet",
    "Body#1:229": "Create the first item to see it in this list.",
    "Variant": "Default"
  },
});
```

### Molecule/Input/Slider
- Type: COMPONENT_SET (DS · System/Molecule/Input/Slider)
- Figma node ID: `1:2559`
- Figma component key: `3ee6103f9c8e17c7654d943c5cae50c0fc14c587`
- Source page: DS · System
- Default variant ID: `1:2541`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Label#1:231`: TEXT default=Volume
  - `Value`: VARIANT default=25 options=25, 50, 75
- Variants:
  - Value=25 — id `1:2541`, key `7d24e8cc0e264b0b1055d5a17498bc6faa8e9bb4` (Value=25)
  - Value=50 — id `1:2547`, key `33a911ea3555e632bb4fb6f3b2db94186bd27b60` (Value=50)
  - Value=75 — id `1:2553`, key `3370dfa52354bd28bf6cc12487533017a1ec2cef` (Value=75)
- Text layers:
  - `Molecule/Input/Slider/Value=25/Label`: "Volume" refs=characters=Label#1:231 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/Slider/Value=50/Label`: "Volume" refs=characters=Label#1:231 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/Slider/Value=75/Label`: "Volume" refs=characters=Label#1:231 constraints={"horizontal":"MIN","vertical":"MIN"}
- Usage:
  - Find it with figma.findComponent("Molecule/Input/Slider").
  - Instantiate the set/default variant with figma.instantiate("1:2559", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Label#1:231`, `Value`.
- Observed instances: 1
- Used on pages: DS · System
- Used in screens: DS · System / Doc/Molecules
- Observed property values:
  - `Label#1:231`: Volume
  - `Value`: 25
- Instantiate:
```js
await figma.instantiate("1:2559", {
  parentId: screen.id,
  props: {
    "Label#1:231": "Volume",
    "Value": "25"
  },
});
```

### Molecule/Input/Stepper
- Type: COMPONENT_SET (DS · System/Molecule/Input/Stepper)
- Figma node ID: `1:2580`
- Figma component key: `31d7eaf4effcaa713368c7b519a7818314a75670`
- Source page: DS · System
- Default variant ID: `1:2560`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `N#1:235`: TEXT default=2
  - `State`: VARIANT default=default options=default, disabled
- Variants:
  - State=default — id `1:2560`, key `7ca0502c2ed52bf2ba1b52bcbbaf0f3c3684a159` (State=default)
  - State=disabled — id `1:2570`, key `23993da9107c761bd8dc043c434585bf6eba6f3b` (State=disabled)
- Usage:
  - Find it with figma.findComponent("Molecule/Input/Stepper").
  - Instantiate the set/default variant with figma.instantiate("1:2580", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `N#1:235`, `State`.
- Observed instances: 1
- Used on pages: DS · System
- Used in screens: DS · System / Doc/Molecules
- Observed property values:
  - `N#1:235`: 2
  - `State`: default
- Instantiate:
```js
await figma.instantiate("1:2580", {
  parentId: screen.id,
  props: {
    "N#1:235": "2",
    "State": "default"
  },
});
```

### Molecule/Input/OTP
- Type: COMPONENT_SET (DS · System/Molecule/Input/OTP)
- Figma node ID: `1:2614`
- Figma component key: `314d21121fc9ab24ac13600dfc9e6c806ed05e05`
- Source page: DS · System
- Default variant ID: `1:2581`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Label#1:238`: TEXT default=Verification code
  - `Digit 1#1:242`: TEXT default=4
  - `Digit 2#1:246`: TEXT default=8
  - `Digit 3#1:250`: TEXT default= 
  - `Digit 4#1:254`: TEXT default= 
  - `State`: VARIANT default=default options=default, focus, error
- Variants:
  - State=default — id `1:2581`, key `e95de58158a95fe634e84df98c2f2eaea961293e` (State=default)
  - State=focus — id `1:2592`, key `bd7e341b218d4d464a0a7630420f91924209a46e` (State=focus)
  - State=error — id `1:2603`, key `b1f52824c4df93a9d02d46ba123f35ec16c7e20e` (State=error)
- Text layers:
  - `Molecule/Input/OTP/State=default/Label`: "Verification code" refs=characters=Label#1:238 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/OTP/State=focus/Label`: "Verification code" refs=characters=Label#1:238 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/OTP/State=error/Label`: "Verification code" refs=characters=Label#1:238 constraints={"horizontal":"MIN","vertical":"MIN"}
- Usage:
  - Find it with figma.findComponent("Molecule/Input/OTP").
  - Instantiate the set/default variant with figma.instantiate("1:2614", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Label#1:238`, `Digit 1#1:242`, `Digit 2#1:246`, `Digit 3#1:250`, `Digit 4#1:254`, `State`.
- Observed instances: 1
- Used on pages: DS · System
- Used in screens: DS · System / Doc/Molecules
- Observed property values:
  - `Digit 4#1:254`:  
  - `Digit 3#1:250`:  
  - `Digit 1#1:242`: 4
  - `Digit 2#1:246`: 8
  - `Label#1:238`: Verification code
  - `State`: default
- Instantiate:
```js
await figma.instantiate("1:2614", {
  parentId: screen.id,
  props: {
    "Label#1:238": "Verification code",
    "Digit 1#1:242": "4",
    "Digit 2#1:246": "8",
    "Digit 3#1:250": " ",
    "Digit 4#1:254": " ",
    "State": "default"
  },
});
```

### Molecule/Display/AccordionItem
- Type: COMPONENT_SET (DS · System/Molecule/Display/AccordionItem)
- Figma node ID: `1:2626`
- Figma component key: `d579e77ebc6e34a05ba48b58de81daac63ec4329`
- Source page: DS · System
- Default variant ID: `1:2615`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Title#1:258`: TEXT default=What is included?
  - `Expanded`: VARIANT default=off options=off, on
- Variants:
  - Expanded=off — id `1:2615`, key `7729b4804b7437b623c82bf063f1beb1788ac932` (Expanded=off)
  - Expanded=on — id `1:2620`, key `6827c97248c46749f399c2cc990cfa705bd4c751` (Expanded=on)
- Text layers:
  - `Molecule/Display/AccordionItem/Expanded=on/Body`: "Tokens, text styles, and the components on this page." constraints={"horizontal":"MIN","vertical":"MIN"}
- Usage:
  - Find it with figma.findComponent("Molecule/Display/AccordionItem").
  - Instantiate the set/default variant with figma.instantiate("1:2626", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Title#1:258`, `Expanded`.
- Observed instances: 1
- Used on pages: DS · System
- Used in screens: DS · System / Doc/Molecules
- Observed property values:
  - `Title#1:258`: What is included?
  - `Expanded`: off
- Instantiate:
```js
await figma.instantiate("1:2626", {
  parentId: screen.id,
  props: {
    "Title#1:258": "What is included?",
    "Expanded": "off"
  },
});
```

### Molecule/Display/MenuItem
- Type: COMPONENT_SET (DS · System/Molecule/Display/MenuItem)
- Figma node ID: `1:2637`
- Figma component key: `17771a84378610784ce7df7aa4af6c773fb12480`
- Source page: DS · System
- Default variant ID: `1:2627`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Label#1:261`: TEXT default=Overview
  - `State`: VARIANT default=default options=default, selected
- Variants:
  - State=default — id `1:2627`, key `2b321bf50d7800532f6487f96a15f3381d11ab76` (State=default)
  - State=selected — id `1:2632`, key `d1ddcc93565ba3b63d0d93e5aa749f9349c6b544` (State=selected)
- Text layers:
  - `Molecule/Display/MenuItem/State=default/Label`: "Overview" refs=characters=Label#1:261 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Display/MenuItem/State=selected/Label`: "Overview" refs=characters=Label#1:261 constraints={"horizontal":"MIN","vertical":"MIN"}
- Usage:
  - Find it with figma.findComponent("Molecule/Display/MenuItem").
  - Instantiate the set/default variant with figma.instantiate("1:2637", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Label#1:261`, `State`.
- Observed instances: 1
- Used on pages: DS · System
- Used in screens: DS · System / Doc/Molecules
- Observed property values:
  - `Label#1:261`: Overview
  - `State`: default
- Instantiate:
```js
await figma.instantiate("1:2637", {
  parentId: screen.id,
  props: {
    "Label#1:261": "Overview",
    "State": "default"
  },
});
```

### Molecule/Display/Breadcrumb
- Type: COMPONENT_SET (DS · System/Molecule/Display/Breadcrumb)
- Figma node ID: `1:2644`
- Figma component key: `be11d69b2b7eb2485db2942aca2ffc11ca87ae4e`
- Source page: DS · System
- Default variant ID: `1:2638`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Home#1:264`: TEXT default=Home
  - `Sep 1#1:266`: TEXT default=/
  - `Settings#1:268`: TEXT default=Settings
  - `Sep 2#1:270`: TEXT default=/
  - `Profile#1:272`: TEXT default=Profile
  - `Variant`: VARIANT default=Default options=Default
- Variants:
  - Variant=Default — id `1:2638`, key `def929a6b98fc9917d22e2e7751527ddaf78fbde` (Variant=Default)
- Text layers:
  - `Molecule/Display/Breadcrumb/Variant=Default/Home`: "Home" refs=characters=Home#1:264 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Display/Breadcrumb/Variant=Default/Sep`: "/" refs=characters=Sep 1#1:266 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Display/Breadcrumb/Variant=Default/Settings`: "Settings" refs=characters=Settings#1:268 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Display/Breadcrumb/Variant=Default/Sep`: "/" refs=characters=Sep 2#1:270 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Display/Breadcrumb/Variant=Default/Profile`: "Profile" refs=characters=Profile#1:272 constraints={"horizontal":"MIN","vertical":"MIN"}
- Usage:
  - Find it with figma.findComponent("Molecule/Display/Breadcrumb").
  - Instantiate the set/default variant with figma.instantiate("1:2644", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Home#1:264`, `Sep 1#1:266`, `Settings#1:268`, `Sep 2#1:270`, `Profile#1:272`, `Variant`.
- Instantiate:
```js
await figma.instantiate("1:2644", {
  parentId: screen.id,
  props: {
    "Home#1:264": "Home",
    "Sep 1#1:266": "/",
    "Settings#1:268": "Settings",
    "Sep 2#1:270": "/",
    "Profile#1:272": "Profile",
    "Variant": "Default"
  },
});
```

### Molecule/Display/Pagination
- Type: COMPONENT_SET (DS · System/Molecule/Display/Pagination)
- Figma node ID: `1:2678`
- Figma component key: `36517b93ee8ff84757738be64bdb19d8050192aa`
- Source page: DS · System
- Default variant ID: `1:2645`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `N 1#1:274`: TEXT default=‹
  - `N 2#1:278`: TEXT default=1
  - `N 3#1:282`: TEXT default=2
  - `N 4#1:286`: TEXT default=3
  - `N 5#1:290`: TEXT default=›
  - `Page`: VARIANT default=1 options=1, 2, 3
- Variants:
  - Page=1 — id `1:2645`, key `e0f7e094df6cc9416dc1f58aae81c37b95c36063` (Page=1)
  - Page=2 — id `1:2656`, key `6a3b0538f5fb4e99d734e8f2853e0c87ca14b59a` (Page=2)
  - Page=3 — id `1:2667`, key `c3e2ce9c0a02cc52330c3d34b707616363ff5119` (Page=3)
- Usage:
  - Find it with figma.findComponent("Molecule/Display/Pagination").
  - Instantiate the set/default variant with figma.instantiate("1:2678", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `N 1#1:274`, `N 2#1:278`, `N 3#1:282`, `N 4#1:286`, `N 5#1:290`, `Page`.
- Observed instances: 1
- Used on pages: DS · System
- Used in screens: DS · System / Doc/Molecules
- Observed property values:
  - `N 4#1:286`: 3
  - `N 5#1:290`: ›
  - `N 3#1:282`: 2
  - `N 2#1:278`: 1
  - `N 1#1:274`: ‹
  - `Page`: 1
- Instantiate:
```js
await figma.instantiate("1:2678", {
  parentId: screen.id,
  props: {
    "N 1#1:274": "‹",
    "N 2#1:278": "1",
    "N 3#1:282": "2",
    "N 4#1:286": "3",
    "N 5#1:290": "›",
    "Page": "1"
  },
});
```

### Molecule/Feedback/LoadingBlock
- Type: COMPONENT_SET (DS · System/Molecule/Feedback/LoadingBlock)
- Figma node ID: `1:2683`
- Figma component key: `e08fd8704250db62cf6b9c429f4bb7e28304a2ed`
- Source page: DS · System
- Default variant ID: `1:2679`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Label#1:294`: TEXT default=Loading
  - `Variant`: VARIANT default=Default options=Default
- Variants:
  - Variant=Default — id `1:2679`, key `adef50b39a35678d493430bc39ac617f6f89cd45` (Variant=Default)
- Text layers:
  - `Molecule/Feedback/LoadingBlock/Variant=Default/Label`: "Loading" refs=characters=Label#1:294 constraints={"horizontal":"MIN","vertical":"MIN"}
- Usage:
  - Find it with figma.findComponent("Molecule/Feedback/LoadingBlock").
  - Instantiate the set/default variant with figma.instantiate("1:2683", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Label#1:294`, `Variant`.
- Instantiate:
```js
await figma.instantiate("1:2683", {
  parentId: screen.id,
  props: {
    "Label#1:294": "Loading",
    "Variant": "Default"
  },
});
```

### Molecule/Input/Date
- Type: COMPONENT_SET (DS · System/Molecule/Input/Date)
- Figma node ID: `1:2705`
- Figma component key: `d461ddce8cd2732796b1e7b7f6f34dc65f399db0`
- Source page: DS · System
- Default variant ID: `1:2684`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Value#1:296`: TEXT default=12 Sep 2026
  - `State`: VARIANT default=default options=default, focus, disabled
- Variants:
  - State=default — id `1:2684`, key `ee9beef2447c97d2d44f28f074042cb422f23a71` (State=default)
  - State=focus — id `1:2691`, key `a0047ec8341fe48663bdce38a24b4ddfa26e536a` (State=focus)
  - State=disabled — id `1:2698`, key `d65e5ac96c7274b190807f093cf233426bbf029c` (State=disabled)
- Text layers:
  - `Molecule/Input/Date/State=default/Value`: "12 Sep 2026" refs=characters=Value#1:296 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/Date/State=focus/Value`: "12 Sep 2026" refs=characters=Value#1:296 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/Date/State=disabled/Value`: "12 Sep 2026" refs=characters=Value#1:296 constraints={"horizontal":"MIN","vertical":"MIN"}
- Usage:
  - Find it with figma.findComponent("Molecule/Input/Date").
  - Instantiate the set/default variant with figma.instantiate("1:2705", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Value#1:296`, `State`.
- Observed instances: 1
- Used on pages: DS · System
- Used in screens: DS · System / Doc/Molecules
- Observed property values:
  - `Value#1:296`: 12 Sep 2026
  - `State`: default
- Instantiate:
```js
await figma.instantiate("1:2705", {
  parentId: screen.id,
  props: {
    "Value#1:296": "12 Sep 2026",
    "State": "default"
  },
});
```

### Molecule/Input/Combobox
- Type: COMPONENT_SET (DS · System/Molecule/Input/Combobox)
- Figma node ID: `1:2733`
- Figma component key: `a68bd2cf617e93c3ce6d4883a7ee6a45fab0bc8f`
- Source page: DS · System
- Default variant ID: `1:2706`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Value#1:300`: TEXT default=Find a person…
  - `State`: VARIANT default=default options=default, open, disabled
- Variants:
  - State=default — id `1:2706`, key `bd05b8b6972e68ff85b7bdc5e4b34a998f25ce2a` (State=default)
  - State=open — id `1:2713`, key `bdb98dabdc27420615b7c8077b3f01f35a62a6ab` (State=open)
  - State=disabled — id `1:2726`, key `22e2870fd5be2f56f6e32f00a8bc4d3d0f317ae5` (State=disabled)
- Text layers:
  - `Molecule/Input/Combobox/State=default/Value`: "Find a person…" refs=characters=Value#1:300 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/Combobox/State=disabled/Value`: "Find a person…" refs=characters=Value#1:300 constraints={"horizontal":"MIN","vertical":"MIN"}
- Usage:
  - Find it with figma.findComponent("Molecule/Input/Combobox").
  - Instantiate the set/default variant with figma.instantiate("1:2733", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Value#1:300`, `State`.
- Observed instances: 1
- Used on pages: DS · System
- Used in screens: DS · System / Doc/Molecules
- Observed property values:
  - `Value#1:300`: Find a person…
  - `State`: default
- Instantiate:
```js
await figma.instantiate("1:2733", {
  parentId: screen.id,
  props: {
    "Value#1:300": "Find a person…",
    "State": "default"
  },
});
```

### Molecule/Input/Dropzone
- Type: COMPONENT_SET (DS · System/Molecule/Input/Dropzone)
- Figma node ID: `1:2752`
- Figma component key: `9341fc458e8f5ab14f9503794563bcb2d9ad1674`
- Source page: DS · System
- Default variant ID: `1:2734`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Title#1:304`: TEXT default=Drop files here
  - `Body#1:308`: TEXT default=PNG or JPG up to 8 MB
  - `State`: VARIANT default=default options=default, active, error
- Variants:
  - State=default — id `1:2734`, key `10c124cfc6bd1a360cc67fc074e3ddf6c4a34f2f` (State=default)
  - State=active — id `1:2740`, key `60105a21f696d4068d4a0796850436dfe81f1296` (State=active)
  - State=error — id `1:2746`, key `61251a53501f4275354e5907cec24f4250125679` (State=error)
- Text layers:
  - `Molecule/Input/Dropzone/State=default/Title`: "Drop files here" refs=characters=Title#1:304 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/Dropzone/State=default/Body`: "PNG or JPG up to 8 MB" refs=characters=Body#1:308 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/Dropzone/State=active/Title`: "Drop files here" refs=characters=Title#1:304 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/Dropzone/State=active/Body`: "PNG or JPG up to 8 MB" refs=characters=Body#1:308 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/Dropzone/State=error/Title`: "Drop files here" refs=characters=Title#1:304 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Molecule/Input/Dropzone/State=error/Body`: "PNG or JPG up to 8 MB" refs=characters=Body#1:308 constraints={"horizontal":"MIN","vertical":"MIN"}
- Usage:
  - Find it with figma.findComponent("Molecule/Input/Dropzone").
  - Instantiate the set/default variant with figma.instantiate("1:2752", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Title#1:304`, `Body#1:308`, `State`.
- Observed instances: 1
- Used on pages: DS · System
- Used in screens: DS · System / Doc/Molecules
- Observed property values:
  - `Body#1:308`: PNG or JPG up to 8 MB
  - `Title#1:304`: Drop files here
  - `State`: default
- Instantiate:
```js
await figma.instantiate("1:2752", {
  parentId: screen.id,
  props: {
    "Title#1:304": "Drop files here",
    "Body#1:308": "PNG or JPG up to 8 MB",
    "State": "default"
  },
});
```

### Molecule/Feedback/ToastStack
- Type: COMPONENT_SET (DS · System/Molecule/Feedback/ToastStack)
- Figma node ID: `1:2762`
- Figma component key: `0b30271f4e98a9b45484ce84aa1bb82eebe19d65`
- Source page: DS · System
- Default variant ID: `1:2753`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Variant`: VARIANT default=Default options=Default
- Variants:
  - Variant=Default — id `1:2753`, key `6c70d50e7ddf3076ebe614e129f7fdfe3b30eb4e` (Variant=Default)
- Usage:
  - Find it with figma.findComponent("Molecule/Feedback/ToastStack").
  - Instantiate the set/default variant with figma.instantiate("1:2762", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Variant`.
- Instantiate:
```js
await figma.instantiate("1:2762", {
  parentId: screen.id,
  props: {
    "Variant": "Default"
  },
});
```

### Molecule/Input/SearchFilter
- Type: COMPONENT_SET (DS · System/Molecule/Input/SearchFilter)
- Figma node ID: `1:2776`
- Figma component key: `4a64c1e250bcab6275785417aab07c2b8a1cc264`
- Source page: DS · System
- Default variant ID: `1:2763`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Label 1#1:312`: TEXT default=All
  - `Label 2#1:314`: TEXT default=Active
  - `Label 3#1:316`: TEXT default=Invited
  - `Variant`: VARIANT default=Default options=Default
- Variants:
  - Variant=Default — id `1:2763`, key `e4d59eeb6d095d8e707db44a4f4828b540d620f6` (Variant=Default)
- Usage:
  - Find it with figma.findComponent("Molecule/Input/SearchFilter").
  - Instantiate the set/default variant with figma.instantiate("1:2776", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Label 1#1:312`, `Label 2#1:314`, `Label 3#1:316`, `Variant`.
- Instantiate:
```js
await figma.instantiate("1:2776", {
  parentId: screen.id,
  props: {
    "Label 1#1:312": "All",
    "Label 2#1:314": "Active",
    "Label 3#1:316": "Invited",
    "Variant": "Default"
  },
});
```

### Organism/Overlay/Dialog
- Type: COMPONENT_SET (DS · System/Organism/Overlay/Dialog)
- Figma node ID: `1:2793`
- Figma component key: `e286f69b89f20e974ae0cd1a458d249f0bff3650`
- Source page: DS · System
- Default variant ID: `1:2777`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Title#1:318`: TEXT default=Confirm action
  - `Body#1:321`: TEXT default=Are you sure you want to proceed? This action cannot be undone.
  - `Tone`: VARIANT default=default options=default, danger
- Variants:
  - Tone=default — id `1:2777`, key `898b4418a72158256dae5e18de1ca715e783a3fb` (Tone=default)
  - Tone=danger — id `1:2785`, key `a0329d1bb3dcefe4a038a43d88de738a5b9cc1be` (Tone=danger)
- Text layers:
  - `Organism/Overlay/Dialog/Tone=default/Title`: "Confirm action" refs=characters=Title#1:318 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Organism/Overlay/Dialog/Tone=default/Body`: "Are you sure you want to proceed? This action cannot be undone." refs=characters=Body#1:321 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Organism/Overlay/Dialog/Tone=danger/Title`: "Confirm action" refs=characters=Title#1:318 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Organism/Overlay/Dialog/Tone=danger/Body`: "Are you sure you want to proceed? This action cannot be undone." refs=characters=Body#1:321 constraints={"horizontal":"MIN","vertical":"MIN"}
- Usage:
  - Find it with figma.findComponent("Organism/Overlay/Dialog").
  - Instantiate the set/default variant with figma.instantiate("1:2793", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Title#1:318`, `Body#1:321`, `Tone`.
- Observed instances: 1
- Used on pages: DS · System
- Used in screens: DS · System / Doc/Organisms
- Observed property values:
  - `Body#1:321`: Are you sure you want to proceed? This action cannot be undone.
  - `Title#1:318`: Confirm action
  - `Tone`: default
- Instantiate:
```js
await figma.instantiate("1:2793", {
  parentId: screen.id,
  props: {
    "Title#1:318": "Confirm action",
    "Body#1:321": "Are you sure you want to proceed? This action cannot be undone.",
    "Tone": "default"
  },
});
```

### Organism/Navigation/Tabs
- Type: COMPONENT_SET (DS · System/Organism/Navigation/Tabs)
- Figma node ID: `1:2830`
- Figma component key: `a8e4f5e7338c0ef827f17943776770486304edcc`
- Source page: DS · System
- Default variant ID: `1:2794`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Label 1#1:324`: TEXT default=Overview
  - `Label 2#1:328`: TEXT default=Activity
  - `Label 3#1:332`: TEXT default=Settings
  - `Selected`: VARIANT default=overview options=overview, activity, settings
- Variants:
  - Selected=overview — id `1:2794`, key `4b1816b6c1a9db836af055839a60e41a2fadfea1` (Selected=overview)
  - Selected=activity — id `1:2806`, key `fca351b7bdf727e8f0217f602a4b83aa2a33749c` (Selected=activity)
  - Selected=settings — id `1:2818`, key `039f4ba1ec9da49080b1964c1418da0dc9fd86fa` (Selected=settings)
- Usage:
  - Find it with figma.findComponent("Organism/Navigation/Tabs").
  - Instantiate the set/default variant with figma.instantiate("1:2830", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Label 1#1:324`, `Label 2#1:328`, `Label 3#1:332`, `Selected`.
- Observed instances: 1
- Used on pages: DS · System
- Used in screens: DS · System / Doc/Organisms
- Observed property values:
  - `Label 3#1:332`: Settings
  - `Label 2#1:328`: Activity
  - `Label 1#1:324`: Overview
  - `Selected`: overview
- Instantiate:
```js
await figma.instantiate("1:2830", {
  parentId: screen.id,
  props: {
    "Label 1#1:324": "Overview",
    "Label 2#1:328": "Activity",
    "Label 3#1:332": "Settings",
    "Selected": "overview"
  },
});
```

### Organism/Page/FormSection
- Type: COMPONENT_SET (DS · System/Organism/Page/FormSection)
- Figma node ID: `1:2843`
- Figma component key: `0c7d5d5656da9daa0a6bc22893957e1dc667c962`
- Source page: DS · System
- Default variant ID: `1:2831`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Title#1:336`: TEXT default=Account
  - `Variant`: VARIANT default=Default options=Default
- Variants:
  - Variant=Default — id `1:2831`, key `ee579e009ef4bd29cd9ba2ab98464beeca9e7071` (Variant=Default)
- Text layers:
  - `Organism/Page/FormSection/Variant=Default/Title`: "Account" refs=characters=Title#1:336 constraints={"horizontal":"MIN","vertical":"MIN"}
- Usage:
  - Find it with figma.findComponent("Organism/Page/FormSection").
  - Instantiate the set/default variant with figma.instantiate("1:2843", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Title#1:336`, `Variant`.
- Instantiate:
```js
await figma.instantiate("1:2843", {
  parentId: screen.id,
  props: {
    "Title#1:336": "Account",
    "Variant": "Default"
  },
});
```

### Organism/Navigation/Sidebar
- Type: COMPONENT_SET (DS · System/Organism/Navigation/Sidebar)
- Figma node ID: `1:2895`
- Figma component key: `1e591dc0f499845d847bf11d966d9d0e1346a1b2`
- Source page: DS · System
- Default variant ID: `1:2844`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Brand#1:338`: TEXT default=AI4BA
  - `Label 1#1:342`: TEXT default=Overview
  - `Label 2#1:346`: TEXT default=Activity
  - `Label 3#1:350`: TEXT default=Settings
  - `Selected`: VARIANT default=overview options=overview, activity, settings
- Variants:
  - Selected=overview — id `1:2844`, key `249ce65030f8c5c7996a64b19ada2ec940fd6e99` (Selected=overview)
  - Selected=activity — id `1:2861`, key `9ccab97c5120ef7c0574a2504bb61adb86ec5df1` (Selected=activity)
  - Selected=settings — id `1:2878`, key `0b5bf3a3e7032484134e9e697f903deee36ee55c` (Selected=settings)
- Text layers:
  - `Organism/Navigation/Sidebar/Selected=overview/Brand`: "AI4BA" refs=characters=Brand#1:338 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Organism/Navigation/Sidebar/Selected=activity/Brand`: "AI4BA" refs=characters=Brand#1:338 constraints={"horizontal":"MIN","vertical":"MIN"}
  - `Organism/Navigation/Sidebar/Selected=settings/Brand`: "AI4BA" refs=characters=Brand#1:338 constraints={"horizontal":"MIN","vertical":"MIN"}
- Usage:
  - Find it with figma.findComponent("Organism/Navigation/Sidebar").
  - Instantiate the set/default variant with figma.instantiate("1:2895", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Brand#1:338`, `Label 1#1:342`, `Label 2#1:346`, `Label 3#1:350`, `Selected`.
- Observed instances: 1
- Used on pages: DS · System
- Used in screens: DS · System / Doc/Organisms
- Observed property values:
  - `Label 3#1:350`: Settings
  - `Label 2#1:346`: Activity
  - `Label 1#1:342`: Overview
  - `Brand#1:338`: AI4BA
  - `Selected`: overview
- Instantiate:
```js
await figma.instantiate("1:2895", {
  parentId: screen.id,
  props: {
    "Brand#1:338": "AI4BA",
    "Label 1#1:342": "Overview",
    "Label 2#1:346": "Activity",
    "Label 3#1:350": "Settings",
    "Selected": "overview"
  },
});
```

### Organism/Page/SettingsGroup
- Type: COMPONENT_SET (DS · System/Organism/Page/SettingsGroup)
- Figma node ID: `1:2905`
- Figma component key: `26d37ad7defe308decc2484d2621479c9e3d5294`
- Source page: DS · System
- Default variant ID: `1:2896`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Title#1:354`: TEXT default=Notifications
  - `Variant`: VARIANT default=Default options=Default
- Variants:
  - Variant=Default — id `1:2896`, key `77413a987a86eb97bc9900b334b8ba8853795acc` (Variant=Default)
- Text layers:
  - `Organism/Page/SettingsGroup/Variant=Default/Title`: "Notifications" refs=characters=Title#1:354 constraints={"horizontal":"MIN","vertical":"MIN"}
- Usage:
  - Find it with figma.findComponent("Organism/Page/SettingsGroup").
  - Instantiate the set/default variant with figma.instantiate("1:2905", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Title#1:354`, `Variant`.
- Instantiate:
```js
await figma.instantiate("1:2905", {
  parentId: screen.id,
  props: {
    "Title#1:354": "Notifications",
    "Variant": "Default"
  },
});
```

### Organism/Page/ListSection
- Type: COMPONENT_SET (DS · System/Organism/Page/ListSection)
- Figma node ID: `1:2924`
- Figma component key: `953eb07d540533f60c612055507cee5754d91b3a`
- Source page: DS · System
- Default variant ID: `1:2906`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Title#1:356`: TEXT default=People
  - `Variant`: VARIANT default=Default options=Default
- Variants:
  - Variant=Default — id `1:2906`, key `3617175ed2f0c045d66bc2fb3a1c4b6d1165211b` (Variant=Default)
- Text layers:
  - `Organism/Page/ListSection/Variant=Default/Title`: "People" refs=characters=Title#1:356 constraints={"horizontal":"MIN","vertical":"MIN"}
- Usage:
  - Find it with figma.findComponent("Organism/Page/ListSection").
  - Instantiate the set/default variant with figma.instantiate("1:2924", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Title#1:356`, `Variant`.
- Instantiate:
```js
await figma.instantiate("1:2924", {
  parentId: screen.id,
  props: {
    "Title#1:356": "People",
    "Variant": "Default"
  },
});
```

### Organism/Navigation/Header
- Type: COMPONENT_SET (DS · System/Organism/Navigation/Header)
- Figma node ID: `1:2935`
- Figma component key: `a2058e97ab41bd7379f70feabc80663eb48fd05e`
- Source page: DS · System
- Default variant ID: `1:2925`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Brand#1:358`: TEXT default=AI4BA
  - `Variant`: VARIANT default=Default options=Default
- Variants:
  - Variant=Default — id `1:2925`, key `65a83f6e94b795ad3a8cfe8997e5b6e2dc5f5637` (Variant=Default)
- Usage:
  - Find it with figma.findComponent("Organism/Navigation/Header").
  - Instantiate the set/default variant with figma.instantiate("1:2935", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Brand#1:358`, `Variant`.
- Instantiate:
```js
await figma.instantiate("1:2935", {
  parentId: screen.id,
  props: {
    "Brand#1:358": "AI4BA",
    "Variant": "Default"
  },
});
```

### Organism/Navigation/Footer
- Type: COMPONENT_SET (DS · System/Organism/Navigation/Footer)
- Figma node ID: `1:2944`
- Figma component key: `4af39fb4bbfb4dc199bde418d471d975e17925d7`
- Source page: DS · System
- Default variant ID: `1:2936`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Copyright#1:360`: TEXT default=© 2026 AI4BA
  - `Privacy#1:362`: TEXT default=Privacy
  - `Terms#1:364`: TEXT default=Terms
  - `Contact#1:366`: TEXT default=Contact
  - `Variant`: VARIANT default=Default options=Default
- Variants:
  - Variant=Default — id `1:2936`, key `561b3ae712b9cf452e7cc659a813c5fb8b25e22b` (Variant=Default)
- Usage:
  - Find it with figma.findComponent("Organism/Navigation/Footer").
  - Instantiate the set/default variant with figma.instantiate("1:2944", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Copyright#1:360`, `Privacy#1:362`, `Terms#1:364`, `Contact#1:366`, `Variant`.
- Instantiate:
```js
await figma.instantiate("1:2944", {
  parentId: screen.id,
  props: {
    "Copyright#1:360": "© 2026 AI4BA",
    "Privacy#1:362": "Privacy",
    "Terms#1:364": "Terms",
    "Contact#1:366": "Contact",
    "Variant": "Default"
  },
});
```

### Organism/Overlay/Drawer
- Type: COMPONENT_SET (DS · System/Organism/Overlay/Drawer)
- Figma node ID: `1:3008`
- Figma component key: `b98e664ba8fe36b2bc2749f91baf34485e9b3871`
- Source page: DS · System
- Default variant ID: `1:2945`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Title#1:368`: TEXT default=Menu
  - `Label 1#1:372`: TEXT default=Overview
  - `Label 2#1:376`: TEXT default=Activity
  - `Label 3#1:380`: TEXT default=Settings
  - `Selected`: VARIANT default=overview options=overview, activity, settings
- Variants:
  - Selected=overview — id `1:2945`, key `54211c62ac9b32acd250569aab67c6226f8c8fea` (Selected=overview)
  - Selected=activity — id `1:2966`, key `244d00f0787cfa66468efb6da7ab8391d4840057` (Selected=activity)
  - Selected=settings — id `1:2987`, key `071a62b1d5ebd9ff31596850c663f3d0868b69b0` (Selected=settings)
- Usage:
  - Find it with figma.findComponent("Organism/Overlay/Drawer").
  - Instantiate the set/default variant with figma.instantiate("1:3008", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Title#1:368`, `Label 1#1:372`, `Label 2#1:376`, `Label 3#1:380`, `Selected`.
- Observed instances: 1
- Used on pages: DS · System
- Used in screens: DS · System / Doc/Organisms
- Observed property values:
  - `Label 3#1:380`: Settings
  - `Label 1#1:372`: Overview
  - `Label 2#1:376`: Activity
  - `Title#1:368`: Menu
  - `Selected`: overview
- Instantiate:
```js
await figma.instantiate("1:3008", {
  parentId: screen.id,
  props: {
    "Title#1:368": "Menu",
    "Label 1#1:372": "Overview",
    "Label 2#1:376": "Activity",
    "Label 3#1:380": "Settings",
    "Selected": "overview"
  },
});
```

### Organism/Page/SkeletonPage
- Type: COMPONENT_SET (DS · System/Organism/Page/SkeletonPage)
- Figma node ID: `1:3020`
- Figma component key: `df40ba9b2bf47a481834e87970f4e70684bd1c34`
- Source page: DS · System
- Default variant ID: `1:3009`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Variant`: VARIANT default=Default options=Default
- Variants:
  - Variant=Default — id `1:3009`, key `d0c245697656ec8041e8263536dbfacbef42386d` (Variant=Default)
- Usage:
  - Find it with figma.findComponent("Organism/Page/SkeletonPage").
  - Instantiate the set/default variant with figma.instantiate("1:3020", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Variant`.
- Instantiate:
```js
await figma.instantiate("1:3020", {
  parentId: screen.id,
  props: {
    "Variant": "Default"
  },
});
```

### Organism/Page/EmptyPage
- Type: COMPONENT_SET (DS · System/Organism/Page/EmptyPage)
- Figma node ID: `1:3032`
- Figma component key: `9e69d8738ec654c131fe338e19c63d719d0eb283`
- Source page: DS · System
- Default variant ID: `1:3021`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Variant`: VARIANT default=Default options=Default
- Variants:
  - Variant=Default — id `1:3021`, key `bf990127a1498eb4f89dc270340a440ddf95e1b7` (Variant=Default)
- Usage:
  - Find it with figma.findComponent("Organism/Page/EmptyPage").
  - Instantiate the set/default variant with figma.instantiate("1:3032", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Variant`.
- Instantiate:
```js
await figma.instantiate("1:3032", {
  parentId: screen.id,
  props: {
    "Variant": "Default"
  },
});
```

### Organism/Display/DataTable
- Type: COMPONENT_SET (DS · System/Organism/Display/DataTable)
- Figma node ID: `1:3053`
- Figma component key: `d8c0a26acd9c03b7fb5f6a0adb6a69f9a4fbb41b`
- Source page: DS · System
- Default variant ID: `1:3033`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Name 1#1:384`: TEXT default=Name
  - `Status#1:386`: TEXT default=Status
  - `Role 1#1:388`: TEXT default=Role
  - `Name 2#1:390`: TEXT default=Alex Nguyen
  - `Label 1#1:392`: TEXT default=Active
  - `Role 2#1:394`: TEXT default=Admin
  - `Name 3#1:396`: TEXT default=Jordan Lee
  - `Label 2#1:398`: TEXT default=Invited
  - `Role 3#1:400`: TEXT default=Editor
  - `Name 4#1:402`: TEXT default=Sam Okonkwo
  - `Label 3#1:404`: TEXT default=Active
  - `Role 4#1:406`: TEXT default=Viewer
  - `Variant`: VARIANT default=Default options=Default
- Variants:
  - Variant=Default — id `1:3033`, key `994805b75c731d95039d37a13403c5a2d7219350` (Variant=Default)
- Usage:
  - Find it with figma.findComponent("Organism/Display/DataTable").
  - Instantiate the set/default variant with figma.instantiate("1:3053", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Name 1#1:384`, `Status#1:386`, `Role 1#1:388`, `Name 2#1:390`, `Label 1#1:392`, `Role 2#1:394`, `Name 3#1:396`, `Label 2#1:398`, `Role 3#1:400`, `Name 4#1:402`, `Label 3#1:404`, `Role 4#1:406`, `Variant`.
- Instantiate:
```js
await figma.instantiate("1:3053", {
  parentId: screen.id,
  props: {
    "Name 1#1:384": "Name",
    "Status#1:386": "Status",
    "Role 1#1:388": "Role",
    "Name 2#1:390": "Alex Nguyen",
    "Label 1#1:392": "Active",
    "Role 2#1:394": "Admin",
    "Name 3#1:396": "Jordan Lee",
    "Label 2#1:398": "Invited",
    "Role 3#1:400": "Editor",
    "Name 4#1:402": "Sam Okonkwo",
    "Label 3#1:404": "Active",
    "Role 4#1:406": "Viewer",
    "Variant": "Default"
  },
});
```

### Organism/Overlay/CommandPalette
- Type: COMPONENT_SET (DS · System/Organism/Overlay/CommandPalette)
- Figma node ID: `1:3081`
- Figma component key: `3d3c1157d15fe5b85f83d5081debb7b7b1142da1`
- Source page: DS · System
- Default variant ID: `1:3054`
- Layout: layoutMode=NONE, clipsContent=true
- Shape: cornerRadius=4, topLeftRadius=4, topRightRadius=4, bottomRightRadius=4, bottomLeftRadius=4
- Component properties:
  - `Value#1:408`: TEXT default=Jump to…
  - `Esc#1:410`: TEXT default=esc
  - `Group#1:412`: TEXT default=Pages
  - `Label 1#1:414`: TEXT default=Overview
  - `Hint 1#1:416`: TEXT default=⌘1
  - `Label 2#1:418`: TEXT default=Activity
  - `Hint 2#1:420`: TEXT default=⌘2
  - `Label 3#1:422`: TEXT default=Settings
  - `Hint 3#1:424`: TEXT default=⌘3
  - `Variant`: VARIANT default=Default options=Default
- Variants:
  - Variant=Default — id `1:3054`, key `a8faee95d1b2c047a7b2c40b395647f339c350d8` (Variant=Default)
- Usage:
  - Find it with figma.findComponent("Organism/Overlay/CommandPalette").
  - Instantiate the set/default variant with figma.instantiate("1:3081", { parentId, props }), or use an exact variant id.
  - Set component properties with exact keys: `Value#1:408`, `Esc#1:410`, `Group#1:412`, `Label 1#1:414`, `Hint 1#1:416`, `Label 2#1:418`, `Hint 2#1:420`, `Label 3#1:422`, `Hint 3#1:424`, `Variant`.
- Instantiate:
```js
await figma.instantiate("1:3081", {
  parentId: screen.id,
  props: {
    "Value#1:408": "Jump to…",
    "Esc#1:410": "esc",
    "Group#1:412": "Pages",
    "Label 1#1:414": "Overview",
    "Hint 1#1:416": "⌘1",
    "Label 2#1:418": "Activity",
    "Hint 2#1:420": "⌘2",
    "Label 3#1:422": "Settings",
    "Hint 3#1:424": "⌘3",
    "Variant": "Default"
  },
});
```

## External & Library Components
_No remote-library component instances were identified in the inspected instance range._

## Screen Evidence
### Page 1 / DS Preview · Styles
- Figma node ID: `1:1212`
- Direct evidence: FRAME, 1232×780, layout=VERTICAL, 3 direct child(ren), 0 component instance(s).
- Top-level composition: VNG Value — pick a style (TEXT) → Same brand colour, same components. Only (TEXT) → Columns (FRAME)

### Roadmap / Roadmap / VNG Value
- Figma node ID: `1:51`
- Direct evidence: FRAME, 1680×2239, layout=VERTICAL, 4 direct child(ren), 64 component instance(s).
- Components observed: Feature chip, Version badge
- Top-level composition: Tiêu đề (FRAME) → Chú thích (FRAME) → Các phiên bản (FRAME) → Ghi chú (TEXT)

### Roadmap / BPMN · Luồng 1 · Tiếp nhận & lập hợp đồng
- Figma node ID: `1:436`
- Direct evidence: FRAME, 1667×1075, layout=NONE, 76 direct child(ren), 0 component instance(s).
- Top-level composition: title (TEXT) → subtitle (TEXT) → pool:kh (RECTANGLE) → pool-head:kh (RECTANGLE) → pool-name:kh (TEXT) → pool:vng (RECTANGLE) → pool-head:vng (RECTANGLE) → pool-name:vng (TEXT) → lane:kd (RECTANGLE) → lane-head:kd (RECTANGLE) → lane-name:kd (TEXT) → lane:duyet (RECTANGLE) → lane-head:duyet (RECTANGLE) → lane-name:duyet (TEXT) → edge s1->gwKH (VECTOR) → edge gwKH->chonKH (VECTOR) → edge gwKH->taoKH (VECTOR) → edge chonKH->mKH (VECTOR) → edge taoKH->mKH (VECTOR) → edge mKH->lapHD (VECTOR)

### Roadmap / Chú giải · Luồng 1 · Tiếp nhận & lập hợp đồng
- Figma node ID: `1:539`
- Direct evidence: FRAME, 416×902, layout=VERTICAL, 2 direct child(ren), 0 component instance(s).
- Top-level composition: header (FRAME) → columns (FRAME)

### Roadmap / BPMN · Luồng 2 · Định giá tài sản & thông báo sơ bộ
- Figma node ID: `1:654`
- Direct evidence: FRAME, 1345×615, layout=NONE, 43 direct child(ren), 0 component instance(s).
- Top-level composition: title (TEXT) → subtitle (TEXT) → pool:kh (RECTANGLE) → pool-head:kh (RECTANGLE) → pool-name:kh (TEXT) → pool:vng (RECTANGLE) → pool-head:vng (RECTANGLE) → pool-name:vng (TEXT) → lane:cv (RECTANGLE) → lane-head:cv (RECTANGLE) → lane-name:cv (TEXT) → edge s1->taoTS (VECTOR) → edge taoTS->hangMuc (VECTOR) → edge hangMuc->tsss (VECTOR) → edge tsss->bang (VECTOR) → edge bang->tinh (VECTOR) → edge tinh->inSB (VECTOR) → edge inSB->done (VECTOR) → edge inSB->kh (VECTOR) → mark:source:inSB->kh (ELLIPSE)

### Roadmap / Chú giải · Luồng 2 · Định giá tài sản & thông báo sơ bộ
- Figma node ID: `1:711`
- Direct evidence: FRAME, 416×750, layout=VERTICAL, 2 direct child(ren), 0 component instance(s).
- Top-level composition: header (FRAME) → columns (FRAME)

### Roadmap / BPMN · Luồng 3 · Hoàn thiện & bàn giao chứng thư
- Figma node ID: `1:805`
- Direct evidence: FRAME, 1702×1034, layout=NONE, 67 direct child(ren), 0 component instance(s).
- Top-level composition: title (TEXT) → subtitle (TEXT) → pool:kh (RECTANGLE) → pool-head:kh (RECTANGLE) → pool-name:kh (TEXT) → pool:vng (RECTANGLE) → pool-head:vng (RECTANGLE) → pool-name:vng (TEXT) → lane:cv (RECTANGLE) → lane-head:cv (RECTANGLE) → lane-name:cv (TEXT) → lane:tdv (RECTANGLE) → lane-head:tdv (RECTANGLE) → lane-name:tdv (TEXT) → lane:chua (RECTANGLE) → lane-head:chua (RECTANGLE) → lane-name:chua (TEXT) → edge s1->sua (VECTOR) → edge sua->mXn (VECTOR) → edge mXn->xn (VECTOR)

### Roadmap / Chú giải · Luồng 3 · Hoàn thiện & bàn giao chứng thư
- Figma node ID: `1:1091`
- Direct evidence: FRAME, 416×994, layout=VERTICAL, 2 direct child(ren), 0 component instance(s).
- Top-level composition: header (FRAME) → columns (FRAME)

### DS · System / Doc/Cover
- Figma node ID: `1:3082`
- Direct evidence: FRAME, 1200×531, layout=VERTICAL, 5 direct child(ren), 0 component instance(s).
- Top-level composition: Badge (FRAME) → Display/Medium (TEXT) → Title/Large (TEXT) → Rule (RECTANGLE) → Row (FRAME)

### DS · System / Doc/Product Information
- Figma node ID: `1:3104`
- Direct evidence: FRAME, 1200×340, layout=VERTICAL, 2 direct child(ren), 0 component instance(s).
- Top-level composition: Heading/H3 (TEXT) → Row (FRAME)

### DS · System / Doc/Summary
- Figma node ID: `1:3125`
- Direct evidence: FRAME, 1200×628, layout=VERTICAL, 2 direct child(ren), 0 component instance(s).
- Top-level composition: Heading/H3 (TEXT) → Stack (FRAME)

### DS · System / Doc/Color System
- Figma node ID: `1:3158`
- Direct evidence: FRAME, 1200×1924, layout=VERTICAL, 15 direct child(ren), 0 component instance(s).
- Top-level composition: Heading/H2 (TEXT) → Heading/H6 (TEXT) → Row (FRAME) → Heading/H6 (TEXT) → Row (FRAME) → Heading/H6 (TEXT) → Row (FRAME) → Heading/H6 (TEXT) → Row (FRAME) → Heading/H6 (TEXT) → Row (FRAME) → Heading/H6 (TEXT) → Row (FRAME) → Heading/H6 (TEXT) → Stack (FRAME)

### DS · System / Doc/Typography System
- Figma node ID: `1:3616`
- Direct evidence: FRAME, 1200×1664, layout=VERTICAL, 27 direct child(ren), 0 component instance(s).
- Top-level composition: Heading/H2 (TEXT) → Label/Small (TEXT) → Row (FRAME) → Row (FRAME) → Row (FRAME) → Label/Small (TEXT) → Row (FRAME) → Row (FRAME) → Row (FRAME) → Row (FRAME) → Row (FRAME) → Row (FRAME) → Label/Small (TEXT) → Row (FRAME) → Row (FRAME) → Row (FRAME) → Label/Small (TEXT) → Row (FRAME) → Row (FRAME) → Row (FRAME)

### DS · System / Doc/Spacing & Layout
- Figma node ID: `1:3684`
- Direct evidence: FRAME, 1200×1008, layout=VERTICAL, 8 direct child(ren), 0 component instance(s).
- Top-level composition: Heading/H2 (TEXT) → Stack (FRAME) → Heading/H6 (TEXT) → Row (FRAME) → Heading/H6 (TEXT) → Row (FRAME) → Heading/H6 (TEXT) → Row (FRAME)

### DS · System / Doc/Radius & Elevation
- Figma node ID: `1:3793`
- Direct evidence: FRAME, 1200×540, layout=VERTICAL, 4 direct child(ren), 0 component instance(s).
- Top-level composition: Heading/H2 (TEXT) → Row (FRAME) → Heading/H2 (TEXT) → Row (FRAME)

### DS · System / Doc/Atoms
- Figma node ID: `1:3856`
- Direct evidence: FRAME, 1200×790, layout=VERTICAL, 4 direct child(ren), 11 component instance(s).
- Components observed: Atom/Icon, Atom/Status/Badge, Atom/Status/Dot, Atom/Status/Chip, Atom/Divider, Atom/Avatar, Atom/Feedback/Progress, Atom/Feedback/Spinner, Atom/Feedback/Skeleton, Atom/Status/Tag, Atom/Feedback/Trend
- Top-level composition: Heading/H2 (TEXT) → Body/Large (TEXT) → Row (FRAME) → Doc/Specimen light (FRAME)

### DS · System / Doc/Molecules
- Figma node ID: `1:3931`
- Direct evidence: FRAME, 1200×1748, layout=VERTICAL, 4 direct child(ren), 25 component instance(s).
- Components observed: Molecule/Action/Button, Molecule/Input/TextField, Molecule/Display/Card, Molecule/Feedback/Alert, Molecule/Action/IconButton, Molecule/Action/Segmented, Molecule/Input/Checkbox, Molecule/Input/Radio, Molecule/Input/Switch, Molecule/Input/SearchField, Molecule/Input/Select, Molecule/Input/TextArea, Molecule/Display/ListItem, Atom/Avatar, Molecule/Display/TabItem, Molecule/Feedback/Toast, Molecule/Input/Slider, Molecule/Input/Stepper, Molecule/Input/OTP, Molecule/Display/AccordionItem, Molecule/Display/MenuItem, Molecule/Display/Pagination, Molecule/Input/Date, Molecule/Input/Combobox, Molecule/Input/Dropzone
- Top-level composition: Heading/H2 (TEXT) → Body/Large (TEXT) → Row (FRAME) → Doc/Specimen light (FRAME)

### DS · System / Doc/Organisms
- Figma node ID: `1:4160`
- Direct evidence: FRAME, 1200×1130, layout=VERTICAL, 4 direct child(ren), 6 component instance(s).
- Components observed: Organism/Overlay/Dialog, Molecule/Action/Button, Organism/Navigation/Tabs, Organism/Navigation/Sidebar, Organism/Overlay/Drawer
- Top-level composition: Heading/H2 (TEXT) → Body/Large (TEXT) → Row (FRAME) → Doc/Specimen light (FRAME)

## Do's and Don'ts
### Do
- Do use the extracted component names and property keys exactly as written.
- Do configure instances with component properties before applying layer-name overrides.
- Do bind or reference color variables instead of hardcoding equivalent hex values.
- Do run `layout_audit` after non-trivial edits and fix overflow/clipping structurally.

### Don't
- Don't create look-alike components when an equivalent component is listed above.
- Don't infer brand semantics from token names alone; confirm with actual screens or screenshots.
- Don't use hidden/truncated text layers as stable selectors unless component properties expose the same control.
- Don't treat this document as exhaustive when Known Gaps lists missing pages, screenshots or anatomy.

## Responsive Evidence
- Layout grid styles exist; map these to implementation breakpoints only after checking target frames.
- Some component children expose Figma constraints. Preserve those resize rules when recreating components.
- Frame widths are observations, not breakpoints. Only document a responsive transformation when matching screens or explicit constraints support it.

## Iteration Guide
1. Start from the Figma IDs/keys in this document, then confirm the chosen binding with `get_component` before a large write.
2. Use exact component property keys from this file in `figma.instantiate(..., { props })`; use a variant ID when the desired set variant is explicit.
3. Use layer overrides only when a desired change has no component property.
4. For code implementation, map Figma variables/styles to design tokens first, then compose components.
5. After generating or editing UI, run `layout_audit`; after major visual changes, take a screenshot for human review.

## Known Gaps
- Component anatomy was not included. Re-run with `includeAnatomy:true` for subtree-level inspection.

## Notes
- Generated from local Figma styles, variables and components plus bounded screen/instance evidence.
- Component property names are the exact API keys to pass to instance.setProperties.
- Observed frequency patterns are evidence, not automatically approved semantic tokens.

