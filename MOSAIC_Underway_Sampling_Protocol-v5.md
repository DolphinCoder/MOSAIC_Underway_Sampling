---
# MIOP terms
methodology_category: sample collection
project: CalCOFI MOSAIC eDNA Sampling
purpose: biodiversity assessment objective [OBI:0001969]
analyses: filtration [OBI:0302885], environmental material collection process [OBI:0600012]
geographic_location: North Pacific Ocean [GAZ:00002418]
broad_scale_environmental_context: marine biome [ENVO:00000447], marine photic zone [ENVO:00000209]
local_environmental_context: marine pelagic zone [ENVO:00000208], marine pelagic biome [ENVO:01000023]
environmental_medium: sea water [ENVO:00002149]
target: environmental DNA [NCIT:C169106]
creator: Nastassia Patin, Eldridge Wisely, Ella Crotty
materials_required: filtration [OBI:0302885]
skills_required: sterile technique, pipetting skills, standard molecular technique, research vessel experience
time_required: 60-300
personnel_required: 1
language: en
issued: 2025-12-12
audience: scientists
publisher: Scripps Institution of Oceanography, UC San Diego
hasVersion: 1
license: CC0 1.0 Universal
maturity level: mature

# FAIRe terms
checkls_ver: 1.0.2
sterilise_method: Bleach and DNAway
neg_cont_0_1: 1
pos_cont_0_1: 0
habitat_natural_artificial_0_1: 0
samp_collect_method: ship underway pump
samp_collect_device: Swinnex filter housing
samp_size: 1-70
samp_size_unit: L
samp_store_temp: -80
samp_store_sol: DNA/RNA Shield
mod_date: 2025-12-12
accessRights: publicly available
bibliographicCitation: None
code_repo: github.com/CalCOFI/eDNA-protocols
---

# CalCOFI Sampling From Ship's Underway Water System

## PROTOCOL INFORMATION

### Minimum Information about an Omics Protocol (MIOP)

- MIOP terms are listed in the YAML frontmatter of this page.
- See <https://github.com/BeBOP-OBON/miop/blob/main/model/schema/terms.yaml> for list and definitions.

### Making eDNA FAIR (FAIRe)

- FAIRe terms are listed in the YAML frontmatter of this page.
- See <https://fair-edna.github.io/download.html> for the FAIRe checklist and more information.
- See <https://fair-edna.github.io/guidelines.html#missing-values> for guidelines on missing values that can be used for missing FAIRe or MIOP terms.

### Authors

| PREPARED BY | AFFILIATION | ORCID | DATE |
| ------------- | ------------- | ------------- | ------------- |
| Nastassia Patin | UC San Diego, CalCOFI | 0000-0001-8522-7682 | 2025-12-12 |
| Eldridge Wisely | UC San Diego, CalCOFI | 0009-0001-2784-4778 | 2025-12-12 |
| Ella Crotty | UC San Diego, CalCOFI | 0009-0004-4340-2007 | 2025-12-12 |

### Protocol Revision Record

- Version numbers start at 1.0.0 when the protocol is first completed and will increase when changes that impact the outcome of the procedure are made (patches: 1.0.1; minor changes: 1.1.0; major changes: 2.0.0).
- Release date is the date when a given protocol version was finalised.
- Description of revisions includes a brief description of what was changed relative to the previous version.

| VERSION | RELEASE DATE | DESCRIPTION OF REVISIONS |
| ------------- | ------------- | ------------- |
| 1.0.0 | 2025-12-12 | Initial release |

### Acronyms and Abbreviations

| ACRONYM / ABBREVIATION | DEFINITION |
| ------------- | ------------- |
| CalCOFI | California Cooperative Oceanic Fisheries Investigations |
| eDNA | environmental DNA |
| PCR | Polymerase Chain Reaction |
| SIO | Scripps Institution of Oceanography |

### Glossary

| SPECIALISED TERM | DEFINITION |
| ------------- | ------------- |
| Deck observers | CalCOFI personnel visually identifying marine mammals during transects |
| Transect | A portion of the research vessel's path between two stations |

## BACKGROUND

### Summary

