# Reflection on CSS Styling Assignment: The Fascinating World of Octopuses

## Development Process
 I started by carefully examining the screenshot to understand the desired layout, color scheme, and typography. I identified the key visual elements: a prominent blue header banner, white content areas with gray backgrounds, a light blue quiz section with side-by-side layout, a styled table, and a footer. 

After creating the CSS, I updated the HTML file to link to the external stylesheet and added detailed comments throughout the HTML structure to explain each section's purpose and styling approach. This dual approach—creating standalone CSS with clear organization, then enhancing HTML with documentation—ensured that my code would be maintainable and easy to understand.

## Challenges and Solutions

The quiz section in the screenshot shows an image positioned to the right of the form content. Initially, I considered using floats, but decided instead to use CSS Flexbox, which is more modern and flexible. I applied `display: flex` to the quiz section container with `gap: 20px` for spacing and used `flex-shrink: 0` on the image to prevent it from shrinking. This approach provides better responsive behavior.

The table needed to look professional while matching the overall design. I applied proper border collapse, added alternating row background colors using CSS selectors, and styled table headers with a distinct background color (`#e6e6e6`) to make them stand out. I also added padding to cells for better spacing and readability.

The screenshot shows clear hierarchy in text sizes and spacing. I carefully set font sizes for different heading levels (h2 through h6), used `text-transform: uppercase` for section titles to match the bold, capitalized appearance in the screenshot, and established consistent margin and padding values throughout the document for visual harmony.

## Key CSS Features Used

1. **Selectors**: ID selectors for major sections, element selectors for general styling, attribute selectors for input types, and pseudo-selectors (`:hover`) for interactive feedback.
2. **Box Model**: Extensive use of padding, margin, and border properties to create proper spacing and visual separation between content areas.
3. **Typography**: Font family (Arial), font weight (bold), font style (italic), font size variations, and text alignment properties to establish visual hierarchy.
4. **Colors and Backgrounds**: Background colors for major sections, color properties for text, creating distinct visual areas (blue header, white content, light blue quiz section, gray footer).
5. **Layout**: Flexbox for the quiz section to achieve the side-by-side image and form layout, text-align for centering, and proper content flow.
6. **Responsive Design**: Added media queries to ensure the layout adapts gracefully on smaller screens (tablets and mobile devices).
