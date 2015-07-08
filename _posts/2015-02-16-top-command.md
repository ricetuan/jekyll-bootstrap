---
layout: post
title: "top command"
description: ""
category: linux
tags: [command]
---
{% include JB/setup %}

    top - 08:11:26 up 327 days, 20:44, 76 users,  load average: 1.00, 1.00, 1.00
    Tasks: 1270 total,   3 running, 1243 sleeping,  24 stopped,   0 zombie
    Cpu(s): 23.3%us,  5.1%sy,  0.0%ni, 71.7%id,  0.0%wa,  0.0%hi,  0.0%si,  0.0%st
    Mem:  33009268k total, 31625216k used,  1384052k free,  1326980k buffers
    Swap:  7815612k total,   199720k used,  7615892k free, 22824280k cached
    PID USER      PR  NI  VIRT  RES  SHR S %CPU %MEM    TIME+  COMMAND
    11483 gadmin    20   0 80792  20m 2876 R  100  0.1  13118:55 ruby
     5713 yuki-eto  20   0  105m 105m  772 S    2  0.3 337:27.10 tmux
    24803 liang-fa  20   0 11808 2252  944 R    2  0.0   0:09.01 top
      920 root      39  19     0    0    0 S    1  0.0   2459:49 kipmi0

8番のプロセスの状態。9番はcpu利用率  
Rは実行（可能）の状態です。

<!--more-->

