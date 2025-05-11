# EXR_multipass

A simple Blender add-on to easily create and manage EXR multipass outputs for compositing.


**Download last release:**

[![Download](https://img.shields.io/badge/Download-EXR_multipass-ff69b4?style=for-the-badge)](https://github.com/KoyomiRei/EXR_multipass/releases/latest)




## Features

- Automatically creates a Render Layers and File Output node setup configured for exporting multilayer EXR files
- Prevents duplicate nodes (if a node created by the add-on already exists, the viewport focuses on it instead)
- Adds a "Refresh" button to reconnect passes without recreating the node
- Standardizes pass names to more widely accepted naming conventions
- Optimized for clean and fast EXR export for post-production

## Installation

1. Download the latest release (.zip).
2. In Blender, go to `Edit` → `Preferences` → `Add-ons` → `Install`.
3. Select the downloaded `.zip` file.
4. Enable the add-on in the list.

## Usage

- Open Blender and go to the **Compositing** tab.
- In the sidebar ("N" key), find the "EXR Multipass" panel.
- Click "Create EXR Multipass" to generate the Render Layers and File Output node setup.
- Use the "Refresh" button if you add or change render passes.

## License

This project is licensed under the [GPL-3.0 License](https://www.gnu.org/licenses/gpl-3.0.en.html).
