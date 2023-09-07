# VSCode settings

## From marketplace
* html boilerplate
* eslint
* prettier
* material icon theme
* path intellisense
* markdown preview for mermaid
* live server
* json crack
* intent-rainbow
* git graph
* git lens
* code spell checker
* Playwright test for VSCode
* indent-rainbow
* CodeSnap

## Commands to install extension

```
code --install-extension adpyke.codesnap
code --install-extension AykutSarac.jsoncrack-vscode
code --install-extension bierner.markdown-mermaid
code --install-extension Blodwynn.featurehighlight
code --install-extension christian-kohler.path-intellisense
code --install-extension dbaeumer.vscode-eslint
code --install-extension eamodio.gitlens
code --install-extension esbenp.prettier-vscode
code --install-extension JozefChmelar.compare
code --install-extension mhutchie.git-graph
code --install-extension ms-azuretools.vscode-docker
code --install-extension ms-playwright.playwright
code --install-extension ms-vscode-remote.remote-containers
code --install-extension oderwat.indent-rainbow
code --install-extension PKief.material-icon-theme
code --install-extension redhat.java
code --install-extension ritwickdey.LiveServer
code --install-extension sidthesloth.html5-boilerplate
code --install-extension streetsidesoftware.code-spell-checker
code --install-extension VisualStudioExptTeam.intellicode-api-usage-examples
code --install-extension VisualStudioExptTeam.vscodeintellicode
code --install-extension vscjava.vscode-java-debug
code --install-extension vscjava.vscode-java-dependency
code --install-extension vscjava.vscode-java-pack
code --install-extension vscjava.vscode-java-test
code --install-extension vscjava.vscode-maven
```
## settings.json
#### May be present in the profile file
```
{
    "workbench.colorTheme": "Default Dark+",
    "editor.fontFamily": "Fira Code",
    "editor.fontLigatures": true,
    "terminal.integrated.cursorStyle": "underline",
    "editor.guides.bracketPairs": true,
    "workbench.iconTheme": "material-icon-theme",
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": true 
    },
    "eslint.validate": ["javascript", "typescript", "typescriptreact"],
    "diffEditor.ignoreTrimWhitespace": false,
    "editor.formatOnSave": true,
    "audioCues.terminalCommandFailed": "on",
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "workbench.editor.untitled.hint": "hidden"
}
```
