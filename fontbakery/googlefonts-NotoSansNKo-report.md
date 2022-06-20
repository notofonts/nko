## Fontbakery report

Fontbakery version: 0.8.9

<details><summary><b>[13] NotoSansNKo-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017-2022 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: FONT_FAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/familyname">com.google.fonts/check/name/familyname</a>)</summary><div>


* 🔥 **FAIL** Entry [FONT_FAMILY_NAME(1):WINDOWS(3)] on the "name" table: Expected "Noto Sans N Ko" but got "Noto Sans NKo". [code: mismatch]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: FULL_FONT_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/fullfontname">com.google.fonts/check/name/fullfontname</a>)</summary><div>


* 🔥 **FAIL** [FULL_FONT_NAME(4):WINDOWS(3)]
Expected: "Noto Sans N Ko Regular"
But got:  "Noto Sans NKo Regular" [code: bad-entry]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansNKo/googlefonts/ttf/NotoSansNKo-Regular.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/nko.json: Expected and actual shaping not matching
<div class="shaping">


<style type="text/css">
    @font-face {font-family: "TestFont"; src: url(../../fonts/NotoSansNKo/googlefonts/ttf/NotoSansNKo-Regular.ttf);}
    .tf { font-family: "TestFont"; }
    .shaping pre { font-size: 1.2rem; }
    .shaping li {
        font-size: 1.2rem;
        border-top: 1px solid #ddd;
        padding: 12px;
        margin-top: 12px;
    }
    .shaping-svg {
        height: 100px;
        margin: 10px;
        transform: matrix(1, 0, 0, -1, 0, 0);
    }
</style>

<h4>qa/shaping_tests/nko.json: Expected and actual shaping not matching</h4>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">߁߭ߜ߽ߩ߮</span> (Added by SIESTA)</li>


<pre>Expected: uni07EE=4@292,-341+0|uni07E9.fina=4+453|uni07FD.wider=2+0|uni07DC.init=2+576|uni07ED=0@297,-150+0|uni25CC=0+594|uni07C1=0+542</pre>



<pre>Got     : uni07EE=4@292,-341+0|uni07E9.fina=4+453|uni07FD.wider=2+0|uni07DC.init=2+576|uni07ED=0@297,1+0|uni07C1=0+542</pre>



