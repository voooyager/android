图形系统
===
- [skia](https://skia.org/docs/)
```
Android采用Skia作为2D图形库
```
- [ImageDecoder](https://developer.android.com/ndk/guides/image-decoder?hl=zh-cn)
```
NDK ImageDecoder API 提供了一种标准 API，供 Android C/C++ 应用直接解码图像。应用开发者不再需要使用 Java API（通过 JNI）或第三方图像解码库。此 API 与 Bitmap 模块中的编码函数结合使用，可实现以下功能：
缩小原生应用和库的大小，因为它们不再需要链接自己的解码库。
应用和库可自动从解码库的平台安全更新中受益。
应用可以直接将图像解码到其提供的内存中。然后，应用可以对图像数据进行后处理（如果需要），并将其传递给 OpenGL 或其绘制代码
```
