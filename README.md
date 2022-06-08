# Entity Configurations

### Installation

If you wish to install one of the above configurations, the best way to do it is in-app via the Snipers tab.

### Creating a Config

At the moment, the configuration file is still **heavily in progress** and is subject to many changes, if you have a specific request about the configuration file, please create a **Pull Request** and specify your change


Example MCSniperGO Configuration -
```json
{
    "name": "MCSniperGO",
    "version": "???",
    "execution": {
        "mode": "cli",
        "keyInputs": {
            "press enter to exit": "Enter"
        },
        "error": {
            "please put one account in the accounts.txt file": "NO_ACCOUNTS",
            "failed to grab droptime from all APIs": "ERROR",
            "parse error": "ERROR"
        },
        "executable": {
            "command": "MCsnipergo_{{version}}_{{platform}}_64-bit.exe",
            "arguments": "start --username {{username}} --offset {{offset}}"
        }
    },
    "installation": {
        "repo": ""
    }
}
```
