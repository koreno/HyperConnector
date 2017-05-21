# HyperConnector
A rigging swiss-army knife for Autodesk Maya

## DATE:       Dec 14, 2006

## DESCRIPTION:
This script creates the HyperConnector popup-menus in the channel-box. Access by ctrl-right-click in the Channel-Box, or "HyperConnector..." in the channel-box menu. The HyperConnector allows advanced connections between nodes. First 'Mark' the channels you wish to use as source for the connection, select the destination channels and choose the type of connection you wish to perform (normal, negate, specific, reverse, visiblity...) The HyperConnector takes into account the number of source channels and destination channels when performing connections, whether 1-to-1, 1-to-many, many-to-many.

## INSTALLATION:
Call "OK_hyperConnector" from the command script, or add the following to your userSetup.mel script:

    `source OK_hyperConnector;`

This script requires OK_utils.mel, OK_manageConnections.mel, OK_connections.mel


## UPDATES:
### Version 2.0:
  * New Window for previewing advanced connection procedures
### Version 1.2:
  * Combine with value - New Advanced Connections allow combining channels with a specified value
### Version 1.12:
  * Connecting multiple channels into one multi-attributes
  * Bug fix - replaces any other popups that occupy the ChannelBox
  * Bug fix - displays a warning if a connection wasn't possible and continues
  * Bug fix - displays a warning if a paste-value wasn't possible and continues
### Version 1.11:
  * Channel List Sorting - RGB attributes maintain RGB sorting order (instead of alphabetical BGR)
### Version 1.1:
  * Modify Connections submenu - Allows modifying a existing connections (applying calculation nodes)
  * Inputs/Outputs submenus - Lists the direct inputs/outputs of a channel
  * Filters Button - Filter the list of attributes in the HyperConnector channels window
  * Added annotations to the various menu items
