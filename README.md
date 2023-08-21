# ARCHhome
AR visualizing tool for home generation
The AI assistant interprets verbal instructions and extracts key parameters to generate floorplan variations. It analyzes the instructions, identifies relevant information, and understands the user's requirements. The assistant then procedurally creates 10-20 different floorplan designs that meet the specified requirements. To ensure a range of possibilities, the AI assistant considers variations in room sizes, layout configurations, and architectural elements. These variations are rendered in both 2D and 3D using a simulation engine, allowing the user to visualize the designs and assess their suitability. The designs are presented in an intuitive interface where the user can scroll through, compare, and choose their favorite. The user can tap or click on different parts of the design to provide specific feedback, allowing for refinements and adjustments to be made. Taking this feedback into account, the AI assistant refines the chosen design iteration based on the user's preferences. It optimizes the design by considering factors such as room arrangement, size adjustments, and architectural details. Once the design is improved to meet the user's preferences, it is exported to CAD software for further advancement to 3D modeling. This allows for a more detailed visualization and analysis of the design.

Frontend Interface

Browser-based web app for conversational interaction
JavaScript for handling voice inputs/outputs
Vue.js or React for modular interface components
Html2Canvas for screenshot exports
Conversational AI Core

Python backend
Open source Claude or MiniLM architecture for speech processing
Train conversational model on architecture data
Expose API for parsing user instructions
Generative Model

Python module for procedural floorplan generation
Constraint-based algorithms parameterized by Claude's extracts
Output design variations as SVG files
Simulation and Rendering

Blender and Three.js for 3D visualization
Programmatically load SVGs and render variations
Allow UI-based design selection and refinement
File Export

DXF export for chosen design via Blender Python API
CAD integrations for advanced modeling