<pre>                                                                                                     + ++  ++++++++++++++
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1571 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M-169.0,800.0L-169.0,811.0Q-148.0,843.0 -125.0,883.0Q-102.0,923.0 -81.0,964.5Q-60.0,1006.0 -46.0,1039.0L44.0,1039.0Q57.0,1006.0 79.0,964.5Q101.0,923.0 125.5,882.5Q150.0,842.0 169.0,811.0L169.0,800.0L107.0,800.0Q82.0,823.0 54.5,861.5Q27.0,900.0 -2.0,946.0Q-28.0,900.0 -55.5,862.5Q-83.0,825.0 -109.0,800.0L-169.0,800.0Z"  transform="translate(292, 452)"/>
<path d="M195.0,-272.0Q146.0,-272.0 116.0,-255.0Q86.0,-238.0 86.0,-212.0Q86.0,-203.0 102.0,-173.0Q118.0,-143.0 143.5,-98.0Q169.0,-53.0 196.0,-1.0Q226.0,56.0 254.5,114.0Q283.0,172.0 303.5,217.0Q324.0,262.0 330.0,280.0L422.0,280.0Q407.0,241.0 387.5,199.0Q368.0,157.0 346.0,113.0Q375.0,78.0 435.0,78.0L487.0,78.0L487.0,0.0L439.0,0.0Q394.0,0.0 369.0,14.5Q344.0,29.0 319.0,58.0Q309.0,40.0 300.0,22.0Q291.0,4.0 282.0,-14.0L300.0,-14.0Q325.0,-14.0 351.5,-21.5Q378.0,-29.0 396.5,-48.0Q415.0,-67.0 415.0,-103.0Q415.0,-130.0 398.5,-159.5Q382.0,-189.0 352.0,-214.5Q322.0,-240.0 282.0,-256.0Q242.0,-272.0 195.0,-272.0ZM210.0,-195.0Q236.0,-195.0 263.0,-183.0Q290.0,-171.0 308.0,-152.0Q326.0,-133.0 326.0,-112.0Q326.0,-92.0 312.0,-86.5Q298.0,-81.0 273.0,-81.0L247.0,-81.0Q233.0,-109.0 217.5,-136.5Q202.0,-164.0 187.0,-192.0Q192.0,-193.0 198.5,-194.0Q205.0,-195.0 210.0,-195.0Z"  transform="translate(0, 793)"/>
<path d="M246.0,-99.0L229.0,0.0L-229.0,0.0L-246.0,-99.0L-310.0,-99.0L-310.0,78.0L310.0,78.0L310.0,-99.0L246.0,-99.0Z"  transform="translate(453, 793)"/>
<path d="M15.0,0.0Q6.0,0.0 -10.0,5.0Q-26.0,10.0 -34.0,16.0L-34.0,78.0L220.0,78.0L39.0,670.0L39.0,714.0L537.0,714.0L537.0,670.0L358.0,80.0Q347.0,38.0 315.5,19.0Q284.0,0.0 244.0,0.0L244.0,0.0L244.0,0.0L239.0,0.0L15.0,0.0ZM255.0,259.0Q269.0,214.0 276.5,186.0Q284.0,158.0 290.0,123.0Q297.0,158.0 303.5,188.0Q310.0,218.0 322.0,257.0L436.0,636.0L142.0,636.0L255.0,259.0Z"  transform="translate(453, 793)"/>
<path d="M0.0,804.0Q-23.0,804.0 -39.5,818.5Q-56.0,833.0 -56.0,864.0Q-56.0,896.0 -39.5,910.0Q-23.0,924.0 0.0,924.0Q23.0,924.0 39.5,910.0Q56.0,896.0 56.0,864.0Q56.0,833.0 39.5,818.5Q23.0,804.0 0.0,804.0Z"  transform="translate(1326, 794)"/>
<path d="M90.0,0.0L90.0,78.0L231.0,78.0L231.0,714.0L362.0,714.0L497.0,459.0L427.0,421.0L355.0,557.0Q346.0,574.0 335.0,598.5Q324.0,623.0 318.0,638.0Q319.0,613.0 319.5,586.0Q320.0,559.0 320.0,529.0L320.0,78.0L481.0,78.0L481.0,0.0L90.0,0.0Z"  transform="translate(1029, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2165 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M-169.0,800.0L-169.0,811.0Q-148.0,843.0 -125.0,883.0Q-102.0,923.0 -81.0,964.5Q-60.0,1006.0 -46.0,1039.0L44.0,1039.0Q57.0,1006.0 79.0,964.5Q101.0,923.0 125.5,882.5Q150.0,842.0 169.0,811.0L169.0,800.0L107.0,800.0Q82.0,823.0 54.5,861.5Q27.0,900.0 -2.0,946.0Q-28.0,900.0 -55.5,862.5Q-83.0,825.0 -109.0,800.0L-169.0,800.0Z"  transform="translate(292, 452)"/>
<path d="M195.0,-272.0Q146.0,-272.0 116.0,-255.0Q86.0,-238.0 86.0,-212.0Q86.0,-203.0 102.0,-173.0Q118.0,-143.0 143.5,-98.0Q169.0,-53.0 196.0,-1.0Q226.0,56.0 254.5,114.0Q283.0,172.0 303.5,217.0Q324.0,262.0 330.0,280.0L422.0,280.0Q407.0,241.0 387.5,199.0Q368.0,157.0 346.0,113.0Q375.0,78.0 435.0,78.0L487.0,78.0L487.0,0.0L439.0,0.0Q394.0,0.0 369.0,14.5Q344.0,29.0 319.0,58.0Q309.0,40.0 300.0,22.0Q291.0,4.0 282.0,-14.0L300.0,-14.0Q325.0,-14.0 351.5,-21.5Q378.0,-29.0 396.5,-48.0Q415.0,-67.0 415.0,-103.0Q415.0,-130.0 398.5,-159.5Q382.0,-189.0 352.0,-214.5Q322.0,-240.0 282.0,-256.0Q242.0,-272.0 195.0,-272.0ZM210.0,-195.0Q236.0,-195.0 263.0,-183.0Q290.0,-171.0 308.0,-152.0Q326.0,-133.0 326.0,-112.0Q326.0,-92.0 312.0,-86.5Q298.0,-81.0 273.0,-81.0L247.0,-81.0Q233.0,-109.0 217.5,-136.5Q202.0,-164.0 187.0,-192.0Q192.0,-193.0 198.5,-194.0Q205.0,-195.0 210.0,-195.0Z"  transform="translate(0, 793)"/>
<path d="M246.0,-99.0L229.0,0.0L-229.0,0.0L-246.0,-99.0L-310.0,-99.0L-310.0,78.0L310.0,78.0L310.0,-99.0L246.0,-99.0Z"  transform="translate(453, 793)"/>
<path d="M15.0,0.0Q6.0,0.0 -10.0,5.0Q-26.0,10.0 -34.0,16.0L-34.0,78.0L220.0,78.0L39.0,670.0L39.0,714.0L537.0,714.0L537.0,670.0L358.0,80.0Q347.0,38.0 315.5,19.0Q284.0,0.0 244.0,0.0L244.0,0.0L244.0,0.0L239.0,0.0L15.0,0.0ZM255.0,259.0Q269.0,214.0 276.5,186.0Q284.0,158.0 290.0,123.0Q297.0,158.0 303.5,188.0Q310.0,218.0 322.0,257.0L436.0,636.0L142.0,636.0L255.0,259.0Z"  transform="translate(453, 793)"/>
<path d="M0.0,804.0Q-23.0,804.0 -39.5,818.5Q-56.0,833.0 -56.0,864.0Q-56.0,896.0 -39.5,910.0Q-23.0,924.0 0.0,924.0Q23.0,924.0 39.5,910.0Q56.0,896.0 56.0,864.0Q56.0,833.0 39.5,818.5Q23.0,804.0 0.0,804.0Z"  transform="translate(1326, 643)"/>
<path d="M297.0,488.0Q287.0,488.0 279.0,496.0Q271.0,504.0 271.0,514.0Q271.0,525.0 279.0,532.5Q287.0,540.0 297.0,540.0Q308.0,540.0 315.5,532.5Q323.0,525.0 323.0,514.0Q323.0,504.0 315.5,496.0Q308.0,488.0 297.0,488.0ZM213.0,470.0Q203.0,470.0 195.0,478.0Q187.0,486.0 187.0,496.0Q187.0,507.0 195.0,514.5Q203.0,522.0 213.0,522.0Q224.0,522.0 231.5,514.5Q239.0,507.0 239.0,496.0Q239.0,486.0 231.5,478.0Q224.0,470.0 213.0,470.0ZM381.0,470.0Q371.0,470.0 363.0,478.0Q355.0,486.0 355.0,496.0Q355.0,507.0 363.0,514.5Q371.0,522.0 381.0,522.0Q392.0,522.0 399.5,514.5Q407.0,507.0 407.0,496.0Q407.0,486.0 399.5,478.0Q392.0,470.0 381.0,470.0ZM455.0,423.0Q445.0,423.0 437.0,431.0Q429.0,439.0 429.0,449.0Q429.0,460.0 437.0,467.5Q445.0,475.0 455.0,475.0Q466.0,475.0 473.5,467.5Q481.0,460.0 481.0,449.0Q481.0,439.0 473.5,431.0Q466.0,423.0 455.0,423.0ZM139.0,423.0Q129.0,423.0 121.0,431.0Q113.0,439.0 113.0,449.0Q113.0,460.0 121.0,467.5Q129.0,475.0 139.0,475.0Q150.0,475.0 157.5,467.5Q165.0,460.0 165.0,449.0Q165.0,439.0 157.5,431.0Q150.0,423.0 139.0,423.0ZM92.0,349.0Q82.0,349.0 74.0,357.0Q66.0,365.0 66.0,375.0Q66.0,386.0 74.0,393.5Q82.0,401.0 92.0,401.0Q103.0,401.0 110.5,393.5Q118.0,386.0 118.0,375.0Q118.0,365.0 110.5,357.0Q103.0,349.0 92.0,349.0ZM502.0,349.0Q492.0,349.0 484.0,357.0Q476.0,365.0 476.0,375.0Q476.0,386.0 484.0,393.5Q492.0,401.0 502.0,401.0Q513.0,401.0 520.5,393.5Q528.0,386.0 528.0,375.0Q528.0,365.0 520.5,357.0Q513.0,349.0 502.0,349.0ZM74.0,265.0Q64.0,265.0 56.0,273.0Q48.0,281.0 48.0,291.0Q48.0,302.0 56.0,309.5Q64.0,317.0 74.0,317.0Q85.0,317.0 92.5,309.5Q100.0,302.0 100.0,291.0Q100.0,281.0 92.5,273.0Q85.0,265.0 74.0,265.0ZM520.0,265.0Q510.0,265.0 502.0,273.0Q494.0,281.0 494.0,291.0Q494.0,302.0 502.0,309.5Q510.0,317.0 520.0,317.0Q531.0,317.0 538.5,309.5Q546.0,302.0 546.0,291.0Q546.0,281.0 538.5,273.0Q531.0,265.0 520.0,265.0ZM92.0,181.0Q82.0,181.0 74.0,189.0Q66.0,197.0 66.0,207.0Q66.0,218.0 74.0,225.5Q82.0,233.0 92.0,233.0Q103.0,233.0 110.5,225.5Q118.0,218.0 118.0,207.0Q118.0,197.0 110.5,189.0Q103.0,181.0 92.0,181.0ZM502.0,181.0Q492.0,181.0 484.0,189.0Q476.0,197.0 476.0,207.0Q476.0,218.0 484.0,225.5Q492.0,233.0 502.0,233.0Q513.0,233.0 520.5,225.5Q528.0,218.0 528.0,207.0Q528.0,197.0 520.5,189.0Q513.0,181.0 502.0,181.0ZM139.0,107.0Q129.0,107.0 121.0,115.0Q113.0,123.0 113.0,133.0Q113.0,144.0 121.0,151.5Q129.0,159.0 139.0,159.0Q150.0,159.0 157.5,151.5Q165.0,144.0 165.0,133.0Q165.0,123.0 157.5,115.0Q150.0,107.0 139.0,107.0ZM455.0,107.0Q445.0,107.0 437.0,115.0Q429.0,123.0 429.0,133.0Q429.0,144.0 437.0,151.5Q445.0,159.0 455.0,159.0Q466.0,159.0 473.5,151.5Q481.0,144.0 481.0,133.0Q481.0,123.0 473.5,115.0Q466.0,107.0 455.0,107.0ZM213.0,60.0Q203.0,60.0 195.0,68.0Q187.0,76.0 187.0,86.0Q187.0,97.0 195.0,104.5Q203.0,112.0 213.0,112.0Q224.0,112.0 231.5,104.5Q239.0,97.0 239.0,86.0Q239.0,76.0 231.5,68.0Q224.0,60.0 213.0,60.0ZM381.0,60.0Q371.0,60.0 363.0,68.0Q355.0,76.0 355.0,86.0Q355.0,97.0 363.0,104.5Q371.0,112.0 381.0,112.0Q392.0,112.0 399.5,104.5Q407.0,97.0 407.0,86.0Q407.0,76.0 399.5,68.0Q392.0,60.0 381.0,60.0ZM297.0,42.0Q287.0,42.0 279.0,50.0Q271.0,58.0 271.0,68.0Q271.0,79.0 279.0,86.5Q287.0,94.0 297.0,94.0Q308.0,94.0 315.5,86.5Q323.0,79.0 323.0,68.0Q323.0,58.0 315.5,50.0Q308.0,42.0 297.0,42.0Z"  transform="translate(1029, 793)"/>
<path d="M90.0,0.0L90.0,78.0L231.0,78.0L231.0,714.0L362.0,714.0L497.0,459.0L427.0,421.0L355.0,557.0Q346.0,574.0 335.0,598.5Q324.0,623.0 318.0,638.0Q319.0,613.0 319.5,586.0Q320.0,559.0 320.0,529.0L320.0,78.0L481.0,78.0L481.0,0.0L90.0,0.0Z"  transform="translate(1623, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ߢ߽ߏ߭ߨ߰߿߫</span> (Added by SIESTA)</li>


