
# Resizable bitmaps (ninepatch images) for Flutter
#9-Patch #ninepatch
what is A 9 patch image ?   is a regular png (.PNG) image which is needful for developers where they require to wrap any content within a background image without pixelating the background image. Usually background images have a fixed height and width, but sometimes we may require background images which does not pixelate though stretched, this now becomes a challenge with regular PNG images.  
example for this images

![enter image description here](https://i.ibb.co/yX4LWVx/bubble-blue-9.png)  
![enter image description here](https://i.ibb.co/ZVq0BkT/orange-9.png)

**Result** :   
![enter image description here](https://i.ibb.co/wWdJtbF/Screenshot-20221012-092152.png)
# how to use

1- This will add a line like this to your package's pubspec.yaml
```yaml
dependencies:
  ninepatch_image: ^0.0.2
```
```dart
NinePatchImage( imageProvider: AssetImage("assets/orange.9.png"),
 child: Text( "Lorem Ipsum is simply dummy text of the printing "))
```


## TODO Progress

- [x] **Stretchable area**
- [x] **Padding box**
- [ ]  **muilti point Stretchable**

## Contributing
Thank you for considering contributing to WidGen! Feel free to contribute in any way you want.
1. Fork the Project
2. Create your Feature Branch (git checkout -b feature/AmazingFeature)
3. Commit your Changes (git commit -m 'Add some AmazingFeature')
4. Push to the Branch (git push origin feature/AmazingFeature)
5. Open a Pull Request


## Contact me via e-mail

For any inquiries or clarifications, you can contact me via e-mail. Just send an email to  [ameral.java@gmail.com](mailto:ameral.java@gmail.com "ameral.java@gmail.com").