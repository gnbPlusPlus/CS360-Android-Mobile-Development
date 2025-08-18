# CS360-Android-Mobile-Development
Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
--
The app is an event tracker that supports account creation and stores event names and dates in a database. These stored events are separated by ID values so that different users see only their events. Users are able to create an account, log in with their credentials, and add, edit, and delete events. They may allow SMS notifications that send event reminders, as well.

What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
--
The app needed a minimum of the following screens to fulfill its basic functionality: login, create an account, add and view upcoming events, edit an event, and accept/deny SMS permission. Each screen then needed a mix of widgets that displayed text, allowed text input, and accepted button presses so that navigation was intuitive and information could be entered. My designs kept the user in mind by sizing all text to at least 12sp, giving padding to visual elements, using high contrast between text and background colors, using cards to house different visual areas, and creating aesthetic, cohesive appeal via a gradient background and logo.

How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?
--
I approached coding the app by working in chunks, although many chunks overlapped throughout development. I referenced specific chapters in my textbook for code regarding the database, adapter, model, fragments, and UI elements (i.e., colors, strings, and layouts). I relied on GeeksForGeeks articles, among others, for specific questions that my textbook couldn't answer, such as what to do for a mock SMS implementation. Android Studio feels like its own world when it comes to coding, so I used these sources to understand the syntax, and I began recognizing patterns along the way. In the future, this pattern recognition will be a huge benefit, since I'll understand the general structure of an app better. Also, because my app referenced a lot of helpful sources, it now acts as a reference itself for my future work.

How did you test to ensure your code was functional? Why is this process important, and what did it reveal?
--
I heeded the compiler and corrected any errors as they came up. I also paid attention to warnings and refactored my code as needed, such as by giving variables local instead of global scope. Testing the app in the emulator was how I weeded out bugs that the compiler couldn't catch. Events for other users were coming up for new users, and I realized I mistyped COLUMN_EVENT_USER_ID as COLUMN_USER_ID, for example.

Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?
--
I "innovated" by toning down my original UI design. This might sound counterintuitive, but it was a valuable lesson in designing with development in mind, because when I sat down to work with my wireframe, I felt overwhelmed. For future designs, I'll think about how layouts lend themselves to placing (and moving) different visual elements. Innovation can then be born from creating development-friendly designs that don't have to sacrifice visual appeal or functionality.

In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
--
I'm proud of the login and account creation screens, as well as the splash screen (that comes after the default Android one in the current app draft). I think these screens are visually appealing and navigable in a way that makes the app feel more professional. I'm also proud of the user-specific event lists, since this took a lot of testing and bug-checking to perfect. The toast messages sprinkled throughout the app add to the theme of conversational, casual language while keeping the user informed on app processes. The RecyclerView successfully displays a varying amount of events and lets the user scroll through them, if the list gets that long. Put together, the blend of UI and UX design and implementation is proof of my expanded skillset, and I will use this app as a frequent reference for future Android projects.
