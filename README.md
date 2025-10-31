## ovl/nro-asset-editor
根据[switchbrew](http://switchbrew.org/index.php?title=NRO#Assets)上描述的 Assets 布局，编辑 Switch 自制软件.nro 文件中的资源数据。

使用此程序，可以为任何 hbmenu/overlays 自制应用添加/更改图标和元数据(图标功能在ovl上禁用)。可从[发布页面](https://github.com/BadFish-HSrui/ovl-nro-asset-editor/releases)下载该程序。

### 图形界面
要运行图形界面，可从发布页面运行预编译的二进制文件，或直接运行 `maker.py`（无需额外参数）。 

### 命令行
```
python3 maker.py [--nro /path/to/file.nro] [--title \"Your App Title\"] [--icon /path/to/icon.(png|jpg)] [--author \"Your Author\"] [--version x.x.x]")
```

运行时，程序会输出 NRO 文件修改前后的信息。任何省略的参数都将保留脚本运行前的值。

<br>
<br>
<br>

## ovl/nro-asset-editor
Edit asset data in Switch homebrew .nro files according to the Assets layout described on [switchbrew](http://switchbrew.org/index.php?title=NRO#Assets).

Using this program it should be possible to add/change icons and metadata for any hbmenu/overlays homebrew apps (with the icon function disabled for ovl). It can be downloaded from the [release page](https://github.com/BadFish-HSrui/ovl-nro-asset-editor/releases).

### GUI
To run the GUI, either run the precompiled binary from the release page, or run `maker.py` without any additional arguments.

### Command Line
```
python3 maker.py [--nro /path/to/file.nro] [--title \"Your App Title\"] [--icon /path/to/icon.(png|jpg)] [--author \"Your Author\"] [--version x.x.x]")
```

When running, it will output the before and after NRO information. Any arguments omitted will retain their value from before running the script.
