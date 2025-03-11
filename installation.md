# Installation

Follow these steps to install Beb Tools in Blender 4.2.

## Prerequisites
- Blender 4.2 or later.
- Internet access (for GitHub imports).

## Steps
1. **Download the Add-on**:
   - Clone or download the `beb_tools` repository from [GitHub](#) (replace with your repo URL).
   - The folder structure should look like:
     ```
     beb_tools/
       __init__.py
       lib/         # Bundled dependencies (requests, etc.)
       modules/     # Core scripts
       scripts/     # Where imported scripts go
     ```

2. **Install in Blender**:
   - Open Blender 4.2.
   - Go to `Edit > Preferences > Add-ons`.
   - Click `Install`, select the `beb_tools` folder as a `.zip` (or the folder directly if unzipped), and click `Install Add-on`.
   - Enable the add-on by checking the box next to "Beb Tools".

3. **Verify Installation**:
   - In the 3D Viewport, press `N` to open the sidebar.
   - Look for the "Beb.Tools" tab.

## Notes
- The `lib/` folder includes the `requests` library, so no external installation is needed.
- Ensure Blender has write permissions to the `scripts/` folder.

See [Troubleshooting](#troubleshooting) if you encounter issues.