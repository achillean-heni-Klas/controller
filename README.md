# zest-minimal-package

lightweight process monitor. logs cpu/mem every 5s.

```bash
curl -sL zest-minimal-package.run/get | sh
zest-minimal-package watch
```

output:

```
PID    NAME         CPU   MEM
1234   node         23%   450MB
5678   postgres     8%    1.2GB
9012   redis        2%    85MB
```

export to csv:

```bash
zest-minimal-package watch --csv > data.csv
```

that's it. no config. no daemon.

MIT • [github.com/proc-watch/zest-minimal-package](https://github.com/proc-watch/zest-minimal-package)
