# TECHIN-513-Final-song-to-emoji
## First Step: STFT for Human Voice Extraction and Lyrics Recognition
1. Download the folder Dataset and Demo Song.
2. Run the DSP_Evaluation_Example -- Photograph.ipynb in folder ALL THE CODES. Follow the instruction inside, and remember to provide the path name of the song file in the Demo song.
3. You can see the difference in frequency of pure bgm and bgm + human voice. Following the instruction inside, remember to provide your own OpenAI API to do the voice to txt recognition.

## Second Step: Lyrics to Emoji
### Emotion Analysis Track
1. Run the Emoji_Generation_NLP_Included.ipynb in folder ALL THE CODES. Follow the instruction inside to train the model. It may takes 10-20 minutes if you have a nice GPU.
2. With the NLP Model, you will be able to get 8 emotion vectors from the lyrics you just got from the first step.
3. Use the emotionVectorToEmoji function, and you can get the emoji from the vectors!

### Context Analysis Track
1. Keep going with Emoji_Generation_NLP_Included.ipynb and you can use text embedding to get 1536 numerical vectors from the lyrics.
2. Use the emotionVectorToEmoji function, and you can get the emoji from the vectors!
