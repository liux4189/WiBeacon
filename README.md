WiBeacon is a tool to repurpose already deployed WiFi infrastructures to be virtual BLE beacons. By software upgrades on existing WiFi access
points (AP), they can broadcast BLE location identifiers to mobile devices.

prerequisite:
Openwrt compliant WiFi router with Qualcomm, Atheros, Broadcom, MediaTek chipset.
We have verified WiBeacon on GL-AR750, GL-AR150, Linksys-E2000, Netgear-A6210. 

What are included?
ipk: The compile WiBeacon ipk and patched WiFi driver. 
image: OpenWRT images. (OpenWRT version must match the patched WiFi driver we provided).
src:  The src for generating WiFi packet for iBeacon broadcast. 
