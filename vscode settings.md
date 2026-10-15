{
    "editor.tabSize": 4,
    "editor.indentSize": 4,
    "editor.insertSpaces": true,
    "editor.renderWhitespace": "all",
    "workbench.startupEditor": "newUntitledFile",
    "workbench.editor.useModal": "off",
    // _________________
    // Extension Stuff
    "vim.disableExtension": true,
    "editor.suggest.selectionMode": "always",
    "editor.acceptSuggestionOnEnter": "off",
    "editor.quickSuggestions": {
        "other": "on"
    },
    "editor.codeActionWidget.includeNearbyQuickFixes": false,
    "editor.multiCursorModifier": "alt",
    "indentRainbow.errorColor": "rgba(200,32,32,0.1)",
    "indentRainbow.indicatorStyle": "light",
    "indentRainbow.colors": [
        "rgba(255, 0, 0, 0.7)",
        "rgba(255, 0, 200, 0.9)",
        "rgba(120, 0, 255, 0.9)",
        "rgba(0, 150, 255, 0.9)",
        "rgba(0, 255, 180, 0.9)",
        "rgba(255, 255, 0, 0.9)"
    ],
    "editor.minimap.enabled": false,
    "window.closeWhenEmpty": true,
    "window.openFilesInNewWindow": "on",
    "workbench.editor.enablePreview": false,
    "editor.rename.enablePreview": false,
    "editor.parameterHints.cycle": false,
    "editor.parameterHints.enabled": false,
    "workbench.editor.titleScrollbarVisibility": "visible",
    "workbench.editor.enablePreviewFromQuickOpen": true,
    // __________________________________________
    // MULTI COMMANDS
    "multiCommand.commands": [
        {
            "command": "multiCommand.increaseSidebarMultiple",
            "sequence": [
                "workbench.action.focusSideBar",
                "workbench.action.increaseViewSize",
                "workbench.action.increaseViewSize",
                "workbench.action.increaseViewSize",
                "workbench.action.increaseViewSize"
            ]
        },
        {
            "command": "multiCommand.decreaseSidebarMultiple",
            "sequence": [
                "workbench.action.focusSideBar",
                "workbench.action.decreaseViewSize",
                "workbench.action.decreaseViewSize",
                "workbench.action.decreaseViewSize",
                "workbench.action.decreaseViewSize",
            ]
        },
        {
            "command": "multiCommand.increaseTerminalMultiple",
            "sequence": [
                "workbench.action.terminal.resizePaneRight",
                "workbench.action.terminal.resizePaneRight",
                "workbench.action.terminal.resizePaneRight",
                "workbench.action.terminal.resizePaneRight",
                "workbench.action.terminal.resizePaneRight",
                "workbench.action.terminal.resizePaneRight",
                "workbench.action.terminal.resizePaneRight",
                "workbench.action.terminal.resizePaneRight",
                "workbench.action.terminal.resizePaneRight",
                "workbench.action.terminal.resizePaneRight",
                "workbench.action.terminal.resizePaneRight",
                "workbench.action.terminal.resizePaneRight"
            ]
        },
        {
            "command": "multiCommand.decreaseTerminalMultiple",
            "sequence": [
                "workbench.action.terminal.resizePaneLeft",
                "workbench.action.terminal.resizePaneLeft",
                "workbench.action.terminal.resizePaneLeft",
                "workbench.action.terminal.resizePaneLeft",
                "workbench.action.terminal.resizePaneLeft",
                "workbench.action.terminal.resizePaneLeft",
                "workbench.action.terminal.resizePaneLeft",
                "workbench.action.terminal.resizePaneLeft",
                "workbench.action.terminal.resizePaneLeft",
                "workbench.action.terminal.resizePaneLeft",
                "workbench.action.terminal.resizePaneLeft",
                "workbench.action.terminal.resizePaneLeft"
            ]
        },
        {
            "command": "multiCommand.increaseTerminalMultipleUp",
            "sequence": [
                "workbench.action.terminal.resizePaneUp",
                "workbench.action.terminal.resizePaneUp",
                "workbench.action.terminal.resizePaneUp"
            ]
        },
        {
            "command": "multiCommand.decreaseTerminalMultipleDown",
            "sequence": [
                "workbench.action.terminal.resizePaneDown",
                "workbench.action.terminal.resizePaneDown",
                "workbench.action.terminal.resizePaneDown"
            ]
        },
        // _____________________
        // Split Right
        {
            "command": "multiCommand.splitRightProper",
            "sequence": [
                "workbench.action.splitEditor",
                "workbench.action.focusPreviousGroup",
                "workbench.action.closeActiveEditor",
                "workbench.action.focusNextGroup"
            ]
        }
    ]
}

