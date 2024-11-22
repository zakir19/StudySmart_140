
**StudySmart** is an Android application designed to help users manage their study sessions efficiently. Built using **Jetpack Compose**, **Room**, and **Android Services**, the app allows users to plan their study hours, create tasks, and track their progress. It also includes features to set reminders and cancel tasks after completion.

## Features

- **Track Study Hours**: Set the number of hours you want to study for each subject.
- **Task Management**: Add your own tasks, set deadlines, and mark them as complete once done.
- **Task Cancellation**: Cancel ongoing tasks whenever you need to.
- **Timer Service**: Use the built-in timer to keep track of your study sessions using Android Services.
- **Persistent Storage**: Study hours, tasks, and related data are stored locally using **Room** Database.

## Tech Stack

- **Jetpack Compose**: UI toolkit to build native UIs with a declarative approach.
- **Room**: SQLite-based database for persistent data storage.
- **Android Services**: To run tasks like study timers in the background.
- **Kotlin**: The primary language used for the app.


## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/zakir19/StudySmart_140.git
    ```

2. Open the project in **Android Studio**.

3. Sync the Gradle files and build the project.

4. Run the app on an emulator or real device.

## How to Use

1. **Set Study Hours**:
    - From the main screen, select the subject you want to study.
    - Input the number of hours you plan to study for that subject.

2. **Create a Task**:
    - Go to the "Tasks" section and add a task by entering its description and deadline.
    - Once added, the task will be listed, and you can view or edit it.

3. **Start Study Timer**:
    - Start the timer for a subject and track how much time you have spent studying.

4. **Cancel a Task**:
    - If you wish to cancel a task, simply click on the task in the "Tasks" section and press "Cancel."

5. **View Task Completion**:
    - Once your task is completed, you can mark it as done or remove it from the list.

- I have attach the drive link in that the video is shown how the app is work. 
- https://drive.google.com/drive/folders/1GV6vR-0Ku8Uh_dNasmmXN5HbBYv4oPcm?usp=drive_link



### 1) Landing Page
![Landing Page](res/drawable/landing%20page.jpg)
The landing page is the initial screen of the app where users can navigate to add subjects, view tasks, and start study sessions.

### 2) Add/Update Subject
![Add/Update Subject](res/drawable/landing%20page%201.jpg)
Here, users can add new subjects or update existing subjects to keep track of their study goals.

### 3) Create Task
![Create Task](res/drawable/Create-of-task.jpg)
This screen allows users to create study tasks for each subject, setting time limits and task descriptions.

### 4) Add Task
![Add Task](res/drawable/Add-Task.jpg)
This section enables users to add specific tasks for their study sessions, ensuring they stay organized.

### 5) Completion of Task
![Completion of Task](res/drawable/Completion-of-task.jpg)
Once a task is completed, users can view their progress and mark the task as finished.

### 6) Delete Subject
![Delete Subject](res/drawable/Delete-subject.jpg)
Users can remove subjects they no longer want to track, keeping their study plans organized.

### 7) Study Session Timer
![Study Session Timer](res/drawable/Study-session-timer.jpg)
The study session timer helps users manage their study sessions, ensuring they stay focused within a set period.

---

