# WordleHelper
 A program that helps you beat the Wordle game
## Usage:
```shell
java -jar WordleHelper.jar [-c [maxTries]]
```
Or just double-click the program icon to launch the program in GUI mode.
### Options:
* `-c`: Launch the program in command line mode (GUI mode by default).
* `maxTries`: The maximum number of tries to find the word (only in CLI mode).<br>

**CAUTION:** The external resource is needed - a TXT dictionary file.
This can be found at [MCUmbrella/AWordle/dictionary](https://github.com/MCUmbrella/AWordle/tree/main/dictionary).
You may need to put it under your workdir and rename it to `words.txt`.
It is recommended to use 'common.txt' as the dictionary.
