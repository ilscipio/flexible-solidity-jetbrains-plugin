![A screenshot of a JetBrains IDE showing the settings panel that allows users to configure Solidity development](https://plugins.jetbrains.com/files/28744/screenshot_576be70d-cecc-4fdd-bc99-accefdf1863a)
# Flexible Solidity
[Flexible Solidity](https://plugins.jetbrains.com/plugin/28744-flexible-solidity) is a plugin for JetBrains IDEs that empowers you to develop, analyze, and deploy smart contracts with confidence.
This repository exists as a community hub and issue tracker.
## Feedback and Support
If you have any feedback, suggestions, or issues with the plugin, please use our Github repository to report them (you may have found it already). You can also use the repository to contribute to the plugin development or request new features. 
- Github repository: [Flexible Solidity](https://github.com/ilscipio/flexible-solidity-jetbrains-plugin)
- Ilscipio Agency: [Ilscipio](https://www.ilscipio.com/en)
- AI Project: [Aivory](https://aivory.net)
## Features
- Syntax highlighting for Solidity smart contract language
- Real-time gas optimization suggestions and security vulnerability detection
- Code completion and navigation for Solidity functions, modifiers, and events
- Smart contract templates for common patterns (ERC20, ERC721, ERC1155, etc.)
- Integration with popular blockchain development frameworks (Hardhat, Truffle, Foundry)
- Built-in ABI viewer and contract interaction tools
- Support for multiple Solidity compiler versions
## Installation
You can install Flexible Solidity from the JetBrains Marketplace or from the IDE settings.
- From the Marketplace: Go to [Flexible Solidity](https://plugins.jetbrains.com/plugin/[YOUR_PLUGIN_ID]-flexible-solidity) and click on the Install button. Then restart your IDE to activate the plugin.
- From the IDE settings: Go to File > Settings > Plugins and search for Flexible Solidity. Click on the Install button and activate the plugin.
## Usage
To use Flexible Solidity, you need to have Solidity smart contract files in your project.
- Install the plugin
- Check that *.sol file types are correctly associated (Settings > File Types > "Flexible Solidity" > List should include *.sol; Add if missing)
- Go to the Settings page (Settings > Tools > "Flexible Solidity") and configure your development environment.
- Add custom contract templates - click on the "+" icon next to the template section. Choose a unique name and hit "Ok".
- Select the newly created template and customize the contract properties in the form below.
- Configure your preferred Solidity compiler version and optimization settings.
- Select "apply" to store all changes.
- Congratulations! You just configured your Solidity development environment. Try it out immediately on your .sol files. Autocomplete, security analysis, and gas optimization suggestions are instantly available.
To develop and analyze smart contracts, follow these steps:
- Open a Solidity contract file in the editor. You will see syntax highlighting, security warnings, and code completion features.
- Use the built-in templates to quickly scaffold common contract patterns.
- Click on the Analyze button on the top right corner to run security and gas optimization checks.
- To compile your contract, click on the Compile button. The plugin will use your configured Solidity version.
- To view the contract ABI and bytecode, click on the ABI Viewer button.
- For integration with Hardhat or Truffle projects, the plugin automatically detects your configuration files.
- To deploy or interact with contracts, use the integrated tools or export to your preferred framework.
