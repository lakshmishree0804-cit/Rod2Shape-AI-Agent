[Rod2Shape_Hackathon_Pro (2).pdf](https://github.com/user-attachments/files/22746596/Rod2Shape_Hackathon_Pro.2.pdf)

# Rod2Shape-AI-Agent
Rod2Shape turns rod lengths into closed 2D/3D shapes with reasoning and interactive visualization. It forms triangles, quadrilaterals, or polygons (up to octagons) and explains its logic. Ideal for hackathons, education, and design projects, it showcases modular, explainable AI.Every rod tells a story, every story becomes a shape.

🔧 Key Components
Input Handler – User provides number of rods and their lengths.
Reasoning Core – Classifies possible shapes:
3 rods → Triangle
4 rods → User chooses: Triangle (closed with 4 edges) or Quadrilateral
5–8 rods → Regular polygons (Pentagon → Octagon)
<3 or >8 rods → Graceful fallback: “Model not trained yet.”
Shape Constructor – Places vertices in 2D/3D space, ensuring rods form a closed loop.
Visualization Module – Generates interactive 3D visuals using Plotly.
This modular design makes Rod2Shape scalable, so future versions can extend to polyhedra (Cube, Tetrahedron, Octahedron, etc.).

Highlights
⚡ Instant reasoning + visualization
✅ Closed figures for rods 3–8
🎨 Interactive 3D output (via Plotly)
🌍 Scalable – extendable to cubes, pyramids, and beyond
