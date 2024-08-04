# Amber

Amber is a mere setup for [Obsidian](https://obsidian.md/) markdown editor, tailored specifically for scientific research and writing papers. The most importantly, it integrates [Zotero](https://www.zotero.org/) - an amazing reference manager, so you can import Zotero's articles right in Obsidian (with citation and bibliography support!). Imported file is called Literature notes and contain metadata, your notes and annotations for a selected document. Setup vault has an example.
## Requirements
For this setup to work, the following must be installed:

- [Obsidian](https://obsidian.md/) app == **latest** (1.6.7 for 2024-08-4)
- [Zotero](https://www.zotero.org/) >= 6.0.37
    - [ZotFile](https://zotfile.com/) >= 5.1.2 - Advanced PDF management for Zotero **(required for Zotero integration)**
    - [Better BibTeX](https://retorque.re/zotero-better-bibtex/) >= 6.7.214 - makes it easier to manage bibliographic data **(required for Zotero integration)**
    - [Night](https://github.com/tefkah/zotero-night) >= 0.4.23 (optional) - Night theme for Zotero UI & Pdf

### Obsidian setup

1. Download and extract the `amber_setup.zip` file. The `amber_setup` directory will be your new [vault](https://help.obsidian.md/Files+and+folders/Manage+vaults) so rename it and/or place it where you desire.

2. From Obsidian open this directory as a vault, click “Trust author and enable plugins” and *et voila* the setup is finished.

3. Some of the plugins are turned off by default, if you are interested try turning them on. Also, the setup has custom css snippets (you can turn off them in the Appearance settings), the `Tests.md` file is here to help you see the difference with/without snippets.

### Zotero setup
Apart from installing Zotero's add-ons, it is recommended to save all your PDFs from Zotero in `Data/'Zotero Files'/` directory. To do this add the path to this directory in Zotfile preferences, on OS X you will find it here:

*Zotero --> Tools --> ZotFile Preferences... --> General Settings --> Location of files --> select Custom location*

## Contributing

If you know how to improve the setup, feel free to open an issue.

## License
Distributed under the MIT License. See LICENSE for more information.
## Acknowledgment

This setup would not have been possible without Alexandra Phelan's post on academic workflow, definitely check it out.

Links used for this setup:
- [Academic workflow](https://medium.com/@alexandraphelan/an-updated-academic-workflow-zotero-obsidian-cffef080addd)
- [Alternative template for literature notes](https://forum.obsidian.md/t/zotero-integration-error-error-retrieving-item-data-unexpected-end-of-json-input/74220)
