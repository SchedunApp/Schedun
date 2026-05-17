# Schedun
The official repository for the Schedun app. Downloading it is free, using it is paid

## ⚠️ Important Disclaimer

*   **Antivirus False Positive:** Windows Defender might flag the `.exe` file as **Trojan:BadJoke**.
*   **Why is this happening?** The application code is heavily encrypted to protect intellectual property and does not have an expensive official digital signature. Since Windows cannot "look inside" the encrypted file, it takes the safest route and flags it.
*   **Safety:** The application is **100% safe and virus-free**. The file has been thoroughly scanned with **Kaspersky**, and no threats were found. You can safely add an exclusion/exception for the app in Windows Defender, or just simply choose no action taken when prompted. All files used by this project can be obtained legally.

## 📋 Instructions & Setup Guide

### Step 1: Windows 11 Compatibility (Critical!)
> [!WARNING]
> **IF YOU ARE USING A WINDOWS 11 DEVICE:** Before running the app for the first time, make sure **"WMIC"** is enabled in your Windows Optional Features.

The application binds your license key to your computer's unique hardware ID using WMIC. If this feature is missing, your license activation might break!
*   **How to enable it:** Open Windows Search -> Type *Optional features* (Választható funkciók) -> Settings.
*   Search for **WMIC** in the list and ensure it is installed/enabled.

### Step 2: License Activation
When you receive your license key, **make sure to enter it on your own primary computer**. The moment you activate it, the license binds to that specific hardware. You will not be able to use the same key on a different device later (e.g., a friend's laptop or a university computer).

### Step 3: Importing Neptun Data (The "Exports" Folder)
To use any of the core functions (Teacher Search, Student Search, Schedule Planner), you need to place your exported Excel files from Neptun into the correct folders. Downloading these files are to be done by the users themselves, however I'm working on a method to make this process easier.

Create a folder named **`Exports`** in the exact same directory as your `.exe` file, and set up the following folder structure:

```text
📂 [Your Application Folder]
 ┣ 📄 Schedun.exe
 ┗ 📂 Exports
     ┣ 📂 Teacher   <-- Excel files for Teacher search
     ┣ 📂 Students  <-- Excel files for Student search
     ┗ 📂 Schedule  <-- Excel files for Schedule planning
```
