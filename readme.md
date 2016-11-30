# Cross-device Web Cam Viewer

This is a web cam viewer that was built with the [XD-MVC cross-device framework](https://github.com/mhusm/XD-MVC)

The main use case in mind is a large screen showing the web cam and a phone acting as a controller.
The large screen just shows the web cam image and QR code for pairing the phones.

![A large screen with a QR code in the top left corner](public/screenshots/setup.png)

After scanning the code, the phone loads a list of web cams that can be displayed, highlighting the current one.

![The phone UI in portrait mode](public/screenshots/controller_vertical.png)

When the phone is flipped to landscape, it can be used to go back and forward in time and to control the camera position.

![The phone UI in landscape mode](public/screenshots/controller_horizontal.png)