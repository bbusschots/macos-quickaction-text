# MacOS Quick Action Text Utilities
A collection of Mac OS Quick Actions (Services) for manipulating text.

## Installation

Each quick action is included as a ZIP file under `Services`. Extract the ZIP file and double-click to install. Or, extract the ZIP file and copy the workflow into `~/Library/Services`.

## Text Replacement Utilities

These quick actions are available when text is selected in any app. Once you have the text selected, either right-click on the selection to access the services menu, or, use the `Services` sub-menu under the app's main menu (the app's name in the menubar). The selected text will be replaced with the altered version.

The following services are provided:

* **Selection to lower case** — converts the selection to lower case, e.g. `HELLO WORLD!` → `hello world!`
* **Selection to Title Case** — converts the selection to Title Case, e.g. `hello world!` → `Hello World!`
* **Selection to Upper Case** — converts the selection to UPPER CASE, e.g. `hello world!` → `HELLO WORLD!`

## Text Measurement Utilities

These quick actions are available when text is selected in any app. Once you have the text selected, either right-click on the selection to access the services menu, or, use the `Services` sub-menu under the app's main menu (the app's name in the menubar). The result of the measurement will be displayed using a MacOS Notification.

The following services are provided:

* **Count Characters** — generates a notification with the number of characters in the selection. Accented characters like `é` count as a single character, as do emoji.
* **Count Words** — generates a notification with the number of words in the selection. The service uses the terminal command `wc -w` to perform the calculation.
* **Count Lines** — generates a notification with the number of lines in the selection. The service uses the terminal command `wc -l` to perform the calculation.

## Clipboard Manipulation Utilities

These quick actions are available in any app at any time from the `Services` sub-menu under the app's main menu (the app's name in the menubar).

* **Clipboard to lower case** — replace the contents of the clipboard with the current contents converted to a string and then converted to lower case.
* **Clipboard to Title Case** — replace the contents of the clipboard with the current contents converted to a string and then converted to Title Case.
* **Clipboard to UPPER CASE** — replace the contents of the clipboard with the current contents converted to a string and then converted to UPPER CASE.
* **Clipboard to Plain Text** — replace the contents of the clipboard with the current contents converted to an un-styled (plain text) string.
* **Trim Clipboard** — replace the contents of the clipboard with the current contents converted to string with all leading and trailing white space removed.