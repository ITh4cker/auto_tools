local_script_classifier
===============
remember to empty the directory 'salineup_for_script_malware\\result' or drag it out each time you use it!

[local_script_classifier] is a automatic tool to detect whether a script file is based on local environment.

Usage:
------
type "python local_script_classifier.py srcfolder_path" in command window

In the directory:
-------------------------
- [local_script_classifier.py]:to implement both the two functions below.

Product:
-------------------------
- [SAL.log]:generated by [salineup_for_script_malware] to show details of detection.
- [report.csv]:generated by [local_script_feature.py].

News
----
- 2016-12-14:separate behaviour_report_helper
- 2016-12-1:rewrite the local_script.py in the mind of OOP
- 2016-11-21:implement the local_script.py v1.0