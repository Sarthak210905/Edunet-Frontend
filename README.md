Zayka Express

Root Directory

index.html: Main HTML file.
package.json: Project dependencies and scripts.
vite.config.js: Vite configuration file.
vercel.json: Vercel configuration for rewrites.
.gitignore: Git ignore file.
src Directory

main.jsx: Entry point for the React application.
App.jsx: Main application component with routes.
index.css: Global CSS file.
App.css: Main CSS file for styling components.
Components Directory (src/suby/components)

NavBar.jsx: Navigation bar component.
SideBar.jsx: Sidebar component with navigation links.
TopBar.jsx: Top bar component with search and login/signup.
Welcome.jsx: Welcome component for vendors.
ItemsDisplay.jsx: Component to display items.
Chains.jsx: Component to display restaurant chains.
FirmCollections.jsx: Component to display firm collections.
Offers.jsx: Component to display offers.
NotFound.jsx: Component for 404 error page.
ProductMenu.jsx: Component to display product menu.
Forms Directory (src/suby/components/forms)
AddFirm.jsx: Form to add a new firm.
AddProduct.jsx: Form to add a new product.
Login.jsx: Login form component.
Register.jsx: Register form component.
Pages Directory (src/suby/pages)

LandingPage.jsx: Main landing page component.
LandingPage1.jsx: Alternative landing page component.
Data Directory (src/suby/data.js)

data.js: Contains item data for display.
Key Features
Routing

Uses react-router-dom for client-side routing.
Routes defined in App.jsx:
/: LandingPage component.
/dashboard: LandingPage1 component.
/products/:firmId/:firmName: ProductMenu component.
Styling

Global styles in index.css.
Component-specific styles in App.css.
Components

NavBar: Displays the navigation bar with login/signup options.
SideBar: Sidebar with navigation links to different sections.
TopBar: Top bar with search functionality.
Welcome: Displays a welcome message for vendors.
ItemsDisplay: Displays a list of items.
Chains: Displays top restaurant chains.
FirmCollections: Displays collections of firms.
Offers: Displays available offers.
NotFound: 404 error page.
ProductMenu: Displays a menu of products.
Forms

AddFirm: Form to add a new firm.
AddProduct: Form to add a new product.
Login: Form for vendor login.
Register: Form for vendor registration.
Configuration
Vite: Used for building and serving the application.
Vercel: Configuration for deployment on Vercel.
Dependencies
React: JavaScript library for building user interfaces.
React Router: Library for routing in React applications.
Lucide React: Icon library for React.
React Loader Spinner: Library for loading spinners.
