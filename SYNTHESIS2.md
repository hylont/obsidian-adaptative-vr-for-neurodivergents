
Conception and validation of a multisensorial adaptative VR immersive framework for neurodivergents : olfactive and auditive approaches

# 1	Objectives 

(Neurodiverse population)
- What sensorials issues occur with audio stimuli ? How to avoid them ?
- Do olfactive stimuli issues occur in the same way ? How to design and balance them ?
- Do a sensorial profile categorization exist ? If yes can we use it for stimuli balancing/disabling ?
- With a sensorial preference (or profile) record created, how should an XR dev use it to create experiences for all populations ?

# 2	Neurodivergence and sensorial issues

## 2.1	Definitions

### 2.1.1	Neurodivergence
- Neurodiversity : “natural variations in brain function that exist across the entire population, encompassing both neurotypical and neurodivergent individuals.” [6]
- Neurodivergent : “individuals whose neurological characteristics differ significantly from what is considered the predominant or typical cognitive pattern within a given society or context” [6]
### 2.1.2	Types of sensitivity disorders
- Hyper-sensitivity : Significantly to extremely increased response to one or more sense's stimuli
- Hypo-sensitivity : Significantly lowered to absent response to stimuli
(better terms needed : conflict with medical definitions)
## 2.2	Neurodiverse populations with recorded sensorial issues
- [[ASD]]
	- “Hyper- or hyporeactivity to sensory input or unusual interest in sensory aspects of the environment” ([1], p. 88)
	- “adverse response to specific sounds or textures, excessive smelling or touching of objects, visual fascination with lights or movement” ([1], p. 88)
- [[Sensory processing Disorder (SPD)]]
	- "Sensory processing disorders (SPD) (aka sensory integration dysfunction) refer to conditions that are generated when a person’s brain is not able to integrate or organize (part of) the flow of sensory impulses so as to provide the individual with good, accurate information about herself/himself or the world around her/him [2], and can affect one or more senses at the same time"
- [[Atypical Auditory Functioning (AAF)]] [5]
	- [[Hyperacusis]]
		- "an over-sensivitity to physical sounds parameters (i.e., sound intensity)" [5]
	- [[Phonophobia]]
		- "consists in a fear of sounds (e.g., dogs barking)" [5]
	- [[Misophonia]]
		- "characterises strong emotional reaction to sounds in specific contexts and/or with a specific meaning to the individual (e.g., chewing)" [5]
	- [[Enhanced perceptual functioning (EPF)]]  [4] (unsure)

## 2.3	Measure neurodivergence

### Autism
- [[Autism Diagnosis Observation Schedule (ADOS)]]
- [[ADIR]]
- [[ICD]]
- [[DSM-5]]
### Sensory perception abnormalities
- 4 steps in sensory integration
	-  registration (the brain receives sensory information from sense organs)
	- modulation (allows the regulation of stimulus intensity)
	- discrimination (the stimulus is organized and interpreted to distinguish its relevance, characteristics and specific qualities)
	- response (the brain integrates all the processed stimuli to generate an appropriate response that will lead to a particular behavior and movements)
- [[Sensory subtypes (or phenotypes)]] [9]
	- [[Sensory adaptative (SA)]]
	- [[Taste and Smell Sensitivity (TSS)]]
	- [[Under-Responsive and Sensory Seeking (URSS)]]
	- [[Movement and Low Energy-Weakness (M-LEW)]]
	- [[Generalized Sensory Differences (GSD)]]
- [[Sensory processing pattern]]
	- [[Avoidance]]
	- [[Registration]]
	- [[Sensitivity (sensory pattern)]]
	- [[Seeking]]
	- ![[DunnSensoryProcessingPatterns.png]]
Little et al came to the conclusion that sensory phenotypes are applicable to all the population. [8]
# 3	Olfactive issues overview

## 3.1	Measurements

- ASD children do not "adjust their sniff in accordance with odorant properties" [10] => Sniff volume & rate
- "76%, in this area, find that the sense of smell affects the sense of [[Presence]] in VR, about 24% found no differences" [11] => Presence ?
- "When exposed to pleasant smells (like orange; Hrdlicka et al., 2011), people with [[ASD]]s seem to better perform at sorting tasks (Wilder et al., 2008)" [12] => Task efficiency ?
- "people with [[ASD]]s were found to be more physiologically sensory reactive in terms of heart rate (HR) compared to neurotypicals across all sensitivity stimuli" => Heart rate ?
- "Olfactory detection is usually measured by the odor threshold test, which evaluates the lowest concentration of a stimulus (normally n-butanol, having a greater trigeminal component, or phenyl-ethyl-alcohol, with higher prevalence of pure olfactory components) that can be discerned" [12] => Base odor threshold ?
- "At the end of the first experiments, users' verbatims, facial expressions and gestures revealed sensations of pleasure when scent was diffused" [14] => Face tracking & emotion recognition 
## 3.2	Challenges

- "there is no general theory on how smell can be similarly sampled and encoded in binary format, as there is no simple analogy to the waveforms that characterize the other senses." [11]
- Constant exposure to a particular odor can cause a perceived loss in intensity, => odor adaptation. Recovery from this is known to be highly variable in studies and depends on the strength of the odorant used [11]
- "mint and chlorine have been reported to be differently perceived in children with [[ASD]] compared to typically developing children" [12]
- participants with [[ASD]] had lower suprathreshold detection scores and used a more liberal decision criterion than the control participants; [13]
- participants with [[ASD]] judged odors to be more intense and perceived unpleasant odors to be less unpleasant than the control participants; [13]
- [[ASD]] participants had difficulty discriminating between the presence and absence of an odor. When uncertain, the participants with [[ASD]] responded yes more often than no when no odor was present. [13]
## 3.3	Parameters

