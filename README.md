# vehicleCAPTAIN
The vehicle communication platform to anything (vehicleCAPTAIN) is a collection of software to enable a quick entry into the vehicle-to-anything (V2X) domain.

## Repositories
The vehicleCAPTAIN is structured into the following components:

- ITS Message Libraries (with ETSI source)
  - [C/CXX](https://github.com/virtual-vehicle/vehicle_captain_its_lib_c_cxx):
    is autogenerated from [ETSI sources](https://forge.etsi.org/rep/ITS/asn1) with CXX wrapper. 
- Platform
  - [Routing Core](https://github.com/virtual-vehicle/vehicle_captain_routing_core):
    is a program that can support multiple V2X hardware components with only one interface.
  - [Receiver Example](https://github.com/virtual-vehicle/vehicle_captain_routing_receiver_example):
    is a receiver example for the routing software
  - [Sender Example](https://github.com/virtual-vehicle/vehicle_captain_routing_sender_example):
    is a sender example for the routing software
- ROS2 Support
  - [ROS2 ITS Messages](https://github.com/virtual-vehicle/v2x_msgs):
    is an autogenerated library from [ETSI sources](https://forge.etsi.org/rep/ITS/asn1) for ROS2.
  - [ROS2 V2X Gateway](https://github.com/virtual-vehicle/v2x_gw):
    is a translator for asn1 messages to ROS2 type messages.
- Tools
  - [asn1 parser](https://github.com/virtual-vehicle/vehicle_captain_asn1_parser):
    is a fork of an FOSS [asn1 parser](https://github.com/brchiu/asn1c/tree/velichkov_s1ap_plus_option_group_plus_adding_trailing_ull) to autogenerate ROS2 messages from [ETSI sources](https://forge.etsi.org/rep/ITS/asn1).

## Copyright
The software is managed by FOSS licenses in the specific repositories.

Publications: please cite the [vehicleCAPTAIN paper](https://TODO_link_to_paper_when_it_is_published) if you used any part of this software toolbox for your work.

## Contribution Guidelines
Feel free to add fixes and new features to the specific repositories.

## Authors
Please find contact information in the corresponding repositories.

## Acknowledgement
The majority of this work is part of my ([Christoph Pilz](https://www.researchgate.net/profile/Christoph-Pilz) PhD studies at [Graz University of Technology](https://www.tugraz.at/home) in cooperation with the [Virtual Vehicle Research GmbH](https://www.v2c2.at/).

Main contributions received funding by the following parties:

### COMET K2
The publication was written at Virtual Vehicle Research GmbH in Graz and partially funded by the COMET K2 Competence Centers for Excellent Technologies from the Austrian Federal Ministry for Climate Action (BMK), the Austrian Federal Ministry for Digital and Economic Affairs (BMDW), the Province of Styria (Dept. 12) and the Styrian Business Promotion Agency (SFG). The Austrian Research Promotion Agency (FFG) has been authorised for the programme management.

### InSecTT 
InSecTT (www.insectt.eu) has received funding from the ECSEL Joint Undertaking (JU) under grant agreement No 876038. The JU receives support from the European Union's Horizon 2020 research and innovation programme and Austria, Sweden, Spain, Italy, France, Portugal, Ireland, Finland, Slovenia, Poland, Netherlands, and Turkey.
The document reflects only the author's view and the Commission is not responsible for any use that may be made of the information it contains.
