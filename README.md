# ⚡ Keystride --- Typing Practice & Skill-Building App

> **Master the rhythm of typing.**

Keystride is a browser-based typing practice application designed to
help users build touch-typing skills through structured lessons, guided
drills, timed typing tests, mini-games, progress tracking, achievements,
and a personalized completion certificate.

The supplied project is implemented as a **single `index.html` file**
using HTML, CSS, and vanilla JavaScript, with browser `localStorage`
used for profile and progress persistence.

------------------------------------------------------------------------

## 📸 Screenshots

### 1. Welcome & Profile Selection

![Keystride Welcome Screen](screenshots/welcome.png)

Users can create/select a local profile and continue their typing
journey with saved progress.

### 2. Study / Course Dashboard

![Keystride Study Course](screenshots/study-course.png)

The Study section provides a structured typing course with lesson
navigation, progress tracking, daily practice goals, and course-duration
controls.

### 3. Guided Drill Practice

![Keystride Drill Practice](screenshots/drill-practice.png)

The drill interface provides highlighted keys, on-screen keyboard
guidance, hand/finger hints, live WPM, accuracy, correct/error counts,
restart, finish/save, and course navigation.

### 4. Timed Typing Test

![Keystride Typing Test](screenshots/typing-test.png)

Users can choose a test duration and measure typing speed and accuracy
with live statistics.

### 5. Typing Games

![Keystride Games](screenshots/games-menu.png)

Keystride includes multiple mini-games for practicing typing in a more
interactive way.

### 6. Space Shooter Game

![Keystride Space Shooter](screenshots/space-shooter.png)

The Space Shooter game combines keyboard input with arcade-style
gameplay, score tracking, lives, and a countdown timer.

### 7. Statistics & Progress

![Keystride Statistics](screenshots/statistics.png)

The Statistics section tracks typing performance with best/average WPM,
accuracy, gross speed, net speed, history, and progress information.

### 8. Settings

![Keystride Settings](screenshots/settings.png)

Users can customize sound, theme, daily practice goal, keypress sound
style, color theme, text size, and other practice preferences.

### 9. About Keystride

![Keystride About](screenshots/about.png)

The About page introduces Keystride and summarizes its core learning
features.

### 10. Certificate of Completion

![Keystride Certificate](screenshots/certificate.png)

After completing **all 12 lessons**, Keystride unlocks a personalized
**Certificate of Completion** containing the learner's name, completion
date, best WPM, best accuracy, and skill level. The certificate can be
**printed or saved as a PDF**.

------------------------------------------------------------------------

## ✨ Features

### 🎓 Structured Typing Course

Keystride provides a 12-lesson learning path:

1.  Home Row
2.  Upper Row
3.  Lower Row
4.  Right Hand Bottom
5.  Full Alphabet
6.  Common Words
7.  Capital Letters
8.  Numbers
9.  Symbols
10. Full Keyboard
11. Advanced Words
12. Speed Challenge

The course is designed to progressively move from keyboard fundamentals
toward speed and accuracy practice.

### ⌨️ Guided Typing Drills

-   Real-time WPM
-   Accuracy tracking
-   Correct and error counts
-   Highlighted target keys
-   On-screen keyboard
-   Hand/finger guidance
-   Backspace correction
-   Restart option
-   Finish & Save
-   Return to course

### ⏱️ Typing Tests

Available test durations include:

-   1 minute
-   2 minutes
-   5 minutes
-   Custom duration

Typing tests provide performance measurements such as WPM, accuracy,
correct characters, and errors.

### 🎮 Typing Games

Keystride includes 8 typing mini-games:

-   🫧 Bubbles
-   🧱 WordTris
-   ☁️ Clouds
-   🏁 ABC Speed Race
-   🟩 Pipe Game
-   🏎️ Cloud Race
-   👻 Ghost Hunter
-   🚀 Space Shooter

### 📊 Statistics & Progress Tracking

The application tracks:

-   Best WPM
-   Average WPM
-   Best accuracy
-   Gross speed
-   Net speed
-   Accuracy history
-   Test history
-   Lesson history
-   Total practice time
-   Typed characters
-   Daily practice goal
-   Progress charts
-   Printable Progress Report

### 🏆 Gamification

Keystride includes:

-   XP
-   User levels
-   Practice streaks
-   Daily goals
-   Achievement badges
-   Personal-best feedback
-   Course completion progress

### 🎓 Certificate of Completion

A certificate is unlocked when the learner completes **all 12 course
lessons**.

The certificate includes:

-   Learner name
-   Completion date
-   Best WPM
-   Best accuracy
-   Skill level
-   Keystride branding/signature
-   Print / Save as PDF option

### 👤 Local Profiles

Users can:

-   Create profiles
-   Select saved profiles
-   Delete profiles
-   Continue with previously stored progress

Profile and progress information is persisted locally in the browser.

### ⚙️ Customization

Settings include options for:

-   Sound on keypress
-   Dark/light mode
-   Daily practice goal
-   Keypress sound style
-   Accent/color theme
-   Text size
-   Resetting progress

### 📱 Responsive Interface

The UI is designed to adapt across different screen sizes, with
responsive layouts for the main learning and practice screens.

------------------------------------------------------------------------

## 🛠️ Tech Stack

  Technology                 Purpose
  -------------------------- -----------------------------------------
  **HTML5**                  Application structure
  **CSS3**                   Layout, styling, themes, responsive UI
  **JavaScript (Vanilla)**   Application logic and interactions
  **localStorage**           Local profile and progress persistence
  **Google Fonts**           Certificate typography / visual styling

