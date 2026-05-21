---
name: uimpl
description: Implementation plan management
disable-model-invocation: true
---

Parse user input as `[options]`.

Identify the root directory of the plugin (PLUGIN_ROOT), run `bash {PLUGIN_ROOT}/bin/softeng.sh action uimpl [options]` and follow the instructions in the output.

Options: `--change-folder <path>`, `--plan`, `--no-self-review`

Do not pass options that are not implied by the instructions above or explicitly requested by the user.
