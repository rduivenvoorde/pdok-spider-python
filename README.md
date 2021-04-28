# PDOK Spider Python

    PDOK service spider written in Python (3.8.5).

## Usage

Install dependencies from `requirements.txt` and run:

```
./spider.py --help
```


## Output Example

Outputs list of layers in the following format:

```json
[
 {
        "name": "2020_ortho25IR",
        "title": "Luchtfoto 2020 Ortho 25cm Infrarood",
        "tilematrixsets": "EPSG:28992,EPSG:3857,EPSG:4258,EPSG:4326,EPSG:25831,EPSG:25832,OGC:1.0:GoogleMapsCompatible",
        "imgformats": "image/jpeg",
        "servicetitle": "Landelijke Voorziening Beeldmateriaal",
        "url": "https://service.pdok.nl/hwh/luchtfotocir/wmts/v1_0?request=GetCapabilities&service=WMTS",
        "type": "wmts"
    },
    {
        "name": "Actueel_ortho25IR",
        "title": "Luchtfoto Actueel Ortho 25cm Infrarood",
        "tilematrixsets": "EPSG:28992,EPSG:3857,EPSG:4258,EPSG:4326,EPSG:25831,EPSG:25832,OGC:1.0:GoogleMapsCompatible",
        "imgformats": "image/jpeg",
        "servicetitle": "Landelijke Voorziening Beeldmateriaal",
        "url": "https://service.pdok.nl/hwh/luchtfotocir/wmts/v1_0?request=GetCapabilities&service=WMTS",
        "type": "wmts"
    },
    {
        "name": "SD.AlopochenAegyptiaca",
        "title": "Invasieve Exoten Nederland EU2018 - alopochen aegyptiaca",
        "style": "verspreiding:DEFAULT",
        "crs": "EPSG:28992,EPSG:25831,EPSG:25832,EPSG:3034,EPSG:3035,EPSG:3857,EPSG:4258,EPSG:4326,CRS:84",
        "minscale": "",
        "maxscale": "1e+12",
        "imgformats": "image/png,image/jpeg,image/png; mode=8bit,image/vnd.jpeg-png,image/vnd.jpeg-png8",
        "url": "https://geodata.nationaalgeoregister.nl/rvo/invasieve-exoten/wms/v1_0?request=GetCapabilities&service=WMS",
        "servicetitle": "Invasieve Exoten EU2018",
        "type": "wms"
    },
    {
        "name": "SD.AsclepiasSyriaca",
        "title": "Invasieve Exoten Nederland EU2018 - asclepias syriaca",
        "style": "verspreiding:DEFAULT",
        "crs": "EPSG:28992,EPSG:25831,EPSG:25832,EPSG:3034,EPSG:3035,EPSG:3857,EPSG:4258,EPSG:4326,CRS:84",
        "minscale": "",
        "maxscale": "1e+12",
        "imgformats": "image/png,image/jpeg,image/png; mode=8bit,image/vnd.jpeg-png,image/vnd.jpeg-png8",
        "url": "https://geodata.nationaalgeoregister.nl/rvo/invasieve-exoten/wms/v1_0?request=GetCapabilities&service=WMS",
        "servicetitle": "Invasieve Exoten EU2018",
        "type": "wms"
    }
]
```
