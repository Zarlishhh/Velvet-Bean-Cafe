Velvet Bean Cafe

A frontend web application for a modern cafe, built with HTML, CSS, and JavaScript. This project focuses heavily on implementing a seamless client-side e-commerce shopping experience—specifically featuring a dynamic Add to Cart system and an Instant Buy workflow using browser local storage.

🔹Features

- Multi-Category Menu: Interactive catalog pages for Pizzas, Pastas, Burgers, Beverages, and Desserts.
- Add to Cart Functionality: 
- Adds selected food items dynamically with item name, pricing, images, and quantities.
- Persists data using "localStorage" so items remain saved across page navigations.
- Automatically handles item quantity aggregation (increments count if the same item is added again).
  
🔹Technologies Used
-HTML: For page structure and semantic markup.
-CSS: For layout design, custom styling, hover effects, and typography.
-JavaScript : For frontend logic, cart management, and interactive UI behaviors

🔹Instant Buy ("Buy Now") Workflow: 
  - Bypasses the standard cart for quick checkouts.
  - Directly stores the selected product into a separate session state and redirects the user straight to the checkout view with a dedicated mode query parameter.

🔹Interactive Checkout & Cart Management:
- Tabbed interface allowing users to toggle between viewing standard "Cart Items" and "Instant Buy" summaries.
- Built-in live quantity modifiers (`+` / `-` buttons) that instantly update sub-totals and totals.
- Clean local storage cleanup upon order placement.


1. Clone or download this repository to your local machine:
   ```bash
   git clone [https://github.com/zarlish-tahir/velvet-bean-cafe.git](https://github.com/zarlish-tahir/velvet-bean-cafe.git)
