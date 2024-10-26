# UNIX Library Manager -- Libux!
Manage your library with ease, and hard links!

## Basic usage
```bash
libux add /path/to/book <name of the list>:<name of the link>

libux read <name of the list>:<name of the link>

libux remove <name of the list>:<name of the link> -- TODO

libux list <name of the list> -- TODO

libux move <name of the list1>:<name of the link2> <name of the list2>:<name of the link2>
```

For example:
```bash
libux add ~/Downloads/Algorithmic\ Thinking.pdf reading:AThinking

libux read reading:AThinking
...

```
