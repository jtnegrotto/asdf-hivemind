[Hivemind](https://github.com/DarthSim/hivemind) plugin for the [asdf](https://github.com/asdf-vm/asdf) version manager.

## Dependencies

For now, this plugin uses [jq](https://jqlang.github.io/jq/), so it should also be installed (`asdf plugin add jq`). I'll work on removing that dependency when I'm not too lazy to parse JSON in Bash.

## Installation

```
asdf plugin add hivemind https://github.com/jtnegrotto/asdf-hivemind.git
asdf install hivemind latest

# Optional global installation
asdf global hivemind latest
```
