# [PatientProfiler](https://agstn.github.io/PatientProfiler/PatientProfiler.html)

This [months (Presented on **June 8thth, 2022**) Wonderful-Wednesdays]( https://github.com/VIS-SIG/Wonderful-Wednesdays/tree/master/data/2022/2022-06-08) challenge was to design a visual patient listing o patient profile. For this challenge, my goal was to develop a proof-of-concept table, where it will be possible to combine different sources of information for all participants to a clinical trial. The result is achieved by creating a highly nested dataset rendered with [reactable]( https://glin.github.io/reactable/). Data for this proof-of-concept table are in ADaM format following the [CDISC pilot data and documents]( https://github.com/phuse-org/phuse-scripts/tree/master/data/adam/cdiscpilot01)
-	ADSL:		Subject Level Structure
-	ADAE:		Adverse Events
-	ADCM:	Concomitant Medications
-	ADLBC:	Patient chemistry lab measurements
-	ADLBH:	Patient hematology lab measurements
-	ADLBHY:	Patient lab measurements - Hy rules.
-	EX:		Patient exposure  

In order to explore different possibilities, sparklines are generated with [sparkline](https://cran.r-project.org/web/packages/sparkline/index.html) or [react_sparkline](https://kcuilla.github.io/reactablefmtr/articles/sparklines.html) the former allowing the display of normal ranges, while the later, doesn’t have those capability without extra coding. I mention this because the goal of my efforts was not on working all the details need it for clinical use but on how to generate highly nested dataset into a single table. 

<img src="https://raw.githubusercontent.com/agstn/PatientProfiler/main/PatientProfiler.png" width="100%" height="100%">
