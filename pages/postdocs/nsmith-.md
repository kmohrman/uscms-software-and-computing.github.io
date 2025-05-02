---
layout: postdoc
pagetype: postdoc
shortname: nsmith-
permalink: /postdocs/nsmith-.html
postdoc-name: Nick Smith
title: Post-doctoral researcher
active: False
dates:
  start: 2022-01-01
  end: 2024-01-01
photo: /assets/images/team/Nick-Smith.jpg
institution: Fermilab
e-mail: nick.smith@cern.ch
project_title: Object Storage for CMS in the HL-LHC era
project_goal: >
    Demonstrate feasability of using Ceph object store technology to store and retrieve CMS event data products at a finer granularity than file-level.
    Benchmark storage usage and analysis access performance and compare to traditional file-level storage solutions.
mentors:
  - Bo Jayatilaka (Fermilab)
  - David Mason (Fermilab)

proposal: /assets/pdfs/Jayatilaka_USCMSpostdoc_proposal.pdf
finalreport: /assets/pdfs/NickSmith_RD_FinalReport.pdf
presentations:
  - title: "Object Stores for CMS data"
    date: 2023-11-08
    url: https://indico.cern.ch/event/1341608/contributions/5648183/attachments/2748905/4784080/ncsmith-blueprint-objectstores.pdf
    meeting: S&C Blueprint Meeting - USCMS Storage R&D
    meetingurl: https://indico.cern.ch/event/1341608/
    record: 
    focus-area: Storage
  - title: "A Ceph S3 Object Data Store for HEP"
    date: 2023-05-09
    url: https://indico.jlab.org/event/459/contributions/11308/
    meeting: CHEP 2023
    meetingurl: https://indico.jlab.org/event/459
    record: 
    focus-area: Storage
  - title: "Ceph S3 Object Storage for CMS data"
    date: 2022-10-27
    url: https://indico.cern.ch/event/1106990/contributions/5097031/
    meeting: ACAT 2022
    meetingurl: https://indico.cern.ch/event/1106990/
    record: 
    focus-area: Storage
  - title: "Object Stores for CMS data: initial presentation"
    date: 2022-02-22
    url: https://indico.cern.ch/event/1131679/contributions/4748741/attachments/2396026/4096861/ncsmith-uscms-objectstores.pdf
    meeting: HL-LHC R&D Initiative Meeting
    meetingurl: https://indico.cern.ch/event/1131679/
    record: 
    focus-area: Storage
current_status: >
  In progress. Single- and multi-client scaling tests of the Ceph object service were presented at CHEP, proceedings to be posted. Now working with CMSSW Core Framework team and RNTuple developers to integrate RNTuple into CMSSW, to leverage RNTuple object storage backend capabilities rather than writing a custom implementation. An automated data ingestion system demonstrator is being developed, where FTS transfers files directly to the S3 endpoint, which then triggers a conversion routine to explode the files into the object data format.
---
