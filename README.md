# SYMBOLIST
SYMBOLIST is a graphic notation environment for music and multimedia. SYMBOLIST is based on an Open Sound Control (OSC) encoding of symbols representing multi-rate and multidimensional control data, which can be streamed as control messages to audio processing or any kind of media environment. Symbols can be designed and composed graphically, and brought in relationship with other symbols. The environment provides tools for creating symbol groups and stave references, by which symbols maybe timed and used to constitute a structured and executable multimedia score.

## Pre-requisites
* **Warning!** For now, symbolist have been compiled, tested and executed only under the macOS platform (starting with version 10.10 Yosemite). Thus, all instructions and informations published here and in the [SYMBOLIST Wiki](https://github.com/ramagottfried/symbolist/wiki) are worth only for this paltform.  
* **Bravura font**. symbolist uses the Bravura font to integrate traditional music notation symbols in its palette. Therefore, the Bravura font must be installed in your computer if you want to use these symbols. You can download the Bravura font at https://www.smufl.org/fonts/. To complete the installation of the Bravura font, copy the bravura_metadata.json file (you'll find it in the Bravura font zip file) into your /Library/Fonts/bravura folder (create this folder if it doesn't exist).

## Project's architecture
Here is described the architecture of the symbolist project.

* **Builds**: contains three subfolders, one for each OS: Linux, Windows and macOS. The symbolist's XCode project is to be found under the *MacOSX* subfolder.
* **Source**: symbolist source code.
* **SymbolistTests**: contains all files for unit tests and integration tests in symbolist.
* **JuceLibraryCode**: contains all headers generated by the Projucer app to include JUCE library's modules into the symbolist source code.
* **Documentation**: contains the Doxygen directory to generate the doc in html format, and the Images directory where are stored the different images populating the Wiki.
* **OM**: contains all files related to the integration of symbolist in the OpenMusic language.
* **max**: contains all files related to the integration of symbolist in the Max language.
* **symbolist.jucer**: the symbolist Projucer file, to manage and generate projects for specific IDE (XCode, Visual Studio…).
* **symbolist-deploy**: bash script to automate the deployment of symbolist as a Max and an OpenMusic object.

## SYMBOLIST's Releases

Please find all releases of the SYMBOLIST Max (and soon OpenMusic) objects in the [Releases](https://github.com/ramagottfried/symbolist/releases) page.

## Contributing to the project

For developers eager to contribute to the SYMBOLIST project, the setting of the work environment and the coding guidelines are described in the [SYMBOLIST Wiki](https://github.com/ramagottfried/symbolist/wiki). 
