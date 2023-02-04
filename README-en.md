### Performance of My Engineering Projects

>    All test videos are collected on the Internet, and the processing size of all models is above 1080P, which is compressed for the convenience of show.

------

#### Show Content

My research mainly focuses on video enhancement. This repo's content takes old film descratch, video derain & desnow and video quality restoration as examples.

* #### DeScratch

https://user-images.githubusercontent.com/38458343/216776387-2960fb36-1b2e-48d9-ab63-aa7395b51c37.mp4

* #### DeSnow & DeRain

https://user-images.githubusercontent.com/38458343/216776436-b5a45bdf-61a0-46c4-8362-439c7cde6e11.mp4

https://user-images.githubusercontent.com/38458343/216776451-d6bc9d71-247a-49a9-ab0d-595253dfa261.mp4

https://user-images.githubusercontent.com/38458343/216776597-e0f3e0d9-4226-4b20-af24-32968e9c5b8d.mp4

https://user-images.githubusercontent.com/38458343/216776620-81a15642-9b77-42c5-99af-f956f1fb90d6.mp4

* #### Quality Recovery

>    Recovery Principle: Use high-quality reference frames with a limited number of frames and limited amount of information to restore the extremely low image quality sequence of input, then get high-quality sequences of output.

The below gif is the comparison between input and output, where the input sequence is the sequence of the original material compressed to a 200k Bitrate by h.264 encoding.

https://user-images.githubusercontent.com/38458343/216776517-dd196a24-d627-4a7e-b10a-bd42a29b1bd8.mp4

The below is the reference frame. Only one high-quality picture is used as the background information reference, and the output picture quality has been significantly improved after processing.

![show-recover-bgr-1](https://user-images.githubusercontent.com/38458343/216776748-e1ee2f8e-29de-4c15-8b4a-336b46eed500.jpeg)
