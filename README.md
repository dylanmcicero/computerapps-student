# Computer Applications — Student Downloads

**Offline IT learning and simulated practice labs for Windows.**

This is the **student download page**, separate from the private classroom development repository. 

> **Status: Windows release in preparation.** The first tested download has not been published yet. There is no EXE to download at this time.

## How to install (once the first release is available)

1. Open the **[Releases](https://github.com/dylanmcicero/computerapps-student/releases)** page.
2. Select the latest Windows release and download `ComputerApplications-Windows-x64.zip`.
3. Right-click the ZIP → **Extract All**. Keep the contents together; do **not** move the EXE out of its folder.
4. Open the extracted `ComputerApplications` folder and double-click `ComputerApplications.exe`.
5. Your normal browser will open with the lessons. Keep the small **Computer Applications** launcher window running while you work; close it with **Stop and exit**.

**Requirements:** Windows 10/11 x64, a web browser, and permission to run a downloaded application. Internet access is only needed to download the ZIP; the training app runs offline.

**No account, Python, Docker, administrator installation, or access to the classroom network is required.** The app serves lessons to your own computer at `http://127.0.0.1:8874/`. It does not provide remote access to your computer or connect to the school's Getac server.

## How progress works

Lesson progress is stored locally by your browser. To keep it, use the same browser profile and do not clear site data for `127.0.0.1`. Progress **does not automatically transfer** between your home computer and the classroom version, and it is not an official grade.

## Problems starting?

- Make sure you **extract the entire ZIP** before running the EXE.
- Leave the `_internal` directory alongside `ComputerApplications.exe` in the extracted folder.
- If you see a Windows security warning or an organizational policy block, **do not bypass your institution's policy**. Ask your instructor for an approved option.
- Only one copy can run at a time; close the previous launcher if the local port is already in use.
- Do not download or run executables from unofficial mirrors.

## For instructors and maintainers

The portable Windows application is built and tested from a separate private development repository. Only an approved versioned ZIP and checksum are published as public release assets. Source code, classroom-specific deployment files, SPOT, personal or student records, and third-party commercial audio are not part of this distribution.

This software uses simulated systems for practice; exercises do not provide access to a real remote machine.
