## Fontbakery report

Fontbakery version: 0.8.11

<details><summary><b>[13] QldSchool-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check family name for GF Guide compliance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_name_compliance">com.google.fonts/check/name/family_name_compliance</a>)</summary><div>


* 🔥 **FAIL** "QldSchool" is a CamelCased name. To solve this, simply use spaces instead in the font name. [code: camelcase]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 2875, but got 2576 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 1245, but got 903 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.11, while a newer 0.10.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* 🔥 **FAIL** Font is not italic, so post.italicAngle should be equal to zero. [code: non-zero-upright]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.7395x (3479) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- i.cv04

	- i.cv05

	- m.cv04

	- m.cv05

	- n.cv04

	- n.cv05

	- u.cv04

	- u.cv05

	- x.cv04 

	- x.cv05
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: oslash	Contours detected: 2	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: oslash	Contours detected: 2	Expected: 3 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 1365 among a set of 2 math glyphs.
The following math glyphs have a different width, though:

Width = 1159:
plus

Width = 1277:
less

Width = 1285:
greater

Width = 1283:
plusminus

Width = 1361:
multiply

Width = 1357:
divide

Width = 1359:
minus

Width = 1363:
approxequal

Width = 1300:
lessequal

Width = 1297:
greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* five (U+0035): X=392.5,Y=-1.0 (should be at baseline 0?)

	* J (U+004A): X=169.0,Y=1.0 (should be at baseline 0?)

	* Q (U+0051): X=627.5,Y=1.0 (should be at baseline 0?)

	* X (U+0058): X=1494.5,Y=1956.5 (should be at cap-height 1958?)

	* e (U+0065): X=286.0,Y=0.5 (should be at baseline 0?)

	* j (U+006A): X=-311.5,Y=-901.5 (should be at descender -903?)

	* j (U+006A): X=-425.0,Y=-904.0 (should be at descender -903?)

	* x (U+0078): X=263.5,Y=1054.5 (should be at x-height 1055?)

	* x (U+0078): X=952.0,Y=1054.0 (should be at x-height 1055?)

	* x (U+0078): X=102.0,Y=-0.5 (should be at baseline 0?)

	* y (U+0079): X=110.0,Y=-902.0 (should be at descender -903?)

	* yen (U+00A5): X=405.0,Y=1960.0 (should be at cap-height 1958?)

	* Aring (U+00C5): X=1188.5,Y=2575.0 (should be at ascender 2576?)

	* ae (U+00E6): X=1068.0,Y=0.5 (should be at baseline 0?)

	* egrave (U+00E8): X=286.0,Y=0.5 (should be at baseline 0?)

	* eacute (U+00E9): X=286.0,Y=0.5 (should be at baseline 0?)

	* ecircumflex (U+00EA): X=286.0,Y=0.5 (should be at baseline 0?)

	* edieresis (U+00EB): X=286.0,Y=0.5 (should be at baseline 0?)

	* oslash (U+00F8): X=479.0,Y=-2.0 (should be at baseline 0?)

	* yacute (U+00FD): X=110.0,Y=-902.0 (should be at descender -903?)

	* ydieresis (U+00FF): X=110.0,Y=-902.0 (should be at descender -903?)

	* emacron (U+0113): X=286.0,Y=0.5 (should be at baseline 0?)

	* edotaccent (U+0117): X=286.0,Y=0.5 (should be at baseline 0?)

	* eogonek (U+0119): X=286.0,Y=0.5 (should be at baseline 0?)

	* ecaron (U+011B): X=286.0,Y=0.5 (should be at baseline 0?)

	* IJ (U+0132): X=1080.0,Y=1.0 (should be at baseline 0?)

	* ij (U+0133): X=236.5,Y=-901.5 (should be at descender -903?)

	* ij (U+0133): X=123.0,Y=-904.0 (should be at descender -903?)

	* Ncaron (U+0147): X=1223.0,Y=2578.0 (should be at ascender 2576?)

	* oe (U+0153): X=957.0,Y=0.5 (should be at baseline 0?)

	* Uring (U+016E): X=1214.5,Y=2575.0 (should be at ascender 2576?)

	* ycircumflex (U+0177): X=110.0,Y=-902.0 (should be at descender -903?)

	* uni0237 (U+0237): X=-418.5,Y=-901.0 (should be at descender -903?)

	* uni0237 (U+0237): X=-535.5,Y=-902.5 (should be at descender -903?)

	* uni1E3E (U+1E3E): X=1768.0,Y=2574.0 (should be at ascender 2576?)

	* uni1EBD (U+1EBD): X=286.0,Y=0.5 (should be at baseline 0?)

	* ygrave (U+1EF3): X=110.0,Y=-902.0 (should be at descender -903?)

	* uni1EF9 (U+1EF9): X=110.0,Y=-902.0 (should be at descender -903?) 

	* notequal (U+2260): X=531.0,Y=-2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* dollar (U+0024) contains a short segment B<<492.0,261.0>-<509.0,261.0>-<527.5,261.0>>

	* dollar (U+0024) contains a short segment B<<527.5,261.0>-<546.0,261.0>-<566.0,262.0>>

	* asterisk (U+002A) contains a short segment L<<744.0,1446.0>--<744.0,1443.0>>

	* asterisk (U+002A) contains a short segment L<<504.0,1431.0>--<497.0,1429.0>>

	* asterisk (U+002A) contains a short segment L<<575.0,1861.0>--<576.0,1865.0>>

	* asterisk (U+002A) contains a short segment L<<813.0,1874.0>--<816.0,1875.0>>

	* five (U+0035) contains a short segment B<<607.0,1327.0>-<629.0,1329.0>-<649.0,1329.0>>

	* at (U+0040) contains a short segment B<<1525.0,396.0>-<1524.0,386.0>-<1521.5,365.0>>

	* at (U+0040) contains a short segment B<<1521.5,365.0>-<1519.0,344.0>-<1517.0,321.0>>

	* at (U+0040) contains a short segment B<<1517.0,321.0>-<1515.0,296.0>-<1516.5,275.0>>

	* at (U+0040) contains a short segment B<<1516.5,275.0>-<1518.0,254.0>-<1525.0,254.0>>

	* at (U+0040) contains a short segment B<<1525.0,254.0>-<1530.0,254.0>-<1564.0,293.5>>

	* at (U+0040) contains a short segment B<<1249.0,-58.0>-<1273.0,-94.0>-<1278.0,-129.0>>

	* at (U+0040) contains a short segment B<<1278.0,-129.0>-<1283.0,-164.0>-<1255.0,-203.0>>

	* at (U+0040) contains a short segment B<<1228.0,268.0>-<1226.0,266.0>-<1223.5,263.0>>

	* at (U+0040) contains a short segment B<<1223.5,263.0>-<1221.0,260.0>-<1219.0,258.0>>

	* I (U+0049) contains a short segment L<<492.0,1718.0>--<488.0,1718.0>>

	* I (U+0049) contains a short segment L<<541.0,236.0>--<545.0,236.0>>

	* M (U+004D) contains a short segment B<<155.0,0.0>-<121.0,0.0>-<85.0,17.5>>

	* M (U+004D) contains a short segment B<<85.0,17.5>-<49.0,35.0>-<33.0,63.0>>

	* M (U+004D) contains a short segment B<<33.0,63.0>-<18.0,92.0>-<18.5,127.0>>

	* W (U+0057) contains a short segment B<<1312.0,1864.0>-<1326.0,1893.0>-<1355.0,1925.5>>

	* W (U+0057) contains a short segment B<<2492.0,1958.0>-<2528.0,1958.0>-<2557.5,1928.5>>

	* d (U+0064) contains a short segment B<<823.0,370.0>-<813.0,358.0>-<804.0,345.5>>

	* d (U+0064) contains a short segment B<<804.0,345.5>-<795.0,333.0>-<785.0,322.0>>

	* d (U+0064) contains a short segment B<<1118.0,299.0>-<1135.0,299.0>-<1150.0,308.0>>

	* d (U+0064) contains a short segment B<<1150.0,308.0>-<1165.0,317.0>-<1171.0,325.0>>

	* k (U+006B) contains a short segment B<<877.0,811.0>-<877.0,828.0>-<863.5,839.5>>

	* k (U+006B) contains a short segment B<<863.5,839.5>-<850.0,851.0>-<831.0,851.0>>

	* m (U+006D) contains a short segment B<<197.0,928.0>-<200.0,946.0>-<216.5,976.0>>

	* q (U+0071) contains a short segment B<<821.0,412.0>-<813.0,403.0>-<805.0,393.0>>

	* q (U+0071) contains a short segment B<<805.0,393.0>-<797.0,383.0>-<789.0,372.0>>

	* w (U+0077) contains a short segment B<<387.0,257.5>-<391.0,231.0>-<406.0,231.0>>

	* w (U+0077) contains a short segment B<<1096.5,262.0>-<1097.0,226.0>-<1113.0,226.0>>

	* cent (U+00A2) contains a short segment B<<339.0,-10.0>-<328.0,-11.0>-<306.5,-12.0>>

	* cent (U+00A2) contains a short segment B<<306.5,-12.0>-<285.0,-13.0>-<274.0,-13.0>>

	* cent (U+00A2) contains a short segment B<<594.0,475.0>-<602.0,488.0>-<606.0,494.0>>

	* copyright (U+00A9) contains a short segment B<<1160.5,651.0>-<1163.0,632.0>-<1176.0,632.0>>

	* Igrave (U+00CC) contains a short segment L<<492.0,1718.0>--<488.0,1718.0>>

	* Igrave (U+00CC) contains a short segment L<<541.0,236.0>--<545.0,236.0>>

	* Iacute (U+00CD) contains a short segment L<<492.0,1718.0>--<488.0,1718.0>>

	* Iacute (U+00CD) contains a short segment L<<541.0,236.0>--<545.0,236.0>>

	* Icircumflex (U+00CE) contains a short segment L<<492.0,1718.0>--<488.0,1718.0>>

	* Icircumflex (U+00CE) contains a short segment L<<541.0,236.0>--<545.0,236.0>>

	* Idieresis (U+00CF) contains a short segment L<<492.0,1718.0>--<488.0,1718.0>>

	* Idieresis (U+00CF) contains a short segment L<<541.0,236.0>--<545.0,236.0>>

	* ae (U+00E6) contains a short segment B<<1150.0,260.0>-<1161.0,250.0>-<1177.5,242.0>>

	* ae (U+00E6) contains a short segment B<<1177.5,242.0>-<1194.0,234.0>-<1213.0,234.0>>

	* dcaron (U+010F) contains a short segment B<<823.0,370.0>-<813.0,358.0>-<804.0,345.5>>

	* dcaron (U+010F) contains a short segment B<<804.0,345.5>-<795.0,333.0>-<785.0,322.0>>

	* dcaron (U+010F) contains a short segment B<<1118.0,299.0>-<1135.0,299.0>-<1150.0,308.0>>

	* dcaron (U+010F) contains a short segment B<<1150.0,308.0>-<1165.0,317.0>-<1171.0,325.0>>

	* dcroat (U+0111) contains a short segment B<<823.0,370.0>-<813.0,358.0>-<804.0,345.5>>

	* dcroat (U+0111) contains a short segment B<<804.0,345.5>-<795.0,333.0>-<785.0,322.0>>

	* dcroat (U+0111) contains a short segment B<<1118.0,299.0>-<1135.0,299.0>-<1150.0,308.0>>

	* dcroat (U+0111) contains a short segment B<<1150.0,308.0>-<1165.0,317.0>-<1171.0,325.0>>

	* Itilde (U+0128) contains a short segment L<<492.0,1718.0>--<488.0,1718.0>>

	* Itilde (U+0128) contains a short segment L<<541.0,236.0>--<545.0,236.0>>

	* Imacron (U+012A) contains a short segment L<<492.0,1718.0>--<488.0,1718.0>>

	* Imacron (U+012A) contains a short segment L<<541.0,236.0>--<545.0,236.0>>

	* Iogonek (U+012E) contains a short segment L<<492.0,1718.0>--<488.0,1718.0>>

	* Iogonek (U+012E) contains a short segment L<<541.0,236.0>--<545.0,236.0>>

	* Idotaccent (U+0130) contains a short segment L<<492.0,1718.0>--<488.0,1718.0>>

	* Idotaccent (U+0130) contains a short segment L<<541.0,236.0>--<545.0,236.0>>

	* IJ (U+0132) contains a short segment L<<492.0,1718.0>--<488.0,1718.0>>

	* IJ (U+0132) contains a short segment L<<541.0,236.0>--<545.0,236.0>>

	* uni0137 (U+0137) contains a short segment B<<877.0,811.0>-<877.0,828.0>-<863.5,839.5>>

	* uni0137 (U+0137) contains a short segment B<<863.5,839.5>-<850.0,851.0>-<831.0,851.0>>

	* Lslash (U+0141) contains a short segment L<<218.0,546.0>--<195.0,533.0>>

	* Wcircumflex (U+0174) contains a short segment B<<1312.0,1864.0>-<1326.0,1893.0>-<1355.0,1925.5>>

	* Wcircumflex (U+0174) contains a short segment B<<2492.0,1958.0>-<2528.0,1958.0>-<2557.5,1928.5>>

	* wcircumflex (U+0175) contains a short segment B<<387.0,257.5>-<391.0,231.0>-<406.0,231.0>>

	* wcircumflex (U+0175) contains a short segment B<<1096.5,262.0>-<1097.0,226.0>-<1113.0,226.0>>

	* uni01CF (U+01CF) contains a short segment L<<492.0,1718.0>--<488.0,1718.0>>

	* uni01CF (U+01CF) contains a short segment L<<541.0,236.0>--<545.0,236.0>>

	* uni1E3E (U+1E3E) contains a short segment B<<155.0,0.0>-<121.0,0.0>-<85.0,17.5>>

	* uni1E3E (U+1E3E) contains a short segment B<<85.0,17.5>-<49.0,35.0>-<33.0,63.0>>

	* uni1E3E (U+1E3E) contains a short segment B<<33.0,63.0>-<18.0,92.0>-<18.5,127.0>>

	* uni1E3F (U+1E3F) contains a short segment B<<197.0,928.0>-<200.0,946.0>-<216.5,976.0>>

	* Wgrave (U+1E80) contains a short segment B<<1312.0,1864.0>-<1326.0,1893.0>-<1355.0,1925.5>>

	* Wgrave (U+1E80) contains a short segment B<<2492.0,1958.0>-<2528.0,1958.0>-<2557.5,1928.5>>

	* wgrave (U+1E81) contains a short segment B<<387.0,257.5>-<391.0,231.0>-<406.0,231.0>>

	* wgrave (U+1E81) contains a short segment B<<1096.5,262.0>-<1097.0,226.0>-<1113.0,226.0>>

	* Wacute (U+1E82) contains a short segment B<<1312.0,1864.0>-<1326.0,1893.0>-<1355.0,1925.5>>

	* Wacute (U+1E82) contains a short segment B<<2492.0,1958.0>-<2528.0,1958.0>-<2557.5,1928.5>>

	* wacute (U+1E83) contains a short segment B<<387.0,257.5>-<391.0,231.0>-<406.0,231.0>>

	* wacute (U+1E83) contains a short segment B<<1096.5,262.0>-<1097.0,226.0>-<1113.0,226.0>>

	* Wdieresis (U+1E84) contains a short segment B<<1312.0,1864.0>-<1326.0,1893.0>-<1355.0,1925.5>>

	* Wdieresis (U+1E84) contains a short segment B<<2492.0,1958.0>-<2528.0,1958.0>-<2557.5,1928.5>>

	* wdieresis (U+1E85) contains a short segment B<<387.0,257.5>-<391.0,231.0>-<406.0,231.0>>

	* wdieresis (U+1E85) contains a short segment B<<1096.5,262.0>-<1097.0,226.0>-<1113.0,226.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<769.0,0.0>-<748.0,1.0>-<713.5,11.5>>

	* daggerdbl (U+2021) contains a short segment L<<461.0,781.0>--<432.0,781.0>>

	* Euro (U+20AC) contains a short segment B<<752.0,1033.0>-<748.0,1009.0>-<742.0,975.0>>

	* Euro (U+20AC) contains a short segment B<<1696.0,652.0>-<1696.0,632.0>-<1685.5,602.5>>

	* Euro (U+20AC) contains a short segment B<<436.0,978.0>-<442.0,1012.0>-<445.0,1027.0>>

	* estimated (U+212E) contains a short segment B<<573.0,948.0>-<554.0,948.0>-<542.5,940.5>>

	* estimated (U+212E) contains a short segment B<<542.5,940.5>-<531.0,933.0>-<531.0,896.0>> 

	* notequal (U+2260) contains a short segment L<<1047.0,1004.0>--<1072.0,1004.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* ordfeminine (U+00AA): B<<905.5,1239.5>-<865.0,1279.0>-<882.0,1351.0>>/L<<882.0,1351.0>--<864.0,1276.0>> = 0.21086679589269736 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[10] QldSchool-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check family name for GF Guide compliance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_name_compliance">com.google.fonts/check/name/family_name_compliance</a>)</summary><div>


