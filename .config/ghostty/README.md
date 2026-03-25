Need to symlink: `ln -s ~/.config/ghostty/config.ghostty /Users/drewyang/Library/Application\ Support/com.mitchellh.ghostty/config.ghostty` 

macOS-specific Path (macOS only):
$HOME/Library/Application\ Support/com.mitchellh.ghostty/config.ghostty.
$HOME/Library/Application\ Support/com.mitchellh.ghostty/config.
macOS also supports the XDG configuration path mentioned below.
XDG configuration Path (all platforms):
$XDG_CONFIG_HOME/ghostty/config.ghostty
$XDG_CONFIG_HOME/ghostty/config
if XDG_CONFIG_HOME is not defined, it defaults to $HOME/.config/ghostty/config.
