# Communicating with Devices via WirelessHART Network Connection - Run 4

Using the [Fieldcare](../../../fieldcare/fieldcare.md) package on the workstation to communicate with [WirelessHART](../../../indexes/index_devices_hart.md) devices installed on [Run 4](../../../flow_runs/run_4.md)

Create Project

{{../../files/generic_images/create_project_cropped_generic.bmp?width=300}}

In the Network pane right click //Host PC// & select __Add Device__
{{../../files/generic_images/right_click_add_device_cropped_generic.bmp}}


Add //HART IP Communication//
{{../../files/generic_images/add_hart_ip_comm_cropped.bmp?width=500}}


In the Network pane right click //HART IP Communication// & select //Add Device//

{{../../files/generic_images/right_click_add_device_2_cropped_generic.bmp}}


Select WirelessHART Fieldgate / SWG70 / V1.xx click OK
{{.\add_wireleshart_swg70_cropped.bmp?width=600}}


Right click //HART IP Communication// & select //Additional Functions - Set DTM Addresses//
{{.\right_click_set_dtm_addresses_cropped.bmp?height=400}}

Enter __192.168.1.45__ in the //UDP Address// field - Click Update changed data
{{.\192_168_1_45_update_changed_data_cropped.bmp?width=800}}


In the Network pane right click WirelessHART Fieldgate & select// Create network//
{{../../files/generic_images/right_click_create_network_dialog_only_generic.bmp}}


Wait for the Scanning to complete


The found wireless gateways devices will appear in the //Network// pane
{{.\network_run_4_wireless_gateways_cropped.bmp}}
Right click on the required [[WirelessHART]] adaptor and select //Create network//
FITWL404 to connect to [[Devices:FIT-404|FIT-404]]
PITWL411 to connect to [[Devices:PIT-411|PIT-411]]
PITWL410 to connect to [[Devices:PIT-410|PIT-410]]
{{.\right_click_wireless_gateways_create_network_cropped.bmp?height=400}}
The end device will appear under the wireless gateway

{{.\network_run_4_wireless_end_device_cropped.bmp}}

To connect to the required device, In the //Network pane// right click on the required device and select //Connect//

The Connection icon will turn from grey to green when connected

Disconnected	Connected
{{../../files/generic_images/connection_disconnected_grey_generic.bmp?width=50}}		{{../../files/generic_images/connection_connected_double_green_generic.bmp?width=50}}


Double click on the green connection icon

*Online Parameterize*will now appear in the DTM frame

{{../../files/generic_images/online_parameterize_cropped_generic.bmp?width=500}}




























Right click the wirelss xxx Creat Network


To connect to the required device, In the //Network pane// right click on the required device and select //Connect **blur out different run ***//
{{.\right_click_connect.bmp?width=800}}

The Connection icon will turn from grey to green when connected
{{.\green_connection_icon_cropped.bmp?width=250}}

//Online Parameterize //will now appear in the DTM frame
{{.\online_parameterize_cropped.bmp?width=800}}


webpage
admin
admin
