# Ball Launcher Game

## Description

This project is a physics-based 2D Ball Launcher game built with Unity. It features a sling-shot mechanic using `SpringJoint2D`, custom despawn/respawn logic, and a multi-platform UI system for mobile and desktop play.

---

## Project Setup

Before you can start the project, ensure you have the following installed:

* **Unity Hub**
* **Unity Editor 2020.2.0f1** (or compatible version)
* **Git LFS** (Highly recommended for tracking large assets)

### 1. Clone the Repository

Open your terminal or command prompt and run:

```bash
$ git clone https://github.com/your-username/ball-launcher.git
$ cd ball-launcher

```

### 2. Open with Unity

1. Open **Unity Hub**.
2. Click **Add** (or **Open**) and navigate to the cloned folder.
3. Select the folder to add it to your project list.
4. Click the project to open it. 
*Note: The first import may take several minutes as Unity generates the `/Library` folder.*

---

## Running the Project

You can run the project directly in the Unity Editor or build it for a specific platform simulator.

### 1. Play in Editor (Windows, Mac, Linux)

* Open the `Scenes` folder in the Project window.
* Double-click `MainMenu.unity`.
* Press the **Play** button at the top of the Editor.

### 2. Local Build Setup

To build the project for a local simulator or executable, follow these steps:

#### Step 1: Configure Build Settings

Go to **File > Build Settings** and select your target platform:

* **Windows/Mac/Linux**: Select `PC, Mac & Linux Standalone`.
* **iOS**: Select `iOS` (Requires a Mac with Xcode).
* **Android**: Select `Android`.

#### Step 2: Switch Platform

If the target platform is not active, click the **Switch Platform** button at the bottom right.

#### Step 3: Build & Run

* **For Desktop**: Click **Build and Run**, select a folder for the build, and the game will launch in a standalone window.
* **For Mobile Simulator**:
1. Go to **Window > General > Device Simulator**.
2. Press **Play** in the editor to test touch inputs on various mobile device profiles.

---
## 🚀 Features

* **Sling-Shot Mechanics:** Interactive dragging using the new Unity Input System.
* **Dynamic Respawning:** Automated ball replacement using C# Coroutines for smooth delays.
* **Physics-Based Gameplay:** Utilizes `SpringJoint2D` and `Rigidbody2D` for realistic motion.
* **Cross-Platform UI:** Designed to work on both Mobile (Touch) and Desktop (Mouse).