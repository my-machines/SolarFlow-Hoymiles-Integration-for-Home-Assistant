# SolarFlow-Hoymiles Integration for Home Assistant

This automation is executed within Home Assistant, configured to control a Hoymiles inverter via Open DTU, ensuring seamless connection and operational efficiency. The automation is specifically designed for use with a Zendure SolarFlow Hub 1200, an AB2000 Battery, and two solar panels, each with a capacity greater than 400 Wp. However, it can be adapted to fit the size of your installation. Its main objective is to prioritize battery charging, maximizing energy storage before directing excess energy elsewhere.

The automation serves as a template, offering a foundational structure that users should customize to align with their system's specific requirements and energy goals. As a work in progress, users are encouraged to modify and enhance the automation to meet their changing needs.

Your feedback and enhancements are highly valued. Contributing to this project can aid in its improvement, benefiting a broader community interested in optimizing their solar energy systems with Home Assistant.

Please use this code cautiously, recognizing the responsibility to adjust and validate it for your setup. The author assumes no liability for any discrepancies, inefficiencies, or potential damages arising from the use of this automation. Conduct thorough testing in your environment to confirm the automation's effectiveness and safety before full integration into your energy management system.

## Preconditions

1. **Integrate Your Solarflow Data into Home Assistant:**  
   Follow the instructions in this guide (in German) to integrate MQTT data from your Solarflow device into Home Assistant: [Integrating Zendure Solarflow Superbase into Home Assistant](https://www.justiot.de/smart-home/anleitung-zendure-solarflow-superbase-in-home-assistent-einbinden/).

2. **Access Your Hoymiles Inverter:**  
   Ensure access to your Hoymiles inverter via openDTU. For more information, visit [openDTU](https://www.opendtu.solar/).
