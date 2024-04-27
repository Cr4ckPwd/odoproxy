
## Uploading and Restoring Proxmox Backup File

1. **Upload Backup File:**
   - Navigate to the Proxmox web interface.
   - Log in using your credentials.
   - Go to the desired storage location where you want to upload the backup file.
   - Click on the "Upload" button and select the `vzdump-qemu-101-2024_01_06-16_54_33.vma.zst` file from your local system.
   - Wait for the upload to complete.

2. **Restore Backup File:**
   - After the upload is finished, navigate to the "Backup" section of the Proxmox interface.
   - Locate the uploaded backup file `vzdump-qemu-101-2024_01_06-16_54_33.vma.zst`.
   - Click on the backup file to select it.
   - Choose the appropriate restore options, such as target node and storage.
   - Start the restore process and wait for it to complete.


# Network Setup

This document outlines the network configuration for a system using the following parameters:

- **Network**: 192.168.40.0/24
- **Gateway**: 192.168.40.1
- **Proxy Server IP**: 192.168.40.225

## Post-Restore Setup

After restoring the system, proceed with the following configuration steps:

### Proxy Server Interface Setup

Configure the proxy server interfaces as follows:

- **Interface Ether1**: Connects to the local network above.
- **Interface Ether 2 to Interface Ether 5**: Connects to the Viettel bridge network.
### USB Interface Setup

Connect all your Dcom devices to the USB interface for seamless integration.



## Proxy Server Access

### WAN Proxy Manager
To access the WAN Proxy Manager, use the following URL: http://192.168.40.225:6868

### Dcom Proxy Manager
To access the Dcom Proxy Manager, use the following URL: http://192.168.40.225:6969

<img width="312" alt="image" src="https://github.com/Cr4ckPwd/odoproxy/assets/84202581/5fb92405-9cec-4475-aa42-ab1c434412e8">

