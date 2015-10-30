# [flexiblecss-scss](http://flexible.gs)

Flexible Front End Framework

## Install

### [Download](https://raw.githubusercontent.com/flexiblegs/flexiblecss-scss/master/flexiblecss-scss.scss)
```scss
// base
$flexiblecss-base: ("true");

// font-family
$property-font-family: (
  "open-sans": "Open Sans",
  "source-code-pro": "Source Code Pro"
);

// breakpoint
$flexiblecss-breakpoint: (
  xl : "",
  lg : "(max-width: 1024px)",
  md : "(max-width: 768px)",
  sm : "(max-width: 667px)"
);

// color
$property-color: (
  "white" : "#FFFFFF",
  "black" : "#222222"
);
$selector-color: (
  "cl": "breakpoint-class",
  "ho": "hover",
  "pl": "placeholder",
  "se": "selection"
);

// background-color
$property-background-color: (
  "white" : "#FFFFFF",
  "black" : "#222222"
);
$selector-background-color: (
  "cl": "breakpoint-class",
  "ho": "hover",
  "pl": "placeholder",
  "se": "selection"
);

// border-color
$property-border-color: (
  "white" : "#FFFFFF",
  "black" : "#222222"
);
$selector-border-color: (
  "cl": "breakpoint-class",
  "ho": "hover",
  "pl": "placeholder",
);

// border-width
$property-border-width: (
  "0",
  "1",
  "2"
);
$selector-border-width: (
  "cl": "breakpoint-class"
);

// border-style
$property-border-style: (
  "bso": "solid",
  "bda": "dashed",
  "bdo": "dotted"
);
$selector-border-style: (
  "cl": "not-breakpoint-class"
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
  "cl": "breakpoint-class"
);

// opacity
$property-opacity: (
  "25": "0.25",
  "50": "0.50",
  "75": "0.75"
);
$selector-opacity: (
  "cl": "not-breakpoint-class",
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
  "cl": "breakpoint-class"
);

// left
$property-left: (
  "100%",
  "0",
  "8",
  "16",
  "-8",
  "-8"
);
$selector-left: (
  "cl": "breakpoint-class"
);

// right
$property-right: (
  "100%",
  "0",
  "8",
  "16",
  "-8",
  "-8"
);
$selector-right: (
  "cl": "breakpoint-class"
);

// top
$property-top: (
  "100%",
  "0",
  "8",
  "16",
  "-8",
  "-8"
);

$selector-top: (
  "cl": "breakpoint-class"
);

// bottom
$property-bottom: (
  "100%",
  "0",
  "8",
  "16",
  "-8",
  "-8"
);

// z-index
$property-z-index: (
  "1",
  "2",
  "3"
);
$selector-z-index: (
  "cl": "not-breakpoint-class"
);

// display
$property-display: (
  "db": "block",
  "dib": "inline-block"
);
$selector-display: (
  "cl": "breakpoint-class"
);

$selector-bottom: (
  "cl": "breakpoint-class"
);

// width
$property-width: (
  "1280"
);
$selector-width: (
  "cl": "not-breakpoint-class"
);

// max-width
$property-max-width: (
  "1280"
);
$selector-max-width: (
  "cl": "not-breakpoint-class"
);

// min-width
$property-min-width: (
  "1280"
);
$selector-min-width: (
  "cl": "not-breakpoint-class"
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
  "cl": "breakpoint-class"
);

// max-height
$property-max-height: (
  "0",
  "8",
  "16",
  "24",
  "40"
);
$selector-max-height: (
  "cl": "breakpoint-class"
);

// min-height
$property-min-height: (
  "0",
  "8",
  "16",
  "24",
  "40"
);
$selector-min-height: (
  "cl": "breakpoint-class"
);

// overflow
$property-overflow: (
  "ov": "visible",
  "oh": "hidden",
  "oa": "auto",
  "os": "scroll"
);
$selector-overflow: (
  "cl": "breakpoint-class"
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
  "cl": "breakpoint-class"
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
  "cl": "breakpoint-class"
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
  "cl": "breakpoint-class"
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
  "cl": "breakpoint-class"
);

// text-align
$property-text-align: (
  "tal": "left",
  "tar": "right",
  "tac": "center",
  "taj": "justify"
);
$selector-text-align: (
  "cl": "breakpoint-class"
);

// letter-spacing
$property-letter-spacing: (
  "1",
  "2"
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
  "900"
);
$selector-font-weight: (
  "cl": "not-breakpoint-class"
);

// font-style
$property-font-style: (
  "fsi": "italic"
);
$selector-font-style: (
  "cl": "not-breakpoint-class"
);

// vertical-align
$property-vertical-align: (
  "vat": "top",
  "vam": "middle",
  "vab": "bottom"
);
$selector-vertical-align: (
  "cl": "not-breakpoint-class"
);

// text-transform
$property-text-transform: (
  "ttu": "uppercase",
  "ttl": "lowercase",
  "ttc": "capitalize"
);
$selector-text-transform: (
  "cl": "not-breakpoint-class"
);

// text-decoration
$property-text-decoration: (
  "tdu": "underline",
  "tdlt": "line-through"
);
$selector-text-decoration: (
  "cl": "not-breakpoint-class",
  "ho": "hover",
);

// text-overflow
$property-text-overflow: (
  "toe": "ellipsis"
);
$selector-text-overflow: (
  "cl": "not-breakpoint-class"
);

// white-space
$property-white-space: (
  "wsnw": "nowrap",
  "wspw": "pre-wrap"
);
$selector-white-space: (
  "cl": "not-breakpoint-class"
);

// word-break
$property-word-break: (
  "wbbw": "break-word"
);
$selector-word-break: (
  "cl": "not-breakpoint-class"
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
  "cl": "not-breakpoint-class"
);

// user-select
$property-user-select: (
  "usn": "none",
  "ust": "text"
);
$selector-user-select: (
  "cl": "not-breakpoint-class"
);

// pointer-events
$property-pointer-events: (
  "pen": "none",
  "pea": "auto"
);
$selector-pointer-events: (
  "cl": "not-breakpoint-class"
);

@import "flexiblecss-scss";
```

## License
- Flexible Front End Framework is licensed under the MIT license.
  - [http://opensource.org/licenses/MIT](http://opensource.org/licenses/MIT)
- Flexible Front End Framework documentation is licensed under a Creative Commons Attribution 4.0 International License.
  - [http://creativecommons.org/licenses/by/4.0](http://creativecommons.org/licenses/by/4.0)
