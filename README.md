## 📟 Alacritty configuration file

<b>Put it to:</b> 

```bash
~/.config/alacritty/.
```

<br />

<b>
If you want to use tmux with alacritty, add this line to file after "program=/bin/bash":
</b>

```yaml
args=["-c", "tmux -u"]
``` 