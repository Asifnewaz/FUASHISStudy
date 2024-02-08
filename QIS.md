
# QIS: Quantum Information Scienc

Winter-Semester 2023/2024, Prof. Dr.-Ing. Peter Thoma

**Objectives:**
- Fundamental concepts
- Hardware implementations
- Building blocks of a quantum computer
- Algorithms 
- Implement

## PDF 1

**Why Quantum ?**
> Speed

**Quantum Supremacy ?**
> When classical computer cannot keep up/ uable to compute the complexity.

**Today’s hardware:**
- IBM: 127 qubits (Eagle processor)
- Google: 53 qubits (Sycamore processor)
- Intel: 49 qubits (Tangle lake processor)
- Honeywell: 10 qubits (large quantum volume = low error rate)
- D-Wave: 5760 qubits (adiabatic, optimization problems only)

**Applications of quantum mechanics:**
- Semiconductors (diodes, transistors, microprocessors), all modern electronics
- Medical diagnostics (X-ray, MRI)
- Laser
- Electron microscope
- Nuclear energy (civil and military)
- Atomic clock
- Quantum computers


**1. Max Planck studied the “black-body radiation problem”. Please describe the phenomenon which could not be described with the classical physics back then. What did Max Planck postulate and what does this mean?**

A black body absorbs all light falling on it and therefore appears to be perfectly black. An approximation for such a body is a cavity with a small hole. Light falling through the hole will be reflected in the cavity multiple times while it gets absorbed. Therefore, almost no light falling into the hole gets reflected through the hole. The hole thus appears to be a black body.
When the cavity is heated, the hole starts glowing. The variation of the spectrum (energy density of the black body radiation as a function of frequency) as a function of the temperature could not be explained by using classical physics.
Max Planck postulated that the light energy which is emitted from the black body cannot take any arbitrary value, but only integer multiples of a small quantity E = h f where h = 6.626 10^34 m^2 kg/s is the Planck constant and f is the light frequency.

**2. What is the “photoelectric effect” and how did Albert Einstein describe this effect?**

The photoelectric effect describes the emission of electrons from metal surfaces as a result to incident light. According to classical physics (Maxwell’s theory), the energy of the emitted electrons should increase with the intensity of the incident light.
In fact, it was discovered by experiments that the energy of the electrons is independent of the incident light intensity.

Einstein described the effect by postulating that the light consists of photons which interact with the electrons in the metal surface like particles. Each photon carries a certain energy E = h f, such that each electron interacting with a single photon will carry this amount of energy afterward. A higher light intensity would result in more photons and therefore more electrons being emitted. However, the individual energy of each electron remains the same.
  
Increasing the light frequency results in a higher energy of each electron interacting with the corresponding photon.

**3. Describe the evolution of the model of the atom.**
Briefly explain Rutherford’s model of the atom.
The ancient Greek Demokrit (400 b.c.) already proposed that all matter consists of small particles - called atoms - which cannot be subdivided further.
Dalton proposed 1803 that atoms are solid particles which behave electrically neutral. A particular type of matter consists of the same type of identical atoms. Atoms of different matter have different shape and weight.
Thomson proposed in 1903 a refined model where the atom is a uniform sphere of positively charged matter with electrons embedded (like raisins in a plum pudding).
Rutherford refined the model in 1911 by proposing that the atom has a small charged core (the nucleus) where almost all mass is concentrated. Light weight electrons are circulating around the nucleus at some distance like planets revolving around the sun.
Bohr proposed his model of the atom in 1915. The main difference to Rutherford’s model is that the electrons revolve around the nucleus in fixed orbits. The energy of an orbit is related to its size. Radiation is emitted or absorbed when an electron switches from one orbit to another.
The most commonly used model today is the Electron Cloud model proposed by Schrödinger. The model is based on a probability distribution of the electron positions in a cloud around the nucleus.

**4. Describe the problem with Rutherford’s model of the atom and how this could be resolved by Niels Bohr’s model of the atom.**

Since the electrons carry a negative electric charge whereas the nucleus carries a positive charge, there is an electrostatic force between these charges. The electron is therefore attracted by the nucleus. Rutherford’s model could not explain why the electrons do not collapse into the nucleus.
Bohr proposes stable orbits where a change of the orbit requires a certain amount of energy. Continuous small radiation due to the movement of the electrons on a circular path would not be enough for an electron to change its orbit. As a result, the electrons revolve on stable orbits around the nucleus.

**5. What does Erwin Schrödinger’s equation describe?**

Schrödinger’s equation is a partial differential wave equation describing the behavior of atomic particles. The solution of this equation is called the “wave function” of the quantum system. The wave function is a probability distribution of finding a particle (e.g. an electron) at a certain position.

**6. What can you tell about the state of a quantum system? What happens when you measure its state?**

The state of a quantum system is internal to the system. We can not tell anything about the state of such a system at a point in time. From a probability point of view, we can assume that the system is in a superposition of all possible states.
We can only determine the state of a quantum system by performing a measurement. The measurement causes the superposition to collapse and we will observer one of the possible states of the system.

**7. Why did Schrödinger propose the “Schrödinger’s cat” experiment? What was Niels Bohr’s position on this experiment? What is the “many worlds” approach?**

Schrödinger proposed his cat thought experiment in order to show how ridiculous the view of quantum mechanics actually is.
Nils Bohr considered quantum mechanics as a mathematical theory to explain the quantum effects. It can also be stated that the measurement of the particle by the Geiger counter already leads to a collapse of the superposition.
The many worlds approach proposes that many worlds exist in parallel. When the box is opened, the observer splits into two independent worlds. In one world the cat is alive and in the other world it is dead. There is no communication or interaction between these worlds possible.

**8. Briefly describe the thought experiment behind the “Einstein-Rosen-Paradoxon”. Can quantum entanglement be used to transport information at speeds larger than the speed of light?**

The thought experiment assumes that two electrons are being created where one has the opposite spin of the other. Afterward these two particles are moved far apart. According to quantum mechanics, both electrons are in a superposition state and only when then spin of one of the electrons is measured, it is actual spin (up/down) is decided. At exactly this point in time, the state of the other electron is also determined since it needs to be opposite.
There seems to be interaction at no time delay (= faster than at the speed of light) between the two particles over a potentially large distance.

Schrödinger explained that these two electrons belong to the same quantum system and are therefore “entangled” regardless of their distance.
It can be shown that no information can be obtained locally by this entanglement. Therefore, information can still not travel faster than at the speed of light.

**9. Please explain briefly the “hidden-variable theory”.**

The hidden variable theory assumes that the description given by the quantum mechanics is incomplete and does not give a complete description of the system. A complete theory would give a description for all quantum phenomena avoiding non- determinism (everything described by probabilities only, no deterministic description possible). As an example, the behavior of a compass needle could not be explained without knowing about the magnetic field (which could have been a hidden variable).

**10. What does John Bell’s inequality relation describe?**
What is the current state of experimental confirmation of Bell’s inequality?
Bell’s theorem states that if quantum mechanics is correct, non-locality exists (interaction of particles over large distances at no time delay). If Bell’s inequality relation holds, all interactions are local in nature.
Several experiments have shown that Bell’s inequality relation is violated and therefore that non-local interaction of particles exists. However, many experiments contain some “loopholes” where one could argue that the experiments are incorrect and deliver misleading results. New experiments are conducted closing the loopholes of previous ones. While it is very likely that non-locality actually exists, it has not yet been experimentally undoubtedly proved.
