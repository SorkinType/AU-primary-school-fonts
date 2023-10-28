## Fontbakery report

Fontbakery version: 0.8.11

<details><summary><b>[13] QldSchool-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check family name for GF Guide compliance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_name_compliance">com.google.fonts/check/name/family_name_compliance</a>)</summary><div>


* 🔥 **FAIL** "QldSchool" is a CamelCased name. To solve this, simply use spaces instead in the font name. [code: camelcase]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.11, while a newer 0.10.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_TransLatin_Pinyin is almost fulfilled. Missing codepoints:

	- 0x207F (SUPERSCRIPT LATIN SMALL LETTER N)


	- 0x030D (COMBINING VERTICAL LINE ABOVE)


	- 0x0358 (COMBINING DOT ABOVE RIGHT)


	- 0x1D3A (MODIFIER LETTER CAPITAL N)


	- 0x0114 (LATIN CAPITAL LETTER E WITH BREVE)


	- 0x012C (LATIN CAPITAL LETTER I WITH BREVE)
 

	- 0x014E (LATIN CAPITAL LETTER O WITH BREVE)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.7395x (3479) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- i.cv04

	- i.cv05

	- idotless_cedillabelowcomb

	- m.cv04

	- m.cv05

	- n.cv04

	- n.cv05

	- u.cv04

	- u.cv05

	- uni0131031B

	- uni01310324

	- uni01310325

	- uni01310326

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

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni02B9	Contours detected: 0	Expected: 1

	- Glyph name: uni02C8	Contours detected: 0	Expected: 1

	- Glyph name: lambda	Contours detected: 0	Expected: 1

	- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lambda	Contours detected: 0	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni02B9	Contours detected: 0	Expected: 1

	- Glyph name: uni02C8	Contours detected: 0	Expected: 1

	- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 1440 among a set of 3 math glyphs.
The following math glyphs have a different width, though:

Width = 1159:
plus

Width = 1340:
less

Width = 1345:
greater

Width = 1364:
plusminus

Width = 1478:
multiply

Width = 1358:
divide

Width = 1359:
minus

Width = 1466:
approxequal

