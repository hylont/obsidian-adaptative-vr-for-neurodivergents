---
author: Seyed Muhammad Hossein Mousavi
year: 2023
doi: 10.3389/fpsyg.2023.1280136
---
# Intro

>“Emotion Recognition (ER) is the task of detecting emotions from a set of observed modalities” (Mousavi et al., p. 1)

>“The integration of ER in VR settings makes it possible to implement immersive yet personalized experiences that adapt to the users based on their emotions, therefore further increasing their engagement.” (Mousavi et al., p. 2)

## Physiological measures

>“Electrodermal activity (EDA) signals, also known as Galvanic Skin Response (GSR), are recorded by sensors that measure changes in skin conductance which can be indicative of emotional arousal levels.” (Mousavi et al., p. 3)

>“Heart Rate Variability is another source of information that can be used to reflect the changes in the affective state. In particular, Electrocardiogram (ECG) is a robust heart rate monitor that requires connecting multiple electrodes to subjects’ chests. A less intrusive and more lightweight measurement of heart rate variability is Blood Volume Pulse (BVP)” (Mousavi et al., p. 3)

>“Skin temperature (SKT) is also used for affect recognition, although it could be influenced by several factors and typically is a weaker signal compared to EDA and BVP” (Mousavi et al., p. 3)

## Body movement measures

>“The raw body movements are processed to extract features in various domains, specifically the time, frequency, and time-frequency domains. In the time domain, features such as velocity, acceleration, trajectory, and angle of joints [4], [5] are generally computed. Features computed in the frequency domain are particularly useful in detecting abrupt or fast movements (e.g., associated with emotions like anger or surprise), which might not be evident in the time domain. Examples of such features are the amplitude and phase of the Discrete Fourier Transform (DFT)” (Mousavi et al., p. 4)

>“While body movements are relatively easy to capture, it is challenging to disambiguate emotions based solely on body movements. Hence, this modality is often used in combination with other signals (e.g., vocal cues) or used to tackle a more limited task, such as the identification of the polarity of the emotion (negative vs positive)” (Mousavi et al., p. 4)
## Audio measures

>“Speech, as an important modality to convey emotions, contains both semantic information and paralinguistic cues. The latter includes features such as intonation, timing, volume, and pitch and, unlike the former, can be transferred through speech only” (Mousavi et al., p. 4)

>“The Extended Geneva Minimalistic Acoustic Parameter Set (eGeMAPS) [10] is a low-level descriptor often used for ER based on speech. This descriptor extracts 88 features related to acoustic information. However, in eGeMAPS, semantic information is lost” (Mousavi et al., p. 4)

>“Another commonly used features are Mel-frequency Cepstral Coefficients (MFCCs). MFCCs have been widely, and successfully, used for automatic speech recognition” (Mousavi et al., p. 4)

>“MFCCs contain both acoustic and semantic information about the speech. However, MFCCs are less robust to noise and ignore the spectrum phase [11], which includes temporal characteristics of phonetic transitions” (Mousavi et al., p. 4)

>“Pre-trained wav2vec2.0 models have already shown better performance compared to eGeMAPS and MFCCs in the task of speech ER [14, 15] but come with a higher computational cost” (Mousavi et al., p. 4)

>“Compared to other modalities, such as facial expressions, speech is easy to acquire in a VR context where the headset may introduce visual occlusions [16]. However, not all VR scenarios require a user to speak, which makes it a limitation of this modality.” (Mousavi et al., p. 4)

## Facial expression measures

>““Facial expressions are highly correlated with a person’s emotional state. Facial expressions can be captured using various instruments, such as cameras, depth sensors, and wearable devices.” (Mousavi et al., p. 5)

## Eye gaze measures

>“high pupil dilation is a sign of emotional arousal” (Mousavi et al., p. 5)

>“features related to gaze (e.g., fixation) provide useful information about emotional states, but are generally used as a complementary modality” (Mousavi et al., p. 5)

>“The analysis of pupil dilation is highly effective in ER, especially to tackle the task of arousal estimation” (Mousavi et al., p. 5)

## The emotions

>“seven classes of emotions (namely joy, fear, disgust, surprise, sadness, anger, and neutral expressions)” (Mousavi et al., p. 6)

>“each person may react differently to the same emotional stimulus” (Mousavi et al., p. 8)

## Openings

>“A second approach is self-annotated datasets. This approach consists in asking users to express their own emotions. However, users may lack awareness of their emotions or provide incorrect labels, leading to biased datasets” (Mousavi et al., p. 8)

>“Given that the theory of flow establishes a connection between task difficulty, individual skills, and emotional response, we argue that it is particularly well-suited for eliciting emotions in an adaptive VR setting” (Mousavi et al., p. 13)****

>“leveraging the interactive nature of VR, users can provide instant emotional feedback through virtual panels or other means.” (Mousavi et al., p. 13)

# Synthesis

This paper lists evry way of emotion Recognition :
- Face tracking (few info)
- Body tracking : velocity, acceleration, trajectory, and angle of joints (better used with audio as well)
- Audio (paralinguitic & semantic) : intonation, timing, volume, and pitch
- Physiological measurements 
	- [[Electrodermal activity (EDA)]]
	- [[Electro-cardiogram (ECG)]]
	- [[Blood Volume Pressure (BVP)]]
	- [[Skin Temperature (SKT)]]
- Eye gaze : Pupils are dilated with arousal and fixation can be used to measure interest/adversion

Also, it states that participants can self-report emotion state but it could not be reliable if timing is unprecise and it could break [[Immersion]]