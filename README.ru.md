## 📟 Alacritty configuration file

<p>Переместите конфигурационный файл по этому пути:</p> 

```bash
~/.config/alacritty/.
```

<br />

<p>
Если вы хотите использовать tmux вместе с alacritty, добавьте эту линию после 
"program=/bin/bash":
</p>

```yaml
args=["-c", "tmux -u"]
``` 

