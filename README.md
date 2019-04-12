# zsh-aliases-ls

## Purpose

This zsh plugin enables a number of aliases extending the `ls` command. 

I created it after I had installed `exa` via [Homebrew]() and wanted more finely grained control of the aliases used. I had installed the `common-aliases` plugin, but it used an all-or-nothing approach. So, I refined it.

## Use

To use it, add `zsh-aliases-ls` to the plugins array of your zshrc file:
```
plugins=(... zsh-aliases-ls)
```

## Aliases

```bash
alias l='ls -lFh'          #size,show type,human readable
alias la='ls -lAFh'        #long list,show almost all,show type,human readable
alias lr='ls -tRFh'        #sorted by date,recursive,show type,human readable
alias lt='ls -ltFh'        #long list,sorted by date,show type,human readable
alias ll='ls -l'           #long list
alias ldot='ls -ld .*'
alias lS='ls -1FSsh'
alias lart='ls -1Fcart'
alias lrt='ls -1Fcrt'
```

## Contributors

- [Darrin Tisdale](https://github.com/darrintisdale)
