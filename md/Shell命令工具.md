# A

## Alias命令
```

alias suz="/usr/local/sh_expect_work/suz.sh"
alias cmt="/usr/local/sh_expect_work/cmt.sh"
alias cdsh='cd /usr/local/sh_expect_work/'
alias cdgit='cd  /Users/aaa/Desktop/code_place/zzj_git/'

```

## ADB 命令

```

adb shell setprop vidc.debug.level 7 


adb shell tcpdump -i any -p -s 0 -w /data/op_pcap.pcap
```

# B
# C
# D
# E
# F
# G
## Git命令
```

git clone  git@github.com:ZukGit/Source_Code.git
git config --global user.name 'yourName'
git config --global user.email yourEmail@xxx.com
git config --global review."gerrit.huaqin.com:8081".username 101002790

git config --list


```

# H
# I
# J
# K
# L
# M
# N
# O
# P

## PS宏   Shell脚本提示符
```
echo $PS1
${ret_status} %{$fg[cyan]%}%c%{$reset_color%} $(git_prompt_info)

【设置显示的样式】
PS1="[XXXXX的MacPro-\`pwd\`]${ret_status} %{$fg[cyan]%}%c%{$reset_color%} $(git_prompt_info)"    【普通权限下显示】

PS1="[\h]\t:\w\$"            //  【root 权限下才能正常显示】
PS1="[XXX的MacPro] \t:\w\$"       //  【root 权限下才能正常显示】

[zhuzhengjiedeMacBook-Pro]10:13:41:~$        // 【  PS1="[\h]\t:\w\$"   显示】
[XXX的MacPro] 10:14:28:~$                   // 【 PS1="[XXX的MacPro] \t:\w\$"   显示】
[XXXXX的MacPro-/Users/aaa]➜  ~            //【脚本提示显示】

```

# Q
# R
# S

## source 命令
```

source .bashrc       //立即更新环境变量 

```
# T
# U
# V
# W
# X
# Y
# Z