<pre>Expected: uni07EB=6@297,-150+0|uni25CC=6+594|uni07FF=6+564|uni07F0=4@292,-341+0|uni07E8.fina=4+453|uni07ED=2@244,-146+0|uni07CF.medi=2+551|uni07FD.wide=0+0|uni07E2.init=0+541</pre>



<pre>Got     : uni07EB=6@136,0+0|uni07FF=6+564|uni07F0=4@292,-341+0|uni07E8.fina=4+453|uni07ED=2@244,-146+0|uni07CF.medi=2+551|uni07FD.wide=0+0|uni07E2.init=0+541</pre>



<pre>                    +++++ ^   ++++++++++++++
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2109 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(136, 793)"/>
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(856, 452)"/>
<path d=""  transform="translate(564, 793)"/>
<path d=""  transform="translate(1261, 647)"/>
<path d=""  transform="translate(1017, 793)"/>
<path d=""  transform="translate(1568, 793)"/>
<path d=""  transform="translate(1568, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2703 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(297, 643)"/>
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(594, 793)"/>
<path d=""  transform="translate(1450, 452)"/>
<path d=""  transform="translate(1158, 793)"/>
<path d=""  transform="translate(1855, 647)"/>
<path d=""  transform="translate(1611, 793)"/>
<path d=""  transform="translate(2162, 793)"/>
<path d=""  transform="translate(2162, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">߁߽߭◌߲ߘ߽</span> (Added by SIESTA)</li>


