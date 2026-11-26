## FontSpector report

fontspector version: 1.9.0






## Check results




<details><summary>[12] fonts/ttf/CCTypewriterCANARY-Regular.ttf</summary>
<div>


<details>
    <summary>⚠️ <b>WARN</b> Check that OS/2 fsSelection WWS bit is set correctly. (opentype/fsselection_wws)</summary>
    <div>








- ⚠️ **WARN** OS/2 fsSelection WWS bit is not set, and the font does not have name IDs 21/22 (WWS Family/Subfamily). If the font's naming is WWS-conformant, the WWS bit should be set. [code: no-wws-without-wws-names]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. (contour_count)</summary>
    <div>








- ⚠️ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are
     inferred from the typical amounts of contours observed in a
     large collection of reference font families. The divergences
     listed below may simply indicate a significantly different
     design on some of your glyphs. On the other hand, some of these
     may flag actual bugs in the font such as glyphs mapped to an
     incorrect codepoint. Please consider reviewing the design and
     codepoint assignment of these to make sure they are correct.


    The following glyphs do not have the recommended number of contours:
* uni0D8D (U+0D8D): found 5, expected one of: [3, 4, 6]
* uni0D8E (U+0D8E): found 7, expected one of: [5, 6, 8]
* uni0D93 (U+0D93): found 3, expected one of: [4, 5, 6]
* uni0D95 (U+0D95): found 2, expected one of: [3, 4]
* uni0D9E (U+0D9E): found 1, expected one of: [2, 3, 4]
* uni0DA5 (U+0DA5): found 1, expected one of: [2, 3, 5]
* uni0DB9 (U+0DB9): found 1, expected one of: [2, 3] [code: contour-count]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Does GPOS table have kerning information? (gpos_kerning_info)</summary>
    <div>








- ⚠️ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. (math_signs_width)</summary>
    <div>








- ⚠️ **WARN** The most common width is 397 among a set of 4  math glyphs.
The following math glyphs have a different width, though:
width=493: multiply
width=470: plus
width=358: equal [code: width-outliers]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure indic fonts have the Indian Rupee Sign glyph. (rupee)</summary>
    <div>








