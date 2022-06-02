# Clean Maya App Dir
This is a utility repository containing the minimum structure of a maya app dir.

# Usage
1. Add it as a submodule to your git repository

2. Before calling `maya.standalone.initialize()`
    - Copy the `maya` folder to a temp directory
    - set `MAYA_APP_DIR` to the full path of the temp directory
4. After calling `maya.standalone.uninitialize()`:
    - Delete the temp directory