# Speaker-Recognition-System
Voice recognition is primarily categorized into two components: speaker identification and speaker
verification. Speaker identification involves identifying which registered speaker is responsible for a given utterance from a known group of speakers. On the other hand, speaker verification assesses and decides whether a speaker’s claimed identity is accepted or rejected. In this project, our primary focus lies in the realm of speaker identification
## Dataset
The dataset that we have used is the "Prominent Leader’s Speeches." It has a uniquely curated
collection of one-second audio clips extracted from speeches delivered by five globally recognized
leaders—Benjamin Netanyahu, Jens Stoltenberg, Julia Gillard, Margaret Thatcher, and Nelson
Mandela. Each audio clip is encoded in the PCM format, ensuring a standardized and high-quality
representation with a consistent sampling rate of 16kHz. To enhance the dataset’s realism and
account for real-world scenarios, a dedicated folder contains background noise audio files, including instances of laughter and applause. We analyzed the dataset and found that the Speaker’s folders are well-balanced.

## Model Training
Our speaker recognition methodology makes use of GMM and is divided into two models based on
the way in which we add noise to our dataset. We have trained 5 different GMMs, one for each class
of speaker, which helps provide more robust results.

## Results
Our model utilising Gaussian Mixture Models (GMM), showcases remarkable performance metrics.
Precision, recall, and F1-score for each class with an overall accuracy of 99 percent. The robustness of the model is evidenced by its ability to effectively distinguish speakers, as supported by the macro and weighted average metrics. The integration of GMM for speaker identification aligns with established practices in the field, highlighting the paper’s commitment to leveraging proven methodologies. This
research contributes to the speaker recognition domain by emphasizing the efficacy of traditional machine learning techniques, specifically GMM, in achieving outstanding results, thereby providing valuable insights for further advancements in the field
