# Git

## Configuration

To set a configuration value, use `git config --global <setting>`
To remove a value, use the `--unset` flag.

`--global`: Applies configuration changes to the global Git configuration file (~/.gitconfig), affecting all repositories for the current user.
`--system`: Applies configuration changes to the system-wide Git configuration file ($(prefix)/etc/gitconfig). Requires administrative privileges and affects all users on the system.
`--local` : Applies configuration changes to the local Git configuration file (.git/config) within the current repository. This is the default scope if no other scope is specified.
`--file` <file>: Applies configuration changes to a specific configuration file instead of the default configuration files. Useful for applying settings to custom configuration files.

--list: Lists all configuration settings for the specified scope (global, local, or system).
--show-scope: Shows the scope (global, local, system) of the configuration setting being applied or queried.

| Command | Description |
|--|--|
| `help.autocorrect immediate` | Assumes the closest match and runs the command |  

## Branches
| Command | Description |
|--|--|
| `git checkout -` | Switches to the previous branch |

