# Youtube Music Tauri App

Just a simple Youtube Music Tauri app to not have to launch a heavy Web browser for it :^)

## Why ?

[This Electron app](https://github.com/th-ch/youtube-music) already exists, I know. But I find it stupidly heavy for what it is supposed to do. The only thing I want from an app like this is to consume less resources it would than on a regular browser, and it is not the case for Electron.

## A note about webkit2gtk

I discovered while doing this little project that ``webkit2gtk`` [is unable to launch a video](https://github.com/tauri-apps/tauri/issues/6512), so this app won't work on Linux/*BSD. People that use MacOS would be pleased to tell me if it works on their OS.

## Licensing

This is licensed under my own license named **Do whatever the fuck you want to do with this as long as you're not behaving like an asshole**. Everything is in the name.


