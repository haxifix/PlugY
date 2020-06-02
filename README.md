# PlugY v12.00 (Unofficial)
This repository contains the source code for PlugY version 12.00 updated for 1.14d.

Please note that I am not the original developer of PlugY (Yohann).  I took his source code for PlugY 11.02 and updated all the features to work on Diablo II 1.14d.

<b>Please backup ALL your save files.  This has not been rigorously tested.</b>

# Installation
Simply download the zip file in the root directory of the repository (PlugY v12.00.zip) and extract the files into your Diablo II directory.  Then, start the mod by running PlugYRun.exe.  If you would like to edit the configuration of the mod, open PlugY.ini in your favorite text editor and save your changes.

<b>It is highly recommended to also backup your save folder before using the mod.</b>

# Features
Each of these features can be turned on/off via PlugY.ini (see "COMMENTS ON THE CONFIGURATION FILE")
<ul>
  <li>Disable access to Battle.net.
  <li>Infinite storage space in the stash.
  <li>Shared storage space in the stash.
  <li>Enabled the ladder only runewords out of realms.
  <li>Local World Event and Uber Quest for singleplayer and multiplayer off-realm !
  <li>Can open Cow Level Portal even when player have kill the Cow King in that difficulty.
  <li>Unassign assigned skills and stats points.
  <li>Change the selected language.
  <li>Always regenerate maps in SinglePlayer like in MultiPlayer.
  <li>Automatically execute /players X when you launch a new game.
  <li>Added some pages for display more characters stats like %MF.
  <li>Display item level in its popup.
  <li>Launch any number of Diablo II games on the same computer.
  <li>Increase the stash to 10x10 squares.
  <li>Change the save path directory.
  <li>Always display Mana and Life values above the globes.
  <li>D2 can load all files, even those opened with Microsoft Excel (disabled by default).
  <li>Display the stats current value (without magical bonus) like Magic/gold find or maximum resistances.
  <li>Can launch game in windowed mode with some options (lock mouse/resize/on top/noborder).
  <li>Add following commands (see "COMMENTS ON THE CONFIGURATION FILE") :
  <ul>
	  <li>/save : Save game without exit.</li>
	  <li>/page 1 : Show normal stats page (stats page must be opened).</li>
	  <li>/page 2 : Show extra stats page (stats page must be opened).</li>
	  <li>/page 3 : Show resistance stats page (stats page must be opened).</li>
	  <li>/page 4 : (beta) Show available runewords (stats page must be opened).</li>
	  <li>/lockmouse : Lock mouse cursor in the window.</li>
	  <li>/lock : Same as /lockmouse.</li>
	  <li>/unlockmouse : Unlock mouse cursor in the window.</li>
	  <li>/unlock : Same as /unlockmouse.</li>
	  <li>/renamechar newname : Rename your character and save it.</li>
	  <li>/renamepage name : Rename current page stash.</li>
	  <li>/setindex : Set current stash page as index.</li>
	  <li>/setmainindex : Set current stash page as main index.</li>
	  <li>/resetindex : Remove index flag on the current stash page.</li>
	  <li>/insertpage : Insert a new page after the current page.</li>
	  <li>/deletepage : Delete current page if empty.</li>
	  <li>/swap page : Swap the content of current stash page with the content of another page.</li>
	  <li>/toggle page : Swap the content of current stash page with the content of another page in opposing stash shared/personal.</li>
	  <li>/dlm : Toggle always display mana and life mode.</li>
	  <li>/dml : Same as /dlm.</li>
	  <li>/dl : Toggle always display life mode.</li>
	  <li>/dm : Toggle always display mana mode.</li>
	  <li>/listcube : (beta) Create a "cube.txt" file in save directory containing all cube's receipts.</li>
    </ul></li>
  <li>Prevent Nihlathak's portal from closing.</li>
</ul>
