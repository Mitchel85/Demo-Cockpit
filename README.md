# Real Estate Management Cockpit — Christian Hoffmann

## Overview
This cockpit serves as the "digital nervous system" for professional real estate management. It centralizes key performance indicators, business processes, and technical dependencies into a single, local, high-performance interface.

## Key Features
- **Live Dashboard**: Real-time display of critical metrics including 142 managed units, €184k monthly rental income, and a 96.5% occupancy rate.
- **BPMN Processes**: Standardized workflows for property leasing and maintenance ticket management, visualized via Mermaid.js. The leasing process is optimized for horizontal viewing (2400px width), while maintenance tickets are presented in a compact vertical flow.
- **C4 Architecture Model**: A comprehensive map of the digital infrastructure, illustrating the connections between the Admin Backend, the Tenant Portal, and external systems like DATEV and the Schufa API.
- **Financial Analysis**: A detailed breakdown of fixed costs (e.g., maintenance, insurance, energy) including a Sankey diagram that visualizes the flow of expenses per building.
- **Portfolio Analytics**: Interactive doughnut charts (powered by Chart.js) visualizing vacancy rates and revenue types. The charts automatically filter out 0% values and display absolute numbers alongside percentages in a custom legend.
- **Interactive Knowledge Graph**: A dynamic entity-relationship map (powered by Vis.js) connecting people, properties, and processes. Clicking on nodes reveals specific details about each entity.

## Technologies Used
- **HTML5/CSS3**: Structured with a professional "Dark Mode" aesthetic and responsive design.
- **Mermaid.js**: Enables "Diagrams-as-Code" for scalable and easily updatable process maps and charts.
- **Chart.js**: Provides high-quality, interactive financial visualizations.
- **Vis.js**: Used for the interactive network visualization of the business knowledge base.
- **Content Delivery Networks (CDN)**: All required libraries are loaded via CDN to ensure the cockpit remains a lightweight, single-file solution without local installation requirements.

## Setup and Usage
1. **Local Access**: Simply open the `cockpit.html` file in any modern web browser.
2. **Connectivity**: An active internet connection is required to fetch the visualization libraries via CDN.
3. **Navigation**: Use the horizontal tab-based navigation to switch between modules without reloading the page.

## Privacy and Control
In line with the "0-Euro-Cockpit" philosophy, all sensitive data remains local and under the user's control. This architecture ensures maximum data privacy while maintaining professional-grade analytical capabilities.

---
*Developed by Christian Hoffmann as part of the "0-Euro-Cockpit" framework.*
