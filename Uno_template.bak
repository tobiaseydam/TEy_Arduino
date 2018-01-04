EESchema Schematic File Version 2
LIBS:power
LIBS:device
LIBS:switches
LIBS:relays
LIBS:motors
LIBS:transistors
LIBS:conn
LIBS:linear
LIBS:regul
LIBS:74xx
LIBS:cmos4000
LIBS:adc-dac
LIBS:memory
LIBS:xilinx
LIBS:microcontrollers
LIBS:dsp
LIBS:microchip
LIBS:analog_switches
LIBS:motorola
LIBS:texas
LIBS:intel
LIBS:audio
LIBS:interface
LIBS:digital-audio
LIBS:philips
LIBS:display
LIBS:cypress
LIBS:siliconi
LIBS:opto
LIBS:atmel
LIBS:contrib
LIBS:valves
LIBS:Uno_template-cache
EELAYER 25 0
EELAYER END
$Descr A4 11693 8268
encoding utf-8
Sheet 1 1
Title ""
Date ""
Rev ""
Comp ""
Comment1 ""
Comment2 ""
Comment3 ""
Comment4 ""
$EndDescr
$Comp
L Conn_01x08 J1
U 1 1 5A4D3F50
P 7350 1250
F 0 "J1" H 7350 1650 50  0000 C CNN
F 1 "POWER" H 7350 750 50  0000 C CNN
F 2 "Pin_Headers:Pin_Header_Straight_1x08_Pitch2.54mm" H 7350 1250 50  0001 C CNN
F 3 "" H 7350 1250 50  0001 C CNN
	1    7350 1250
	-1   0    0    -1  
$EndComp
Text Notes 6750 1650 0    60   ~ 0
1 = N.C.\n2 = IOREF\n3 = RESET\n4 = 3.3V\n5 = 5V\n6 = GND\n7 = GND\n8 = Vin
$Comp
L Conn_01x06 J2
U 1 1 5A4D408D
P 7350 2350
F 0 "J2" H 7350 2650 50  0000 C CNN
F 1 "ANALOG IN" H 7350 1950 50  0000 C CNN
F 2 "Pin_Headers:Pin_Header_Straight_1x06_Pitch2.54mm" H 7350 2350 50  0001 C CNN
F 3 "" H 7350 2350 50  0001 C CNN
	1    7350 2350
	-1   0    0    -1  
$EndComp
Text Notes 6750 2650 0    60   ~ 0
1 = A0\n2 = A1\n3 = A2\n4 = A3\n5 = A4\n6 = A5
$Comp
L Conn_01x08 J4
U 1 1 5A4D413D
P 9850 2350
F 0 "J4" H 9850 1850 50  0000 C CNN
F 1 "IOL" H 9850 2750 50  0000 C CNN
F 2 "Pin_Headers:Pin_Header_Straight_1x08_Pitch2.54mm" H 9850 2350 50  0001 C CNN
F 3 "" H 9850 2350 50  0001 C CNN
	1    9850 2350
	1    0    0    1   
$EndComp
$Comp
L Conn_01x10 J3
U 1 1 5A4D4192
P 9850 1250
F 0 "J3" H 9850 650 50  0000 C CNN
F 1 "IOH" H 9850 1750 50  0000 C CNN
F 2 "Pin_Headers:Pin_Header_Straight_1x10_Pitch2.54mm" H 9850 1250 50  0001 C CNN
F 3 "" H 9850 1250 50  0001 C CNN
	1    9850 1250
	1    0    0    1   
$EndComp
Text Notes 10000 2650 0    60   ~ 0
 8 = IO7\n 7 = IO6 (PWM)\n 6 = IO5 (PWM)\n 5 = IO4\n 4 = IO3 (PWM)\n 3 = IO2\n 2 = IO1/TX\n 1 = IO0/RX
Text Notes 10000 1650 0    60   ~ 0
10 = SCL\n 9 = SDA\n 8 = AREF\n 7 = GND\n 6 = IO13 (SCK)\n 5 = IO12 (MISO)\n 4 = IO11 (MOSI, PWM)\n 3 = IO10 (SS, PWM)\n 2 = IO9 (PWM)\n 1 = IO8
Text Label 8150 1050 2    60   ~ 0
IOREF
Text Label 8150 1150 2    60   ~ 0
RESET
Text Label 8150 1250 2    60   ~ 0
3V3
Text Label 8150 1350 2    60   ~ 0
5V
Text Label 8150 1450 2    60   ~ 0
GND
Text Label 8150 1650 2    60   ~ 0
Vin
$Comp
L +3V3 #PWR01
U 1 1 5A4D447E
P 8300 1150
F 0 "#PWR01" H 8300 1000 50  0001 C CNN
F 1 "+3V3" H 8300 1290 50  0000 C CNN
F 2 "" H 8300 1150 50  0001 C CNN
F 3 "" H 8300 1150 50  0001 C CNN
	1    8300 1150
	1    0    0    -1  
