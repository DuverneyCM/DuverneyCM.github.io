---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.Eng. in Electronics, Universidad del Valle, CO, 2019
* Ing. in Electronics, Universidad del Valle, CO, 2015

Work experience
======
* Summer 2019: Research Assistant
  * University Of Delaware
  * Duties included: Bash and makefile scripting to automate CETUS's testbench 
  * Supervisor: Rudolf Eigenmann

* Fall 2015: Research Assistant
  * Universidad del Valle
  * Duties included: Develop a multi-photon coincidence counter (OMPCC), a python software (Spectra3D) to synchronize the measurements of a spectrometer located on a 3D electromechanical platform.
  * Supervisor: John H. Reina
  
Skills
======
* Embedded Systems (SoC-FPGA, microcontrollers, RS-232, RS-485, I2C, SPI, Xbee, Bluetooth, WiFi)
* BackEnd (SQL, NoSQL, CGI, C, C++, Python, Java, JS) 
* FrontEnd (ReactJS, HTML, CSS)
* Cloud (AWS)
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
