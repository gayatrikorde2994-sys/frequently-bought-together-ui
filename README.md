# frequently-bought-together-ui
Frontend interface for Amazon's 'Frequently Bought Together' recommendation feature. Implements UI widgets to display complementary product bundles and drive upsell conversions. Includes bundled-to-cart functionality, collaborative filtering visualization, and mobile-responsive layout for optimized e-commerce product pages.
# Amazon UI Clone: Frequently Bought Together
https://gayatrikorde2994-sys.github.io/frequently-bought-together-ui/
# Amazon UI Clone: Frequently Bought Together

## 📋 Assignment Context
This project was developed as a technical exercise to recreate a specific e-commerce user interface component. The primary goal was to solve the challenge of maintaining a multi-column horizontal layout where images and their corresponding metadata (titles/prices) remain perfectly synchronized across a single row.

## 🔍 Overview
The "Frequently Bought Together" component mimics the Amazon bundle purchase interface. It features:
* **Horizontal Alignment:** A main flex-row that keeps product units and the checkout summary side-by-side.
* **Vertical Synchronization:** Nested flex-columns ensuring product titles and prices stay anchored exactly below their respective images.
* **Checkout Logic:** A dedicated action area with the signature Amazon yellow button and pricing summary.

## 💻 Languages Used
* **HTML5:** Used for semantic structuring of product cards and layout containers.
* **CSS3:** Utilized for Flexbox implementation, specifically `flex-direction: row` for the main layout and `flex-direction: column` for internal product alignment.

## 👤 About the Author
    Name: Gayatri Korde
    Branch : VLSI
    Roll no.:09 
    Subject : MDM- WEB DEVELOPMENT

I am a developer focused on mastering modern CSS layout techniques. My work emphasizes clean, readable code and high-fidelity UI recreations to improve user experience and interface consistency.

## 📜 Declaration
I hereby declare that this implementation is my original work. All layout logic, styling, and structural components were developed from scratch through visual analysis of e-commerce design patterns. No external JavaScript was used, prioritizing a pure CSS solution for layout stability.

## 🏁 Conclusion
This project successfully demonstrates the power of **Nested Flexbox**. By isolating each product into its own vertical unit before placing them into a horizontal row, we avoid the common issue of misaligned text. This modular approach ensures that even as content varies in length, the structural integrity of the horizontal row remains intact.
