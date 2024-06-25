# PeakBuy

Modern E-commerce Platform with MERN Stack

## Key Features:

### User Authentication and Authorization:
- Signing up and logging in with email along with email verification.
- Forgot and reset password features for enhanced user account security.
- Firebase Authentication for secure user authentication, including login with Google.
- JSON Web Tokens (JWT) for managing user sessions and authorization.

### Category and Product Management:
- Allows administrators to create, update, and delete product categories.
- Product management includes features such as uploading images, setting descriptions, pricing, and managing inventory levels.
- Product variations such as color and size, allowing for detailed product specifications.

### Search and Filtering:
- Search functionality based on keywords.
- Sorting options such as sorting by time, popularity, price, and name to customize the product display.
- Enables filtering by category, price range, rating, and other relevant criteria to refine search results.

### Shopping Cart and Wishlist:
- The shopping cart allows users to manage items, update quantities, and remove products before checkout.
- Users can create wishlists to save favorite products for future reference and easy access.

### Order Types and Payment:
- Supports multiple order types including cash on delivery (COD) and online payment.
- Online payment with Stripe for secure and seamless transaction processing.
- Utilizes web hooks to handle events such as successful payment confirmation and update order statuses accordingly.

### Invoice Generation:
- Generates invoices for completed orders, providing users with a detailed summary of their purchases.
- PDF format for easy viewing, printing, and sharing.

### Discount and Voucher Coupon Management:
- Discounts can be specified as flat-rate or percentage-based, offering flexibility in promotional strategies.
- Discounts can be applied to individual products or entire categories, allowing for targeted promotions.
- Voucher coupons can be created with conditions such as expiry date, minimum purchase limit, and discount type.

### Data Visualization:
- Data visualization with charts and graphs representing key metrics such as sales, orders.
- Allows customization and filtering options to view data over specific periods such as the last 7 days, last 30 days, etc.

### Verified Purchase and Review:
- Allows users to leave reviews and ratings for products they have purchased, contributing to the overall product rating and feedback system.

### SEO Optimization:
- Implements React-Helmet to manage SEO metadata dynamically for each page.
- Optimizes metadata such as title tags, meta descriptions to improve search engine visibility.
- Mobile responsiveness and fast page loading times to meet search engine ranking criteria and enhance user experience.

### Notifications:
- Integrates React Toastify for displaying notifications to users.
- Displays notifications for various events such as successful login, successful purchase, order updates, etc.

### Dark and Light Mode:
- Automatically detects the user's system theme preference (light or dark mode).
- Provides users with a manual toggle option to switch between light and dark modes regardless of the system theme.

## Tech Stack:
- **Frontend:** React.js, Tailwind CSS, Zustand, TanStack Query, Axios, React Helmet, React Toastify.
- **Backend:** Node.js, Express.js, MongoDB, Mongoose, Firebase Authentication, JSON Web Tokens (JWT), Nodemailer.
- **Additional Services:** Cloudinary (for image storage), Stripe (for payment processing).

## Live Demo:
- [https://peak-buy.onrender.com/](https://peakbuy.luminatech.agency/)