$EndComp
$Comp
L +5V #PWR02
U 1 1 5A4D449A
P 8450 1250
F 0 "#PWR02" H 8450 1100 50  0001 C CNN
F 1 "+5V" H 8450 1390 50  0000 C CNN
F 2 "" H 8450 1250 50  0001 C CNN
F 3 "" H 8450 1250 50  0001 C CNN
	1    8450 1250
	1    0    0    -1  
$EndComp
$Comp
L GND #PWR03
U 1 1 5A4D44D1
P 8300 1650
F 0 "#PWR03" H 8300 1400 50  0001 C CNN
F 1 "GND" H 8300 1500 50  0000 C CNN
F 2 "" H 8300 1650 50  0001 C CNN
F 3 "" H 8300 1650 50  0001 C CNN
	1    8300 1650
	1    0    0    -1  
$EndComp
Wire Wire Line
	7550 1050 8150 1050
Wire Wire Line
	7550 1150 8150 1150
Wire Wire Line
	7550 1250 8300 1250
Wire Wire Line
	7550 1350 8450 1350
Wire Wire Line
	7550 1450 8300 1450
Wire Wire Line
	7550 1550 8300 1550
Wire Wire Line
	7550 1650 8150 1650
Wire Wire Line
	8300 1250 8300 1150
Wire Wire Line
	8450 1350 8450 1250
Wire Wire Line
	8300 1450 8300 1650
Connection ~ 8300 1550
Wire Wire Line
	7550 2150 8150 2150
Wire Wire Line
	7550 2250 8150 2250
Wire Wire Line
	7550 2350 8150 2350
Wire Wire Line
	7550 2450 8150 2450
Wire Wire Line
	7550 2550 8150 2550
Wire Wire Line
	7550 2650 8150 2650
Text Label 8150 2150 2    60   ~ 0
A0
Text Label 8150 2250 2    60   ~ 0
A1
Text Label 8150 2350 2    60   ~ 0
A2
Text Label 8150 2450 2    60   ~ 0
A3
Text Label 8150 2550 2    60   ~ 0
A4
Text Label 8150 2650 2    60   ~ 0
A5
Wire Wire Line
	9050 1550 9650 1550
Wire Wire Line
	9650 1650 9050 1650
Wire Wire Line
	9650 1450 9050 1450
Wire Wire Line
	9650 1350 9050 1350
Wire Wire Line
	9650 1250 9050 1250
Wire Wire Line
	9650 1150 9050 1150
Wire Wire Line
	8900 1050 9650 1050
Wire Wire Line
	9650 950  9050 950 
Wire Wire Line
	9650 850  9050 850 
Wire Wire Line
	9650 750  9050 750 
Wire Wire Line
	9650 1950 9050 1950
Wire Wire Line
	9650 2050 9050 2050
Wire Wire Line
	9650 2150 9050 2150
Wire Wire Line
	9650 2250 9050 2250
Wire Wire Line
	9650 2350 9050 2350
Wire Wire Line
	9650 2450 9050 2450
Wire Wire Line
	9650 2550 9050 2550
Wire Wire Line
	9650 2650 9050 2650
Text Label 9050 750  0    60   ~ 0
A5
Text Label 9050 850  0    60   ~ 0
A4
Text Label 9050 950  0    60   ~ 0
AREF
Text Label 9050 1050 0    60   ~ 0
GND
Text Label 9050 1150 0    60   ~ 0
SCK
Text Label 9050 1250 0    60   ~ 0
MISO
Text Label 9050 1350 0    60   ~ 0
MOSI
Text Label 9050 1450 0    60   ~ 0
SS
Text Label 9050 1550 0    60   ~ 0
IO9
Text Label 9050 1650 0    60   ~ 0
IO8
Text Label 9050 1950 0    60   ~ 0
IO7
Text Label 9050 2050 0    60   ~ 0
IO6
Text Label 9050 2150 0    60   ~ 0
IO5
Text Label 9050 2250 0    60   ~ 0
IO4
Text Label 9050 2350 0    60   ~ 0
IO3
Text Label 9050 2450 0    60   ~ 0
IO2
Text Label 9050 2550 0    60   ~ 0
TX
Text Label 9050 2650 0    60   ~ 0
RX
$Comp
L GND #PWR04
U 1 1 5A4D49BF
P 8900 1150
F 0 "#PWR04" H 8900 900 50  0001 C CNN
F 1 "GND" H 8900 1000 50  0000 C CNN
F 2 "" H 8900 1150 50  0001 C CNN
F 3 "" H 8900 1150 50  0001 C CNN
	1    8900 1150
	1    0    0    -1  
$EndComp
Wire Wire Line
	8900 1050 8900 1150
Text Notes 7450 6950 0    197  ~ 0
Heizungssteuerung
$EndSCHEMATC
