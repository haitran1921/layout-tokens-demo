# Layout Tokens Demo

This repository demonstrates the implementation of Level 3 Layout Tokens in a practical UI wireframe. Each token is visualized through concrete examples showing how they affect layout and spacing in a real UI context.

## Token Implementation Guide

### Spacing Tokens
- `layout.element.paddingX/Y`: Base padding for zones (32px horizontal, 24px vertical)
- `layout.element.nestedPaddingX/Y`: Reduced padding for nested elements (20px horizontal, 16px vertical)
- `layout.element.textToText`: Vertical spacing between text elements (16px)
- `layout.element.textToIcon`: Gap between text and icons (8px)
- `layout.element.textToButton`: Space between text and buttons (12px)
- `layout.element.groupGap`: Spacing in form groups (8px)
- `layout.element.nestedGap`: Reduced spacing for nested elements (12px)

### Layout Tokens
- `layout.element.fullWidth`: Removes horizontal constraints
- `layout.element.radius`: Border radius for zones (8px)
- `layout.element.nestedRadius`: Smaller radius for nested elements (4px)
- `layout.element.shadow`: Default shadow for zones
- `layout.element.nestedShadow`: Flat appearance for nested elements
- `layout.element.alignment`: Content alignment options
- `layout.element.wrap`: Flex-wrap behavior
- `layout.element.overlap`: Layered element positioning

## Usage

Open `index.html` in a web browser to see the demonstration of all layout tokens in action. Each section demonstrates different aspects of the layout system:

1. Basic zones with default padding and shadow
2. Nested cards with reduced spacing
3. Text spacing demonstrations
4. Form group layouts
5. Full-width containers
6. Centered content
7. Wrap behavior
8. Overlapping elements

## Visual Examples

Each token is implemented in a way that clearly shows its effect on the layout. The demo includes:
- Container zones
- Nested cards
- Text elements
- Form inputs
- Buttons
- Icons
- Overlapping cards
- Responsive layouts

## Implementation Details

All tokens are implemented using CSS custom properties (variables) and can be easily modified in the `styles.css` file. The implementation focuses on:
- Consistent spacing
- Visual hierarchy
- Responsive design
- Clean, maintainable code