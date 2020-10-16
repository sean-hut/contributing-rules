# Git Configuration

Add the following to the copy of the project's git configuration file
`.git/config`.

```
[gpg]
	# Use gpg2 as the program for gpg signing.
	program = gpg2

[core]
	# Convert Carriage Return and Line Feed endings to Line Feed
	# endings on commit but not the other way around. Leave
	# Carriage Return and Line Feed endings in Windows checkouts,
	# but Line Feed endings in Linux, macOS and the repository.
	autocrlf = input

	# Enable blank-at-eol: Looking for spaces at the end of a line.
	# Enable blank-at-eof: Looking for blank lines at the end of a file.
	# Enable space-before-tab: Looking for spaces before tabs at the beginning of a line.
	# Enable tab-in-indent: Looking for tabs in the indentation portion of a line.
	# Disable indent-with-non-tab: Looking for lines that begin with spaces instead of tabs.
	whitespace = blank-at-eol,blank-at-eof,space-before-tab,tab-in-indent,-indent-with-non-tab
```
