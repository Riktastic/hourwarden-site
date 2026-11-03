---
title: "HourWarden: time tracking per customer, without timers"
description: "HourWarden checks once a second which customer you work for and records the hours. Windows, Linux (KDE Plasma) and Android, in English and Dutch. Sync can be end-to-end encrypted."
hero:
  title: "Your timesheet, filled in while you work"
  text: "HourWarden reads the window in front of you once a second and books the time to the customer it belongs to: by Edge profile, document folder, remote desktop server, mail domain or Teams meeting. On Friday you check the week and copy it as decimal hours."
  shot: "today.png"
  alt: "The HourWarden Today screen, recording time for the fictional customer Northwind Traders"
features:
  - icon: "radar"
    title: "Recognises the customer"
    text: "It matches Edge profiles, folders, file names, mail and web domains, Microsoft tenant IDs, remote desktop and SSH servers, and the participants of Teams meetings. A glance at another window shorter than 10 seconds does not count as a switch."
  - icon: "bar"
    title: "Top bar and screen border"
    text: "A bar at the top of the screen shows the customer and the time since the last switch; the screen border takes the customer's colour. The bar shrinks to a dot with the time, or docks at the left or right edge. Neither takes keyboard focus."
  - icon: "sheet"
    title: "Week, reports and Excel"
    text: "The week view shows hours per customer per day, rounded to 6, 15 or 30 minutes if your customer wants that. Copy week puts decimal hours on the clipboard. Every table exports to CSV and Excel, and the monthly report makes one sheet per customer."
  - icon: "phone"
    title: "Android app"
    text: "The phone shows what the computer is recording and can pause or switch it. It runs a timer for site visits, adds meetings in a few taps, and turns calls from a customer's phone numbers into time."
  - icon: "tasks"
    title: "Tasks, Pomodoro and breaks"
    text: "Time on a task is recorded against its estimate. The Pomodoro timer runs 25 minutes of focus and 5 minutes of rest. After every 20 minutes of keyboard and mouse use it asks you to look 6 metres away for 20 seconds (the 20-20-20 rule)."
  - icon: "lock"
    title: "Window titles stay on your computer"
    text: "Window titles, paths and sites are used on the computer and never sent. Only the resulting hours sync. With end-to-end encryption on, the server stores them encrypted with AES-256 and has no key to read them."
demo:
  title: "Try it in your browser"
  text: "These are the real screens of HourWarden, running on a made-up week with fictional customers. Click around: switch customers, open the week, edit an entry. Nothing is saved, and nothing leaves this page."
  desktop: "Windows and Linux"
  phone: "Android"
  note: "The demo runs in your browser; it forgets everything when you close it."
  fullscreen: "Open it full screen."
security:
  title: "What is stored where"
  points:
    - "All data is in a database on your own computer and phone. Tracking, reports and backups work without internet."
    - "Window titles, file paths and site addresses do not leave the computer. Sync sends customers, tasks and hours."
    - "End-to-end encryption uses AES-256-GCM with a 256-bit key that only your devices hold."
    - "Sign-in supports a second step with any authenticator app. Passwords are stored as Argon2id hashes."
    - "The sync server runs in the EU. You can also run it on your own server with one install script."
    - "No ads, no analytics, no third-party trackers in the app or on this site."
steps:
  title: "Getting started"
  items:
    - "Install HourWarden on Windows 11, or on Linux with KDE Plasma."
    - "The setup guide asks for your customers and their mail domains. You can skip it."
    - "Work as usual. When it cannot tell the customer for 3 minutes, the top bar asks once."
    - "Optional: create an account to sync your laptop, desktop and phone."
cta:
  title: "Try it on your own week"
  text: "The app works on its own without an account. An account adds sync between your devices."
---
