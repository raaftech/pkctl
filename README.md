pkctl: a tool for managing ssh public keys on large cross platform environments
=====
pkctl is a public key management and distribution utility. It handles automated ssh-key installation on target systems according to easily defined rules.

Currently it handles ssh key distribution based on grouping rules that you can flexibly use to control who can login as which specific user landscape-wide.

In each subfolder (humans, roles, services and specifics) you'll find an example file that shows the intent of the subdirectory. When you remove the .example extension, it would become a file that pkctl picks up.
