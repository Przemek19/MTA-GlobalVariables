# MTA-GlobalVariables
**[PL]**

Zasób umożliwia pobieranie zapisanych wartości w każdym zasobie. (Globalna)

**[EN]**

The resource allows you to get saved values ​​in each resource. (Global)

**[PL/Usage]**

* Pobieranie wszystkich zmiennych/wartości
```lua
local data = exports["resource"]:GetVariable(nil, nil)
outputDebugString(data["global"]["prefix"])
```
* Pobieranie całej tablicy
```lua
local data = exports["resource"]:GetVariable("NAME_TABLE", nil)
outputDebugString(data["prefix"])
```
* Pobieranie poszczególnej wartości z konkretnej tablicy
```lua
local data = exports["resource"]:GetVariable("NAME_TABLE", "VALUE")
outputDebugString(data)
```
**[EN/Usage]**

* Get all variables/values
```lua
local data = exports["resource"]:GetVariable(nil, nil)
outputDebugString(data["global"]["prefix"])
```
* Get the entire array
```lua
local data = exports["resource"]:GetVariable("NAME_TABLE", nil)
outputDebugString(data["prefix"])
```
* Get a particular value from a specific table
```lua
local data = exports["resource"]:GetVariable("NAME_TABLE", "VALUE")
outputDebugString(data)
```
