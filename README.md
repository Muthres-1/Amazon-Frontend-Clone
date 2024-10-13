# Amazon-Frontend-Clone

This project is an Amazon-like clone website that simulates a basic e-commerce layout using HTML and CSS.

## Project Structure

index.html # Main HTML file
style.css # CSS file for styling
assets/ # Folder for images (like amazon_logo.png, hero_image.jpg, etc.)


## Technologies Used

- HTML5
- CSS3
- Font Awesome Icons
- Google Fonts

## Setup Instructions

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-repo/amazon-clone.git
    ```
   
2. **Navigate to the project directory**:
    ```bash
    cd amazon-clone
    ```

3. **Open the project**:
    - You can open the `index.html` file in your preferred web browser to see the website.

## External Resources

- **Font Awesome**: Icons are imported using Font Awesome. You can change or add icons from [Font Awesome](https://fontawesome.com/).
- **Google Fonts**: The project uses `Arial, Helvetica, sans-serif` as the default fonts. You can replace or add fonts by importing from Google Fonts.

## Project Layout

### Navbar Section

- **Logo**: Located in the left corner, using the `amazon_logo.png` image.
- **Address**: A delivery location option with an icon.
- **Search Bar**: A search input with a dropdown for selecting search categories.
- **Sign In**: A link to sign in and view account lists.
- **Orders**: Links for returns and orders.
- **Cart**: A cart icon linked to the shopping cart.

### Main Section

- **Hero Image**: A background image displaying an Amazon-like banner.
- **Message Box**: A notification asking if the user wants to visit the Amazon India website.

### Shop Section

- A four-column layout showcasing different product categories like fashion, personal care, and popular items.

### Footer Section

- Links to various sections such as Careers, Blog, Investor Relations, and more.
- **Back-to-Top** button at the top of the footer to scroll back to the top of the page.

### Lower Footer

- Language and currency selection options for users.

## How to Customize

### Change the Logo

- Update the `logo` class background image in the CSS file:
    ```css
    .logo {
        background-image: url('path-to-your-logo.png');
    }
    ```

### Change the Hero Image

- Replace `hero_image.jpg` in the `.main` section of the CSS:
    ```css
    .main {
        background-image: url('your-hero-image.jpg');
    }
    ```

### Modify the Footer Links

- You can change the text and links in the footer by modifying the `<footer>` section in the `index.html` file.

## License

This project is open-source and free to use under the MIT license. Feel free to clone and modify it for personal or educational purposes.

