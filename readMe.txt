readMe

# My Portfolio

This is a simple personal portfolio webpage created with HTML and CSS, focusing on CSS Flexbox for responsiveness.

## Project Structure

- personalportfolio.html: Main HTML file containing the structure of the webpage.
- personalportfolio: CSS file with styles for the webpage.
- profile.jpg, project1.jpg, project2.jpg: Image assets used in the portfolio.

## Choices Made During Development

- Used semantic HTML elements for better structure and accessibility.
- Implemented Flexbox to create a responsive layout.
- Included interactive features like hover effects on navigation links and project cards.
- Utilized media queries for responsiveness on smaller screens.




header {
    background-color: #f0f0f0; /* Set your desired background color */
}

.nav-list {
    display: flex;
    justify-content: space-around;
    padding: 10px; /* Adjust padding as needed */
}

.nav-item {
    list-style: none;
}

.nav-item li {
    margin: 0;
}

a {
    text-decoration: none;
    color: #333; /* Set your desired text color */
    display: block;
    padding: 10px;
    border-radius: 5px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1); /* Adjust shadow as needed */
    transition: background-color 0.3s ease;
}

a:hover {
    background-color: #ddd; /* Set your desired hover background color */
}