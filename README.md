# MacOS Quick Action Text Utilities
A collection of Mac OS Quick Actions (Services) for manipulating text.

## Included Quick Actions

### Text Replacement Utilities

These quick actions are available when text is selected in any app. Once you have the text selected, either right-click on the selection to access the services menu, or, use the `Services` sub-menu under the app's main menu (the app's name in the menubar). The selected text will be replaced with the altered version.

The following services are provided:

* **Selection to lower case** — converts the selection to lower case, e.g. `HELLO WORLD!` → `hello world!`
* **Selection to Title Case** — converts the selection to Title Case, e.g. `hello world!` → `Hello World!`
* **Selection to Upper Case** — converts the selection to UPPER CASE, e.g. `hello world!` → `HELLO WORLD!`

### Text Measurement Utilities

These quick actions are available when text is selected in any app. Once you have the text selected, either right-click on the selection to access the services menu, or, use the `Services` sub-menu under the app's main menu (the app's name in the menubar). The result of the measurement will be displayed using a MacOS Notification.

The following services are provided:

* **Count Characters** — generates a notification with the number of characters in the selection. Accented characters like `é` count as a single character, as do emoji.
* **Count Words** — generates a notification with the number of words in the selection. The service uses the terminal command `wc -w` to perform the calculation.
* **Count Lines** — generates a notification with the number of lines in the selection. The service uses the terminal command `wc -l` to perform the calculation.

### Clipboard Manipulation Utilities

These quick actions are available in any app at any time from the `Services` sub-menu under the app's main menu (the app's name in the menubar).

* **Clipboard to lower case** — replace the contents of the clipboard with the current contents converted to a string and then converted to lower case.
* **Clipboard to Title Case** — replace the contents of the clipboard with the current contents converted to a string and then converted to Title Case.
* **Clipboard to UPPER CASE** — replace the contents of the clipboard with the current contents converted to a string and then converted to UPPER CASE.
* **Clipboard to Plain Text** — replace the contents of the clipboard with the current contents converted to an un-styled (plain text) string.
* **Trim Clipboard** — replace the contents of the clipboard with the current contents converted to string with all leading and trailing white space removed.

## Installation

Each quick action is included as a ZIP file in this repository's `Services` folder. Extract the ZIP file and double-click to install. Or, extract the ZIP file and copy the workflow into `~/Library/Services`.

## Using the Quick Actions

### Via Right-Click on Text Selection

The Quick Actions that alter or measure selected text can be accessed by right-clicking on a text selection in any app and expanding the *Services* menu.

![Screenshot showing Quick Actions in right-click menu on text selection](/screenshots/Services%20via%20Right%20Click%20on%20Text%20Selection.png?raw=true)

### Via Menu Bar

The Quick Actions that alter the clipboard are primarily accessed via the *Services* sub-menu in any app's main menu (the first item in the Menu Bar after the Apple logo, i.e. the one with the same name as the app itself). If there is currently text selected within the app, then the text selection services will show in this menu too.

![Screenshot showing Quick Actions in main menu](/screenshots/Services%20via%20Menu%20Bar.png?raw=true)

## Assigning Shortcut Keys

Assigning shortcut keys can be particularly useful for the Quick Actions that alter the clipboard contents. Shortcuts can be registered for any Quick Action via the *Shortcuts* tab in the *Keyboard* preference pane in *System Preferences*. You'll find the Quick Actions listed under *Services* in the left side-bar. With *Services* selected in the left side bar you'll find the Quick Actions that alter or measure selected text under *Text* in the primary panel, and the actions for altering the clipboard contents under *General*.

![Screenshot showing the Shortcuts tab of the Keyboard System Preference Pane](/screenshots/Keyboard%20Shortcuts.png?raw=true)