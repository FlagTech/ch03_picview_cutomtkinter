# PicView

PicView is a lightweight, Windows-oriented image-folder viewer built with
Tkinter and CustomTkinter. It keeps image files untouched: rotation and mirror
commands only change the current view.

## Features

- Browse all supported images in a folder with naturally sorted thumbnails.
- Open a folder or drag in either a folder or image file.
- Switch between top/bottom and left/right pane layouts, or maximize either pane.
- Zoom, pan, rotate, and mirror images without modifying the source file.
- View images full screen; animated GIFs play in the viewer.
- Remember the last folder, selected image, pane layout, thumbnail size, and zoom.
- Toggle the interface between English and Traditional Chinese.

Supported formats: JPEG, PNG, WebP, BMP, GIF, TIFF, and TIF.

## Requirements

- Windows 10 or later
- Python 3.11 or later
- [uv](https://docs.astral.sh/uv/)

## Install and run

Clone the repository, then run:


```powershell
uv sync
uv run picview
```

## Controls

Use **Open Folder** or drop a folder/image file onto the window. The thumbnail
slider changes thumbnail size. In the image pane, use the zoom slider or
`Ctrl` + mouse wheel; `+`, `-`, and `0` also adjust or reset zoom. Plain mouse
wheel scrolls an enlarged image. Press `Esc` to leave full-screen mode.

## Development

Run the test suite with:

```powershell
uv run pytest -q
```
