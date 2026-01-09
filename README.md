# timer

Simple countdown timer with notification.

```
$ timer 5m
⏱ Timer: 5:00
⏱ 4:59
...
⏱ Done!
🔔 (notification + sound)

$ timer 25 Focus session
⏱ Focus session: 25:00
```

## Install

```bash
git clone https://github.com/yksanjo/timer-cli.git
chmod +x timer-cli/timer
cp timer-cli/timer /usr/local/bin/
```

## Usage

```bash
timer 5         # 5 minutes
timer 5m        # 5 minutes
timer 90s       # 90 seconds
timer 1h30m     # 1 hour 30 min
timer 25 Work   # with label
```

## License

MIT
