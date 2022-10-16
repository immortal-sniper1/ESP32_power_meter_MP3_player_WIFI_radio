# PCB_test_project_01
 First ESP32 pcb project, it will have power meters( 24V 3A, 5V 0.5A, and self consumption), uSD card, WIFI/BT and the ability to play back MP3/audio file.     
 Also it will feature a power usage meter. It can also be powered from a 18650 Li ion cell, if the USB is alsoo pluged in the cell will start chargeing.
 The chargeing current is limited by the chargeing IC useing a potenciometer as the input. If the red LED is on then the cell is cahrgeing and if the green
 LED is on then the cell is fully charged.
 NOTE: the voltage levels are set by the ICs and it is : 4.2V as charged state and 3V as discharged.
 If the cel voltage reaches 3V or lower then a circuit will activate and disconect the cell from the system so that it will not overdischarge.
