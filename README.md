# Learn To Be Style Guide

This is a shortcut to various things we may need access to as we use our new style guide.

# Colors #

## Overview

![Brand Logo](/assets/color_pallette.png)

## Colors Table

**NAME**|**RGB**|**HEX**|**CMYK**|**PANTONE**|**NEAREST TAILWIND 3**|**Current Hex > OKLCH**|**Tailwind 4 OKLCH**
:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:
Dream Big Blue| 37-99-235| #2563EB|84-57-0-0| 2386 C | blue-600 exact | oklch(54.61% 0.2152 262.88)| oklch(0.546 0.245 262.881)
Sky Blue| 147-197-253| #93C5FD| 41-11-0-0| 283 C | blue-300 exact | oklch(80.91% 0.0956 251.81)| oklch(0.882 0.059 254.128)
Cloud Blue| 219-234-254| #DBEAFE| 20-6-0-0| 643 C | blue-100 exact | oklch(93.19% 0.0316 255.59)| oklch(0.97 0.014 254.604)
Midnight| 17-24-39| #111827| 100-58-21-92| 7547 C | gray-900 exact | oklch(21.01% 0.0318 264.66)| oklch(0.21 0.034 264.665)
Daydream Orange| 255-236-209| #FFECD1| 3-15-30-0| 4029 C | orange-100 CLOSE | oklch(95.13% 0.041 76.75)| oklch(0.646 0.222 41.116)
Electric Orange| 240-78-35| #F04E23| 0-80-98-0| 172 C | orange-600 CLOSE | oklch(64.53% 0.2054 35.1)| oklch(0.954 0.038 75.164)

# Fonts 

## Primary Typeface

Jubilat (Google Font Alternative: [Domine](https://fonts.google.com/specimen/Domine))

## Secondary Typeface

Circular (Google Font Alternative: [DM Sans](https://fonts.google.com/specimen/DM+Sans))

Also: [Satoshi](https://www.fontshare.com/fonts/satoshi)

## Screenshot 

![Font Screenshot](/assets/font.png)

## Logo

![LTB Logo Black](/assets/ltb_logo_black_large.png)

![LTB Logo Blue](/assets/ltb_logo_blue_large.png)

![LTB Logo Reverse](/assets/ltb_logo_reverse_large.png)

## Tailwind Style Tile
Here is a Tailwind Play link version of our Style Tile: [https://play.tailwindcss.com/mpPISdjAd2](https://play.tailwindcss.com/mpPISdjAd2)

This can help preview changes between Tailwind versions, since the official Tailwind colors will shift over time. In general, Tailwind 4 seems to be the best match so far for our image style tile above.

![image](https://github.com/user-attachments/assets/424754cd-839d-493c-ae6f-ccbf32ac95b9)


You can also paste this code to rebuilt it. 
```
<div class="grid grid-cols-5 grid-rows-5 text-gray-900">
  <div class="col-span-2 row-span-5 bg-blue-600 p-4 text-white">
    <ul>
      <li class="font-bold">Dream Big Blue</li>
      <li>blue-600</li>
    </ul>
  </div>
  <div class="col-span-3 col-start-3 row-span-2 flex flex-row">
    <div class="grow bg-blue-300 p-4">
      <ul>
        <li class="font-bold">Sky Blue</li>
        <li>blue-300</li>
      </ul>
    </div>
    <div class="grow bg-blue-100 p-4">
      <ul>
        <li class="font-bold">Cloud Blue</li>
        <li>blue-100</li>
      </ul>
    </div>
  </div>
  <div class="col-span-3 col-start-3 row-start-3 bg-gray-900 p-4 text-white">
    <ul>
      <li class="font-bold">Midnight</li>
      <li>gray-900</li>
    </ul>
  </div>
  <div class="col-start-3 row-span-2 row-start-4 bg-white p-4">
    <ul>
      <li class="font-bold">White</li>
      <li>white</li>
    </ul>
  </div>
  <div class="col-start-4 row-span-2 row-start-4 bg-orange-100 p-4">
    <ul>
      <li class="font-bold">Daydream Orange</li>
      <li>orange-100</li>
    </ul>
  </div>
  <div class="col-start-5 row-span-2 row-start-4 bg-orange-600 p-4 text-white">
    <ul>
      <li class="font-bold">Electric Orange</li>
      <li>orange-600</li>
    </ul>
  </div>
</div>
```
