# My RWXROB's `zet` Bash Utility Go Port

![WIP](https://img.shields.io/badge/status-wip-red.svg)
[![GoDoc](https://godoc.org/github.com/rossim2i2/zet-go?status.svg)](https://godoc.org/github.com/rossim2i2/zet-go)
[![Go Report Card](https://goreportcard.com/badge/github.com/rossim2i2/zet-go)](https://goreportcard.com/report/github.com/rossim2i2/zet-go)
[![Coverage](https://gocover.io/_badge/github.com/rossim2i2/zet-go)](https://gocover.io/github.com/rossim2i2/zet-go)

This is my attempt to port Rob's (rwxrob) `zet` command to go. 

<https://github.com/rwxrob/cmd-zet>
<https://youtube.com/rwxrob>

## Reasons for Binary Port

The main reason I'm looking to port this to Go, is that I cannot install
any version of Linux on my work computer (no bare metal, no WSL(2),
Docker Desktop is out of the question now, no minicubes, etc.). 

I do, however, believe I can get approval to have Vim installed. Based
on my research, you can get Vim running from PowerShell, which should
also be able to execute this `zet` binary.

<https://www.vim.org/download.php>

Also, while Rob integrated YouTube posting into his workflow, this isn't
something I require and can probably cut down on the amount of code to
write.

## Local Repo

As my company doesn't have an Enterprise GitHub account, I'll be storing
all data locally (well on a share drive where it will be backed up). Rob
(rwxrob) has been porting his `zet` tool to rely less and less on
GitHub. 

## Legal

Released under Apache-2.0 License
