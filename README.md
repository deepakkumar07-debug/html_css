
# Box model

The box model is a fundamental concept in HTML and CSS that describes how elements are structured in terms of content, padding, border, and margin. Each HTML element is considered a box, and the box model helps define the space each box occupies.

1. **Content**: This is the actual content of the element, such as text, images, or other media. It is enclosed by the padding.

2. **Padding**: Padding is the space between the content and the element's border. It helps to create space inside the element, providing a visual separation between the content and the border.

3. **Border**: The border surrounds the padding and content. It can be styled and colored to create visual distinctions between elements.

4. **Margin**: The margin is the space outside the element's border. It provides separation between the element and its surrounding elements.

```code
+-----------------------------+
|          Margin             |
|  +-----------------------+  |
|  |       Border          |  |
|  |  +-----------------+  |  |
|  |  |     Padding     |  |  |
|  |  |  +-----------+  |  |  |
|  |  |  |  Content  |  |  |  |
|  |  |  +-----------+  |  |  |
|  |  +-----------------+  |  |
|  +-----------------------+  |
+-----------------------------+

```
- to achieve box model we can use width, height, padding, border, margin. 
- override default margin, padding, why we should override, because when we override it will apply to all elements
- box-sizing property on div - but this only affects this div
- Total Width = Content Width + Padding + Border + Margin

# Flex box
flex container has following properties

`justify-content` main axis
`align-items` cross axis
if we change flex direction main axis become cross axis
`align-items` cross axis

`align-content` works only if we set `flex-wrap` set to wrap 

## flex items
flex items has like `.item-1` has following propeties

```css
flex-grow: 1;
flex-shrink: 0;
flex-basis: 300px;
flex: 1;

```
also it has align-self which overrides containers align items property

## Grid
Grids are two dimensional layouts, we can place things on it horizontally or vertically or even both