# py-geohex3
Geohex v3.2 python implementation.

## Install

```
python setup.py install
```

## Usage

```
import geohex

## retrieve geohex code from latitude / longitude
zone = geohex.get_zone_by_location(35.65858, 139.745433, 11)
print zone.code
# 'XM48854457273'

## retrieve location from geohex code
zone = geohex.get_zone_by_code('XM48854457273')
print zone.lat, zone.lon
# (35.658618718910624, 139.74540917994662)
```

