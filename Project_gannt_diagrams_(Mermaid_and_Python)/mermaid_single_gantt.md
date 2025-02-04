```mermaid
%%{
    init: {
        "fontSize": 12,
        "gantt": {
            "fontSize": 11, 
            "sectionFontSize": 14,
            "topAxes": true,
            "barHeight": 12,
            "topPadding": 50
            } 
    } 
}%%
gantt

dateFormat  YYYY-MM-DD
axisFormat  %d-%b-%y
todayMarker on
title POLI Annual Plan

section  Instrumentation
Monochromator shielding                        : 2022-08-01,2022-11-01
%% Cleaning up           : 2022-08-01,2022-08-10
%% Open shielding        : 2022-08-11,2022-08-12
%% Test flipping         : 2022-08-12,2022-08-20
%% Minor modification    : 2022-08-20,2022-08-31
%% Close shielding       : 2022-09-01,2022-10-01
BIDIM 2D detector A                        : 2022-10-01,2022-12-15
BIDIM 2D detector B                        : 2023-04-01,2023-07-31
SEOP analyser                              : 2022-11-01,2022-12-15
Piezo slit A                               : 2022-12-15,2023-02-01
Piezo slit B                               : 2023-03-01,2023-03-31
SEOP polarier                              : 2023-04-15,2023-05-15
Design connector for SEOP and CryoPAD      : 2023-05-01,2023-05-31

section Other improvements
POLI documentation                         : 2022-09-01,2022-10-31
DigitalTwin                                : 2022-11-01,2022-12-15
Lab course training materials              : 2022-12-15,2023-03-31
Visit D3@ILL?                              : des1, 2023-01-01, 14d
Software improvements (after the visit)    : after des1, 0d

section Research
ISIS Beamtime A                            : 2022-11-23,2022-12-01
Preparation and data analysis              : 2022-11-01,2022-12-15
ISIS Beamtime B                            : 2023-02-27,2023-03-05
Preparation and data analysis              : 2023-02-01,2023-03-15
Neutron proposal (D3@ILL)                  : 2022-09-07, 0d
New samples and experiments                : 2023-01-01, 0d
Paper reading and publishing               : 2023-01-01, 0d
Grant applications                         : 2023-01-01, 0d

section Conferences and workshops
JCNS workshop 2022                        : 2022-10-11, 2022-10-14
French-German workshop                    : 2022-11-21, 2022-11-22
MLZ user meeting                          : 2022-12-07, 2d
European Conference on Neutron Scattering : 2023-03-20, 2023-03-23
The Joint European Magnetic Symposia 2023 : 2023-08-27, 2023-09-01
```
