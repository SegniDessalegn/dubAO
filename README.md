# dubAO
A script to dub videos into Afaan Oromo language

# How does this work?
- Meta has released a [Massively Multilingual Speech (MMS)](https://about.fb.com/news/2023/05/ai-massively-multilingual-speech-technology/). It is an ongoing research, also called [fairseq](https://github.com/facebookresearch/fairseq/tree/main/examples%2Fmms), that aims at developing and training language models for more than 1000 lanugages. It supports, TTS (Test To Speach), ASR (Automatic Speach Recognition), and many more.
- One of the supported languages is [Afaan Oromo](https://www.ethnologue.com/language/orm/)

The following are high level steps involved in this project
- we will separate the audio and video
- We will change the audio to text using Meta MMS
- Then we translate the text to Afaan Oromo
- Now, this is where the Meta MMS plays huge part, we will convert the text to audio using Meta MMS
- Finally merge the audio and video

# Wait, there are some HUGE PROBLEMS here
- syncing the audio and video
- Background music might disturb the final output
- What if two or more people talk at the same time?

All of these have their own solutions, but this can clearly be fixed by collaboration of the community.

# Getting Started
- clone this repo
- install necessary packages, this might take time as there are many packages used
- follow the notebook carefully
- That's it, currently it is only script, may be in the future a web or desktop application might be developed

# 👥 You are very welcome to contribute
To contribute to Idea-Log, follow these simple steps
- Fork this repo
- Create a new branch in the forked repo
- Do the work on this branch
- Finally when you are done, create a Pull Request
- Then wait for the approval

# One more thing, please ⭐star⭐ this repo, it means a lot to me ❤️
