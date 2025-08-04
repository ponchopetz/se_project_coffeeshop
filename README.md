# Triple Peaks Coffee Shop

This project is a responsive and visually engaging landing page for the "Triple Peaks Coffee Shop," a fictional café located in a library. It was developed as the second project for the TripleTen Software Engineering program. The primary goal was to build a static webpage from a design brief, focusing on modern web development practices.

The website is a single-page layout that provides users with information about the coffee shop, including its menu, recipes for home-brewing, a table reservation form, and contact details.

## Project features

- **Semantic HTML5**: The structure of the page is built with semantic tags (header, main, section, footer, nav) for better accessibility and SEO.

- **CSS3**: All styling is done using modern CSS. Key features include:

  - **Flexbox**: Used extensively for creating flexible and responsive layouts for sections like the navigation, header, menu cards, and footer.

  - **Positioning**: Absolute and relative positioning are used to layer elements, such as the main image in the header and the decorative circles in the "About" section.

  - **CSS Custom Properties (Variables)**: While not explicitly used in the provided files, this would be a natural next step for managing colors and fonts.

  - **CSS Animations & Transitions**: Subtle animations, like the pulsating circle and hover effects on links and buttons, are used to create a more dynamic user experience.

  - **Custom Form Styling**: The booking form and its checkbox element are custom-styled to create a unique look that overrides default browser styles.

- **Flat BEM (Block, Element, Modifier)**: A methodology for writing component-based, reusable, and maintainable CSS. The class names (.header**title, .nav**link, .form\_\_label_type_checkbox) follow this convention.

- **Responsive Design Principles**: The layout is designed to be functional and aesthetically pleasing, with considerations for how elements reflow and adapt.

## Plan on improving the project

While the current version of the project is a complete static page, here are some ideas for future enhancements:

1. **Interactive Menu with JavaScript:**

   - **Functionality**: Instead of a hard-coded HTML menu, the menu items could be stored in a JavaScript array of objects. A script would then dynamically generate the menu cards on the page.

   - **Benefit**: This would make the menu much easier to update and manage without touching the HTML structure. It also opens the door to adding features like filtering the menu by category (e.g., "Espresso", "Baked Goods") or highlighting daily specials.

2. **Advanced Form Validation & Submission:**

   - **Functionality**: Implement client-side validation using JavaScript to give users immediate feedback if they enter incorrect information (e.g., an invalid email format or a date in the past). Upon successful submission, instead of just having a button, the form could display a confirmation message or a "Thank You" modal without reloading the page.

   - **Benefit**: This creates a much smoother and more user-friendly experience, preventing user frustration and ensuring data is collected correctly.

3. **Dark/Light Mode Theme Toggle:**

   - **Functionality**: Add a toggle switch that allows users to switch between the current (light) theme and a new dark theme. This would be implemented by defining CSS variables for colors and changing their values based on a class applied to the <body> element.

   - **Benefit**: This is a popular feature that improves accessibility, reduces eye strain in low-light conditions, and allows for greater user personalization.

4. **Full Mobile-First Responsiveness**:

   - **Functionality**: Re-architect the CSS using a "mobile-first" approach with media queries (@media). This would involve designing the base styles for small screens and then adding complexity for larger screens (tablets, desktops).

   - **Benefit**: Ensures a seamless and optimized experience on all devices, which is critical for modern web development. The current min-width: 1100px on the .page class could be removed in favor of a more fluid layout.
