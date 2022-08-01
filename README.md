# Задачи практики

- [ ] Научиться работать с исходными изображениями (через GDAL)
    - По команде `pip install gdal` GDAL не устанавливается, поэтому, согласно способу, описанному в [видео](https://www.youtube.com/watch?v=8iCWUp7WaTk&list=LL&index=1&ab_channel=OpenSourceOptions), нужно:
        - скачать [отсюда](https://www.lfd.uci.edu/~gohlke/pythonlibs/#gdal) подходящий для установленной версии Python GDAL wheel-файл;
        - установить его командой `pip install [wheelfile name]`;
        - после этого GDAL и другие модули можно импортировать так: `from osgeo import gdal`, `from osgeo import ogr`, `from osgeo import osr`.
- [ ] Построить результат классификации в виде карты
- [ ] Научиться ее анализировать (с помощью [QGIS](https://www.qgis.org/en/site/forusers/download.html))