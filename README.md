# TrafficGenerator
B32 Traffic Generator

Studio scripts:
Top section (click to call): 
ChimericalCorporation\Extension\ChimericalClickToCall

Middle and bottom secctions (vertical call and custom call):  
Initial script: ChimericalCorporation\Extension\ASUMRTIG\ASUMRTIG_ClickToCall
	Above script does a runsub (could be combined into a single script) to ChimericalCorporation\Extension\ASUMRTIG\ASUMRTIG_Customer
	This script does a placecall to 8884047759, which is tied to script:  ChimericalCorporation\Extension\ASUMRTIG\ASUMRTIG_IVRRoot
		above script does a runsub (could be combined into a single script) to ChimericalCorporation\Extension\ASUMRTIG\ASUMRTIG_Agent

