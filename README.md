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

Pour installer, exécutez la commande suivante : <code>code --install-extension NexusSystem-header-0.42.8.vsix</code>.

Allez dans les paramètres de l'extension et ajoutez votre email ainsi que votre nom d'utilisateur.

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

fork from https://github.com/kube/vscode-NSheader

MIT
