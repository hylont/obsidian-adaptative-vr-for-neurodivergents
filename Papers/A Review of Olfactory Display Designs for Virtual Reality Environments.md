---
author: Jordan Tewell
year: "2024"
doi: 10.1145/3665243
keyword1: "[[VR]]"
keyword2: "[[Olfaction (or smell)]]"
keyword3: "[[Presence]]"
keyword4: "[[Immersion]]"
keyword5: "[[Multisensory]]"
keyword6: "[[Olfactive VR]]"
---
## Definitions and quotes

>the sense of [[Olfaction (or smell)]] is more challenging to deliver accurately. Whereas vision, audio, and even haptics are relatively easy to codify in digital form (e.g., based on frequency spectrums) and present to users, there are significant challenges with coding smells and delivering them via [[Olfactory]] displays, mainly due to the chemical nature of the sense.

>A visual stimulus can be characterized by its wavelength, which can be easily encoded as a combination of red, green, and blue values. An audio stimulus can be similarly described in terms of its wavelength and frequency, which can be sampled and converted to binary. A vibrotactile stimulus is similar to a sound stimulus in that its wavelength and frequency can also be sampled for binary storage. However, there is no general theory on how smell can be similarly sampled and encoded in binary format, as there is no simple analogy to the waveforms that characterize the other senses.

>The sense of smell depends on the duration of exposure [158] and its intensity, which affects how quickly humans can perceive a smell
>Moreover, gender can also affect sensitivity [97], as can age [29]. Even culture can play a role as some cultures may be more receptive to certain smells than others

>Constant exposure to a particular odor can cause a perceived loss in intensity [158], a process known as odor adaptation [52]. Recovery from this is known to be highly variable in studies and depends on the strength of the odorant used [17]. Another type of adaptation that presents itself in prior studies are cross-adaptation effects. These occur when smells are mixed together, either intentionally to create new smells or unintentionally, such as smells lingering in the environment or when the user is wearing perfume or deodorant [158]. The results of mixing smells may produce unpredictable results, depending on the type of odorant used [28]. In addition, mixture suppression [43] can result in nonaddictive behavior in that combining odors of similar intensities does not necessarily result in a new odor that is twice as strong [90]. [[Olfactory]] stimuli can also be potent and may elicit adverse reactions in some individuals, such as allergies, nausea, or headaches. Ensuring the safety and comfort of users is paramount when designing [[Olfactory]] hardware for VR

>For instance, the degree of complexity in a [[Scent]] can be influenced by the balance of [[Scent]] notes, the number of [[Scent]] notes, and the intensity of each note. When delivering [[Olfactory]] information through a technical framework, the other sensory information should also be considered to handle the sensory influences. For example, music can contribute to the perception of smell

>necessary steps must be taken to reduce delays, as non-synchronized sensory information might cause uncomfortable conditions, including nausea
[[Cybersickness]]

>One method is to use variables to control the intensity of the [[Scent]] being released, for example, based on the distance between the user and the source of the [[Scent]]. If the user is close to the source of a strong smell, then the software could instruct the OVR display to release a higher concentration of the [[Scent]]
## [[Olfactory]] devices types

>two types of [[Olfactory]] display approaches that could be used in VR therapy treatments: 
- ubiquitous-type displays in which the [[Olfactory]] display is situated in the environment
- wearable-type displays, which the user wears
- Handled : embed OVR displays into various objects that can be used in VR systems, such as controllers that deliver the [[Scent]]

>ubiquitous setups make it challenging to clean the air and change [[Scent]]s, though the use of ventilation techniques such as fans or air purifiers can help mitigate this. Without ventilation, however, different [[Scent]]s may accumulate and mix, causing unpleasant and unintentional interaction effects when detected by the user.
## [[Olfactory]] delivery methods

>combination of both works’ suggestions and suggest three categories: 
- airflow vaporization
	- natural airflow is similar to our day-to-day [[Olfactory]] experiences
	- forced airflow methods accelerate a [[Scent]]’s diffusion into the air.
	- Bubbling vaporization methods blow fresh air into an odorous liquid, which creates bubbles that lift the [[Scent]]ed air out of a container
- heat vaporization : diffuse [[Scent]]s into an environment is to vaporize them using heat, e.g., heated solid perfumes
- atomization :converting liquid odorous substances into fine, almost mist-like particles that can be easily carried and diffused into the environment
	- Spraying is a relatively straightforward liquid atomizing method and is most commonly used in everyday spray bottles
	- Venturi Effect
	- Nebulization uses airflow to diffuse oil-based [[Scent]] substances into an environment
	- ultrasonic wave atomization is another technique for generating mists
	- SAW atomization (extremely fine mist)

