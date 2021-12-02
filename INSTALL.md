### [ghostwriter](https://wereturtle.github.io/ghostwriter/)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

    git clone https://github.com/dracula/ghostwriter.git

#### Install manually

Download using the [GitHub .zip download](https://github.com/dracula/ghostwriter/archive/master.zip) option and unzip them.

#### Copy theme to ghostwriter config directory

On most UNIX-based systems the following should work:

`mkdir -p ~/.config/ghostwriter/themes && cp ghostwriter/Dracula.json ~/.config/ghostwriter/themes/Dracula.json`

If that does not work on your machine, manually copy `Dracula.json` to the themes directory in the ghostwriter config directory:

- Windows: `C:\Users<your_user_name>\AppData\Roaming\ghostwriter\themes`
- Windows portable mode: `<your_ghostwriter_portable_folder>\data\themes`
- GNU/Linux: `~/.config/ghostwriter/themes`
- macOS: `~/Library/Application Support/ghostwriter/themes`

#### Activate theme in ghostwriter

Go to `Settings | Themes...`, select `Dracula`

![Activate Theme](https://raw.githubusercontent.com/dracula/ghostwriter/master/activate-theme.png)
