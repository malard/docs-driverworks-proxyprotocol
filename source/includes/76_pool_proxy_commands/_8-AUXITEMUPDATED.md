## AUX ITEM UPDATED

Received from the proxy when the auxiliary id is changed in Auxiliary Controls card. The command should be received only when [provides\_aux\_list][1] capability is set to true.


### Signature

`AUX_ITEM_UPDATED ()`


| Parameter | Description |
| --- | --- |
| `ID` | str: Current auxiliary ID |
| `NEW_ID` | str: New auxiliary ID |


### Returns

`None`

[1]:	https://control4.github.io/docs-driverworks-proxyprotocol/#pool-capabilities
