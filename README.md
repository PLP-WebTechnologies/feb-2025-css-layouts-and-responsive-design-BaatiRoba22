# CSS Layouts and Responsive Design

## Objectives

Implement Flexbox and Grid for layout design.
Make the webpage responsive using media queries.
Ensure proper alignment and spacing.

## Instructions

- use Flexbox or CSS Grid.
- Add a navigation bar and structure the content.
- Use media queries to adjust layout for mobile, tablet, and desktop.

>[!NOTE]
>  - Include at least:
>  - navigation bar
>  - media queries

# Tasks

- Apply Flexbox or Grid for layout.
- Make the page responsive.
- Test across different screen sizes.
HTML Structure

   Start with a basic HTML structure for your page. This is a simple example:

   ```html
   <!DOCTYPE html>
   <html lang="en">
   <head>
       <meta charset="UTF-8">
       <meta name="viewport" content="width=device-width, initial-scale=1.0">
       <title>My Responsive Page</title>
       <link rel="stylesheet" href="style.css">
   </head>
   <body>
       <header>
           <nav>
               <ul>
                   <li><a href="#">Home</a></li>
                   <li><a href="#">About</a></li>
                   <li><a href="#">Contact</a></li>
               </ul>
           </nav>
       </header>
       <main>
           <section class="content">
               <!-- Your main content goes here -->
           </section>
       </main>
       <footer>
           <p>&copy; 2023 My Website</p>
       </footer>
   </body>
   </html>
   ```

2. CSS: Flexbox or Grid

   Flexbox:

   ```css
   /* Basic Flexbox Styles */
   body {
       margin: 0;
       font-family: sans-serif;
   }

   header {
       display: flex; /* Enable Flexbox */
       justify-content: space-between; /* Distribute space evenly */
       align-items: center; /* Vertically center items */
       padding: 1rem;
       background-color: #f0f0f0;
   }

   nav ul {
       list-style: none;
       margin: 0;
       padding: 0;
   }

   nav li {
       display: inline-block;
       margin-left: 20px;
   }

   nav a {
       text-decoration: none;
- 

Happy Coding! 💻✨
