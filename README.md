# Multi-Step Form

This project is a responsive multi-step form built using React.js. The form includes three steps: Personal Information, Address Information, and Confirmation. The form data is validated, persisted in local storage, and ensures sequential completion of steps. 

## Features

- Multi-step form with three steps:
  - Step 1: Personal Information (Name, Email, Phone)
  - Step 2: Address Information (Address Line 1, Address Line 2, City, State, Zip Code)
  - Step 3: Confirmation (Review all entered data)
- Navigation and Buttons:
  - Tabbed navigation to switch between steps
  - Disabled back button on the first step
  - Disabled next button on the last step, replaced with a submit button
- Validation:
  - Client-side validation to ensure all fields are filled before allowing navigation to the next step
  - Appropriate error messages if fields are empty or invalid (e.g., email format)
  - Highlighting of fields with errors
- State Management:
  - Managed form data using React state
  - Used hooks like `useState` and `useEffect` for state management
  - State updates reflect user inputs and form navigation
- Local Storage:
  - Persisted entered data to local storage when the user navigates between steps
  - Retrieved and pre-filled form fields if the user revisits the form
- Responsive Design:
  - Responsive design that works well on desktop, tablet, and mobile screens
  - Used Material UI for layout and responsiveness

## Getting Started

### Prerequisites

- Node.js
- npm (Node Package Manager)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/suryathangaraj2003/multi-form.git
   cd multi-step-form
