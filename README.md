# Unity Persian Support
This is a project for writing Persian (right to left) text in a UI Text in the Unity3d
# Why this project?
There are a lot of package available for writing right to left string inside a UI Text however most of them can not do their job when Unity3d wrap a long string in order to fit inside the UI Text. By using this project, a long right to left string can be inserted to a UI Text in the correct layout.
# How to use?
- Insert [UnityPersianSupport.dll](bin/Debug/) to your Unity3d project.
- yourUIText.text= FixMultiline(yourString,yourUIText);
