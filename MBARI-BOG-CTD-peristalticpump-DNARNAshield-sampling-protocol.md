---
# MIOP terms
methodology_category: sample collection
project: Monterey Bay Time Series (MBTS)
purpose: biodiversity assessment objective [OBI:0001969]
analyses: filtration [OBI:0302885], environmental material collection process [OBI:0600012]
geographic_location: Monterey Bay [GAZ:00002509]
broad_scale_environmental_context: marine biome [ENVO:00000447]
local_environmental_context: upwelling [ENVO:01000005]
environmental_medium: sea water [ENVO:00002149]
target: deoxyribonucleic acid (DNA) [NCIT:C449]
creator: Jacoby Baker, Kobun Truelove, Kathleen Pitz
materials_required: peristaltic pump
skills_required: sterile technique
time_required: 60
personnel_required: 1
language: en
issued: 2025-11-25
audience: scientists
publisher: Monterey Bay Aquarium Research Institute
hasVersion: 1
license: CC0 1.0 Universal
maturity level: mature

# FAIRe terms
## sample collection
samp_category: # sample-specific
env_broad_scale: marine biome [ENVO:00000447]
env_local_scale: # sample-specific
env_medium: sea water [ENVO:00002149]
habitat_natural_artificial_0_1: 0
samp_collect_method: CTD rosette
samp_collect_device: Niskin bottle
samp_size: 1000
samp_size_unit: mL
samp_store_temp: -80
samp_store_sol: DNA/RNA Shield
## sample preparation
samp_mat_process: Water samples were filtered using a peristaltic pump (pore size 0.22 micrometers).
filter_passive_active_0_1: 1
prefilter_material: # not applicable
size_frac_low: # not applicable
size_frac: 0.22
filter_diameter: 25
filter_material: polyvinylidene difluoride (PVDF)
---

# eDNA sampling using a peristaltic pump with preservation in DNA/RNA Shield solution

## PROTOCOL INFORMATION

### Minimum Information about an Omics Protocol (MIOP)

