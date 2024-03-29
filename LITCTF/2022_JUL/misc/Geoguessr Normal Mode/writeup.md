# Geoguessr Normal Mode

## Description
I like the city! The flag is LITCTF{latitude,longtitude} rounded to the third decimal place. (Example: LITCTF{42.444,-71.230})
`The challenge file is present in the same directory with the name challenge.png.`

## Solution

#### Method-1

1. Use this link -> https://yandex.com/ to find the name of the place given in the challenge file.
2. Once you find the name, map it on Google maps and take out the latitude and longitude.
3. [ latitude and longitude can be found in the address bar ]

#### Method-2

By looking at the image the sign in the foreground is written in both Portuguese and Chinese, meaning that this is almost definitely Macau, a former Portuguese colony in China - especially because of the prominent skyline. Find the most significant landmark in the image, the skyscraper with the red orb on top, by browsing Macau's tallest buildings (https://en.wikipedia.org/wiki/List_of_tallest_buildings_in_Macau, number 11) then appproximate where the image was taken from.

`flag format -> LITCTF{lattitude,longitude} and roundoff the lattitude and longitude to 3 decimal places.`

Challenge Link -> https://lit.lhsmathcs.org/ctfchal