<pre>Expected: uni07FD.widest=5@396,0+0|uni07D8=5+792|uni07F2=3@297,0+0|uni25CC=3+594|uni07ED=0@297,-150+0|uni07FD=0@297,0+0|uni25CC=0+594|uni07C1=0+542</pre>



<pre>Got     : uni07FD.widest=5@396,0+0|uni07D8=5+792|uni07F2=3@297,0+0|uni25CC=3+594|uni07ED=0@297,1+0|uni07FD=0+0|uni07C1=0+542</pre>



<pre>                                                                                               + ++            ++++++  ++++++++++++++
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1928 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(396, 793)"/>
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(1089, 793)"/>
<path d=""  transform="translate(792, 793)"/>
<path d=""  transform="translate(1683, 794)"/>
<path d=""  transform="translate(1386, 793)"/>
<path d=""  transform="translate(1386, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2522 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(396, 793)"/>
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(1089, 793)"/>
<path d=""  transform="translate(792, 793)"/>
<path d=""  transform="translate(1683, 643)"/>
<path d=""  transform="translate(1683, 793)"/>
<path d=""  transform="translate(1386, 793)"/>
<path d=""  transform="translate(1980, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ߜ߫ߘ߱ߧ߽ߜ߃߲</span> (Added by SIESTA)</li>