This protocol describes the sampling of marine eDNA from the underway pump of a moving or stationary research vessel. This protocol was used on CalCOFI cruises, but could be adapted for use on any research vessel with an underway pump. The end result of this protocol is filters with preserved eDNA from surface seawater along the research vessel's path.

### Method description and rationale

This protocol describes sampling eDNA from the underway pump of a research vessel. A filter in a Swinnex housing is attached to the vessel's underway pump using tube adapters, and surface seawater underneath the vessel is pumped through the filter by the ship's underway system. After a certain distance and time decided by the goals of the specific sampling effort, the filter is taken out of the housing in a PCR hood, preserved in buffer, and stored in a freezer. This protocol could be adapted for use on any research vessel with an underway pump.

### Spatial coverage and environment(s) of relevance

This protocol can be used on any oceanographic research vessel with an underway pump that delivers surface seawater to the lab.

## PERSONNEL REQUIRED

One person with pipetting experience. Research vessel experience is recommended but not required. Two people can sample 24/7.

### Safety

There are no major safety concerns with this protocol. Proper PPE should be worn at all times, especially when sterilizing equipment with bleach.

### Training requirements

Standard molecular biology training including sterile technique and pipetting technique is required to properly conduct this protocol. Research vessel experience is recommended. In-person training in this method prior to the cruise is recommended.

### Time needed to execute the procedure

The process of setting up, starting, and finishing a sample should take around 60 minutes. The time to actually sample is determined by the goals of the study, since the samples are left running. Samples must be checked on approximately every 20 minutes during the sampling.

## EQUIPMENT

| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| **Durable equipment** |
| 10 L carboy | 10 L Nalgene carboy | Generic brand | 2 | Mark these carboys with permanent marker every 250 mL and write the liter measurements for each. This will take a long time but will make measuring outflow much easier. |
| 20 L carboy | 20 L Nalgene carboy | Generic brand | 1 | To hold bleach. Label "DO NOT PUT DOWN DRAIN". |
| 1 L graduated cylinder | Graduated cylinder - 1 L | Generic brand | 1 | Diameter should be sufficient to hold one Swinnex filter housing |
| -80 °C freezer | -80 °C commercial chest freezer | Generic brand | 1 | |
| Forceps | Plastic or metal forceps | Generic Brand | 4 | This protocol uses approx. 50 plastic forceps and sterilizes them when more are needed. 4 metal forceps with constant sterilization would also work (see scissors sterilization protocol). |
| Cryovial rack | Any rack that fits final sample storage cryovials | Generic brand | 1 |  |
| Ruler/straightedge | Ruler | Generic brand | 1 | Useful for lab notebook records |
| PCR station | MY-PCR Prep Station | Mystaire | 1 | Portable hood with fan, not needed if you have access to a hood on the research vessel. Bring power cord. |
| Permanent Marker (Thick) | Sharpie Permanent Marker, Fine Point, Black | Sharpie | 2 | To label large items |
| Permanent Marker (Thin) | Sharpie Permanent Marker, Extra Fine Point, Black | Sharpie | 2 | To label cryovials |
| Pencils | Pencil | Generic brand | 5 | To write in lab notebook, include extras. |
| Ball valve | Asahi AV Valve, 150 PSI at 70ºF, EPDM seals, PVC, 13 1/2, Type-C | ASAHI | 1 | In order to take replicate samples from one underway tap, use this valve to split the flow and enable taking either one or two samples. |
| Tubing | Masterflex 6424-17 | Masterflex | 10 | If also CTD sampling, ensure that your tube size is compatible with your peristaltic pump before departing for a cruise. Bring at least one tube per parallel sample (Underway, CTD, and replicates) and bring extras in case of damage. |
| Screw end for tubing | Stainless Steel 1/4" Hose Barb to 1/4" Female | Beduan or generic brand | 4 | To attach the filter housings to the tube. Assemble the tubing with housing before departing on a cruise to ensure good fit. |
| **Consumable equipment** |
| Field notebook | Notebook, ideally with waterproof pages | Generic brand | 1 | Transfer to digital sample sheet once a day during cruise |
| DNA/RNA Shield | Zymo DNA/RNA Shield, Catalog # R1100-250 | Zymo Research | 250 mL | 0.4mL required per sample. |
| DNAway | DNA Away Catalog # 7010 | Molecular BioProducts | 250 mL | For sterilizing the hood, pipette, and scissors. |
| Gloves | Powder-free nitrile gloves | Generic brand | 1 box | Expect approximately 3 boxes for a 10-day cruise. Can be any generic brand of gloves. |
| 1000 µL Pipette Tips | 1000 µL Pipette Tips | Generic Brand | 1 box | Quantity depends on cruise length. Expect 1 tip per sample. Verify that tips fit your pipette before cruise begins. |
| Filters | 5.0 µm MCE Filters, 47 mm | Millipore | 1 | Quantity depends on cruise length. Expect 1 filter per sample and bring extra. |
| Cryovials | CryoELITE® Cryogenic Vials, Freestanding, External Thread, 2 mL | Wheaton | 1 | Quantity depends on cruise length. Expect 1 cryovial per sample. |
| Cryovial storage box | Cardboard box with grid inside for cryovials | Generic brand | 1 | Enough boxes to store all samples in freezer. |
| Shop towels | Shop towels | Generic brand | 1 roll | Used to cover the benchtop in the PCR hood. Expect to replace every 5-10 samples. |
| Ziplock bags | Gallon-sized ziplock bags | Ziploc | 1 box | Used to sterilize equipment. Expect it to need replacing every 3-5 sterilizations. |
| Repair tape | White Duct Tape | Generic Brand | 1 roll | For repairs. |
| **Chemicals** |
| 5-9% Sodium hypochlorite | Household bleach | Generic brand | 1 bottle | Dilute 1:10 for sterilization |
| Deionized or Milli-Q water | DI water | Generic brand | 2 | (L per sterilization) Can use ship's MilliQ water |

