Image Upload and Resize v1.0

============================
1. What does this script do?
============================
This script will upload one or more images to a file location of your choice,
and will also generate a correctly cropped thumbnail, and resize the full-size
image to a maximum dimension of your choice.

============================
2. How do I use it?
============================
There are two files: index.php and imageUpload.php. Index.php contains a simple
form for selecting the files to upload. imageUpload.php handles the upload.

At the top of the imageUpload.php file, there are some variables that need to be
modified to your preferences. Once you have decided on a file path, you must
make sure it exists, and also create a 'thumbs' directory underneath it.

IMPORTANT: You will also need to edit lines 40 and 44 - as described in the
comments of the imageUpload.php file.