- ⚠️ **WARN** Font is missing the Indian Rupee Sign glyph. Please add a glyph for Indian Rupee Sign (₹) at codepoint U+20B9. (Overriden: Sinhala fonts: U+20B9 is optional (Sri Lanka writes රු / Rs)) [code: missing-rupee]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs (unreachable_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

* iisignsinh.alt1
* viramasinh.alt1 [code: unreachable-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure font has overlaps bit set correctly. (overlaps_bit)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlaps but the overlaps bit is not set:
* phIsinh
* rsinh
* uni0D92 (U+0D92) [code: no-overlaps-bit]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (googlefonts/meta/script_lang_tags)</summary>
    <div>








- ⚠️ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? (outline_colinear_vectors)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have colinear vectors:

* uni0D87 (U+0D87): from (550.0, 474.0) to (550.0, 474.0) is colinear with segment from (550.0, 474.0) to (714.0, 473.0)
* uni0D8D (U+0D8D): from (778.0, 133.0) to (778.0, 107.0) is colinear with segment from (778.0, 107.0) to (782.0, 35.0)
* uni0D8D (U+0D8D): from (778.0, 107.0) to (782.0, 35.0) is colinear with segment from (782.0, 35.0) to (784.0, 21.0)
* uni0D8E (U+0D8E): from (778.0, 133.0) to (778.0, 107.0) is colinear with segment from (778.0, 107.0) to (782.0, 35.0)
* uni0D8E (U+0D8E): from (778.0, 107.0) to (782.0, 35.0) is colinear with segment from (782.0, 35.0) to (784.0, 21.0)
* uni0D8E (U+0D8E): from (1065.0, 138.0) to (1065.0, 110.0) is colinear with segment from (1065.0, 110.0) to (1070.0, 33.0)
* uni0D8E (U+0D8E): from (1065.0, 110.0) to (1070.0, 33.0) is colinear with segment from (1070.0, 33.0) to (1072.0, 18.0)
* uni0D91 (U+0D91): from (48.0, 373.0) to (48.0, 373.0) is colinear with segment from (48.0, 373.0) to (202.0, 373.0)
* uni0D92 (U+0D92): from (48.0, 373.0) to (48.0, 373.0) is colinear with segment from (48.0, 373.0) to (202.0, 373.0)
* uni0D93 (U+0D93): from (523.0, 373.0) to (523.0, 373.0) is colinear with segment from (523.0, 373.0) to (677.0, 373.0)
* uni0DB4 (U+0DB4): from (289.0, 54.0) to (289.0, 54.0) is colinear with segment from (289.0, 54.0) to (294.0, 54.0)
* uni0DB4 (U+0DB4): from (289.0, 54.0) to (294.0, 54.0) is colinear with segment from (294.0, 54.0) to (294.0, 54.0)
* uni0DB7 (U+0DB7): from (45.0, 376.0) to (45.0, 376.0) is colinear with segment from (45.0, 376.0) to (196.0, 376.0)
* uni0DC1 (U+0DC1): from (528.0, 23.0) to (528.0, 21.0) is colinear with segment from (528.0, 21.0) to (528.0, 19.0)
* uni0DC3 (U+0DC3): from (44.0, 409.0) to (117.0, 410.0) is colinear with segment from (117.0, 410.0) to (117.0, 410.0)
* uni0DD0 (U+0DD0): from (37.0, 474.0) to (37.0, 474.0) is colinear with segment from (37.0, 474.0) to (201.0, 473.0)
* uni0DF3 (U+0DF3): from (248.0, 465.0) to (246.0, 450.0) is colinear with segment from (246.0, 450.0) to (241.0, 373.0)
* uni0DF3 (U+0DF3): from (246.0, 450.0) to (241.0, 373.0) is colinear with segment from (241.0, 373.0) to (241.0, 345.0)
* uniE001 (U+E001): from (242.0, 55.0) to (242.0, 55.0) is colinear with segment from (242.0, 55.0) to (243.0, 55.0)
* uniE001 (U+E001): from (242.0, 55.0) to (243.0, 55.0) is colinear with segment from (243.0, 55.0) to (245.0, 55.0)
* uniE001 (U+E001): from (243.0, 55.0) to (245.0, 55.0) is colinear with segment from (245.0, 55.0) to (248.0, 55.0)
* uni0DD8 (U+0DD8): from (244.0, 138.0) to (244.0, 110.0) is colinear with segment from (244.0, 110.0) to (249.0, 33.0)
* uni0DD8 (U+0DD8): from (244.0, 110.0) to (249.0, 33.0) is colinear with segment from (249.0, 33.0) to (251.0, 18.0)
* uni0DF2 (U+0DF2): from (244.0, 138.0) to (244.0, 110.0) is colinear with segment from (244.0, 110.0) to (249.0, 33.0)
* uni0DF2 (U+0DF2): from (244.0, 110.0) to (249.0, 33.0) is colinear with segment from (249.0, 33.0) to (251.0, 18.0)
* uni0DF2 (U+0DF2): from (548.0, 138.0) to (548.0, 110.0) is colinear with segment from (548.0, 110.0) to (553.0, 33.0)
* uni0DF2 (U+0DF2): from (548.0, 110.0) to (553.0, 33.0) is colinear with segment from (553.0, 33.0) to (555.0, 18.0)
* rUsinh: from (586.0, 474.0) to (586.0, 474.0) is colinear with segment from (586.0, 474.0) to (750.0, 473.0)
* logo (U+E000): from (810.0, 575.0) to (809.0, 618.0) is colinear with segment from (809.0, 618.0) to (809.0, 633.0)
* rAesinh: from (380.0, 646.0) to (381.0, 646.0) is colinear with segment from (381.0, 646.0) to (534.0, 644.0)
* nine (U+0039): from (95.0, 122.0) to (95.0, 121.0) is colinear with segment from (95.0, 121.0) to (96.0, 111.0) [code: found-colinear-vectors]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? (outline_jaggy_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have jaggy segments:

* uni0DC1 (U+0DC1): Quad(QuadBez { p0: (493.0, 404.0), p1: (531.0, 346.0), p2: (532.0, 260.0) })/Line(Line { p0: (532.0, 260.0), p1: (532.0, 261.0) }) = 0.6661999701832053 degrees
* kSsasinh: Quad(QuadBez { p0: (523.0, 57.0), p1: (461.0, 104.0), p2: (449.0, 184.0) })/Quad(QuadBez { p0: (449.0, 184.0), p1: (449.0, 154.0), p2: (442.0, 127.0) }) = 8.530765609948139 degrees
* kSsasinh: Quad(QuadBez { p0: (446.0, 228.0), p1: (447.0, 227.0), p2: (447.0, 225.0) })/Quad(QuadBez { p0: (447.0, 225.0), p1: (449.0, 300.0), p2: (497.0, 348.0) }) = 1.5275254422129318 degrees
* nDasinh: Quad(QuadBez { p0: (415.5, 91.5), p1: (399.0, 120.0), p2: (396.0, 160.0) })/Quad(QuadBez { p0: (396.0, 160.0), p1: (391.0, 113.0), p2: (367.0, 79.0) }) = 10.361609736026754 degrees
* nDasinh: Quad(QuadBez { p0: (393.0, 231.0), p1: (396.0, 215.0), p2: (397.0, 199.0) })/Quad(QuadBez { p0: (397.0, 199.0), p1: (402.0, 236.0), p2: (417.5, 263.5) }) = 11.27238609701398 degrees
* vIsinh: Quad(QuadBez { p0: (320.0, 617.0), p1: (379.0, 599.0), p2: (421.0, 560.0) })/Quad(QuadBez { p0: (421.0, 560.0), p1: (409.0, 574.0), p2: (418.0, 590.0) }) = 6.5198017516569164 degrees
* logo (U+E000): Quad(QuadBez { p0: (800.0, 237.0), p1: (808.0, 240.0), p2: (817.0, 242.0) })/Quad(QuadBez { p0: (817.0, 242.0), p1: (816.0, 242.0), p2: (815.0, 244.0) }) = 12.528807709151492 degrees
* rAesinh: Quad(QuadBez { p0: (446.0, 108.0), p1: (436.0, 136.0), p2: (435.0, 178.0) })/Quad(QuadBez { p0: (435.0, 178.0), p1: (435.0, 177.0), p2: (434.0, 176.0) }) = 1.3639275316029233 degrees
* rAesinh: Quad(QuadBez { p0: (435.0, 314.0), p1: (438.0, 304.0), p2: (439.0, 292.0) })/Quad(QuadBez { p0: (439.0, 292.0), p1: (446.0, 349.0), p2: (457.0, 406.5) }) = 11.764909248221517 degrees [code: found-jaggy-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? (outline_semi_vertical)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

* uni0D87 (U+0D87): Line(Line { p0: (665.0, 427.0), p1: (550.0, 428.0) }) (angle: 179.50 degrees, expected: 180.00 degrees)
* uni0D87 (U+0D87): Line(Line { p0: (550.0, 474.0), p1: (714.0, 473.0) }) (angle: -0.35 degrees, expected: 0.00 degrees)
* uni0D88 (U+0D88): Line(Line { p0: (542.0, 474.0), p1: (701.0, 475.0) }) (angle: 0.36 degrees, expected: 0.00 degrees)
* uni0D92 (U+0D92): Line(Line { p0: (352.0, 494.0), p1: (351.0, 660.0) }) (angle: 90.35 degrees, expected: 90.00 degrees)
* uni0DA0 (U+0DA0): Line(Line { p0: (326.0, 311.0), p1: (196.0, 312.0) }) (angle: 179.56 degrees, expected: 180.00 degrees)
* uni0DA4 (U+0DA4): Line(Line { p0: (903.0, 94.0), p1: (905.0, -155.0) }) (angle: -89.54 degrees, expected: -90.00 degrees)
* uni0DA4 (U+0DA4): Line(Line { p0: (859.0, -155.0), p1: (858.0, 50.0) }) (angle: 90.28 degrees, expected: 90.00 degrees)
* uni0DA5 (U+0DA5): Line(Line { p0: (927.0, 80.0), p1: (928.0, -166.0) }) (angle: -89.77 degrees, expected: -90.00 degrees)
* uni0DAF (U+0DAF): Line(Line { p0: (482.0, 97.0), p1: (484.0, -178.0) }) (angle: -89.58 degrees, expected: -90.00 degrees)
* uni0DB3 (U+0DB3): Line(Line { p0: (595.0, 97.0), p1: (597.0, -178.0) }) (angle: -89.58 degrees, expected: -90.00 degrees)
* nDasinh: Line(Line { p0: (744.0, 80.0), p1: (746.0, -182.0) }) (angle: -89.56 degrees, expected: -90.00 degrees)
* nDasinh: Line(Line { p0: (708.0, -182.0), p1: (707.0, 34.0) }) (angle: 90.27 degrees, expected: 90.00 degrees)
* uni0DD1 (U+0DD1): Line(Line { p0: (29.0, 474.0), p1: (188.0, 475.0) }) (angle: 0.36 degrees, expected: 0.00 degrees)
* uni0DD0 (U+0DD0): Line(Line { p0: (152.0, 427.0), p1: (37.0, 428.0) }) (angle: 179.50 degrees, expected: 180.00 degrees)
* uni0DD0 (U+0DD0): Line(Line { p0: (37.0, 474.0), p1: (201.0, 473.0) }) (angle: -0.35 degrees, expected: 0.00 degrees)
* uni0DDA (U+0DDA): Line(Line { p0: (291.0, 494.0), p1: (290.0, 660.0) }) (angle: 90.35 degrees, expected: 90.00 degrees)
* uni0DDD (U+0DDD): Line(Line { p0: (538.0, 494.0), p1: (537.0, 660.0) }) (angle: 90.35 degrees, expected: 90.00 degrees)
* uni0DD4 (U+0DD4): Line(Line { p0: (-94.0, -220.0), p1: (-471.0, -222.0) }) (angle: -179.70 degrees, expected: -180.00 degrees)
* uni0DD4 (U+0DD4): Line(Line { p0: (-468.0, -172.0), p1: (-119.0, -170.0) }) (angle: 0.33 degrees, expected: 0.00 degrees)
* uni0DD4 (U+0DD4): Line(Line { p0: (-71.0, 84.0), p1: (-69.0, -195.0) }) (angle: -89.59 degrees, expected: -90.00 degrees)
* uni0DD6 (U+0DD6): Line(Line { p0: (-120.0, -151.0), p1: (-122.0, 82.0) }) (angle: 90.49 degrees, expected: 90.00 degrees)
* uni0DCA (U+0DCA): Line(Line { p0: (-184.0, 494.0), p1: (-185.0, 660.0) }) (angle: 90.35 degrees, expected: 90.00 degrees)
* viramasinh.alt1: Line(Line { p0: (-184.0, 494.0), p1: (-185.0, 660.0) }) (angle: 90.35 degrees, expected: 90.00 degrees)
* csinh: Line(Line { p0: (304.0, 309.0), p1: (184.0, 310.0) }) (angle: 179.52 degrees, expected: 180.00 degrees)
* chsinh: Line(Line { p0: (272.0, 495.0), p1: (271.0, 662.0) }) (angle: 90.34 degrees, expected: 90.00 degrees)
* jsinh: Line(Line { p0: (272.0, 495.0), p1: (271.0, 662.0) }) (angle: 90.34 degrees, expected: 90.00 degrees)
* cIsinh: Line(Line { p0: (313.0, 309.0), p1: (193.0, 310.0) }) (angle: 179.52 degrees, expected: 180.00 degrees)
* dIsinh: Line(Line { p0: (499.0, 98.0), p1: (500.0, -177.0) }) (angle: -89.79 degrees, expected: -90.00 degrees)
* ndIsinh: Line(Line { p0: (576.0, 97.0), p1: (578.0, -176.0) }) (angle: -89.58 degrees, expected: -90.00 degrees)
* cIisinh: Line(Line { p0: (313.0, 312.0), p1: (193.0, 313.0) }) (angle: 179.52 degrees, expected: 180.00 degrees)
* dIisinh: Line(Line { p0: (517.0, 98.0), p1: (519.0, -177.0) }) (angle: -89.58 degrees, expected: -90.00 degrees)
* ndIisinh: Line(Line { p0: (582.0, 96.0), p1: (584.0, -179.0) }) (angle: -89.58 degrees, expected: -90.00 degrees)
* ndIisinh: Line(Line { p0: (533.0, -179.0), p1: (532.0, 48.0) }) (angle: 90.25 degrees, expected: 90.00 degrees)
* dUsinh: Line(Line { p0: (455.0, -228.0), p1: (90.0, -230.0) }) (angle: -179.69 degrees, expected: -180.00 degrees)
* dUsinh: Line(Line { p0: (93.0, -181.0), p1: (430.0, -179.0) }) (angle: 0.34 degrees, expected: 0.00 degrees)
* ndUsinh: Line(Line { p0: (565.0, -235.0), p1: (188.0, -236.0) }) (angle: -179.85 degrees, expected: -180.00 degrees)
* ndUsinh: Line(Line { p0: (190.0, -186.0), p1: (539.0, -185.0) }) (angle: 0.16 degrees, expected: 0.00 degrees)
* rUsinh: Line(Line { p0: (701.0, 427.0), p1: (586.0, 428.0) }) (angle: 179.50 degrees, expected: 180.00 degrees)
* rUsinh: Line(Line { p0: (586.0, 474.0), p1: (750.0, 473.0) }) (angle: -0.35 degrees, expected: 0.00 degrees)
* lUsinh: Line(Line { p0: (504.0, -222.0), p1: (127.0, -223.0) }) (angle: -179.85 degrees, expected: -180.00 degrees)
* lUsinh: Line(Line { p0: (129.0, -173.0), p1: (478.0, -172.0) }) (angle: 0.16 degrees, expected: 0.00 degrees)
* rUusinh: Line(Line { p0: (578.0, 474.0), p1: (737.0, 475.0) }) (angle: 0.36 degrees, expected: 0.00 degrees)
* lUusinh: Line(Line { p0: (479.0, -183.0), p1: (478.0, -67.0) }) (angle: 90.49 degrees, expected: 90.00 degrees)
* rAaesinh: Line(Line { p0: (381.0, 642.0), p1: (522.0, 643.0) }) (angle: 0.41 degrees, expected: 0.00 degrees)
* one (U+0031): Line(Line { p0: (40.0, 25.0), p1: (41.0, 489.0) }) (angle: 89.88 degrees, expected: 90.00 degrees)
* three (U+0033): Line(Line { p0: (297.0, 464.0), p1: (93.0, 463.0) }) (angle: -179.72 degrees, expected: -180.00 degrees)
* three (U+0033): Line(Line { p0: (82.0, 513.0), p1: (339.0, 514.0) }) (angle: 0.22 degrees, expected: 0.00 degrees)
* four (U+0034): Line(Line { p0: (383.0, 0.0), p1: (173.0, 1.0) }) (angle: 179.73 degrees, expected: 180.00 degrees)
* four (U+0034): Line(Line { p0: (95.0, 204.0), p1: (253.0, 203.0) }) (angle: -0.36 degrees, expected: 0.00 degrees)
* four (U+0034): Line(Line { p0: (253.0, 203.0), p1: (254.0, 429.0) }) (angle: 89.75 degrees, expected: 90.00 degrees) [code: found-semi-vertical]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments (overlapping_path_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlapping path segments:

* uni0DA0 (U+0DA0): Quad(QuadBez { p0: (275.0, 361.0), p1: (275.0, 361.0), p2: (275.0, 361.0) }) has the same coordinates as a previous segment.
* csinh: Quad(QuadBez { p0: (257.0, 359.0), p1: (257.0, 359.0), p2: (257.0, 359.0) }) has the same coordinates as a previous segment.
* cIsinh: Quad(QuadBez { p0: (266.0, 359.0), p1: (266.0, 359.0), p2: (266.0, 359.0) }) has the same coordinates as a previous segment.
* bIsinh: Quad(QuadBez { p0: (69.0, 554.0), p1: (69.0, 554.0), p2: (69.0, 554.0) }) has the same coordinates as a previous segment.
* cIisinh: Quad(QuadBez { p0: (266.0, 362.0), p1: (266.0, 362.0), p2: (266.0, 362.0) }) has the same coordinates as a previous segment.
* logo (U+E000): Quad(QuadBez { p0: (788.0, 242.0), p1: (788.0, 242.0), p2: (788.0, 242.0) }) has the same coordinates as a previous segment. [code: overlapping-path-segments]
  
  

</div>
</details>


</div>
</details>


<details><summary>[1] fonts/ttf</summary>
<div>


<details>
    <summary>⚠️ <b>WARN</b> Ensure Fonts have 'ital' STAT axis. (opentype/STAT/ital_axis)</summary>
    <div>








- ⚠️ **WARN** Static font is missing the 'STAT' table. [code: no-stat-table]
  
  

</div>
</details>


</div>
</details>






### Summary

| ⚠️ WARN | ℹ️ INFO | ✅ PASS | ⏩ SKIP | 
| ---|---|---|---|
| 13 | 12 | 81 | 51 | 
| 8% | 8% | 52% | 32% | 



