# npcscan - WoW 1.12 addOn 

This fork of npcscan shouts what you find to guild chat, so this fork should only be used for camping world bosses.

![Alt text](http://i.imgur.com/d7TLkZm.png)

This addOn automatically scans for characters by name and alerts you upon finding one. Instead of the modern scanning methods which don't work for Vanilla it uses the API function *TargetByName* which was removed with TBC.

The alert is visually and acoustically an exact copy of the famous addOn *_NPCScan* which first appeared during WotLK and in tribute to which this is named *npcscan*, though it also works for players.

There are two commands:<br/>
**/npcscan** lists the active scan targets<br/>
**/npcscan name** adds/removes **name** to/from the scan targets<br/>
When a target is detected it is removed and has to be readded to continue scanning for it.
