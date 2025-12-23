# Blender 3D Printing Notes

How to use Blender for 3D printing: settings, optional plugins and some helpful shortcuts.


# Blender 3D Print Settings

These settings will ensure that measurements are compatible with your favorite slicer (e.g. PrusaSlicer) when exporting to STL (File → Export → STL).

Note that in Blender you can export a single selected object, multiple selected objects, or all objects at once into a single STL file.

## These changes will set measuing units to millimeters and adjust the UI to display them correctly:

<img width="250" height="412" alt="o~ Scene" src="https://github.com/user-attachments/assets/f74fb0c4-865a-4ff1-9393-45148b9c5b25" /><br />

<img width="350" height="210" alt="Focal Length" src="https://github.com/user-attachments/assets/f4482109-e128-4d2b-b692-47b4dd58eb78" /><br />

<img width="299" height="204" alt="Viewport Overlays" src="https://github.com/user-attachments/assets/c6fe3872-5936-4f5f-b830-afe4b763bd2a" /><br />
⬇<br />
(This is optional but helps to see if any faces are flipped by accident.)<br />
<img width="295" height="88" alt="Geometry" src="https://github.com/user-attachments/assets/52870d25-036d-4a59-a431-4e942aad8fde" /><br />

## Snap to grid helps making precise changes:

<img width="215" height="275" alt="Snap Base" src="https://github.com/user-attachments/assets/f82447d0-96e3-4b58-912a-77b65d7d6b5f" /><br />

## Save the settings as startup default:

<img width="387" height="183" alt="J  Import" src="https://github.com/user-attachments/assets/2f678b7d-f696-4eab-9563-e3c43b7a3276" /><br />


# Optional Plugins and Settings:

Edit → Preferences → Get Extensions:

<img width="295" height="100" alt="v Installed" src="https://github.com/user-attachments/assets/69816299-1cf2-476f-8e85-8a4fc4eeb04a" />

Edit → Preferences → System:

<img width="562" height="100" alt="v Memory   Limits" src="https://github.com/user-attachments/assets/da9ee530-992d-4b81-8bf2-ae5643c923d6" />


# Useful Keyboard Shortcuts etc.

| Common | |
|--------|-|
| G                    | Grab (Move) |
| R                    | Rotate |
| S                    | Scale |
| X                    | Delete |
| Ctrl+Z               | Undo |
| Shift+Ctrl+Z         | Redo |
| Shift+Z              | Switch between Viewport Shading (Wireframe, Solid) |
| T                    | Toggle Toolbar |
| N                    | Toggle Sidebar |

| Edit Mode | |
|-----------|-|
| Ctrl+B               | Bevel Edges |
| Ctrl+R               | Loop Cut |
| Shift+Tab            | Toggle Snap |
| E                    | Extrude |
| F                    | Fill |
| 1, 2, 3              | Select Mode: Vertex, Edge, Face |
| V                    | Set Handle Type (Curves) |
| M → By Distance      | Merge Vertices |
| Alt+N                | Flip Normals (Faces) |
| *N/A* | Select → Select All by Trait → Non Manifold |

| Object Mode | |
|-------------|-|
| Shift+D              | Duplicate Object |
| Ctrl+J               | Join |
| Ctrl+A               | Apply Scale, Rotation, ... |
| *N/A* | Object → Set Origin → Origin to Geometry |
