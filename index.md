# A header

## Not quite a header

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

* Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
* tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
* quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
* consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
* cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
* proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

```mcfunction
# This is comment
execute store result score @s objective run data get storage foo:bar Baz
tellraw @a {"text": "This is a text component", "color": "gold", "bold": true}
```
Another cool thing is that we get JSON:
```jsonc
{
  // Comments are allowed here
  "replace": false,
  "values": [
    "minecraft:stone",
    "minecraft:dirt"
  ]
}
```
