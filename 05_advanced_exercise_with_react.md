# Advanced Exercise: Creating a Responsive Credit Card Form with React and Bootstrap

## Objective

- Build a credit card form using React.
- Apply responsive design principles using Bootstrap.
- Utilize GitHub Copilot to assist with code generation and refactoring.

## Prerequisites

- Basic knowledge of React and Bootstrap.
- Visual Studio Code with GitHub Copilot installed.

## Steps

### 1. Setup React Project

1. **Initialize a new React project:**

   ```bash
   npx create-react-app credit-card-form
   cd credit-card-form
   ```

2. **Install Bootstrap:**

   ```bash
   npm install bootstrap
   ```

3. **Include Bootstrap CSS in `src/index.js`:**

   ```javascript
   import 'bootstrap/dist/css/bootstrap.min.css';
   ```

### 2. Create the Credit Card Form Component

**Step-by-Step Implementation:**

1. **Create `CreditCardForm.js`:**

2. **Include the Component in `App.js`:**

   ```javascript
   import React from 'react';
   import CreditCardForm from './CreditCardForm';

   function App() {
     return (
       <div className='App'>
         <CreditCardForm />
       </div>
     );
   }

   export default App;
   ```

### 3. Making the Form Responsive

Bootstrap ensures the form is responsive out of the box. The `d-flex justify-content-center align-items-center min-vh-100 bg-light` classes center the form both vertically and horizontally. The `form-control` class makes input fields responsive.

### 4. Using GitHub Copilot for Code Suggestions

**Example of GitHub Copilot Assistance:**

- While typing the form's JSX, Copilot can suggest the input fields, labels, and classes based on common patterns.
- For instance, typing `<input` and selecting the suggestion from Copilot can speed up the coding process significantly.

### 5. Testing the Component

1. **Manual Testing:**

   - Run the application using `npm start`.
   - Check the form on different screen sizes to ensure responsiveness.
   - Submit the form and verify the console logs the entered details.

2. **Automated Testing (Optional):**
   - Use tools like Jest and React Testing Library to write tests for the form component.

## Conclusion

Building a responsive credit card form using React and Bootstrap is straightforward with the help of GitHub Copilot. It assists in generating boilerplate code, applying best practices, and speeding up the development process.

## References

- [Bootstrap Documentation](https://getbootstrap.com/docs/5.0/getting-started/introduction/)
- [React Documentation](https://reactjs.org/docs/getting-started.html)
- [GitHub Copilot Documentation](https://docs.github.com/en/copilot)
