# Ranks
aLib comes with very to use very configurable ranks. 

## Creating
Ranks run on a UUID rather than a string name. Because of this you cna have a rank with the same name.
To create a rank you type `/rank create <name`. 

## Management
Each rank can be giving a weight, this is to determine the position of the rank. This feature doesn't provide anything but sorting.

## Discord
If you plan on doing discord syncing, you must sync each rank, I even recommend syncing staff ranks. To sync a rank type `rank edit <rank> sync <rank id`.

## Permissions
As of right now aLib does not support wildcard permissions meaning the `*` will not work. You will have to manually set each permission.