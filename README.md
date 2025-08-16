A vibrant, hands-on physics playground built with Python and pygame.
It features an authentic, real-time fluid dynamics engine—create walls and boundaries, pour colorful liquid, and watch emergent patterns swirl, collide, and cascade across the screen. It’s part sandbox, part art toy, and endlessly mesmerizing.


---

✨ Features

Authentic Fluid Simulation
Stable, real-time 2D fluid solver (advection, diffusion, pressure projection) with pleasing, painterly motion.

Interactive Sandbox
Draw walls and boundaries, spawn liquid/ink, and stir the fluid with your mouse to sculpt the flow.

Color-Rich Visuals
Multiple dye channels blend into vivid gradients; tweak palette and diffusion for wildly different moods.

Physics Toys
Toggle gravity, viscosity, turbulence, and boundary behavior to explore fluid regimes from silky to chaotic.

Screenshot & Presets
Save moments you love and reload parameter presets to experiment quickly.



---

🕹️ How to Play

Left Click + Drag: Paint walls/boundaries

Right Click + Drag: Pour colorful liquid (dye)

Middle Click + Drag / Hold Shift + Drag: Add velocity (stir / push the fluid)

1 / 2 / 3: Switch dye colors or palettes

G: Toggle gravity

V / B: Decrease / increase viscosity

T: Toggle turbulence/noise

R: Reset simulation

P: Pause / resume

S: Save screenshot to ./screenshots/

Esc / Q: Quit


(You can change keys in config.py.)


---

🚀 Getting Started

1. Clone

git clone https://github.com/yourusername/chromaflow-pygame.git
cd chromaflow-pygame


2. Install

pip install -r requirements.txt


Typical stack: pygame, numpy (and optionally numba for a speed boost).


3. Run

python main.py




---

⚙️ Configuration

Edit config.py to tune:

Resolution & scale (simulation grid vs. window size)

Viscosity / diffusion / timestep

Gravity strength & direction

Boundary mode (solid walls vs. wrap-around)

Color palettes & dye behavior



---

🧠 Under the Hood

Numerical Method: Semi-Lagrangian advection, Gauss–Seidel diffusion/pressure solve, incompressibility via Jacobi/Poisson iterations

Performance: Vectorized operations in NumPy; optional numba jit for hotspots

Rendering: Pygame surface blits with dye → RGB mapping + velocity overlays (optional)



---

🧪 Roadmap

Particle tracers and buoyant smoke

Save/load custom wall maps

Brush shapes (lines, circles, stencils)

Shader-based renderer (PyOpenGL)

Recording to GIF/MP4



---

📸 Gallery

(Drop GIFs or screenshots here once you have them)

/media/teaser-01.gif
/media/teaser-02.gif


---

📝 License

MIT — have fun, get curious, and please credit if you build on it.
If you share creations, tag the project so we can see your flows!