>- MIOP terms are listed in the YAML frontmatter of this page.
- See [MIOP_definition.md](https://github.com/BeBOP-OBON/0_protocol_collection_template/blob/main/MIOP_definition.md) for list and definitions.

### Making eDNA FAIR (FAIRe)

>- FAIRe terms are listed in the YAML frontmatter of this page.
- See <https://fair-edna.github.io/download.html> for the FAIRe checklist and more information.
- See <https://fair-edna.github.io/guidelines.html#missing-values> for guidelines on missing values that can be used for missing FAIRe or MIOP terms.

### Authors

> - All authors known to have contributed to the preparation of this protocol, including those who filled in the template.
- Visit https://orcid.org/ to register for an ORCID.
- Date is the date the author first worked on the protocol.

| PREPARED BY  | AFFILIATION  | ORCID        | DATE       |
| ------------ | ------------ | ------------ | ---------- |
| Jacoby Baker | MBARI | 0000-0002-0673-7535 | 2025-11-25 |
| N. Kobun Truelove | MBARI | 0000-0002-2236-1849 | 2025-11-25 |
| Kathleen J. Pitz | MBARI | 0000-0002-4931-8592 | 2025-11-25 |

### Related Protocols

>- This section contains protocols that should be known to users of this protocol.
- Include the link to each protocol.
- Include the version number and release date (if available).
- Internal/External: "Internal" are derivative or altered protocols, or other protocols in this workflow. "External" are protcols from manufacturers or other groups.

| PROTOCOL NAME | LINK         | VERSION      | RELEASE DATE | INTERNAL/EXTERNAL |
| ------------- | ------------ | ------------ | ------------ | ----------------- |
|    |   |   |    |        |
|    |   |   |    |        |

### Protocol Revision Record

>- Version numbers start at 1.0.0 when the protocol is first completed and will increase when changes that impact the outcome of the procedure are made (patches: 1.0.1; minor changes: 1.1.0; major changes: 2.0.0).
- Release date is the date when a given protocol version was finalised.
- Description of revisions includes a brief description of what was changed relative to the previous version.

| VERSION | RELEASE DATE | DESCRIPTION OF REVISIONS |
| ------------- | ------------- | ------------- |
| 1.0.0 | 2025-11-25 | Initial release |

### Acronyms and Abbreviations

| ACRONYM / ABBREVIATION | DEFINITION |
| ------------- | ------------- |
|    |    |
|    |    |

### Glossary

| SPECIALISED TERM | DEFINITION |
| ------------- | ------------- |
|    |    |
|    |    |

## BACKGROUND


### Summary


This protocol is for water samples collected from Niskin bottles on a CTD rosette (although it can be applied to other water sample collection methods). The goal is to concentrate environmental DNA and RNA from seawater onto a flat filter membrane for preservation and later analysis through metabaroding and qPCR.

### Method Description and Rationale

This protocol is designed for relatively high-throughput sampling in primarily nearshore surface waters where environmental DNA concentrations are higher but also due to phytoplankton blooms or other biomass aggregations, passing more than 1L through a 0.22 uM membrane can be sometimes difficult. When sampling in lower eDNA environments (offshore or in deeper environments) consider increasing the volume of seawater filtered. A larger poresize filter can also be used to sample higher volumes of seawater but may be detrimental to prokaryote community collection.


### Spatial Coverage and Environment(s) of Relevance

This protocol has been used to collect environmental DNA from sea water samples taken from marine stations off the western coast of North America (primarily off of California).

- ocean [ENVO:00000015]

### PERSONNEL REQUIRED

1 technician

### Safety

>Identify hazards associated with the procedure and specify protective equipment and safety training required to safely execute the procedure

### Training Requirements

sterile technique

### Time Needed to Execute the Procedure

Depending on how quickly the water passes through the filter, the water collection and filtration process can take around 60 minutes.

## EQUIPMENT

- Description: E.g., "filter".
- Product Name and Model: Provide the official name of the product.
- Manufacturer: Provide the name of the manufacturer of the product.
- Quantity: Provide quantities necessary for one application of the standard operating procedure (e.g., number of filters).
- Remark: For example, some of the consumable may need to be sterilized, some commercial solution may need to be diluted or shielded from light during the operating procedure.

| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| **Durable equipment** |
| forceps |   |   |   |   |
| Swinnex filter cartridges |   |   |   |   |
|peristaltic pump and pumpheads|||||
|2L wide-mouth square plastic bottles|||||
|vinyl outflow tubing|||||
|1L collection bottles|||||
|milk crate (optional)|||||
| **Consumable equipment** |
| 50mL falcon tubes |   |   |   |   |
|falcon tube stand|||||
| serological pipettes |   |   |   |   |
|25 mm Millipore filters|   |   |   |   |
|DNA/RNA Shield collection tubes|||||
|disposable absorbent under pad|||||
|MasterFlex tubing|||||
|Whirlpak disposable bags|||||
|sterile syringe|||||
| **Chemicals** |
| RNase Away |   |   |   |   |
| 70% ethanol |   |   |   |   |
|10% bleach|||||
|MilliQ water|||||

## STANDARD OPERATING PROCEDURE


### Prior to collection: 
- This protocol is for water samples collected from Niskin bottles on a CTD rosette (although it can be applied to other water sample collection methods) and assumes that sterile techniques are practiced for all disposable items
- Prepare the following 50mL falcon tubes (one set per sampling day):
 - 50mL of RNase Away (x1)
 - 50mL of MilliQ / DI water (x3)
 - 50mL of 70% ethanol (x1)
- Remove cotton from the ends of the sterile serological pipettes with clean forceps
- Assemble Swinnex filter cartridges and load them with a 25 mm Millipore filter (0.22uM pore diameter). This assumes we are using a peristaltic pump for water filtration and that we use 25 mm sized filters. A vacuum pump can also be used as well as other filter sizes (e.g. 47 mm). A key element of all of the filtration/handling is to avoid contamination from biological/DNA sources outside of the sample (e.g. bacteria, human, net tow material) or from a previous sample that was filtered on the same rig. 

### Sampling Notebook and Storage Setup:
- In field notebook, note the station, above labeling scheme, date, max depth, time of CTD cast
- Create a list of anticipated samples by listing Depths(m), Niskin #, Cast #, Notes (to be filled in as collection and filtering occurs)
- Label DNA/RNA Shield collection tubes (apply horizontally on standing tube), labelling scheme is CRUISEc##_BB_eDNA (where ## is cast number and BB is niskin bottle number, i.e. CN18Sc01_12_eDNA is cast 1, bottle 12). *This labeling is specific to MBARI cruises and should be adapted for each campaign. It is key to be able to have the correct information (metadata) to be able link the sample to location, date/time, water filtered (and associated protocol) and environmental information from CTD (or other sources).*

### Sampling Area Staging:
- Spray 10% bleach (or RNase Away) onto benchtop where filtering work will be conducted
- Wipe away bleach with clean paper towel and rinse with MilliQ / DI water; dry with paper towel
- Use a 70% solution (or disinfectant wipes) to further clean surface; let dry
- Cover clean area with disposable absorbent under pad (this is changed daily; occasionally more frequently if water is spilled in excess) 
- Place peristaltic pump and pumpheads on pad and secure to bench; the pump should be placed next to a sink or deep trough for running sample water through tubing and to prevent potential spills
- Set the prepared 50mL tubes in a falcon tube holder or stand; these should be changed out daily. Order of use with be (1) water (2) RNAse Away (3) water (4) water (5) ethanol.
- Sterilize forceps with an intitial dip into the first water tube, then place into RNAse Away for at least 1 minute, then dip into two sequential tubes of water (allow to drip before transferring), and finally set into the tube of ethanol; forceps cleaned in the prior steps can stay in ethanol while doing other preparation activities. Initial tube of water is to reduce DNA/RNA shield carry-over into RNAase Away solution.
- Excess ethanol on cleaned forceps can be air-dried or dried with a clean Kimwipe before contacting a filter.

### Peristaltic Array Setup:
- Each peristaltic pump can hold six sets of tubing each (2 per pump head; 3 pump heads per device) for a maximum of 12 water samples at a time
- Set the 63cm / 25 inch MasterFlex tubing in the pump heads. If sampling won't take place for more than two hours, you can cover tubing ends with paper towels or other sterile supplies (i.e. labware plastic bags) to reduce contamination. (As indicated above a vacuum pump can also be used for all of the steps instead of a peristaltic pump)

### Collection Blank:
- Run 1L of MilliQ / DI water through one pump and loaded Swinnex cartridge; this is to serve as a negative collection blank
- Immediately place Millipore filter into a labeled DNA/RNA Shield collection tube
- Run a new collection blank daily

### Water Sampling Setup:
- Label Whirlpak disposable bags to correspond with Niskin bottle number
- Fold sterile stand-up Whirl-Pak bag lengthwise and insert into 2L wide-mouth square plastic bottle (this provides structural support for bag when filled with water).
- The Whirlpak bags are used to avoid contamination and the need to wash bottles between samples. Water collection can be made with other bottles if care is taken to avoid contamination. MBARI historical sample collections made before targeted eDNA sampling were done with reusable plastic bottles that were rinsed three times before sample collection and filtered using vacuum pumps.

### Niskin Sampling:
- At the Niskin sampling area, open the Whirlpak from the top; fill with water from Niskin up to bottle neck line, roll bag down, fold in twist-tie, and twist to re-seal 
- Total volume collected should be within 1.3 - 1.5 liters
- Repeat until all of the corresponding bottles have been collected
- Carry the filled Whirlpaks inside of the 2L bottles back to the sampling area inside the wet lab (a crate may be useful for handling multiple)

### Peristaltic Pump Filtration and Sample Preservation:
- Stage the water samples near the peristaltic arrays; six samples per array
- Insert the pointed end of the serological pipette into the “wide” end of the peristaltic pump tubing
- Insert the other end of the pipette into the water sample and wrap Whirlpak seal around the pipette to reduce contamination from air particles
- Repeat steps 6 and 7 for every water sample; once staged, start the pump
- Ensure the water flow is moving towards the sink / waste collection and allow ~0.3 liters of sample water to flow through the MasterFlex tubing and into the waste unimpeded; this is to inoculate the tubing with sample
- Once 0.3 liters has passed, stop the pump
- Place the preloaded Swinnex filter cartridges on the tubing outflow end; attach 15cm vinyl outflow tubing to the opposite end of the Swinnex cartridges to direct water flow into 1L collection bottles
- Pump 1L of sample water through the Swinnex cartridge; stop the pump when finished
- Remove the cartridge from the tubing. [optional] Use a sterile syringe to blow air through the cartridge to remove remaining water droplets on the Millipore filter.
- For vacuum filtration measure the appropriate volume and pour through disposable filter holders.
- Using sterile forceps, remove the filter from the cartridge and carefully insert into a pre-labeled DNA/RNA Shield collection tube

### Storage

- Samples are kept shipboard in DNA/RNA Shield solution at room temperature until return to MBARI where samples are placed in a -80°C freezer until further processing.

### Quality Control

>Describe and explain criteria used to validate results of the standard operating procedure.

### Basic Troubleshooting Guide

>- Identify known issues associated with the procedure, if any.
- Provide troubleshooting guidelines when available.

## REFERENCES

>- Insert all references cited in the document.
- Please insert full DOI address when available, e.g. http://doi.dx.org/10.1007/s11258-014-0404-1.

## APPENDIX A: DATASHEETS

>Link templates (e.g. preformatted spreadsheets) used to record measurements and report on the quality of the data as well as any documents such as manufacturer specifications, images, etc that support this protocol. Please include a short note describing the document's relevance. 

