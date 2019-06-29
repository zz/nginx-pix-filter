# What is Nginx Pix Filter

Fork from Nginx Image Filter, and add pixelate feature.

## Nginx Config

```
 pix_filter       crop 180 180;
 # or use below to proxy only
 pix_filter       proxy;
 pix_filter_jpeg_quality 95;  # Adjust to your preferences.
 pix_filter_pixelate 5;  # Adjust to your preferences.
 pix_filter_buffer 12M;
 pix_filter_interlace on;
```

## Todo:
* add blur feature
