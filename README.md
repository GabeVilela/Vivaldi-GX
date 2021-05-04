# Vivaldi-GX
A custom UI mod for Vivaldi Browser, based on Opera GX<br>
***DISCLAIMER: This mod wasn't developed and/or approved by either Opera Norway AS, or Vivaldi Technologies***
***
## How to install?
1. **Enable CSS modifications** *(You need to do this only once)*</br>
Go in `vivaldi://experiments` and check `Allow for using CSS modifications`
2. **Download the mod**</br>
In this page, click on `Releases`, select a version and download its `Source code (zip)`<br>
3. Extract the `Mod` folder to anywhere safe on your PC
4. Open Vivaldi Settings > Apperance and in "Custom UI Modifications", select that `Mod` folder
5. Restart Vivaldi (you can easily do this by going in `vivaldi://restart`)

**Note: Depending on your current Vivaldi theme, you might need to change its colors for a better look.<br/>
Check the file `list of preset themes.md` if you want some inspiration.**

## How to inspect the UI
- Open `vivaldi://inspect/#apps`<br>
There should be listed every Vivaldi window you have open, with its tabs, in a "tree style" view.
- Look for the window you want to use as test subject (Vivaldi windows are named `Vivaldi` with its url being `chrome-extension://<something>/browser.html`).
- Hit `Inspect` under "Vivaldi"<br>
This will open the Dev tools, inspecting the UI