- Scent notes are the individual components that constitute the overall composition of a fragrance. The top notes are the first impressions of a scent that are detected immediately, followed by the middle notes that are lighter and last longer, and finally, the base notes that are the heaviest and take the longest time to detect [11]
- Intensity doesn't seem appear to be easily measured, thus is subjective
## 3.4	Notes for protocols

- "gender can also affect sensitivity, as can age [11, 12]. Even culture can play a role as some cultures may be more receptive to certain smells than others" [11]
- music can contribute to the perception of smell [11]
- Studies on olfactory testing in [[ASD]]s have generally demonstrated a decrease in the ability to identify odors in people with [[ASD]] [12]
- odor identification performances have been correlated with self-ratings of [[empathy]], one of the most clearly impaired cognitive functions in individuals with [[ASD]] [13]
- three types of [[Olfactory]] display approaches that could be used in VR therapy treatments: [11]
	- ubiquitous-type displays in which the [[Olfactory]] display is situated in the environment
	- wearable-type displays, which the user wears
	- Handled : embed OVR displays into various objects that can be used in VR systems, such as controllers that deliver the [[Scent]]


# 4	Auditive issues overview

## 4.1	Measurements

### 4.1.1	Visible

- Putting hands on ears [5]
- Overarousal => reduced attention [15]

### 4.1.2	Physiological

- Heart rate (can also be caused by anticipation) [15]
- Skin reactions

### 4.1.3	Others [5]
- Drawings
- Echolalias 
- Qualitative data
- Practitioner 
## 4.2	Types of audio stimuli [5]

### 4.2.1	    Positive

- Nature 
- Home
- Music (predictible & low-pitch are more pleasant)
### 4.2.2	Negative

- Cries
- Crowded place
- School
- City
## 4.3	Parameters [5]

![[Pasted image 20260107230622.png]]
## 4.4	Recommendations for protocols [5]

- " shortened to ten, five, and one second files based on their original duration. Short and similar durations were chosen to facilitate future comparisons during auditory assessments. Second, background noise was partially removed from the audio files so that they can then be used in actual audio assessments with autistic individuals. Third, all files were normalized to -20dBFS.”
- “to avoid generating over-arousal, an enjoyable sound is heard between every three disliked sounds”
- "assess a comfortable sound level for the child. To that end, he will display a neutral sound for them (chosen with them beforehand) at a very low intensity and gradually increase its level by 5dB steps until the child indicates that a comfortable level has been reached (the level is expected to be between 50dB and 60dB, and will not exceed 65dB). If no sign is given, the level of 55dB will be used"
- “filtering could consist in filtering sounds by blurring them, e.g., adjusting their pitch or frequency range.”

# 5 Debates about the thesis

- Olfactive issues with neurodivergents : few literature exist (but very limited in VR), but it represents very few individuals and seems not really problematic => replace with visual ?
- Do we promote accessibility, or neurodiversity ?

# 6 Hypotheses (Not supported by references)

- As Bauer found, it's possible to create a taxonomy of smells (eg classify negative and positive smells + classify them in contexts) for neurodivergents, that can fit the vast majority of neurotypical preferences.
- 
- There is a pleasantness correlation between smells contexts and sounds contexts

# 7 Protocols

## 7.1 Discomfort scenarios adaptator
# 8 Sources

[1] : Diagnostic and statistical manual of mental disorders: DSM-5, 2013
[2] : A. J. Ayres and J. Robbins, Sensory integration and the child: Understanding hidden sensory challenges. Western Psychological Services, 2005
[3] : [[Imaginator - A Virtual Reality Based Game for the Treatment of Sensory Processing Disorders]]
[4] : Laurent Mottron et Al, Enhanced Perceptual Functioning in Autism: An Update, and Eight Principles of Autistic Perception, 2006
[5] : [[Exploring Multisensory Extended Reality Approaches for Autistic Children - Improve Well-Being and Assess Auditory Perception]]
[6] :  Vargas-Salas et Al : Neurodivergence and the Workplace: A Systematic Review of the Literature, 2025
[7] : Adrian Galiana-Simal et al : Sensory processing disorder: Key points of a frequent alteration in neurodevelopmental disorders, 2018
[8] : [[Classifying sensory profiles of children in the general population]]
[9] : [[Exploring sensory phenotypes in autism spectrum disorder]]
[10] : [[A Mechanistic Link between Olfaction and Autism Spectrum Disorder]]
[11] : [[A Review of Olfactory Display Designs for Virtual Reality Environments]]
[12] : [[Olfaction in autism spectrum disorders A systematic review]]
[13] : [[Olfactory processing in adults with autism spectrum disorders]]
[14] : [[Virtual Reality and Autism Spectrum Disorder - Emergence of Sensory-Motor and Olfactory Potentialities in an Anthropocentric Epistemological Approach]]
[15] : [[Application of Supervised Machine Learning for Behavioral Biomarkers of Autism Spectrum Disorder Based on Electrodermal Activity and Virtual Reality]]
