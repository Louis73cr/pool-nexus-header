# NS Header for VSCode

This extension provides the Nexus system header integration in VS Code.

```bash
#********************************************************************************#
#                                                                                #
#                                                   ::::    :::     ::::::::     #
#    $FILENAME__________________________________    :+:+:   :+:    :+:    :+:    #
#                                                   :+:+:+  +:+    +:+           #
#    By: $AUTHOR________________________________    +#+ +:+ +#+    +#++:++#++    #
#                                                   +#+  +#+#+#           +#+    #
#    Created: $CREATEDAT_________ by $CREATEDBY_    #+#   #+#+#    #+#    #+#    #
#    Updated: $UPDATEDAT_________ by $UPDATEDBY_    ###    ####     ########     #
#                                                                                #
#********************************************************************************#
```

## Install

Launch Quick Open with <kbd>⌘</kbd>+<kbd>P</kbd> and enter
```
ext install NSheader
```

## Usage

### Insert a header
 - **macOS** : <kbd>⌘</kbd> + <kbd>⌥</kbd> + <kbd>H</kbd>
 - **Linux** / **Windows** : <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>H</kbd>.

Header is automatically updated on save.


## Configuration

Default values for **username** and **email** are imported from environment variables.

To override these values, specify these properties in *User Settings* :

```ts
{
  "NSheader.username": string,
  "NSheader.email": string
}
```

## License

fork from https://github.com/kube/vscode-42header

MIT
