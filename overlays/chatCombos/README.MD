### How to setup:
* Download (https://github.com/GibberishDev/resrrep/blob/main/overlays/chatCombos/combo.html)[html file] and put it in any folder you want. Then open html file in browser and copy link into obs browser source (DO NOT use local file as it doesnt allow settings aplied).
* To change channel or other settings append `?` at the end of the link and then follow by the `[setting]=[value]` and separate settings by `&` symbol
<br>Example: `file:///C:/Users/... .../combo.html?channel=gibbdev&number-regular=4`

Avaliable settings:
| setting | value type | default | description |
| --- | --- | --- | --- |
| channel | `string` | "gibbdev" | channel id from which chat tracking will occur
| number-normal | `integer` | 2 | number of repeats required to show regular animation
| number-mega | `integer` | 10 | number of repeats required to show mega animation (rainbow animation)
| number-super | `integer` | 25 | number of repeats required to show mega animation (shake animation)
| timeout-normal | `integer` | 10000 | number in milliseconds before regular combo expires
| timeout-mega | `integer` | 15000 | number in milliseconds before regular combo expires
| timeout-super | `integer` | 20000 | number in milliseconds before regular combo expires
| show-timer | `boolean` | "true" | decides whether to show timer (circle)
| position | `string` | "bottom-left" |  decides anchor of the whole widget in the window.  <details><summary>avaliable values</summary><br>top-left<br>top-center<br>top-right<br>left<br>center<br>right<br>bottom-left<br>bottom-center<br>bottom-right</details>
