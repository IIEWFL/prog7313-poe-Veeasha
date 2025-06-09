# SpendSense 

SpendSense is a smart budgeting app built with Android and Firebase that helps users track income and expenses, visualize spending, monitor progress toward goals, and get rewarded with a gamified ranking system.

## Features
- *Register Page*: Create a new user to the database
-**Login Page**; Login an existing user
- **Track Finances Page**: Add income and expenses categorized by type which is stored to database. Images of finances can also be captured and stored.
- **Home Page**: Visual summary of balance, top categories, and frequent spending.
- **Bar Graph**: See users progress of expenses compared to min and max goals in a selectable period/timeline.
-**Visual Format**: Shows monthly expense spending progress for different categories which compares users progress to their min and max goals with a colour coded progress bar that determines users progress.
-*Gamified Ranking System**:
  - Earn points based on your balance.
  - Unlock ranks: Bronze → Silver → Gold → Emerald → Platinum.
-  **Firebase Integration**:
  - Authentication with FirebaseAuthentication.
  - Real-time financial data storage using Firebase Realtime Database.
- **Goal Tracking**: Navigate to the Goals Progress screen and set financial goals. Progress of the goals can then be viewed on graph and visual format.
- **Expense Bar Graph**: View your monthly expenses compared to min max goals. 
- **Calendar Page**: View added expenses for a selected day
**Additional Features**:
- Confetti celebration is shown when rank image is clicked. 
- Pie Chart Visualization
- Splash Screen
- Total Balance displayed and calculated dynamically (Total Income - Total Expenses)
- Calculator Page to do small calculations if needed.
- Add Income as well, not only an expense 
- Profile Icon Customization (Bill and Penny)
---
# Updates From Part 2
-**Minamalist Finance Page**: Added buttons to open new views to display Income and Expense entries
-**Improved Code Attribution**: Code attributed properly and added descriptive comments.


## Tech Stack

- **Kotlin** – Primary language
- **Android Jetpack** – Fragment-based navigation
- **Firebase** – Auth & Realtime Database
- **MPAndroidChart** – Pie chart visualizations
- **Konfetti** – Animated confetti celebration
- **MVVM** – (Model-View-ViewModel) architecture pattern 

---

# Youtube demonstration video 
- **Link**: https://youtu.be/EP6hEKsN_UA
---
# References (is included in code as well): 
Firebase Documentation and Tools
 Anon (2019). Saving Data | Firebase Realtime Database. [online] Firebase.
Available at: https://firebase.google.com/docs/database/admin/save-data.
 Anon (2020a). Manage Users in Firebase. [online] Firebase. Available at:
https://firebase.google.com/docs/auth/web/manage-users.
 Anon (2020b). Read and Write Data on the Web | Firebase Realtime
Database. [online] Firebase. Available at:
https://firebase.google.com/docs/database/web/read-and-write.
 Firebase (2019). Firebase Realtime Database. [online] Firebase. Available at:
https://firebase.google.com/docs/database.
 Firebase (n.d.). Firebase Guides. [online] Firebase. Available at:
https://firebase.google.com/docs/guides.

UI Elements (Buttons, SeekBar, Spinner, etc.)
 A. Sharabiani (2018). Android - How to create a drop-down list? [online] Stack
Overflow. Available at: https://stackoverflow.com/questions/13377361/how-to-
create-a-drop-down-list. (A. Sharabiani, 2018)
 Developers, A. (n.d.). Spinners. [online] Android Developers. Available at:
https://developer.android.com/develop/ui/views/components/spinner.
(Developers, A., n.d.)
 GeeksforGeeks (2019). Creating a SeekBar in Android. [online]
GeeksforGeeks. Available at: https://www.geeksforgeeks.org/android-
creating-a-seekbar/. (GeeksforGeeks, 2019)
 Show, S. (2017). Android SeekBar: Show progress value along the seekbar.
[online] Stack Overflow. Available at:
https://stackoverflow.com/questions/41774963/android-seekbar-show-
progress-value-along-the-seekbar. (Show, S., 2017)
Camera Integration
 Developers, A. (2024). Get started with camera on Android. [online] Android
Developers. Available at: https://developer.android.com/media/camera/get-
started-with-camera. (Developers, A., 2024)
Profile Editing &amp; User Data
 Aamjit Yanglem (2022). How do I add a functional edit icon for a profile picture
in Android Studio? [online] Stack Overflow. Available at:
https://stackoverflow.com/questions/71860869/how-do-i-add-a-functional-edit-
icon-for-a-profile-picture-in-android-studio. (Aamjit Yanglem, 2022)

 GeeksforGeeks (2021). Implementing Edit Profile Data Functionality in Social
