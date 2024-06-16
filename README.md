# Task Manager Implementation

## Overview

This project implements a React application for managing tasks with tagging functionality. The following features have been successfully implemented:

### Features Implemented

1. **Initial State:**
   - The list of tasks and the task input field are initially empty.
   - The active option in the `Tags` select element is the first item of the given `tagsList`.

2. **Adding Tasks:**
   - When non-empty values for tasks and tags are provided, and the **Add Task** button is clicked:
     - A new task is added to the list.
     - The task input and tag select elements are reset to their initial values.

3. **Filtering Tasks by Tags:**
   - Clicking a tag changes it to an active state, and tasks are filtered accordingly.
   - When no tag is active, all tasks are displayed.

4. **Data Management:**
   - Used the `uuid` package to generate unique IDs for tasks.

5. **Design Implementation:**
   - Implemented the design files provided for different screen sizes, ensuring responsiveness and adherence to the provided color palette and font families.

6. **Component Organization:**
   - Ensured all components are placed in the `src/components` directory without altering the folder names to maintain compatibility with the tests.

### Refer to the image below:
<br>
<div style="text-align: center;">
  <video style="max-width:80%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12);outline:none;" loop="true" autoplay="autoplay" controls="controls" muted>
    <source src="https://assets.ccbp.in/frontend/content/react-js/my-tasks-output.mp4" type="video/mp4">
  </video>
</div>
<br/>

### Set Up Instructions

To set up the project, follow these steps:

1. Download dependencies by running:
   ```bash
   npm install
   ```

2. Start up the app using:
   ```bash
   npm start
   ```

### Important Note

- The following instruction is required for the tests to pass:
  - Use the `uuid` package to generate the unique id.

### Design Files

The design files used in this implementation can be viewed here:

- [No Tasks View](https://assets.ccbp.in/frontend/content/react-js/my-tasks-output-no-tasks-view.png)
- [Default View](https://assets.ccbp.in/frontend/content/react-js/my-tasks-output.png)
- [Filter View](https://assets.ccbp.in/frontend/content/react-js/my-tasks-output-filter-view.png)

### Colors

The following colors were used in the application:

- ![#131213](https://via.placeholder.com/15/131213/000000?text=+) `#131213`
- ![#f3aa4e](https://via.placeholder.com/15/f3aa4e/000000?text=+) `#f3aa4e`
- ![#f1f5f9](https://via.placeholder.com/15/f1f5f9/000000?text=+) `#f1f5f9`
- ![#64748b](https://via.placeholder.com/15/64748b/000000?text=+) `#64748b`
- ![#f8f8f8](https://via.placeholder.com/15/f8f8f8/000000?text=+) `#f8f8f8`
- ![#475569](https://via.placeholder.com/15/475569/000000?text=+) `#475569`
- ![#323f4b](https://via.placeholder.com/15/323f4b/000000?text=+) `#323f4b`
- ![#000000](https://via.placeholder.com/15/000000/000000?text=+) `#000000`
- ![#ffffff](https://via.placeholder.com/15/ffffff/000000?text=+) `#ffffff`
- ![#1a171d](https://via.placeholder.com/15/1a171d/000000?text=+) `#1a171d`
- ![#f8fafc](https://via.placeholder.com/15/f8fafc/000000?text=+) `#f8fafc`

### Font Families

The following font family was used in the application:

- Roboto

### Next Steps

- **Testing:** Ensure all functionalities are thoroughly tested.
- **Optimization:** Further optimize the code for performance and scalability.

## Conclusion

The task manager application with tagging functionality has been successfully implemented as per the provided requirements and design specifications.
