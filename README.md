# Aplicación de redes neuronales convolucionales a la discriminación gamma-hadrón en chubascos atmosféricos
Tesis de Maestría en Ciencias Físicas


------------


### RESUMEN

Las observaciones de rayos gamma de alta energía provenientes del espacio exterior, se basan en experimentos en tierra que permiten detectar partículas secundarias de chubascos atmosféricos (EAS, por sus siglas en inglés) inducidos por rayos cósmicos de alta energía. Sin embargo, el obstáculo en la observación de fuentes de rayos gamma, es el gran fondo de rayos cósmicos de origen hadrónico. Es por ello la importancia de poder identificar cuáles EAS son inducidos por rayos gamma y cuáles por hadrones.
En este trabajo se propone un modelo computacional de inteligencia artificial basado en redes neuronales convolucionales (CNNs, por sus siglas en inglés) para la discriminación de EAS inducidos por rayos gamma o hadrones (partículas primarias), a partir de su huella al piso, es decir, en base a las partículas secundarias observadas en tierra. Se aborda este problema como un problema clasificación en el contexto del aprendizaje supervisado. Se proponen dos casos de estudio: la discriminación entre el tipo de partícula primaria (gamma o hadrón) y su energía a partir del EAS inducido.
Los datos de entrenamiento para el modelo de aprendizaje supervisado fueron producidos a partir de simulaciones numéricas de EAS generadas con el simulador de rayos cósmicos CORSIKA (COsmic Ray SImulations for KAscade). Se consideraron EAS verticales $((c)zenith $\theta = 0^{\circ},  ac(z)imuth  \phi  = 0^{\circ}$)$, inducidos por rayos gamma y protones (hadrones) con rangos de energía entre 0.5 y 30 TeV.
Se muestra que las RNC son un modelo con una alta eficiencia en la discriminación de EAS inducidos por rayos gamma o hadrones.

**Palabras clave:** redes neuronales convolucionales, discriminación gamma-hadrón, chubascos atmosféricos, CORSIKA, aprendizaje supervisado.


------------


### ABSTRACT

High-energy gamma-ray observations from outer space are based on ground-based experiments that detect secondary particles of extensive air showers (EAS) induced by high-energy cosmic rays. However, the obstacle in observing gamma-ray sources is the large background of cosmic rays of hadronic origin. It is therefore important to be able to identify which EAS are induced by gamma rays and which by hadrons.
This paper proposes a computational model of artificial intelligence based on convolutional neural networks (CNNs) for discrimination of EAS induced by gamma rays or hadrons (primary particles), from their footprint to the ground, that is, based on the secondary particles observed on the ground. This problem is addressed as a classification problem in the context of supervised learning. Two cases of study are proposed: the discrimination between the type of primary particle (gamma or hadron) and its energy from induced EAS.
Training data for the supervised learning model were produced from numerical simulations of EAS generated with the cosmic ray simulator CORSIKA (COsmic Ray SImulations for KAscade). Vertical EAS ($\theta = 0^{\circ}, \phi  = 0^{\circ}$), induced by gamma rays and protons (hadrons) with energy ranges between 0.5 and 30 TeV, were considered.
It is shown that CNNs is a model with a high efficiency in the discrimination of EAS induced by gamma rays or hadrons.


**Keywords:** convolutional neural networks, gamma-hadron discrimination, extensive air showers, CORSIKA, supervised learning.


------------


