# manga-cli-downloads

Fork of 7USTIN's manga-cli.
Now able to download a specfic range of chapters of a manga.

Bash script for downloading mangas into PDF format via the terminal by scraping [manganato](https://manganato.com/)

## Table of Contents

- [Usage](#Usage)
- [Install](#Install)
- [Dependencies](#Dependencies)
- [Preview](https://user-images.githubusercontent.com/81305164/152664895-8c1ad584-eea9-4cb2-8baa-4c27c09eb8a3.mp4)
- [Disclaimer](./DISCLAIMER.md)
- [License](./LICENSE.md)

## Usage

```text
Bash script for reading mangas via the terminal

Usage:
	manga-cli-downloads [Option] [Manga Name]

Options:
	-h, --help		Print this help page
	-V, --version		Print version number
	-u, --update		Fetch latest version from the Github repository
	-l, --last-session    	Open last session
```
Mangas are automatically downloaded to $HOME/manga-cli-downloads/mangas

## Install


### Linux

Install dependencies [(See below)](#Dependencies)

```sh
git clone https://github.com/chrogram/manga-cli-downloads.git && cd manga-cli-downloads
sudo chmod a+rx manga-cli-downloads
sudo cp manga-cli-downloads /usr/local/bin/manga-cli-downloads
```

## Dependencies

- GNU coreutils (ls, tr, rm, du, cat, mkdir)
- GNU diffutils (diff)
- GNU patch
- GNU gawk (awk)
- GNU sed
- curl
- git
- img2pdf
