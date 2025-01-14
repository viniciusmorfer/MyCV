
# CV Portfolio

## Overview

This project is a simple CV portfolio website designed to showcase personal information, skills, resume, portfolio, and contact details in a clean and professional layout. It is built with HTML, CSS, and Materialize CSS framework for responsive design and Font Awesome for social media icons and other icons.

## Features

- **Responsive Layout**: The website is designed to work on both desktop and mobile devices, adapting to screen size.
- **Sidebar Navigation**: A fixed sidebar that allows easy navigation between sections.
- **Smooth Scrolling**: Navigation links scroll smoothly to corresponding sections on the page.
- **Social Media Integration**: Links to personal social media profiles are included in the sidebar.
- **Portfolio Section**: Displays projects with images, descriptions, and links to external websites.
- **Contact Form**: Users can submit inquiries through a contact form.
- **Embedded Map**: An embedded Google map shows the address location.

## Technologies Used

- **HTML**: Provides the structure for the webpage.
- **CSS**: Custom styles to make the page visually appealing and responsive.
- **Materialize CSS**: A CSS framework for responsive design and ready-to-use components.
- **Font Awesome**: Provides scalable vector icons for social media links and other icons.
- **Google Maps API**: Embedded map to display the location.

## Installation

To get started with this project, follow the steps below:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/cv-portfolio.git
   ```

2. **Navigate into the project directory**:
   ```bash
   cd cv-portfolio
   ```

3. **Open the `index.html` file in your web browser**:
   Simply double-click the `index.html` file to open it in your default browser.

## Customization

You can personalize this CV portfolio by modifying the following files:

- **index.html**: This is the main HTML file that contains the structure of the webpage. You can update sections such as "About Me", "Resume", "Portfolio", and "Contact" with your personal information.
- **styles.css**: This file contains custom CSS styles. Modify the colors, fonts, and layout according to your preferences.

To change the profile picture, replace the `src` of the `<img>` tag in the sidebar:
```html
<img src="path/to/your/profile-image.jpg" alt="Profile Picture">
```

To modify the portfolio section, add or update cards like this:
```html
<div class="card">
    <img src="path/to/project-image.jpg" alt="Project Name">
    <h3>Project Name</h3>
    <a href="https://project-link.com" target="_blank">Visit Website</a>
    <p>Project Duration</p>
    <p>Short Description</p>
</div>
```

## Contributing

If you'd like to contribute to this project, feel free to fork the repository and submit a pull request with your changes. Please ensure that your contributions align with the overall structure and style of the project.

## License

This project is open source and available under the [MIT License](LICENSE).

