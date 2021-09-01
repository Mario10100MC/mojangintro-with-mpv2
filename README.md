# mojangintro-with-mpv2
3 shell scripts that open mpv and minecraft that shows up an mojang studios logo on startup of the game(presumably if you know when the game launches)
mc_start.sh = the launcher
mcintro.sh = contains the mpv script
whatever-you-call-it.sh = the main script that calls the two scripts
 
# Main script(whatever-you-call-it.sh)
```bash
sh ~/Downloads/mc_start.sh | sh ~/Downloads/mcintro.sh
```
