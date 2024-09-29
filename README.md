# cd-memo
A shell script cd implementation that memorizes your working directory across sessions
## Behavior
Any newly opened shell instance will be right where you left off
## Usage
Add `source /usr/sbin/cd-memo-init` to your shell init \
For example:
- For bash, this will be `~/.bashrc`
- For zsh, this will be `~/.zshrc`
- For fish, this will be `~/.config/fish/config.fish`
## What shell am I using?
You can check by executing \
`echo $0`
