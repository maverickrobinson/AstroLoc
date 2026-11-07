
AstroLoc is an advanced web-based geospatial intelligence and scientific discovery platform engineered to identify, characterize, and evaluate terrestrial Earth analog sites for lunar and Martian exploration base camps.

Link to Project Demonstration
https://canva.link/zxdbsrmayvizmrh (Canva)
AstroLoc
https://drive.google.com/drive/folders/1qnrpWQHGgKuQIFedxXLEgO-N1LTU8oas?usp=drive_link (Google Drive)
Project Details
The Problem
Selecting optimal terrestrial analog sites for lunar and Martian exploration missions requires synthesizing complex multidisciplinary data across geology, mineralogy, extreme thermal conditions, topography, subsurface shelter, and astrobiology. Traditional mission planning relies on fragmented literature and static catalogs, lacking dynamic 3D spatial visualization and rigorous multi-criteria similarity evaluation tools.

How It Works
Data Ingestion & Benchmarking: The platform initializes with a curated database of primary Mars and Moon analog locations and research facilities.


Live Telemetry & Elevation Fetching: Users can query real-time meteorological parameters and digital elevation models via NASA POWER and Copernicus/Open-Meteo elevation APIs for any coordinate.
 
5-Dimension Evaluation & Visualization: The interactive 3D globe renders precision-styled target markers while the scoring engine computes exact fidelity percentages across five key scientific dimensions.
 
Key Features & Benefits
Interactive 3D Planetary Globe: Built with Three.js and Globe.gl, offering satellite, geological, relief, and thermal map visualization layers.


Dual Planetary Target Switcher: Instant filtering between Mars benchmarks (orange pointers) and Moon benchmarks (blue pointers).
 
5-Dimension Fidelity Scoring Engine: Dynamic weighting across geological, topographic, thermal, subsurface, and astrobiological criteria.
 terra_x_planetary_analog_discovery_platform_ver7.html+ 1
Comparative Analysis Deck: Side-by-side telemetry matrices and 5-dimension radar charts for evaluating multiple analog sites simultaneously.
 terra_x_planetary_analog_discovery_platform_ver7.html+ 1
Export Capabilities: One-click export of individual site dossiers and comparative analysis reports in Markdown and JSON formats.
 terra_x_planetary_analog_discovery_platform_ver7.html+ 1
Tools, Coding Languages & Hardware Used
Frontend & Visualization: HTML5, JavaScript (ES6+), Tailwind CSS, Three.js, Globe.gl, JetBrains Mono typography.
APIs & External Services: NASA POWER Climatology API, Open-Meteo Elevation API, Nominatim Geocoding API.
Data Storage: Browser LocalStorage for persistent user-added candidate sites and custom similarity weights.
t
Use of Artificial Intelligence (AI)

We use AI such as Gemini argon and Lovable Ai to accelerate the project to finish.

Product Features: An algorithmic 5-dimension weighted scoring model combined with automated spatial clustering and micro-label culling to prevent visual clutter on the 3D globe interface.


Development Assistance: Utilized AI collaborators for rapid prototyping, UI layout structuring, and JavaScript modularization.
NASA Data
NASA POWER (Prediction of Worldwide Energy Resources) API: Utilized for climatological parameters including surface temperatures and annual precipitation estimates.
Planetary Analog Benchmarks: Leveraged open datasets and spectral libraries associated with NASA analog research (CRISM, MOLA, THEMIS, HiRISE, LOLA, Diviner, LROC).

Space Agency Partner & Other Data
Copernicus / Open-Meteo DEM: Utilized digital elevation models for site altitude and topographic relief profiling.
OpenStreetMap Nominatim API: Integrated for global place-name geocoding and coordinate resolution.