Width = 1376:
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

	* yen (U+00A5): X=540.0,Y=1960.0 (should be at cap-height 1958?)

	* Aring (U+00C5): X=1088.5,Y=2575.0 (should be at ascender 2576?)

	* ae (U+00E6): X=1068.0,Y=0.5 (should be at baseline 0?)

	* egrave (U+00E8): X=286.0,Y=0.5 (should be at baseline 0?)

	* eacute (U+00E9): X=286.0,Y=0.5 (should be at baseline 0?)

	* ecircumflex (U+00EA): X=286.0,Y=0.5 (should be at baseline 0?)

	* edieresis (U+00EB): X=286.0,Y=0.5 (should be at baseline 0?)

	* yacute (U+00FD): X=110.0,Y=-902.0 (should be at descender -903?)

	* ydieresis (U+00FF): X=110.0,Y=-902.0 (should be at descender -903?)

	* emacron (U+0113): X=286.0,Y=0.5 (should be at baseline 0?)

	* ebreve (U+0115): X=286.0,Y=0.5 (should be at baseline 0?)

	* edotaccent (U+0117): X=286.0,Y=0.5 (should be at baseline 0?)

	* eogonek (U+0119): X=286.0,Y=0.5 (should be at baseline 0?)

	* ecaron (U+011B): X=286.0,Y=0.5 (should be at baseline 0?)

	* IJ (U+0132): X=1080.0,Y=1.0 (should be at baseline 0?)

	* ij (U+0133): X=236.5,Y=-901.5 (should be at descender -903?)

	* ij (U+0133): X=123.0,Y=-904.0 (should be at descender -903?)

	* Jcircumflex (U+0134): X=169.0,Y=1.0 (should be at baseline 0?)

	* jcircumflex (U+0135): X=-418.5,Y=-901.0 (should be at descender -903?)

	* jcircumflex (U+0135): X=-535.5,Y=-902.5 (should be at descender -903?)

	* Ncaron (U+0147): X=1122.0,Y=2578.0 (should be at ascender 2576?)

	* oe (U+0153): X=957.0,Y=0.5 (should be at baseline 0?)

	* Uring (U+016E): X=1057.5,Y=2575.0 (should be at ascender 2576?)

	* ycircumflex (U+0177): X=110.0,Y=-902.0 (should be at descender -903?)

	* uni0181 (U+0181): X=331.0,Y=1957.0 (should be at cap-height 1958?)

	* uni018A (U+018A): X=351.0,Y=1957.0 (should be at cap-height 1958?)

	* uni0198 (U+0198): X=1574.0,Y=1959.0 (should be at cap-height 1958?)

	* uni01B3 (U+01B3): X=468.0,Y=1957.0 (should be at cap-height 1958?)

	* uni01B4 (U+01B4): X=110.0,Y=-902.0 (should be at descender -903?)

	* uni01B7 (U+01B7): X=439.0,Y=-2.0 (should be at baseline 0?)

	* uni01C7 (U+01C7): X=1772.0,Y=1.0 (should be at baseline 0?)

	* uni01C8 (U+01C8): X=1165.5,Y=-901.5 (should be at descender -903?)

	* uni01C8 (U+01C8): X=1052.0,Y=-904.0 (should be at descender -903?)

	* uni01C9 (U+01C9): X=243.5,Y=-901.5 (should be at descender -903?)

	* uni01C9 (U+01C9): X=130.0,Y=-904.0 (should be at descender -903?)

	* uni01CA (U+01CA): X=1883.0,Y=1.0 (should be at baseline 0?)

	* uni01CB (U+01CB): X=1358.5,Y=-901.5 (should be at descender -903?)

	* uni01CB (U+01CB): X=1245.0,Y=-904.0 (should be at descender -903?)

	* uni01CC (U+01CC): X=920.5,Y=-901.5 (should be at descender -903?)

	* uni01CC (U+01CC): X=807.0,Y=-904.0 (should be at descender -903?)

	* uni01DC (U+01DC): X=1044.0,Y=1957.0 (should be at cap-height 1958?)

	* uni01E3 (U+01E3): X=1068.0,Y=0.5 (should be at baseline 0?)

	* uni01EE (U+01EE): X=439.0,Y=-2.0 (should be at baseline 0?)

	* uni0205 (U+0205): X=286.0,Y=0.5 (should be at baseline 0?)

	* uni0207 (U+0207): X=286.0,Y=0.5 (should be at baseline 0?)

	* uni0229 (U+0229): X=286.0,Y=0.5 (should be at baseline 0?)

	* uni0233 (U+0233): X=110.0,Y=-902.0 (should be at descender -903?)

	* uni0237 (U+0237): X=-418.5,Y=-901.0 (should be at descender -903?)

	* uni0237 (U+0237): X=-535.5,Y=-902.5 (should be at descender -903?)

	* uni1E15 (U+1E15): X=286.0,Y=0.5 (should be at baseline 0?)

	* uni1E17 (U+1E17): X=286.0,Y=0.5 (should be at baseline 0?)

	* uni1E19 (U+1E19): X=286.0,Y=0.5 (should be at baseline 0?)

	* uni1E1B (U+1E1B): X=286.0,Y=0.5 (should be at baseline 0?)

	* uni1E1D (U+1E1D): X=286.0,Y=0.5 (should be at baseline 0?)

	* uni1E3E (U+1E3E): X=1668.0,Y=2574.0 (should be at ascender 2576?)

	* uni1E8A (U+1E8A): X=1494.5,Y=1956.5 (should be at cap-height 1958?)

	* uni1E8B (U+1E8B): X=102.0,Y=-0.5 (should be at baseline 0?)

	* uni1E8C (U+1E8C): X=1494.5,Y=1956.5 (should be at cap-height 1958?)

	* uni1E8D (U+1E8D): X=102.0,Y=-0.5 (should be at baseline 0?)

	* uni1E8F (U+1E8F): X=110.0,Y=-902.0 (should be at descender -903?)

	* uni1EB5 (U+1EB5): X=1118.0,Y=1960.0 (should be at cap-height 1958?)

	* uni1EB9 (U+1EB9): X=286.0,Y=0.5 (should be at baseline 0?)

	* uni1EBB (U+1EBB): X=286.0,Y=0.5 (should be at baseline 0?)

	* uni1EBD (U+1EBD): X=286.0,Y=0.5 (should be at baseline 0?)

	* uni1EBF (U+1EBF): X=286.0,Y=0.5 (should be at baseline 0?)

	* uni1EC1 (U+1EC1): X=286.0,Y=0.5 (should be at baseline 0?)

	* uni1EC3 (U+1EC3): X=286.0,Y=0.5 (should be at baseline 0?)

	* uni1EC5 (U+1EC5): X=286.0,Y=0.5 (should be at baseline 0?)

	* uni1EC7 (U+1EC7): X=286.0,Y=0.5 (should be at baseline 0?)

	* ygrave (U+1EF3): X=110.0,Y=-902.0 (should be at descender -903?)

	* uni1EF5 (U+1EF5): X=110.0,Y=-902.0 (should be at descender -903?)

	* uni1EF7 (U+1EF7): X=110.0,Y=-902.0 (should be at descender -903?)

	* uni1EF9 (U+1EF9): X=110.0,Y=-902.0 (should be at descender -903?)

	* uni2075 (U+2075): X=392.5,Y=-1.0 (should be at baseline 0?)

	* uni2085 (U+2085): X=392.5,Y=-1.0 (should be at baseline 0?)

	* uni2206 (U+2206): X=1231.0,Y=2.0 (should be at baseline 0?)

	* uni2206 (U+2206): X=214.0,Y=2.0 (should be at baseline 0?)

	* uni2206 (U+2206): X=1235.0,Y=2.0 (should be at baseline 0?) 

	* notequal (U+2260): X=558.0,Y=-2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* ordfeminine (U+00AA): B<<905.5,1239.5>-<865.0,1279.0>-<882.0,1351.0>>/L<<882.0,1351.0>--<864.0,1276.0>> = 0.21086679589269736 

	* uni2151 (U+2151): B<<2148.5,1097.5>-<2179.0,1124.0>-<2197.0,1125.0>>/L<<2197.0,1125.0>--<2137.0,1125.0>> = 3.1798301198641643 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* arrowleft (U+2190): L<<1717.0,754.0>--<822.0,755.0>>

	* arrowleft (U+2190): L<<856.0,993.0>--<1728.0,992.0>>

	* arrowright (U+2192): L<<1309.0,797.0>--<437.0,798.0>>

	* arrowright (U+2192): L<<448.0,1036.0>--<1343.0,1035.0>>

	* uni0181 (U+0181): L<<331.0,1957.0>--<594.0,1958.0>> 

	* uni018A (U+018A): L<<351.0,1957.0>--<751.0,1958.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[11] QldSchool-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check family name for GF Guide compliance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_name_compliance">com.google.fonts/check/name/family_name_compliance</a>)</summary><div>


