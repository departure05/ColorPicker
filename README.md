# ColorPicker
A color picker for Directory Opus 13
This script add-in lets you pick the color currently under the mouse anywhere on the screen.

[](https://resource.dopus.com/uploads/default/original/3X/6/b/6b9489e5a5e21b76e78a300f601ec1f8e1e3dfe1.mp4)



### **Requirements**

* Directory Opus 13.22.5 or higher.
* Windows 10 1803 or higher.

---

### **Installation**

[Download the installer from here](https://github.com/departure05/ColorPicker/releases/download/latest/ColorPickerInstaller.exe)

Then install it.

---

### **Usage**

Simply use `ColorPicker` to open the dialog. Use `ZOOM=2|4|8|16|32|64` to start with a specific zoom.
By default, the dialog ignores its own window area.
You can press <kbd>F8</kbd> to resume/pause the dialog.
Press <kbd>F6</kbd> to save a color to the list.
Double click a color in the list to show more extended info.

In the extended info window, you can choose other colors to view its data as well. And also save them to the list.

---

### **Notes**

* The script runs a local server for communication, so your security software may ask for network access permission (the script itself never accesses the internet).
* Doesn't run constantly in background, once is not needed, the server will auto close.
* Color names comes from the Go library. You can choose which one to use in the Options dialog.
* When copying hex values, you can choose whether to include or not the `#` char. Configurable in Options.

---

### **Copyright/Greetings**

Feel free to use it.

The GO helper uses the following third parties libraries:
* `github.com/muesli/gamut`
