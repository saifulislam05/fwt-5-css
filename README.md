# Amazon Home Page Clone W-T-5


## Project Description
The "Amazon Home Page Clone" is a web page project that replicates the layout and design of the Amazon homepage. It features a header section with navigation links, a search bar, and user account information. The project also includes a banner section showcasing various links, and a product category section with responsive product cards.

## HTML Structure

### Header Section:

- `<header>`: The header section of the web page.
  - `<nav class="navbar">`: Navigation bar.
    - `<div class="logo">`: Amazon logo.
    - `<div class="location">`: Delivery location and country.
    - `<div class="search-bar">`: Search bar with category dropdown.
    - `<div class="sign-in">`: User sign-in information.
    - `<div class="returns">`: Returns and orders information.
    - `<div class="cart">`: Shopping cart.

### Banner Section:

- `<section class="banner">`: Banner section with links.
  - `<div class="content">`: Content within the banner.
    - `<div class="panel">`: Menu panel.
    - `<ul class="links">`: Links section.
    - `<div class="deals">`: Deals link.

### Hero Section:

- `<section class="hero">`: Hero section (empty for now).

### Product Category Section:

- `<section class="product-category">`: Product category section.
  - `<div class="container product-category-wrapper">`: Wrapper for product categories.
    - `<div class="single-product-category">`: Individual product category card.
      - `<h3 class="category-name">`: Category name.
      - `<img src="category-image.jpg" alt="Category">`: Category image.
      - `<a href="#">Shop now</a>`: Shop now link.

## CSS Styles

### Global Styles (`*`)
- `margin: 0;`: Resets margin for all elements.
- `padding: 0;`: Resets padding for all elements.
- `box-sizing: border-box;`: Ensures elements include padding and borders in their total width.
- `font-family: "Open Sans", sans-serif;`: Specifies the default font for the entire document.

### HTML (`html`)
- `scroll-behavior: smooth;`: Adds smooth scrolling behavior to anchor links within the HTML document.

### Container (`div.container`)
- `.container`:
  - `width: 100%;`: Makes the container span the entire width.
  - `max-width: 1200px;`: Sets the maximum width of the container to 1200 pixels.
  - `margin: 0 auto;`: Centers the container horizontally on the page.

### Links (`a`)
- `text-decoration: none;`: Removes underlines from links.
- `color: #fff;`: Sets the default text color for links.
- `color: #ddd;` (on hover): Changes the text color of links when hovered.

### Header Section (`header`)
- `background: #0f1111;`: Sets the background color of the header section.

### Navbar (`nav.navbar`)
- `.navbar`:
  - `width: 100%;`: Sets the navbar's width to 100%.
  - `height: 60px;`: Defines the height of the navbar.
  - `display: flex;`: Arranges navbar items in a horizontal line.
  - `justify-content: space-between;`: Separates items with space.
  - `align-items: center;`: Vertically centers items.
  - `color: #ffffff;`: Sets the text color in the navbar.
  - `cursor: pointer;`: Changes the cursor to a pointer.

- `.navbar .logo img`:
  - `width: 128px;`: Sets the logo's width.
  - `margin-top: 10px;`: Adds top margin to the logo.

- `.location .deliver`:
  - `color: #ccc;`: Styles the delivery text with a light gray color.
  - `margin-left: 20px;`: Adds left margin.
  - `font-size: 0.75rem;`: Sets the font size for the delivery text.

- `.location .map-icon`:
  - `display: flex;`: Arranges items in a row.
  - `align-items: center;`: Vertically centers items.

- `.search-bar`:
  - `display: flex;`: Arranges items in a row.
  - `justify-content: space-evenly;`: Distributes space evenly.
  - `max-width: 620px;`: Sets the maximum width.
  - `width: 100%;`: Spans the entire width.
  - `height: 40px;`: Defines the height.
  - `border-radius: 4px;`: Rounds the corners.

