---
name: upr
description: Create pull request from current branch
disable-model-invocation: true
---

Parse user input as `[options]`.

Identify the root directory of the plugin (PLUGIN_ROOT), run `bash {PLUGIN_ROOT}/bin/softeng.sh action upr [options]` and follow the instructions in the output.

Possible options: `--no-archive`

Do not pass options that are not implied by the instructions above or explicitly requested by the user.
