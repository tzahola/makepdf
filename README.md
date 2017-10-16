# makepdf
Creates a single PDF booklet from multiple scanned images in a folder structure like this:

```
  input_dir/
    01 - Front cover/
      01 - Front cover outside.png
      02 - Front cover inside.png
    02 - Booklet/
      01 - Booklet front.png
      02 - Booklet 1-2.png
      03 - Booklet 3-4.png
      04 - Booklet 5-6.png
      05 - Booklet back.png
    03 - CD/
      01 - CD front.png
      02 - CD back.png
    04 - Back cover/
      01 - Back cover inside.png
      02 - Back cover outside.png
```

The resulting PDF will contain the folder- and filenames as bookmark titles (without the file extension and leading numerals).

## Usage
```
makepdf input_dir
```
