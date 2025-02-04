# NeoEngine

## Overview

NeoEngine is a Python-based utility designed to perform a deep clean of the Windows registry by removing unused and old entries. This aims to enhance system performance by eliminating clutter and outdated data that may slow down your system.

## Features

- **Backup Registry**: Before performing any cleaning operations, NeoEngine creates a backup of the registry keys to ensure that any changes can be reverted safely.
- **Deep Clean**: Automatically identifies and removes registry keys that are deemed unnecessary or outdated.
- **Support for Multiple Hives**: Cleans keys across the major registry hives, including:
  - HKEY_CLASSES_ROOT
  - HKEY_CURRENT_USER
  - HKEY_LOCAL_MACHINE
  - HKEY_USERS
  - HKEY_CURRENT_CONFIG

## Usage

1. **Installation**: Ensure Python is installed on your Windows machine.
2. **Running NeoEngine**:
   - Open a command prompt with administrative privileges.
   - Run the script by executing `python neoengine.py`.
   - The script will first back up the registry and then proceed to clean it.

## Important Notes

- **Caution**: Modifying the Windows registry can have serious consequences if done incorrectly. Ensure you have backups and understand what keys are being modified.
- **Placeholder Logic**: The current implementation uses placeholder logic for determining if a key is unused. This needs to be implemented with actual conditions based on your specific requirements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Disclaimer

NeoEngine is provided "as-is" without any warranties. Use at your own risk. The author is not responsible for any damage caused by using this software.