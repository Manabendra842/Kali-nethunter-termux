# Kali NetHunter (Rootless Edition)

```bash
termux-setup-storage
pkg install wget
wget -O install-nethunter-termux https://offs.ec/2MceZWr
chmod +x install-nethunter-termux
./install-nethunter-termux
```

## Usage:

Open Termux and type one of the following:

<!-- Make sure `./install-nethunter-termux` is in sync -->

| Command                   | To                                                      |
| ------------------------- | ------------------------------------------------------- |
| `nethunter`               | Start Kali NetHunter command line interface             |
|`nethunter <command>`     | Run `<command>` in Kali NetHunter environment           |
| `nethunter -r`            | Start Kali NetHunter cli as root                        |
| `nethunter -r <command>`  | Run `<command>` in Kali NetHunter environment as root   |

