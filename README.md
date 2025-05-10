# Rolling Greens Dispensary

A web-based dispensary application where customers can browse cannabis products, leave ratings and reviews, and manage their accounts. Built with PHP, MySQL, and MAMP/XAMPP, Rolling Greens provides a simple CRUD interface for both products and customer feedback.

---

## Features Implemented

- **User Authentication**  
  - Sign up with email & password  
  - Login / logout  
  - Session-based access control

- **Product Catalog (Read)**  
  - Dashboard listing all products from the database  
  - Individual product pages with image, description, price, etc.

- **Review System (Create & Delete)**  
  - Authenticated users can submit a star rating (1–5) and comment  
  - Users can delete their own reviews

- **Profile Management (Update)**  
  - Users can edit their display name and password

- **Additional Functionality**  
  - Responsive table layouts for product listings  
  - Basic search by product name or category

---

## Features Not Yet Implemented

- Shopping cart and checkout workflow  
- Payment-gateway integration (e.g., Stripe, PayPal)  
- Product filtering & sorting (price, strain type, THC/CBD levels)  
- Admin dashboard for managing users & products  
- User roles (admin vs. customer)  
- Email verification & password-reset flows  
- Mobile-first responsive design

---

## Known Bugs & Limitations

- **Styling mismatches**  
  Some pages (e.g., product grid, forms) don’t fully match the Figma mockup—colors, margins, and fonts need fine-tuning.

- **Image handling**  
  Product images may appear overly zoomed or cropped; no thumbnail generation yet.

- **Review deletion refresh**  
  After deleting a review, the page doesn’t always update immediately; user must manually refresh.

- **Form validation**  
  Client-side checks are minimal, and error messages can be unclear when input is invalid.

- **Security considerations**  
  - No rate-limiting or CAPTCHA on signup/review forms  
  - Limited sanitization—parameterized queries help, but further hardening is needed

---

## Credits

- **Developer:** Osita Odunze  
- **Technologies & Libraries:**  
  - PHP 7+  
  - MySQL / MariaDB  
  - MAMP (macOS) / XAMPP (Windows)  
  - [Bootstrap](https://getbootstrap.com/) for layout & components  
  - [Font Awesome](https://fontawesome.com/) icons  

- **Design:** Figma mockups by Osita Odunze  
- **Inspiration:** Various open-source e-commerce and review-platform tutorials

Feel free to open an issue or submit a pull request if you’d like to contribute enhancements or fixes!
