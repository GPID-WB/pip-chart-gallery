## Publishing instructions  
This document is currently published on the internal PositConnect server. The 
shareable URL is [https://datanalytics-int.worldbank.org/pip-chart-gallery/](https://datanalytics-int.worldbank.org/pip-chart-gallery/)

The published document is linked to this Github directory. In order to update
it, please follow these steps:  

1. Make changes locally  
2. Update the `manifest.json` file by running `rsconnect::writeManifest()`  
3. Commit your changes  
4. The PositConnect server periodically checks for changes to the `manifest.json`  
in this repo, and will update the published version if changes are found.
5. You can also update the published version manually by navigating to the app
dashboard: [https://datanalytics-int.worldbank.org/connect/#/apps/df03e01e-e804-450b-b0c2-37900506b0e6/info/101](https://datanalytics-int.worldbank.org/connect/#/apps/df03e01e-e804-450b-b0c2-37900506b0e6/info/101)
and clicking the "Update now" button.  
 ![posit-connect-screenshot](/images/positconnect-git-update.png)