## STANDARD OPERATING PROCEDURE

### Notes
- You will be sampling during the day in parallel with deck observers. Collaborate as much as possible with the observers so you can keep track of mammal sightings.
- Each day, one or more transects will be sampled. Each transect starts and ends at a station.
- The underway system pulls water directly from the surface of the ocean (~5m deep). It operates consistently, but you can control the outflow through the tap at your work station. You should aim to run the tap and filter water from the beginning to the end of a transect. When on station, you can keep the tap running even when not sampling, unless told otherwise by the ship’s crew.
- The transect and station information will be written on the white board in the main lab; check this board at the beginning of each transect and consult with a CalCOFI technician if you have questions. Use the information to fill in the sample sheet. Please convert the lat-long from degree minutes to decimal degrees!

### Time Management
- Setup at the beginning of a shift:
  - Use DNAway to wipe down the hood, pipette, DNA/RNA Shield bottle, and anything else you touch a lot (See Step 2 below)
  - Swap out the shop towel
- Before each station (30-60 mins before):
  - Check the protocol and any plans you have for replicates so you know what you're doing on station
  - Make sure you've bleached enough equipment to use on station: Enough housings for the samples you'll start, forceps
  - Keep an eye on the ship's speed! Depending on the ship, starting and stopping could be very smooth and tough to notice.
- On station:
  - Check your latitude and longitude, take a picture or write it down
  - Stop the underway filtering, begin an on-station filter (see full protocol below)
- Leaving station:
  - Check latitude and longitude, take a picture or write it down
  - Stop the on-station filtering, begin transect filters (check: will you be doing two filters?) (see full protocol below)
  - After 1-2 hours (depending on the transect and your plans for the cruise), end the partial transect filter, and start a new one if that's the plan (see full protocol below)
- During spare time:
  - Sterilize housings and forceps
  - Check on filtration - is it still running?
  - If the waste carboys have more than 4 liters of water in them, record the volume and pour them out (see protocol below and video)
  - Data entry (try to do at least once per day)
  - Check with marine mammal observers, note sightings and audio detections
- End of shift:
  - If working alone, make a note of any issues, clean up and secure station.
  - If working shifts, pass on any information about equipment issues and current samples running.

### Sampling Protocol

#### Setup

