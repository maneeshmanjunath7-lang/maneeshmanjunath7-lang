# Hi, I'm Maneesh Manjunath 👋

**Satellite Platform Engineering | Operations & Performance | Python/MATLAB | Verification & Validation**

I am an M.Sc. Aerospace Engineering candidate at the Technical University of Munich and a Geospatial Analyst Intern at osapiens Terra. My work connects satellite-system architecture, Earth-observation data, scientific software, payload integration, and engineering verification.

## Current focus

- Completing my master’s thesis on task allocation in heterogeneous distributed satellite systems
- Comparing 891 Walker-constellation and central-node configurations using Python and TAT-C
- Analysing communication, observation, capacity, latency, robustness, and deadline-performance trade-offs
- Supporting satellite-image analysis, GIS validation, and quality-control workflows at osapiens Terra
- Developing a quality-aware TanDEM-X DEM Change Map proof of concept for Arctic permafrost change
- Expanding hands-on experience in spacecraft payload electronics, interfaces, testing, and anomaly investigation

## Featured public work

### [Quality-Aware TanDEM-X DEM Change Analysis](https://github.com/maneeshmanjunath7-lang/TANDEMX-48hours) *(ongoing)*

A reproducible 48-hour proof of concept investigating apparent negative elevation change at a published active retrogressive thaw-slump site in eastern Taymyr.

- Uses public DLR TanDEM-X 30 m DEM Change Map products: FIRST1622 and LAST1622
- Integrates elevation change, acquisition date, height-accuracy indication, and reliability classes
- Emphasises archive validation, quality masks, stable-terrain diagnostics, uncertainty sensitivity, and evidence-bounded claims
- Analyses SAR-derived DEM products; it does not claim raw SAR or InSAR processing

### [MetNet-2-Inspired Precipitation Nowcasting](https://github.com/maneeshmanjunath7-lang/metnet2-inspired-nowcasting)

**TUM semester thesis | Grade 1.0 | 11 ECTS**

Developed and evaluated a reduced MetNet-2-inspired workflow for short-term precipitation nowcasting under limited academic computing resources.

- Uses six five-minute historical frames to forecast eight future frames over a 40-minute horizon
- Combines PyTorch, ConvLSTM layers, and dilated convolutional networks
- Includes weather-radar data preparation, training, validation, lead-time evaluation, and scientific documentation
- Preserves the recoverable prototype and reported results without overstating full reproducibility

## Current academic research

### Distributed Satellite Systems — Master’s Thesis

**Impact of Central Node Orbital Configuration on Task Allocation in Heterogeneous Distributed Satellite Systems**

Developing a modular Python and TAT-C simulation framework for architecture trade studies and wildfire-response task allocation in Walker constellations.

- Evaluates 891 architecture and central-node configurations
- Models priority-aware dissemination, observation opportunities, finite communication-window capacity, and deadlines
- Analyses latency, completeness, link usage, robustness, sensitivity, and tasks reaching 100% of satellites before deadline
- Uses Python, TAT-C, Skyfield, NumPy, Pandas, Matplotlib, structured campaign configurations, and parallel execution

The research code and full results are not published here while the thesis is ongoing.

## Spacecraft engineering and verification

### EventSat — Event-Based Vision Payload

- Co-developed traceable electrical requirements and interfaces for an event-camera payload
- Integrated a Jetson Orin Nano, STM32 controller, GNSS, IMU, environmental sensors, storage, and recovery trackers
- Supported functional verification and post-flight root-cause analysis after a low-temperature battery-BMS cutoff
- Converted flight findings into thermal-test, battery-selection, and interface improvements

### Thermal-vacuum and control projects

- Supported instrumentation and a three-cycle TVAC campaign for a spacecraft thermal model
- Correlated measured and simulated temperature histories using Thermal Desktop and SINDA
- Contributed to a PID/PWM temperature-regulator prototype using thermistors, heating foil, Peltier cooling, and Teensy control

## Professional experience

- **osapiens Terra — Geospatial Analyst Intern:** satellite-image analysis, GIS workflows, segmentation validation, quality control, and technical documentation
- **Airbus Group India — Associate Engineer:** physical design and integration for A321 XLR electrical-harness installations using CATIA V5/DMU and ENOVIA VPM
- **TUM Project IDEAL — Student Research Assistant:** structured design-build-test, inspection, validation, and post-processing for aerospace additive-manufacturing research

## Tools and technologies

**Satellite systems and mission analysis:** TAT-C, Skyfield, STK, GMAT, Walker constellations, observation geometry, communication-window analysis, architecture trade studies  
**Earth observation and GIS:** QGIS, PostGIS, Rasterio, GeoPandas, Sentinel-3 SLSTR, VIIRS FIRMS, RADOLAN, IMERG, ERA5, TanDEM-X DEM Change Maps  
**Programming and data:** Python, MATLAB, C++, PyTorch, NumPy, Pandas, SciPy, Matplotlib, Linux, Git, NetCDF, GeoJSON, YAML  
**Spacecraft integration and V&V:** requirements, interfaces, electrical integration, instrumentation, TVAC, thermal cycling, telemetry, anomaly investigation  
**Engineering tools:** CATIA V5, DMU, ENOVIA VPM, Thermal Desktop, SINDA, Siemens NX, SolidWorks

## Recent public activity

<!-- RECENT_ACTIVITY:START -->
- **2026-09-02:** Hardened public thesis evidence-table preservation across Git and CI checkouts ([CI safeguard](https://github.com/maneeshmanjunath7-lang/Master-Thesis/commit/4736640cf50e69e9a81e17816b022b43f3438470), [byte-preservation update](https://github.com/maneeshmanjunath7-lang/Master-Thesis/commit/1e8916fa739230d598dfdaff5d672170e27c1839)).
- **2026-09-02:** Updated the public [Master’s thesis report with validated California results](https://github.com/maneeshmanjunath7-lang/Master-Thesis/commit/9050dc3b7dd0f217dc7b775ab0d49629edf7e38a).
- **2026-08-31:** Created and structured the [TANDEMX 48-hour project](https://github.com/maneeshmanjunath7-lang/TANDEMX-48hours) with reproducibility, data-protection, provenance, and scientific-claims safeguards.
- **2026-08-11:** Published reported lead-time metrics and documented the recoverable [MetNet-2-inspired nowcasting repository](https://github.com/maneeshmanjunath7-lang/metnet2-inspired-nowcasting).
<!-- RECENT_ACTIVITY:END -->

## Connect

- [Engineering portfolio](https://maneesh-aerospace-portfolio.vercel.app)
- [LinkedIn](https://www.linkedin.com/in/maneesh-manjunath-4bba7614b/)
- [Email](mailto:maneesh.manjunath7@gmail.com)
