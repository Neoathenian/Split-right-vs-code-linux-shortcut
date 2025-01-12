# Split-right-vs-code-linux-shortcut
Instructions on how to add the split right vs code shortcut like in windows (Ctrl+º)(a.k.a Ctrl+\\).

## Instructions:
1. Press Ctrl+Shift+P
2. Select: "Open Keyboard Shortcuts (JSON)"
3. Add:

    {
        "key": "ctrl+[Backquote]",
        "command": "workbench.action.splitEditorRight"
    }


