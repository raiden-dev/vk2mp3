# vk2mp3

Download VK's index.m3u8 as a single mp3 file.

## Usage

You need `bash`, `curl`, `sed`, `hexdump`, `openssl` and `ffmpeg`. Install missing dependencies using your distro package manager. On Windows [install WSL](https://docs.microsoft.com/en-us/windows/wsl/install-win10) first.

Run this script directly from GitHub replacing `URL` with a full link to index.m3u8 and script will save the audio file as `out.mp3` into the current directory.

```sh
curl -sL http://bit.ly/VK2MP3 | bash -s URL out.mp3
```

## License

[The Unlicense](LICENSE).
