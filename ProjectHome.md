Automatically upload images and video taken on you android device to a server.

This project has two goals. 1) to provide an automatic upload facility in the form of an android application & 2) a server endpoint to accept the uploaded files, provide notifications and filing functionality.

The android application will listen for new images and video taken by the camera application. When a network is available it will compress and send the image/video to the configured server component.

The server will accept the media file, notify interest parties and allow the file to be moved (via a ui) to another location I.e. NAS, cloud storage, etc. Bulk operations will be available.