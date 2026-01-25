---
title: "Paper Title Number 4"
collection: publications
category: conferences
permalink: /publication/2024-02-17-paper-title-number-4
date: 2024-02-17
venue: 'GitHub Journal of Bugs'
paperurl: 'https://doi.org/10.1109/SOCC66126.2025.11235406'
citation: 'H. Xia et al., “A High Accuracy and Hardware Efficient Approximate Computing based Leaky integrate-and-fire Neuron Model,” in 2025 IEEE 38th International System-on-Chip Conference (SOCC), Oct. 2025, pp. 1-6.'
---
Abstract: The adoption of Spiking Neural Networks (SNNs) has grown significantly, driven by their potential to enhance image processing, robotics, and motor control. These applications typically demand both high performance and low power consumption, especially when deployed on edge devices. Achieving high-performance and low-power SNNs in hardware remains challenging due to their computational complexity and large-scale design. Balancing accuracy and speed often increases power and resource usage, making efficient implementation essential. Optimizing a single neuron model—a fundamental unit replicated thousands of times—is key to improving overall hardware efficiency. The Leaky Integrate-and-Fire (LIF) model, widely used in SNNs, offers a more efficient alternative to other neuron models by improving computational and energy efficiency.This paper presents a LIF neuron model design based on approximate multiplication. Given the high robustness of SNNs, they are well-suited for approximate computing. The proposed design significantly reduces multiplication complexity with only 2.6099% error. The minimal error has little impact on SNN performance, as shown by similar training results between approximate and precise LIF-based SNNs across various datasets and network sizes. To further demonstrate the advantages of our AM-based LIF neuron model, we carry on a test through a Xilinx FPGA. The FPGA implementation results demonstrate that the AM-based LIF neuron achieves a 8.26% to 84.36% reduction in Look-Up Table utilization, a 17.04% to 86.49% reduction in slice register utilization, and achieving a 10.31-fold increase in energy efficiency relative to the state-of-the-art LIF neuron model.