<pre>Expected: uni07F2=7@297,0+0|uni25CC=7+594|uni07C3=7+514|uni07DC.fina=6+576|uni07FD.wide=4@268,0+0|uni07E7.medi=4+529|uni07F1=2@371,-146+0|uni07D8.medi=2+792|uni07EB=0@292,0+0|uni07DC.init=0+576</pre>



<pre>Got     : uni07F2=7@281,0+0|uni07C3=7+514|uni07DC.fina=6+576|uni07FD.wide=4@268,0+0|uni07E7.medi=4+529|uni07F1=2@371,-146+0|uni07D8.medi=2+792|uni07EB=0@292,0+0|uni07DC.init=0+576</pre>



<pre>                     ^^    ++++++++++++++
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2987 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(281, 793)"/>
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(514, 793)"/>
<path d=""  transform="translate(1358, 793)"/>
<path d=""  transform="translate(1090, 793)"/>
<path d=""  transform="translate(1990, 647)"/>
<path d=""  transform="translate(1619, 793)"/>
<path d=""  transform="translate(2703, 793)"/>
<path d=""  transform="translate(2411, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3581 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(297, 793)"/>
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(594, 793)"/>
<path d=""  transform="translate(1108, 793)"/>
<path d=""  transform="translate(1952, 793)"/>
<path d=""  transform="translate(1684, 793)"/>
<path d=""  transform="translate(2584, 647)"/>
<path d=""  transform="translate(2213, 793)"/>
<path d=""  transform="translate(3297, 793)"/>
<path d=""  transform="translate(3005, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ߒߥ߱ߋ߬߿߮</span> (Added by SIESTA)</li>


