# Simple Chat App Meteor

A very simple chat app is written by MeteorJS + React + Tailwind to prove that MeteorJS is still working with the newest frontend techs and simple to build a real-time application

<img width="1030" alt="Screen Shot 2023-09-09 at 14 46 48" src="https://github.com/vanbui1995/chat-app-meteor/assets/47735787/aca36489-8e6d-4cf3-a498-3d7112598cec">
Demo link: https://chat-app-2023-vanbui.au.meteorapp.com


### How to run it locally

1. Make sure you are on NodeJS version 14 (recommended by MeteorJS)
2. Install meteor
    ```
    npm install meteor -g
    ```
3. Install dependencies & start locally
    ```
        meteor npm install
        meteor
    ```
### Feature
- Loggin, Loggout
- Manage DM Conversations
- Send message
- Unread count
- Notifications

### Folder structure

    .
    src
    ├── ...
    └── server/main.tsx           # Backend entry point file (Root)
    ├── imports                   # Contain all main pages, the root component of each page
    │   ├── ui/*                  # All frontend source code
    │   ├── api/collections/*     # Define all collection schema
    │   ├── api/methods/*         # Define all Meteor methodss (APIs)
    │   └── api/publications/*    # Define all Meteor publications (backend realtime)
    │   └── api/job-handlers/*    # Define all jobs on the backend side
    └── tailwind.config.cjs       # Tailwind config, I configured all colors/spacing of the guideline via this file
    

