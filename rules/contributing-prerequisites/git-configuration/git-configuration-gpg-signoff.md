# Git Configuration

Add the lines of git configuration below to your version of the
project's git configuration file `.git/config`.

You may also want to add this configuration in addition to those below:

```
[user]
	signingKey = <fingerprint-without-spaces>
```
[Lookup your `<fingerprint-without-spaces>`.][key-id]

For more information on these git configuration settings see `man
git-config`.

```
[gpg]
	# Use gpg2 as the program for gpg signing.
	program = gpg2

[commit]
	# Use gpg2 to sign commits.
	gpgSign = true

[format]
	# Add sign off line to commits.
	signOff = true

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

[transfer]
	# git-receive-pack will check all received objects.
	fsckObjects = true

[fetch]
	# git-fetch-pack will check all fetched objects.
	fsckObjects = true
```

[key-id]: <https://github.com/sean-hut/contributing-rules/blob/develop/reference/gpg2-key-id-for-git.md>
