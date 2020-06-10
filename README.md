# rak2247_usb_for_ubuntu

##	Introduction 

The aim of this project is to help users set up a LoRa network easily. 

We tested on ubuntu16 and ubuntu18 and successfully installed and ran.

make sure the mini-pcie PERST# signal(pin 22) pulled down (default high will cause rak833 function error like "ERROR: Failed to load fw 1").

The default gateway_id is set to "0102030405060708", you can modify it in the /opt/ttn-gateway/packet_forwarder/lora_pkt_fwd/local_conf.json file.