* 🔥 **FAIL** "QldSchool" is a CamelCased name. To solve this, simply use spaces instead in the font name. [code: camelcase]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.11, while a newer 0.10.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_TransLatin_Pinyin is almost fulfilled. Missing codepoints:

	- 0x207F (SUPERSCRIPT LATIN SMALL LETTER N)


	- 0x030D (COMBINING VERTICAL LINE ABOVE)


	- 0x0358 (COMBINING DOT ABOVE RIGHT)


	- 0x1D3A (MODIFIER LETTER CAPITAL N)


	- 0x0114 (LATIN CAPITAL LETTER E WITH BREVE)


	- 0x012C (LATIN CAPITAL LETTER I WITH BREVE)
 

	- 0x014E (LATIN CAPITAL LETTER O WITH BREVE)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.7395x (3479) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- i.cv04

	- i.cv05

	- idotless_cedillabelowcomb

	- m.cv04

	- m.cv05

	- n.cv04

	- n.cv05

	- u.cv04

	- u.cv05

	- uni0131031B

	- uni01310324

	- uni01310325

	- uni01310326

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

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni02B9	Contours detected: 0	Expected: 1

	- Glyph name: uni02C8	Contours detected: 0	Expected: 1

	- Glyph name: lambda	Contours detected: 0	Expected: 1

	- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lambda	Contours detected: 0	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni02B9	Contours detected: 0	Expected: 1

	- Glyph name: uni02C8	Contours detected: 0	Expected: 1

	- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 1362 among a set of 2 math glyphs.
The following math glyphs have a different width, though:

Width = 1105:
plus

Width = 1260:
less

Width = 1261:
greater

Width = 1278:
plusminus

Width = 1402:
multiply

Width = 1284:
divide

Width = 1280:
minus

Width = 1374:
approxequal

Width = 1347:
lessequal

