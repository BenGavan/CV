# CV - Ben Gavan

This README is the GitHub version of my CV with additional links and explanations of projects & examples.

[//]: # (TODO: add links to specific projects mentioned)

## Education

| Date      | Details                                                                                                    |
|-----------|------------------------------------------------------------------------------------------------------------|
| 2018-2022 | MPhys (Hons) Physics with Theoretical Physics<br/>University of Manchester, UK                             |
| 2016-2018 | Cardinal Newman College, Preston <br/>A levels in Physics (A*), Maths (A*), and Further Maths (A*)         |
| 2011-2016 | St Cecilia’s RC High School, Longridge <br/>9 GCSEs (4 A*’s, 2 A’s, 3 B’s) <br/>1 BTEC Engineering (Merit) |


## Employment
| Date       | Details                                                                                                    |
|------------|------------------------------------------------------------------------------------------------------------|
|2022-present| Research Engineer (Imetrum Ltd, Bristol, UK) <br/>Focus on developing, calibrating, and verifying non-contact measurement systems leveraging digital image correlation and computer vision techniques <br/>Main languages used: Python, C\#, and C++.|                                                 


## Skills

| Skill                   | Description                                                                                                                                                                                                                                                                                                                                                                                                                    |
|-------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Python                  | Data analysis, numerical calculations and Monte Carlo simulations.                                                                                                                                                                                                                                                                                                                                                             |
| Go                      | Server-side backend (for mobile and web) using microservice architecture (using Docker and Kubernetes hosted on AWS). Also used for Monte Carlo simulations.                                                                                                                                                                                                                                                                   |
| C++                     | Contributing to oomph-lib (an object-oriented, open-source multi-physics finite-element library). Also completed [“PHYS30762: Object-Oriented Programming in C++”](https://github.com/BenGavan/PHYS30762-Cpp).                                                                                                                                                                                                                 |
| Fortran                 | Numerical calculations - MPhys project.                                                                                                                                                                                                                                                                                                                                                                                        |
| Java                    | Android development, libGDX, and desktop applications.                                                                                                                                                                                                                                                                                                                                                                         |
| Swift                   | iOS development.                                                                                                                                                                                                                                                                                                                                                                                                               |
| Web development         | HTML, CSS, and JavaScript to build lightweight websites without depending heavily on external libraries.                                                                                                                                                                                                                                                                                                                       |
| Databases               | Using PostgreSQL and Neo4j in real-world applications.                                                                                                                                                                                                                                                                                                                                                                         |
| Quantum Computing       | [Qiskit](https://github.com/BenGavan/qiskit-exp) and my own [quantum circuit output calculator in C++]() from scratch. Also completed “COMP39112 - Quantum computing”.                                                                                                                                                                                                                                                         |
| Data Analysis           | Data Science Bootcamp (Udemy) and data analysis throughout university labs.                                                                                                                                                                                                                                                                                                                                                    |
| Finite Element Analysis | Using Oomph-lib for fluid and solid mechanics calculations.                                                                                                                                                                                                                                                                                                                                                                    |
| Algorithms              | Implemented common algorithms and data structures in a [variety of languages.](https://github.com/BenGavan/Algorithms-and-DataStructures) Also completed [6.006: Introduction to Algorithms](https://github.com/BenGavan/6.006-Intro-to-Algs) (MIT OpenCourseWare).                                                                                                                                                            |
| Mathematics             | Differential, integral, tensor and vector calculus, abstract algebra, probability theory, and complex analysis.                                                                                                                                                                                                                                                                                                                |
| Physics                 | Classical mechanics, electrodynamics, quantum mechanics, quantum field theory, gauge theories, general relativity, particle and nuclear physics, statistical physics, fluid & solid mechanics, and quantum computing. <br/> Lab work experience includes working with radiative samples, liquid nitrogen, digital and analogue electronics, oscilloscopes, data analysis using python, presenting results, and report writing. |  

## Research and Projects

#### 2021-2022:	[MPhys Project](https://github.com/BenGavan/MPhys-QPI-public)
“Modeling quasiparticle interference in two-dimensional materials”
By considering impurity-based scattering, theoretical numerical calculations, based on T-matrix formalism, were completed to successfully replicate scanning tunnelling microscopy (STM) data for NbSe2 in the charge density wave (CDW) phase.  A paper is currently being prepared based on the results and insights achieved by our novel way of probing CDWs in TMDs.  Python and Fortran were both used.

#### 2021: Third-year lab project
“ATLAS”
Using Python to interface with ROOT to analyse the 13 TeV ATLAS open data set, I reproduced the cross-sections for various processes including Z, W, and Higgs boson decays.

#### 2020: [Theory Computing Project](https://github.com/BenGavan/TheoryProject)
“Random Sampling and Monte-Carlo Simulation of Neutrons within a Nuclear Fission Reactor.”
The project involved using Monte-Carlo simulations to calculate the critical mass for nuclear fission reactions to be sustained via chain reaction for a variety of fuels, moderators, and geometries.  Python and Go were used to write the simulations from scratch.

## Additional Projects and Experience

#### Oomph-lib, Summer 2021

Over the 2021 summer break, I worked on a project using C++ and Gmsh to improve adaptive meshing within oomph-lib (an
object-oriented, open-source multi-physics finite-element library).

#### 2nd place in the UK CANSAT competition at the design stage, 2019-2020

I participated in a team of six in the UK CANSAT competition where we had to design and build a “satellite” that could
be dropped from a variety of heights, detect detachment, deploy parachutes, and perform additional tasks, all whilst
relaying data to a ground station designed and built by the team. Unfortunately, due to the COVID-19 pandemic, the
competition and any further hands-on work were cancelled in March 2020. At that time, we had placed 2nd in the UK
at the design stage. Even though we could not complete the project, I gained experience through hands-on work and
short courses in CAD, electronics, microcontrollers, embedded programming, sensing, radio communication, aerodynamics,
and how to work and manage a group project spanning a wide range of skill sets.

#### Co-ran a robotics club at my previous secondary school, 2017
My GCSE physics teacher invited me back to co-run a robotics club aimed at introducing younger pupils to STEM through on
hands experience.

#### Academic Excellence Award, 2016

Awarded for the highest GCSE grades for my year leaving school.

#### Completed an additional GCSE out of school hours, 2014-2016

Due to my interest and aptitude for geography, I completed an additional GCSE in geography. This involved
completing fieldwork analysing how river features vary along a watercourse. Overall, I received an A*.

#### BAE work experience week, 2015

After a competitive application process, I completed a work experience placement within the R&D department at BAE
Warton. I was exposed to aerodynamics research and testing, computer vision and other software development, advanced
materials research, manufacturing techniques, and CAD design.

#### Software, on-going

For some examples of projects I have worked on: [github.com/BenGavan](https://github.com/BenGavan/).

## Details of Projects & Examples 

#### [Language Overviews]()
A collection of code snippets in a few languages.

### C++
#### [Basic HTTP client](https://github.com/BenGavan/cpp-networking/tree/main/http-client)
A basic minimal HTTP client written in pure C++ (no external libraries) on top of TCP sockets.
<br/>(uses sys/socket.h, sys/types.h, and netinet/in.h)

#### [PHYS30762: Object-Oriented Programming in C++](https://github.com/BenGavan/PHYS30762-Cpp)
My collection of notes, examples, and solutions to the course "PHYS30762: Object-Oriented Programming in C++" at UoM. 
(Note: examples might not be original).

#### [Quantum Circuit Calculator](https://github.com/BenGavan/QuantumCircuitCalc)
Calculates the output state of a quantum circuit given n-qubits, m-quantum gates, and the initial state.  Written in pure C++.  

#### [Adaptive meshing using GMSH](https://github.com/BenGavan/gmsh-experimenting)
Adaptive mesh refinement interfacing with GMSH using C++.  Also includes target mesh size field estimation. 

[//]: # (Astro data querying/search)
[//]: # (png generator)
[//]: # (Plotting library)

### [Go](https://github.com/BenGavan/Go)
#### [Twitter clone/copy](https://github.com/BenGavan/TwitterClone-services)
The backend service of a simplified copy/clone of Twitter. 
<br/>Uses: Go, Docker, PostgreSQL, Neo4j.

#### [BG Physics](https://github.com/BenGavan/BG-Physics)
A dynamically generated website for presenting some of my physics and maths notes.
Uses a Golang HTTP web server as a Docker container running on AWS EC2 with routing using route 53.

#### [Personal Website](https://github.com/BenGavan/PersonalWebsite)
A static website about me.  Uses HTML, CSS, & JS for the front end, and Go & Docker for the backend hosted on AWS.

#### [Theory Computing Project](https://github.com/BenGavan/TheoryProject)
“Random Sampling and Monte-Carlo Simulation of Neutrons within a Nuclear Fission Reactor.”
This involved using Monte-Carlo simulations to calculate the critical mass for nuclear fission reactions to be sustained via chain reaction for a variety of fuels, moderators, and geometries. Python and Go were used to write the simulations from scratch.


### Python
#### [Thickness of Boron Nitrate](https://github.com/BenGavan/Thickness-of-Boron-Nitrate)
Calculates the thickness of a boron nitrate sample by using a minimising chi-squared fit of the expected transmission
coefficients for different electron energies.

#### [Qiskit Examples](https://github.com/BenGavan/qiskit-exp)
Examples using the Qiskit SDK.

### iOS
#### [Twitter Clone/copy](https://github.com/BenGavan/TwitterClone-iOS)
iOS app of a simplified copy/clone of Twitter.

#### [Collection of iOS projects using Swift](https://github.com/BenGavan/ios)
Collection of small iOS projects using Swift.  These projects originate from learning iOS development.


### Algorithms
#### [6.006 - Introduction to Algorithms (MIT)](https://github.com/BenGavan/6.006-Intro-to-Algs)
My collection of notes and solutions relating to 6.006: Introduction to Algorithms (MIT OpenCourseWare)

#### [Algorithms and Data Structures](https://github.com/BenGavan/Algorithms-and-DataStructures)
A collection of Algorithms and Data Structures implemented in several programming languages (C/C++, Python 3, Java, Fortran 90, Swift, JS).

### Databases
#### [PostgreSQL Examples](https://github.com/BenGavan/postgreSQL-examples)
Examples/snippets for interfacing a postgreSQL database in Go.

#### [Neo4j Examples](https://github.com/BenGavan/neo4j-examples)
Examples/snippets for interfacing a Neo4j database in Go.


### Quantum Computing 
#### [Qiskit Examples](https://github.com/BenGavan/qiskit-exp)
Some notes and examples using Qiskit (Quantum Information Software Kit for Quantum Computation)

#### [A basic calculator for quantum circuit output calculations in C++](https://github.com/BenGavan/QuantumCircuitCalc)
