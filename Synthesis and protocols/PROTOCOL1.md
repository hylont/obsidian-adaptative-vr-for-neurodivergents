# Context

## Research problem
How to detect when an olfactive stimuli is unadapted to the participant ?

## Research question
Do varying scent intensities (mild, medium, strong) — selected based on individual preference — affect performance, satisfaction, and cognitive load for neurodiverse users in Virtual Reality immersive environments ?

## Hypothesis
H1 : Medium intensity olfactive stimuli show best results of user satisfaction [source needed] 
H2 : Mild olfactive stimuli show best performance and lowest cognitive load ([[Sensory overload - A concept analysis]] & [[Measuring Visual Fatigue and Cognitive Load via Eye Tracking while Learning with Virtual Reality Head-Mounted Displays - A Review]] & [other needed with neuroa])
H3 : Strong olfactive stimuli increases cognitive load while decreasing performance and satisfaction

# Pre-studies

## 1 - Pleasantness judgment

Using 10 scents that could be present in a supermarket environment and that could be represented in a hand-sized object, we ask participants to push buttons to release them, and ask them directly how pleasant they find them using a line-drawing method.
The goal is to find the scents that are the most neutral in terms of pleasantness according to answers.
## 2 - Intensity correlations

Using the 3 scents that have been identified by the previous study, we aim to find their intensity pair with butanol.

# Experience

## Measures

- [[Cognitive load]]:
	- Fixation ([[Measuring Visual Fatigue and Cognitive Load via Eye Tracking while Learning with Virtual Reality Head-Mounted Displays - A Review]])
	- [[NASA-TLX]] 
- Performance :
	- Win rate
	- Response times
	- Time spent in Market Task
- Olfactive intensity preferences :
	- Line length ([[Odor Intensity and pleasantness for a diverse set of odorants]])
- Behavior :
	- Gestures notes
	- Amount of teleportations 
- Satisfaction [[Questionnaire of User Interface Satisfaction (QUIS)]]
# Protocol creation:
- Variables :
	- Independent :
		- Order of scenari : within subject (even subjects ID try A then B, odds try B then A)
		- Scenario A :
			- Intensity (?) of stimuli
			- Order of stimuli
			- visual distractors placement
	- Dependent :
		- Adapted scents concentrations (mild, medium, strong)
		- Neurodivergence profile
- Before beginning the experience, we need to know what are mild, correct and strong scent concentrations :
	- All participants must try various concentrations of n-butanol to point out which one is the most pleasant according to their preferences. ([[Odor Intensity and pleasantness for a diverse set of odorants]])
	- For each one of the ? (at least 3, 6 would be ideal) flavors, 5 concentrations must be available (low, medium-low, medium, medium-high, high) (source ?) (pre-study needed !!!)
- Pas de feedback haptique ([[Investigation into Stress Triggers in Autistic Adults for the Development of Technological Self-Interventions]])
- Comment terminer une tâche :
	- Bouton "quitter d'urgence" ([[Investigation into Stress Triggers in Autistic Adults for the Development of Technological Self-Interventions]])
	- Fin du scénario
## Things to answer before:
- [x] Trouver plusieurs scénarios de tâches adaptées aux neuroa [[Designing virtual reality tools for students with Autism Spectrum Disorder A systematic review]]
	- Distractors [[The impact of visual and auditory distractions on the performance of neurodiverse students in virtual reality (VR) environments]] : 3 corners of the room (one for each flavor), the participant grabs an item that will diffuse a scent, then the participant has to find the distractors like in the mentioned experiment. 6 or 9 expositions (2 mild, 2 medium, 2 high at random)
	  Can't make too much expositions due to odor adaptation that will decrease odor detection and perceived intensity ([[Psychophysical and Behavioral Characteristics of Olfactory Adaptation]])
	- Supermarché [[Virtual Reality and Autism Spectrum Disorder - Emergence of Sensory-Motor and Olfactory Potentialities in an Anthropocentric Epistemological Approach]], Bozgeyikli et al. (2017)
	  In a shop, do groceries freely (more info needed)
- [ ] Trouver les différents paramètres olfactifs
	- [ ] Intensité (par rapport à du n-buthanol ?) [[Odor Intensity and pleasantness for a diverse set of odorants]]
- [ ] Si impact, trouver les questionnaires
	- [ ] Satisfaction (scenario B)
	- [ ] Performance (scénario A)
	- [ ] Cognitive / sensory load
	- [ ] Utilisabilité (scénario B)
	- [ ] Performance (scénario A) ([[Olfaction in autism spectrum disorders A systematic review]])
	- [ ] [[Presence]] ([[A Review of Olfactory Display Designs for Virtual Reality Environments]]) => secondaire selon Guillaume
## Hardware possibilities:

- https://www.eyetrackvr.dev/ & https://www.youtube.com/watch?v=PhRpa6c0FjE
- Varjo headsets (https://www.reddit.com/r/oculus/comments/1afhdyl/is_there_any_way_to_get_pupil_size_and_eye/)
- 

# In french

Première tâche : Création des préférences olfactives Les participants doivent indiquer à quel point une odeur est agréable ou désagréable (taille de la ligne désagréable OU agréable) selon son intensité (exprimée en Unité Diffuseur : UD). 5 x 8 expositions

Variables dépendantes :
- Agréable ou désagréable (ressenti)
- Taille de la ligne du ressenti 
Variables indépendantes :
- Odeur testée (5 odeurs : orange, menthe, chocolat, fleurs, butanol [justifier & risque])
- Intensité émise (5 UD, 10 UD, 20 UD, 50 UD, 100 UD, 200 UD, 500 UD, 1000 UD [source nécessaire])

Après cette tâche, le système va choisir 3 odeurs dont le pic d'agréabilité (ordonnées) selon l'intensité (abscisses) sont à la même hauteur. On les appellera odeurs choisies. On définira aussi 3 intensités par odeur choisie :
- Le seuil de perception C0
- L'intensité idéale (meilleure agréabilité) Ci
- L'intensité la plus haute à l'agréabilité nulle (égale à 0) Cmax

Tâche A : Recherche visuelle Les participants vont devoir trouver une image parmi d'autres, tout en étant exposés à une odeur. 3 x 2 x 3 expositions. 
Variables dépendantes :
- Temps pour trouver l'image
- Faux positif
- Nombre d'images regardées
- Fréquence de changement de regard des images 
Variables indépendantes :    
- Odeur émise (Parmi les odeurs choisies)
- Intensité émise (C0, Ci ou Cmax)

Tâche B : Supermarché Les participant devront trouver, en réalité virtuelle, 3 produits en lien avec leurs odeurs choisies. Une odeur sera émise quand le participant sera dans le rayon virtuel. Les autres rayons associés aux odeurs testées au début émettront aussi une odeur. L'expérience se finit lorsque les 3 produits ont été mis dans le sac et ramenés à la caisse. Une seule exposition. Variables dépendantes :

- Fréquence de téléportation
- Temps passé
- Réponse au questionnaire QUIS
- Réponse au questionnaire NASA-TLX

Variables indépendantes :

- Intensité des odeurs (C0, Ci ou Cmax), uniforme dans toute l'expérience.

S'en suivra un entretien qualitatif sur le ressenti, si le choix des odeurs était bon...etc

## Limites

- Quel est le nombre de quantités différentes qui permettrait d'obtenir une meilleure courbe de préférence sensorielle ?