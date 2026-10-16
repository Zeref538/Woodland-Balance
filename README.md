# Woodland Balance

A two-player woodland balance scene based on the supplied sketch. Project preparation is in progress; the playable scene is not yet complete.

## Clone on the Mac lab

Open Terminal and run:

```bash
cd ~/Desktop
git clone https://github.com/Zeref538/Woodland-Balance.git
cd Woodland-Balance
```

## Get the latest changes

Close Unity before updating project files. In Terminal:

```bash
cd ~/Desktop/Woodland-Balance
git pull --ff-only
```

This downloads changes and applies them if your branch can advance directly. If you have edited the same files locally, save or commit your work before updating; do not discard it.

To download and inspect changes without applying them yet:

```bash
git fetch origin
git log --oneline HEAD..origin/main
```

Apply the fetched changes when ready:

```bash
git merge --ff-only origin/main
```

## Artwork only

The separate artwork repository is [Woodland-Scouts](https://github.com/Zeref538/Woodland-Scouts). Its smaller frame ZIP avoids downloading a Unity project when only sprites are needed.

## Supplied script

CharacterController2DP2.cs is preserved unchanged. John authorized a separate input script for this assignment. The intended lab editor is 6000.2.2f1; that version is not yet installed on the home PC.
