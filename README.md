Assignment 2: Advanced CSS (Flexbox & Grid)
Name: Nauryzgali Yerassyl
Group: IT-2513

Task 0 & 1: Flexbox (Navigation Bar and Card Row)
<img width="1920" height="1080" alt="Снимок экрана (222)" src="https://github.com/user-attachments/assets/62d5a8df-343c-48da-98d9-53b24c46e0ad" />

Task 2 & 3: Grid System (Page Layout and Image Gallery)
<img width="1920" height="1080" alt="Снимок экрана (223)" src="https://github.com/user-attachments/assets/a2920db6-5b54-4303-b27b-cd939ed46260" />
<img width="1920" height="1080" alt="Снимок экрана (225)" src="https://github.com/user-attachments/assets/98ce46e7-7f72-48ed-9103-f0d45373c4ce" />

Task 4: Combining Flexbox & Grid (Portfolio Page)
<img width="1920" height="1080" alt="Снимок экрана (226)" src="https://github.com/user-attachments/assets/6598a632-ec2c-4b02-a8b7-c2dac4c693cb" />

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
