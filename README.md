# Battery-Neofetch

<div align="center" style="margin-top: 25px">

Fully compatible <a href="https://github.com/dylanaraps/neofetch">neofetch</a> configuration with custom scripted 
battery and color bar.

<img alt="example" src="assets/images/example.png" style="margin-top: 15px">

<div style="margin-top: 15px">
<img alt="badge" src="https://forthebadge.com/images/badges/does-not-contain-treenuts.svg">
<img alt="badge" src="https://forthebadge.com/images/badges/built-with-love.svg">
</div>

</div>

## Features

Why this is more than just a simple neofetch configuration:

### Battery bar

<div style="position:relative; left: 5%; margin-top: 25px">

<b>Draining Battery</b><br>
<img alt="bar" src="assets/images/bar_discharge.png" width=80%>

<b>Below 30%</b><br>
<img alt="bar" src="assets/images/bar_low.png" width=80%>

<b>Below 20%</b><br>
<img alt="bar" src="assets/images/bar_critical.png" width=80%>

<b>Below 10%</b><br>
<img alt="bar" src="assets/images/bar_empty.png" width=80%>

<b>Charging</b><br>
<img alt="bar" src="assets/images/bar_charging.png" width=80%>

<b>Full and plugged in</b><br>
<img alt="bar" src="assets/images/bar_full.png" width=80%>

<b>Disabled</b><br>
<img alt="bar" src="assets/images/bar_disabled.png" width=80%>

<b>Battery not found</b><br>
<img alt="bar" src="assets/images/bar_error.png" width=80%>

</div>

### Bottom bar

<div style="position:relative; left: 5%; margin-top: 25px">

<b>Colorful Pacman themed bar</b>
<img src="assets/images/bar_bottom.png" alt="Bar" width=80%>

</div>

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

<div align="center">

Feel free to submit suggestions!<br>
<sub>(No warranties on anything provided, run at your own risk.)</sub>

<img alt="badge" src="https://forthebadge.com/images/badges/built-with-love.svg"><br>

</div>
