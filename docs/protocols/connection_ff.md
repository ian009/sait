# Communicating with Foundation Fieldbus Devices
# Run 2

Using the [Fieldcare](../fieldcare/fieldcare.md) package on the workstation to communicate with [Foundation Fieldbus](../indexes/index_devices_ff.md) devices installed on [Run 2](../flow_runs/run_2.md)

Create Project

![](../images/generic_images/create_project.bmp)

In the Network pane right click *Host PC* & select *Add Device*

![](../images/generic_images/right_click_add_device.bmp)

Add *1757-FFLD4*

![](../images/generic_images/add_1757-FFLD4.png)

In the Network pane right click *1757-FFLD4 - Device Functions - Configuration*

![](../images/generic_images/right_click_device_functions_configuration_cropped_generic.bmp)

In the DTM frame click *AB_FFLD* in the HSE Live List - It may take a few seconds for the HSE Live List to populate

![](../images/generic_images/click_ABB_FFLD.bmp)

The status should now turn green & indicate *Comm DTM assigned*

In the Network pane right click *1757-FFLD4 - Create network*

![](../images/generic_images/right_click_create_network_dialog_only_generic.bmp)


Press OK to scan all 4 channels

![](../images/generic_images/select_communication_channel_ff.png)


Wait for the Scanning to complete

To connect to the required device, In the *Network pane* right click on the required device and select *Connect*


![](../images/generic_images/right_click_network_connect_generic.bmp)

The Connection icon will turn from grey to green when connected

Disconnected	Connected

![](../images/generic_images/connection_disconnected_grey_generic.bmp)
![](../images/generic_images/connection_connected_double_green_generic.bmp)


Double click on the green connection icon

*Online Parameterize* will now appear in the DTM frame

![](../images/generic_images/online_parameterize_cropped_generic.bmp)