## Application areas

- Gaming. VR gaming is one area that holds the most profound implications of [[Olfactory]] integration.
- VR Cinema. VR cinema can benefit from OVR technology in many different areas, such as in movies, documentaries, and advertisements
- Health. Smell has been used extensively in the area of aromatherapy to treat mood disorders such as [[Anxiety]] and [[Depression]] [106], [[Sleep disorders]] [70], and nausea [103]. VR has also been applied to health-related areas, primarily mental health, as a form of virtual therapy, for instance, to mediate pain [80] and in exposure therapy ... OVR research has examined applications in rehabilitation [39], eating behaviors [108], and relaxation
- Education and training : multisensory serious games that aid in firefighter training
- V-Commerce : tourist agents can use smell and VR to help clients experience virtual destinations that are truly [[Multisensory]]al. Research with OVR tourism has shown smell can influence consumer travel recommendations [81] and increase the sensation of walking while touring a virtual destination
- Perception. OVR perception is an extensive research area that examines the efficacy of utilizing the sense of smell as an immersive technology and its effect on human behavior
- Engineering. Engineering applications investigate potential OVR mechanical and hardware designs and provide performance evaluation of those technologies

## Objectives & Experimental design

>discuss these challenges as they pertain to VR and identify academic contributions in the area of OVR research up to the present

>The main objectives of our systematic review were to survey relevant literature on OVR display research, categorize their setups according to a classification, and consolidate the main findings

>The search was based on combinations of the keywords “virtual reality” or “VR” and any of the keywords “smell,” “odor,” or “[[Scent]].” This search led to a total of 118 works, 53 of which involved a ubiquitous approach (Table 1), 57 that involved a wearable approach (Table 2), and 8 that involved either a handheld approach or a CAVE configuration
## Results

>Most configurations employed ubiquitous (45%) or wearable presentation (48%) approaches. However, very little work has been explored using a handheld approach (3%) in OVR design or a CAVE setup (4%). These results are not surprising considering the ease of deploying existing commercial [[Olfactory]] displays for ubiquitous setups and the straightforward approach of mounting an [[Olfactory]] display to an [[HMD]], as we observed in most wearable techniques.

>very few wearable OVR works utilized an [[Olfactory]] display embedded within clothing or accessories like necklaces, as most work has opted for a head-mounted method instead
>One exception to this was the work of Egan et al. [49], who used an [[Olfactory]] emitting necklace by Exhalia [54]. Another work by Amores et al. [4] used a DIY necklace called Essense [3]. Murray et al. [126] classified these types of wearable [[Olfactory]] displays as “on-body” as opposed to “headmounted” types

>Gaming was found to be a popular area explored in OVR research. Broadly speaking, we identified five categories of interest in this area: [[Immersion]], [[Presence]], performance, [[Scent]] localization, and novelty.

>congruent and pleasant smells can positively affect evaluations of a product’s shape, usability, and overall value

>for patients with autism or spinal injuries. There is also interest in using smell to improve attention for patients suffering from visuospatial defects caused by lesions in the brain

>virtual food exposure may decrease consumption of real food

>Oh and Whangbo measured EEG data and found significant differences in concentration, sense of stability, and stress when the smell was used [136]. Ranasinghe et al

>research with perception has also looked at the effect of smell on realism [14, 15, 41], the sense of reality [15, 16], the sense of existence [135], the sense of involvement [65], emotion [41, 59, 150, 194], [[Immersion]] ,  [41, 49, 67, 182], memory [44, 150], engagement and [[Flow]] [41], [[Anxiety]] [142], and enjoyment and [[Discomfort]] [49]
## Conclusion

>While the majority of work, approximately 76%, in this area, find that the sense of smell affects the sense of [[Presence]] in VR, about 24% found no differences

>However, the sense of smell is not mandatory for the sense of [[Presence]]; instead, smell sensations help to enhance it.
>...
>it is not an essential component for creating a sense of [[Presence]] in VR, as [[Presence]] can also be achieved through other modalities such as visual and auditory cues, haptic feedback, and body tracking

>Our systematic review revealed that most work in OVR has been in the last decade, with a focus on ubiquitous and wearable presentations concentrated on studying perceptual, engineering, and mental health challenges

## Images

![[TewellOVRClassification.png]]
![[TewellOVRBreakdown.png]]
![[TewellPublications.png]]