### This is an example of how to use [W3Diff](https://github.com/BogdanW3/W3Diff) in a git repository to get readable diffs for most Warcraft 3's map/campaign files.
1. Copy everything from this repository's .gitattributes into your own
2.	a) put W3Diff somewhere on your path and set it as the conversion tool with `git config diff.w3diff.textconv w3diff`\
	b) put W3Diff in your repository instead and set it as the conversion tool with `git config diff.w3diff.textconv ./w3diff`
	
I recommend you put the gitattributes in your .gitignore so you can comment out lines containing the extensions you want to exclude when you don't want then to have a detailed diff.