# PowerApps PCF Controls

This repository contains custom PowerApps PCF (PowerApps Component Framework) controls packaged as a solution for Microsoft Power Platform / Dynamics 365.

## Solution Overview

- **Solution Name:** PowerApps_PCF_Controls
- **Type:** Both Managed and Unmanaged (see `src/Other/Solution.xml`)
- **Customization Prefix:** papcf

## Project Structure

- `src/Other/` — Contains solution XML files (customizations, relationships, solution manifest)
- `bin/Debug/` — Contains the built solution package (ZIP file)

## List of controls

- TreeView
- Encrypted Textbox
- Decrypted Textbox

## How to Find the Solution Package

After building the project, the solution ZIP file can be found at:

```
bin/Debug/PowerApps_PCF_Controls.zip
```

This file can be imported into your Power Platform environment.

## Getting Started

1. Clone this repository.
2. Build the solution using your preferred tools.
3. Import the ZIP file from `bin/Debug/PowerApps_PCF_Controls.zip` into your Power Platform environment.

## License

Specify your license here.

## Author

Arpit Shah
