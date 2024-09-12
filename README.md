# Kanban Board 
The Kanban Board application is an interactive, React-based web application for managing tasks across different columns. It allows users to efficiently organize, prioritize, and manage their workload. The responsive design ensures optimal user experience across devices, providing a streamlined approach to task management.

# Key Features:
(1) User-Friendly Interface:

    (a) Navigation Bar:
    -> Provides access to the core sections of the app, allowing users to switch between task views.
    -> Enables a smooth transition between board columns via scroll functionality.

    (b) Board View:
    -> Displays tasks categorized into columns such as To Do, In Progress, Done, and Cancelled.
    -> Offers easy task visualization with task details visible on cards.

(2) Task Management:

    (a) Drag-and-Drop Functionality:
    -> Users can easily drag tasks between columns to update their status.
    -> The system automatically adjusts the task list to reflect changes.

    (b) Task Grouping:
    -> Tasks can be grouped based on status, user, or priority, providing flexibility in task management.

(3) Dynamic Task Ordering:

    (a) Sort by Priority:
    -> Organizes tasks in ascending or descending order based on priority levels.
    
    (b) Sort by Title:
    -> Alphabetically sorts tasks for better navigation and searchability.

(4) Responsive Design:

    (a) Mobile and Desktop Compatibility:
    -> Adapts to any screen size, ensuring a seamless experience on both mobile devices and larger screens.
    -> Flexbox and media queries are used to provide a fluid layout.

(5) Task Status Indicators:

    (a) Visual Indicators:
    -> Each task is color-coded to reflect its current status, making it easy to identify tasks at a glance.
    
    (b) Task Status Updates:
    -> Users can manually update the status of each task with a single click.
# Folder Structure
    Copy code
    ├── public
    │   ├── index.html        # HTML Template
    │   └── favicon.ico       # App Icon
    ├── src
    │   ├── Assets            # Images and icons
    │   ├── Components        # Reusable components (Navbar, List)
    │   ├── App.js            # Main React Component
    │   ├── App.css           # Global styles
    │   └── index.js          # Entry point
    └── package.json          # Project metadata and dependencies

# Tools and Technologies Used:
(1) Frontend:

    (a) React.js:
    -> Utilized for building a dynamic, component-based user interface.
    -> Efficiently handles state changes and ensures a responsive design.
    
    (b) CSS Flexbox & Media Queries:
    -> Enables a responsive and adaptive layout for mobile and desktop views.
    
    (c) JavaScript:
    -> Implements interactive features like task sorting, drag-and-drop, and status updates.

(2) Data Fetching:

    (a) Axios:
    -> Used for fetching external data from the Kanban API to populate task cards dynamically.
    -> API URL: https://api.quicksell.co/v1/internal/frontend-assignment

(3) State Management:
    
    (a) React State:
    -> Effectively manages the application's state to ensure seamless transitions and task updates.
# Future Enhancements
    (1) User Authentication: Allowing users to log in and manage personal Kanban boards.
    (2) Task Details Modal: Click on a task to view and edit detailed information.
    (3) Real-time Collaboration: Multiple users can manage the board simultaneously.
    (4) Drag-and-Drop Reordering: Enhance task interaction by allowing drag-and-drop across lists.
    (5) Task Filtering: Provide options to filter tasks based on specific criteria like status, priority, or user.

# Contribution:
Contributions are welcome! If you have any suggestions for improvements or new features, feel free to fork the repository and create a pull request. Please ensure your changes are well-documented and tested.

    (1) Fork the repository:
    URL : git clone https://github.com/your-username/kanban-board.git
    
    (2) Create a feature branch:
    URL : git checkout -b feature-name
    
    (3) Commit your changes:
    URL : git commit -m "Add feature"
    
    (4) Push to the branch:
    URL : git push origin feature-name
    
    (5) Submit a pull request.

# License:
This project is licensed under the MIT License. See the LICENSE file for details.

# Contact:
For questions or feedback, please reach out via email@example.com.
