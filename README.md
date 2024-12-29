
# Task Assignment from Programming Hero

We are thrilled to assess your skills and passion for technology through this job task.  

### **Important Details:**  
- **Task Deadline:** January 8, 2025  
- **Submission Email:** [jhankar.mahbub145@gmail.com](mailto:jhankar.mahbub145@gmail.com)  
- **Result Announcement Date:** January 16, 2025  

We look forward to seeing your creativity and expertise in action!
Here’s a detailed breakdown of your Free Fire Diamond and PUBG UC selling website project with **client-side** and **server-side** requirements, organized by components and routes. I'll also suggest a fancy name: 

**Website Name:** **GameVault BD**

---

### **Client-Side (Frontend) Requirements**

**1. Landing Page (Homepage)**
   - **Component:** `LandingPage`
   - **Route:** `/`
   - **Features:**
     - Hero section with attractive banner images.
     - Highlights of services (Free Fire Diamonds and PUBG UC).
     - Call-to-action (CTA) buttons for registration and product browsing.
     - Testimonials and trust badges (e.g., "Trusted by 10,000+ users").
   - **Technology:** React.js with Tailwind CSS for styling.

---

**2. Product Listing Page**
   - **Component:** `ProductList`
   - **Route:** `/products`
   - **Features:**
     - Display packages for Free Fire Diamonds and PUBG UC.
     - Filters by game, package size, and price range.
     - Pagination for browsing all packages.
   - **Technology:** React.js, Axios for API calls.

---

**3. Product Details Page**
   - **Component:** `ProductDetails`
   - **Route:** `/products/:productId`
   - **Features:**
     - Detailed information about the selected package.
     - Input field for game ID (for account-specific top-ups).
     - "Add to Cart" button.
   - **Technology:** React Router for dynamic routing.

---

**4. Cart Page**
   - **Component:** `Cart`
   - **Route:** `/cart`
   - **Features:**
     - List of selected products.
     - Update or remove items from the cart.
     - Display total price and proceed to checkout button.
   - **Technology:** Redux or Context API for cart management.

---

**5. Checkout Page**
   - **Component:** `Checkout`
   - **Route:** `/checkout`
   - **Features:**
     - Input fields for user details and payment method.
     - Option for bKash, Nagad, Rocket, or card payments.
     - Confirmation step before placing the order.
   - **Technology:** Form validation with react-hook-form.

---

**6. Order Confirmation Page**
   - **Component:** `OrderConfirmation`
   - **Route:** `/order-confirmation`
   - **Features:**
     - Thank you message with order ID.
     - Summary of order details.
     - Links to track orders or return to homepage.
   - **Technology:** React.js.

---

**7. User Authentication**
   - **Components:** `Register`, `Login`, `ForgotPassword`
   - **Routes:**
     - `/register`
     - `/login`
     - `/forgot-password`
   - **Features:**
     - User registration with email verification.
     - Login with email/password or social accounts.
     - Forgot password functionality with reset link.
   - **Technology:** Firebase Auth or custom JWT authentication.

---

**8. User Profile**
   - **Component:** `UserProfile`
   - **Route:** `/profile`
   - **Features:**
     - Display user information.
     - Edit profile and update payment methods.
     - View order history.
   - **Technology:** React.js with secure API integration.

---

**9. Admin Dashboard**
   - **Components:** `AdminDashboard`, `ManageProducts`, `ManageOrders`, `ManageUsers`
   - **Routes:**
     - `/admin`
     - `/admin/products`
     - `/admin/orders`
     - `/admin/users`
   - **Features:**
     - Add, edit, or delete products.
     - View and update order statuses.
     - Manage registered users.
   - **Technology:** React.js with protected routes.

---

**10. Support Page**
   - **Component:** `Support`
   - **Route:** `/support`
   - **Features:**
     - FAQs and contact form.
     - Live chat integration.
     - Links to social media support channels.
   - **Technology:** React.js with third-party chat SDK.

---

**11. About Us Page**
   - **Component:** `AboutUs`
   - **Route:** `/about`
   - **Features:**
     - Company story and vision.
     - Meet the team section.
     - Social proof (e.g., milestones, customer counts).
   - **Technology:** React.js.

---

### **Server-Side (Backend) Requirements**

**1. User Management**
   - **Routes:**
     - `POST /api/register` - User registration.
     - `POST /api/login` - User login.
     - `POST /api/forgot-password` - Handle password reset.
     - `GET /api/profile` - Fetch user profile.
   - **Features:** JWT-based authentication, email verification.

---

**2. Product Management**
   - **Routes:**
     - `GET /api/products` - Get all products.
     - `GET /api/products/:id` - Get product by ID.
     - `POST /api/products` - Add a new product (admin only).
     - `PUT /api/products/:id` - Edit product (admin only).
     - `DELETE /api/products/:id` - Delete product (admin only).
   - **Features:** Role-based authorization.

---

**3. Cart Management**
   - **Routes:**
     - `POST /api/cart` - Add item to cart.
     - `GET /api/cart` - Get cart items.
     - `PUT /api/cart/:id` - Update cart item.
     - `DELETE /api/cart/:id` - Remove item from cart.
   - **Features:** Associate cart with user sessions.

