a) Documentation
Main Concepts Applied
In this project, I created a single-page portfolio using HTML for layout, Tailwind CSS for styling, and JavaScript to manage section visibility. Key concepts included:

HTML Structure: Each main section (Home, About, Education, Contact) is wrapped in <div> elements, making the content easy to identify and manage.
Styling with Tailwind CSS: I used Tailwind for fast and responsive styling. Classes like flex, text-lg, and bg-gray-700 provided a sleek dark theme and ensured a consistent layout.
JavaScript for Navigation: JavaScript functions toggle the display of each section, giving the page a smooth, interactive feel.
New Skills or Knowledge Acquired
I became more comfortable with utility-first CSS through Tailwind, which made styling quicker and allowed for a cohesive design. This project also helped me better understand how to use JavaScript for single-page content management.

b) Reflection
What I Learned
This project taught me how to combine HTML, CSS, and JavaScript to build a portfolio that’s both functional and visually appealing. It also reinforced the value of responsive design principles for optimal display on different devices.

Challenges Faced
1. JavaScript Section Toggle Issue:

Challenge: Initially, all sections displayed at once, as I hadn’t set default visibility.
Solution: Adding window.onload = function() { showSection('mainSection'); } ensured that only the home section displayed by default, while others were hidden until selected.
2. Responsiveness Adjustments:

Challenge: The layout appeared stretched on smaller screens.
Solution: Using Tailwind’s responsive classes (sm:, md:, lg:) for font sizes and spacing improved readability and layout adaptability on mobile devices.