- `.search-select`:
  - `background: #f3f3f3;`: Sets the background color.
  - `width: 50px;`: Defines the width.
  - `text-align: center;`: Centers text horizontally.
  - `border: none;`: Removes the border.
  - `border-radius: 4px 0 0 4px;`: Rounds the left corners.

- `.search-input`:
  - `max-width: 600px;`: Sets the maximum width.
  - `width: 100%;`: Spans the entire width.
  - `border: none;`: Removes the border.
  - `outline: none;`: Removes the outline.
  - `padding-left: 10px;`: Adds left padding.
  - `font-size: 1rem;`: Sets the font size.

- `.search-icon`:
  - `max-width: 45px;`: Sets the maximum width.
  - `width: 100%;`: Spans the entire width.
  - `display: flex;`: Arranges items in a row.
  - `justify-content: center;`: Centers content horizontally.
  - `align-items: center;`: Centers content vertically.
  - `font-size: 1.2rem;`: Sets the font size.
  - `background: #febd68;`: Sets the background color.
  - `color: #000;`: Sets the text color.
  - `cursor: pointer;`: Changes the cursor to a pointer.
  - `border-top-right-radius: 4px;`: Rounds the top-right corner.
  - `border-bottom-right-radius: 4px;`: Rounds the bottom-right corner.

- `.sign-in p, .returns p`:
  - `font-size: .75rem;`: Sets the font size for the "Hello, sign in" and "Returns" text.

- `.sign-in, .returns span`:
  - `font-size: 0.875rem;`: Sets the font size.
  - `font-size: 600;`: Makes the font weight bold.

- `.cart`:
  - `display: flex;`: Arranges items in a row.
  - `align-items: center;`: Centers items vertically.

- `.cart .cart-icon`:
  - `font-size: 2.5rem;`: Sets the font size for the shopping cart icon.

- `.cart p`:
  - `margin-top: 20px;`: Adds top margin.
  - `font-weight: 500;`: Sets the font weight.

### Banner Section (`section.banner`)
- `.banner`:
  - `padding: 10px 0;`: Adds padding to the top and bottom.
  - `background: #222f3d;`: Sets the background color.
  - `font-size: 0.875rem;`: Sets the font size.
  - `color: #fff;`: Sets the text color.

- `.banner .content`:
  - `display: flex;`: Arranges items in a row.
  - `align-items: center;`: Centers items vertically.
  - `justify-content: space-between;`: Separates items with space.

- `.banner .content .panel`:
  - `display: flex;`: Arranges items in a row.
  - `align-items: center;`: Centers items vertically.
  - `gap: 5px;`: Sets the gap between items.
  - `cursor: pointer;`: Changes the cursor to a pointer.

- `.links`:
  - `display: flex;`: Arranges items in a row.
  - `align-items: center;`: Centers items vertically.
  - `list-style: none;`: Removes list bullets.
  - `gap: 15px;`: Sets the gap between items.
  - `flex-grow: 1;`: Allows items to grow within the available space.
  - `margin-left: 15px;`: Adds left margin.

- `.panel span`:
  - `margin-right: 7px;`: Adds right margin.

- `.deals a`:
  - `font-size: 0.9rem;`: Sets the font size.
  - `font-weight: 500;`: Sets the font weight.
  - `white-space: nowrap;`: Prevents text from wrapping.

### Hero Section (`section.hero`)
- `.hero`:
  - `height: 400px;`: Sets the height of the hero section.
  - `background-image: url("images/hero-bg.jpg");`: Sets the background image.
  - `background-position: center;`: Centers the background image.
  - `background-size: cover;`: Makes the background image cover the entire section.

### Product Category Section (`section.product-category`)
- `.product-category`:
  - `background-color: #f3f3f3;`: Sets the background color.
  - `padding: 50px 0;`: Adds padding to the top and bottom.
  - `display: flex;`: Arranges items in a column.
  - `align-items: center;`: Centers items vertically.
  - `flex-direction: column;`: Stacks items vertically.

