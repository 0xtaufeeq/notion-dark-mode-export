
# Notion Dark Mode Export

This method is applicable only for HTML files


## How to -

1. Open the HTML file in a text-editor.

2. Find the body tag and replace ```<body>``` with ```<body style="background-color: #000000; color: white;">```

3. Make sure you save the file.

4. Done! you now now have your export in dark mode. And if you are using selects, then follow along.

5. Find this piece of code 

```
.select-value-color-pink { background-color: rgba(245, 224, 233, 1); }
.select-value-color-purple { background-color: rgba(232, 222, 238, 1); }
.select-value-color-green { background-color: rgba(219, 237, 219, 1); }
.select-value-color-gray { background-color: rgba(227, 226, 224, 1); }
.select-value-color-opaquegray { background-color: rgba(255, 255, 255, 0.0375); }
.select-value-color-orange { background-color: rgba(250, 222, 201, 1); }
.select-value-color-brown { background-color: rgba(238, 224, 218, 1); }
.select-value-color-red { background-color: rgba(255, 226, 221, 1); }
.select-value-color-yellow { background-color: rgba(253, 236, 200, 1); }
.select-value-color-blue { background-color: rgba(211, 229, 239, 1); }

```

and replce it with 

```
.select-value-color-pink { background-color: #69314c; }
.select-value-color-purple { background-color: #492f64; }
.select-value-color-green { background-color: #2b593f; }
.select-value-color-gray { background-color: #5a5a5a; }
.select-value-color-opaquegray { background-color: #2d2d2d; }
.select-value-color-orange { background-color: #854c1d; }
.select-value-color-brown { background-color: #603b2c; }
.select-value-color-red { background-color: #6e3630; }
.select-value-color-yellow { background-color: #89632a; }
.select-value-color-blue { background-color: #28456c; }

```

:)
## Author

- [TaufeeqRiyaz](https://github.com/TaufeeqRiyaz)

[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs)

