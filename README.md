# This is an example of how to use W3Diff in a git repository to get readable diffs for most Warcraft 3's map/campaign files.
This is very simple, and as such 2 steps are required:
1) Copy everything from this repository's .gitattributes into your own
2) set W3Diff as the tool to create text representations of your binary files like this: `git config diff.w3diff.textconv w3diff`