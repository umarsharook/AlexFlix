# Netflix Clone (Frontend Only)

Netflix Clone is a front-end project that replicates the UI/UX design of Netflix’s homepage using only HTML, CSS, and JavaScript—without any frameworks or back-end logic. The purpose of this project is to demonstrate mastery over:

Responsive layouts using CSS Flexbox/Grid

DOM manipulation using JavaScript

Data-driven UI rendering

Interactive elements like hover effects and click handlers

The homepage dynamically loads a list of popular movies and series using a hardcoded array of objects in JavaScript. Each movie card features:

A poster image (with fallback if the image is broken)

The movie title and description

A Play button that opens the trailer on YouTube

This project mimics the essential feel of Netflix’s movie browser and can be extended with features like search, category filters, API integration (e.g., TMDB), and user authentication.


## 🌟 Features

- ✅ Movie and series posters arranged in a horizontal scroll
- ✅ Movie title displayed under each poster
- ✅ Hover zoom effect on posters (like Netflix)
- ✅ Responsive design for all screen sizes
- ✅ Play button on each poster — opens trailer in a new YouTube tab
- ✅ Fallback image if poster not found


##  Tech Stack

| Technology     | Purpose                      |
|----------------|------------------------------|
| **HTML5**       | Page structure               |
| **CSS3**        | Styling & responsive design  |
| **JavaScript (Vanilla)** | DOM manipulation, dynamic rendering |


## Folder Structure

Netflix-Clone/
│
├── index.html    
├── style.css       
└── script.js



##  Getting Started

To set up and run this project locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/umarsharook/AlexFlix-clone.git
````

2. **Navigate into the project folder**:

   ```bash
   cd netflix-clone
   ```

3. **Open the app**:

   * Open `index.html` with your browser
   * Or use **Live Server** in Visual Studio Code for auto reload

---

## How It Works

* All movie data (title, poster image, trailer URL) is stored in the `script.js` file as a JavaScript array.
* For each movie, the DOM dynamically creates:

  * An image (with hover zoom),
  * A title below the poster,
  * A "Play" button that opens the trailer on YouTube.
* If the image link fails, a default placeholder image is displayed.

---

## 🧩 Improvements to Make

Here are some ideas for extending the project:

* [ ] Add filter/search bar for movies
* [ ] Create multiple rows (Trending, Originals, etc.)
* [ ] Use real-time movie data using TMDB API
* [ ] Add login/signup UI page
* [ ] Implement backend using Firebase or Node.js




## License

This project is licensed under the MIT License.
Feel free to use, modify, and distribute it.
