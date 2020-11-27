# Testbed
A testbed for the game library API.

git submodule update --init --recursive

In order for collaboration to work over Git, you must update your .gitconfig file found in your username profile root directory with:

    [merge]
    tool = unityyamlmerge

    [mergetool "unityyamlmerge"]
    trustExitCode = false
    cmd = '<< path to UnityYAMLMerge >>' merge -p "$BASE" "$REMOTE" "$LOCAL" "$MERGED"
    
**Example paths:**

    Mac: /Volumes/Hard\ Drive/Applications/Unity/2019.4.15f1/Unity.app/Contents/Tools/UnityYAMLMerge
    Windows: C:\Program Files\Unity\Editor\Data\Tools\UnityYAMLMerge.exe
