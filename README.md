# Zero-to-Monero

This is a comprehensive conceptual (and technical) explanation of Monero. I will be updating periodically, and publishing full editions when they are complete.

The first and second editions were published on getmonero.org in the Library section: https://web.getmonero.org/library/

## PDFs

Browsers with built-in PDF readers (e.g. recent versions of Firefox) can display PDFs with the following links. Non-supporting browsers may automatically download the PDF if you click the links.

- English: [PDF link](https://raw.githubusercontent.com/UkoeHB/Monero-RCT-report/master/Zero-to-Monero-2-0-0.pdf)
- Russian: [PDF link](https://raw.githubusercontent.com/UkoeHB/Monero-RCT-report/master/Zero-to-Monero-2-0-0-ru.pdf)
- Portuguese: [PDF link](https://raw.githubusercontent.com/UkoeHB/Monero-RCT-report/master/Zero-to-Monero-2-0-0-pt.pdf)
- Italian: [PDF link](https://raw.githubusercontent.com/UkoeHB/Monero-RCT-report/master/Zero-to-Monero-2-0-0-it.pdf)



## Checksums

To calculate a checksum, open the terminal/command line and navigate into the folder containing the file you wish to check. Type 'shasum -a 256 file_name'.

First Edition checksum: 8e235da06fd96fe84701c3812ad47599985c0b72fe05ddd6e4af3c2f573ab28c  Zero-to-Monero-1-0-0.pdf

Second Edition checksum: a784a342141a6c237bdc1ef1c227e6865fae08b2a1b5f10aa4a47af01929a55a  Zero-to-Monero-2-0-0.pdf



## Translations

ZtM is written in LaTeX, so it is not easily integrated with translation services like transifex. The unwieldy solution is to make new Github repositories for translation projects, which contributors can submit pull requests to.

1. Fork this repository. Tell me the name/link of your repository (can email me at ukoe@protonmail.com, or make an Issue on this repository), and what language you are aiming at. I will update this README with your information, so other translators can find your work.
2. Copy the original LaTeX files into a new folder under translations/your_language_folder/source-files-to-translate.
3. Edit those files as you see fit. A service like Overleaf can let you build the document, just make a new Overleaf project -> 'upload project' and select the folder containing all the source files (e.g. clone the Github repo and open your_language_folder in Overleaf). A lot of math and formatting is imbedded in text, so be careful with what you change. Rebuilding with Overleaf lets you see the effect of changes on typesetting and so on.
4. Once you are done editing a file, make a pull request on the translation repo with your changes. Easiest may be to open the relevant file, 'edit' it, and paste in the contents of your personal file containing changes.
5. After the document is done being translated, either make a pull request on my repository here, or let me know and I will pull it in.



## License

This repository is public domain.
