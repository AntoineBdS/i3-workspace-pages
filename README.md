# i3-workspace-pages
Small script to extend the i3 workspaces to multiple 'master' pages of 'child' workspaces

## Script usage
`i3-workspace-pages <command> <master> <child>`

- command:
  - s2c:    switch to child
  - s2m:    switch to master
  - mc2c:   move focused container to child
  - mc2m:   move focused container to master
  
- master:
  - Name of the page
  
- child
  - Number of the child workspace

## How to effectively use it
This script is intended to be used with shortcuts in the i3 config file. See "i3_config_sample" for an example with 10 pages [a-j] each containing ten workspace [1-10].