* 🔥 **FAIL** "QldSchool" is a CamelCased name. To solve this, simply use spaces instead in the font name. [code: camelcase]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 2875, but got 2576 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 1245, but got 903 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.11, while a newer 0.10.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* 🔥 **FAIL** Font is not italic, so post.italicAngle should be equal to zero. [code: non-zero-upright]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.7395x (3479) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- i.cv04

	- i.cv05

	- m.cv04

	- m.cv05

	- n.cv04

	- n.cv05

	- u.cv04

	- u.cv05

	- x.cv04 

	- x.cv05
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 1286 among a set of 2 math glyphs.
The following math glyphs have a different width, though:

Width = 1105:
plus

Width = 1196:
less

Width = 1199:
greater, plusminus

Width = 1284:
multiply, divide

Width = 1281:
minus

Width = 1285:
approxequal

Width = 1219:
lessequal

Width = 1231:
greaterequal
 [code: width-outliers]
</div></details><br></div></details><details><summary><b>[13] QldSchool-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check family name for GF Guide compliance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_name_compliance">com.google.fonts/check/name/family_name_compliance</a>)</summary><div>


* 🔥 **FAIL** "QldSchool" is a CamelCased name. To solve this, simply use spaces instead in the font name. [code: camelcase]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 2875, but got 2576 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 1245, but got 903 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.11, while a newer 0.10.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* 🔥 **FAIL** Font is not italic, so post.italicAngle should be equal to zero. [code: non-zero-upright]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.7395x (3479) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- i.cv04

	- i.cv05

	- m.cv04

	- m.cv05

	- n.cv04

	- n.cv05

	- u.cv04

	- u.cv05

	- x.cv04 

	- x.cv05
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 1335 among a set of 2 math glyphs.
The following math glyphs have a different width, though:

