# Case 01: Windows Registry Analysis


## Case Overview
This case examines Windows Registry artifacts to support user activity and system configuration analysis.


## Objective
The objective of this analysis is to identify relevant registry artifacts and interpret their forensic significance.

## Tools Used
- FTK Registry Viewer
- EnCase (analysis only)
- Open-source registry analysis utilities

## Evidence Source
Publicly available CFReDS Windows Registry datasets were used for this analysis.

## Methodology
This analysis was conducted using publicly available Windows Registry hive datasets obtained from the NIST CFReDS repository. All registry hives were examined in a read-only manner to preserve data integrity.

Analysis focused on user-centric registry artifacts commonly used in Windows forensic investigations, including RecentDocs, UserAssist, Run and RunOnce keys, and ShellBag data. These artifacts were examined to identify indicators of user activity, program execution, and persistence mechanisms.

Findings were interpreted within the context of known Windows registry behavior and correlated where possible to support investigative conclusions. No attempt was made to modify, repair, or recover deleted registry data beyond standard parsing techniques.


## Key Findings
(Findings will be documented after analysis is complete.)

## Limitations
This analysis is limited to the artifacts available within the provided dataset.

## Next Steps
Future analysis will include cross-tool validation and timeline correlation.

