# List Repos (list-repos)

This utility lists the current active branch on repos present in specified directory. By default it takes the current directory

To install the utility, simply do
```
sudo npm install -g list-repos
```
And in few seconds(or minutes), it should be installed after you enter the password for `sudo`.

To use the utility, type following on CLI,
```
# Check for the current active branch on repos present in parent directory
list-repos ../
```

And will comeup with this output:
```
../
┌─────────────────────────────┬───────────────────┐
│ Directory                   │ Current Branch/NA │
├─────────────────────────────┼───────────────────┤
│ movieDB                     │ master            │
├─────────────────────────────┼───────────────────┤
│ list-repos                  │ master            │
├─────────────────────────────┼───────────────────┤
│ pankajpatel.github.io       │ master            │
├─────────────────────────────┼───────────────────┤
│ time2hack                   │ master            │
├─────────────────────────────┼───────────────────┤
│ ui-bootstrap                │ master            │
└─────────────────────────────┴───────────────────┘

```
