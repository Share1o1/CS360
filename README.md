# CS360

App Requirements & User Needs
The app, a fitness tracker, was designed to help users monitor daily workouts, track health metrics, and receive SMS alerts for goal achievements. It addresses user needs for simplified fitness logging, progress visualization, and motivation through automated notifications.

Screens & User-Centered UI
Key screens included a login/registration screen, workout dashboard, data grid, and SMS settings. Features like one-tap logging, password visibility toggles, and collapsible cards prioritized ease of use. The UI followed Material Design 3 guidelines for consistency, with clear visual hierarchy (e.g., primary actions in FABs) and accessibility features (48dp touch targets).

Coding Approach & Strategies
The app used MVVM architecture with Room for local data persistence and LiveData for real-time UI updates. Modular code separation (model, view, repository) simplified maintenance. Future projects could replicate this structure for scalability.

Testing & Outcomes
Testing involved unit tests for database operations, manual UI testing via the Android Emulator, and edge cases (e.g., denied permissions). This revealed issues like unhandled null inputs and SMS permission race conditions, emphasizing the need for rigorous validation.

Innovation & Challenges
Innovation was required to handle SMS permission denials gracefully. The app dynamically disabled SMS features while maintaining core functionality, using Snackbars to explain limitations without disrupting the user flow.

Standout Component
The SMS permission system best demonstrated expertise. It integrated Android’s ActivityResult API for modern permission handling, offered contextual explanations, and preserved app functionality when denied—showcasing user-centric design and technical proficiency.
