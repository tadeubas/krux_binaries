# Krux Binaries
Experimental compiled Krux binaries. These binaries are NOT signed and for test purposes only

For stable releases, please download from [official repository](https://github.com/selfcustody/krux/releases/latest)

# Flash Instructions:
Make ktool executable:
```
chmod +x ktool-linux 
```

To Flash TZT run:
```
./ktool-linux -B dan -b 1500000 maixpy_tzt/kboot.kfpkg
```

To Flash Wonder K run:
```
./ktool-linux -B dan -b 1500000 maixpy_wonder_k/kboot.kfpkg
```

To Flash Wonder MV run:
```
./ktool-linux -B dan -b 1500000 maixpy_wonder_mv/kboot.kfpkg
```

To Flash Maix Amigo run:
```
./ktool-linux -B goE -b 1500000 maixpy_amigo/kboot.kfpkg
```

To Flash M5stickV run:
```
./ktool-linux -B goE -b 1500000 maixpy_m5stickv/kboot.kfpkg
```

To Flash Yahboom Aimotion you'll have to manually specify the port, on this example `/dev/ttyUSB0`:
```
./ktool-linux -B goE -b 1500000 -p /dev/ttyUSB0 maixpy_yahboom/kboot.kfpkg
```

To Flash Maix Cube run:
```
./ktool-linux -B goE -b 1500000 maixpy_cube/kboot.kfpkg
```

To Flash Embed Fire run:
```
./ktool-linux -B dan -b 1500000 maixpy_embed_fire/kboot.kfpkg
```

To Flash Maix Dock run:
```
./ktool-linux -B dan -b 1500000 maixpy_dock/kboot.kfpkg
```

Obs: You might need to use "sudo" if your user don't have access to serial port

# Flashing on Windows

Replace './ktool-linux' for 'ktool-win.exe' and `/` for `\` in commands. Ex:
```
ktool-win.exe -B goE -b 1500000 maixpy_amigo\kboot.kfpkg
```
