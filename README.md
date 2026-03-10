##📖 Bible Study Toolkit

A mobile Bible study app built with React Native and the King James Version (KJV) Bible.
It allows you to:

-View a daily verse

-Search for any verse by text

-Navigate by book → chapter → verse

-Add reading plans, memory training, and notes (future features)

This is a public domain Bible project, perfect for learning, personal use, or open-source contributions.

##⚡ Features

-Daily Verse: Randomly displays a verse each day.

-Verse Search: Search any word or phrase in the entire KJV.

-Navigation: Browse books, chapters, and verses easily.

-Offline Ready: All verses stored locally in JSON.

-Expandable: Easy to add reading plans, memory training, and favorites.

##🛠️ Project Structure
```
Bible-Study-Toolkit
│
├── app
│   ├── data
│   │   └── kjv.json          # Full KJV dataset (31,102 verses)
│   ├── screens
│   │   ├── HomeScreen.js
│   │   ├── SearchScreen.js
│   │   ├── ReadingPlanScreen.js
│   │   └── MemoryScreen.js
│   ├── utils
│   │   └── bible.js           # Bible search & utility functions
│   └── App.js                 # Navigation & main app
│
└── package.json
```
##🚀 Getting Started

Prerequisites

-Node.js ≥ 16

-npm or yarn

-Expo CLI (for React Native)

Install Expo CLI globally:


