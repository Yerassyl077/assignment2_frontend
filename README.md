Assignment 2: Advanced CSS (Flexbox & Grid)
Name: Nauryzgali Yerassyl
Group: IT-2513

Task 0 & 1: Flexbox (Navigation Bar and Card Row)
<img width="1919" height="964" alt="photo_5309868884548591333_w" src="https://github.com/user-attachments/assets/c021f74d-dd5c-44a1-bd85-6e40614222e8" />

Task 2 & 3: Grid System (Page Layout and Image Gallery)
<img width="1919" height="962" alt="photo_5309868884548591335_w" src="https://github.com/user-attachments/assets/b072f7f0-9582-4303-a4ab-7640ee5d3d54" />
<img width="1919" height="956" alt="photo_5309868884548591336_w" src="https://github.com/user-attachments/assets/34097c5d-823f-4fca-8c75-33f129e5926c" />

Task 4: Combining Flexbox & Grid (Portfolio Page)
<img width="1919" height="959" alt="photo_5309868884548591337_w" src="https://github.com/user-attachments/assets/6fbd63f4-89f2-46c7-abcf-5f57b2adaf52" />

Summary of Work Process

During this assignment, I focused on building complex, responsive web layouts using modern CSS techniques without relying on outdated floats or external frameworks.

### Task 0 & 1: Flexbox (Navigation Bar and Card Row)
In the first part of the assignment, I learned how to use Flexbox to align elements efficiently. For the navigation bar, I applied `display: flex` with `justify-content: space-between` to separate the logo and the navigation links. I also used the `gap` property to create even spacing between the links. For the card row, I turned the main container into a flex container to arrange the cards in a horizontal row. I ensured that all cards have equal heights by using `align-items: stretch` and `flex-grow: 1` for the text content inside the cards. Finally, I added a smooth hover effect using the `box-shadow` and `transform` properties to make the cards interactive.

### Task 2: Grid System (Page Layout)
For the page layout, I utilized CSS Grid to create a structured and semantic design. I set the parent container to `display: grid` and defined specific rows and columns. Using the `grid-template-areas` property, I successfully mapped out the layout so that the header spans across the top, the sidebar is fixed on the left, the main content takes up the remaining space on the right, and the footer spans across the bottom. This method proved to be highly efficient for building clear and responsive two-column layouts.

### Task 3: Image Gallery
In the image gallery task, I continued working with CSS Grid to arrange nine image placeholders. I used `grid-template-columns: repeat(3, 1fr)` to create a perfectly balanced three-column grid with consistent gaps between the items. To make the gallery interactive, I implemented a hover effect using CSS transitions and absolute positioning. When a user hovers over a gallery item, a hidden caption smoothly appears over the image, enhancing the overall user experience.

### Task 4: Combining Flexbox & Grid (Portfolio Page)
The final task required combining both Flexbox and Grid to build a complete portfolio page structure. I used CSS Grid for the main macro-layout to separate the projects area (left) from the info sidebar (right). Inside the header and the individual project cards, I used Flexbox (micro-layout) to align the internal content, such as titles, descriptions, and buttons. This combined approach demonstrated how Grid is perfect for overall page structures, while Flexbox is ideal for aligning content within specific components.
