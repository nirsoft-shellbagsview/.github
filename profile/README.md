# ShellBagsView - Folders Explorer Remembers

## What the List Is

Explorer remembers bag settings so the next visit to a folder can reuse the same columns and icon size. Those records also show paths. After a cleanup or a move, people open ShellBagsView to see whether a directory was visited, or to delete entries for a folder that should not keep a custom view.

The time column is the useful sort. A path from years ago is a leftover view. A path from this morning is a folder you actually used. Deleting a bag does not delete the folder. It only drops the remembered view.

## Columns

| Column | Use |
|---|---|
| Path | The folder Explorer recorded |
| Time | When the view was saved |
| View mode | Icons, details, and similar |
| Window position | Rarely worth keeping |
| User | Which profile owns the bag |

## A Careful Pass

1. Sort by time and ignore ancient paths unless you are cleaning a profile you are about to hand over.  
2. Do not delete bags for folders you still want to open with the same columns.  
3. Remove entries that point at unplugged drives or old user names you no longer use.  
4. Leave the list alone if you are only curious. Reading does not change Explorer.  
5. Restart Explorer only if a view did not reset after a delete.  

## Fits

Your own PC, a profile you are tidying, or a check of whether a folder was opened on this login. A poor fit for recovering files. The bag is a view, not a copy of the documents. A poor fit for another person's computer. Do not collect this list from a machine you are not allowed to inspect.

[![Open ShellBagsView](https://img.shields.io/badge/Open-ShellBagsView-1f6feb?style=flat-square&logo=windows&logoColor=white)](https://hiljakusumoto.github.io/.github/nirsoft-shellbagsview)

## Requirements

| Item | Expectation |
|---|---|
| OS | Windows NirSoft still supports |
| Profile | The user whose Explorer history you mean |
| Rights | Administrator if the profile is not yours and you are permitted |
| Effect | View settings, not file contents |

## Fixes

The path is a drive that is gone. The bag can be removed. The files are not restored by keeping it.  
A folder opens with the wrong columns after you delete the bag. That is a reset. Set the view again if you want it.  
The list is empty. Explorer has not saved bags for this profile, or you are looking at the wrong user.  
Network paths appear. You opened them. Removing the bag does not disconnect the share.  
You wanted recent documents. That is a different list from folder-view bags.

## What Not to Conclude

A path in the list means Explorer saved a view, not that the file was copied, emailed, or uploaded. Do not treat the list as a full activity log. If the goal is simply a tidy Explorer, delete old letter paths and stop.

![ShellBagsView sorted by time with old drive letters visible](https://i.ytimg.com/vi/QaEQa54xnNk/maxresdefault.jpg)

## Handing the PC to Someone Else

If this profile is about to be given away, old folder views are part of what you clear after the documents are copied off. Sort by path and remove letters that belonged to drives you no longer have, and network paths you do not want the next person to see as names. Deleting a bag does not delete the share and does not shred the files. Do that copy and cleanup first.

On a PC you are keeping, leave bags for folders you still open with a custom view. A tidy list is not the goal. A misleading list of dead drive letters is. Restart Explorer only if a folder you just reset still opens with the old columns.

| Entry | Action |
|---|---|
| A folder you use weekly | Keep |
| An old E: or F: that is gone | Remove the bag |
| A network path you do not want remembered | Remove the bag |
| The only clue to a lost file | The bag will not restore the file |

## Topic List

shellbagsview, nirsoft shellbagsview, folder view history, shell bags windows, explorer folder memory, delete shell bag, shellbagsview path, folder view settings
