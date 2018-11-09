# GetVMwareLANSegment

A VMware LAN Segment PowerShell cmdlet for VMware Workstation Pro (Windows).

## Usage

Returns each of the VMWare LAN Segments as a custom object.

    Get-VMwareLANSegment

In addition to the default output, this will display the total number of VMware LAN Segments.

    Get-VMwareLANSegment -Verbose

This will return a specific VMWare LAN Segment object with the value 'link005' for the Name property.

    Get-VMwareLANSegment | where Name -eq 'link005'

## Reference

   - [LAN Segments for VMware Workstation Pro on Windows](https://binarynature.blogspot.com/2018/02/lan-segments-vmware-workstation-windows.html)
   - [Configuring LAN Segments](https://docs.vmware.com/en/VMware-Workstation-Pro/15.0/com.vmware.ws.using.doc/GUID-DEE1E2F1-5DA4-4C83-B7C5-A1165C84C757.html)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
