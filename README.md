# adobe_freescripts
Tools, Snippets and little helpers I created on the way while building larger stuff. Mostly ExtendScript Stuff for Adobe Photoshop and After Effects . I'm not actively working on most of these and won't make updates or bugfixes on a regular basis. But feel free to contact me if you find any bugs or have a request fo a feature. Licensed under the “Free License – No Resale” by Gregor Urabl (https://gregorurabl.at). Credits are not required but very appreciated - thank you - share the open source spirit! I'm in no way affiliated with Adobe, just coding what I need myself for their software.

# The Scripts in Detail

## Expression Baker
${\color{purple}Adobe \space After \space Effects}$

☑ Dockable

A little tool to batch bake expressions fur multiple compositions at once. 

**How to use:** Select compositions and hit the button. Expression Baker copies these compositions to a new folder, samples the frames of all expressions in all selected compositions and removes the expressions afterwards. The original compositions remain unaffected. Don't touch it while it's sampling, it doesn't like that and may bite.

## Mass Replacer
${\color{blue}Adobe \space Photoshop}$

☒ Not Dockable

A batch replacer for photoshop templates. Replaces two different text layers by name with content from a txt data file.

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
Run the script and select what format (png or psd) you need, if the template name should be included in the file names (the files are named after name/description) and if you need to escape special characters in your data. Load up a datafile and watch the magic happen. Have a look in the OUTPUT folder after it's done if you dare.

# License

This project is licensed under the **Free License – No Resale**  
© 2025 [Gregor Urabl, BA](https://gregorurabl.at)

# Summary
- Free to use, copy, and share — even in **commercial projects**  
- **Resale or direct monetization** of the scripts themselves is **not allowed**  
- **Attribution appreciated** but **not required**

See the full [LICENSE.md](./LICENSE.md) for details.
