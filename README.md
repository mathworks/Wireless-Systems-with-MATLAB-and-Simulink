# Wireless Systems with MATLAB&reg; and Simulink&reg; Resources

Collection of useful resources on Wireless Systems for researchers, educators, and students using MATLAB and Simulink.

## Summary

- [General Resources on Wireless Systems](#general-resources)
  - [Academic Stories](#academic-stories)
  - [Industry Stories](#industry-stories)
  - [Student Projects and Competitions](#student-projects-and-competitions)
  - [Courseware and Curriculum Modules](#courseware-and-curriculum-modules)
- [Wireless Systems Research](#wireless-systems-research)
  - [6G Waveforms](#6g-waveforms)
  - [Non-Terrestrial Networks (NTNs) / Satellite Communications](#non-terrestrial-networks-ntns--satellite-communications)
  - [Reconfigurable Intelligent Surfaces (RIS) / Intelligent Reflecting Surfaces (IRS)](#reconfigurable-intelligent-surfaces-ris--intelligent-reflecting-surfaces-irs)
  - [Wireless Networks / Network Modeling / Network Simulation](#wireless-networks--network-modeling--network-simulation)
  - [Wireless Digital Twins](#wireless-digital-twins)
  - [Community Tools](#community-tools)

## General Resources

### Academic Stories

- [Teaching Digital Communication Theory with Simulink at Brigham Young University](https://in.mathworks.com/company/technical-articles/teaching-digital-communication-theory-with-simulink-at-brigham-young-university.html) helps to make complex theoretical concepts tangible and interactive for students, enhancing student understanding and engagement.
- [Lanzhou University enhanced Student Understanding of Electromagnetic Fields and Waves using MATLAB Live Scripts](https://in.mathworks.com/company/user_stories/enhancing-student-skills-through-innovative-teaching.html) by integrating simulations and interactive visualizations, improving teaching effectiveness and student engagement.
- [AI-Driven Innovations in Wireless Communication Education](https://in.mathworks.com/company/user_stories/ai-driven-innovations-in-wireless-communication-education.html) at Southern University of Science and Technology enhance student engagement and skill development through advanced experimental projects using MATLAB and Deep Learning Toolbox.
- [Penn State Develops Software Defined Radio Ground Station for Nanosatellite](https://in.mathworks.com/company/user_stories/penn-state-develops-software-defined-radio-ground-station-for-nanosatellite.html) using MATLAB and Simulink to model, simulate, and prototype a reconfigurable SDR system integrating TI DSPs and Xilinx FPGAs.
- [Optimizing Data Rates for Visible Light Communication (VLC) with Carrierless Amplitude and Phase (CAP) Modulation](https://in.mathworks.com/company/technical-articles/optimizing-data-rates-for-visible-light-communication-with-carrierless-amplitude-and-phase-modulation.html), Researchers from INSA Rennes and University of Sherbrooke used MATLAB for modeling transmitter, channel, and receiver components including LED nonlinearity, and validated the high-throughput with real-world hardware experiments.
- [Refining GPS Accuracy with Reduced LEO Satellite Dependency](https://in.mathworks.com/company/technical-articles/refining-gps-accuracy-with-reduced-leo-satellite-dependency.html), researchers from Virginia Tech used MATLAB and Satellite Communications Toolbox to demonstrate Doppler-only positioning with time-diverse measurements from four Low-Earth Orbit Satellites.

### Industry Stories

- [Using MATLAB to Develop 5G RF Front-End Components and Algorithms at Qualcomm](https://in.mathworks.com/company/user_stories/case-studies/using-matlab-to-develop-5g-rf-front-end-components-and-algorithms-at-qualcomm.html), a complete model of Tx/Rx paths with fixed-point digital blocks and hardware-accurate power amplifier models was developed to predict and optimize system performance, and automate testing across a range of 5G waveform combinations.
- [Nokia Develops 5G Communication Analysis App](https://in.mathworks.com/company/user_stories/enhancing-5g-communications-analysis-at-nokia-bell-shanghai.html) for 5G downlink receiver using 5G Toolbox, MATLAB Compiler, MATLAB App Designer, and MATLAB Web App Server, streamlining baseband data analysis and identifying hardware-software interface issues efficiently.
- [CENTUM develops the Lifeseeker system transforming cell phones into powerful locator beacons for search-and-rescue operations](https://in.mathworks.com/company/mathworks-stories/signal-processing-turns-cell-phones-into-search-and-rescue-beacons.html), leveraging MATLAB and Simulink to design and implement sophisticated signal processing that enable real-time geolocation, compatibile across multiple generations of cellular networks and diverse terrains.
- [DigitalGlobe Simulates Complete Satellite-to-Ground Communications Systems](https://in.mathworks.com/company/user_stories/digitalglobe-simulates-complete-satellite-to-ground-communications-systems.html) by modeling an end-to-end RF and digital link in Simulink—including 8-PSK modulation, Reed-Solomon encoding, adaptive LMS equalization, and Butterworth filtering to achieve higher data rates, low BER, and compliance with stringent spectral constraints.
- [NanoSemi Improves System Efficiency for 5G and Other RF Products](https://in.mathworks.com/company/user_stories/nanosemi-Improves-system-efficiency-for-5g-and-other-rf-products.html) by using MATLAB to rapidly develop and validate digital predistortion and machine learning algorithms to linearize RF power amplifiers and enabling early validation of IP for high-performance wireless systems.
- [Capgemini Accelerates O-RAN Development of 5G NR Wireless Communication System with Arria 10 FPGA](https://in.mathworks.com/company/user_stories/capgemini-accelerates-o-ran-development-of-5g-nr-wireless-communication-system-with-arria-10-fpga.html) by using MATLAB and Simulink for Model-Based Design of a 5G O-RAN emulator, reducing overall development time and helping validate communication protocols, signal processing algorithms, components, and third-party IP blocks.
- [ShortLink Uses Model-Based Design with Simulink and HDL Coder to Develop an IEEE 802.15.4 Receiver](https://in.mathworks.com/company/user_stories/shortlink-uses-model-based-design-with-simulink-and-hdl-coder-to-develop-an-ieee-802154-receiver.html) with GFSK/OQPSK/PSK modulation leveraging ready-made IP blocks and HDL code generation to accelerate FPGA prototyping, verify functionality using testbenches, and produce a hardware-ready ASIC design.
- [Qoherent Uses MATLAB to Accelerate Research on Next-Generation AI for Wireless](https://in.mathworks.com/company/user_stories/qoherent-uses-matlab-to-accelerate-research-on-next-generation-ai-for-wireless.html) leveraging 5G Toolbox, LTE Toolbox, and Deep Learning Toolbox to streamline signal classification workflows, reduce development time, and validate synthetic datasets against real-world 5G radio access network data.
- [Modeling 5G Millimeter Wave Beamformer Integrated Circuits](https://in.mathworks.com/company/technical-articles/modeling-5g-millimeter-wave-beamformer-integrated-circuits.html) with behavioural models of Otava OTBF103 BFIC across 24–40 GHz, incorporating power dividers, phase shifters, and nonlinear amplifiers from RF Blockset, and enabling system-level simulations of gain, phase, EVM, ACLR, and antenna performance before hardware availability.
- [MMRFIC Implements a 5G Massive MIMO Array with Hybrid Beamforming](https://in.mathworks.com/company/user_stories/case-studies/mmrfic-implements-a-5g-massive-mimo-array-with-hybrid-beamforming.html) using MATLAB, Phased Array System Toolbox, and 5G Toolbox to evaluate beamformer architectures, standard and custom channel models, and end-to-end uplink/downlink performance at mmWave frequencies for multiuser scenarios, optimizing link-level system performance.
- [Lekha Wireless Accelerates Development and Interoperability Testing of 5G NR Technology](https://in.mathworks.com/company/user_stories/lekha-wireless-accelerates-development-and-interoperability-testing-of-5G-nr-technology.html) by leveraging MATLAB and 5G Toolbox to build and validate complete 3GPP-compliant gNB signal chains—including MIMO, channel coding, and decoding—enabling unit-level and end-to-end testing, reducing development time, UE test setup time, and RF testing time.
- [Semiconductor Startups Access Tools Through Accelerator](https://in.mathworks.com/company/mathworks-stories/silicon-catalyst-helps-chip-based-semiconductor-startups-innovate-medicine-and-wireless-products.html) enabling companies like SPARK Microsystems to use MATLAB for RF testing, phased array design, and beamforming for ultra-wideband (UWB) transceivers with lower latency, higher bandwidth, and lower power consumption to support applications in gaming, audio, AR/VR, and smartwatches.

### Student Projects and Competitions

- [Wireless Systems Challenge Projects from MathWorks](https://github.com/mathworks/MATLAB-Simulink-Challenge-Project-Hub/blob/main/megatrends/Wireless%20Communication.md) on GitHub for undergraduate and graduate students.
- [Build a Wireless Communications Link with Software-Defined Radio](https://github.com/mathworks/MATLAB-Simulink-Challenge-Project-Hub/tree/main/projects/Build%20a%20wireless%20communications%20link%20with%20software%20defined%20radio) - Gain practical experience in wireless communication by designing inexpensive software-designed radios.
- [Classify RF Signals using AI](https://github.com/mathworks/MATLAB-Simulink-Challenge-Project-Hub/tree/main/projects/Classify%20RF%20Signals%20Using%20AI) - Use deep learning to classify wireless signals and perform real-world testing with software defined radios.
- [Optimize Antenna Performance in an Indoor Propagation Environment](https://github.com/mathworks/MATLAB-Simulink-Challenge-Project-Hub/tree/main/projects/Optimizing%20Antenna%20Performance%20in%20an%20Indoor%20Propagation%20Environment) - Design an antenna to optimize transmission and reception in indoor environment.
- [Optimization of Large Antenna Arrays for Astronomical Applications](https://github.com/mathworks/MATLAB-Simulink-Challenge-Project-Hub/tree/main/projects/Optimization%20of%20Large%20Antenna%20Arrays%20for%20Astronomical%20Applications) - Design a large antenna array and optimize its multiple design variables to achieve desired transmission/reception characteristics.
- [Improve the Accuracy of Satellite Navigation Systems](https://github.com/mathworks/MATLAB-Simulink-Challenge-Project-Hub/tree/main/projects/Improve%20the%20Accuracy%20of%20Satellite%20Navigation%20Systems) - Improve the accuracy of satellite navigation systems by using non-binary LDPC codes.
- [Signal Coverage Maps Using Measurements and Machine Learning](https://github.com/mathworks/MATLAB-Simulink-Challenge-Project-Hub/tree/main/projects/Signal%20Coverage%20Maps%20Using%20Measurements%20and%20Machine%20Learning) - Reduce the cost of 5G and IoT network deployment by generating coverage maps from limited measurements.
- [SDR University Challenge](https://in.mathworks.com/academia/student-competitions/sdr-university-challenge.html) - Identify specific challenges and use software-defined radios (SDRs) to build real-world, over-the-air solutions for land, air, and sea communications challenges.

### Courseware and Curriculum Modules

- [Introductory Communication Systems Course Using SDR](https://in.mathworks.com/matlabcentral/fileexchange/69417-introductory-communication-systems-course-using-sdr) - Course Materials for an Introduction to Analog and Digital Communications Systems Course using Software-Defined Radio, for undergraduate Electrical and Computer Engineering students.
- [Digital Communications Course](https://in.mathworks.com/matlabcentral/fileexchange/135964-digital-communications-course) - Instructional material for Digital Communications, a graduate level class at NYU Tandon.
- [Wireless Communications Onramp](https://matlabacademy.mathworks.com/details/wireless-communications-onramp/wireless) - Learn the basics of simulating a Wireless Communications link in MATLAB involving transmitting binary digits over a channel to a receiver.

## Wireless Systems Research

### 6G Waveforms

- [Introduction to OTFS Modulation](https://www.mathworks.com/help/comm/ug/otfs-modulation.html) \[Example\] - Simulate a communication link using Orthogonal Time Frequency Space (OTFS) modulation and compare it to Orthogonal Frequency Division Multiplexing (OFDM) modulation.
- [Configure Custom Modulation Schemes for 6G](https://www.mathworks.com/help/5g/ug/configure-custom-modulation-schemes-for-6g.html) \[Example\] - Explore custom modulation schemes for 6G using 5G Toolbox and 6G Exploration Library.
- [6G Link-Level Simulation](https://in.mathworks.com/help/5g/ug/pre-6g-link-level-simulation.html) \[Example\] - Measure throughput of a pre-6G link with larger bandwidths and sub-carrier spacing.
- [Explore 400 MHz 6G Waveform Using USRP X410](https://www.mathworks.com/help/5g/ug/explore-400-mhz-6g-waveform-using-usrp-x410.html) \[Example\] - Generate, transmit, capture, and analyze a large-bandwidth 6G candidate waveform using an NI USRP SDR.
- [Measure Impact of Sub-THz Hardware Impairments on 6G Waveforms](https://in.mathworks.com/help/5g/ug/evm-measurement-with-hex-x-phase-noise-model.html) \[Example\] - Explore impact of hardware impairments, including phase noise, power amplifier (PA) nonlinearity, and filters limiting spectral emissions outside of channel bandwidth on a candidate 6G waveform.
- [OTFS Modulation: Theory and Applications](https://in.mathworks.com/academia/books/otfs-modulation-mohammed.html) \[Book\] - A textbook covering fundamentals of OTFS, including the Zak theory of linear time-varying systems, delay-Doppler communication and radar sensing, and machine learning with MATLAB code implementing an OTFS transceiver.

### Non-Terrestrial Networks (NTNs) / Satellite Communications

- [Analyze NTN Coverage and Capacity for LEO Mega-Constellation](https://www.mathworks.com/help/satcom/ug/analyze-ntn-coverage-and-capacity-for-leo-mega-constellation.html) \[Example\] - Analyzes the coverage and capacity of Low-Earth Orbit (LEO) satellite constellations for NTN applications.
- [Coverage Maps for Satellite Constellation](https://in.mathworks.com/help/satcom/ug/coverage-maps-for-satellite-constellation.html) \[Example\] - Analyze received power from LEO satellite constellation to ground-based receivers and generate 2-D coverage maps over a region of interest.
- [NB-IoT NTN Link Budget Analysis](https://in.mathworks.com/help/satcom/ug/nb-iot-ntn-link-budget-analysis.html) \[Example\] - compute the link budget for narrowband Internet-of-Things (NB-IoT) equipment in NTN using the parameter sets described in 3GPP TR 36.763.
- [NB-IoT NTN NPDSCH Throughput](https://in.mathworks.com/help/satcom/ug/nb-iot-ntn-npdsch-throughput.html) \[Example\] - simulate a NB-IoT narrowband physical downlink shared channel (NPDSCH) throughput in a NTN channel modeled as ETSI Rician fading channel and the ITU-R P.681 land mobile-satellite (LMS) channel.
- [Receiver Position Estimation Using Range and Range-Rate Measurements in NTN Systems](https://in.mathworks.com/help/satcom/ug/receiver-position-estimation-using-range-and-range-rate-measurements-in-ntn-systems.html) \[Example\] - determine approximate position of a receiver on Earth surface using range and range-rate data from a single LEO satellite for satellite-based NTN systems.
- [NR NTN PDSCH Throughput](https://in.mathworks.com/help/satcom/ug/nr-ntn-pdsch-throughput.html) - measure physical downlink shared channel (PDSCH) throughput of a 5G NR link in a NTN channel, as defined by the 3GPP NR standard.
- [Model NR NTN Channel](https://in.mathworks.com/help/satcom/ug/model-nr-ntn-channel.html) \[Example\] - model two types of NR-NTN channels: a flat fading narrowband channel and a frequency selective fading tapped delay line (TDL) channel as defined in 3GPP TR 38.811.

### Reconfigurable Intelligent Surfaces (RIS) / Intelligent Reflecting Surfaces (IRS)

- [Introduction to Reconfigurable Intelligent Surfaces](https://in.mathworks.com/help/phased/ug/introduction-to-reconfigurable-intelligent-surfaces.html) \[Example\] - Simulate a simple RIS-aided link with a deterministic channel model and BPSK modulation.
- [Model Reconfigurable Intelligent Surfaces with CDL Channels](https://in.mathworks.com/help/5g/ug/model-reconfigurable-intelligent-surfaces-with-cdl-channels.html) \[Example\] - Simulate a 6G-like link using RIS and a stochastic channel with an iterative algorithm to control the phases of each RIS element.
- [Radar Sensing with Reconfigurable Intelligent Surfaces](https://in.mathworks.com/help/phased/ug/reconfigurable-intelligent-surfaces-ris-aided-sensing.html) \[Example\] - Model a RIS to help improve target detection for target outside a radar's field of view and a line-of-sight (LOS) link is not available.
- [Electromagnetic Analysis of Reconfigurable Intelligent Surface](https://in.mathworks.com/help/antenna/ug/electromagnetic-analysis-of-intelligent-reflecting-surface.html) \[Example\] - Model the response of a RIS using full-wave electromagnetic simulation with external phase control mechanism for varying reflection characteristics of the RIS.
- [Intelligent Reflecting Surfaces: Physics, Propagation, and Pathloss Modeling](https://github.com/emilbjornson/IRS-modeling) \[Code\] - Results from Özgecan Özdogan, Emil Björnson, Erik G. Larsson, "[Intelligent Reflecting Surfaces: Physics, Propagation, and Pathloss Modeling](https://arxiv.org/pdf/1911.03359)," IEEE Wireless Communications Letters.
- [Reconfigurable Intelligent Surfaces: Three Myths and Two Critical Questions](https://github.com/emilbjornson/RIS-myths) \[Code\] - Results from Emil Björnson, Özgecan Özdogan, Erik G. Larsson, "[Reconfigurable Intelligent Surfaces: Three Myths and Two Critical Questions](https://arxiv.org/pdf/2006.03377.pdf)," IEEE Communications Magazine, vol. 58, no. 12, pp. 90-96, December 2020.

### Wireless Networks / Network Modeling / Network Simulation

<!--
#### Overview

- [AB](https://www.mathworks.com/discovery/wireless-network.html)
- <https://www.mathworks.com/help/5g/ug/overview-system-level-simulation-in-5g-network-analysis.html>
-->

#### Cellular Communications

- [Evaluate 3GPP Indoor Reference Scenario](https://www.mathworks.com/help/5g/ug/evaluate-3gpp-indoor-reference-scenario.html) \[Example\] - Model, simulate, and evaluate the system-level performance of a 3GPP enhanced mobile broadband indoor hotspot scenario, described in 3GPP TR 38.913.
- [NR Intercell Interference Modeling](https://www.mathworks.com/help/5g/ug/nr-intercell-interference-modelling.html) \[Example\] - Simulate a 5G NR multicell interference scenario and measure the impact on network performance due to downlink intercell interference caused by nearby cells.
- [NR Cell Performance with Downlink MU-MIMO](https://www.mathworks.com/help/5g/ug/nr-cell-performance-with-downlink-mu-mimo.html) \[Example\] - Evaluate the system performance of downlink multi-user MIMO with a focus on link-to-system mapping-based abstract physical layer.
- [Massive MIMO Networks: Spectral, Energy, and Hardware Efficiency](https://github.com/emilbjornson/massivemimobook) \[Book\] - Model and simulate massive MIMO networks with spatially correlated fading channels. Assess the spectral efficiency, energy efficiency, and the impact of hardware impairments.

#### Cell-Free MIMO

- [Evaluate Performance of Cell-Free mMIMO Networks](https://www.mathworks.com/help/5g/ug/evaluate-performance-of-cell-free-mmimo-networks.html?requestedDomain=) \[Example\] - Evaluate the performance of centralized and distributed implementations of cell-free massive MIMO networks with full physical layer processing.
- [Making Cell-Free Massive MIMO Competitive With MMSE Processing and Centralized Implementation](https://github.com/emilbjornson/competitive-cell-free) \[Paper\] - Simulate and analyze cell-free massive MIMO systems under different degrees of cooperation among the APs.
- [Scalable Cell-Free Massive MIMO Systems](https://github.com/emilbjornson/scalable-cell-free) \[Paper\] - Simulate and analyze scalable cell-free massive MIMO systems by exploiting the dynamic cooperation cluster concept from the network MIMO literature.
- [Foundations of User-Centric Cell-Free Massive MIMO](https://github.com/emilbjornson/cell-free-book) \[Book\] - Comprehensively model and simulate cell-free massive MIMO networks, tackling channel estimation, uplink and downlink operations, and spatial resource allocation.

<!--
#### WLAN

- <https://www.mathworks.com/help/wlan/ug/802-11be-system-level-simulation-using-emlsr-multi-link-operation.html> \[Example\] -
- <https://www.mathworks.com/help/wlan/ug/dynamic-bandwidth-channel-access-in-wifi-networks.html> \[Example\] -

#### Bluetooth
- <https://www.mathworks.com/help/bluetooth/ug/bluetooth-le-auracast-broadcast-audio-simulation-using-lc3-encoded-audio.html> \[Example\] -
- <https://www.mathworks.com/help/bluetooth/ug/simulate-periodic-advertisements-in-a-bluetooth-le-network.html> \[Example\] -

#### Coexistence
- <https://www.mathworks.com/help/wlan/ug/explore-bluetooth-le-and-wlan-noncollaborative-coexistence-in-6ghz-with-lbt-ssbd-and-daa-channel-access-mechanisms.html> \[Example\] -
- <https://www.mathworks.com/help/bluetooth/ug/phy-simulation-of-bluetooth-br-edr-and-le-in-presence-of-bluetooth-nr-or-wlan-interference.html> \[Example\] -
-->

### Wireless Digital Twins

- [Mobility Modeling with Ray Tracing Channel](https://www.mathworks.com/help/comm/ug/mobility-modeling-with-ray-tracing-channel.html) \[Example\] - Model user mobility in a communication link with a ray-tracing channel model.
- [Indoor MIMO-OFDM Communication Link Using Ray Tracing](https://www.mathworks.com/help/comm/ug/indoor-mimo-ofdm-communication-link-using-ray-tracing.html) \[Example\] - Perform ray tracing in an indoor environment and use the results to build a channel model for a link-level simulation with the MIMO-OFDM technique.
- [Connecting MATLAB with NVIDIA Aerial Omniverse Digital Twin for 6G Research](https://blogs.mathworks.com/semiconductors/2025/03/12/connecting-matlab-with-nvidia-aerial-omniverse-digital-twin-for-6g-research/) \[Blog\] - Import a channel response generated with NVIDIA Aerial Omniverse to MATLAB for a 6G-like link-level simulation.
- [Analyze SINR in 6G FR3 Network Using Digital Twin](https://www.mathworks.com/help/phased/ug/analyze-sinr-in-6g-fr3-network-using-digital-twin.html) \[Example\] - Use digital twin techniques to analyze the SINR performance in a 6G FR3 network.

### Community Tools

- [QuaDRiGa - QUAsi Deterministic RadIo channel GenerAtor](https://github.com/fraunhoferhhi/QuaDRiGa) - generate realistic radio channel impulse responses for system-level simulations of mobile radio networks.
- [NYUSIM](https://wireless.engineering.nyu.edu/nyusim/) - comprehensive mmWave and sub-THz wireless channel simulator supporting realistic 5G and 6G simulations across frequencies from 0.5 GHz to 150 GHz for various indoor and outdoor scenarios.


