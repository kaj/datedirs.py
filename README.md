# datedirs.py

Move images (photos) into a year/month/day directory structure based
on exif information.

It finds all `*.jpg` images in a given directory and moves them into a
`$BASE/$YEAR/$MONTH/$DAY/` directory structure (the `$BASE` is
hardcoded).
Any missing directory is created as needed.
Any file that has the same base name as the image but a different
suffix (e.g. a `.txt` or `.md` file with notes about the image or the
camera raw format of the image) is moved along with the image.
