
// KEYBOARD
// MINE
{
    "key": "cmd+w",
    "command": "workbench.action.closeWindow",
    "when": "!editorIsOpen && !multipleEditorGroups"
},
{
    "key": "cmd+u",
    "command": "toggle.diff.renderSideBySide"
},
{
    "key": "ctrl+alt+c",
    "command": "your.extension.command.name", // Replace with the actual command name from your extension
    "when": "editorTextFocus"
},
{
    "key": "cmd+shift+g",
    "command": "java.action.generateConstructorsPrompt"
},
// KEYBINDS
// _____________________
// BASIC FUNCTIONALITY
{
    "key": "shift+cmd+1",
    "command": "workbench.action.previousEditor"
},
{
    "key": "cmd+shift+c",
    "command": "workbench.panel.chat.view.copilot.focus"
},
{
    "key": "cmd+l",
    "command": "workbench.action.editor.changeLanguageMode",
    "when": "!notebookEditorFocused"
},
{
    "key": "cmd+k m",
    "command": "-workbench.action.editor.changeLanguageMode",
    "when": "!notebookEditorFocused"
},
// _______________________________________
// WINDOW MANAGEMENT
{
    "key": "ctrl+shift+right",
    "command": "multiCommand.increaseSidebarMultiple",
},
{
    "key": "ctrl+shift+left",
    "command": "multiCommand.decreaseSidebarMultiple",
},
{
    "key": "ctrl+shift+cmd+left",
    "command": "multiCommand.decreaseTerminalMultiple",
},
{
    "key": "ctrl+shift+cmd+right",
    "command": "multiCommand.increaseTerminalMultiple",
},
{
    "key": "ctrl+shift+down",
    "command": "multiCommand.decreaseTerminalMultipleDown",
},
{
    "key": "ctrl+shift+up",
    "command": "multiCommand.increaseTerminalMultipleUp",
},
{
    "key": "cmd+\\",
    "command": "multiCommand.splitRightProper"
},
// _____________________________________
// Toggles
{
    "key": "ctrl+shift+v",
    "command": "toggleVim"
},
{
    "key": "ctrl+shift+cmd+c",
    "command": "workbench.action.chat.openInNewWindow",
    "when": "chatIsEnabled"
},
{
    "key": "ctrl+b",
    "command": "workbench.files.action.collapseExplorerFolders"
},
{
    "key": "cmd+t",
    "command": "workbench.action.terminal.focus"
},
{
    "key": "cmd+e",
    "command": "workbench.action.focusActiveEditorGroup"
},
{
    "key": "cmd+f1",
    "command": "editor.foldAll",
    "when": "editorTextFocus && foldingEnabled"
},
{
    "key": "cmd+k cmd+0",
    "command": "-editor.foldAll",
    "when": "editorTextFocus && foldingEnabled"
},
{
    "key": "shift+cmd+3",
    "command": "editor.foldRecursively",
    "when": "editorTextFocus && foldingEnabled"
},
{
    "key": "cmd+k cmd+[",
    "command": "-editor.foldRecursively",
    "when": "editorTextFocus && foldingEnabled"
},
{
    "key": "shift+cmd+4",
    "command": "editor.unfoldRecursively",
    "when": "editorTextFocus && foldingEnabled"
},
{
    "key": "cmd+k cmd+]",
    "command": "-editor.unfoldRecursively",
    "when": "editorTextFocus && foldingEnabled"
},
{
    "key": "cmd+f2",
    "command": "editor.unfoldAll",
    "when": "editorTextFocus && foldingEnabled"
},
{
    "key": "cmd+k cmd+j",
    "command": "-editor.unfoldAll",
    "when": "editorTextFocus && foldingEnabled"
},
{
    "key": "shift+cmd+2",
    "command": "editor.unfold",
    "when": "editorTextFocus && foldingEnabled"
},
{
    "key": "alt+cmd+]",
    "command": "-editor.unfold",
    "when": "editorTextFocus && foldingEnabled"
},
{
    "key": "shift+cmd+1",
    "command": "editor.fold",
    "when": "editorTextFocus && foldingEnabled"
},
{
    "key": "alt+cmd+[",
    "command": "-editor.fold",
    "when": "editorTextFocus && foldingEnabled"
},
{
    "key": "alt+cmd+1",
    "command": "editor.foldLevel1",
    "when": "editorTextFocus && foldingEnabled"
},
{
    "key": "cmd+k cmd+1",
    "command": "-editor.foldLevel1",
    "when": "editorTextFocus && foldingEnabled"
},
{
    "key": "alt+cmd+2",
    "command": "editor.foldLevel2",
    "when": "editorTextFocus && foldingEnabled"
},
{
    "key": "cmd+k cmd+2",
    "command": "-editor.foldLevel2",
    "when": "editorTextFocus && foldingEnabled"
},
{
    "key": "alt+cmd+3",
    "command": "editor.foldLevel3",
    "when": "editorTextFocus && foldingEnabled"
},
{
    "key": "cmd+k cmd+3",
    "command": "-editor.foldLevel3",
    "when": "editorTextFocus && foldingEnabled"
},
{
    "key": "alt+cmd+4",
    "command": "editor.foldLevel4",
    "when": "editorTextFocus && foldingEnabled"
},
{
    "key": "cmd+k cmd+4",
    "command": "-editor.foldLevel4",
    "when": "editorTextFocus && foldingEnabled"
},
{
    "key": "alt+cmd+5",
    "command": "editor.foldLevel5",
    "when": "editorTextFocus && foldingEnabled"
},
{
    "key": "cmd+k cmd+5",
    "command": "-editor.foldLevel5",
    "when": "editorTextFocus && foldingEnabled"
},
{
    "key": "alt+cmd+7",
    "command": "editor.foldLevel7",
    "when": "editorTextFocus && foldingEnabled"
},
{
    "key": "cmd+k cmd+7",
    "command": "-editor.foldLevel7",
    "when": "editorTextFocus && foldingEnabled"
},
{
    "key": "alt+cmd+6",
    "command": "editor.foldLevel6",
    "when": "editorTextFocus && foldingEnabled"
},
{
    "key": "cmd+k cmd+6",
    "command": "-editor.foldLevel6",
    "when": "editorTextFocus && foldingEnabled"
},
{
    "key": "ctrl+enter",
    "command": "editor.action.addSelectionToNextFindMatch",
    "when": "editorFocus"
},
{
    "key": "cmd+d",
    "command": "-editor.action.addSelectionToNextFindMatch",
    "when": "editorFocus"
},
{
    "key": "ctrl+shift+cmd+`",
    "command": "workspace-colors.switchLight"
},
{
    "key": "cmd+enter",
    "command": "editor.action.revealDefinition",
    "when": "editorHasDefinitionProvider && editorTextFocus"
},
{
    "key": "f12",
    "command": "-editor.action.revealDefinition",
    "when": "editorHasDefinitionProvider && editorTextFocus"
},
{
    "key": "shift+cmd+=",
    "command": "workbench.action.zoomIn"
},
{
    "key": "cmd+=",
    "command": "-workbench.action.zoomIn"
},
{
    "key": "shift+cmd+-",
    "command": "workbench.action.zoomOut"
},
{
    "key": "cmd+-",
    "command": "-workbench.action.zoomOut"
},
{
    "key": "cmd+t",
    "command": "workbench.action.terminal.toggleTerminal",
    "when": "terminal.active"
},
{
    "key": "ctrl+`",
    "command": "-workbench.action.terminal.toggleTerminal",
    "when": "terminal.active"
},
{
    "key": "alt+cmd+r",
    "command": "toggleSearchEditorRegex",
    "when": "inSearchEditor && searchInputBoxFocus"
},
{
    "key": "alt+cmd+r",
    "command": "-toggleSearchEditorRegex",
    "when": "inSearchEditor && searchInputBoxFocus"
},
{
    "key": "cmd+r",
    "command": "toggleFindRegex",
    "when": "editorFocus"
},
{
    "key": "alt+cmd+r",
    "command": "-toggleFindRegex",
    "when": "editorFocus"
},
{
    "key": "shift+alt+d",
    "command": "workbench.view.debug",
    "when": "viewContainer.workbench.view.debug.enabled"
},
{
    "key": "shift+cmd+d",
    "command": "-workbench.view.debug",
    "when": "viewContainer.workbench.view.debug.enabled"
},
{
    "key": "cmd+shift+d",
    "command": "workbench.action.moveEditorToNewWindow"
},
{
    "key": "cmd+[",
    "command": "-editor.action.outdentLines",
    "when": "editorTextFocus && !editorReadonly"
},
{
    "key": "cmd+]",
    "command": "-editor.action.indentLines",
    "when": "editorTextFocus && !editorReadonly"
},
{
    "key": "cmd+[",
    "command": "workbench.action.navigateBack",
    "when": "canNavigateBack"
},
{
    "key": "ctrl+-",
    "command": "-workbench.action.navigateBack",
    "when": "canNavigateBack"
},
{
    "key": "cmd+]",
    "command": "workbench.action.navigateForward",
    "when": "canNavigateForward"
},
{
    "key": "ctrl+shift+-",
    "command": "-workbench.action.navigateForward",
    "when": "canNavigateForward"
},
{
    "key": "shift+cmd+[",
    "command": "editor.action.outdentLines"
},
{
    "key": "shift+cmd+]",
    "command": "editor.action.indentLines"
},
{
    "key": "cmd+j",
    "command": "workbench.action.toggleActivityBarVisibility"
},
{
    "key": "cmd+k",
    "command": "workbench.action.keepEditor"
},
{
    "key": "cmd+k enter",
    "command": "-workbench.action.keepEditor"
},
{
    "key": "shift+cmd+s",
    "command": "workbench.scm.focus"
},
{
    "key": "shift+cmd+b",
    "command": "gitlens.toggleLineBlame"
},
{
    "key": "shift+cmd+h",
    "command": "gitlens.showFileHistoryView"
},
{
    "key": "shift+alt+r",
    "command": "gitlens.toggleCodeLens"
},
{
    "key": "shift+alt+b",
    "command": "-gitlens.toggleCodeLens",
    "when": "editorTextFocus && !gitlens:disabled && !gitlens:disabledToggleCodeLens && config.gitlens.keymap == 'alternate'"
},
{
    "key": "alt+cmd+t",
    "command": "workbench.view.extension.test",
    "when": "viewContainer.workbench.view.extension.test.enabled"
},
{
    "key": " cmd+1",
    "command": "-workbench.action.previousEditor"
},
{
    "key": "ctrl+tab",
    "command": "workbench.action.nextEditorInGroup"
},
{
    "key": "cmd+k alt+cmd+right",
    "command": "-workbench.action.nextEditorInGroup"
},
{
    "key": "cmd+2",
    "command": "workbench.action.focusNextGroup"
},
{
    "key": "ctrl+shift+tab",
    "command": "workbench.action.previousEditorInGroup"
},
{
    "key": "cmd+k alt+cmd+left",
    "command": "-workbench.action.previousEditorInGroup"
},
{
    "key": "ctrl+n",
    "command": "explorer.newFile"
},
{
    "key": "cmd+1",
    "command": "workbench.action.focusPreviousGroup"
},
{
    "key": "cmd+1",
    "command": "-workbench.action.focusFirstEditorGroup"
},
{
    "key": "shift+cmd+w",
    "command": "workbench.action.closeEditorsInGroup"
},
{
    "key": "cmd+k cmd+w",
    "command": "-workbench.action.closeAllEditors"
},
{
    "key": "ctrl+cmd+n",
    "command": "explorer.newFolder"
},
{
    "key": "ctrl+cmd+p",
    "command": "search-folder.searchFolder"
},
{
    "key": "ctrl+cmd+w",
    "command": "workbench.action.closeOtherEditors"
},
{
    "key": "alt+cmd+t",
    "command": "-workbench.action.closeOtherEditors"
},
{
    "key": "ctrl+cmd+h",
    "command": "toggle.diff.renderSideBySide"
},
{
    "key": "f20",
    "command": "editor.action.smartSelect.expand",
    "when": "editorTextFocus"
},
{
    "key": "ctrl+shift+right",
    "command": "-editor.action.smartSelect.expand",
    "when": "editorTextFocus"
},
{
    "key": "ctrl+shift+cmd+right",
    "command": "-editor.action.smartSelect.expand",
    "when": "editorTextFocus"
},
{
    "key": "ctrl+cmd+`",
    "command": "workspace-colors.switchDefault"
},
{
    "key": "alt+cmd+j",
    "command": "roo-cline.SidebarProvider.focus"
},
{
    "key": "ctrl+l",
    "command": "workbench.action.gotoLine"
},
{
    "key": "ctrl+g",
    "command": "-workbench.action.gotoLine"
},
{
    "key": "ctrl+cmd+h",
    "command": "markdown.extension.editing.toggleBold",
    "when": "editorTextFocus && !editorReadonly && editorLangId =~ /^markdown$|^rmd$|^quarto$/"
},
{
    "key": "cmd+b",
    "command": "-markdown.extension.editing.toggleBold",
    "when": "editorTextFocus && !editorReadonly && editorLangId =~ /^markdown$|^rmd$|^quarto$/"
},
{
    "key": "ctrl+cmd+j",
    "command": "workbench.action.closeAuxiliaryBar"
},
{
    "key": "alt+cmd+j",
    "command": "workbench.action.toggleAuxiliaryBar"
},
{
    "key": "alt+cmd+b",
    "command": "-workbench.action.toggleAuxiliaryBar"
},
{
    "key": "ctrl+t",
    "command": "workbench.panel.testResults.view.focus"
},
{
    "key": "cmd+e",
    "command": "references-view.findReferences",
    "when": "editorHasReferenceProvider"
},
{
    "key": "shift+alt+f12",
    "command": "-references-view.findReferences",
    "when": "editorHasReferenceProvider"
},
{
    "key": "shift+f3",
    "command": "-editor.action.previousMatchFindAction",
    "when": "editorFocus"
},
{
    "key": "shift+cmd+g",
    "command": "-editor.action.previousMatchFindAction",
    "when": "editorFocus"
},
{
    "key": "shift+alt+c",
    "command": "continue.continueGUIView.focus"
},
{
    "key": "cmd+o",
    "command": "git.openFile"
},
{
    "key": "shift+cmd+k",
    "command": "-editor.action.deleteLines",
    "when": "textInputFocus && !editorReadonly"
}