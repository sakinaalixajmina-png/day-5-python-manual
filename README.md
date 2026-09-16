 # Day 5 Assignment: User Manual Procedure

## Task: Creating and Activating a Python Virtual Environment and Installing a Package
**Audience:** First-semester computing student with basic computer literacy but no prior experience using Python virtual environments.

### 1. Prerequisites
Before starting this procedure, ensure you have completed the following setup requirements:
* A computer running Windows 10 or 11.
* **Python 3.12** installed on your system.
* The system environment variable **PATH** configured to include Python during your initial installation.
* An active internet connection to download software packages.

---

### 2. Step-by-Step Procedure

1. Open your Windows Start menu, type **`cmd`**, and press **Enter** to open the Command Prompt terminal.
   * *Expected Result:* A black terminal window opens displaying your user profile directory path (e.g., `C:\Users\YourName>`) with a blinking cursor.

2. Type **`cd Desktop`** into the terminal and press **Enter** to navigate your workspace directory to the desktop.
   * *Expected Result:* The directory prompt changes to end with `\Desktop>`, showing you are successfully inside your desktop folder.

3. Type **`python -m venv my_env`** and press **Enter** to create your isolated environment folder.
   * *Expected Result:* The terminal pauses for a few seconds and then displays a fresh, empty command prompt line. 

4. **[Screenshot Note]**
   * *Terminal Status:* At this point, the user should see a new folder named `my_env` appear on their desktop workspace without any terminal errors displayed.

5. Type **`my_env\Scripts\activate`** and press **Enter** to turn on the virtual environment workspace.
   * *Expected Result:* The prefix `(my_env)` appears in parentheses at the very beginning of your terminal command line prompt.

6. Type **`pip install requests`** and press **Enter** to install an external code package named "requests".
   * *Expected Result:* White progress bars fill across the screen showing the package downloading, followed by a status message stating: `"Successfully installed requests"`.

---

### 3. Troubleshooting Note
* **Common Beginner Error:** You type `my_env\Scripts\activate` in Step 5 and receive an error message that says: *"Script execution is disabled on this system"* or nothing changes.
* **Solution:** This happens because Windows has a security block on running terminal scripts. To fix this, close your current window, search for "Command Prompt" in your Windows menu again, right-click its icon, select **Run as administrator**, and attempt the command sequence again.
