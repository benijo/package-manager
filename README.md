# Package Manager Concept

Shell script/php tool

## Commands

List all packages

`pm list` 

Clone vcs repository

`pm clone <vcs-url> --name` / default from composer.json

Pull package

`pm pull <package> | --all`

Remove package

`pm remove <package> | --all`

Test package

`pm test <package> | --all`

Fix package

`pm fix <package> | --all`

Commit package

`pm commit <package> --message`

Push package

`pm push <package> --vcs`

## Tests 

Different types of tests 

- Bash scripts
- Bin scripts

- Exclude/include files
- ...
