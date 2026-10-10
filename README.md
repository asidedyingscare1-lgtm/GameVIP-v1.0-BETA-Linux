# 🎮 GameVIP v1.0 BETA | Linux

**Unofficial Community Project | Public Beta Testing**

GameVIP v1.0 BETA for Linux is an experimental community application providing a local web-based control panel and network configuration tools for use with a jailbroken PlayStation 4.

This release is intended for public testing, feedback, bug reporting, and continued development.

## ✨ Features

- 🐧 Linux installation and setup
- 🌐 Local web-based control panel
- 🎮 PS4 network configuration support
- ⚙️ Automated dependency installation
- 🔄 ON/OFF control functionality
- 💻 Graphical and headless launch options
- 🛠️ Installation and uninstallation scripts

## 📋 Requirements

- Linux computer with terminal access
- Jailbroken PlayStation 4
- PS4 and Linux computer connected to the same local network
- Internet connection for required dependencies
- Administrator privileges when prompted
- Available network ports required by the application

## 📥 Installation Method 1: GitHub

**Step 1: Clone the repository**

Replace `YOUR-USERNAME` with your GitHub username.

`git clone https://github.com/YOUR-USERNAME/GameVIP-v1.0-BETA-Linux.git`

**Step 2: Enter the project directory**

`cd GameVIP-v1.0-BETA-Linux`

**Step 3: Make the installation scripts executable**

`chmod +x install.sh tap.sh`

**Step 4: Run the installer**

`./install.sh`

### ✅ Expected Installation Behavior

The installer is intended to:

1. Request administrator privileges when necessary.
2. Install required dependencies.
3. Configure and launch the local control panel.
4. Open the web interface in your browser.

**🌐 Local Dashboard:**

http://127.0.0.1:8899/

Once the dashboard opens, turn the application switch **ON** to activate its functionality.

*These steps describe the intended behavior. Successful installation and operation have not yet been independently verified.*

---

## 📦 Installation Method 2: ZIP Archive

If you downloaded the project as a ZIP archive, follow these instructions.

**Step 1: Extract the archive**

`unzip gbt-vip-linux.zip -d gamevip`

**Step 2: Enter the extracted directory**

`cd gamevip`

**Step 3: Make the scripts executable**

`chmod +x install.sh tap.sh`

**Step 4: Run the installer**

`./install.sh`

**Note:** These commands assume the archive contains the installation scripts directly inside the extracted directory. If the ZIP contains another folder, navigate into that folder first.

Once installation completes, open:

http://127.0.0.1:8899/

Turn the application switch **ON**.

---

## 🎮 PlayStation 4 Network Configuration

After launching GameVIP on Linux, you can configure your PS4 to use the DNS address displayed in the application.

### Step 1: Identify the DNS Address

Open the GameVIP dashboard on your Linux computer.

Locate the **PS4 DNS Target** tile.

Example:

`192.168.1.42`

This is an example only. Use the actual IP address displayed by your application.

### Step 2: Configure Your PS4

On your PlayStation 4:

1. Open **Settings**.
2. Navigate to **Network**.
3. Select **Set Up Internet Connection**.
4. Select **Use Wi-Fi**.
5. Choose **Custom**.
6. Continue through the network settings.
7. Select **Manual** for DNS settings.
8. Enter the DNS values shown below.

**Primary DNS:** Your Linux computer's displayed IP address

**Secondary DNS:** `1.1.1.1`

**Proxy Server:** Do Not Use

Complete the remaining network configuration.

### Step 3: Test the Connection

Once your PS4 network settings have been saved:

1. Confirm that GameVIP is running.
2. Verify that the dashboard switch is ON.
3. Test your PS4 network connection.
4. Open the applicable application and check its behavior.

**Important:** GameVIP does not activate a legitimate paid subscription on GameBaTo's servers. Premium access and restricted features are not guaranteed.

---

## 💻 Daily Usage

You do not need to repeat the installation process every time you want to use GameVIP.

### Launch With Desktop Window

`./tap.sh`

Intended to open the application window and local dashboard.

### Launch in Headless Mode

`./tap.sh --headless`

Intended to start the service without its desktop window while keeping the web dashboard available.

**Dashboard URL:**

http://127.0.0.1:8899/

### Turn GameVIP OFF

Open the dashboard and move the switch to **OFF**.

The application is intended to release its use of ports **53** and **80** when disabled.

### Close GameVIP Completely

Close the application's window or open:

http://127.0.0.1:8899/quit

This endpoint is intended to shut down the running application.

---

## 🗑️ Uninstallation

To uninstall GameVIP, open a terminal in the project directory and execute:

`./install.sh --uninstall`

This command is intended to remove components installed by the application's setup script.

Review the script before execution to understand which files and system configurations it changes.

---

## 🐞 Bug Reports & Feedback

GameVIP is currently in public beta testing.

If you encounter problems, please report them through GitHub Issues or the appropriate development and bug-reporting channels in our Discord community.

When reporting an issue, include:

- Linux distribution and version
- GameVIP application version
- PS4 firmware version, if applicable
- Description of the problem
- Steps needed to reproduce the issue
- Error messages or relevant logs
- Screenshots when available

---

## 🚀 Development Status

**Version:** 1.0 BETA

**Platform:** Linux

**Development Stage:** Public Testing

**Status:** Experimental

Future development will focus on resolving reported problems, improving compatibility, strengthening security, and improving the overall user experience.

## 💜 Community Support

Thank you to everyone participating in public testing and helping improve GameVIP.

Your bug reports, suggestions, and feedback are appreciated.

**GameVIP Development 
