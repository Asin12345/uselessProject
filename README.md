AsA mealmate 🍽️
A simple and elegant food booking web application that allows users to browse a menu and place orders with a beautiful, responsive interface.
📋 Table of Contents

Features
Demo
Installation
Usage
Menu Items
File Structure
Technologies Used
Contributing
License
TEAM MEMBERS 
Asin Mariya
Alwina k j
✨ Features

Interactive Menu Display: Browse categorized menu items with prices
Multiple Item Booking: Add multiple food items to a single order
Dynamic Form: Add/remove items dynamically during order creation
Order Calculation: Automatic price calculation for each item and grand total
Responsive Design: Beautiful UI with food-themed background
Form Validation: Built-in validation for required fields and phone numbers
Order Confirmation: Display complete order summary upon successful booking

🎯 Demo
The application provides a clean, user-friendly interface featuring:

Menu sections (Starters, Main Course, Desserts)
Dynamic booking form with add/remove functionality
Real-time order summary and total calculation
Success confirmation with complete order details

🚀 Installation

Clone or Download: Save the HTML file to your local machine
Open in Browser: Simply open index.html (or your filename) in any modern web browser
No Server Required: This is a client-side application that runs entirely in the browser

bash# If using git
git clone [your-repository-url]
cd mealmate

# Or simply download the HTML file and open it
open index.html
🍕 Usage
For Customers:

Browse Menu: View available items organized by category
Select Items: Choose food items from dropdown menus
Set Quantities: Specify quantity for each item
Add More Items: Click "Add Another Item" to include multiple items
Fill Details: Enter your name, phone number, and location
Place Order: Click "Book Now" to confirm your order
View Summary: See your complete order details and total amount

For Developers:
The application uses vanilla JavaScript and can be easily customized:
javascript// Modify prices in the priceMap object
const priceMap = {
  "Spring Rolls": 80,
  "Chicken Soup": 100,
  // Add or modify items here
};
🍽️ Menu Items
Starters

Spring Rolls - ₹80
Chicken Soup - ₹100
Paneer Tikka - ₹120

Main Course

Chicken Biryani - ₹150
Beef Biryani - ₹170
Vegetable Biryani - ₹130
Pizza - ₹250
Burger - ₹120
Pasta - ₹180
Sandwich - ₹90
Fries - ₹70

Desserts

Ice Cream - ₹60
Gulab Jamun - ₹50
Brownie - ₹90

📁 File Structure
mealmate/
│
├── index.html          # Main application file
├── README.md          # This file
└── [optional assets/]
    ├── images/        # Local images (if needed)
    └── styles/        # Additional CSS (if separated)
🛠️ Technologies Used

HTML5: Structure and semantic markup
CSS3: Styling, responsive design, and visual effects
JavaScript (ES6+): Dynamic functionality and form handling
Unsplash API: Background image integration

Key Libraries/APIs:

None required - Pure vanilla web technologies
External background image from Unsplash

🎨 Customization
Adding New Menu Items:

Update the menu display in HTML
Add options to the select dropdowns
Update the priceMap object with new prices

Styling Changes:

Modify CSS variables for colors and fonts
Change background image URL in the CSS
Adjust container styling and responsive breakpoints

Functionality Extensions:

Add payment integration
Include order tracking
Implement user authentication
Add database connectivity

🔧 Known Issues

Option Mismatch: Some dropdown options don't match their values (e.g., "Spring Rolls" option shows "Chicken Soup(Starter)")
Ice Cream Categorization: Ice Cream appears in Main Course dropdown instead of Desserts
Phone Validation: Basic pattern validation - could be enhanced for different regions

📝 Contributing

Fork the repository
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request

📄 License
This project is open source and available under the MIT License.
📞 Support
For support or questions:

Create an issue in the repository
Contact the development team
Check the documentation for common solutions

🚀 Future Enhancements

 Backend integration for order processing
 Payment gateway integration
 Order tracking system
 Admin panel for menu management
 Mobile app version
 Email notifications
 User accounts and order history


The Screenshots 
1-[fodd Menu]<img width="1920" height="1080" alt="Screenshot 2025-08-08 150303" src="https://github.com/user-attachments/assets/cae870df-f1a9-4fa6-86d1-712cbe3fd97f" />

2-[ordering food]<img width="1920" height="1080" alt="Screenshot 2025-08-08 150233" src="https://github.com/user-attachments/assets/9014dfcb-17c0-4539-b865-0f13bb4b7efa" />

3-[Result is unordering food]<img width="1920" height="1080" alt="Screenshot 2025-08-08 150303" src="https://github.com/user-attachments/assets/e8281259-fbea-4193-9348-ba315cb2d252" />


MealMate - Making food ordering simple and delightful! 🍽️✨
