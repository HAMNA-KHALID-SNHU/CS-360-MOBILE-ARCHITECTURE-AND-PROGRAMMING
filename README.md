# CS-360 Mobile Architecture and Programming

## Module 8

## Github Repository

### Submitted By:

**Hamna Khalid**

hamna.khalid@snhu.edu

### Submitted To:

**Professor Dr. William Smith**

w.smith8@snhu.edu

Southern New Hampshire University

Monday, April 20, 2026

---

This repository contains coursework from CS-360 at Southern New Hampshire University.

# Contents

- Inventory Management Application
- User Authentication System
- SQLite Database Integration
- RecyclerView Grid Display
- SMS Notification Permissions
- App Launch Plan (Optional)


# Technologies Used

- Java
- Android Studio
- SQLite
- RecyclerView
- Android SDK
- ConstraintLayout
- Runtime Permission Handling

---

Repository Overview

This repository contains selected artifacts from CS-360: Mobile Architecture and Programming. The included files demonstrate my ability to design and implement a fully functional Android mobile application using structured architecture, persistent database storage, user authentication, runtime permissions, and user-centered interface design.

Included Artifact:

* Project Three: Completed App Code Design (ZIP File)

This artifact demonstrates end-to-end development from UI planning (Project Two) through backend implementation and launch planning (Project Three).

Together, these artifacts showcase both technical implementation and strategic application design.

---

# Reflection

# Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

The Inventory Management Application was developed to provide a structured and reliable method for tracking inventory items. The app allows users to create secure login credentials, manage inventory records, and receive alerts when item quantities reach zero.

The primary user need addressed was efficient inventory tracking with persistent storage and notification handling. The application was designed to reduce manual tracking errors and provide immediate visibility into inventory status.


# What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

The application required:

A login screen for secure authentication
An inventory dashboard displaying items in a structured grid
Add and delete item functionality
Quantity tracking and update capability
SMS permission handling screen

The UI was designed with clarity and minimalism in mind. Layout hierarchy was structured logically, ensuring users could navigate intuitively. Clear labels, organized data presentation, and immediate feedback through confirmation messages reduced confusion and improved usability.

The designs were successful because they prioritized workflow efficiency and reduced unnecessary complexity.


# How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?

I approached development incrementally. Rather than implementing all functionality at once, I built and tested one feature at a time.

My techniques included:

Designing the UI before backend implementation
Testing each feature immediately using the Android Emulator
Debugging early and frequently
Keeping classes focused and logically separated
Using meaningful naming conventions and structured comments

This incremental approach prevented integration failures and improved stability. In future projects, especially those involving APIs or cloud services, this method will help manage complexity and maintain code clarity.

# How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

Testing was performed continuously using the Android Emulator.

I verified:

Account creation and login validation
Database persistence after closing and reopening the app
Create, Read, Update, and Delete (CRUD) functionality
SMS permission request behavior
App stability when permissions were denied

Continuous testing is important because it reveals logical errors early. It also ensures that edge cases, such as permission denial, do not compromise core functionality. This process strengthened the reliability of the final application.

# Where did you have to innovate to overcome a challenge?

One of the main challenges was integrating runtime SMS permissions while ensuring that denial of permission did not disrupt core application functionality.

To address this, I separated permission logic from database and authentication operations. This modular approach ensured that inventory management features remained fully functional regardless of SMS permission status.

This required structured conditional handling and reinforced the importance of defensive programming.


# In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

The integration of authentication, SQLite database management, and RecyclerView display was the strongest demonstration of my skills.

This component required:

Designing relational database tables
Writing structured SQL queries
Managing ContentValues and Cursor objects
Updating UI dynamically based on database changes

Successfully integrating these systems demonstrated my ability to build structured, persistent, and user-centered mobile applications.

---

# What This Repository Demonstrates

* User-centered mobile application design
* Authentication system implementation
* SQLite database integration
* CRUD functionality
* Runtime permission handling
* Incremental development practices
* Structured debugging and emulator testing
* Launch planning and deployment awareness

This repository represents competency in building a functional Android application using disciplined architecture and structured development practices.

---

# AI Acknowledgment

Generative AI tools were used to assist in refining written reflections for clarity, organization, and formatting. All technical implementation, architectural decisions, and development work reflect my independent work completed throughout the course.

---
