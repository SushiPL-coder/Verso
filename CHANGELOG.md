# Changelog

All notable changes to this project are documented here.
This project adheres to a simple, human-readable changelog.

## [0.5.0] - 2026
### Added
- Resize from all 8 handles (corners + edges) — shrink and grow from any side,
  not just bottom-right. Aspect lock applies on corner handles.
- Copy / paste / duplicate elements: `Ctrl+C` / `Ctrl+V` / `Ctrl+D`, plus a Duplicate button.
- Keyboard shortcuts now work whether focus is on the canvas or inside the preview.

## [0.4.0] - 2026
### Added
- Undo / redo with toolbar buttons and `Ctrl+Z` / `Ctrl+Shift+Z` (`Ctrl+Y`).
- New brand logo and repository banner.

## [0.3.0] - 2026
### Added
- Drag & drop for `.html` files and images/videos onto the canvas.
- Drop an image directly onto an existing `<img>` to swap its source (code keeps the filename).
- Expanded element editing: font family, weight, italic, alignment, line-height,
  letter-spacing, text color, background, border width/style/color, corner radius,
  opacity, padding, margin.
- On-canvas handles: corner grip to resize (aspect lock), circle handle to rotate.

### Fixed
- Image/element **resize** now works (handles get parent-side pointer handling).
- **Zoom** now scales the page inside the frame, not just the frame box.
- Rotation is discoverable via an on-canvas handle.
- Cross-document computed-style reads use the iframe's own window.

## [0.2.0] - 2026
### Added
- Open file / Download file workflow.
- Zoom controls and collapsible side panel.
- Named asset slots (e.g. `hero.mp4`) with upload-backed previews and clean filenames on export.
- Initial resize and rotate controls.

## [0.1.0] - 2026
### Added
- First working version: paste HTML/CSS, live iframe preview, click-select,
  drag-to-move, color/size editing, in-place text editing, and code round-trip.
