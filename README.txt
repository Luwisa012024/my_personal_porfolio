Nicole Loise Alejandro - Personal Info & Project Gallery
This is a simple HTML-based portfolio showcasing the personal information and project gallery of Nicole Loise Alejandro, a fourth-year nursing student. The project is composed of two main pages:

1.Home Page (index3.html): Displays personal information, hobbies, and a description of Nicole's educational journey.
2.Project Gallery Page (project.html): A gallery of images showcasing Nicole's academic and professional experiences.

Project Structure
project-root/
│
├── index3.html        # Personal Info Page (Home)
├── project.html       # Project Gallery Page
├── img/               # Folder for all gallery images
│   ├── 1.jpg
│   ├── 2.jpg
│   └── ...           # More images
├── README.md          # Project README file (this file)
└── style.css          # Styles integrated within the HTML files

Technologies Used
HTML5: Structure and layout of the pages.
CSS3: For the styling, including a frosted glass effect, falling petal animation, and responsive design.

Features
-Personal Info Page (index.html)
-Displays Nicole Loise Alejandro's personal details such as:
-Name, profession, and contact information (email, social media, phone).
Hobbies, such as watching series and creating visual art.
A detailed description of Nicole's journey as a nursing student.
Features a frosted glass style container with a dark theme.
Includes a simple navigation bar with links to the gallery.
Includes falling petal animations for visual appeal.

Project Gallery Page (project.html)
-A responsive image gallery showcasing various moments from Nicole's nursing journey and experiences.
Hover effects that slightly zoom in on the image when hovered.
-A lightbox feature that displays the full-sized image when clicked, and can be closed with a click.

Setup and Usage

Running the Project
-Clone or download this repository to your local machine.
-Navigate to the project folder and open index3.html or project.html in your browser.

Viewing the Pages
-Home Page: Open index3.html in your browser to view the personal information page.
-Project Gallery: Open project.html to see Nicole's project gallery.

-Adding New Images to the Gallery
-Add the image files to the img/ folder.
-In the project.html file, add new image elements inside the <div class="gallery"> section. 
For example:
<div class="image-wrapper">
    <img src="img/new-image.jpg" alt="New image description" onclick="openLightbox(this)">
</div>