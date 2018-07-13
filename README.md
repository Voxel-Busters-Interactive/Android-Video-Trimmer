### Project Introduction
Realize the use of ffmpeg for video cropping and compression on Android. Open source projects like video cropping are personally scarce.
Not as much as ios open source, I also constantly explored in the development process, which also encountered a lot of problems.
Now let's talk about the implementation of this project.

### Use to related technology
* FFmpeg implements cropping video
* FFmpeg achieves video compression after cropping
* ContentResolver gets all video resources
* Play video with VideoView
* Display a frame image of a video using a horizontally scrolled ListView
* Get a Bitmap of a video frame via MediaMetadataRetriever
* View customization

### Functional expansion thinking
Video cropping function often involves compression and uploading of video. Each function is high-level content in Android development. For example, video compression, compression library is actually open source,
However, it can achieve high compression ratio, fast compression speed, and at the same time guarantee the quality of video. Such open source libraries are still relatively rare.
In this project, I simply implemented the cropped video compression. To achieve a good compression effect, I also need to adjust the video compression parameters in the project.
You can carry out the corresponding porting and modification of the fork project.

### Other
* After the video crop is completed, the cropped video output will be saved to the Android->data->package name->cache folder of the app.

### Welcome to star, fork, and issues.

### License

See the [LICENSE](https://github.com/iknow4/Android-Video-Trimmer/blob/master/LICENSE) file.

#### Video screenshot of project refactoring

<img src="https://github.com/iknow4/iknow.Images/blob/master/gif/videoTrim2.gif?raw=true" width="400" height="700" alt="videoTrim2"/>

#### Video screenshot before project refactoring
<img src="https://github.com/iknow4/iknow.Images/blob/master/gif/videoTrim.gif?raw=true" width="400" height="700" alt="VideoTrim"/>


### Other
* After the video crop is completed, the cropped video output will be saved to the Android->data->package name->cache folder of the app.

### Welcome to star, fork, and issues.
