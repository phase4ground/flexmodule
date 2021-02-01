# Gnu Radio Implementation for FLEX

Gnu Radio is an open-source development toolkit, capable of simulating real-world radio systems. It is a modular flow-based framework, in which you piece together predefined functions and operations to develop your own communication system. 
The FLEX-6400 is a SDR where components and calibrations usually defined in hardware are instead implemented with software. Most of the RF signal processing is performed with an API/Driver, allowing for greater flexibility in what channels and frequencies the radio is listening to, as well as easier modulation of the signal it’s transmitting. SDRs can be reconfigured on the fly, essentially completely transforming its purpose with plug-and-play programs able to run on demand.
Currently, The FLEX-6400 radio comes with an API, but it is restrictive due to the fact it is built with the .NET framework. Building a new API with gnu-radio would enable cross-platform uses of the SDR, opening many more opportunities to use its potential.
Many examples of these uses are research projects that could benefit from the flexibility of Gnu Radio and the performance of FLEX. One example could be Oberoi’s paper (Oberoi, 2000), in which the authors outline how low frequency radio signals are the last truly unexplored area of Earth’s electromagnetic spectrum. This is a common research proposal, and one I believe could benefit from the inclusion of a SDR. For example, SDRs can be quickly and easily upgraded with enhanced features. This update can be delivered over-the-air, meaning the desired radio settings can be adjusted with the satellite already deployed. Furthermore, Gnu Radio is an excellent framework to create these updates, so a marrying of the two may prove very beneficial.
The general purpose of this project is a proof of concept through the combination of the FLEX-6400 and Gnu Radio, but there are still some clear objectives that should be met at the end of the 13 weeks. These objectives are discussed in the next section.