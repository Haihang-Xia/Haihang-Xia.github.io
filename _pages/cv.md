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
* Ph.D in Hardware implementation of Spiking Neural Network, University of Sheffield, 2027 (expected)
* M.S. in Electronics & Electrical Engineering, University of Glasgow, 2023
* B.S. in Integrated circuit design and integrated system, Hefei University of Technology, 2022

Work experience
======
* Spring 2021: Research Intern
  * Wenzhou Branch of China Telecom Co.Ltd.
  * Duties includes:
    * Theoretical study and practice of proprietary cloud operation and maintenance;
    * Learning and practice of SQL injection;
    *  Learning and practice of network password security and analysis;
    * Vulnerability scanning and testing for telecommunication-related networks;
    * Participated in a series of conferences and seminars to study network security. 

* Summer 2020: Hardware Design Intern
  * Rosenberger Asia Pacific Electronic Co., Ltd.
  * Duties included:
    * Participated in the hardware design of 5G vehicle wireless terminal products, completed multiple chip peripheral circuit device selection and calculation;
    * Selected the circuit devices essential for products, calculated the power consumption, current, voltage and other data of the circuit required by the chip periphery, and calculated the devices’ resistance and inductance and other parameters for device selection.
  
Skills
======
* ASIC/FPGA Design & Implementation
* SoC architecture and AI accelerator design
* AI model development and application
* Coding
  * Verilog
  * Python
  * Matlab
  * C & C++

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Conferences
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
