OverBlast is a work in progress "WIP"
Read Me Document contains most recent fixes and additions. For known bugs scroll to the bottom.

- Recent fixes and additions
 
Fixes 3/19/2020
-	Added a humanize feature to the metronome to allow for a more authentic groove to the sequence.
	(Hint* adding more swing to the sequence will make the humanize feature more noticeable.)
-	Added midi in feature this is still going under testing but a good bulk of the coding has been done.
-	
Fixes 3/10/2020
 -	Will overwrite data of newly selected sequence with previously selected data. (Fixed)
 - 	Many small fixes across the whole patch.
 
Fixes 2/15/2020
- 	Songbuilder data is written properly for 16 items in the playlist. Still a bit buggy when changing pages on the song playlist
-	Remove unneeded code from SequencerTrk
-	Connection managment for metronome.

Fixes 2/14/2020
-	Long periods of time after selecting a new pattern or sequence. (Fixed)
-	Will overwrite data of newly selected sequence with previously selected data. (Fixed)
- 	Steps do not updated when a sequence is changed. (Fixed)
-	Modifications to accomidate sequence changes.


Fixes 2/8/2020
-	Pattern and sequence selector remodled. Patterns can be changed on the fly with very little delay if any at all.
-	Small corretions made to recieve sequencer steps for the metronome.
-	Red error messages in pd due to [r checkpadnum] = 0 inside the metronome patch. Red messages>>>> text set: line number (-1) < 0 (Fixed)

Fixes 2/2/2020
-	More internal fixes for the sequence selector. 
- 	Small fix for 1 MultiSamplePlayer 64 cloned objects. Corrected to start at 0 instead of 1
- 	Many corrections for the startup sequence the whole startup sequence is gettig faster.
-	Major fixes to the song playlist data is being stored more consistently.

Fixes 1/23/2020
- 	Internal structure for velocity changes. Can now be heard when playing a sequence
	(Velocities work somtimes hard to notice a difference. Other times wont work at all.)(Fixed)
- 	Corrections in the sequencer to accomidate velocity chagnges.

Fixes 1/18/2020
- 	Aditional cleaning up of the songbuilder currently much more stable.
- 	More color scheme options provided.
- 	Internally change how the active playlist items are displayed. Also while in play mode.
- 	Pattern selector color will changed to the corrisponding playlist item "Patts" value while in play mode.
- 	Song playlist data will be overwritten if the page is changed.(Fixed)
- 	Atoms in the song list items will change when not scrolled. Always seams to be +2 items ahead.(Fixed)
- 	Sequencer updated to accomidate color changes.

Fixes 12/31/2019

- 	Added abilty to change color scheme. To change permament startup
	values open OBAlphaSongBuilder.pd to edit values as needed currently set to "1" = Grey for default
	and "17" = Light Blue for active song playlist items.
- 	Removed a bunch of unneeded objects from MultiSamplePlayer.pd 
- 	Song playlist items are highlighted when played in the correct order.
- 	When color changes to the active color the previous pattern will stay selected. (Fixed)
- 	When color changes to the active color the previous sequence will stay selected. (Fixed)

Fixes 12/30/2019

- 	Default files are now generated correctly when Overblast is run for the first time.
- 	Now the playlist will now increment when playing and continue past 16 song items.

Fixes 12/28/2019
- 	Sample Editor is avalible to chop and edit wave samples.

Known Bugs

Recently fix but incase these errors show again. A lot of red messages when Overblast
first starts indicating pattern or velocity default files are missing you should do the following.
Click Create_New button to create temp default files then close and reopen Overblast.

Pattern Selector -

-	velocity request (0 32) out of range in console when the pattern bank is changed.

Sequence Selector -

-	No known Bugs

Song Playlist -

- 	EOS check box does not work. Not developed at all as of yet.
- 	Pause song does not work. Only can stop and play from begining of the song.
- 	Mixdown and Stems toggle not working. Not developed at all as of yet. 
- 	Export Song to Wave button is not working. Not developed at all as of yet. 

Sample Editor -

- Trucate button can be buggy.

Sequencer - 

- 	One shot and loop toggles not working. Not developed at all as of yet. 
- 	Fade in and fade out sliders not working. Not developed at all as of yet. 
- 	Effects are not working. Not developed at all as of yet. 
- 	Pan slider not working. Not developed at all as of yet. 
- 	Mute and solo toggle not working. Not developed at all as of yet. 

Metronome -

- 	No known bugs
