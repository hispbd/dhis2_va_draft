# dhis2_va_draft

**DHIS2 metadata repository** of the openVA (Open Verbal Autopsy) module including a guide to install DHIS2 metadata in production environments (or on a demo server), a Development Manual and and a Technical Implementation Manual for interfacing with the module in the `docs` folder.

A _module_ is a term used to describe a set of Metadata objects (like programs, data elements, ...), scripts to maintain/install the module and all its documentation.

## Getting started

The folder `docs` contains the following guides:

- `Installation.md` provides a step-by-step guide to install the module on an existing DHIS2 instance
- `Technical-Implementation.md` specifies interfacing with third party systems (i.e. OpenVA Pipeline) via DHIS2's Web API
- `Dev-Setup.md` describes how to set up a development environment for a) interfacing with the module via third party systems and b) for further development of this module
- `Demo-Setup.md` describes how to populate a prepared server with dummy VA events

Currently supported DHIS2 versions:

- 2.25
- 2.26-2.27 (not tested but will probably work)
- 2.28 (needs adjustments)

Current status: in development

## Licence
GNU General Public License v3.0
