---
category: minorAnalysis
---
* The heuristic to enable certain Android queries has been improved. Now it ignores Android Manifests which don't define an activity, content provider or service. We also only consider files which are under a folder containing such an Android Manifest for these queries. This should remove some false positive alerts.
