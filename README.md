# [flexiblecss-scss](http://flexible.gs)

Flexible Front End Framework

## Install

### [Download](https://raw.githubusercontent.com/flexiblegs/flexiblecss-scss/master/flexiblecss-scss.scss)
```scss
$flexiblecss-base: ("true");


$property-font-family: (
  "open-sans": "Open Sans",
  "source-code-pro": "Source Code Pro"
);


$flexiblecss-breakpoint: (
  xl : "",
  lg : "(max-width: 1024px)",
  md : "(max-width: 768px)",
  sm : "(max-width: 667px)"
);


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


$property-border-color: (
  "white" : "#FFFFFF",
  "black" : "#222222"
);
$selector-border-color: (
  "cl": "breakpoint-class",
  "ho": "hover",
  "pl": "placeholder",
);


$property-border-width: (
  "0",
  "1",
  "2"
);
$selector-border-width: (
  "cl": "breakpoint-class"
);


$property-border-style: (
  "bso": "solid",
  "bda": "dashed",
  "bdo": "dotted"
);
$selector-border-style: (
  "cl": "not-breakpoint-class"
);


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


$property-opacity: (
  "25": "0.25",
  "50": "0.50",
  "75": "0.75"
);
$selector-opacity: (
  "cl": "not-breakpoint-class",
  "ho": "hover",
);


$property-position: (
  "pr": "relative",
  "pa": "absolute",
  "pf": "fixed",
  "ps": "static"
);
$selector-position: (
  "cl": "breakpoint-class"
);


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


$property-bottom: (
  "100%",
  "0",
  "8",
  "16",
  "-8",
  "-8"
);
$selector-bottom: (
  "cl": "breakpoint-class"
);


$property-z-index: (
  "1",
  "2",
  "3"
);
$selector-z-index: (
  "cl": "not-breakpoint-class"
);


$property-display: (
  "db": "block",
  "dib": "inline-block"
);
$selector-display: (
  "cl": "breakpoint-class"
);


$property-width: (
  "1280"
);
$selector-width: (
  "cl": "not-breakpoint-class"
);


$property-max-width: (
  "1280"
);
$selector-max-width: (
  "cl": "not-breakpoint-class"
);


$property-min-width: (
  "1280"
);
$selector-min-width: (
  "cl": "not-breakpoint-class"
);


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


$property-overflow: (
  "ov": "visible",
  "oh": "hidden",
  "oa": "auto",
  "os": "scroll"
);
$selector-overflow: (
  "cl": "breakpoint-class"
);


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


$property-text-align: (
  "tal": "left",
  "tar": "right",
  "tac": "center",
  "taj": "justify"
);
$selector-text-align: (
  "cl": "breakpoint-class"
);


$property-letter-spacing: (
  "1",
  "2"
);
$selector-letter-spacing: (
  "cl": "not-breakpoint-class"
);


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


$property-font-style: (
  "fsi": "italic"
);
$selector-font-style: (
  "cl": "not-breakpoint-class"
);


$property-vertical-align: (
  "vat": "top",
  "vam": "middle",
  "vab": "bottom"
);
$selector-vertical-align: (
  "cl": "not-breakpoint-class"
);


$property-text-transform: (
  "ttu": "uppercase",
  "ttl": "lowercase",
  "ttc": "capitalize"
);
$selector-text-transform: (
  "cl": "not-breakpoint-class"
);


$property-text-decoration: (
  "tdu": "underline",
  "tdlt": "line-through"
);
$selector-text-decoration: (
  "cl": "not-breakpoint-class",
  "ho": "hover",
);


$property-text-overflow: (
  "toe": "ellipsis"
);
$selector-text-overflow: (
  "cl": "not-breakpoint-class"
);


$property-white-space: (
  "wsnw": "nowrap",
  "wspw": "pre-wrap"
);
$selector-white-space: (
  "cl": "not-breakpoint-class"
);


$property-word-break: (
  "wbbw": "break-word"
);
$selector-word-break: (
  "cl": "not-breakpoint-class"
);


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


$property-user-select: (
  "usn": "none",
  "ust": "text"
);
$selector-user-select: (
  "cl": "not-breakpoint-class"
);


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
