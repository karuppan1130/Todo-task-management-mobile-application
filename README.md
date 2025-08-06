# ✅ Todo Task Manager App

A beautifully designed, user-friendly Todo Task Manager App built using **Flutter**.  
This app helps you stay organized with task scheduling, reminders, and customizable statuses — all without needing login or Firebase setup!

---

## ✨ Features

- 🎯 **Add Tasks** with title, target date, and custom status
- ✅ **Mark tasks as completed**
- 🗓️ **Set target deadlines** with a calendar picker
- 📝 **Edit or update status** of any task (`Pending`, `In Progress`, `Completed`)
- ❌ **Delete tasks** with confirmation dialog
- 🎨 **Clean UI** with animations and splash screen
- ⚙️ **Settings panel** with options (About, Reminders, Theme)
- 💾 **Persistent storage** using `shared_preferences`
- 🎥 **Lottie animations** for splash screen and empty state

---

## 📸 Screenshots

> _Add your screenshots here by uploading images to GitHub repo and linking them below:_

```
![Splash Screen](screenshots/splash.png)
![Task List](screenshots/tasks.png)
```

---

## 🚀 Getting Started

### 🧱 Prerequisites

- Flutter SDK (>= 3.8.0)
- Android Studio / VS Code
- Android NDK version: `27.0.12077973`

### 🛠️ Setup Instructions

1. **Clone the repo**

```bash
git clone https://github.com/your-username/todo-task-manager.git
cd todo-task-manager
```

2. **Install dependencies**

```bash
flutter pub get
```

3. **Run the app**

```bash
flutter run -d <your-device-id>
```

(Or choose from the connected devices using `flutter devices`)

---

## 🧱 Project Structure

```
lib/
├── main.dart                # Entry point & splash screen
├── todo_home.dart           # Main task list and UI
├── models/task.dart         # Task model class
├── assets/
│   └── images/todo.jpg      # Background image
│   └── animations/intro.json  # Lottie animation
```

---

## 📦 Dependencies

- [shared_preferences](https://pub.dev/packages/shared_preferences)
- [intl](https://pub.dev/packages/intl)
- [lottie](https://pub.dev/packages/lottie)
- [flutter](https://flutter.dev)

---

## ❤️ Credits

Made with 💙 using **Flutter**  
UI inspired by modern minimalistic task apps.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
