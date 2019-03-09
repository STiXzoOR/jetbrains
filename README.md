# Dracula for [JetBrains](http://jetbrains.com)

> A dark theme for [JetBrains](http://jetbrains.com).

![Screenshot](https://draculatheme.com/assets/img/screenshots/jetbrains.png)

## Install

~~All instructions can be found at [draculatheme.com/jetbrains](https://draculatheme.com/jetbrains).~~

### Install using Git
You can install the theme and keep up to date by cloning the repo:
```
$ git clone https://github.com/STiXzoOR/jetbrains.git
```

### Install manually
Download using the [GitHub .zip download](https://github.com/STiXzoOR/jetbrains/archive/master.zip) option and unzip them.

>Whenever you see a **{NameOfIDE}**, translate it to the IDE you're using.
<!-- -->
>Whenever you see a **{You}**, translate it to your username on your local machine.

* **Windows:**
	- Download [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts/releases/download/v2.0.0/Hack.zip) and install the **windows compatible** ones.
	- Create a folder called **colors**, if it doesn't exist, inside `C:/Users/{you}/.{NameOfIDE}/config/`.
	- Copy the `./jetbrains/Dracula.icls` file to the `C:/Users/{you}/.{NameOfIDE}/config/colors/` directory on your local machine.
	-	Close and re-open **{NameOfIDE}**!

* **MacOS:**
	<!-- -->
	Run the **install_fonts.sh** by entering:
	```
	$ ./install_fonts.sh
	```

	* Option 1:
		- Create a folder called **colors**, if it doesn't exist, inside `~/Library/Preferences/{NameOfIDE}/`.
		- Copy the `./jetbrains/Dracula.icls` file to the `~/Library/Preferences/{NameOfIDE}/colors/` directory on your local machine.
		- Close and re-open **{NameOfIDE}**.
		- Navigate to `{NameOfIDE} -> Preferences -> Editor -> Color Scheme`.
		- Select **Dracula** from the dropdown menu.
		- Click the **Ok** button to activate the color scheme.

	* Option 2:
		- Open **{NameOfIDE}** and navigate to `Preferences -> Editor -> Color Scheme`.
		- Click the **settings cog** and **Import Scheme**....
		- Navigate to 'Dracula.icls' and apply changes.
		- Close and re-open '{NameOfIDE}'.

* **Linux:**
	- Download [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts/releases/download/v2.0.0/Hack.zip) and install the **non windows compatible** ones.
	- Create a folder called **colors**, if it doesn't exist, inside `~/.{NameOfIDE}/config/`.
	- Copy the `./jetbrains/Dracula.icls` file to the `~/.{NameOfIDE}/config/colors/` directory on your local machine.
	- Close and re-open **{NameOfIDE}**.
	- Navigate to `{NameOfIDE} -> Preferences -> Editor -> Colors & Fonts`.
	- Select **Dracula** from the dropdown menu.
	- Click the **Ok** button to activate the color scheme.

### Note

[Material Theme UI](https://plugins.jetbrains.com/plugin/8006-material-theme-ui) as of `3.0.0` or greater bundles with Dracula scheme and whole IDE theme based on the scheme.

## Team

This theme is maintained by the following person(s) and a bunch of [awesome contributors](https://github.com/dracula/jetbrains/graphs/contributors).

| [![João Pedro Evangelista](https://avatars0.githubusercontent.com/u/5256711?v=3&s=70)](https://github.com/joaoevangelista) | [![Neoptolemos Kyriakou](https://avatars2.githubusercontent.com/u/23358296?v=3&s=70)](https://github.com/STiXzoOR) |
| -------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| [João Pedro Evangelista](https://github.com/sleepiejohn) 																																	 | [Neoptolemos Kyriakou](https://github.com/STiXzoOR) 																																|

## License

[MIT License](./LICENSE)
