# Satellite Orbit Visualization

This project predicts satellite orbital paths using TLE (Two-Line Element) data and visualizes them in 3D, with Earth and Moon textures. It also generates CSV files with satellite position data over a time period.

---

## Features
- Predict satellite positions using TLE data.
- Visualize orbits in 3D with Earth and Moon textures.
- Save position data to a CSV file.
- Save images of the satellite's orbit and celestial bodies.

---

## Requirements
The following dependencies are required to run this project:
- Python 3.7 or higher
- Required Python packages (see `requirements.txt`).

---
##Respository Structure
```bash
satellite-orbit-visualization/
├── README.md
├── main.py
├── requirements.txt
├── data/
│   ├── last30.txt
├── textures/
│   ├── earth_texture.jpg
│   ├── moon_texture.jpg
├── output_images/
│   └── (Generated Images)
```

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/satellite-orbit-visualization.git
   cd satellite-orbit-visualization

2. Add TLE data:

Place your TLE data file (last30.txt) in the data/ directory.
Format should be:

```bash
Satellite Name
Line1 of TLE
Line2 of TLE
```

4.Add textures:

Place Earth and Moon texture images (earth_texture.jpg and moon_texture.jpg) in the textures/ directory.
Run the program:
```bash
python main.py
```
Input
TLE File: File containing satellite TLE data.
Example (last30.txt):
```bash
ISS (ZARYA)
1 25544U 98067A   21275.51861111  .00001431  00000-0  32273-4 0  9998
2 25544  51.6458 340.0053 0006231 132.5353 345.3695 15.48982581288011
```
Earth and Moon Texture Images: Provide high-quality images for Earth and Moon visualization.

##Output
Satellite Orbit Visualization: Saved in output_images/.
CSV File: satellite_orbit.csv with time-stamped positions of the satellite.

##Notes
Ensure the TLE data file is formatted correctly.
You can adjust visualization parameters in main.py.


##Example Run
Add the following TLE data to data/last30.txt:
```bash
ISS (ZARYA)
1 25544U 98067A   21275.51861111  .00001431  00000-0  32273-4 0  9998
2 25544  51.6458 340.0053 0006231 132.5353 345.3695 15.48982581288011
```
Place earth_texture.jpg and moon_texture.jpg in the textures/ directory.

Run the program:
```
python main.py
```
##Outputs:

Visualizations in output_images/.
Positions in satellite_orbit.csv.
License
This project is licensed under the MIT License.
```

### `requirements.txt`
```
numpy matplotlib sgp4 pandas

yaml

---

### `main.py`

Copy your code with necessary comments and place it in the root directory as `main.py`. Update the paths to match the repository structure:
- TLE file: `data/last30.txt`
- Textures: `textures/earth_texture.jpg`, `textures/moon_texture.jpg`

---

### Instructions

After setting up the repository structure, push it to GitHub:

```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/your-username/satellite-orbit-visualization.git
git branch -M main
git push -u origin main


---

### `main.py`

Copy your code with necessary comments and place it in the root directory as `main.py`. Update the paths to match the repository structure:
- TLE file: `data/last30.txt`
- Textures: `textures/earth_texture.jpg`, `textures/moon_texture.jpg`

---

### Instructions

After setting up the repository structure, push it to GitHub:

```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/your-username/satellite-orbit-visualization.git
git branch -M main
git push -u origin main
Replace https://github.com/your-username/satellite-orbit-visualization.git with your actual repository URL. Let me know if you need help updating your code for this structure!

