# Google Clone - CS50 Web Development Project 0

This project is a simple clone of Google's homepage, Google Images, and Google Advanced Search. It was built as part of **Project 0** in Harvard's CS50 Web Development course. The goal of this project is to practice HTML and CSS by replicating the functionality and design of Google's search pages.

---

## Features

1. **Google Search**: A replica of Google's homepage with a search bar and buttons for "Google Search" and "I'm Feeling Lucky."
2. **Google Images**: A page that mimics Google Images, allowing users to search for images.
3. **Google Advanced Search**: A page that replicates Google's Advanced Search functionality, allowing users to refine their search queries.

---

## Files

### HTML Files
1. **`index.html`**: The main Google homepage.
2. **`pages/images.html`**: The Google Images page.
3. **`pages/advanced-search.html`**: The Google Advanced Search page.

### CSS Files
1. **`style/index.css`**: Styles for the Google homepage and Google Images page.
2. **`style/advanced-search.css`**: Styles for the Google Advanced Search page.

### Assets
- **`assets/google_image.png`**: The Google logo used in the project.

---

## How to Use

1. **Google Search**:
   - Open `index.html` in your browser.
   - Enter a search query in the input field and click "Google Search" to perform a search on Google.
   - Alternatively, click "I'm Feeling Lucky" to be redirected directly to the first result of your query.

2. **Google Images**:
   - Open `pages/images.html` in your browser.
   - Enter a search query in the input field and click "Google Search" to search for images on Google.

3. **Google Advanced Search**:
   - Open `pages/advanced-search.html` in your browser.
   - Use the advanced search fields to refine your search query:
     - **All these words**: Pages containing all the words you enter.
     - **This exact word or phrase**: Pages containing the exact phrase you enter.
     - **Any of these words**: Pages containing any of the words you enter.
     - **None of these words**: Pages excluding the words you enter.
   - Click "Advanced Search" to perform the search.

---

## Styling Details

### `index.css`
- **Global Styles**: Resets margins, padding, and box-sizing for all elements.
- **Body**: Centers content vertically and horizontally, with a clean white background.
- **Navigation**: Buttons are styled to resemble Google's navigation links, with hover effects and proper spacing.
- **Search Bar**: The search input field has a rounded design with a subtle shadow effect on hover and focus.
- **Buttons**: The "Google Search" and "I'm Feeling Lucky" buttons are styled with a light background and rounded edges, matching Google's design.

### `advanced-search.css`
- **Global Styles**: Similar to `index.css`, but with left-aligned content for the advanced search form.
- **Form Layout**: The form uses a flexbox layout to align labels and input fields neatly.
- **Input Fields**: Input fields have a clean border and subtle hover/focus effects.
- **Submit Button**: The "Advanced Search" button is styled with a blue background and white text, matching Google's design.

---

## Setup Instructions

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/google-clone.git
   ```
2. Navigate to the project director:
   ```bash
    cd google-clone
   ```
3. Open any of the HTML files in your borwser to view the project:
- `index.html`: for the Google homepage.
- `pages/images.html`: for Google Images.
- `pages/advanced-search.html`: for Google Advanced Search.

---

## Technologies Used
- **HTML**: For structring the web pages
- **CSS**: For styling the web pages and making them visually similar to Google's design

---

## Acknowledgments

- This project was created as Project 0 in Harvard's CS50 Web Development course.
- Special thanks to the CS50 team for providing the resources and guidance to complete this project

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.
