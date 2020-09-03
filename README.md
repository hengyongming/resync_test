Implement a task tracker app using Firebase Auth and Cloud Firestore:

1) Create a base flutter project. 

2) Create a firebase project and link it to the mobile app project.(just work on the android part of the app, don't worry about the ios side).

3) This will be a 2 page-app, you are free to implement the navigation between the pages using a bottom nav bar or a    drawer.

4) On first launch, the app lets users sign in with Firebase, just use anonymous authentication.

5) After sign in, the app shows the first page where the user can:
    - Enter his/her task title and description into a form and submit it.
    - Save this into Firestore.

6) On the second page, show the list of tasks (title and description) of that particular user.

7) On the second page, the user should be able to edit the tasks and delete the task. All these actions, should be reflected in firestore as well.

8) Implement a sign-out functionality as well. 


Feel free to use any libraries that you may require,when building the UI and navigating between screens, choose the approach that makes most sense in terms of usability. Adding tests is not required for this project, but the final code should be testable.

If some requirements appear to be vague or lack sufficient details, make assumptions based on your own judgment.

The assignment will be evaluated according to the following criteria:
1) the app works and satisfies the requirements outlined above
2) general project structure and organization of code
3) separation of concerns between UI, authentication, database code
4) simplicity - we don't require an over-engineered solution
4) naming conventions for variables, functions and classes
5) Making the UI look nice is not required as part of this task - legible text and usable UI is sufficient.(Good creative UI is always welcome!)

The expected duration of this assignment is between 3 and 8 hours.

When submitting the assignment, push the entire flutter project to a separate branch in this repo with this naming convention <your-name>_flutter_assignment. If there are any parts of this assignment that you can not complete, include a brief explanation of why in a shortcomings.txt file in the root folder. All the best!
