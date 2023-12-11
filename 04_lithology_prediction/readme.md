# Lithofacies prediction from well logs 

From wells located in both the south and north of the Viking graben, apply supervised learning to predict lithofacies from well logs. Participants will be provided with well logs such as caliper, resistivity, gamma ray, density, porosity, sonic, and others . Each observation will have an associated lithology class label and confidence. The objective is to predict lithofacies of blind wells using machine learning approaches. The data includes 22 train wells and 3 blind wells. 

**Case Study:** Viking Graben

## The data 

A subset of wells in the south of the Viking graben. 25 wells in total. These well contain the following features: 

- WELL: Name of the Well
- DEPTH_MD: Measured depth
- X_LOC: X UTM coordinate
- Y_LOC: Y UTM coordinate
- Z_LOC: DEPTH
- GROUP: NPD (Norwegian Petroleum Directorate) Lithostratigraphy group
- FORMATION: NPD (Norwegian Petroleum Directorate) Lithostratigraphy group
- CALIPER
- RSHA
- RMED
- RDEP
- RHOB
- GR
- SGR
- NPHI
- PEF
- DTC
- SP
- BS
- ROP
- DTS
- DCAL
- DRHO
- MUDWEIGHT
- RMIC
- ROPA: Rate Of Penetration Average
- RXO
- FORCE_2020_LITHOFACIES_LITHOLOGY
- FORCE_2020_LITHOFACIES_CONFIDENCE



This miniproject is a subset of:

Bormann, P., Aursand, P., & Dilib, F. (2020). FORCE Machine Learning Competition [Computer software]. https://github.com/bolgebrygg/Force-2020-Machine-Learning-competition