1. Set up the hood for your clean work space. This is where you will assemble the new filters + housings, and transfer the filters from the housings to the cryovials.
2. Decontaminate the inside the hood thoroughly using DNAway or bleach. Spray the solution, let sit for 10 minutes, and wipe down.
3. Wipe down your forceps, cleaning solutions, P1000 pipet and tips, DNA/RNA Shield bottle, Sharpies and anything else you will use consistently in the hood before storing them inside.
4. After the hood has been decontaminated, keep it closed at all times unless working in it.

#### Underway water filtration

Filtration may be full transect or partial transect. The only difference is in Step 9.

1. After the ship begins transiting, turn on the underway outflow tap. Allow the water to run for 5 minutes to flush out any residual material in the line. You can run the line while you process your filter and set up the new one.
2. Turn off the tap and attach the pump tubing to the tap outflow.
3. Turn the tap on very low pressure, and press the end of the pump tubing against the bottom of the Swinnex housing to flow water through it backwards. This prevents bubbles.
4. Attach the Swinnex housing + filter to the adapter at the end of the tubing with the tap on low pressure.
5. Turn on the tap and adjust the outflow. Mark the start time.
6. Place the tubing outflow end in a marked carboy or graduated cylinder so you can collect the outflow.
7. When there are around 4 liters in the marked carboy, it is heavy and this is a good time to pour it out. Write the volume, place the tubing outflow in a graduated cylinder, pour out the carboy, and place the tubing outflow back in the carboy while pouring any water that was filtered into the graduated cylinder into the carboy.
8. When you reach the end of the transect (or decide to stop sampling for another reason) divert the tap outflow into the sink. It is acceptable to leave the tap flowing on station unless advised otherwise by the crew.
9. Filter until one of the following happens:
      - You notice the flow is slowing, indicating the filter is getting clogged
        - If the filter clogs near the end of a transect, there is no need to start a second filter. However, if it is less than halfway through the transect, attach a new filter to the line and continue filtration. Use a separate line in the sample sheet for each filter.
      - The transect is completed (you reach the last station).
      - The partial transect is completed (It has been 1 hour, 2 hours, or halfway through the transect depending on study goals).

10. Turn off the tap.
11. Measure the filtrate volume and mark the end time, and take a photo of or write down the latitude and longitude. This is very important!
12. In the PCR hood, set out your forceps decontamination kit: 4 x 50 mL Falcon tubes containing DNAway, water (x 2 tubes), and 100% EtOH, in that order.
13. Detach the Swinnex housing + filter from the tubing and bring them into the hood.
14. Label a cryovial with the cruise number and filter number.
15. In the hood, disassemble the Swinnex and transfer the filter into a labeled cryovial. Decontaminate your forceps by dipping them sequentially into the Falcon tubes before touching the filter. Label the tube - see below for the labeling scheme.
    - Roll the filter into a little tube or fold into eighths and stick into the vial. It is helpful to use two sets of forceps for this. See video protocol for one possible technique to do this with one pair of forceps.

#### Sample Preservation

1. Using a P1000 (1000 uL pipette), add 400 uL of DNA/RNA Shield preservative into the cryovial.
2. Place the cryovial in a -80ºC freezer as soon as possible.

#### Storage

1. Freeze at –80 °C in a box with other samples until extraction.

#### Post-Sampling/Sterilization

- You do not need to sterilize all tubing and filter housings in between every sample, but you should try to clean periodically.
- Clean both the tubing and the filter housing by attaching the empty housing (without a filter) to the tubing.
- Clean the filter housings by placing the tops in one bag and the bottoms in another, soaking in bleach 15 minutes, then rinsing and shaking three times with milliQ water in the bag.
- Wipe down the benches and other surfaces with 70% ethanol and/or DNAway.
- For every sample, allow the sample water to run through tubing for 5 minutes before adding a filter. This will flush any residual bleach and/or material from a previous sample.
- Do not allow bleach to go down the sink. Bleach can go in and out of its bottles and bags, and in the bleach waste carboy if it is dirty and you need to make new bleach.

#### Data records

