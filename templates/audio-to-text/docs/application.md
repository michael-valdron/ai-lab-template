<!-- Original Recipe README: https://github.com/containers/ai-lab-recipes/blob/main/recipes/audio/audio_to_text/README.md
-->

# Audio to Text Application

## Application Information

The application created by this AI Software Template utilizes the [ggerganov/whisper.cpp](https://huggingface.co/ggerganov/whisper.cpp) model. This is classified as an "Automatic Speech Recognition" model and is licensed under the MIT license.

This application relies on [Langchain's python package](https://python.langchain.com/docs/introduction/) to simplify communication with the Model Service and uses [Streamlit](https://streamlit.io/) for the UI layer. The UI prompts the user to upload an audio file from the following media types:

- .wav
- .mp3
- .mp4
- .flac

After a user uploads an acceptable audio file, the user can view the displayed contents of the uploaded audio file on the screen. You can view an example of this application in the following image:

![image](./images/audio-to-text.png)


If you are interested in the source code for this application, you can find it at [https://github.com/redhat-ai-dev/ai-lab-samples/tree/main/audio-to-text](https://github.com/redhat-ai-dev/ai-lab-samples/tree/main/audio-to-text).