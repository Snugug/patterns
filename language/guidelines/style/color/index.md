---
type: guideline
title: Color
resources:
  files:
    name: "IBM Color Palette ASE"
    source: /assets/color/ibm-color-palette.ase
variables:
  example:
    paletteApplication:
      light:
        title: "Example: Light Palette"
        visualDisplay: /images/color/light-palette.svg
        description: "Primary: Blue 60, Secondary: Orange 50, Accent: Teal 40"
        caption: "Consider users who are sensitive to brightness and high contrast colors by using a neutral value as a background color instead of pure white."
      dark:
      title: "Example: Dark Palette"
      visualDisplay: /images/color/dark-palette.svg
      description: "Primary: Blue 30, Secondary: Orange 30, Accent: Teal 30"
      caption: "Consider users who are sensitive to brightness and high contrast colors by using a grey value as a background color instead of pure black."
  primaryColors:
    instructions: "Choose a primary and secondary color"
    colors:
      palette: Blue
      tone: 60
      adjectives:
        Trustworthy
        Systematic
      palette: Orange
      tone: 50
      adjectives: 
        Innovation
        Utility
      palette: Teal
      tone: 60
      adjectives:
        Awareness
        Approachability
  accentColors:
    instructions: "Choose an accent color. Add hues as necessary."
    colors:
      palette: Blue
      tone: 40
      palette: Orange
      tone: 30
      palette: Teal
      tone: 40
      palette: Yellow
      tone: 30
  supportingGreys:
    instructions: "Choose supporting greys and neutrals"
    colors:
      palette: Grey
      tone: 90
      palette: Grey
      tone: 80
      palette: Grey
      tone: 60
      palette: Grey
      tone: 50
      palette: Grey
      tone: 10
      palette: Neutral
      tone: 4
      palette: Neutral
      tone: 2
---

Color is a crucial component of our visual vernacular, helping to unify the look and feel of all communications. The [IBM Design Language](http://www.ibm.com/design/language/framework/visual/color.shtml) comprises a wide spectrum of colors; IBM Watson relies on a defined subset of those colors to establish its unique presence while respecting the broader IBM Design guidelines.

{{> SomeFunctionHere resources}}

## Colors for Watson

The colors chosen for IBM Watson are flexible and distinguish Watson as a brand across all user experiences. The colors chosen for IBM Watson were developed using color psychology to support the Watson [brand attributes](brand-attributes.html), reinforce Watson's personality, and set the tone of each specific product.

{{> primaryColorDisplay primaryColors}}

## Choosing A Color Palette

Choose a primary color, a secondary color, and an accent color. Additional tints and shades of the chosen palette can help to unify the design. These values can add variety to a palette without additional colors. Use the IBM Design Language for a wider variety of colors, values, and neutrals.

{{> colorPicker primaryColors}}

{{> colorPicker accentColors}}

{{> colorPicker supportingGreys}}

## Applying A Color Palette

Color is a powerful communication tool to determine hierarchy on a page. Use ample white space and neutrals to create balance and to direct users' attention.

{{> example paletteApplication.light }}

{{> example paletteApplication.dark }}