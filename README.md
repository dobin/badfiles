# badfiles

List of dangerous or potentially malicious file extensions.

Used for: 
* Content Filter Proxy blacklist
* Content Filter Proxy checks
* [Waasa](https://github.com/dobin/waasa)

Check it at: [badfiles.ch](https://github.com/dobin/badfiles)


## Where is the data coming from?

* [filesec.io](https://filesec.io) list
* [govcert.ch](https://govcert.ch/downloads/blocked-filetypes.txt) list 
* IOProtect.ch list
* Microsoft [Blocked attachments in Outlook/Onenote/Teams
](https://support.microsoft.com/en-us/office/blocked-attachments-in-outlook-434752e1-02d3-4e90-9124-8b81e49a8519)
* [michalzobec List of blocked file extensions](https://github.com/michalzobec/Security-Blocked-File-Extensions-Attachments)
* ChatGPT
* Me
* [Chrome Safe Browsing list](https://github.com/chromium/chromium/blob/main/components/safe_browsing/content/resources/download_file_types.asciipb)

MITRE Initial Access and MITRE Execution is done based on my CTI. 

The main reference file is located in the Waasa project at [info.yaml](https://github.com/dobin/waasa/blob/master/waasa/Data/info.yaml).
badfiles.ch is just a viewer. Check the waasa project more more information about the data sources.


## Dat Files

* `info.yaml`: List of bad file extensions as yaml
* `info.json`: `info.yaml` converted to json
