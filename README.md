# hana_cap_app
Get Started with SAP HANA XS Advanced Native Development

https://developers.sap.com/group.hana-xsa-cap-get-started.html

## Notes
Original name in SAP tutorial: **MyHANAApp**

It was changed to: **hana_cap_app**

This needs to be consitently changed in all of the source code.


## Features

- **interactions.cds** and **interaction_srv.cds** Core Data and Services


## Further references

Core Data and Services (CDS) Language Reference Documentation: https://help.sap.com/viewer/65de2977205c403bbc107264b8eccf4b/Cloud/en-US/855e00bd559742a3b8276fbed4af1008.html


## Troubleshooting

- Errors occurring on CDS Build as well as on running node.js application fixed by changing dependency to @sap/cds to "3.21.1" or "3.21.x" in package.json in app root as well as srv subfolder. Used HANA Express VM based on HANA 2.00 SP04.