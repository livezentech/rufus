Rufus now creates USB media to bypass Windows 11 requirements during an in-place upgrade and clean installation.

On Rufus version 3.18 (beta) and higher, you can use the “Extended” option to create a Windows 11 bootable USB that bypasses the TPM 2.0, Secure Boot, and memory requirements on unsupported hardware.


Although you can use the Media Creation Tool, Rufus makes it easier to create a USB flash drive to install Windows 11 since you can provide an existing ISO file or you can use the option to download the files directly from Microsoft. Furthermore, the tool now includes a new “Extended Windows 11 Installation (no TPM / no Secure Boot)” to bypass the system requirements during a clean install and in-place upgrade.

This guide will teach you the steps to use Rufus to create bootable media to install Windows 11.


Create Windows 11 bootable USB with requirement bypass 
To create a Windows 11 bootable USB to bypass system requirements, use these steps:

- Open Rufus 3.18 website.
- Click the link to download the latest version.
- Double-click the rufus.3.18.exe file to launch the tool.
- Under the “Device” section, use the drop-down menu and select the flash drive to create the Windows 11 bootable USB media.
- Under the “Boot selection” section, use the drop-down menu and select the Disk or ISO image option.
- Click the Select button.
- Select the Windows 11 ISO file.
- Click the Open button.
- Under the “Image option” section, select the Extended Windows 11 Installation (no TPM/no Secure Boot/8GB – RAM) option.
