# Communicating with Devices via HART Network Connection - Run 3

Using the [Fieldcare](../../../fieldcare/fieldcare.md) package on the workstation to communicate with [HART](../../../indexes/index_devices_hart.md) devices installed on [Run 3](../../../flow_runs/run_3.md)

Create Project

![](../../../images/generic_images/create_project.bmp)

In the Network pane right click *Host PC* & select *Add Device*

![](../../../images/generic_images/right_click_add_device.bmp)


Add *RSLinx 1756 Backplane*
![](../../../images/generic_images/add_rslinx_1756_backplane_cropped_generic.bmp)


In the Network pane right click *RSLinx 1756 Backplane - Device Functions - Configuration*
![](../../../images/generic_images/right_click_device_functions_configuration_cropped_generic.bmp)

Click *Select Path* & drill down

	AB_ETHIP-1,Ethernet
	192.168.1.31, 1756-EN2T, 1756-EN2T/C
	Backplane,1756-A7/A
	05, 1756-IF16H/A, 1756-IF16H/A HART Analog In

![](../../../images/run3_drill_1756.bmp)

Press OK

In the Network pane right click *RSLinx 1756 Backplane* & select *Add Device*
![](../../../images/generic_images/right_click_add_device_2_cropped_generic.bmp)

Select *1756-IF16H*
![](../../../images/generic_images/add_1756-IF16H_cropped_generic.bmp)

Select- *Slot Number 5* click OK

![](../../../images/generic_images/slot_5_cropped.bmp)

In the Network pane right click *1756-IF16H * *- Create network*

![](../../../images/generic_images/right_click_create_network_dialog_only_generic.bmp)

Press OK in the Select Communication dialog box

![](../../../images/generic_images/hartch_ok_cropped.bmp)


Wait for the Scanning to complete

To connect to the required device, In the *Network pane* right click on the required device and select *Connect*


![](../../../images/generic_images/right_click_network_connect_generic.bmp)

The Connection icon will turn from grey to green when connected

Disconnected	Connected

![](../../../images/generic_images/connection_disconnected_grey_generic.bmp)
![](../../../images/generic_images/connection_connected_double_green_generic.bmp)


Double click on the green connection icon

*Online Parameterize* will now appear in the DTM frame

![](../../../images/generic_images/online_parameterize_cropped_generic.bmp)
