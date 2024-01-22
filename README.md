# Quarto Cheatsheet

This is a simple quarto extension to create cheat sheets as PDF files.

## Installation

Add to existing project:

```
$ quarto add produnis/quarto-cheatsheet
```

Use as template for a new project:

```
$ quarto use template produnis/quarto-cheatsheet
```

## Usage

Add an entry using:
```  
:::{.cheat title="Title of Node"}
Content of Node
:::
```

### Colors

You can change the colors of nodes, lines, headings and texts in `YAML` with parameters:

```
nodecolor: "185191"  # HTML color only
linecolor: "185191"  # HTML color only
headcolor: "FFFFFF"  # HTML color only
textcolor: "000000"  # HTML color only
```
As you can see, hexcode is supported, only.


## Screenshot

![](https://i.imgur.com/WKcvBvN.jpeg)