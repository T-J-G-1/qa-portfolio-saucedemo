# Test Cases - Sauce Demo Web Application

-----

## Login Test Cases

### TC-01: Login with valid credentials
**Preconditions:**
- User is on the login page

**Steps:**
1. Enter Valid Username
2. Enter Valid Password
3. Click the Login button

**Expected Result:**
- User is successfully logged in
- Product Page is displayed

-----

### TC-02: Login with Invalid Password
**Preconditions:**
- User is on the Login Page
  
**Steps:**
1. Enter Valid Username
2. Enter Invalid Password
3. Click the Login Button
   
**Expected Result:**
- Error message is displayed
- User remains on login page

-----

### TC-03: Login with empty Username and Password
**Preconditions:**
- User is on the login page
  
**Steps:**
1. Leave Username field empty
2. Leave Password field empty
3. Click the Login button
   
**Expected Result:**
- Validation error message is displayed

-----

## Product Page Test Cases

### TC-04: View Product list after Login
**Preconditions:**
- User is Logged in
  
**Steps:**
1. Navigate to the product page
   
**Expected Result:**
- List of products is displayed
- Each product shows name, image and price

-----

### TC-05: Add a Product to the Cart
**Preconditions:**
- User is logged in
- Product page is displayed
  
**Steps:**
1. Click "Add to Cart" on a product
   
**Expected Result:**
- Product is added to cart
- Cart Icon updates with the item count

-----

### TC-06: Romove a product from the Cart
**Preconditions:**
- User has a product in the cart
  
**Steps:**
1. Click "Remove" on the product
   
**Expected Result:**
- Product is removed from cart
- Cart Icon item count updates

-----

## Cart Test Cases

### TC-07: View Cart Contents:**
**Preconditions:**
- User has added a product to the cart
  
**Steps:**
1. Click the cart icon

**Expected Result:**
- Cart page displays correct product(s)

-----

### TC-08: Continue shopping from Cart:**
**Preconditions:**
- User is on the cart page
  
**Steps:**
1. Click "Continue Shopping"
   
**Expected Result:**
- User is returned to the product page

-----

## Checkout Test Cases

### TC-09: Complete Checkout with valid Details:**
**Preconditions**
- User has a product in the cart
**Steps:**
1. Click "Checkout"
2. Enter valid first name
3. Enter Valid last name
4. Enter valid post code
5. Click "continue"
6. Click "finish"
   
**Expected Result:**
- Checkout completes successfully
- Order confirmation page is displayed

-----

### TC-10: Checkout with missing required details:**
**Preconditions**
- User has a product in the cart
  
**Steps:**
1. Click "Checkout"
2. Leave one required field empty
3. Click "Continue"
   
**Expected Result:**
- Error message is displayed
- User cannot proceed to next step

-----

## Navigation Test Cases

### TC-11: Logout from the application 
**Preconditions:**
- User is logged in
  
**Steps:**
1. Open the menu
2. Click "Logout"
   
**Expected Result:**
- User is logged out
- Login page is displayed