- While filtering, record all the relevant information on the printed copy of the appropriate data sheet (underway vs CTD samples).
- Periodically (at least once per day) transcribe the written records into the electronic copy of the sample sheet.
- Full underway sample IDs should be as follows:
\<CRUISE-ID>_ \<LINENUMBER-TRANSECTNUMBER>_\<FILTER-NUMBER>
  - For example: RS2311\_LINE80-01\_F001
- Full CTD sample IDs should be labeled as follows:
\<CRUISE-ID>\_\<STATION>\_\<CTD-CAST>_\<FILTER-NUMBER>
  - For example: RS2311\_90-55\_C001_F002
- Cryovials can be labeled with the filter number only (F001 - FXXX)

### Quality control

**Negative Controls**
- To take a negative control, start with a filter in a housing. Turn on the ship's milliQ dispenser and press the back side of the housing to it, to make water flow backwards through the housing. Then, set the milliQ dispenser to dispense 2 liters of water and press the housing against it with the screw top facing the dispenser, so that water is flowing through the correct way. Once the 2 liters have flowed through the housing, take the housing to the sink where the underway samples are taken and rub the housing around the mouths of the outflow carboys used for underway samples. Put the housing in the PCR hood and process the filter as normal.

### Basic troubleshooting guide

**Filter clog**

If flow slows, first check the underway pump flow. If underway pump flow has slowed or stopped, ask the chief scientist what to do, and they will probably refer you to engineering. If a filter clogs and there's more than one hour left in the transect, end that and start a new one.

**Filters keep coming out torn**

If filters are torn when you open the filter housing to preserve them, try not tightening the housings quite as hard. Undertightening can lead to leaks, but overtightening can lead to filter tears.

**Filter housing is leaking**

Screw the housing together tighter. If the problem persists, try to screw it together straighter.

## REFERENCES

Work in progress.

## APPENDIX A: DATASHEET TEMPLATE

![Sample sheet template (Excel file)](https://github.com/CalCOFI/MOSAIC_Underway_Sampling/blob/main/CalCOFI%20eDNA%20Underway%20Filtration%20Sample%20Sheet%20TEMPLATE.xlsx)

## APPENDIX B: VIDEO & IMAGE FILES

[Video Protocol](https://youtu.be/XGT-FZi2hi4?si=DsedQEnom17YF58_)

![CarboyOutflowMeasurement)](https://github.com/CalCOFI/MOSAIC_Underway_Sampling/blob/main/Images/CarboyOutflowMeasurement.JPG)

Figure 1. Step 7. When there are around 4 liters in the marked carboy, it is heavy and this is a good time to pour it out. Write the volume, place the tubing outflow in a graduated cylinder, pour out the carboy, and place the tubing outflow back in the carboy while pouring any water that was filtered into the graduated cylinder into the carboy.

![CarboyMarkings)](https://github.com/CalCOFI/MOSAIC_Underway_Sampling/blob/main/Images/CarboyMarkings.JPG)

Figure 2. Recommended carboy markings.

![Backflow)](https://github.com/CalCOFI/MOSAIC_Underway_Sampling/blob/main/Images/Backflow.JPG)

Figure 3. Step 3. Turn the tap on very low pressure, and press the end of the pump tubing against the bottom of the Swinnex housing to flow water through it backwards. This prevents bubbles.

![FilterFold)](https://github.com/CalCOFI/MOSAIC_Underway_Sampling/blob/main/Images/FilterFold.JPG)

Figure 4. Step 15. ...Roll the filter into a little tube or fold into eighths and stick into the vial. It is helpful to use two sets of forceps for this. See video protocol for one possible technique to do this with one pair of forceps.

![HousingAttach)](https://github.com/CalCOFI/MOSAIC_Underway_Sampling/blob/main/Images/HousingAttach.JPG)

Figure 5. Step 4. Attach the Swinnex housing + filter to the adapter at the end of the tubing with the tap on low pressure.

![PCRHoodSetup)](https://github.com/CalCOFI/MOSAIC_Underway_Sampling/blob/main/Images/PCRHoodSetup.JPG)

Figure 6. PCR hood setup used in this protocol.

![SinkSetup)](https://github.com/CalCOFI/MOSAIC_Underway_Sampling/blob/main/Images/SinkSetup.JPG)

Figure 7. Underway filtration setup in a lab sink.
