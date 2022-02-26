# SDML - Structural Design supported by Machine Learning

This project introduces a computer-aided design framework for the generation of non-standard structural forms in static equilibrium that takes advantage of the interaction between human and machine intelligence. The design framework relies on the implementation of a series of operations (generation, clustering, evaluation, selection) that allow to create multiple design options and to navigate in the design space according to objective and subjective criteria defined by the human designer. 
<br>
<br>
Within the proposed framework, two main algorithms are used: 
- Combinatorial Equilibrium Modeling (https://github.com/OleOhlbrock/CEM) for generating structural forms in static equilibrium as design options;
- Self-Organizing Map (https://github.com/sevamoo/SOMPY) for clustering the design options.
<br>
These algorithms are combined with the ability of human designers to evaluate non-quantifiable aspects of the design. The work presented here is a further development of a research project started in 2018 as a collaboration between the Chair of Digital Architectonics (Karla Saldana Ochoa, Vahid Moosavi) and the Chair of Structural Design (Pierluigi D'Acunto, Patrick Ole Ohlbrock) at ETH Zurich (https://github.com/sakarla/Beyond-typologies-beyond-optimization). The scripts and tools included in this repository were developed for the workshop "Structural Form-Finding with Machine Learning" at the Advances in Architectural Geometry (AAG) 2020 (https://www.aag2020.com/form-finding-machine-learning). 
<br>
<br>

SDML is developed by:
- __Pierluigi D'Acunto__ [Technical University of Munich, Professorship of Structural Design](https://www.arc.ed.tum.de/sd/startseite/)
- __Patrick Ole Ohlbrock__ [ETH Zurich, Chair of Structural Design](https://schwartz.arch.ethz.ch/)
- __Karla Saldana Ochoa__ [University of Florida, School of Architecture](https://www.ai-share-lab.com/)
- __Vahid Moosavi__ SwissRe, Zurich
<br>

If you use the scripts in SDML, please refer to the official GitHub repository: <br>
@Misc{sdml2021, <br>
author = {D'Acunto, Pierluigi and Ohbrock, Patrick Ole and Saldana Ochoa, Karla and Moosavi, Vahid}, <br>
title = {{SDML: Structural Design supported by Machine Learning}}, <br>
year = {2021}, <br>
url = {https://github.com/pierluigidacunto/SDML}, <br>
}
<br>
<br>

To use SDML, please make sure that the Python distribution platform [Anaconda3](https://www.anaconda.com/products/individual) is installed on your computer.
<br>
<br>

Publications related to the VGS project include:
- __Karla Saldana Ochoa, Ohlbrock,Patrick Ole Ohlbrock, Pierluigi D′Acunto, Vahid Moosavi__: Beyond typologies, beyond optimization, International Journal of Architectural Computing, 9(3), 466–490, 2021
- __Federico Bertagna, Pierluigi D'Acunto, Patrick Ole Ohlbrock, Vahid Moosavi__: Holistic Design Explorations of Build-ing Envelopes Supported by Machine Learning. Journal of Facade Design and Engineering, 9(1), 31-46, 2021
- __Patrick Ole Ohlbrock, Pierluigi D′Acunto__: A Computer-aided Approach to Equilibrium Design based on Graphic Statics and Combinatorial Variations, Computer-Aided Design, Volume 121, 102802, 2020
- __Lukas Fuhrimann, Vahid Moosavi, Patrick Ole Ohlbrock, Pierluigi D′Acunto__: Data-Driven Design: Exploring new Structural Forms using Machine Learning and Graphic Statics, Proceedings of the IASS Symposium 2018 - Creativity in Structural Design, Boston, 2018
