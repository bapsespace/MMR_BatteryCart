# MMR_BatteryCart

## ToDo
- [ ] Programmare Tutto


## Connections  
- **CAN BMS Zoom**  
- **AC/DC Charge Zexion Zoom**  
- Server-like connection between PCB and CAN line  

## Fault Line Readings  
- **NGS:** Supply, Ground, CAN L, CAN H  
- **LED Indicators:**  
  - CHARGE light up  
  - LOAD light up  
  - SML-NGS light-up/Traumatic  

## Switches (Vertical)  
1. **EN Mode:** Charging the battery  
2. **Enable Load:** Discharge the battery  
3. **Extra:** /FAN /Pump not connected  
   - **SML_ENGS:** Likely related to charger  

## Task Buttons  
- **Reset:** Allows resetting the bus in case of error  
- **Start GOV:** Errors → through STM-to CAN BMS  
- **PUSH ROOM**  

## Battery Connector  
- **CAN BMS**  
- **CAN L BMS**  
- **Zexion relay** → battery board  

## CAN Usage  
- Send commands to change measurements  
  - Load on from ions  
- **ING3 /Nist relay**  
- No use safe location  