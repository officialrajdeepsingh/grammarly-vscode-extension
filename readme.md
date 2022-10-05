vscode Grammarly project demo, I  config the vscode Grammarly extension. To run the Grammarly extension, firstly add the config for your project; you need to add or change the Grammarly configuration in the `.vscode/settings.json` file. 

```json
// .vscode/settings.json
{
    "grammarly.files.include": ["**/README.md", "**/readme.md","**/CONTRIBUTING.md","chapter/*.md","mytext.txt"]
}
```
Add those files in `grammarly.files.include` section that you need to fix spells and grammar with vscode Grammarly extension.

[https://medium.com/frontendweb/how-to-use-grammarly-in-vscode-6767c2e06a71](https://medium.com/frontendweb/how-to-use-grammarly-in-vscode-6767c2e06a71)