Width = 1287:
greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* A (U+0041): L<<1019.0,1441.0>--<1018.0,1691.0>>

	* Aacute (U+00C1): L<<1019.0,1441.0>--<1018.0,1691.0>>

	* Abreve (U+0102): L<<1019.0,1441.0>--<1018.0,1691.0>>

	* Acircumflex (U+00C2): L<<1019.0,1441.0>--<1018.0,1691.0>>

	* Adieresis (U+00C4): L<<1019.0,1441.0>--<1018.0,1691.0>>

	* Agrave (U+00C0): L<<1019.0,1441.0>--<1018.0,1691.0>>

	* Amacron (U+0100): L<<1019.0,1441.0>--<1018.0,1691.0>>

	* Aogonek (U+0104): L<<1019.0,1441.0>--<1018.0,1691.0>>

	* Aring (U+00C5): L<<1019.0,1441.0>--<1018.0,1691.0>>

	* Atilde (U+00C3): L<<1019.0,1441.0>--<1018.0,1691.0>>

	* arrowleft (U+2190): L<<1716.0,768.0>--<695.0,769.0>>

	* arrowleft (U+2190): L<<724.0,948.0>--<1737.0,947.0>>

	* arrowright (U+2192): L<<1430.0,809.0>--<417.0,810.0>>

	* uni0181 (U+0181): L<<326.0,1959.0>--<557.0,1958.0>>

	* uni0181 (U+0181): L<<430.0,1761.0>--<314.0,1762.0>>

	* uni018A (U+018A): L<<361.0,1959.0>--<689.0,1958.0>>

	* uni01CD (U+01CD): L<<1019.0,1441.0>--<1018.0,1691.0>>

	* uni01DE (U+01DE): L<<1019.0,1441.0>--<1018.0,1691.0>>

	* uni01E0 (U+01E0): L<<1019.0,1441.0>--<1018.0,1691.0>>

	* uni0200 (U+0200): L<<1019.0,1441.0>--<1018.0,1691.0>>

	* uni0202 (U+0202): L<<1019.0,1441.0>--<1018.0,1691.0>>

	* uni0226 (U+0226): L<<1019.0,1441.0>--<1018.0,1691.0>>

	* uni1E00 (U+1E00): L<<1019.0,1441.0>--<1018.0,1691.0>>

	* uni1EA0 (U+1EA0): L<<1019.0,1441.0>--<1018.0,1691.0>>

	* uni1EA2 (U+1EA2): L<<1019.0,1441.0>--<1018.0,1691.0>>

	* uni1EA4 (U+1EA4): L<<1019.0,1441.0>--<1018.0,1691.0>>

	* uni1EA6 (U+1EA6): L<<1019.0,1441.0>--<1018.0,1691.0>>

	* uni1EA8 (U+1EA8): L<<1019.0,1441.0>--<1018.0,1691.0>>

	* uni1EAA (U+1EAA): L<<1019.0,1441.0>--<1018.0,1691.0>>

	* uni1EAC (U+1EAC): L<<1019.0,1441.0>--<1018.0,1691.0>>

	* uni1EAE (U+1EAE): L<<1019.0,1441.0>--<1018.0,1691.0>>

	* uni1EB0 (U+1EB0): L<<1019.0,1441.0>--<1018.0,1691.0>>

	* uni1EB2 (U+1EB2): L<<1019.0,1441.0>--<1018.0,1691.0>>

	* uni1EB4 (U+1EB4): L<<1019.0,1441.0>--<1018.0,1691.0>>

	* uni1EB6 (U+1EB6): L<<1019.0,1441.0>--<1018.0,1691.0>>

	* uni2206 (U+2206): L<<1019.0,1441.0>--<1018.0,1691.0>> 

	* uni2206 (U+2206): L<<280.0,190.0>--<1115.0,189.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[12] QldSchool-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check family name for GF Guide compliance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_name_compliance">com.google.fonts/check/name/family_name_compliance</a>)</summary><div>


* 🔥 **FAIL** "QldSchool" is a CamelCased name. To solve this, simply use spaces instead in the font name. [code: camelcase]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.11, while a newer 0.10.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_TransLatin_Pinyin is almost fulfilled. Missing codepoints:

	- 0x207F (SUPERSCRIPT LATIN SMALL LETTER N)


	- 0x030D (COMBINING VERTICAL LINE ABOVE)


	- 0x0358 (COMBINING DOT ABOVE RIGHT)


	- 0x1D3A (MODIFIER LETTER CAPITAL N)


	- 0x0114 (LATIN CAPITAL LETTER E WITH BREVE)


	- 0x012C (LATIN CAPITAL LETTER I WITH BREVE)
 

	- 0x014E (LATIN CAPITAL LETTER O WITH BREVE)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.7395x (3479) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- i.cv04

	- i.cv05

	- idotless_cedillabelowcomb

	- m.cv04

	- m.cv05

	- n.cv04

	- n.cv05

	- u.cv04

	- u.cv05

	- uni0131031B

	- uni01310324

	- uni01310325

	- uni01310326

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

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni02B9	Contours detected: 0	Expected: 1

	- Glyph name: uni02C8	Contours detected: 0	Expected: 1

	- Glyph name: lambda	Contours detected: 0	Expected: 1

	- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lambda	Contours detected: 0	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni02B9	Contours detected: 0	Expected: 1

	- Glyph name: uni02C8	Contours detected: 0	Expected: 1

	- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 1411 among a set of 2 math glyphs.
