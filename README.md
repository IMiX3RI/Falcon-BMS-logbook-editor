# Standalone Logbook (.lbk) Editor for Falcon BMS

This standalone editor, built on the Electron platform, allows for quick and easy modification all statistics and data within the Logbook files (.lbk) used by the Falcon BMS flight simulator.

The application safely encrypts and decrypts the logbook file using the original XOR logic and password masking key, allowing you to edit data without the risk of file corruption.

Features

- Full Key Support: Reads and writes all major fields, including Flight Hours, Rank, Dogfight/Combat Records, and Medal statistics.

- Security: Utilizes the original XOR encryption/decryption algorithm implemented by Falcon BMS.

- Ease of Use: Simple, user-friendly interface powered by Electron.

# How to Use (Download and Run)
Step 1: Download the Application

The application is distributed as an Electron package for Windows and does not require installation.

    Go to the [Releases] section on GitHub. (Replace this link with your actual releases page.)

    Download the latest package (e.g., Falcon.BMS.logbook.editor.rar).

Step 2: Run

    Unzip the downloaded folder (e.g., Falcon.BMS.logbook.editor.rar).

    Run the executable file inside the folder (e.g., falcon-bms-logbook-editor.exe).

Step 3: Edit the Logbook

    Open File: Click the "Load .lbk File" button and navigate to your .lbk file (Falcon BMS 4.38\User\Config\___.lbk).

    Edit Data: Modify the statistical and text fields, such as you want.

    Save: Click "Save .lbk File". The editor will overwrite the existing file (or prompt for a new location if you loaded a backup).
