# 🌸 Sakura Community Bucket

The community-maintained package repository for [Sakura Package Manager](https://github.com/838288383838383/sakura-package-manager).

## 🚀 Add This Bucket

```powershell
sakura bucket add community https://github.com/838288383838383/sakura-community-bucket
```

## 📦 Available Packages

| Package | Version | Description |
|---------|---------|-------------|
| mpv | 0.37.0 | Media player |
| yt-dlp | 2024.07.02 | YouTube video downloader |
| rufus | 4.5 | USB bootable drive creator |
| flowframes | 1.41.0 | AI video frame interpolation |
| lossless-cut | 7.0.2 | Lossless video editor |
| localsend | 1.13.0 | Cross-platform file sharing |
| obsidian | 1.6.5 | Knowledge base and note-taking |
| stremio | 4.7 | Media center |
| gearlift | 1.0 | Minecraft mod manager |

## 🤝 Contributing

1. Fork this repo
2. Create your manifest in `bucket/<app-name>.json`
3. Fill out the manifest template below
4. Submit a Pull Request!

## 📋 Manifest Template

```json
{
    "name": "your-app",
    "version": "1.0.0",
    "description": "What your app does",
    "homepage": "https://example.com",
    "license": "MIT",
    "url": "https://example.com/app.zip",
    "hash": "sha256-hash-here",
    "bin": ["app.exe"],
    "checkver": {
        "url": "https://github.com/user/repo/releases",
        "regex": "v([\\d.]+)"
    }
}
```

## 📜 Rules

- No malware, adware, or bundled crap
- Must be freely distributable or open source
- URL must point to a stable release (no latest/dev builds)
- Include a hash when possible
- Keep descriptions accurate and non-misleading

## 📁 Structure

```
bucket/
├── mpv.json
├── yt-dlp.json
├── rufus.json
├── flowframes.json
├── lossless-cut.json
├── localsend.json
├── obsidian.json
├── stremio.json
└── gearlift.json
```
