# mdolint
This is a Vale plugin for linting MDO Lab publications.

## Installation
First install [Vale](https://vale.sh/docs/vale-cli/installation/) and the [Vale plugin for VS Code](https://marketplace.visualstudio.com/items?itemName=errata-ai.vale-server).

Then clone this somewhere on your computer and put the following in your config file.
```
"vale.valeCLI.config": "<path-to-vale.ini>",
"vale.valeCLI.path": "<path-to-vale-exe>",
```

## Usage
The default configuration file (`.vale.ini`) also includes some settings for other Vale plugins. Those can be installed from the following locations (typically just by cloning the files to this root directory). You can also comment out those entries if you do not want them activated.

- [proselint](https://github.com/errata-ai/proselint)
- [Microsoft](https://github.com/errata-ai/Microsoft)
- [write-good](https://github.com/errata-ai/write-good)
