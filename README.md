# PHM-Datasets
Collection of datasets related to prognostics and health management (PHM).

Currently, datasets within this topic are scattered around the web at different repositories -- such as the NASA PCoE (https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/) -- or competition sites like the PHM Society data challenges. This list aims to consolidate these in to one place in order to accelerate research.

## Table-of-Contents
* [Mechanical Systems](#mechanical-systems)
    + [Turbofan Engines](#turbofan-engines)
        + [PHM08 Challenge](#PHM08-challenge)
        + [CMAPSS](#cmapss)
        + [N-CMAPSS](#n-cmapss)
    + [Bearings](#bearings)
        + [FEMTO](#femto)
        + [IMS](#ims)
    + [Milling](#milling)
        + [Milling Machine](#milling-machine)
        + [CNC Milling Machine](#cnc-milling-machine)
    + [Anemometer](#anemometer)
    + [Wafer Chemical-Mechanical Planarization](#wafer-chemical-mechanical-planarization)
    + [Multi-Component System](#aramis)
    + [Bogie Vehicle](#bogie)
    + [Aluminum Fatigue Cracking](#aluminum-fatigue-cracking)
    + [CRFP Fatigue](#crfp-fatigue)
* [Electronics](#electronics)
    + [IGBTs](#igbts)
    + [MOSFETs](#mosfets)
    + [Capacitors](#capacitors)
    + [Hard Drives](#hard-drives)
* [Batteries and Fuel Cells](#batteries-and-fuel-cells)
    + [Proton Exchange Membrane Fuel Cell](#proton-exchange-membrane-fuel-cell)
    + [Li-Ion Batteries](#li-ion-batteries)
    + [Randomized Battery Usage Data](#randomized-battery-usage-data)
    + [HIRF Batteries](#hirf-batteries)
* [Other](#other)
    + [Ion Mill Etch Tool](#ion-mill-etch-tool)
    + [Filtration System](#filtration-system)

## Mechanical Systems
---
### Turbofan Engines
This data set was generated with the 'Commercial Modular Aero-Propulsion System Simulation' (CMAPSS) simulator, a tool for the simulation of commercial turbofan engine data. There are three sets of data:

#### PHM08 Challenge:
Data from the data challenge competition held at the 1st international conference on Prognostics and Health Management (PHM08)

Download link: https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/#phm08_challenge


#### CMAPSS:
Turbofan engine degradation dataset. Similar to the PHM08 challenge data.

Download link: https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/#turbofan

#### N-CMAPSS:
A newly released update to the old cmapss data. This time the simulated data is redone with real flight condition data which is also mapped to the degradation. Data is of higher frequency hence the size is significantly larger then the two previous datasets. Furthermore, the data include parameters for the underlying degradation model.

Data description: https://www.mdpi.com/2306-5729/6/1/5

Download link: https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/

---
### Bearings

#### FEMTO:
IEEE PHM 2012 Prognostic Challenge. The challenge is focused on prognostics of the remaining useful life (RUL) of bearings, a critical problem since most of failures of rotating machines are related to these components, strongly affecting availability, security and cost effectiveness of mechanical or power industries.

Data description: https://hal.archives-ouvertes.fr/hal-00719503/document

Download link: https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/#femto

#### IMS:
Bearing run-tofailure tests were performed under normal load conditions on a specially designed test rig. The bearing test rig hosts four test bearings on one shaft. The shaft is driven by an AC motor and coupled by rub belts. The rotation speed was kept constant at 2000 rpm. A radial load of 6000 lbs. is added to the shaft and bearing by a spring mechanism

Data description: https://doi.org/10.1016/j.jsv.2005.03.007

Download link: https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/#bearing

---
### Milling:

#### Milling Machine:
Experiments on a milling machine for different speeds, feeds, and depth of cut. Records the wear of the milling insert, VB
Download link: https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/#milling

#### CNC Milling Machine:
RUL estimation for a high-speed CNC milling machine cutters using dynamometer, accelerometer, and acoustic emission data

Data description: https://www.phmsociety.org/competition/phm/10

Download link: https://www.phmsociety.org/competition/phm/10

---

### Anemometer
Dataset to determine if 1 or more of the anemometers exhibit excessive error due to damage or wear.

Data description: https://www.phmsociety.org/competition/phm/11/problem

Download link: https://www.phmsociety.org/competition/phm/11

---

### Wafer Chemical-Mechanical Planarization
The primary objective of this challenge is to predict polishing removal rate of material from a wafer using physics-based modeling methods and the data provided. The condition of the polishing pad and dresser change over time as they are being used. If these states can be estimated, then polishing time estimates can possibly be improved.

Challenge/data description: https://www.phmsociety.org/events/conference/phm/16/data-challenge

Direct download link: https://www.phmsociety.org/sites/all/modules/pubdlcnt/pubdlcnt.php?fid=1506450

---

### Multi-Component System
Degradation state assessment of a multi-component system in evolving enviroments. The degradation of one component can accelerate the degradation processes of the other components, thus modifying their lifetime distributions and the statistical properties of the monitored signals over time.

Data description: https://aramis3d.com/wp-content/uploads/2019/10/Aramis-Challenge.pdf

Download link: http://aramis3d.com/innovation-challenges/

---

### Bogie Vehicle
The system under investigation is a conventional bogie vehicle, consisting of a vehicle body, two bogies and four wheelsets. The simplified model includes coil springs and dampers used in the primary suspension, and air springs in the secondary suspension. Sensors are placed on the wheelsets, on the bogie frames and on the car body. The primary objective of this challenge is to predict faulty regimes of operation of a train car using the data provided and physics-based modeling methods.

Data download: https://www.phmsociety.org/events/conference/phm/17/data-challenge

---

### Aluminum Fatigue Cracking
This data set consists of measurement from piezeoelectric (PZT) sensors that are mounted on aluminum specimen that were tested to fatigue conditions. Fatigue cracks developed in the specimen and failure was declared at a particular crack length.
A hydraulic material testing machine working at 5Hz at room temperature conducted the fatigue testing.

Data description: https://www.phmdata.org/2019datachallenge/

Download link: https://www.phmdata.org/2019datachallenge/

---

### CRFP Fatigue
Run-to-failure experiments were run on CFRP panels with periodic measurements to capture internal damage growth under tension-tension fatigue. Monitoring data consist of lamb wave signals from a network of 16 piezoelectric (PZT) sensors and multiple triaxial strain gages. Additionally, periodic x-rays were taken to characterize internal damage as ground truth information. Three different layups were tested.

Download link: https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/#composites

---

## Electronics

---

### IGBTs
Data from thermal overstress accelerated aging of IGBTs. The data set contains aging data from 6 devices, one device aged with DC gate bias and the rest aged with a squared signal gate bias. Several variables are recorded and in some cases, high-speed measurements of gate voltage, collector-emitter voltage and collector current are available

Data description: https://ieeexplore.ieee.org/document/4662613

Download link: https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/#igbt

---

### MOSFETs
Run-to-failure overstress experiments on discrete power MOSFETs.

Data description: https://ti.arc.nasa.gov/m/project/prognostic-repository/MOSFET%20Thermal%20Overstress%20Aging%20Document.pdf

Download link: https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/#mosfet

---

### Capacitors
Three sets of 8 electrolytic capacitors continuously charged and discharged. Each set charged to 10V, 12V and 14V respectively.

Data description: https://ti.arc.nasa.gov/m/project/prognostic-repository/Description%20of%20Electrolytic%20Capacitors%20under%20Electrical%20Overstress%20Data%20Sets.pdf

Download link: https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/#escapacitor

---

### Hard Drives
Large dataset of hard drive failures. SMART (https://en.wikipedia.org/wiki/S.M.A.R.T.) stats recorded.

Data description: https://www.backblaze.com/b2/hard-drive-test-data.html

Download link: https://www.backblaze.com/b2/hard-drive-test-data.html#downloading-the-raw-hard-drive-test-data

---

## Batteries and Fuel Cells
---
### Proton Exchange Membrane Fuel Cell
IEEE PHM 2014 Data Challenge. Objective is to estimate remaining useful life of proton exchange membrane fuel cells (PEMFC).

Data description: https://repository.lboro.ac.uk/articles/dataset/IEEE_2014_Data_Challenge_Data/3518141

Download link: https://repository.lboro.ac.uk/articles/dataset/IEEE_2014_Data_Challenge_Data/3518141

### Li-Ion Batteries
Experiments on Li-Ion batteries. Charging and discharging at different temperatures. Records the impedance as the damage criterion.

Download link: https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/#battery

### Randomized Battery Usage Data
Batteries are continuously cycled with randomly generated current profiles. Reference charging and discharging cycles are also performed after a fixed interval of randomized usage in order to provide reference benchmarks for battery state of health.

Download link: https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/#batteryrnddischarge


### HIRF Batteries
Battery Data collected from the Experiments on the Edge 540 Aircraft in HIRF Chamber

Data description: https://ti.arc.nasa.gov/m/project/prognostic-repository/HighIntensityRadiatedFieldsDataSet.pdf

Download link: https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/#hirfbatterytests

### Satellite Batteries
Data collected from the simulated experiments on small satellite BP930 batteries using the MACCOR system

Data description: https://ieeexplore.ieee.org/document/7356483 
& 
https://ti.arc.nasa.gov//m/project/prognostic-repository/Description_of_Simulated_Small_Satellite_Operation_Data_Sets.pdf

---

## Other

---

### Ion Mill Etch Tool
An ion source generates ions that are accelerated through an electric field using a series of grids set at specific voltages. This creates an ion beam that travels and eventually strikes the wafer surface. Material is removed from the wafer when ions hit the wafer surface. Many different failure mechanisms can be present in this system including leaks between flowcool and ion mill chambers, electric grid wear, ion chamber wear, etc. It would be beneficial to predict where and when these failures occur and schedule downtime of these ion mills for maintenance operations.

Data description: https://www.phmsociety.org/sites/phmsociety.org/files/PHM%20Data%20Challenge%202018%20vFinal%20v2_0.pdf

Download link: https://www.phmsociety.org/events/conference/phm/18/data-challenge

---

### Filtration System
 Remaining Useful Life (RUL) of a filtration system. ‘Run-to-Failure’ data is provided with key condition monitoring parameters: flow rate, upstream pressure (before filter) and downstream pressure (after filter). Data is generated under controlled conditions, with key experimental variables of contamination particle size and concentration, i.e. solid-to-liquid ratio.

 Download link: http://phmeurope.org/2020/data-challenge-2020


