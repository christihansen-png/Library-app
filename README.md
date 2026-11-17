# Library

**An online bookstore built with React, with a working shopping cart and price sorting.**

**Live site:** [library-app-thal.vercel.app](https://library-app-thal.vercel.app/)

---

## About

Library is a sample bookstore website. Shoppers can browse books, sort them, open a page for each book and build a cart that keeps track of quantities and totals.

---

## Features

**Home page**
- Landing section with a big headline and a "Browse books" button
- Highlights section explaining why to shop here
- Featured books and discounted books sections

**Browsing books**
- Page with every book
- Sort by price (low to high or high to low) or by rating
- Star ratings and sale prices shown on each book
- Each book has its own page with details and recommended 5-star books

**Shopping cart**
- "Add to cart" turns into "Checkout" once a book is in the cart
- Change quantities or remove books
- Subtotal, tax and total update right away
- Cart count in the nav bar stays up to date on every page
- Friendly empty-cart message with a button back to the books

---

## Built With

- React
- React Router (home, books, book info and cart pages)
- Hooks: `useState`, `useEffect`
- Reusable components (Book, Price, Rating, Highlight)
- Font Awesome icons
- Hosted on Vercel

---

## What I Learned

- Breaking a page into small, reusable components
- Keeping the cart in one place (`App`) and passing it down with props
- Updating state without changing the original array (`...spread`, `.map()`, `.filter()`)
- Sorting a copy of an array with `.slice().sort()`
- Using routes and URL IDs to show a different page for each book

---

## Author

**Christi Hansen Moore** | Beautiful You Web Studio
[beautifulyouwebstudio.com](https://beautifulyouwebstudio.com) | [Portfolio](https://christihansen-png.github.io/eportfolio.christi/) | [GitHub](https://github.com/christihansen-png)
