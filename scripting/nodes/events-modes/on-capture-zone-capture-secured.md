# On Capture Zone Capture Secured
![](../../../.gitbook/assets/on-capture-zone-capture-secured.png)
## Description
Event called whenever any *Capturable Zone*'s capture progress is reduced to 0 by the *Controlling Team*. In other words, this event fires when the team that owns the zone successfully resets an attacker's capture progress.

## Node Type
Nodes fall into two basic categories: Data and Execution. This node listens for an Event, then triggers it's node string.

## Inputs
| Input | Type | Required | Description |
|------------------|------------------|----------|--------------------------------------------------------------|
| N/A | N/A | N/A | |

## Outputs
| Output | Type | Description |
|------------------|------------------|--------------------------------------------------------------|
| Controlling Team | Team | Team that owns the zone.|
| Capture Team | Team | The team whose capture attempt progress was reset.|
| Capturable Zone | Object | The zone that was just secured.|

\
\
**Contributors**

AddiCt3d 2CHa0s