Width = 1139:
plus

Width = 1247:
less

Width = 1253:
greater

Width = 1252:
plusminus

Width = 1332:
multiply

Width = 1330:
minus, divide

Width = 1334:
approxequal

Width = 1270:
lessequal

Width = 1272:
greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* ampersand (U+0026): X=684.0,Y=-2.0 (should be at baseline 0?)

	* ampersand (U+0026): X=684.0,Y=-2.0 (should be at baseline 0?)

	* asterisk (U+002A): X=627.5,Y=1960.0 (should be at cap-height 1958?)

	* five (U+0035): X=385.5,Y=-1.0 (should be at baseline 0?)

	* at (U+0040): X=737.0,Y=-1.0 (should be at baseline 0?)

	* at (U+0040): X=1453.0,Y=1.0 (should be at baseline 0?)

	* at (U+0040): X=737.0,Y=-1.0 (should be at baseline 0?)

	* J (U+004A): X=147.0,Y=1.0 (should be at baseline 0?)

	* V (U+0056): X=1448.0,Y=1956.0 (should be at cap-height 1958?)

	* W (U+0057): X=2483.0,Y=1957.0 (should be at cap-height 1958?)

	* X (U+0058): X=1454.0,Y=1958.5 (should be at cap-height 1958?)

	* X (U+0058): X=1128.0,Y=0.5 (should be at baseline 0?)

	* d (U+0064): X=1068.0,Y=1.0 (should be at baseline 0?)

	* d (U+0064): X=1068.0,Y=1.0 (should be at baseline 0?)

	* e (U+0065): X=274.5,Y=0.5 (should be at baseline 0?)

	* h (U+0068): X=182.0,Y=1.0 (should be at baseline 0?)

	* h (U+0068): X=182.0,Y=1.0 (should be at baseline 0?)

	* j (U+006A): X=-331.5,Y=-901.5 (should be at descender -903?)

	* j (U+006A): X=-444.0,Y=-904.0 (should be at descender -903?)

	* x (U+0078): X=258.0,Y=1054.5 (should be at x-height 1055?)

	* x (U+0078): X=965.5,Y=1054.5 (should be at x-height 1055?)

	* x (U+0078): X=792.5,Y=0.5 (should be at baseline 0?)

	* x (U+0078): X=93.0,Y=-0.5 (should be at baseline 0?)

	* y (U+0079): X=98.5,Y=-902.0 (should be at descender -903?)

	* yen (U+00A5): X=395.0,Y=1959.0 (should be at cap-height 1958?)

	* brokenbar (U+00A6): X=787.0,Y=1956.0 (should be at cap-height 1958?)

	* section (U+00A7): X=830.0,Y=1959.0 (should be at cap-height 1958?)

	* section (U+00A7): X=1053.0,Y=1959.0 (should be at cap-height 1958?)

	* ae (U+00E6): X=1055.0,Y=0.5 (should be at baseline 0?)

	* egrave (U+00E8): X=274.5,Y=0.5 (should be at baseline 0?)

	* eacute (U+00E9): X=274.5,Y=0.5 (should be at baseline 0?)

	* ecircumflex (U+00EA): X=274.5,Y=0.5 (should be at baseline 0?)

	* edieresis (U+00EB): X=274.5,Y=0.5 (should be at baseline 0?)

	* yacute (U+00FD): X=98.5,Y=-902.0 (should be at descender -903?)

	* thorn (U+00FE): X=427.0,Y=1957.0 (should be at cap-height 1958?)

	* ydieresis (U+00FF): X=98.5,Y=-902.0 (should be at descender -903?)

	* dcaron (U+010F): X=1068.0,Y=1.0 (should be at baseline 0?)

	* dcaron (U+010F): X=1068.0,Y=1.0 (should be at baseline 0?)

	* dcroat (U+0111): X=1068.0,Y=1.0 (should be at baseline 0?)

	* dcroat (U+0111): X=1068.0,Y=1.0 (should be at baseline 0?)

	* emacron (U+0113): X=274.5,Y=0.5 (should be at baseline 0?)

	* edotaccent (U+0117): X=274.5,Y=0.5 (should be at baseline 0?)

	* eogonek (U+0119): X=274.5,Y=0.5 (should be at baseline 0?)

	* ecaron (U+011B): X=274.5,Y=0.5 (should be at baseline 0?)

	* hbar (U+0127): X=182.0,Y=1.0 (should be at baseline 0?)

	* hbar (U+0127): X=182.0,Y=1.0 (should be at baseline 0?)

	* IJ (U+0132): X=1033.0,Y=1.0 (should be at baseline 0?)

	* ij (U+0133): X=212.5,Y=-901.5 (should be at descender -903?)

	* ij (U+0133): X=100.0,Y=-904.0 (should be at descender -903?)

	* oe (U+0153): X=945.5,Y=0.5 (should be at baseline 0?)

	* Wcircumflex (U+0174): X=2483.0,Y=1957.0 (should be at cap-height 1958?)

	* ycircumflex (U+0177): X=98.5,Y=-902.0 (should be at descender -903?)

	* uni0237 (U+0237): X=-538.0,Y=-902.5 (should be at descender -903?)

	* Wgrave (U+1E80): X=2483.0,Y=1957.0 (should be at cap-height 1958?)

	* Wacute (U+1E82): X=2483.0,Y=1957.0 (should be at cap-height 1958?)

	* Wdieresis (U+1E84): X=2483.0,Y=1957.0 (should be at cap-height 1958?)

	* uni1E9E (U+1E9E): X=274.0,Y=-2.0 (should be at baseline 0?)

	* uni1EBD (U+1EBD): X=274.5,Y=0.5 (should be at baseline 0?)

	* ygrave (U+1EF3): X=98.5,Y=-902.0 (should be at descender -903?)

	* uni1EF9 (U+1EF9): X=98.5,Y=-902.0 (should be at descender -903?)

	* dagger (U+2020): X=918.0,Y=1956.0 (should be at cap-height 1958?)

	* daggerdbl (U+2021): X=918.0,Y=1956.0 (should be at cap-height 1958?) 

	* uniA78B (U+A78B): X=601.0,Y=1959.0 (should be at cap-height 1958?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* dollar (U+0024) contains a short segment B<<470.0,233.0>-<490.0,233.0>-<513.0,233.5>>

	* dollar (U+0024) contains a short segment B<<519.0,-9.0>-<506.0,-10.0>-<494.0,-10.0>>

	* dollar (U+0024) contains a short segment B<<494.0,-10.0>-<482.0,-10.0>-<470.0,-10.0>>

	* at (U+0040) contains a short segment B<<1498.0,397.0>-<1497.0,385.0>-<1493.5,357.0>>

	* at (U+0040) contains a short segment B<<1493.5,357.0>-<1490.0,329.0>-<1488.0,304.0>>

	* at (U+0040) contains a short segment B<<1488.0,304.0>-<1487.0,277.0>-<1488.0,253.0>>

	* at (U+0040) contains a short segment B<<1488.0,253.0>-<1489.0,229.0>-<1502.0,229.0>>

	* at (U+0040) contains a short segment B<<1502.0,229.0>-<1515.0,229.0>-<1555.0,271.5>>

	* at (U+0040) contains a short segment B<<1245.0,349.0>-<1234.0,330.0>-<1221.0,311.5>>

	* at (U+0040) contains a short segment B<<1221.0,311.5>-<1208.0,293.0>-<1194.0,275.0>>

	* C (U+0043) contains a short segment B<<1404.0,645.0>-<1404.0,626.0>-<1394.0,598.5>>

	* I (U+0049) contains a short segment L<<507.0,1745.0>--<490.0,1745.0>>

	* I (U+0049) contains a short segment L<<509.0,211.0>--<525.0,211.0>>

	* M (U+004D) contains a short segment B<<132.0,0.0>-<102.0,0.0>-<71.0,15.0>>

	* M (U+004D) contains a short segment B<<71.0,15.0>-<40.0,30.0>-<26.0,55.0>>

	* M (U+004D) contains a short segment B<<26.0,55.0>-<13.0,80.0>-<13.5,111.5>>

	* M (U+004D) contains a short segment B<<910.0,1866.0>-<932.0,1910.0>-<956.5,1934.0>>

	* W (U+0057) contains a short segment B<<1313.0,1870.0>-<1326.0,1898.0>-<1353.0,1928.0>>

	* W (U+0057) contains a short segment B<<2483.0,1957.0>-<2514.0,1956.0>-<2539.5,1930.0>>

	* W (U+0057) contains a short segment B<<2539.5,1930.0>-<2565.0,1904.0>-<2573.0,1863.5>>

	* k (U+006B) contains a short segment B<<880.0,825.0>-<880.0,843.0>-<866.0,857.0>>

	* k (U+006B) contains a short segment B<<866.0,857.0>-<852.0,871.0>-<830.0,871.0>>

	* m (U+006D) contains a short segment B<<211.0,940.0>-<214.0,959.0>-<229.0,986.0>>

	* m (U+006D) contains a short segment B<<1592.0,836.5>-<1585.0,862.0>-<1559.0,862.0>>

	* m (U+006D) contains a short segment B<<891.0,836.5>-<884.0,862.0>-<859.0,862.0>>

	* w (U+0077) contains a short segment B<<358.0,232.5>-<364.0,205.0>-<382.0,205.0>>

	* w (U+0077) contains a short segment B<<1844.5,1042.0>-<1869.0,1029.0>-<1880.0,1011.0>>

	* cent (U+00A2) contains a short segment B<<337.0,-8.0>-<325.0,-9.0>-<306.0,-9.5>>

	* cent (U+00A2) contains a short segment B<<306.0,-9.5>-<287.0,-10.0>-<278.0,-10.0>>

	* sterling (U+00A3) contains a short segment B<<173.5,16.0>-<149.0,32.0>-<143.0,55.0>>

	* sterling (U+00A3) contains a short segment B<<144.5,106.0>-<153.0,133.0>-<169.0,150.0>>

	* Ccedilla (U+00C7) contains a short segment B<<1404.0,645.0>-<1404.0,626.0>-<1394.0,598.5>>

	* Igrave (U+00CC) contains a short segment L<<507.0,1745.0>--<490.0,1745.0>>

	* Igrave (U+00CC) contains a short segment L<<509.0,211.0>--<525.0,211.0>>

	* Iacute (U+00CD) contains a short segment L<<507.0,1745.0>--<490.0,1745.0>>

	* Iacute (U+00CD) contains a short segment L<<509.0,211.0>--<525.0,211.0>>

	* Icircumflex (U+00CE) contains a short segment L<<507.0,1745.0>--<490.0,1745.0>>

	* Icircumflex (U+00CE) contains a short segment L<<509.0,211.0>--<525.0,211.0>>

	* Idieresis (U+00CF) contains a short segment L<<507.0,1745.0>--<490.0,1745.0>>

	* Idieresis (U+00CF) contains a short segment L<<509.0,211.0>--<525.0,211.0>>

	* Cacute (U+0106) contains a short segment B<<1404.0,645.0>-<1404.0,626.0>-<1394.0,598.5>>

	* Cdotaccent (U+010A) contains a short segment B<<1404.0,645.0>-<1404.0,626.0>-<1394.0,598.5>>

	* Ccaron (U+010C) contains a short segment B<<1404.0,645.0>-<1404.0,626.0>-<1394.0,598.5>>

	* Itilde (U+0128) contains a short segment L<<507.0,1745.0>--<490.0,1745.0>>

	* Itilde (U+0128) contains a short segment L<<509.0,211.0>--<525.0,211.0>>

	* Imacron (U+012A) contains a short segment L<<507.0,1745.0>--<490.0,1745.0>>

	* Imacron (U+012A) contains a short segment L<<509.0,211.0>--<525.0,211.0>>

	* Iogonek (U+012E) contains a short segment L<<507.0,1745.0>--<490.0,1745.0>>

	* Iogonek (U+012E) contains a short segment L<<509.0,211.0>--<525.0,211.0>>

	* Idotaccent (U+0130) contains a short segment L<<507.0,1745.0>--<490.0,1745.0>>

	* Idotaccent (U+0130) contains a short segment L<<509.0,211.0>--<525.0,211.0>>

	* IJ (U+0132) contains a short segment L<<507.0,1745.0>--<490.0,1745.0>>

	* IJ (U+0132) contains a short segment L<<509.0,211.0>--<525.0,211.0>>

	* uni0137 (U+0137) contains a short segment B<<880.0,825.0>-<880.0,843.0>-<866.0,857.0>>

	* uni0137 (U+0137) contains a short segment B<<866.0,857.0>-<852.0,871.0>-<830.0,871.0>>

	* lslash (U+0142) contains a short segment L<<498.0,1048.0>--<520.0,1056.0>>

	* eng (U+014B) contains a short segment B<<211.0,940.0>-<214.0,958.0>-<229.0,985.5>>

	* Wcircumflex (U+0174) contains a short segment B<<1313.0,1870.0>-<1326.0,1898.0>-<1353.0,1928.0>>

	* Wcircumflex (U+0174) contains a short segment B<<2483.0,1957.0>-<2514.0,1956.0>-<2539.5,1930.0>>

	* Wcircumflex (U+0174) contains a short segment B<<2539.5,1930.0>-<2565.0,1904.0>-<2573.0,1863.5>>

	* wcircumflex (U+0175) contains a short segment B<<358.0,232.5>-<364.0,205.0>-<382.0,205.0>>

	* wcircumflex (U+0175) contains a short segment B<<1844.5,1042.0>-<1869.0,1029.0>-<1880.0,1011.0>>

	* uni01CF (U+01CF) contains a short segment L<<507.0,1745.0>--<490.0,1745.0>>

	* uni01CF (U+01CF) contains a short segment L<<509.0,211.0>--<525.0,211.0>>

	* uni1E3E (U+1E3E) contains a short segment B<<132.0,0.0>-<102.0,0.0>-<71.0,15.0>>

	* uni1E3E (U+1E3E) contains a short segment B<<71.0,15.0>-<40.0,30.0>-<26.0,55.0>>

	* uni1E3E (U+1E3E) contains a short segment B<<26.0,55.0>-<13.0,80.0>-<13.5,111.5>>

	* uni1E3E (U+1E3E) contains a short segment B<<910.0,1866.0>-<932.0,1910.0>-<956.5,1934.0>>

	* uni1E3F (U+1E3F) contains a short segment B<<211.0,940.0>-<214.0,959.0>-<229.0,986.0>>

	* uni1E3F (U+1E3F) contains a short segment B<<1592.0,836.5>-<1585.0,862.0>-<1559.0,862.0>>

	* uni1E3F (U+1E3F) contains a short segment B<<891.0,836.5>-<884.0,862.0>-<859.0,862.0>>

	* Wgrave (U+1E80) contains a short segment B<<1313.0,1870.0>-<1326.0,1898.0>-<1353.0,1928.0>>

	* Wgrave (U+1E80) contains a short segment B<<2483.0,1957.0>-<2514.0,1956.0>-<2539.5,1930.0>>

	* Wgrave (U+1E80) contains a short segment B<<2539.5,1930.0>-<2565.0,1904.0>-<2573.0,1863.5>>

	* wgrave (U+1E81) contains a short segment B<<358.0,232.5>-<364.0,205.0>-<382.0,205.0>>

	* wgrave (U+1E81) contains a short segment B<<1844.5,1042.0>-<1869.0,1029.0>-<1880.0,1011.0>>

	* Wacute (U+1E82) contains a short segment B<<1313.0,1870.0>-<1326.0,1898.0>-<1353.0,1928.0>>

	* Wacute (U+1E82) contains a short segment B<<2483.0,1957.0>-<2514.0,1956.0>-<2539.5,1930.0>>

	* Wacute (U+1E82) contains a short segment B<<2539.5,1930.0>-<2565.0,1904.0>-<2573.0,1863.5>>

	* wacute (U+1E83) contains a short segment B<<358.0,232.5>-<364.0,205.0>-<382.0,205.0>>

	* wacute (U+1E83) contains a short segment B<<1844.5,1042.0>-<1869.0,1029.0>-<1880.0,1011.0>>

	* Wdieresis (U+1E84) contains a short segment B<<1313.0,1870.0>-<1326.0,1898.0>-<1353.0,1928.0>>

	* Wdieresis (U+1E84) contains a short segment B<<2483.0,1957.0>-<2514.0,1956.0>-<2539.5,1930.0>>

	* Wdieresis (U+1E84) contains a short segment B<<2539.5,1930.0>-<2565.0,1904.0>-<2573.0,1863.5>>

	* wdieresis (U+1E85) contains a short segment B<<358.0,232.5>-<364.0,205.0>-<382.0,205.0>>

	* wdieresis (U+1E85) contains a short segment B<<1844.5,1042.0>-<1869.0,1029.0>-<1880.0,1011.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<740.0,0.0>-<720.0,0.0>-<690.0,9.5>>

	* uni1E9E (U+1E9E) contains a short segment B<<690.0,9.5>-<660.0,19.0>-<636.5,44.5>>

	* uni1E9E (U+1E9E) contains a short segment B<<1791.5,1923.5>-<1822.0,1905.0>-<1839.0,1875.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<1839.0,1875.0>-<1854.0,1846.0>-<1851.5,1808.5>>

	* Euro (U+20AC) contains a short segment B<<1663.0,645.0>-<1663.0,626.0>-<1653.0,598.5>>

	* Euro (U+20AC) contains a short segment B<<439.0,974.5>-<445.0,1010.0>-<448.0,1025.0>>

	* estimated (U+212E) contains a short segment B<<573.0,948.0>-<554.0,948.0>-<542.5,940.5>> 

	* estimated (U+212E) contains a short segment B<<542.5,940.5>-<531.0,933.0>-<531.0,896.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* ordfeminine (U+00AA): B<<914.0,1235.5>-<878.0,1271.0>-<893.0,1335.0>>/L<<893.0,1335.0>--<881.0,1302.0>> = 6.792495809693081

	* oslash (U+00F8): B<<651.0,444.0>-<698.0,517.0>-<729.0,588.0>>/L<<729.0,588.0>--<670.0,486.0>> = 6.459404721682291 

	* oslash (U+00F8): L<<670.0,486.0>--<651.0,444.0>>/B<<651.0,444.0>-<698.0,517.0>-<729.0,588.0>> = 8.43378738757168 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[11] QldSchool-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check family name for GF Guide compliance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_name_compliance">com.google.fonts/check/name/family_name_compliance</a>)</summary><div>


* 🔥 **FAIL** "QldSchool" is a CamelCased name. To solve this, simply use spaces instead in the font name. [code: camelcase]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 2875, but got 2576 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 1245, but got 903 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.11, while a newer 0.10.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* 🔥 **FAIL** Font is not italic, so post.italicAngle should be equal to zero. [code: non-zero-upright]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.7395x (3479) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- i.cv04

	- i.cv05

	- m.cv04

	- m.cv05

	- n.cv04

	- n.cv05

	- u.cv04

	- u.cv05

	- x.cv04 

	- x.cv05
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 1216 among a set of 4 math glyphs.
The following math glyphs have a different width, though:

Width = 1057:
plus

Width = 1125:
less

Width = 1124:
greater

Width = 1126:
plusminus

Width = 1220:
divide

Width = 1212:
minus

Width = 1148:
lessequal

Width = 1173:
greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* numbersign (U+0023): X=490.0,Y=-1.0 (should be at baseline 0?)

	* numbersign (U+0023): X=490.0,Y=-1.0 (should be at baseline 0?)

	* dollar (U+0024): X=384.0,Y=1.0 (should be at baseline 0?)

	* dollar (U+0024): X=72.0,Y=1.0 (should be at baseline 0?)

	* dollar (U+0024): X=384.0,Y=1.0 (should be at baseline 0?)

	* five (U+0035): X=549.0,Y=1957.0 (should be at cap-height 1958?)

	* five (U+0035): X=1251.0,Y=1957.0 (should be at cap-height 1958?)

	* six (U+0036): X=1064.5,Y=1957.0 (should be at cap-height 1958?)

	* nine (U+0039): X=853.0,Y=1957.0 (should be at cap-height 1958?)

	* nine (U+0039): X=1222.0,Y=1957.0 (should be at cap-height 1958?)

	* C (U+0043): X=1383.5,Y=1956.5 (should be at cap-height 1958?)

	* J (U+004A): X=88.5,Y=1.0 (should be at baseline 0?)

	* N (U+004E): X=530.0,Y=1959.0 (should be at cap-height 1958?)

	* N (U+004E): X=1545.0,Y=1959.0 (should be at cap-height 1958?)

	* S (U+0053): X=45.5,Y=2.0 (should be at baseline 0?)

	* X (U+0058): X=1455.5,Y=1957.0 (should be at cap-height 1958?)

	* X (U+0058): X=114.0,Y=0.5 (should be at baseline 0?)

	* Y (U+0059): X=1375.5,Y=1956.5 (should be at cap-height 1958?)

	* a (U+0061): X=717.0,Y=1054.0 (should be at x-height 1055?)

	* a (U+0061): X=1024.0,Y=1054.0 (should be at x-height 1055?)

	* f (U+0066): X=269.0,Y=-1.0 (should be at baseline 0?)

	* f (U+0066): X=269.0,Y=-1.0 (should be at baseline 0?)

	* g (U+0067): X=101.5,Y=-901.0 (should be at descender -903?)

	* m (U+006D): X=152.0,Y=1.0 (should be at baseline 0?)

	* m (U+006D): X=873.0,Y=1.0 (should be at baseline 0?)

	* m (U+006D): X=152.0,Y=1.0 (should be at baseline 0?)

	* n (U+006E): X=152.0,Y=1.0 (should be at baseline 0?)

	* x (U+0078): X=1018.5,Y=1054.5 (should be at x-height 1055?)

	* x (U+0078): X=849.5,Y=1.5 (should be at baseline 0?)

	* x (U+0078): X=60.0,Y=1.0 (should be at baseline 0?)

	* y (U+0079): X=52.5,Y=-902.5 (should be at descender -903?)

	* yen (U+00A5): X=1390.5,Y=1956.5 (should be at cap-height 1958?)

	* section (U+00A7): X=1081.0,Y=1959.0 (should be at cap-height 1958?)

	* registered (U+00AE): X=1356.0,Y=1960.0 (should be at cap-height 1958?)

	* registered (U+00AE): X=561.5,Y=1960.0 (should be at cap-height 1958?)

	* cedilla (U+00B8): X=124.0,Y=-2.0 (should be at baseline 0?)

	* ordmasculine (U+00BA): X=492.5,Y=1956.5 (should be at cap-height 1958?)

	* Ccedilla (U+00C7): X=1383.5,Y=1956.5 (should be at cap-height 1958?)

	* Ccedilla (U+00C7): X=477.0,Y=-2.0 (should be at baseline 0?)

	* Ntilde (U+00D1): X=530.0,Y=1959.0 (should be at cap-height 1958?)

	* Ntilde (U+00D1): X=1545.0,Y=1959.0 (should be at cap-height 1958?)

	* Yacute (U+00DD): X=1375.5,Y=1956.5 (should be at cap-height 1958?)

	* germandbls (U+00DF): X=78.0,Y=-1.0 (should be at baseline 0?)

	* germandbls (U+00DF): X=78.0,Y=-1.0 (should be at baseline 0?)

	* ccedilla (U+00E7): X=271.0,Y=-2.0 (should be at baseline 0?)

	* ntilde (U+00F1): X=152.0,Y=1.0 (should be at baseline 0?)

	* yacute (U+00FD): X=52.5,Y=-902.5 (should be at descender -903?)

	* ydieresis (U+00FF): X=52.5,Y=-902.5 (should be at descender -903?)

	* Cacute (U+0106): X=1383.5,Y=1956.5 (should be at cap-height 1958?)

	* Cdotaccent (U+010A): X=1383.5,Y=1956.5 (should be at cap-height 1958?)

	* Ccaron (U+010C): X=1383.5,Y=1956.5 (should be at cap-height 1958?)

	* gbreve (U+011F): X=101.5,Y=-901.0 (should be at descender -903?)

	* gdotaccent (U+0121): X=101.5,Y=-901.0 (should be at descender -903?)

	* uni0123 (U+0123): X=101.5,Y=-901.0 (should be at descender -903?)

	* Iogonek (U+012E): X=363.0,Y=-2.0 (should be at baseline 0?)

	* IJ (U+0132): X=872.5,Y=1.0 (should be at baseline 0?)

	* Nacute (U+0143): X=530.0,Y=1959.0 (should be at cap-height 1958?)

	* Nacute (U+0143): X=1545.0,Y=1959.0 (should be at cap-height 1958?)

	* nacute (U+0144): X=152.0,Y=1.0 (should be at baseline 0?)

	* uni0145 (U+0145): X=530.0,Y=1959.0 (should be at cap-height 1958?)

	* uni0145 (U+0145): X=1545.0,Y=1959.0 (should be at cap-height 1958?)

	* uni0146 (U+0146): X=152.0,Y=1.0 (should be at baseline 0?)

	* Ncaron (U+0147): X=530.0,Y=1959.0 (should be at cap-height 1958?)

	* Ncaron (U+0147): X=1545.0,Y=1959.0 (should be at cap-height 1958?)

	* ncaron (U+0148): X=152.0,Y=1.0 (should be at baseline 0?)

	* eng (U+014B): X=152.0,Y=1.0 (should be at baseline 0?)

	* Sacute (U+015A): X=45.5,Y=2.0 (should be at baseline 0?)

	* Scedilla (U+015E): X=45.5,Y=2.0 (should be at baseline 0?)

	* Scedilla (U+015E): X=402.0,Y=-2.0 (should be at baseline 0?)

	* scedilla (U+015F): X=252.0,Y=-2.0 (should be at baseline 0?)

	* Scaron (U+0160): X=45.5,Y=2.0 (should be at baseline 0?)

	* uni0162 (U+0162): X=547.0,Y=-2.0 (should be at baseline 0?)

	* uni0163 (U+0163): X=205.0,Y=-2.0 (should be at baseline 0?)

	* Ycircumflex (U+0176): X=1375.5,Y=1956.5 (should be at cap-height 1958?)

	* ycircumflex (U+0177): X=52.5,Y=-902.5 (should be at descender -903?)

	* Ydieresis (U+0178): X=1375.5,Y=1956.5 (should be at cap-height 1958?)

	* uni0218 (U+0218): X=45.5,Y=2.0 (should be at baseline 0?)

	* uni0237 (U+0237): X=-524.5,Y=-901.5 (should be at descender -903?)

	* ogonek (U+02DB): X=448.0,Y=-2.0 (should be at baseline 0?)

	* uni0327 (U+0327): X=124.0,Y=-2.0 (should be at baseline 0?)

	* uni0328 (U+0328): X=448.0,Y=-2.0 (should be at baseline 0?)

	* uni1E21 (U+1E21): X=101.5,Y=-901.0 (should be at descender -903?)

	* uni1E3F (U+1E3F): X=152.0,Y=1.0 (should be at baseline 0?)

	* uni1E3F (U+1E3F): X=873.0,Y=1.0 (should be at baseline 0?)

	* uni1E3F (U+1E3F): X=152.0,Y=1.0 (should be at baseline 0?)

	* uni1E44 (U+1E44): X=530.0,Y=1959.0 (should be at cap-height 1958?)

	* uni1E44 (U+1E44): X=1545.0,Y=1959.0 (should be at cap-height 1958?)

	* uni1E45 (U+1E45): X=152.0,Y=1.0 (should be at baseline 0?)

	* uni1E9E (U+1E9E): X=815.0,Y=-1.0 (should be at baseline 0?)

	* uni1E9E (U+1E9E): X=815.0,Y=-1.0 (should be at baseline 0?)

	* Ygrave (U+1EF2): X=1375.5,Y=1956.5 (should be at cap-height 1958?)

	* ygrave (U+1EF3): X=52.5,Y=-902.5 (should be at descender -903?)

	* uni1EF8 (U+1EF8): X=1375.5,Y=1956.5 (should be at cap-height 1958?)

	* uni1EF9 (U+1EF9): X=52.5,Y=-902.5 (should be at descender -903?)

	* Euro (U+20AC): X=1640.0,Y=1956.5 (should be at cap-height 1958?)

	* uni2116 (U+2116): X=530.0,Y=1959.0 (should be at cap-height 1958?) 

	* uni2116 (U+2116): X=1545.0,Y=1959.0 (should be at cap-height 1958?) [code: found-misalignments]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 20 | 27 | 474 | 25 | 374 | 0 |
| 0% | 2% | 3% | 52% | 3% | 41% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
