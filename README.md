# WinFix-Toolbox
WinFixToolbox is a versatile batch script for repairing and optimizing Windows systems. It automates essential diagnostic and repair tasks to enhance system performance and reliability.

# WinFix-Toolbox

## Overview

**WinFix-Toolbox** is a comprehensive PowerShell script designed to diagnose, repair, and optimize Windows systems. This tool automates a variety of essential maintenance tasks, leveraging built-in Windows utilities to ensure your system runs smoothly and efficiently. Whether you encounter common issues or need to perform regular maintenance, WinFix-Toolbox simplifies the process, making it accessible even to those with minimal technical expertise.

## Features

- **System File Check and Repair:** Utilizes `sfc /scannow` to verify and repair corrupted system files.
- **Disk Check and Repair:** Executes `chkdsk` to find and fix disk errors.
- **Windows Update Reset:** Stops, restarts, and reconfigures Windows Update components to resolve update-related issues.
- **Network Reset:** Resets TCP/IP stack and clears DNS cache to solve connectivity problems.
- **Temporary Files Cleanup:** Runs Disk Cleanup utility to free up space by removing temporary files.
- **Advanced Diagnostics and Repairs:** Uses `DISM` to repair Windows images and additional commands to address more specific issues.
- **Restore Point Creation:** Creates a system restore point before making any changes.
- **Driver Updates:** Updates system drivers to the latest versions.
- **Uninstall Recent Programs:** Offers the option to uninstall programs installed in the last 30 days.
- **Disable Unnecessary Services:** Disables services that are not essential to improve system performance.
- **Monitor Resource Usage:** Provides a summary of processes consuming the most resources.

## How It Works

1. **Initial Setup:** The script starts by checking for administrative privileges and requesting them if necessary.
2. **Command Execution:** It systematically runs a series of commands to check and repair system files, perform disk checks, reset network settings, and clean up unnecessary files.
3. **User Interaction:** Minimal user interaction is required, making it easy to use. Follow the on-screen prompts and allow the script to complete its tasks.
4. **Reboot:** Some fixes may require a system reboot, which the script will prompt when necessary.

## Usage

1. **Download the Script:**
   - Clone the repository or download the script file to your Windows computer.
     ```sh
     git clone https://github.com/espinozan/WinFix-Toolbox.git
     ```
2. **Run as Administrator:**
   - Right-click on the script file and select "Run as administrator."
3. **Follow Prompts:**
   - Follow the on-screen instructions to initiate the repair processes.
4. **Restart if Required:**
   - Restart your computer when prompted to apply changes and complete repairs.

## Objective

The goal of WinFix-Toolbox is to provide a user-friendly tool for troubleshooting and maintaining Windows systems, reducing downtime and enhancing performance. This script is particularly useful for resolving common issues like system crashes, slow performance, network problems, and Windows Update failures.

You can use WinFix-Toolbox when you notice performance degradation, encounter errors that prevent normal operation, or as part of regular system maintenance to ensure your Windows environment remains stable and efficient.

By automating these tasks, WinFix-Toolbox aims to simplify Windows maintenance for users of all technical levels, providing a reliable and consistent approach to system care.

## Contributing

Contributions are welcome! Please fork this repository and submit pull requests with improvements, bug fixes, or new features. Ensure your code follows the existing style and includes appropriate comments.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or support, please open an issue on GitHub or contact [espinozan](https://github.com/espinozan).

---

*Note: Always ensure you have a backup of your important data before running repair scripts.*
