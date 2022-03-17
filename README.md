Terminator Config setup for [starship](https://starship.rs/)

# Starship Setup  
## Install Fonts (Linux)  
1. Extract FiraCode.zip  
2. Move all tff and otf files to /usr/share/fonts  
`mv dep/*.*tf /usr/share/fonts`  
  
## Install Starship  (Linux)  
1. Download and install starship:  
`curl -sS https://starship.rs/install.sh | sh`  
2. Add Starship startup when terminal starts:  
**(applies for bash, see instructions [here](https://starship.rs/guide/#%F0%9F%9A%80-installation) for other types of shells)**  
`eval "$(starship init bash)"`  
2. Copy starship config to .config dir:  
`cp config/starship.toml ~/.config/starship.toml`  
  
# Load Terminator Config:  
1. Copy terminator config to ~/.config/terminator:  
`cp config/terminator_config ~/.config/terminator/config`  
