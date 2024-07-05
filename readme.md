# CSS Utility Classes

This document provides a comprehensive guide to the CSS utility classes designed for quick and efficient styling of web pages. These utility classes cover a wide range of CSS properties, including typography, spacing, display, flexbox, grid system, backgrounds, borders, dimensions, overflow, list style, positioning, visibility, and responsive design.

## Reset and Base Styles
- `* { padding: 0; margin: 0; box-sizing: border-box; }`: Resets padding, margin, and sets box-sizing to border-box for all elements.
- `html, body { height: 100%; width: 100%; }`: Sets the height and width of the html and body elements to 100%.

## Typography
- `.t-left`, `.t-right`, `.t-center`, `.t-justify`: Text alignment classes.
- `.fs-sm`, `.fs-md`, `.fs-lg`: Font size classes for small, medium, and large text.
- `.fw-light`, `.fw-normal`, `.fw-bold`: Font weight classes.
- `.tt-up`, `.tt-low`, `.tt-cap`: Text transform classes for uppercase, lowercase, and capitalize.
- `.c-muted`, `.c-primary`, etc.: Text color classes based on the context.

## Spacing
- `.m-0` to `.m-5`, `.p-0` to `.p-5`: Margin and padding classes with different sizes.
- `.mt-0` to `.mt-5`, `.pt-0` to `.pt-5`: Margin-top and padding-top classes.
- `.mb-0` to `.mb-5`, `.pb-0` to `.pb-5`: Margin-bottom and padding-bottom classes.
- `.ml-0` to `.ml-5`, `.pl-0` to `.pl-5`: Margin-left and padding-left classes.
- `.mr-0` to `.mr-5`, `.pr-0` to `.pr-5`: Margin-right and padding-right classes.

## Display and Flexbox
- `.d-blk`, `.d-in`, `.d-inblk`, `.d-f`, `.d-gr`: Display property classes.
- `.f-row`, `.f-col`, `.j-start`, `.j-center`, etc.: Flexbox related classes.

## Grid
- `.gr-2`, `.gr-3`, `.gr-4`: Grid template columns classes.
- `.gr-gap-1`, `.gr-gap-2`, `.gr-gap-3`: Grid gap classes.

## Backgrounds and Borders
- `.bg-primary`, `.bg-success`, etc.: Background color classes.
- `.b`, `.b-top`, `.b-right`, etc.: Border classes.
- `.br-1`, `.br-2`, `.br-3`, `.br-50`: Border-radius classes.

## Width, Height, and Overflow
- `.w-25`, `.w-50`, etc., `.h-25`, `.h-50`, etc.: Width and height percentage classes.
- `.w-2`, `.w-4`, etc., `.h-2`, `.h-4`, etc.: Width and height in pixels classes.
- `.ov-hidden`, `.ov-scroll`, `.ov-auto`: Overflow classes.

## Positioning and Visibility
- `.pos-static`, `.pos-rel`, etc.: Position classes.
- `.top-0`, `.top-50`, etc.: Top position classes.
- `.vis-visible`, `.vis-hidden`: Visibility classes.

## Media Queries
- Media queries for extra small to extra large devices with overrides for font sizes, padding, and margin.

Use these utility classes to style your HTML elements quickly by adding the respective class names to your elements. This modular approach helps in maintaining a consistent design throughout your web application.