The following math glyphs have a different width, though:

Width = 1139:
plus

Width = 1310:
less

Width = 1314:
greater

Width = 1332:
plusminus

Width = 1450:
multiply

Width = 1330:
divide

Width = 1329:
minus

Width = 1431:
approxequal

Width = 1405:
lessequal

Width = 1343:
greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* ordfeminine (U+00AA): B<<914.0,1235.5>-<878.0,1271.0>-<893.0,1335.0>>/L<<893.0,1335.0>--<881.0,1302.0>> = 6.792495809693081 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* arrowleft (U+2190): L<<1717.0,759.0>--<774.0,760.0>>

	* arrowleft (U+2190): L<<806.0,976.0>--<1731.0,975.0>>

	* arrowright (U+2192): L<<1354.0,802.0>--<430.0,803.0>> 

	* uni2206 (U+2206): L<<348.0,239.0>--<1110.0,238.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[11] QldSchool-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check family name for GF Guide compliance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_name_compliance">com.google.fonts/check/name/family_name_compliance</a>)</summary><div>


* 🔥 **FAIL** "QldSchool" is a CamelCased name. To solve this, simply use spaces instead in the font name. [code: camelcase]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.11, while a newer 0.10.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_TransLatin_Pinyin is almost fulfilled. Missing codepoints:

	- 0x207F (SUPERSCRIPT LATIN SMALL LETTER N)


	- 0x030D (COMBINING VERTICAL LINE ABOVE)


	- 0x0358 (COMBINING DOT ABOVE RIGHT)


	- 0x1D3A (MODIFIER LETTER CAPITAL N)


	- 0x0114 (LATIN CAPITAL LETTER E WITH BREVE)


	- 0x012C (LATIN CAPITAL LETTER I WITH BREVE)
 

	- 0x014E (LATIN CAPITAL LETTER O WITH BREVE)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.7395x (3479) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- i.cv04

	- i.cv05

	- idotless_cedillabelowcomb

	- m.cv04

	- m.cv05

	- n.cv04

	- n.cv05

	- u.cv04

	- u.cv05

	- uni0131031B

	- uni01310324

	- uni01310325

	- uni01310326

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

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni02B9	Contours detected: 0	Expected: 1

	- Glyph name: uni02C8	Contours detected: 0	Expected: 1

	- Glyph name: lambda	Contours detected: 0	Expected: 1

	- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lambda	Contours detected: 0	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni02B9	Contours detected: 0	Expected: 1

	- Glyph name: uni02C8	Contours detected: 0	Expected: 1

	- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 1293 among a set of 3 math glyphs.
The following math glyphs have a different width, though:

Width = 1057:
plus

Width = 1190:
less

Width = 1188:
greater

Width = 1202:
plusminus

Width = 1336:
multiply

Width = 1220:
divide

Width = 1211:
minus

Width = 1265:
lessequal

Width = 1209:
greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* W (U+0057): L<<516.0,440.0>--<515.0,224.0>>

	* Wacute (U+1E82): L<<516.0,440.0>--<515.0,224.0>>

	* Wcircumflex (U+0174): L<<516.0,440.0>--<515.0,224.0>>

	* Wdieresis (U+1E84): L<<516.0,440.0>--<515.0,224.0>>

	* Wgrave (U+1E80): L<<516.0,440.0>--<515.0,224.0>>

	* arrowleft (U+2190): L<<608.0,909.0>--<1744.0,908.0>>

	* arrowright (U+2192): L<<1536.0,820.0>--<400.0,821.0>>

	* uni018A (U+018A): L<<370.0,1960.0>--<635.0,1958.0>>

	* uni1E86 (U+1E86): L<<516.0,440.0>--<515.0,224.0>>

	* uni1E88 (U+1E88): L<<516.0,440.0>--<515.0,224.0>>

	* uni1E9E (U+1E9E): L<<804.0,-1.0>--<612.0,0.0>>

	* uni2206 (U+2206): L<<1137.0,0.0>--<131.0,1.0>> 

	* uni2206 (U+2206): L<<186.0,121.0>--<1122.0,120.0>> [code: found-semi-vertical]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 8 | 39 | 462 | 25 | 386 | 0 |
| 0% | 1% | 4% | 50% | 3% | 42% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
