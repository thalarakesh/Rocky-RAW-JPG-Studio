RAW Thumbnail Fix Update

The thumbnail endpoint now logs errors to your Windows user home folder: Rocky_RAW_JPG_thumbnail_errors.log
Embedded JPEG first; fallback to half-size RAW decoding. JPEG thumbnails unchanged.
Upload source files to GitHub, rebuild EXE using Actions.
IMPORTANT: This patch has not been tested against the provided Sony RAW because rawpy is not installed in the test environment.
