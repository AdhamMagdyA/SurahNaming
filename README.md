# Surah Naming Script
This script renames a collection of audio files containing Surahs from the Quran, using the Arabic names of each Surah. The script takes the path to the folder containing the audio files as input, and uses a pre-defined dictionary of Surah names to rename each file in the folder.

# Usage
To use the script, follow these steps:

- Place your audio files in a folder.
- open the terminal/cmd and run the following command
`python surah_naming_script.py -p /path/to/audio/files`
- Replace `/path/to/audio/files` with the actual path to your audio files folder.
- you can simply run the py file inside the same folder as the audio files and you will not have to specify the path

- The script will rename each file in the folder using the Arabic name of the corresponding Surah. The new file names will have the format 001-الفاتحة.mp3, where 001 is the Surah number and الفاتحة is the Arabic name of the Surah.
# Example
Suppose you have the following files in a folder called surahs:
- `001.mp3`
- `002.mp3`
- `003.mp3`

To rename these files using the Surah names, you can run the script using the following command:

`python surah_naming_script.py -p surahs`

After the script finishes running, the files in the surahs folder will be renamed as follows:

- `001-الفاتحة.mp3`
- `002-البقرة.mp3`
- `003-آل عمران.mp3`
# License
This script is licensed under the MIT License. Feel free to use, modify, and distribute it as you wish.
