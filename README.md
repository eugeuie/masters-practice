# Задачи практики

- [x] Научиться работать с исходными [изображениями](https://onedrive.live.com/?authkey=%21AEjVPTIOgFOYu8k&id=706392B596BF0CFA%215501&cid=706392B596BF0CFA) (через GDAL)
    - По команде `pip install gdal` GDAL не устанавливается, поэтому, согласно способу, описанному в [видео](https://www.youtube.com/watch?v=8iCWUp7WaTk&list=LL&index=1&ab_channel=OpenSourceOptions), нужно:
        - скачать [отсюда](https://www.lfd.uci.edu/~gohlke/pythonlibs/#gdal) GDAL wheel-файл, подходящий для установленной версии Python;
        - установить его командой `pip install [wheelfile name]`;
        - после этого GDAL и другие модули можно импортировать так: `from osgeo import gdal`, `from osgeo import ogr`, `from osgeo import osr`.
    - [Документация GDAL](https://gdal.org/)
- [x] Выполнить классификацию по этим изображениям
- [x] Построить результат классификации в виде карты растительного покрова
- [x] Научиться ее анализировать (например, визуально с помощью [QGIS](https://www.qgis.org/en/site/forusers/download.html))