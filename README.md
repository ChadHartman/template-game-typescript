## Topics

* Data Types
* Variables
* Functions
* Array or Lists
* If statements
* Conditional loops
* Classes and objects
* Exception handling
* Trees, maps, and more.

## Lesson 0: Setup & Types

1. Install Live Server Extension
2. Install https://github.com/coreybutler/nvm-windows
  * `nvm install latest`
  * `nvm list`
  * `nvm use <version>`
3. `npm install -g typescript`
4. Update `settings.json`:

```json
{
    "telemetry.telemetryLevel": "off",
    "editor.renderWhitespace": "all",
    "terminal.integrated.profiles.windows": {
        "PowerShell": {
            "source": "PowerShell",
            "icon": "terminal-powershell",
            "args": [
                "-ExecutionPolicy",
                "Bypass"
            ]
        }
    },
    "terminal.integrated.defaultProfile.windows": "PowerShell",
}
```

