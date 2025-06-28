Attend to What I Say: Highlighting Relevant Content on Slides

📌 Overview The goal of this project is to automatically highlight slide content that is relevant to a given spoken narration, enhancing understanding and accessibility for viewers. This is particularly useful in educational and conference presentation settings where slides and speech are tightly coupled.

This repository includes:

A curated dataset of slide frames aligned with audio and transcripts Code for different methods

Dataset The dataset consists of: Slide frames extracted from conference talks Speech transcripts (aligned to slides) Ground-truth highlight annotations marking slide regions relevant to each spoken segment

Details:

Format: Images (PNG/JPG), Transcripts (SRT), Annotations (JSON), Audio (MP3) Collected from various academic conferences (NeurIPS, ICML)

Dataset Statistics:
The total duration of the dataset exceeds one hour. Figure~\ref{fig:distribution} illustrates the distribution of presentation slides based on the duration of their corresponding audio segments, highlighting that most slides are associated with audio segments lasting between 10 and 20 seconds. The slide text corpus contains 7,466 unique alphabetical words, while the transcript text comprises 6,708 unique alphabetical words. Additionally, Figure~\ref{tab:audio_stats} provides statistics on the audio segment durations, word count in \textsc{ocr}, and word count in \textsc{asr}, including the minimum, maximum, average, and median values. This dataset serves as a valuable resource for evaluating the approach discussed below.