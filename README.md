# [pixelperfectcss-scss](http://pixelperfectcss.com)

Pixel Perfect CSS (Scss)

## Install

### [npm](https://www.npmjs.com/package/pixelperfectcss-scss)
```
$ npm install --save pixelperfectcss-scss
```

### [bower](http://bower.io/search/?q=pixelperfectcss-scss)
```
$ bower install --save pixelperfectcss-scss
```

### [Download](https://raw.githubusercontent.com/pixelperfectcss/pixelperfectcss-scss/master/pixelperfectcss-scss.scss)
```scss
// base
$pixelperfectcss-base: (
  "true"
);

// font-family
$property-font-family: (
  "open-sans": "Open Sans",
  "source-code-pro": "Source Code Pro",
);

// breakpoint
$pixelperfectcss-breakpoint: (
  "xl": "",
  "lg": "(max-width: 1024px)",
  "md": "(max-width: 768px)",
  "sm": "(max-width: 667px)",
);

// color, background-color, border-color
$property-color: (
  "white":       "#FFFFFF",

  "gray-100":    "#F5F5F5",
  "gray-200":    "#E8E8E8",
  "gray-300":    "#D8D8D8",
  "gray-400":    "#B1B1B1",
  "gray-500":    "#A1A1A1",

  "red-100":     "#FCA9B6",
  "red-200":     "#F9536D",
  "red-300":     "#F72848",
  "red-400":     "#C6203A",
  "red-500":     "#94182B",

  "green-100":   "#A0EEC3",
  "green-200":   "#41DD87",
  "green-300":   "#12D469",
  "green-400":   "#0EAA54",
  "green-500":   "#0B7F3F",

  "blue-100":    "#9FD4FB",
  "blue-200":    "#40A9F8",
  "blue-300":    "#1094F6",
  "blue-400":    "#0D76C5",
  "blue-500":    "#0A5994",

  "purple-100":  "#D5B1E5",
  "purple-200":  "#AC63CA",
  "purple-300":  "#973CBD",
  "purple-400":  "#793097",
  "purple-500":  "#5B2471",

  "yellow-100":  "#FFEB99",
  "yellow-200":  "#FFD633",
  "yellow-300":  "#FFCC00",
  "yellow-400":  "#CCA300",
  "yellow-500":  "#997A00",

  "black-100":   "#666666",
  "black-200":   "#555555",
  "black-300":   "#444444",
  "black-400":   "#333333",
  "black-500":   "#222222",
);
$selector-color: (
  "cl": "not-breakpoint-class",
  "ho": "hover",
  "fo": "focus",
  "ac": "active",
);

// width
$property-border-width: (
  "0",
  "1",
  "2",
);
$selector-border-width: (
  "cl": "not-breakpoint-class",
);

// border-style
$property-border-style: (
  "bsso": "solid",
  "bsda": "dashed",
  "bsdo": "dotted",
);
$selector-border-style: (
  "cl": "not-breakpoint-class",
);

// border-radius
$property-border-radius: (
  "50%",
  "0",
  "4",
  "8",
  "16",
  "24",
  "40",
);
$selector-border-radius: (
  "cl": "not-breakpoint-class",
);

// position
$property-position: (
  "pr": "relative",
  "pa": "absolute",
  "pf": "fixed",
  "ps": "static",
);
$selector-position: (
  "cl": "not-breakpoint-class",
);

// left, right, top, bottom
$property-position-value: (
  "100%",
  "50%",
  "0",
  "8",
  "16",
  "-8",
  "-16",
);
$selector-position-value: (
  "cl": "not-breakpoint-class",
);

// z-index
$property-z-index: (
  "1",
  "2",
);
$selector-z-index: (
  "cl": "not-breakpoint-class",
);

// transform
$property-transform: (
  "tn": "none",
);
$selector-transform: (
  "cl": "breakpoint-class",
);

// transform-translate
$property-transform-translate: (
  "50": "50%",
  "-50": "-50%",
);
$selector-transform-translate: (
  "cl": "not-breakpoint-class",
);

// display
$property-display: (
  "dn": "none",
  "db": "block",
  "di": "inline-block",
);
$selector-display: (
  "cl": "breakpoint-class",
);

// width
$property-width: (
  "1280",
);
$selector-width: (
  "cl": "not-breakpoint-class",
);

// max-width
$property-max-width: (
  "1280",
);
$selector-max-width: (
  "cl": "not-breakpoint-class",
);

// min-width
$property-min-width: (
  "1280",
);
$selector-min-width: (
  "cl": "not-breakpoint-class",
);

// line-height
$property-line-height: (
  "0",
  "12",
  "14",
  "16",
  "18",
  "20",
  "22",
  "24",
);
$selector-line-height: (
  "cl": "not-breakpoint-class",
);

// height
$property-height: (
  "0",
  "8",
  "16",
  "24",
  "40",
);
$selector-height: (
  "cl": "not-breakpoint-class",
);

// max-height
$property-max-height: (
  "0",
  "8",
  "16",
  "24",
  "40",
);
$selector-max-height: (
  "cl": "not-breakpoint-class",
);

// min-height
$property-min-height: (
  "0",
  "8",
  "16",
  "24",
  "40",
);
$selector-min-height: (
  "cl": "not-breakpoint-class",
);

// margin
$property-margin: (
  "auto",
  "0",
  "8",
  "16",
  "24",
  "40",
);
$selector-margin: (
  "cl": "breakpoint-class",
);

// padding
$property-padding: (
  "0",
  "8",
  "16",
  "24",
  "40",
);
$selector-padding: (
  "cl": "breakpoint-class",
);

// overflow
$property-overflow: (
  "ov": "visible",
  "oh": "hidden",
  "oa": "auto",
  "os": "scroll",
);
$selector-overflow: (
  "cl": "breakpoint-class",
);

// opacity
$property-opacity: (
  "50": "0.50",
);
$selector-opacity: (
  "cl": "not-breakpoint-class",
  "ho": "hover",
);

// font-size
$property-font-size: (
  "0",
  "12",
  "14",
  "16",
  "18",
  "20",
  "22",
  "24",
);
$selector-font-size: (
  "cl": "not-breakpoint-class",
);

// text-align
$property-text-align: (
  "tal": "left",
  "tar": "right",
  "tac": "center",
  "taj": "justify",
);
$selector-text-align: (
  "cl": "breakpoint-class",
);

// letter-spacing
$property-letter-spacing: (
  "1",
  "2",
);
$selector-letter-spacing: (
  "cl": "not-breakpoint-class"
);

// font-weight
$property-font-weight: (
  "200",
  "300",
  "400",
  "500",
  "600",
  "700",
  "800",
  "900",
);
$selector-font-weight: (
  "cl": "not-breakpoint-class"
);

// font-style
$property-font-style: (
  "fsi": "italic",
);
$selector-font-style: (
  "cl": "not-breakpoint-class",
);

// vertical-align
$property-vertical-align: (
  "vat": "top",
  "vam": "middle",
  "vab": "bottom",
);
$selector-vertical-align: (
  "cl": "not-breakpoint-class"
);

// text-transform
$property-text-transform: (
  "ttu": "uppercase",
  "ttl": "lowercase",
  "ttc": "capitalize",
);
$selector-text-transform: (
  "cl": "not-breakpoint-class",
);

// text-decoration
$property-text-decoration: (
  "tdu": "underline",
  "tdlt": "line-through",
);
$selector-text-decoration: (
  "cl": "not-breakpoint-class",
  "ho": "hover",
);

// text-overflow
$property-text-overflow: (
  "toe": "ellipsis",
);
$selector-text-overflow: (
  "cl": "not-breakpoint-class",
);

// white-space
$property-white-space: (
  "wsnw": "nowrap",
  "wspw": "pre-wrap",
);
$selector-white-space: (
  "cl": "not-breakpoint-class",
);

// word-break
$property-word-break: (
  "wbbw": "break-word",
);
$selector-word-break: (
  "cl": "not-breakpoint-class",
);

// cursor
$property-cursor: (
  "ca": "auto",
  "cd": "default",
  "cp": "pointer",
  "ct": "text",
  "cn": "not-allowed",
);
$selector-cursor: (
  "cl": "not-breakpoint-class",
);

// user-select
$property-user-select: (
  "usn": "none",
  "ust": "text",
);
$selector-user-select: (
  "cl": "not-breakpoint-class",
);

// pointer-events
$property-pointer-events: (
  "pen": "none",
  "pea": "auto",
);
$selector-pointer-events: (
  "cl": "not-breakpoint-class",
);

@import "pixelperfectcss-scss";
```

## License
- Pixel Perfect CSS is licensed under the MIT license.
  - [http://opensource.org/licenses/MIT](http://opensource.org/licenses/MIT)
- Flexible Front End Framework documentation is licensed under a Creative Commons Attribution 4.0 International License.
  - [http://creativecommons.org/licenses/by/4.0](http://creativecommons.org/licenses/by/4.0)
