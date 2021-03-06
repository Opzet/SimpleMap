# SimpleMap

This is fully workable sample project on C# for Visual Studio 2019

Sample demonstrates how You can use maps in your projects. 

You can download and run SimpleMap.exe. Or download and compile the source code.

SimpleMap/ExampleForms/FrmMapDownloader.cs demonstrates how to download google map area as single image (GetFullMapThread function) or how to cache google map on local disk (DownloadThread function).

SimpleMap/ExampleForms/Controls/MapCtl.cs demostrates how to draw cached google map images to screen with custom objects as lines, bitmaps etc.

## Features

All in one Winform control
  - No un-managed Code & No Dependancies.
  - Small code size
  - Lightweight

### Rendering

- Fast image draw to screen via GDI+, written pure on C# without any direct mapping to WinApi.

- Double buffering technology, all image changes draw into memory buffer and then changes apply to the screen.

### Tile servers

- Download map images from tile servers (e.g google).

- Cache map tile on disk.

- Download google image file cache to local storage.

- Save google map as one image.

- Base classes to draw any map layers.

## GIS Projection

- Projection of coordinate system through sub classes and operators. Translate google coordinates to longitude and latitude.

- Translate longitude and latitude to google coordinates. Math operators support to work with coordinates. 

- Spatial in-memory index with fast search by coordinates based on google map coordinate system.

- Spatial index tuning.

- Spatial index supported objects are: Point, Line, Rectangle, Poligon(patially suppoted).


## It is absolutely free for use.
