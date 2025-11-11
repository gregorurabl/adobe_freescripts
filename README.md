# adobe_freescripts
Tools, Snippets and little helpers I created on the way while building larger stuff. Mostly ExtendScript Stuff for Adobe Photoshop and After Effects . I'm not actively working on most of these and won't make updates or bugfixes on a regular basis. But feel free to contact me if you find any bugs or have a request for a feature: https://www.gregorurabl.at/kontakt <br><br>If you like to support me buy one of my larger scripts: https://aescripts.com/authors/gregor-urabl (currently only "Advanced Selection", but more coming soon). <br><br>Licensed under the “Free License – No Resale” by Gregor Urabl (https://gregorurabl.at). Credits are not required but very appreciated - thank you - share the open source spirit! I'm in no way affiliated with Adobe, just coding what I need for myself while working with their software.

# The Scripts in Detail

## Expression Baker
${\color{purple}Adobe \space After \space Effects}$

☑ Dockable

A little tool to batch bake expressions fur multiple compositions at once. 

<details>
  <summary>Click to see Screenshots</summary>
<br><img width="161" height="170" alt="grafik" src="https://github.com/user-attachments/assets/e0d6d5ec-26ca-47ad-90ef-34631f139d8a" /><br>
<img width="739" height="612" alt="grafik" src="https://github.com/user-attachments/assets/7318fd98-187b-4606-a360-270105b5d75a" /><br>
</details>

**How to use:** 
1. Select compositions and hit the button.
2. Expression Baker copies these compositions to a new folder, samples the frames of all expressions in all selected compositions and removes the expressions afterwards.
3. The original compositions remain unaffected.
4. Don't touch it while it's sampling, it doesn't like that and may bite.
<br><br>
## AE Expression Checker
${\color{purple}Adobe \space After \space Effects}$

☒ Not Dockable

A tool for scanning, viewing, and editing expressions across your entire After Effects project. Finds all expressions regardless of nesting depth (up to 4 property levels) and provides an interface to navigate and modify them without manually opening layer properties.

<details>
  <summary>Click to see Screenshots</summary>
<br>
<img width="225" height="163" alt="grafik" src="https://github.com/user-attachments/assets/37c63f06-a7bd-4f57-b499-5eb5edeed394" /><br>
<img width="286" height="211" alt="grafik" src="https://github.com/user-attachments/assets/f31bd2d4-c251-4c6b-be2b-3190a38b12eb" /><br>
<img width="591" height="720" alt="grafik" src="https://github.com/user-attachments/assets/06044f91-a8fd-4aec-8fa9-3ab078c63002" />
<br>
</details>

### Features:
- Scans entire project for expressions in all compositions and layers
- Dropdown menus for quick navigation to specific compositions and layers
- Keyboard shortcuts (Arrow keys for navigation, Escape to close)
- Edit expressions directly in the tool
- Update expressions back to After Effects with one click
- Shows statistics for expression count per property level
- Handles large projects efficiently (tested with 6000+ expressions)

**How to use:** 
1. Run the script
2. Browse expressions using dropdowns or arrow keys
3. Edit expression text in the window
4. Click "Update" to write changes back to the project
5. Navigate to the next expression and repeat

Useful for bulk-editing similar expressions or getting an overview of expression usage in complex projects.
<br><br>
## AE Diagnostics
${\color{purple}Adobe \space After \space Effects}$

☒ Not Dockable

A diagnostics tool that reads a lot of information about your After Effects installation(s) and displays it in a container that let's you copy it's content. So you can tell people like me why scripts like mine throw errors on your machine. And only on your machine specifically :P

<details>
  <summary>Click to see Screenshots</summary>
<br>
<img width="839" height="1153" alt="grafik" src="https://github.com/user-attachments/assets/dc8a112e-8467-4835-a1d2-9a4801c9cab6" />
<br>
</details>

**How to use:** 
1. Run the script.
2. Copy the output.
3. Paste it in an email, on pastebin or write it on a piece of paper.
4. Send it to someone who needs that info.
<br><br>
## Mass Replacer
${\color{blue}Adobe \space Photoshop}$

☒ Not Dockable

A batch replacer for photoshop templates. Replaces two different text layers by name with content from a txt data file.

<details>
  <summary>Click to see Screenshots</summary>
<br><img width="485" height="171" alt="grafik" src="https://github.com/user-attachments/assets/72e16128-5a49-479c-8f58-d8d60447f8d4" /><br>
</details>

**How to use:** It's essential that the folder structure and naming of the Mass Replacer is kept intact: One folder "OUTPUT", one folder "psd_master". Put your photoshop files in the "psd_master" folder and add text layers strictly named "SpeakerName" and "SpeakerDescription" as you like. Fill a txt file with name and description alternating. No limit, empty lines are being ignored. So as example:
<br><br>
George Nespresso<br>
Coffee Influencer<br>
<br>
Britney Shears<br>
Hairdresser<br>
<br>
Justin Thyme<br>
Watchmaker<br>
<br>
1. Run the script and select what format (png or psd) you need, if the template name should be included in the file names (the files are named after name/description) and if you need to escape special characters in your data.
2. Load up a datafile and watch the magic happen.
3. Have a look in the OUTPUT folder after it's done if you dare.
<br><br>
# License

This project is licensed under the **Free License – No Resale**  
© 2025 [Gregor Urabl, BA](https://gregorurabl.at)

# Summary
- Free to use, copy, and share — even in **commercial projects**  
- **Resale or direct monetization** of the scripts themselves is **not allowed**  
- **Attribution appreciated** but **not required**

See the full [LICENSE.md](./LICENSE.md) for details.
