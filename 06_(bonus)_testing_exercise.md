# Bonus: Adding Tests with React Testing Library

## Objective

- Write tests for the credit card form using React Testing Library.
- Ensure the form behaves as expected, including validation and submission.

## Prerequisites

- Basic knowledge of React Testing Library and Jest.
- The existing React credit card form component.

## Steps

### 1. Install React Testing Library

1. **Install necessary packages:**

   ```bash
   npm install @testing-library/react @testing-library/jest-dom
   ```

### 2. Create Tests for the Credit Card Form

**Step-by-Step Implementation:**

1. **Create `CreditCardForm.test.js`:**

2. **Explanation of the Tests:**

   - **Rendering the Form:**
     - The first test checks that the form is rendered correctly and all input fields are present.
   - **Form Validation and Submission:**
     - The second test simulates user input and form submission, ensuring the input values are correctly handled.

### 3. Running the Tests

1. **Run the tests using the following command:**

   ```bash
   npm test
   ```

2. **Check the output:**
   - Ensure all tests pass successfully.
   - If any tests fail, review the error messages and adjust the component or tests as needed.

## Conclusion

Adding tests with React Testing Library ensures that the credit card form component behaves as expected. By simulating user interactions and validating input fields, you can catch potential issues early and ensure a reliable user experience.

## References

- [React Testing Library Documentation](https://testing-library.com/docs/react-testing-library/intro/)
- [Jest Documentation](https://jestjs.io/docs/getting-started)
- [Bootstrap Documentation](https://getbootstrap.com/docs/5.0/getting-started/introduction/)
- [React Documentation](https://reactjs.org/docs/getting-started.html)
