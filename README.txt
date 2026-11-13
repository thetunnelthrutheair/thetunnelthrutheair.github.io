Vedic Planet Clock (Swiss Ephemeris, fully static)
Upload this whole folder to your Render Static Site (publish directory = this folder).
index.html loads ./swisseph/src/swisseph.js, which loads ./swisseph/wasm/swisseph.wasm and swisseph.data.
Must be served over http(s) (not file://). Swiss Ephemeris is AGPL/commercial; swisseph-wasm is GPLv3.
Also included: astronomy.browser.min.js (astronomy-engine 2.1.19, MIT) used for eclipse calculations. Keep it next to index.html.