Media Android App. [online] GeeksforGeeks. Available at:
https://www.geeksforgeeks.org/implementing-edit-profile-data-functionality-in-
social-media-android-app/. (GeeksforGeeks, 2021)
Android Development Basics (Fragments, Layout Editor, etc.)
 Android Developers (n.d.). Fragments. [online] Android Developers. Available
at: https://developer.android.com/guide/fragments. (Android Developers, n.d.)
 Developers, A. (n.d.). Build a UI with Layout Editor. [online] Android
Developers. Available at: https://developer.android.com/studio/write/layout-
editor. (Developers, A., n.d.)
Other Development Tools &amp; Guides
 GeeksforGeeks (2019a). Android | Creating a Calendar View app. [online]
GeeksforGeeks. Available at: https://www.geeksforgeeks.org/android-
creating-a-calendar-view-app/. (GeeksforGeeks, 2019a)
 GeeksforGeeks (2019b). How to build a simple Calculator app using Android
Studio? [online] GeeksforGeeks. Available at:
https://www.geeksforgeeks.org/how-to-build-a-simple-calculator-app-using-
android-studio/. (GeeksforGeeks, 2019b)
 GeeksforGeeks (2023). Android - Login and Logout Using Shared
Preferences in Kotlin. [online] GeeksforGeeks. Available at:
https://www.geeksforgeeks.org/android-login-and-logout-using-shared-
preferences-in-kotlin/. (GeeksforGeeks, 2023)
 Kittle (n.d.). Kittl - Join the design revolution. [online] Available at:
https://www.kittl.com/ [Used to design variations of our logo]. (Kittle, n.d.)
Manifest &amp; Category in List Item
 Developers, A. (2025). Category element in Android manifest. [online] Android
Developers. Available at:
https://developer.android.com/guide/topics/manifest/category-element
[Accessed 28 Apr. 2025]. (Developers, A., 2025)
 Zouarv42 (2016). How to create ‘category’ in the list item? [online] Stack
Overflow. Available at: https://stackoverflow.com/questions/37923966/how-to-
create-category-in-the-list-item. (Zouarv42, 2016)
General Assistance
 OpenAI (2025). Assistance with designing and cleaning XML in Android
Studio. [online] Available at: https://www.openai.com [Accessed 1 May 2025].
(OpenAI, 2025)

Charting and Data Visualization
 PhilJay (2019). PhilJay/MPAndroidChart. [online] GitHub. Available at:
https://github.com/PhilJay/MPAndroidChart.
 Anon (2021). Build a realtime graph in Android | Pusher tutorials. [online]
Pusher.com. Available at: https://pusher.com/tutorials/graph-android/
[Accessed 6 Jun. 2025].
 GeeksforGeeks (2020). How to add a Pie Chart into an Android Application. [online]
GeeksforGeeks. Available at: https://www.geeksforgeeks.org/how-to-add-a-pie-chart-
into-an-android-application/.
 Developer Chunk (2023). Create Custom Pie Chart with Animations in Jetpack
Compose | Android Studio | Kotlin. [online] Medium. Available at:
https://medium.com/@developerchunk/create-custom-pie-chart-with-animations-in-
jetpack-compose-android-studio-kotlin-49cf95ef321e [Accessed 6 Jun. 2025].
 GeeksforGeeks (2021). How to Create a BarChart in Android? [online]
GeeksforGeeks. Available at: https://www.geeksforgeeks.org/how-to-create-a-
barchart-in-android/.
 Medium.com. (2025). Welcome To Zscaler Directory Authentication. [online]
Available at: https://medium.com/@developerchunk/create-bargraph-in-jetpack-
compose-android-studio-kotlin-ec526be25479 [Accessed 6 Jun. 2025].
 Android Developers. (2025). Progress indicators. [online] Available at:
https://developer.android.com/develop/ui/compose/components/progress [Accessed 6
Jun. 2025].
 GeeksforGeeks. (2021b). Line Graph View in Android with Example. [online]
Available at: https://www.geeksforgeeks.org/line-graph-view-in-android-with-
example/.
Animation Libraries
 Segijn, D. (2024). DanielMartinus/Konfetti. [online] GitHub. Available at:
https://github.com/DanielMartinus/Konfetti.
 https://cssgradient.io/
Android Development Components

 Anon (2025). View binding. [online] Android Developers. Available at:
https://developer.android.com/topic/libraries/view-binding?authuser=1
[Accessed 6 Jun. 2025].
 GeeksforGeeks (2022). ProgressBar in Android. [online] Available at:
https://www.geeksforgeeks.org/progressbar-in-android/.
