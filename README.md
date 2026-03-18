# Recreating the Cessna 210 (NASA Variant) Using OpenVSP

## Project Overview
This project recreates the **Cessna 210 aircraft (NASA variant)** using **Open Vehicle Sketch Pad (OpenVSP)**, a parametric aircraft geometry tool widely used in aerospace engineering. The model combines **solid 3D renderings** and **wireframe views** to visualize aerodynamic surfaces, structural layout, and stability characteristics.

## Key Features
- **Wing Configuration**: High-wing design for stability and visibility.
- **Tail Assembly**: Conventional tail with vertical and horizontal stabilizers.
- **Fuselage Design**: Streamlined cockpit and cabin sections with aerodynamic shaping.
- **Wireframe Analysis**: Red wireframe + blue propeller views for aerodynamic simulations.
- **Color-Coded Models**: Blue wings, green stabilizers, teal fuselage for clarity.

## Aircraft Geometry Parameters
- **Wing Span**: 36.20 ft  
- **Wing Area**: 172.21 ft²  
- **Aspect Ratio**: 7.61  
- **Root Chord**: 5.51 ft  
- **Tip Chord**: 4.00 ft  
- **Dihedral**: 1.5°  

- **Fuselage Length**: 24.58 ft  
- **Max Fuselage Width**: 3.85 ft  

- **Horizontal Tail Area**: 45.46 ft²  
- **Horizontal Tail Span**: 12.99 ft  
- **Vertical Tail Area**: 20.68 ft²  
- **Vertical Tail Span**: 5.17 ft  

## Methodology
- **Image Tracing**: Imported three-view drawings (top, front, side, iso) into OpenVSP.  
- **Tail Sizing**: Adjusted dimensions for positive static margin and realistic stability.  
- **Empirical Ratios**: Fine-tuned geometry to match general aviation standards.  

## Applications
- Educational visualization of aircraft geometry.  
- Aerodynamic and structural analysis.  
- Design validation using three-view references.  

---

### Repository Contents
- `models/` → OpenVSP files of the Cessna 210  
- `images/` → Solid and wireframe renderings (top, front, side, iso views)  

---
