# 3D Virtual Art Gallery

An interactive 3D art gallery experience built with Three.js. This project showcases a collection of paintings in a virtual carousel, allowing users to navigate the space with smooth, animated transitions. It features a minimalist design with dynamic text overlays and a reflective floor to create an immersive environment.

![A screenshot of the 3D gallery](/public/art-gallery.png)


---

## Features

* **Interactive 3D Carousel**: Artworks are arranged in a circular gallery layout.
* **Smooth Navigation**: Clicking on navigation arrows triggers fluid animations to move between pieces.
* **Dynamic Information Display**: The title of the artwork and the artist's name are displayed for the current piece.
* **Realistic Environment**: The scene includes a spotlight focused on the artwork and a reflective floor for enhanced visual depth.
* **Responsive Design**: The 3D scene and camera automatically adjust to fit the browser's window size.

---

## Technology Stack

* **Three.js**: A cross-browser JavaScript library used to create and display the 3D scene and objects.
* **Tween.js**: A lightweight animation engine used to create smooth transitions for camera and object movements.
* **HTML5 & CSS3**: Used for the core structure of the page and styling of text overlays.
* **JavaScript (ES Modules)**: The core language for application logic and interactivity.

---

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You will need [Node.js](https://nodejs.org/) and the npm package manager installed on your system.

### Installation

1.  **Clone the repository** to your local machine:
    ```sh
    git clone (https://github.com/abhaydesu/virtual-gallery.git)
    ```

2.  **Navigate into the project directory**:
    ```sh
    cd virtual-gallery
    ```

3.  **Install the required dependencies**:
    ```sh
    npm install
    ```

4.  **Launch the development server**:
    This project uses ES modules and should be run with a local development server. A simple option like Vite is recommended.
    ```sh
    npm run dev
    ```
    Once the server is running, you can view the project in your browser at the local URL provided (e.g., `http://localhost:5173`).

---

## Customization

The gallery's collection can be easily customized.

1.  **Add Image Files**: Place your artwork images (e.g., `.jpg`, `.png`) into the `public/` directory.

2.  **Update Data Arrays**: Open `main.js` and modify the `images`, `titles`, and `artists` arrays. Ensure that the items in each array correspond by index.

    ```javascript
    // /main.js

    const images = [
      'my-artwork-1.jpg',
      'my-artwork-2.jpg',
    ];

    const titles = [
      'Title of First Artwork',
      'Title of Second Artwork',
    ];

    const artists = [
      'Name of First Artist',
      'Name of Second Artist',
    ];
    ```

The gallery will automatically rebuild with your custom collection upon saving the changes.