### 

```
./tools/configure.sh -l nucleo-f103rb:nsh

https://zhuanlan.zhihu.com/p/350962581

openocd -f interface/stlink-v2.cfg -f target/nucleo-f103rb.cfg -c 'init' \
  -c 'program nuttx/nuttx.bin verify reset' -c 'shutdown'
  

```

