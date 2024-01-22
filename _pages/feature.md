---
title: "Featured project"
layout: splash
permalink: /feature/
hidden: true
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/header-images/header-gds-mod.jpg
  teaser: /assets/images/header-images/header-gds-mod.jpg
  overlay_filter: 0.5 # same as adding an opacity of 0.5 to a black background
excerpt: >

gallery_feature:
  - url: /assets/images/landing-images/featured/oedometer_cylinder4.jpg
    image_path: /assets/images/landing-images/featured/oedometer_cylinder4.jpg
    alt: "placeholder image 1"
  - url: /assets/images/landing-images/featured/oedometer_cylinder2.jpg
    image_path: /assets/images/landing-images/featured/oedometer_cylinder2.jpg
    alt: "placeholder image 2"
  - url: /assets/images/landing-images/featured/oedometer_cylinder3.jpg
    image_path: /assets/images/landing-images/featured/oedometer_cylinder3.jpg
    alt: "placeholder image 3"
  - url: /assets/images/landing-images/featured/oedometer_cylinder4.jpg
    image_path: /assets/images/landing-images/featured/oedometer_cylinder4.jpg
    alt: "placeholder image 4"
  - url: /assets/images/landing-images/featured/DAQ1.jpg
    image_path: /assets/images/landing-images/featured/DAQ1.jpg
    alt: "placeholder image 5"
  - url: /assets/images/landing-images/featured/DAQ2.jpg
    image_path: /assets/images/landing-images/featured/DAQ2.jpg
    alt: "placeholder image 6"
---

# Cambridge's Frost Heave Research with MSMT's Instrumentation Support

Frost heave presents a significant challenge to infrastructure built in cold regions, creating suction or negative pore water pressure during the freezing process. The University of Cambridge initiated a research project to understand the relationships involved in suction development and ice lens formation. 

MSMT Solutions was approached by the university to design a novel oedometer cell wall compatible with their pre-existing bespoke oedometer apparatus. The university's frost heave project necessitated 10 distinct temperature and pressure probes, spaced along the soil sample column. Additionally, they needed a uniquely tailored micro-controller capable of recording pressure and temperature data simultaneously, transmitting it via Bluetooth to their DAQ system (UniLab).

MSMT accepted the challenge to acquire these complex measurements. The project began with an extensive market survey for the perfect sensor,  capable of measuring extreme low temperatures as well as high negative pore pressures. Initial tests of a selection of sensors were carried out to understand the performance of the individual sensors and the cavitation limit defined by the properties of the porous ceramic filter.

The design of the cell wall and sensor housing was subsequently undertaken to accommodate the selected sensors. Given the high pressures applied to the soil samples, it was essential for MSMT to assess the structural stability of the cell. A Finite Element Analysis was conducted, aiding in the determination of the optimal layout within the oedometer cell wall. This ensured an adequate safety factor was maintained even under peak load conditions. 
Following this, MSMT designed a custom-made DAQ board based on the Raspberry Pi Pico W. The design parameters were strictly influenced by the constricted space within the oedometer apparatus. The final PCB has the capacity to read from 16 channels and is adaptable to external power sources ranging from 5-12V. A functional C++ software was developed to read the sensor data, which serves as a model for the University of Cambridge to incorporate into their existing DAQ system. The research is still underway, with results and accompanying publications expected in the near future.

{% include gallery id="gallery_feature" caption="" %}

