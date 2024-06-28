#### Setting up Starship for System Configuration

Starship is a customizable prompt for any shell. You can find more about Starship [here](https://starship.rs/).

To use my configuration, you'll need to follow these steps:

    1. **Install Nerd Font Fira Code**: Ensure you have the Nerd Font Fira Code installed on your system.

    2. **Move starship.toml**: Place the `starship.toml` configuration file in `~/.config/`.

    3. **Update ~/.bashrc**: Add the following line to your ~/.bashrc file:
        `eval "$(starship init bash)"`

This setup will configure Starship according to the specifications you prefer.
