# Why would I want this?

Because there's a whole lot of probably-could-be-built-in features that you can get with one install.

# What are examples of some automatic features

- The ability to open PDF's (yeah thats not built in)
- File path auto-completion
- Syntax highlighting colors for basically every language
- Displays who made the last git change for the current line in your current file
- Color-numbers (hex colors or RGB) are highlighted as their actual color
- If you enable the built-in `renderWhitespace`, you'll see spaces, tabs, and newlines instead of only spaces and tabs
- Auto-complete for C++
- Auto-complete for Python

# What are examples of useful commands

Open and run basically any file with `CMD/CTRL + R`, thanks to code-runner
Compare a file between two git branches with `GitHD: View Branch Diff`, thanks to GitHD
Scroll through file history with the GitLens side-bar, thanks to GitLens
Open the current file on GitHub.com with the `Open in GitHub` command, thanks to open-in-github


# What are some useful settings?

```json
{
    // general
    "extensions.ignoreRecommendations": true,
    "extensions.ignoreRecommendations": true,
    "editor.quickSuggestionsDelay": 0,
    "zenMode.centerLayout": false,
    
    // code runner
    "code-runner.runInTerminal": true,
    "code-runner.clearPreviousOutput": true,
    "code-runner.ignoreSelection": true,
    
    // git
    "git.autofetch": true,
    "git.confirmSync": false,
    "git.enableSmartCommit": true,
    
    // fancy visuals
    "editor.cursorSmoothCaretAnimation" : true,
    "editor.cursorBlinking": "expand",
    "editor.smoothScrolling": true,
    "editor.fontLigatures": true,
    "terminal.integrated.rendererType": "dom",
    
    // likely but may not always want
    "editor.multiCursorModifier": "ctrlCmd",
    "editor.find.seedSearchStringFromSelection": false,
} 
```