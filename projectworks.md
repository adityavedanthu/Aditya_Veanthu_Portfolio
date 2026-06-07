## Project 1 – AI-Driven Tool Life Prediction in Factory+

* Leading the integration of the **SmaRT TLP (Smart Real-Time Tool Life Prediction)** digital twin within the Factory+ open-source framework, establishing a scalable AI architecture for real-time tool wear monitoring in high-value manufacturing environments.
* Developing high-speed data pipelines using **Siemens Brownfield Connectors (BFCs)** to facilitate the standardised streaming of CNC machine signals.
* Conducting industrial case studies in turning and composite drilling, overseeing the collection of high-frequency sensor data and ground-truth annotation via the **Auto Tool Wear Imaging System (ATWIS)** for deep-learning model validation.
* Performing objective benchmarking between edge-based and cloud-integrated deployments, evaluating system latency, prediction accuracy, and scalability to establish robust and transferable digital manufacturing frameworks.

## Project 2 – Manipulation of Residual Stress in Castings

* Led the end-to-end automation of the Contour Method workflow in **ABAQUS** using Python scripting, reducing simulation setup and execution time from approximately 15 minutes to under 60 seconds while ensuring a repeatable, error-free numerical reconstruction pipeline.
* Engineered a novel Python-based volumetric material removal framework to generate watertight STL stage geometries from G-code toolpaths, bridging the gap between CAD/CAM and FEA and enabling accurate distortion modelling of intermediate machining sequences.
* Developed and validated an enhanced version of the AMRC Bulk Residual Stress measurement workflow, replacing legacy GUI-based tools with streamlined MATLAB and Fortran (**UDISP.for**) integrations to improve spatial resolution and local stress capture in complex components.
* Quantified the impact of heat treatment and quenching on residual stress heterogeneity in aluminium and titanium castings, identifying stress magnitudes of up to **150 MPa** and validating numerical predictions against international **KIMS (Korea Institute of Materials Science)** benchmarks.
* Implemented a structured uncertainty quantification methodology using stochastic perturbation techniques to establish **95% confidence intervals (±18–19 MPa)** and proposed Monte Carlo-based simulation frameworks to improve predictive model reliability.

## Project 3 – Rotational Vibration-Assisted Incremental Sheet Forming (RV-ISF)

* Led delivery of the RV-ISF research programme on the **Hermle C52 5-axis CNC platform** and **Lasertec 65 3D CNC platform**, optimising the thermo-mechanical forming of **AA5251** and **AA6082** alloys.
* Engineered a high-resolution measurement chain integrating a Kistler dynamometer, IEPE tri-axial accelerometers, eddy-current sensor, laser displacement sensor, and FLIR thermal imaging camera, utilising MATLAB and Python for signal processing and spectral decomposition to isolate tool-induced vibrations.
* Designed and executed a systematic **Design of Experiments (DoE)** study that achieved a **15.8% reduction in forming forces** and a **21.2% improvement in thermal management** through the implementation of novel rosette tool geometries.
* Established a rigorous validation framework and led industrial case studies to evaluate the scalability of RV-ISF for large-scale automotive components.

## Project 4 – RiR: Virtual Prediction of Vibrations and Their Effects on Machining-Induced Residual Stresses

* Developed and virtually verified CNC turning programmes for **C45 steel** using **Siemens NX** and **CGTech Vericut**, engineering specialised workpieces with fins for Cutting Force Coefficient (CFC) testing and ensuring error-free roughing, finishing, and plunging operations.
* Participated in on-machine experimental trials using the **WFL M30 CNC platform** with real-time process monitoring, conducting tap testing and modal analysis on dynamometer, tool, and workpiece assemblies to characterise system stability and identify vibration limits affecting surface integrity.
* Served as the primary technical lead for the **Research in Residence (RiR)** programme, collaborating with academic partners to translate complex machining dynamics into validated, data-driven manufacturing strategies.

## Project 5 – Korean Institute of Materials Science (Prediction of Residual Stress in Thin-Wall Aluminium Alloy Components)

* Developed a robust finite element framework in **ABAQUS** to predict deformation in large-scale aerospace aluminium extrusions (~950 mm), utilising element deactivation methods to simulate sequential material removal and stress redistribution.
* Engineered and implemented user-defined subroutines (**SIGINI/UMAT**) to integrate experimentally derived **Bulk Residual Stress (BRS)** and **Machining-Induced Residual Stress (MIRS)** fields, enabling spatially and depth-dependent stress mapping.
* Designed a hybrid meshing architecture using **C3D8 structured** and **C3D4 unstructured** elements, incorporating refined surface layers to accurately capture near-surface stress gradients while maintaining geometric flexibility for thin-walled components.
* Validated predictive models against high-precision **CMM** measurements, successfully characterising bending-dominated distortion profiles and providing a transferable basis for industrial process optimisation.

## Project 6 – Benchmarking of Residual Stress in Aluminium Castings

* Led a benchmarking programme using the **Contour Method** to quantify bulk residual stresses and distortion in **11 complex aerospace-grade aluminium castings**, overseeing the complete workflow from WEDM sectioning through to final stress reconstruction.
* Performed surface deformation measurements using a **Hexagon Leitz PMM-C CMM**, implementing advanced data-processing techniques including cubic spline fitting and spatial interpolation to reduce measurement noise and improve displacement mapping accuracy.
* Developed linear-elastic finite element models in **ABAQUS** to compute full-field residual stress distributions using refined meshing strategies and displacement boundary conditions to correlate measured deformation with internal stress states.
* Established a robust validation framework through statistical repeatability studies and uncertainty quantification (**±11% error band**), identifying localised stress concentrations and improving confidence in experimental results.
