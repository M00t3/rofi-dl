# rofi-dl

`rofi-dl` is a simple bash script that utilizes the power of `rofi` and `aria2c`
to manage and download links. It provides a simple and interactive interface to
add, view, clear, and download links.

## Features

- Add links to a playlist
- View the current playlist
- Clear all links from the playlist
- Download the entire playlist using `aria2c`

## Prerequisites

- `rofi`
- `aria2c`

## Usage

1. Clone the repository:

```sh
git clone https://github.com/mooteee/rofi-dl.git
cd rofi-dl
```

2. Make the script executable:

```sh
chmod +x rofi-dl
```

3. Run the script:

```sh
./rofi-dl
```

You will be presented with a `rofi` menu with the following options:

- `add`: Write your link in the prompt to add it to the playlist.
- `show playlist`: Opens the playlist in `lvim` for viewing.
- `clear links`: Clears all links from the playlist.
- `download playlist`: Downloads all the links in the playlist using `aria2c`.

## Configuration

You can configure the script by editing the `config` file in the same directory. The `config` file should define the following variables:

- `download_dir`: The directory where the downloads should be saved.
- `terminal_cmd`: The terminal command to use for opening the playlist and downloading.

## License

This project is licensed under the GPL3 License - see the [LICENSE](LICENSE.txt) file for details.
