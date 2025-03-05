# Cricket Field Interactive UI

This project creates an interactive cricket field using Konva.js, allowing users to add, drag, and rename players while enforcing movement constraints and player limits.

## Features
- **Interactive Player Placement:** Users can click on the field to add players dynamically.
- **Draggable Players:** Players can be repositioned using drag-and-drop functionality.
- **Editable Player Names:** Double-clicking a player's label opens a text box to rename them.
- **Movement Constraints:** Players have restricted movement areas to ensure realistic positioning.
- **Player Limits:** Users can add up to 11 players to maintain proper team structure.
- **Background Field Image:** A cricket field image is used as the background for a realistic experience.

## Technologies Used
- **Konva.js** – Handles rendering and interactive graphics.
- **jQuery** – Manages event handling for click and drag operations.
- **jQuery Touch Events** – Enhances touch support for mobile devices.

## How to Use
1. Open `index.html` in a browser.
2. Click on the field to add blue players (up to 11).
3. Drag players to reposition them within the allowed boundaries.
4. Double-click a player's label to edit their name.
5. Enjoy customizing your interactive cricket field!

## File Structure
- `index.html` – Main file containing the cricket field and interactive logic.
- `img/blankField.png` – Background image of the cricket field.
- External libraries: Konva.js, jQuery, jQuery Touch Events (loaded via CDN).

## Future Enhancements
- Add different player types with unique colors and roles.
- Implement a save/load feature to preserve player positions.
- Improve touch interactions for a smoother mobile experience.
- Introduce team management options (e.g., removing players, reassigning roles).

## Dependencies
- Konva.js
- jQuery
- jQuery Touch Events

