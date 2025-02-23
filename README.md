This library is based on
[clshortfuse/react-native-pcm-audio](https://github.com/clshortfuse/react-native-pcm-audio),
with some improvements:

1. Allows asynchronous writes of streaming audio data (using an unbounded queue)
2. Allows volume control
3. Supports modern react-native (v0.74.5 and v0.78 have been tested, others
   should work)
