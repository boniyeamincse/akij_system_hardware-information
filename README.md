# AKIJ System Hardware Information Tool

## Overview

This PowerShell script generates a detailed HTML report of system hardware information. It collects comprehensive hardware information from the system, including:

- System overview and identifiers
- BIOS and serial numbers
- Motherboard details
- Processor information
- Memory (RAM) specifications
- Storage devices
- Graphics adapters

The information is formatted into a styled HTML report for easy viewing.

## Prerequisites

- PowerShell 3.0 or later

## Usage

1. Download the `akijinfo.ps1` script.
2. Open a PowerShell terminal.
3. Navigate to the directory where the script is located.
4. Run the script using the following command:

    ```powershell
    .\akijinfo.ps1
    ```

5. The script will generate an HTML report in the current directory with a filename in the format `AkijSystemInfo_<computer_name>_<timestamp>.html`.

## Example

To run the script and generate an HTML report, use the following command:

```powershell
.\akijinfo.ps1
```
# Version Information

## Current Version
**v1.0.0**
## Notes

- Ensure you have the required permissions to execute PowerShell scripts on your system.
- The report file will be saved in the same directory where the script is executed.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

- Boni Yeamin
