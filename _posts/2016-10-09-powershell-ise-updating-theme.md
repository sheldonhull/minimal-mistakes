---


title:  "Powershell ISE: Updating Theme"
date: 2016-10-09
tags: ["development","powershell","tech","powershell","cool-tools"]
---

For all the **dark theme aficionados**, or those who just want a better theme than the default, here's a quick set of directions to update your ISE.1. Go to download a theme from [Github > PowerShell_ISE_Themes](http://bit.ly/29DNVu2)
2. Unzip
3. Go to ISE > Tools > Options > Colors & Fonts > Manage Themes
4. Import selected theme
5. For consistency, adjust the `background` and `forecolor` of the `console pane` as well as the `text background` to match if you want to. In my case I took the RGB values from the theme on the `script pane background` and applied to the `console pane` below it.
6. If you want the background for the error, warning, and other output streams to match, update the RGB background as well.

![ISE Color Options](/assets/img/2016-07-13_10-07-40.png)
Your eyes will now thank you, especially if you are jumping from Visual Studio dark theme to ISE with it's previously glaring white screen.

![Powershell Themed](/assets/img/2016-07-13_10-02-58_powershell_ise_themed.png)