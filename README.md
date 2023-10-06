#Folder Structure Overview :

The architecture of the project is divided into several folders:

  src: This folder contains all the source code files for the application.

  src/public: Contains static assets that are publicly accessible by the client-side code.

  scr/assets: Contains all static images that are used across the application.

  src/components: This folder contains all components such as Navbar, Footer, etc. Each component contains its JSX, styling, and other related files.

  src/components/shared: This folder contains components that are commonly used - Categories, FeaturedProducts & PageHeader.

  src/contexts: This folder has two components - ProductsContext and CartContext. This is where the state is managed and shared to other components.

  src/pages: This folder contains all the pages that the user can navigate to - Home, Products, Abput, etc.

  src/styles: This folder contains all Scss partials - _base.scss, _variables.scss, etc.
