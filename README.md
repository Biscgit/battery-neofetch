# [Battery-Neofetch](https://github.com/Biscgit/battery-neofetch)

**Fully compatible [neofetch](https://github.com/dylanaraps/neofetch) configuration with custom scripted battery and
color bar**

![Example](assets/images/example.png)

## Features

### Battery bar

- Normal drain <br>
  ![Bar state](assets/images/bar_discharge.png)


- Below 30% <br>
  ![Bar state](assets/images/bar_low.png)


- Below 20% <br>
  ![Bar state](assets/images/bar_critical.png)


- Below 10% <br>
  ![Bar state](assets/images/bar_empty.png)


- Charging <br>
  ![Bar state](assets/images/bar_charging.png)


- Full and plugged in <br>
  ![Bar state](assets/images/bar_full.png)


- Disabled <br>
  ![Bar state](assets/images/bar_disabled.png)


- Battery not found <br>
  ![Bar state](assets/images/bar_error.png)

### Bottom bar

- Colorful Pacman themed bar <br>
  ![Bottom Bar](assets/images/bar_bottom.png)

### Other

- Planet ASCII-art with colorful stars
- Extendable with own configs

## How to install

Open a bash prompt and execute the code below.
It will create a backup of your current neofetch config.

```shell
git clone https://github.com/Biscgit/battery-neofetch.git
cd battery-neofetch
chmod +x install.sh
./install.sh
```

**NOTE: install.sh is a WIP**

Check installation by typing `neofetch` into the command prompt and switch the Distro Icon to your preferred one.
> [!IMPORTANT]
> You need to have Nerdfonts installed on your machine.

Finally, you can configure the settings in the configuration file as your needs fit.

> [!NOTE]
> If "Battery error" shows up on running `neofetch`,
> check if the correct battery has been selected in the configuration file.

## ToDo's

- [x] Battery bar icons
- [x] Fix bar when battery charge is limited
- [ ] Create simple install script
- [ ] Make example images better looking
- [ ] Option to make stars the same color as the battery bar

## Thank you

Feel free to create suggestions!

<sub>
(No warranties on anything provided, run at your own risk.)
</sub>
