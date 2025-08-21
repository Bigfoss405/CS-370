# CS-370
Foster Hare

# Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
The main goal of EventBuddy was to provide users with a simple way to track and manage events. It was designed to address user needs such as creating, viewing, and deleting events quickly, while keeping information organized in an easy-to-navigate interface. The requirement was to make event management accessible to everyday users without requiring advanced technical skills.

# What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
-Login Screen: To create an account or sign in securely.

-Event List Screen (Data Grid): To display all saved events in a structured list or card format.

-Event Card View: Showing individual event details such as title, date, and location.

-Add Event Screen: For entering new event information.

-SMS Permission Feature: Allowing optional text message reminders.

The UI design used a clean layout with readable text, consistent buttons, and card-based displays so users could quickly scan events. By keeping the design minimal and intuitive, it reduced cognitive load, which made it successful in delivering a user-centered experience.

# How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?
The app was built in Android Studio using Java with an object-oriented design to keep it organized and easy to manage. It used a Model–View–Adapter pattern, where the Event class handled the data and the EventAdapter displayed it in RecyclerView cards. Each activity had its own job, like LoginActivity for sign-in and DataGridActivity for showing events. The code was also modular, making it easy to add future features like notifications or event filtering. These strategies helped keep the code clean, flexible, and ready to grow with the app.

# How did you test to ensure your code was functional? Why is this process important, and what did it reveal?
Testing involved running the app on the Android emulator to check UI flow, event creation/deletion, and SMS permissions. Debugging tools in Android Studio were used to trace crashes and layout issues. This process was important because it revealed problems like adapter mismatches, small touch targets for buttons, and layout fidelity issues. Testing ensured the app was not only functional but also user-friendly.

# Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?
One challenge was ensuring smooth integration of the RecyclerView with dynamic event data. Overcoming this required careful use of adapters and debugging mismatches between Event objects and UI binding.

# In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
A particularly successful component was the RecyclerView with card-based event display. It demonstrated knowledge of data handling, UI/UX design, and adapter-based programming. This component made the app professional, responsive, and scalable — showing skills in both front-end design and back-end data management.