<pre>Expected: uni07EE=5@297,-150+0|uni25CC=5+594|uni07FF=5+564|uni07EC=3@332,-146+0|uni07CB.fina=3+660|uni07F1=1@263,0+0|uni07E5.medi=1+525|uni07D2.init=0+685</pre>



<pre>Got     : uni07EE=5@136,0+0|uni07FF=5+564|uni07EC=3@332,-146+0|uni07CB.fina=3+660|uni07F1=1@263,0+0|uni07E5.medi=1+525|uni07D2.init=0+685</pre>



<pre>                    +++++ ^   ++++++++++++++
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2434 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(136, 793)"/>
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(896, 647)"/>
<path d=""  transform="translate(564, 793)"/>
<path d=""  transform="translate(1487, 793)"/>
<path d=""  transform="translate(1224, 793)"/>
<path d=""  transform="translate(1749, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3028 2362" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(297, 643)"/>
<path d=""  transform="translate(0, 793)"/>
<path d=""  transform="translate(594, 793)"/>
<path d=""  transform="translate(1490, 647)"/>
<path d=""  transform="translate(1158, 793)"/>
<path d=""  transform="translate(2081, 793)"/>
<path d=""  transform="translate(1818, 793)"/>
<path d=""  transform="translate(2343, 793)"/>
</svg>


</div> [code: shaping-regression]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<159.0,84.0>--<159.0,80.0>>

	* at (U+0040) contains a short segment B<<613.0,293.0>-<612.0,275.0>-<612.0,267.5>>

	* at (U+0040) contains a short segment B<<612.0,267.5>-<612.0,260.0>-<612.0,257.0>>

	* M (U+004D) contains a short segment L<<177.0,626.0>--<173.0,626.0>>

	* M (U+004D) contains a short segment L<<450.0,129.0>--<454.0,129.0>>

	* N (U+004E) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* N (U+004E) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* Q (U+0051) contains a short segment B<<416.0,-9.0>-<410.0,-9.0>-<403.5,-9.5>>

	* Q (U+0051) contains a short segment B<<403.5,-9.5>-<397.0,-10.0>-<391.0,-10.0>>

	* W (U+0057) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>> 

	* And 63 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uniFD3E (U+FD3E): L<<272.0,409.0>--<273.0,459.0>> -> L<<273.0,459.0>--<273.0,583.0>> [code: found-colinear-vectors]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 7 | 6 | 115 | 8 | 99 | 0 |
| 0% | 3% | 3% | 49% | 3% | 42% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
