# Credit Card Validation 🏦💳

This is a simple JavaScript project to validate credit card numbers using the **Luhn Algorithm**. It identifies valid and invalid cards and then maps them to the issuing companies (Visa, Mastercard, Amex, Discover).

## Features ✨
- **Validate Credit Card Numbers** ✅
- **Identify Invalid Cards** ❌
- **Detect Card Issuers** 🏢

## How It Works ⚙️
1. Validates each card using the Luhn algorithm.
2. Identifies the issuing company based on the first digit.
3. Returns an array of companies that have issued invalid cards.

## Example 🔍
```javascript
const batch = [ 
  [4, 5, 3, 2, 7, 7, 8, 7, 7, 1, 0, 9, 1, 7, 9, 5], 
  [5, 7, 9, 5, 5, 9, 3, 3, 9, 2, 1, 3, 4, 6, 4, 3]
];

console.log(idInvalidCardCompanies(findInvalidCards(batch)));
// Output: [ 'Visa', 'Mastercard' ]
