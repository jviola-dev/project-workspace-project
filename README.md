I built Orchid Task because I wanted a clean, satisfying way to organize daily workloads. It's a digital project board that lets you map out tasks, set priorities, and break big goals down into bite-sized subtasks. To make it more fun and personal, I also built in customizable visual themes so users can change up the workspace look whenever they want.


I chose Vue.js and TypeScript for the core engine to keep the code reliable and easy to expand down the road. Instead of grabbing a pre-made design package to build the layout, I challenged myself to design the dashboard from scratch using native CSS Grid. I started by sketching the layouts on paper to map out how the columns should shift. The biggest engineering challenge was managing the component state so that drag-and-drop tasks aligned perfectly inside the grid cells without breaking the layout when items were moved.


Multi-column Kanban boards easily get cramped and messy on small mobile screens. To fix this, I focused on responsive UX design specifically for smartphones. I used CSS spacing rules and the box-sizing property to force the columns to automatically collapse from a wide horizontal view into a single-column, vertical scroll layout. I also enlarged the touch targets for buttons and cards so users can easily tap and slide tasks with their thumbs on smaller screens.


For data persistence, I utilized the browser's localStorage API to save the board state as a JSON string. This ensures that a user's tasks remain saved permanently in their browser, even if they refresh the tab or close the window.


To improve this project in the future, I plan to upgrade the storage from localStorage to a cloud-hosted database like Firebase. This will allow me to implement secure user authentication and multi-device syncing so users can access their tasks from anywhere.









