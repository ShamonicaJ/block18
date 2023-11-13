# block18



Multiplication Function Test

unit test

1.Expect the result of calling the multiplication function with arguments (2, 3) to be 6.

2.Expect the result of calling the multiplication function with arguments (0, 5) to be 0.

3.Expect the result of calling the multiplication function with arguments (-4, 7) to be -28.

4.Edge Case: Expect the result of calling the multiplication function with arguments (0, 0) to be 0 (handling multiplication by zero).

5.Edge Case: Expect the result of calling the multiplication function with arguments (1, 1000000) to be 1000000 (testing large numbers).




ConcatOdds Function Test

unit test

1.Expect the result of calling the concatOdds function with two arrays: [3, 2, 1] and [9, 1, 1, 1, 4, 15, -1] to be [-1, 1, 3, 9, 15].


2.Expect the result of calling the concatOdds function with two arrays: [2, 4, 6, 8] and [10, 12, 14, 16] to be an empty array [].

3.Expect the result of calling the concatOdds function with two arrays: [1, 3, 5] and [] to be [1, 3, 5].

4.Edge Case: Expect the result of calling the concatOdds function with two arrays containing multiples of the same odd number, e.g., [3, 3, 3, 3] and [3, 3, 3], to be [3, 3, 3, 3, 3, 3, 3, 3, 3, 3] (checking handling of duplicates).


Functional Tests:

 Shopping Cart Checkout Feature Test

1.Given a user with items in their cart, when they choose to check out as a guest, expect the system to allow guest checkout without requiring account creation or login.

2.Given a user with an empty cart, expect the system to notify the user that the cart is empty and prevent them from proceeding with checkout.

3.Given a user with items in their cart, when they check out as a guest, expect the system to prompt the user to provide shipping and payment information.

4.Given a user with items in their cart, when they check out as a logged-in user, expect the system to bypass the account creation step.

5.Given a user with items in their cart, when they check out, expect the system to show a summary of the order at each step of the checkout process.

6.Given a user with items in their cart, when they check out as a guest, expect the system to ask the user if they want to create an account, and if they decline, proceed with the guest checkout process.

7.Edge Case: Given a user with an empty cart, expect the system to notify the user about an empty cart at various stages of checkout.