- `.product-category-wrapper`:
  - `display: grid;`: Arranges items in a grid layout.
  - `grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));`: Defines the grid columns.
  - `gap: 40px;`: Sets the gap between grid items.
  - `overflow: hidden;`: Hides overflowing content.

- `.single-product-category`:
  - `padding: 30px;`: Adds padding around each product category.
  - `background-color: #fff;`: Sets the background color of product category boxes.
  - `cursor: pointer;`: Changes the cursor to a pointer.
  - `display: flex;`: Arranges items in a column.
  - `flex-direction: column;`: Stacks items vertically.
  - `white-space: nowrap;`: Prevents text from wrapping.
  - `transition: transform 0.5s ease-in-out;`: Adds a smooth transformation effect.
  - `-webkit-transition: transform 0.5s ease-in-out;`: Adds a smooth transformation effect (for Safari).
  - `-moz-transition: transform 0.5s ease-in-out;`: Adds a smooth transformation effect (for Firefox).
  - `-ms-transition: transform 0.5s ease-in-out;`: Adds a smooth transformation effect (for Microsoft Edge).
  - `-o-transition: transform 0.5s ease-in-out;`: Adds a smooth transformation effect (for Opera).

- `.single-product-category:hover`:
  - `transform: scale(1.05);`: Enlarges the product category box on hover.
  - `-webkit-transform: scale(1.05);`: Enlarges the product category box on hover (for Safari).
  - `-moz-transform: scale(1.05);`: Enlarges the product category box on hover (for Firefox).
  - `-ms-transform: scale(1.05);`: Enlarges the product category box on hover (for Microsoft Edge).
  - `-o-transform: scale(1.05);`: Enlarges the product category box on hover (for Opera).

- `.single-product-category img`:
  - `width: 100%;`: Sets the width of product category images.
  - `height: 280px;`: Sets the height of product category images.
  - `object-fit: cover;`: Makes images cover the entire box.
  - `margin: 10px 0;`: Adds margin around the images.

- `.single-product-category a`:
  - `color: blue;`: Sets the link color for "Shop now."
  - `margin-top: 10px;`: Adds top margin.
  - `font-size: 0.9rem;`: Sets the font size.
  - `display: inline-block;`: Makes links inline-block elements.
  - `font-weight: 500;`: Sets the font weight.

- `.single-product-category a:hover`:
  - `color: #c7511f;`: Changes the link color on hover.
  - `text-decoration: underline;`: Adds an underline to links on hover.

### Footer Section (`footer`)
- `background: #232f3e;`: Sets the background color of the footer.
- `color: #ffffff;`: Sets the text color of the footer.

- `.back-to-top`:
  - `display: flex;`: Arranges items in a row.
  - `font-size: 0.875rem;`: Sets the font size for "Back to top" link.
  - `font-weight: 600;`: Sets the font weight.
  - `height: 60px;`: Defines the height of the link.
  - `background: #37475a;`: Sets the background color.
  - `justify-content: center;`: Centers content horizontally.
  - `align-items: center;`: Centers content vertically.

- `.footer-items-wrapper`:
  - `display: flex;`: Arranges items in a row.
  - `justify-content: space-between;`: Separates items with space.
  - `padding: 20px 0 18px 0;`: Adds padding.

- `.footer-items-wrapper ul`:
  - `list-style: none;`: Removes list bullets.

- `.footer-items-wrapper ul h3`:
  - `margin-bottom: 10px;`: Adds bottom margin.
  - `font-size: 1rem;`: Sets the font size for section headings.
  - `font-weight: 500;`: Sets the font weight.

- `.footer-items-wrapper ul li a`:
  - `color: #ddd;`: Sets the text color for links in the footer.
  - `font-size: 0.875rem;`: Sets the font size for links.

- `.footer-items-wrapper ul li a:hover`:
  - `text-decoration: underline;`: Underlines links on hover.
