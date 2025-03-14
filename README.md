# 🦌 ➕ 🚢 🟰 🏴‍☠️
<div align="center">
  <img src="https://moco.mehiz.live/get/@choppeh?theme=moebooru&" />
</div>

## Alias
```sh
alias code="flatpak run com.visualstudio.code $* 2> /dev/null"
alias idea="flatpak run com.jetbrains.IntelliJ-IDEA-Community $* 2> /dev/null"
alias presenterm="~/.asdf/installs/rust/1.75/bin/presenterm"
alias neofetch="hyfetch"
alias e="cd ~/Workspace/extensions-source/"
alias q="exit"
alias edit="micro ~/Workspace/extensions-source/info/sparse-checkout"
alias files="nautilus"
alias arm="rm ~/.var/app/com.google.AndroidStudio/config/Google/AndroidStudio*/.lock"
alias open="xdg-open $1 2> /dev/null"

function u() {
  sh -c 'cd ~/Workspace/extensions-source/ && cbch=$(git branch --show-current) && echo $cbch && git switch main && git pull && git switch $cbch && git rebase main'
}

```
<!--
alias ai='podman ps --format "{{.Names}}" | grep -q "^open-webui$" && { podman stop open-webui; echo "AI encerrada"; } || { podman start open-webui; echo "Iniciando AI..." ; sleep 5; flatpak run org.mozilla.firefox http://localhost:8080 1> /dev/null & }'
alias emu='~/Android/Sdk/./emulator/emulator -avd Pixel_3a_API_34 -gpu host'
-->
