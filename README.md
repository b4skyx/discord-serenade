![Banner](https://user-images.githubusercontent.com/55960554/128627327-32d86b66-502a-45e0-a907-57e5489c1a6d.png)

---

## Preview

A comfy easy, easy on eyes theme for Dicsord. Based on the colorscheme Serenade.

### Overview
![Overview](https://user-images.githubusercontent.com/55960554/128630532-eec90d15-b51f-4119-8c53-0e5533bece9a.png)

### Auto Hide on Tile

![auto-hide](https://user-images.githubusercontent.com/55960554/128631307-322d3163-a6cf-4965-9caa-63e9d06d3466.gif)


| Channel Separator                                                                                                           | Message Replies                                                                                                   |
| :---                                                                                                                        | :---                                                                                                              |
| ![Channel Separator](https://user-images.githubusercontent.com/55960554/128630587-58af61b2-ad3e-4f7e-851b-eb85d76fa62d.png) | ![Replies](https://user-images.githubusercontent.com/55960554/128630463-bc00c76a-53de-4a1a-be40-9ae684ee70ae.png) |




## Installation

### Powercord

Clone this repo in your Powercord themes directory

```sh
cd powercord/src/Powercord/themes && git clone https://github.com/b4skyx/discord-serenade
```

### BeautifulDiscord
A nice css injector if you need only the css injection. Hot reloading works very well.
```sh
git clone https://github.com/b4skyx/discord-serenade
beautifuldiscord --css ./discord-serenade/discord_serenade.css
```

### Styues/Web Extension

The theme works very well with Stylus extension. It's a single big file and not refactored for the same reason.
Copy the contents of [css][./discord_serenade.css] file and paste it in your newly created userstyle.

[Install via UserStyles](https://userstyles.world/style/1109/discord-serenade)

## Customization

You can use this theme as a base and customize values according to your usecase.

```css
@import 'https://raw.githubusercontent.com/b4skyx/discord-serenade/master/discord_serenade.css';
.theme-dark {
    --background-primary: #2a2f33;
    --background-secondary: #2e3338;
    --background-tertiary: #373d41;
    --background-tertiary-alt: #31363b;
    --background-accent: #504945;
    --text-normal: #bfddb2;
    --text-spotify: #B3CFA8;
    --text-muted: #bdae93;
    --text-link: #458588;
    --background-floating: #31363b;
    --background-mentioned: #2e3338;
    --header-primary: #B3CFA7;
    --header-secondary: #bdae93;
    --header-spotify: #b8bb26;
    --interactive-normal: #B3CFA7;
    --interactive-hover: #bdae93;
    --interactive-active: #B3CFA8;
    --server-radius: 4%;
}
```
Similarly you can define `.theme-light` if you use the light theme.
