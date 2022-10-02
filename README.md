# [ESX]Eclipse-Lockpicking


## Installation:
Put `eclipse_Lockpicking` in your resources folder.
Ensure `eclipse_Lockpicking` in your server cfg.


For change config data use `config.lua`. `eclipse_Lockpicking/config.json`

![image](https://user-images.githubusercontent.com/36680471/193465693-7f8bf80d-439d-45d6-8d8c-ec6e9021d591.png)

For start Lockpicking use export function:

```lua

exports['eclipse_Lockpicking']['OpenLockpick']
```

For get callback use client event:

```lua
AddEventHandler('ECLIPSE:SuccessLockpick', function()
	-- to do...
end)

```
