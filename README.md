OverBlast ReadMe Document

- Recent Fixes and additions

Fixes 1/18/2020
- Aditional cleaning up of the songbuilder currently much more stable.
- More color scheme options provided.
- Internally change how the active playlist items are displayed. Also while in play mode.
- Pattern selector color will changed to the corrisponding playlist item "Patts" value while in play mode.
- Song playlist data will be overwritten if the page is changed.(Fixed)
- Atoms in the song list items will change when not scrolled. Always seams to be +2 items ahead.(Fixed)
- Sequencer updated to accomidate color changes.

Fixes 12/31/2019

- Added abilty to change color scheme. To change permament startup
values open OBAlphaSongBuilder.pd to edit values as needed currently set to "1" = Grey for default
and "17" = Light Blue for active song playlist items.
- Removed a bunch of unneeded objects from MultiSamplePlayer.pd 
- Song playlist items are highlighted when played in the correct order.
- When color changes to the active color the previous pattern will stay selected. (Fixed)
- When color changes to the active color the previous sequence will stay selected. (Fixed)

Fixes 12/30/2019

- Default files are now generated correctly when Overblast is run for the first time.
- Now the playlist will now increment when playing and continue past 16 song items.

Fixes 12/28/2019
- Sample Editor is avalible to chop and edit wave samples.

Known Bugs

Recently fix but incase these errors show again. A lot of red messages when Overblast
first starts indicating pattern or velocity default files are missing you should do the following.
Click Create_New button to create temp default files then close and reopen Overblast.

Song Playlist -

- EOS check box does not work. Not developed at all as of yet.
- Pages (Prev) and [Next] buttons both work but does not change songlist items visually.
- Pause song does not work. Only can stop and play from begining of the song.
- Mixdown and Stems toggle not working. Not developed at all as of yet. 
- Export Song to Wave button is not working. Not developed at all as of yet. 

Sample Editor -

- Trucate button can be buggy.

Sequencer - 

- Velocities work somtimes hard to notice a difference. Other times wont work at all.
- One shot and loop toggles not working. Not developed at all as of yet. 
- Fade in and fade out sliders not working. Not developed at all as of yet. 
- Effects are not working. Not developed at all as of yet. 
- Pan slider not working. Not developed at all as of yet. 
- Mute and solo toggle not working. Not developed at all as of yet. 

Metronome -

- Red error messages in pd due to [r checkpadnum] = 0 inside the metronome patch. Red messages>>>> text set: line number (-1) < 0
