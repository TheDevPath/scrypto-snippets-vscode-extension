# scrypto-snippets README

This is the beginning of the Scrypto Snippets VS Code extension. If you would like additional snippets added submit and issue or pull request to the repo [here](https://github.com/TheDevPath/scrypto-snippets-vscode-extension)

## Features

Start typing scrypto in a rust file to test the first snippet a scrypto use statement. `use scrypto::prelude::*;`

All of the snippets are set with tab stops for renaming default placeholders.

`blueprint` Will scaffold a basic blueprint with `new()` instantiation function stubbed out.

`token` will scaffold a fungible token.

`badge` Will scaffold a fungible badge.

`vault_struct` Will generate the vault declaration for your blueprint stuct.

`vault_empty` Will generate an empty vault constructor.

`vault_w_bucket` Will generate a vault with bucket constructor.

## Requirements

Be sure you have installed the scrypto Cargo Crate.

## Extension Settings

This extension adds VS Code settings through the `contributes.configuration` extension point.

This extension contributes the following settings:

rust language snippets through snippets.json

## Known Issues

Need to add more snippets we're just getting started here.

## Release Notes

First publish, just getting the foundation set up.

### 1.0.0

Initial release of scrypto snippets.

**Enjoy!**
