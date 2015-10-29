# [flexiblecss-scss](http://flexible.gs)

Flexible Front End Framework

## Install

### [Download](https://raw.githubusercontent.com/flexiblegs/flexiblecss-scss/master/flexiblecss-scss.scss)
```scss
// base
$base: ("true");

// font-family
$property-font-family: (
  "open-sans": "Open Sans",
  "source-code-pro": "Source Code Pro"
);

// breakpoint
$breakpoint: (
  "xl" : "",
  "lg" : "(max-width: 1024px)"
);

// color
$property-color: (
  "white" : "#FFFFFF",
  "black" : "#222222"
);
$selector-color: (
  "cl": "class",
  "ho": "hover",,
  "pl": "placeholder",
  "se": "selection"
);

// background-color
$property-background-color: (
  "white" : "#FFFFFF",
  "black" : "#222222"
);
$selector-background-color: (
  "cl": "class",
  "ho": "hover",,
  "pl": "placeholder",
  "se": "selection"
);

// border-color
$property-border-color: (
  "white" : "#FFFFFF",
  "black" : "#222222"
);
$selector-border-color: (
  "cl": "class",
  "ho": "hover",,
  "pl": "placeholder",
);

// border-width
$property-border-width: (
  "0",
  "1",
  "2"
);
$selector-border-width: (
  "cl": "class",
  "ho": "hover",
);

// border-style
$property-border-style: (
  "bso": "solid",
  "bda": "dashed",
  "bdo": "dotted"
);
$selector-border-style: (
  "cl": "class",
  "ho": "hover",
);

// border-radius
$property-border-radius: (
  "0",
  "8",
  "16",
  "24",
  "40"
);
$selector-border-radius: (
  "cl": "class",
  "ho": "hover",
);

// position
$property-position: (
  "pr": "relative",
  "pa": "absolute",
  "pf": "fixed",
  "ps": "static"
);
$selector-position: (
  "cl": "class",
  "ho": "hover",
);

// left
$property-left: (
  "100%",
  "0"
);
$selector-left: (
  "cl": "class",
  "ho": "hover",
);

// right
$property-right: (
  "100%",
  "0"
);
$selector-right: (
  "cl": "class",
  "ho": "hover",
);

// top
$property-top: (
  "100%",
  "0"
);

$selector-top: (
  "cl": "class",
  "ho": "hover",
);

// bottom
$property-bottom: (
  "100%",
  "0"
);

$selector-bottom: (
  "cl": "class",
  "ho": "hover",
);

// width
$property-width: (
  "1280"
);
$selector-width: (
  "cl": "class",
  "ho": "hover",
);

// height
$property-height: (
  "0",
  "8",
  "16",
  "24",
  "40"
);
$selector-height: (
  "cl": "class",
  "ho": "hover",
);

// margin
$property-margin: (
  "0",
  "8",
  "16",
  "24",
  "40"
);
$selector-margin: (
  "cl": "class",
  "ho": "hover",
);

// padding
$property-padding: (
  "0",
  "8",
  "16",
  "24",
  "40"
);
$selector-padding: (
  "cl": "class",
  "ho": "hover",
);

// font-size
$property-font-size: (
  "12",
  "14",
  "16",
  "18",
  "20",
  "22",
  "24"
);
$selector-font-size: (
  "cl": "class",
  "ho": "hover",
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
  "24"
);
$selector-line-height: (
  "cl": "class",
  "ho": "hover",
);

// text-align
$property-text-align: (
  "tal": "left",
  "tar": "right",
  "tac": "center",
  "taj": "justify"
);
$selector-text-align: (
  "cl": "class",
  "ho": "hover",
);

// opacity
$property-opacity: (
  "25": "0.25",
  "50": "0.50",
  "75": "0.75"
);
$selector-opacity: (
  "cl": "class",
  "ho": "hover",
);

// letter-spacing
$property-letter-spacing: (
  "1",
  "2"
);
$selector-letter-spacing: (
  "cl": "class",
  "ho": "hover",
);

// z-index
$property-z-index: (
  "1",
  "2",
  "3"
);
$selector-z-index: (
  "cl": "class",
  "ho": "hover",
);

// display
$property-display: (
  "db": "block",
  "dib": "inline-block"
);
$selector-display: (
  "cl": "class",
  "ho": "hover",
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
  "900"
);
$selector-font-weight: (
  "cl": "class",
  "ho": "hover",
);

// font-style
$property-font-style: (
  "fsi": "italic"
);
$selector-font-style: (
  "cl": "class",
  "ho": "hover",
);

// vertical-align
$property-vertical-align: (
  "vat": "top",
  "vam": "middle",
  "vab": "bottom"
);
$selector-vertical-align: (
  "cl": "class",
  "ho": "hover",
);

// text-transform
$property-text-transform: (
  "ttu": "uppercase",
  "ttl": "lowercase",
  "ttc": "capitalize"
);
$selector-text-transform: (
  "cl": "class",
  "ho": "hover",
);

// text-decoration
$property-text-decoration: (
  "tdu": "underline",
  "tdlt": "line-through"
);
$selector-text-decoration: (
  "cl": "class",
  "ho": "hover",
);

// text-overflow
$property-text-overflow: (
  "toe": "ellipsis"
);
$selector-text-overflow: (
  "cl": "class",
  "ho": "hover",
);

// white-space
$property-white-space: (
  "wsnw": "nowrap",
  "wspw": "pre-wrap"
);
$selector-white-space: (
  "cl": "class",
  "ho": "hover",
);

// word-break
$property-word-break: (
  "wbbw": "break-word"
);
$selector-word-break: (
  "cl": "class",
  "ho": "hover",
);

// overflow
$property-overflow: (
  "ov": "visible",
  "oh": "hidden",
  "oa": "auto",
  "os": "scroll"
);
$selector-overflow: (
  "cl": "class",
  "ho": "hover",
);

// cursor
$property-cursor: (
  "ca": "auto",
  "cd": "default",
  "cp": "pointer",
  "ct": "text",
  "cn": "not-allowed"
);
$selector-cursor: (
  "cl": "class",
  "ho": "hover",
);

// user-select
$property-user-select: (
  "usn": "none",
  "ust": "text"
);
$selector-user-select: (
  "cl": "class",
  "ho": "hover",
);

// pointer-events
$property-pointer-events: (
  "pen": "none",
  "pea": "auto"
);
$selector-pointer-events: (
  "cl": "class",
  "ho": "hover",
);

@import "flexiblecss-scss";
```

## License
- Flexible Front End Framework is licensed under the MIT license.
  - [http://opensource.org/licenses/MIT](http://opensource.org/licenses/MIT)
- Flexible Front End Framework documentation is licensed under a Creative Commons Attribution 4.0 International License.
  - [http://creativecommons.org/licenses/by/4.0](http://creativecommons.org/licenses/by/4.0)
