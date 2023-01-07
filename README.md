# automator-actions
Automator Apps and workflows to add EXIF tags to images using Exiftool.

To use these workflows, you must have Exiftool for macOS installed for terminal use.

1. EXIF-DateTime -- If you have scanned images that lack internal DateTime metadata, many photo organization programs will not know where to place this image in your library, and will normally treat it as if it was taken on the day the file was created rather than the actual date the photo was taken. This tool can work either as a finder workflow or a drag and drop application. It will set the DateTime properly, and then rename the files using the (YYY-MM-DD) HH-MM-SS.jpg naming convention. To use, drag images to this app or workflow and get prompted to add a DateTime to the Exif metadata. The date gets added to all relevant datatime metadata and the file is then renamed based on this date. If you prefer not to have the file renamed, chop off the last two automator action.
