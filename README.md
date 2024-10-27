# Platzi Ecommerce in Angular 17

This project is an e-commerce application built in Angular 17 [Angular CLI](https://github.com/angular/angular-cli) version 17.3.10, using the latest technologies, including Signals and HTTP requests to a simulated API. The application allows users to browse through different categories, filter products, view product details, and dynamically add products to a shopping cart.

## Technologies Used

	•	Angular 17: JavaScript framework for building web applications.
	•	Angular Signals: New feature for managing reactive state.
	•	Angular HTTPClient: For making HTTP requests to a simulated API.
	•	TypeScript: Programming language for front-end development.
	•	RxJS: Reactive library to handle data streams.

## Features

	1.	Product Catalog: Product list that can be filtered by categories using URL parameters.
	2.	Result Filtering: Products are dynamically filtered using URL parameters, making it easy to access specific categories directly.
	3.	Product Details: Each product has a detail page accessible via a specific route.
	4.	Shopping Cart: Ability to add products to a shopping cart dynamically in real-time.
	5.	Simulated API: HTTP calls to a simulated API to retrieve products, categories, and product details.

## Project Setup

### Prerequisites

	•	Node.js (v18 or higher)
	•	Angular CLI (v17 or higher)

### Installation

Clone the repository and install the dependencies:
``` bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
npm install
````

## Installation of Tailwind CSS

To incorporate Tailwind CSS into your Angular application, follow these steps:

### 1. Install Tailwind CSS
Go to the official website [Tailwindcss](https://tailwindcss.com/) and follown the installation instructions.
Run the following command to install Tailwind CSS along with PostCSS and Autoprefixer:

```bash
npm install -D tailwindcss postcss autoprefixer
```

### 2. Install Tailwind Prettier
Install Prettier and the Tailwind CSS plugin to ensure consistent styling across your project:
```bash
npm install -D prettier prettier-plugin-tailwindcss
```

### 3. Include Tailwind Styles
Add the Tailwind styles to your ./src/styles.css file by including the following lines:
```css
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
```

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

`Access the app at http://localhost:4200.`

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
