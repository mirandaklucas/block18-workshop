Unit Tests
---
Happy Path
- Returns only 1 array
- Returns only odd numbers
- Returns odd numbers in ascending order
- If unexcepted inputs are set in the code, return NaN or undefined
- Returns negative odd numbers
- Correct multiplication is done

Unhappy Path
- Returns even and odd numbers
- Does not return in ascending order
- Does not return negative odd numbers
- Code just goes up in error when even no valid odd number given
- Does not multiply two arrays, either adds or divides


Functional Tests
---
Happy Path
- Should prompt the user to login/create acct when going to checkout
- If user does not wish to create acct, allow them to checkout as guest
- both ways of check out needs to have the same pages afterwards; contact, shipping, promo codes, credit card info, confirm purchase
- After submitting info during each step it is retained until the completion of the checkout(info isn't discarded after hitting 'enter' to next step)

Unhappy Path
- If the cart is empty, user cannot checkout
- Customer can't checkout without logging in/creating account
- Not all steps are given to exsiting customers &/ guest checkouts
- Customer not given the option to login if existing customer & can't create new account since email/info is already in use
- 'Submit' or 'enter' buttons do not work