No frontend framework is required for the supplied version.

------------------------------------------------------------------------

## 🚀 How to Run

The supplied Keystride version is a client-side browser application, so
no Node.js installation or backend server is required.

### Option 1 --- Open directly

1.  Download or clone the project.
2.  Open the project folder.
3.  Double-click `index.html`.
4.  Keystride will open in your browser.

### Option 2 --- VS Code

1.  Open the project folder in VS Code.
2.  Open `index.html`.
3.  Run it in your browser.
4.  Start by creating or selecting a profile.

------------------------------------------------------------------------

## 🧭 How to Use

### Step 1 --- Create or Select a Profile

Choose **New user** to create a profile, or select an existing saved
profile.

### Step 2 --- Start the Course

Open **Studying** and begin the structured typing lessons.

### Step 3 --- Practice Drills

Complete guided drills while following the highlighted keyboard keys and
finger guidance.

### Step 4 --- Take Typing Tests

Use **Typing Test** to measure speed and accuracy under timed
conditions.

### Step 5 --- Play Typing Games

Use the games section to practice typing through interactive challenges.

### Step 6 --- Track Your Progress

Open **Statistics** to review speed, accuracy, history, practice time,
and other progress information.

### Step 7 --- Complete All 12 Lessons

Finish the complete course to unlock the certificate.

### Step 8 --- Get Your Certificate

Open the certificate after course completion and use **Print / Save as
PDF** to keep a copy.

------------------------------------------------------------------------

## 🏗️ Project Structure

``` text
Keystride/
│
├── index.html
├── README.md
│
└── screenshots/
    ├── 01-welcome.png
    ├── 02-study-course.png
    ├── 03-drill-practice.png
    ├── 04-typing-test.png
    ├── 05-games-menu.png
    ├── 06-space-shooter.png
    ├── 07-statistics.png
    ├── 08-settings.png
    ├── 09-about.png
    └── 10-certificate.png
```

> The screenshot files in this README package are the real screenshots
> supplied for the project.

------------------------------------------------------------------------

## 🧠 Application Architecture

The supplied project keeps the main application in a single HTML
document:

-   **HTML** --- page structure and UI components
-   **CSS** --- themes, layout, cards, controls, game screens,
    certificate styling, and responsive behavior
-   **JavaScript** --- navigation, lessons, drills, tests, games,
    statistics, profiles, settings, XP, streaks, achievements, and
    certificate logic
-   **localStorage** --- local persistence of user/profile and progress
    data

This makes the supplied version easy to run and suitable for a
lightweight browser-based project.

------------------------------------------------------------------------

## 🔐 Data & Privacy

Keystride's supplied implementation stores profile/progress information
locally in the browser using `localStorage`.

There is no required external application backend in the supplied
version.

Because the data is stored locally, clearing browser storage can remove
saved local profiles and progress.

------------------------------------------------------------------------

## 🎯 Portfolio Highlights

Keystride demonstrates practical frontend development concepts
including:

-   Interactive single-page application behavior
-   DOM manipulation
-   Event handling
-   Keyboard-event processing
-   Typing-speed calculations
-   Accuracy/error tracking
-   Timed activities
-   Game-state handling
-   Local data persistence
-   Progress dashboards
-   Gamification
-   Responsive UI design
-   Theme/settings management
-   Dynamic certificate generation
-   Print/PDF-friendly certificate output

------------------------------------------------------------------------

## 🧪 Testing Checklist

Before publishing or demonstrating the project, verify:

-   [ ] New profile can be created
-   [ ] Existing profile can be selected
-   [ ] Profile deletion works
-   [ ] Course lessons open correctly
-   [ ] Drill accepts keyboard input
-   [ ] Correct/error counts update
-   [ ] WPM and accuracy update
-   [ ] Typing tests start and finish correctly
-   [ ] All games open correctly
-   [ ] Game scores/timers behave correctly
-   [ ] Statistics update after practice
-   [ ] Settings are saved
-   [ ] Dark/light mode works
-   [ ] Progress reset works as expected
-   [ ] All 12 lessons can be completed
-   [ ] Certificate unlocks after completing all 12 lessons
-   [ ] Certificate shows the correct learner name
-   [ ] Certificate shows completion details
-   [ ] Print / Save as PDF works

------------------------------------------------------------------------

## 🔮 Future Enhancements

Possible future improvements:

-   Cloud account synchronization
-   Online leaderboards
-   User authentication
-   Backend database
-   More typing courses
-   More advanced typing games
-   Multiplayer typing races
-   Exportable performance reports
-   Teacher/admin dashboard
-   More certificate templates
-   Keyboard-layout selection
-   Detailed per-key accuracy analytics

------------------------------------------------------------------------

## 👨‍💻 Author

**Ankit Kumar**

Built as a typing-practice and skill-development web application.

------------------------------------------------------------------------

## 📄 License

It is created for **educational purposes only**. Feel free to use the code to learn. A credit or a star ⭐ to this repository would be highly appreciated!


------------------------------------------------------------------------

## ⭐ Support

If you find Keystride useful, consider giving the repository a ⭐ on
GitHub and sharing feedback or feature ideas.

------------------------------------------------------------------------

## 📌 Project Summary

**Keystride** is more than a basic typing test. It combines:

**Structured Lessons + Guided Drills + Timed Tests + Typing Games +
Statistics + Gamification + Certificate of Completion**

to create a complete browser-based typing practice experience.
