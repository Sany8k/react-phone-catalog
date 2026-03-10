# React Typescript Phone catalog

Nice Gadgets is a responsive e-commerce web application for an electronics store. 

It features a dynamic product catalog with sorting and filtering options, an interactive promotional slider, and detailed individual product pages. The application uses dynamic routing and fetches data from a local mock API to simulate a real-world shopping experience.

## Live Demo

Experience the live website: [Phone catalog demo](https://sany8k.github.io/react-phone-catalog/)

## Design Reference

[Design Reference](https://www.figma.com/file/T5ttF21UnT6RRmCQQaZc6L/Phone-catalog-(V2)-Original)

## Technologies Used

**Core**
* React (v18.3.1) - UI framework
* TypeScript (v5.2.2) - Type safety
* Sass (v1.77.8) - Styling

**UI/UX**
* React Router (v6.25.1) - Navigation
* Swiper (v12.1.2) - Image galleries
* React Paginate (v8.3.0) - Pagination

**Development & Deployment**

* Vite (v5.3.1) - Build tool
* ESLint (v8.57.0) - Code quality
* Github Pages (v6.1.1) - Hosting and deployment

## Getting Started

1. Clone the repository:
   
```bash
git clone https://github.com/Sany8k/react-phone-catalog.git
cd react-phone-catalog
```

2. Install dependencies:

```bash
npm install
# or
yarn install
```

3. Run the project locally:

```bash
npm start
# or
yarn start
```

## Features

* Responsive Design: Optimized for different screen sizes and devices, responses on width 320px, 640px, 1200px, 1440px,
* Navigation react-router-don library is used in the application to enable navigation between multiple pages, and URL-based search parameters saved when navigating
* Favorites & Cart: adding products to favorites or shopping cart, with total price calculation,
* Sorting: Sort products based on criterias: year, price, alphabeticaly.
* Pagination: Navigate through large lists of products, opportunity to choose number of items per page, and number of pages depends on this.
* Sticky Header: Keeps the header visible as you scroll.
* Scroll to Top Button: Easily return to the top of the page.
* Loader: Indicates loading status for a better user experience.



