Dynamic Gallery

A simple Dynamic Gallery created using HTML5 and CSS3. The project displays multiple images in four vertical columns, with each column containing the images in a different order.

📌 Project Overview

This project demonstrates how to create a basic image gallery using:

- HTML
- CSS
- Flexbox
- Image elements
- CSS box sizing

The gallery is divided into four equal columns, and images are arranged differently in each column to create a dynamic visual layout.

🛠️ Technologies Used

- HTML5
- CSS3

📂 Project Structure

Dynamic-Gallery/
│
├── index.html
├── image 1.PNG
├── image 2.PNG
├── image 3.PNG
├── image 4.PNG
└── README.md

✨ Features

- Four-column image gallery
- Four images displayed in each column
- Different image arrangements in each column
- Equal-width gallery columns
- Simple and clean design
- Uses CSS Flexbox for the main gallery layout
- Images automatically fit the width of their column

🎨 Layout

The main gallery container uses:

.con {
    height: 600px;
    display: flex;
}

The four gallery columns each use:

.box {
    height: 100%;
    width: 25%;
}

Since each column has a width of 25%, four columns fill the complete width of the gallery.

🖼️ Images

The project uses four image files:

image 1.PNG
image 2.PNG
image 3.PNG
image 4.PNG

Each image is displayed using:

<img src="image 1.PNG" alt="">

Make sure all image files are located in the same directory as "index.html".

🚀 How to Run

1. Download or clone the project.

2. Place the following files in the same folder:

index.html
image 1.PNG
image 2.PNG
image 3.PNG
image 4.PNG

3. Open "index.html" in a web browser.

You can also use VS Code Live Server to run the project.

📐 CSS Explanation

Main Container

.con {
    height: 600px;
    border: 1px solid black;
    display: flex;
}

This creates the main gallery area with a fixed height of 600px and uses Flexbox to arrange the columns horizontally.

Gallery Columns

.box {
    height: 100%;
    width: 25%;
    border: 1px solid black;
}

Each ".box" takes up 25% of the available width, creating four equal columns.

Images

img {
    width: 100%;
}

Each image takes the full width of its respective gallery column.

Global Styling

* {
    padding: 0%;
    margin: 0%;
    box-sizing: border-box;
}

This removes the default margin and padding and makes sizing more predictable.

🔮 Future Improvements

The project can be improved by adding:

- Responsive design for mobile devices
- Image hover effects
- Image captions
- Click-to-enlarge functionality
- CSS Grid or Masonry layout
- Smooth animations
- Lightbox functionality
- JavaScript-based dynamic image loading
- Search and filtering options

📱 Responsive Design

Currently, the gallery is designed primarily for larger screens. Media queries can be added to change the number of columns on smaller devices.

For example:

@media (max-width: 768px) {
    .con {
        flex-wrap: wrap;
    }

    .box {
        width: 50%;
    }
}

@media (max-width: 480px) {
    .box {
        width: 100%;
    }
}

👨‍💻 Author

BCA 1st Year Student
Dezyne Ecole College

📄 License

This project is created for educational and learning purposes. Feel free to modify and improve it for your own projects.# Dynamic-Gallery
