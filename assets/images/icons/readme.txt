
These icons were taken directly from the SVG file for font awesome…

http://fontawesome.io/license/


The basic steps to add a new icon are…

1. Download font awesome

2. Find the name of the icon you want to use. For example, “bicycle”

http://fontawesome.io/icon/bicycle/

3. Find the character code for that icon in the font awesome CSS file. For example, “f206”

font-awesome-4.6.1/css/font-awesome.css

4. Find the glyph for that character code in the SVG file. For example… <glyph unicode="&#xf206;" … />

font-awesome-4.6.1/fonts/fontawesome-webfont.svg

5. Copy the “d” property of the element. For example…

d="M762 384h-314q-40 0 -57.5 35t6.5 67l188 251q-65 31 -137 31q-132 0 -226 -94t-94 -226t94 -226t226 -94q115 0 203 72.5t111 183.5zM576 512h186q-18 85 -75 148zM1056 512l288 384h-480l-99 -132q105 -103 126 -252h165zM2176 448q0 132 -94 226t-226 94 q-60 0 -121 -24l174 -260q15 -23 10 -49t-27 -40q-15 -11 -36 -11q-35 0 -53 29l-174 260q-93 -95 -93 -225q0 -132 94 -226t226 -94t226 94t94 226zM2304 448q0 -185 -131.5 -316.5t-316.5 -131.5t-316.5 131.5t-131.5 316.5q0 97 39.5 183.5t109.5 149.5l-65 98l-353 -469 q-18 -26 -51 -26h-197q-23 -164 -149 -274t-294 -110q-185 0 -316.5 131.5t-131.5 316.5t131.5 316.5t316.5 131.5q114 0 215 -55l137 183h-224q-26 0 -45 19t-19 45t19 45t45 19h384v-128h435l-85 128h-222q-26 0 -45 19t-19 45t19 45t45 19h256q33 0 53 -28l267 -400 q91 44 192 44q185 0 316.5 -131.5t131.5 -316.5z"

6. Make a copy of one of the current icon files, and give it a new name. For example, “bicycle.svg”

7. Open your new icon file in a text editor, and paste the “d” property over the one in the file. It should look something like this when you’re finished…

<svg …>
<path d="M762 384h-314q-40 0 -57.5 35t6.5 67l188 251q-65 31 -137 31q-132 0 -226 -94t-94 -226t94 -226t226 -94q115 0 203 72.5t111 183.5zM576 512h186q-18 85 -75 148zM1056 512l288 384h-480l-99 -132q105 -103 126 -252h165zM2176 448q0 132 -94 226t-226 94 q-60 0 -121 -24l174 -260q15 -23 10 -49t-27 -40q-15 -11 -36 -11q-35 0 -53 29l-174 260q-93 -95 -93 -225q0 -132 94 -226t226 -94t226 94t94 226zM2304 448q0 -185 -131.5 -316.5t-316.5 -131.5t-316.5 131.5t-131.5 316.5q0 97 39.5 183.5t109.5 149.5l-65 98l-353 -469 q-18 -26 -51 -26h-197q-23 -164 -149 -274t-294 -110q-185 0 -316.5 131.5t-131.5 316.5t131.5 316.5t316.5 131.5q114 0 215 -55l137 183h-224q-26 0 -45 19t-19 45t19 45t45 19h384v-128h435l-85 128h-222q-26 0 -45 19t-19 45t19 45t45 19h256q33 0 53 -28l267 -400 q91 44 192 44q185 0 316.5 -131.5t131.5 -316.5z" />
</svg>

8. Open the your new icon file in Illustrator (or your favorite vector editing program) and resize the icon to about 20 pixels tall and wide at most. You may also need to flip it vertically.

9. Save the file, and you’re done!
