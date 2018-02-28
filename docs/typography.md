 Text is one of the most important way to provide informations to users. It is used to create visual hierarchy between elements and maximize readability.
 Having a good typography and following good typography principles is very important.

## Font

The font used is `Roboto Condensed`.

ABCDEFGHIJKLMNOPQRSTUVWXYZ
abcdefghijklmnopqrstuvwxyz
0123456789

## Weights

This is a regular text - $regular - 400
_This is an italic text - $italic - 400_

**This is a bold text - $bold - 700**
**_This is a bold italic text - $boldItalic - 700_**

## Sizes

**Headings**

```type
{
  "headings": [
    { "label": "$uberSize - H1 - Line height 81px", "value": 54 },
    { "label": "$heroSize - H2 - Line height 72px", "value": 48 },
    { "label": "$giantSize - H3 - Line height 60px", "value": 40 },
    { "label": "$extraLargeSize - H4 - Line height 48px", "value": 32 },
    { "label": "$largeSize - H5 - Line height 36px", "value": 24 },
    { "label": "$mediumSize - H6 - Line height 27px", "value": 18 }
  ],
  "font": "sans-serif",
  "color": "#333333"
}
```

```type
{
  "paragraphs": [
    { "label": "$regularSize - Paragraph 16px / Line height 24px", "value": "16/24" }
  ],
  "font": "sans-serif",
  "color": "#333333"
}
```

```type
{
  "paragraphs": [
    { "label": "$smallSize - Paragraph 14px / Line height 21px", "value": "14/21" }
  ],
  "font": "sans-serif",
  "color": "#333333"
}
```

```type
{
  "paragraphs": [
    { "label": " $captionSize - Paragraph 12px / Line height 18px", "value": "12/18" }
  ],
  "font": "sans-serif",
  "color": "#333333"
}
```

**Specific text size**

You should avoid using text sizes which are not included in this styleguide. They add consistency and hierarchy to the
content and were created with these objectives.

In case you **must** add a new text size (to answer an accessibility problem for example), don't forget to add it to
the styleguide, with the appropriate line-height.


## Line height:

The line height is determined by the following equation :
`font-size + (font-size / 2)`.

In case of an odd number (like 13px), the result of the equation should be rounded to the `superior number`.

Example: With a 13px text size, line-height would be : `13 + (13/2) = 19,5` rounded to `20`.
