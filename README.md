# Introduction

This tool allows you to quickly check and switch Azure subscriptions via the azure-cli tool.

# Compatibility

This script has been tested on MacOS (zsh) and Ubuntu Linux (bash)

# Installation

Simply drop the file in one of the directories specified in the `$PATH` environmental variable. Ensure that the file has `EXECUTE` permissions set.

Remember to set the `$PERSONAL_SUB` environmental variable to the Subscription ID of your Azure sub. This can be done with the following command:
`export PERSONAL_SUB="SUB_ID_GOES_HERE"`

Command above can be added at the end of `~/.zshrc` and `~/.bashrc` for persistence.

# Use

1. log into your Azure  via `az login`
2. Type `azhelper` in the terminal
3. follow the on-screen instructions
