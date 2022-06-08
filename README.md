Code for the fifth independent project for Android Basics in Kotlin. This project pairs
with Unit 5 of Android Basics in Kotlin

The Forage app allows users to keep track of items, food for example, that they've foraged for in nature. This data is persisted between sessions using Room.

When the app is first launched, the user is presented with an empty screen containing a recycler view that will display foraged items, as well as a floating button in the bottom right corner to add new items.

When adding a new item, the user can specify a name, the location where it was found, as well as some additional notes. There's also a checkbox for whether or not the food item is currently in season.

Once an item has been added, it will appear in the recycler view on the first screen.

Tapping an item leads to a detail screen which shows the name, location, and notes.

The floating button also changes from a plus symbol to an edit icon. Tapping this button leads to a screen that lets you edit the name, location, notes, and "in season" checkbox. Tapping the delete button will remove the item from the database.
