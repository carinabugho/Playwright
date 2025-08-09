# Playwright
Playwright sample test script

In this project I included these UI Test Scenarios:
1. Navigate to the Spree Commerce demo store.
2. Click on the user icon and Sign Up as a new user from the registration page from
the side menu. (Log out if needed)
3. Log in with the newly registered user credentials.
4. Browse products and open a product detail page.
5. Add the product to cart.
6. Go to the cart and verify the product details (name, quantity, price).
7. Proceed to checkout and complete the following:
○   Add a shipping address.
○ Select a shipping method.
○ Verify the different delivery and pricing options.
○ Select a payment method. (Kindly refer test card details on the checkout)
○ Complete the order.
8. Verify the order confirmation page is shown with an order number and success message.
9. Add assertions at each key step (e.g., URL validation, UI messages, order confirmation, etc.)
    

This project will run 4 testclasses:
<class name="tests.RegisterNewUser"/>
<class name="tests.Logout"/>
<class name="tests.Login"/>
<class name="tests.OrderAnItem"/>
