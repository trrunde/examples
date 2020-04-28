## pyATS Clean for NXOS N7K

This folder contains the following sample files:

- clean.yaml file for NXOS N7K platform
- testbed.yaml file for NXOS N7K platform

These files can be used as a template to execute a full end-to-end clean on an
NXOS N7K device. It performs the following steps in order:

- connects to NXOS N7K device
- (Optional) pings execution servers to verify connectivity
- (Optional) copies necessary images to intermediate server
- copies images to device
- changes boot variables
- executes 'write erase'
- reload device
- apply base configuration after reload
- verifies the running image matches what was specified

Please substitute your device IP addresses, credentials and image directories in
the templates provided before use.