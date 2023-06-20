# image_caption_text_to_audio

### Summary
Business problem description: See through your Ears is a product designed for people with
visual disabilities. Attempts to make those with disabilities feel more inclusive has been a
continuous effort. Through this product we hope to convert visuals into real time audio so a
person with a visual disability can get a descriptive sense of what is going on around them.
Our project would be building a small Proof-of-Concept to aid this product and if
productized we believe it would be revolutionary.
</br></br>
High-level process approach:
1. The user has a device that continuously takes pictures of their surroundings and sends it
to the model as input.
2. The model uses image recognition and detects all the objects in the image and
generates a caption.
3. Further this caption is input to a text to audio transformer that generates the audio
which is sent to the earpiece of the user.

### Dataset Used
COCO (Common Objects in Context) image captioning dataset which is a widely used dataset in the field of computer vision and natural language processing.

### Caption Pre-processing
![image](https://github.com/sripriya97/image_caption_text_to_audio/assets/59286247/c3616a34-db7d-492f-a0ff-5763a4154d2a)

### Image Pre-processing
![image](https://github.com/sripriya97/image_caption_text_to_audio/assets/59286247/d0ce4338-b21c-4979-8078-a99597f1d154)

### Caption Generator - Stage 1
![image](https://github.com/sripriya97/image_caption_text_to_audio/assets/59286247/066a5e85-b592-445e-ac60-1433d7b9df75)

### Text-to-Speech Converter - Stage 2
- GTTS (Google Text-to-Speech) is a Python library tool that enables text-to-speech conversion using the Google Text-to-Speech API.  
- The library utilizes the power of Google's infrastructure  to generate audio files (mp3) from the predicted captions using a simple and straightforward interface. 
- It has various attributes like Lang to choose the type of language and Slow to decide the the speed of the speech.




