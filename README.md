latex bot - slack
=============

## Overview
This is a Slack Bot, hosted on Beep Boop, that with return any valid Latex string with a link to the formated PNG. All latex images are generated, free of cost, by QuickLatex.

## Usage

### In Slack
- Bot must be hosted on BeepBoop to add to private channels.
  - Limited usage is free
- Add the latex bot to the channel
- Type in "@latexbot " followed by valid latex.
  - Does not need to be wrapped in "$ <latex>latex</latex> $" dollar-sign syntax.
  
<b>Note:</b> To view the images from the returned links in the Slack channel, please ensure that "Preview" is turned on.

### Repository
To create a BeepBoop bot, register a free account with them. Then fork, or otherwise point their repository to this repo. Once activated, the bot should perform as mentioned above.


## References
Boilerplate for the BeepBoop bot are from the start kit repository.
- https://github.com/BeepBoopHQ/beepboop-botkit

Python code is inspired from Ellis Michael's similar slack bot code. Thanks, Ellis!
- https://github.com/BeepBoopHQ/starter-python-bot


## License
See the [LICENSE](LICENSE.md) file for license rights and limitations (MIT).
