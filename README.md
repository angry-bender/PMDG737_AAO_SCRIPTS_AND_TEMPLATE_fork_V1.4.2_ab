# Credit

This project is a fork of the already existing mod on flightsim.to https://flightsim.to/file/32603/pmdg737-axis-and-ohs-scripts-and-full-template-for-honeycomb-alpha-and-bravo by Andrew2448

# Usecase

This updates the existing configuration to add the following features

- Remove the cuttoff feature from the throttle axis
- Add in a flap lever that is compatable with the offical Honeycomb Bravo flap kit
- Add in a custom spoiler axis that has FligtDetent at a more logical location with detent being right at the bottom of the physical leaver, and up in the middle.

# Custom config
Thus template has even more, it includes rhe lights and some tweaks to the controls as detailed below

## Layouts
Thanks for the clarification! Here's how those two rows can be formatted into clean Markdown tables:

---

### ✈️ - AP Selector and Correlating Light Indicator

| HDG SEL MODE | VNAV             | **Short:** _App_ **Long:** _VOR/LOC_ |LNAV | **Short:** _ALT HLD_ **Long:** _ALT INTV_ |V/S Mode  | **Short:** _LVL CHNG _**Long:**_ SPD INTV_|
|--------------|------------------|----------------------------------|-----|---------------------------------------|----------|--------------------------------------|
|              |VNAV _or_  VOR/LOC|                                  |LNAV |    ALT HLD                            |          |                  | SPD     |

---

### 🧭 Switches

| **SEATBELT** _On/Off_ | **Eng Mode Switch** _CONT/OFF_ | **ENG ANTI-ICE** _On/Off_ | **APU** _On/off_ |  **APU BLEED**_ On/Off_ | **DOME LIGHT** _CONT/OFF_ | **PArking Break** _On/Off_ 
|-----------------------|--------------------------------|---------------------------|------------------|-------------------------|---------------------------|---------------------------

### ⚡ Yoke

| **GRD POWER** _On/Off_ | **BAT** _ON/OFF_ | **IRS1+2** _On/Off_ | **TARA/CLOCK** _Start/Off_ | |  **AUTOBRK** _RTO/Off/2/3/MAX_ 
|-----------------------|-------------------|---------------------|----------------------------|-|--------------------------------



## Requirements for custom config
If you want to use the custom config you need to allow the sdk from %ROAMINGAPPDATA%\Microsoft Flight Simulator\Packages\PMDG 73X\main.cfg

for **both** 738 and 737 (thus cought me out)