---

**4. Order Management**
   - **Routes:**
     - `POST /api/orders` - Place a new order.
     - `GET /api/orders` - Get user-specific orders.
     - `GET /api/orders/:id` - Get order by ID.
     - `PUT /api/orders/:id` - Update order status (admin only).
   - **Features:** Integration with payment gateway.

---

**5. Payment Gateway Integration**
   - **Routes:**
     - `POST /api/payments` - Handle payment processing.
   - **Features:** Integrate with bKash, Nagad, Rocket, and Stripe for secure payments.

---

**6. Analytics**
   - **Routes:**
     - `GET /api/admin/sales-report` - Sales analytics.
   - **Features:** Generate reports for revenue, popular products, and user activity.

---

**7. Support System**
   - **Routes:**
     - `POST /api/support` - Submit support tickets.
     - `GET /api/support` - View tickets (admin only).
   - **Features:** Ticket management and live chat integration.

---

**8. Deployment**
   - **Frontend Hosting:** Vercel or Netlify.
   - **Backend Hosting:** Render, Heroku, or AWS.
   - **Database:** MongoDB Atlas.
## Optional But stand out you

To make **GameVault BD** a standout platform in the Bangladeshi market for Free Fire Diamond and PUBG UC sales, here are **additional features** that can enhance its functionality, user experience, and uniqueness:

---

### **Client-Side (Frontend) - Additional Features**

**1. Referral System**
   - **Component:** `ReferralPage`
   - **Route:** `/referral`
   - **Features:**
     - Users receive a unique referral link.
     - Earn rewards (e.g., discount coupons or diamonds) for every successful referral.
     - Display referral status and earned rewards in the user dashboard.

---

**2. Loyalty Rewards Program**
   - **Component:** `RewardsPage`
   - **Route:** `/rewards`
   - **Features:**
     - Reward points for each purchase.
     - Points can be redeemed for discounts or free packages.
     - Tier-based system (e.g., Silver, Gold, Platinum).

---

**3. Flash Sales & Special Offers**
   - **Component:** `FlashSalePage`
   - **Route:** `/flash-sale`
   - **Features:**
     - Limited-time offers displayed prominently.
     - Countdown timers for active deals.
     - "Claim Now" button for instant purchase.

---

**4. Dynamic Blog Section**
   - **Component:** `Blog`
   - **Route:** `/blog`
   - **Features:**
     - Gaming tips, tricks, and news articles.
     - Guides for Free Fire and PUBG gameplay.
     - SEO-optimized blog posts to attract organic traffic.

---

**5. Social Media Integration**
   - **Component:** `SocialLinks`
   - **Placement:** Footer, About Us Page
   - **Features:**
     - Follow us buttons for Facebook, Instagram, and YouTube.
     - Live social feed integration.

---

**6. Dark Mode**
   - **Component:** `ThemeToggle`
   - **Feature:**
     - Toggle between light and dark themes.
     - Persistent theme preference stored in cookies or local storage.

---

**7. Chatbot for Instant Help**
   - **Component:** `ChatBot`
   - **Features:**
     - AI-powered chatbot for FAQs and order queries.
     - Escalate to live chat support if needed.

---

**8. Game ID Validation**
   - **Component:** `GameIdValidator`
   - **Feature:**
     - Verify the entered Game ID to prevent errors in top-up.
     - Real-time validation with the game servers (if possible).

---

**9. Multilingual Support**
   - **Component:** `LanguageSwitcher`
   - **Feature:**
     - Support for Bangla and English languages.
     - Easily switch between languages using a dropdown or toggle.

---

**10. Notifications System**
   - **Component:** `Notifications`
   - **Feature:**
     - Push notifications for order updates, offers, and announcements.
     - Alerts for flash sales or low stock on popular packages.

---

**11. Wishlist**
   - **Component:** `Wishlist`
   - **Route:** `/wishlist`
   - **Features:**
     - Save favorite packages for quick access.
     - Notify users when wishlist items are on sale.

---

**12. Custom Top-Up Orders**
   - **Component:** `CustomOrder`
   - **Route:** `/custom-order`
   - **Features:**
     - Users can specify custom diamond or UC amounts.
     - Dynamic price calculation for custom orders.

---

**13. Order Tracking**
   - **Component:** `OrderTracking`
   - **Route:** `/track-order`
   - **Features:**
     - Track order status with order ID.
     - Display estimated delivery time.

### **Server-Side (Backend) - Additional Features**
**1. Advanced Admin Analytics**
   - **Features:**
     - Real-time sales data visualization (charts, graphs).
     - User activity tracking (most active users, most purchased packages).
     - Heatmaps for understanding user interaction.

---

**2. AI-Powered Recommendation System**
   - **Features:**
     - Recommend popular packages based on user preferences and purchase history.
     - "Frequently Bought Together" suggestions on product detail pages.


---

**3. Subscription Plans**
   - **Features:**
     - Offer subscription tiers (e.g., weekly or monthly UC/Diamond top-ups).
     - Automated recurring billing for subscriptions.

---

**4. Coupon System**
   - **Features:**
     - Admin-generated coupon codes for discounts.
     - Apply coupon codes during checkout.
