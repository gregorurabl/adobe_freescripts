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

**How to use:** Select compositions and hit the button. Expression Baker copies these compositions to a new folder, samples the frames of all expressions in all selected compositions and removes the expressions afterwards. The original compositions remain unaffected. Don't touch it while it's sampling, it doesn't like that and may bite.

## AE Diagnostics
${\color{purple}Adobe \space After \space Effects}$

☒ Not Dockable

A diagnostics tool that reads a lot of information about your After Effects installation(s) and displays it in a container that let's you copy it's content. So you can tell people like me why scripts like mine throw errors on your machine. And only on your machine specificaly :P

<details>
  <summary>Click to see Screenshots</summary>
<br>
<img width="839" height="1153" alt="grafik" src="https://github.com/user-attachments/assets/dc8a112e-8467-4835-a1d2-9a4801c9cab6" />
<br>
</details>

**How to use:** Run the script. Copy the output. Paste it in a mail, pastebin or write it on a piece of paper. Send it to someone who needs that info.

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
Run the script and select what format (png or psd) you need, if the template name should be included in the file names (the files are named after name/description) and if you need to escape special characters in your data. Load up a datafile and watch the magic happen. Have a look in the OUTPUT folder after it's done if you dare.

# License

This project is licensed under the **Free License – No Resale**  
© 2025 [Gregor Urabl, BA](https://gregorurabl.at)

# Summary
- Free to use, copy, and share — even in **commercial projects**  
- **Resale or direct monetization** of the scripts themselves is **not allowed**  
- **Attribution appreciated** but **not required**

See the full [LICENSE.md](./LICENSE.md) for details.
