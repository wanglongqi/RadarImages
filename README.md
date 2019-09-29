# Singapore geo-referenced radar images

This is an old project to collect, geo-reference and store radar images from NEA Singapre. As the project not goes on well, the collection service is not working very well recently. Thus, I move the collection process here, and update these images to this repository.

The collection is done on a Raspberry Pi. The update freqency can be as high as 5 minutes, and normal delay is within 7 minutes. To reduce the number of commits, the images are commited every 6 hours.

## 50km image data range

```
Driver: GTiff/GeoTIFF
Size is 217, 120
Coordinate System is:
GEOGCS["WGS 84",
    DATUM["WGS_1984",
        SPHEROID["WGS 84",6378137,298.257223563,
            AUTHORITY["EPSG","7030"]],
        AUTHORITY["EPSG","6326"]],
    PRIMEM["Greenwich",0],
    UNIT["degree",0.0174532925199433],
    AUTHORITY["EPSG","4326"]]
Origin = (103.553427090999989,1.478177269000000)
Pixel Size = (0.002674484000000,-0.002710508000000)
Metadata:
  AREA_OR_POINT=Area
Image Structure Metadata:
  COMPRESSION=LZW
  INTERLEAVE=BAND
Corner Coordinates:
Upper Left  ( 103.5534271,   1.4781773) (103d33'12.34"E,  1d28'41.44"N)
Lower Left  ( 103.5534271,   1.1529163) (103d33'12.34"E,  1d 9'10.50"N)
Upper Right ( 104.1337901,   1.4781773) (104d 8' 1.64"E,  1d28'41.44"N)
Lower Right ( 104.1337901,   1.1529163) (104d 8' 1.64"E,  1d 9'10.50"N)
Center      ( 103.8436086,   1.3155468) (103d50'36.99"E,  1d18'55.97"N)
Band 1 Block=217x9 Type=Float32, ColorInterp=Gray
```

## 240km image data range

```
Driver: GTiff/GeoTIFF
Size is 480, 480
Coordinate System is:
GEOGCS["WGS 84",
    DATUM["WGS_1984",
        SPHEROID["WGS 84",6378137,298.257223563,
            AUTHORITY["EPSG","7030"]],
        AUTHORITY["EPSG","6326"]],
    PRIMEM["Greenwich",0],
    UNIT["degree",0.0174532925199433],
    AUTHORITY["EPSG","4326"]]
Origin = (101.790434317294782,3.525492233766941)
Pixel Size = (0.009018185374883,-0.009023367613664)
Metadata:
  AREA_OR_POINT=Area
Image Structure Metadata:
  COMPRESSION=LZW
  INTERLEAVE=BAND
Corner Coordinates:
Upper Left  ( 101.7904343,   3.5254922) (101d47'25.56"E,  3d31'31.77"N)
Lower Left  ( 101.7904343,  -0.8057242) (101d47'25.56"E,  0d48'20.61"S)
Upper Right ( 106.1191633,   3.5254922) (106d 7' 8.99"E,  3d31'31.77"N)
Lower Right ( 106.1191633,  -0.8057242) (106d 7' 8.99"E,  0d48'20.61"S)
Center      ( 103.9547988,   1.3598840) (103d57'17.28"E,  1d21'35.58"N)
Band 1 Block=480x4 Type=Float32, ColorInterp=Gray
```

## 480km image data range

```
Driver: GTiff/GeoTIFF
Size is 480, 480
Coordinate System is:
GEOGCS["WGS 84",
    DATUM["WGS_1984",
        SPHEROID["WGS 84",6378137,298.257223563,
            AUTHORITY["EPSG","7030"]],
        AUTHORITY["EPSG","6326"]],
    PRIMEM["Greenwich",0],
    UNIT["degree",0.0174532925199433],
    AUTHORITY["EPSG","4326"]]
Origin = (99.613775486054038,5.703283058876599)
Pixel Size = (0.018148997587795,-0.018083735753235)
Metadata:
  AREA_OR_POINT=Area
Image Structure Metadata:
  COMPRESSION=LZW
  INTERLEAVE=BAND
Corner Coordinates:
Upper Left  (  99.6137755,   5.7032831) ( 99d36'49.59"E,  5d42'11.82"N)
Lower Left  (  99.6137755,  -2.9769101) ( 99d36'49.59"E,  2d58'36.88"S)
Upper Right ( 108.3252943,   5.7032831) (108d19'31.06"E,  5d42'11.82"N)
Lower Right ( 108.3252943,  -2.9769101) (108d19'31.06"E,  2d58'36.88"S)
Center      ( 103.9695349,   1.3631865) (103d58'10.33"E,  1d21'47.47"N)
Band 1 Block=480x4 Type=Float32, ColorInterp=Gray
```
