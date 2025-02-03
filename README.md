# cursor-keybinding

```sh

// Place your key bindings in this file to override the defaults
[
    // Terminal Focus
    {
        "key": "cmd+t",
        "command": "workbench.action.terminal.newWithFocus",
        "when": "terminalFocus"
    },
    // Toggle between terminals - up
    {
        "key": "cmd+alt+up",
        "command": "workbench.action.terminal.focusPrevious",
        "when": "terminalFocus"
    },
    // Toggle between terminals - down
    {
        "key": "cmd+alt+down",
        "command": "workbench.action.terminal.focusNext",
        "when": "terminalFocus"
    },
    // Create a new terminal in terminalFocus
    {
        "key": "cmd+t",
        "command": "workbench.action.terminal.newInActiveWorkspace",
        "when": "terminalFocus"
    },
    // Kill the terminal in terminalFocus
    {
        "key": "cmd+w",
        "command": "workbench.action.terminal.kill",
        "when": "terminalFocus"
    },
    // Create a new terminal and focus
    {
        "key": "shift+cmd+t",
        "command": "workbench.action.terminal.new",
        "when": "!terminalFocus"
    },
    // Toggle the terminal
    {
        "key": "ctrl+alt+up",
        "command": "workbench.action.terminal.toggleTerminal"
    }
]

```
