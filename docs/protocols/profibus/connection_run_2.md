# Communicating with Profibus Devices
# Run 2

Using the [Fieldcare](../../fieldcare/fieldcare.md) package on the workstation to communicate with [Profibus](../../indexes/index_devices_profibus.md) devices installed on [Run 2](../../flow_runs/run_2.md)

Create Project

![](../../images/generic_images/create_project.bmp)

In the Network pane right click *Host PC* & select *Add Device*

![](../../images/generic_images/right_click_add_device.bmp)


Select *HS Ethernet/IP*
![](../../images/generic_images/add_hs_ethernet_ip_cropped_generic.bmp)

In the Network pane right click *HS Ethernet/IP* & select **Add Device**

![](../../images/generic_images/right_click_add_device_2_cropped_generic.bmp)

Select **1788-EN2PAR**
![](../../images/generic_images/add_1788-EN2PAR_cropped_generic.bmp)

In the Network pane right click **R1788-EN2PAR** & select Device Functions - Configuration
![](../../images/generic_images/right_click_device_functions_configuration_cropped_generic.bmp)

Enter *Module IP Address* **192.168.1.23**

Press Enter - Ensure green check mark is displayed

Enter *Max Scan Address* **126**

Press Enter - Ensure green check mark is displayed
![](../../images/run2_192_168_1_23_126_green.bmp)

In the Network pane right click **1788-EN2PAR - Create network**

![](../../images/generic_images/right_click_create_network_dialog_only_generic.bmp)

Wait for the Scanning to complete

To connect to the required device, In the *Network pane* right click on the required device and select *Connect*


![](../../images/generic_images/right_click_network_connect_generic.bmp)

The Connection icon will turn from grey to green when connected

Disconnected	Connected

![](../../images/generic_images/connection_disconnected_grey_generic.bmp)
![](../../images/generic_images/connection_connected_double_green_generic.bmp)


Double click on the green connection icon

*Online Parameterize* will now appear in the DTM frame

![](../../images/generic_images/online_parameterize_cropped_generic.bmp)
