# GitHub Action to Create Releases Based on a Keyword
The Hello sayer will greet you from the custom action

# Examples
Here's an example workflow that uses the Keyword Releaser action.  The workflow is triggered by a `PUSH` event and looks for the keyword `"FIXED"`.

```
name: keyword-releaser

on: [push]

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
    - uses: actions/checkout@v1
    - uses: JoJothewatercan/customAction@master
```
