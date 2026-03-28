---
author: " Pedro Henrique Barcha Correia"
year: 2024
keyword1: "[[Adaptative Virtual Reality (AVR)]]"
doi: 10.1145/3691573.3691574
---
[[Virtual Reality]]
## Introduction

>“AVR systems are capable of intelligently responding to users’ needs and preferences, enhancing efficacy, satisfaction, and engagement.” (Correia, 2024, p. 1)

>“for a VR system to be considered adaptive, it must incorporate three fundamental elements: (1) user’s performance measurements, obtained during the VR experience, such as accuracy, task completion time, gestures, and physiological data (e.g., heart rate, blink rate). Optionally, profile information such as age and experience with VR can also be used; (2) adaptive variables, which represent adjustable features that dynamically change based on user performance, including simulation difficulty and feedback; and (3) adaptive logic, the underlying mechanism that governs the behavior of adaptive training systems, ensuring automatic adjustment of the adaptive variables based on user performance. This logic may be implemented using several approaches, such as simple Finite State Machines, Fuzzy Inference Systems, and Machine Learning-based classification models.” (Correia, 2024, p. 1)

## Related Works

> Zahabi et al. ... “The 2019 study reveals that most of the analyzed works use non-immersive technology, utilize adaptation to adjust the difficulty of the experience, and are meant for rehabilitation.” (Correia, 2024, p. 2)

>Wood et al ... “According to the authors, skin responses, gaze, heart rate, and brain activity, for instance, offer reliable insights into the user’s response to VR environments. These data can then be used to assess the user experience and improve it in personalized ways.” (Correia, 2024, p. 2)

## Solutions

>“social interaction platforms for children with autism, and neurorehabilitation applications. As illustrated in Table 3, adaptive approaches to these solutions typically focus on identifying the user’s limitations and maintaining a balanced difficulty level” (Correia, 2024, p. 5)

>“the time taken for users to carry out tasks and their reliance on the shopping list are used to adjust the tasks’ difficulty.” (Correia, 2024, p. 5)

>“Predefined combinations of affect, engagement levels, and in-game performance metrics dictate specific changes in the required tasks.” (Correia, 2024, p. 6)

>“emotion-inducing solutions should be applied with caution, considering the possibility of unintended adaptation outcomes, due to biases in the Machine Learning model, for example. Moreover, it is advisable to notify users that such algorithms are in use and that they may exhibit unexpected behavior.” (Correia, 2024, p. 6)

>“the assessment relied on questionnaires, which may offer less reliable information.” (Correia, 2024, p. 6)

## Discussion

>“performance measures may vary, such as task completion time, cognitive workloads, stress level, emotional state, engagement, gestures, and cybersickness” (Correia, 2024, p. 7)

>“the adaptive variables may relate to feedback, cybersickness, emotions, and learning preferences. In particular, 50% of the reviewed works are interested in adapting their difficulty level to match the users’ necessities, as seen in Figure 2” (Correia, 2024, p. 8)

>“46.67% of the studies compare AVR and non-AVR implementations of their systems. This is an important step towards not only assessing the benefits of the proposed AVR applications, but also evaluating potential advantages of leveraging adaptative mechanisms.” (Correia, 2024, p. 8)

>“physiological sensors are still not typically included in standard user setups. Thus, using the latter to gather performance measures is discouraged when the solution is meant for more casual scenarios” (Correia, 2024, p. 8)

>“However, it’s important to note that biometrics do not necessarily replace usability self-report measures, such as the System Usability Scale (SUS)” (Correia, 2024, p. 8)

>“Other general guidelines for testing and evaluating VR applications [29] are: a) blinding: do not reveal the research questions (e.g., how does the VR solution compare to the AVR one?)” (Correia, 2024, p. 8)

>“Although there is a certain level of consistency in the expression of emotions among individuals, each person has a unique way of conveying them” (Correia, 2024, p. 8)

>“This individuality poses a challenge in developing a universal system capable of effectively recognizing or inducing emotions” (Correia, 2024, p. 8)

>“While “Adaptive Virtual Reality” is commonly used, other studies employ terms like “Intelligent Virtual Reality” [15, 48] and “Adaptive Virtual Environments”” (Correia, 2024, p. 8)

## Conclusion

>“Roughly half of the analyzed works compare adaptive and non-adaptive versions of their solutions, usually suggesting that the adaptive form is preferable, automatically adjusting itself to suit the user’s preferences and needs.” (Correia, 2024, p. 9)

# Synthesis

[[Adaptative Virtual Reality (AVR)]] is presented. Authors think that AVR systems are capable of intelligently responding to users’ needs and preferences, enhancing efficacy, satisfaction, and engagement.
For a [[Virtual Reality]] system to be considered adaptive, it must have :
- user’s performance measurements (accuracy, task completion time, gestures, age, experience and physiological data (e.g., heart rate, blink rate))
- adaptive variables : adjustable features that dynamically change based on user performance
- adaptive logic, the underlying mechanism ensuring automatic adjustment of the adaptive variables (Finite State Machines, [[Fuzzy Inference Systems]], or Machine Learning)
For 50% of the papers reviewed, AVR is used to balance difficulty. Also less than 50% of the studies had a control condition.
Physiological measures are encouraged, but gathering them often leads not non-casual scenarios, so performance measures are preferred.