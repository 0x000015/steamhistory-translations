# SteamHistory Translations

This repository contains the translations for SteamHistory.net

[![Crowdin](https://badges.crowdin.net/steamhistory-translations/localized.svg)](https://crowdin.com/project/steamhistory-translations)

## Contribution Guidelines

The localization workflow is powered by Crowdin, Inlang, and Paraglide. Contributions are accepted through the following channels:

### Crowdin (Recommended)
The preferred and easiest way to contribute is through [the Crowdin page](https://crowdin.com/project/steamhistory-translations)

### Development Environment
Alternatively, you can contribute locally through the Sherlock (Inlang) extension for Visual Studio Code:
1. Clone the repository.


```
git clone https://github.com/0x000015/steamhistory-translations
```


2. [Install the Sherlock](https://marketplace.visualstudio.com/items?itemName=inlang.vs-code-extension) (Inlang) extension.
3. The extension will provide an integrated translation interface within the IDE

### Manual Submissions
Direct modifications to the JSON files within the `messages/` directory are accepted via Pull Request. Contributors must ensure that the JSON structure remains valid and follows the existing key-value format.

## Repository Structure
- messages/: Localization files for all supported locales.
- project.inlang/: Configuration and project-specific settings for the Inlang ecosystem.

## License
By contributing to this repository, you agree to license your work under the MIT License.
