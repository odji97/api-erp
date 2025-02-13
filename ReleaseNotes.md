# Release 1.3.24
* add missing link on fhirversion_changes.adoc

# Release 1.3.23
* added missing KBV Profiles that were declared as deprecated but moved to FOR

# Release 1.3.22
* added missing Profiles in transition files for compare_results

# Release 1.3.21
* fixed an issue where "compare_results" would be in the wrong location

# Release 1.3.20
erp_fhirversion_changes.adoc
* fixed links and content for hapi validator compare results

# Release 1.3.19
erp_fhirversion_changes.adoc
* added preview präfix to show rendered html

# Release 1.3.18
readme.md
* added link to erp_fhirversion_changes.adoc

# Release 1.3.17
added erp_fhirversion_changes.adoc
* comparison of profiles
* comparison results
erp_fhirversion
* discalaimer update
* details update

# Release 1.3.15
pkv_ik_numbers.adoc
* added info of new destination of pkv-ik-list
erp_chargeItem.adoc
* updated examples for chargeitem page

# Release 1.3.14
 erp_charg‎eItem.adoc
* fixed signature in examples
* fixed reference issues
* fixed escaped pipes in examples

# Release 1.3.13
Fix github build script

# Release 1.3.12
Fix for image reference

# Release 1.3.11
Fixes for puml images

# Release 1.3.10
Hinzufügen der API Beschreibung für die Alternative Zuweisung an die Apotheke

# Release 1.3.9
Korrektur des Link für TI-Lagebild zum Probing per API

# Release 1.3.8
* Beispiel für User-Agent bei der Authentisierung korrigiert
* Hinzufügen und Beschreibung des TI-Lagebild zum Probing per API

# Release 1.3.7
* fixed description for IncludeRevocationInfo
*  corrected note about IncludeRevocationInfo=false
* updated releasenotes for KBV and Gematik Erezept workflow package
* updated errorcodes für eRezept deletion
* updated text for errorcode 403 in $abort
* updated pkv update list

# Release 1.3.6
* updated releasenotes for KBV and gematik Erezept workflow packages 
* corrected wording about tageslimit for einlösen mit egk

# Release 1.3.5
* updated pkv-ik numbers list

# Release 1.3.4
* updated pkv-ik numbers list

# Release 1.3.3
* corrected errorcodes for $abort operations

# Release 1.3.2
* added Healthcheck doku
* internal refactoring to use includes
* better fhir timeline details
* altered vau image description

# Release 1.3.1
Fixed formatting bug in 'erp_steuerung_durch_le'

# Release 1.3.0
Verbesserung der Fehlerbeschreibung für Fehlercode 403 in erp_abrufen_egk

# Release 1.2.9
Verbesserungen an Api Beschreibung eGK in der Apotheke

# Release 1.2.7
- FHIR Version Timeline
- Api Beschreibung EGK in der Apotheke
- Updated Link zu TA7 Anlage 2 des GKV SV

# Release 1.2.6
- revert latest release
- gitub doe not support include action from adoc

# Release 1.2.5
- Herauslösung von Beispiel requests und responds
- Ersetzung von Links auf korrekte Umgebung

# Release 1.2.4
Changes

- updated CodeSystem, NamingSystem, Profile, Extensions-URLs
- added Api Description zytostatika
- renaming of Link from https://simplifier.net/erezept-abrechnungsinformationen/ to https://simplifier.net/erezept-patientenrechnung/
- corrected request  in 'Abrechnungsinformationen für Versicherte ändern' 

# Release 1.2.3
Changes

- fixed some old links to simplifier.net

- updated old canonicals
 
- fixed post request in ChargeItem

- updated statuscodes document


# Release 1.2.2
Changes

- new version of document "Signatur der Abrechnungsinformation"

# Release 1.2.1
Changes

Fixed the layout of the frontpage


# Release 1.2.0
New Feature

PKV: Use cases for private insured

- Description of handling the electronic billing data with “ChargeItem” resource

- Description of handling the consent with “Consent” resource

- Publish a list of private IK-Numbers


Changes

- update on FHIR versioning in the versions overview

- bug fixing of a response status code of the authenticate request in notification_avs



# Release 1.1.9
Updated docs/erp_fhirversion.adoc with PKV ChargeItem informations

# Release 1.1.8
Added Information on RU-configuration for FHIR-profiles support in ePrescrioption backend

# Release 1.1.7
Update FHIR-release management
Overview http-statuscodes ePrescription-backend
Overview multiple prescriptions
Update sample prescriptions and other corrections

# Release 1.1.6
New Feature

- new document with status and error codes ‘erp_statuscodes’

Changes

- edited some error codes
- update on FHIR versioning in the versions overview
- bug fixing in notification document
- added code example in notification_avs
- added kbv blanko example

# Release 1.1.5
New Feature

- new PoC for verification of an prescription receipt signature outside the TI


Changes

- fixed example of request in $close-operation

- fixed get request of messages in an certain time range

# Release 1.1.4
Changes

- Update on FHIR-Profile overview

- APOVZD-interface switched from Organization (draft 2021) to Location (as used)

- Minor fixes on API-Parameters

# Release 1.1.3
New Feature PKV (private health insurance)
 
- added description on new workflowtype “200” for “pkv”. Described how to start the workflow for patients with private health insurance ($create-Operation) and what to do when finishing the workflow ($close-Operation)
 
- other functions and interfaces will follow in later releases
 

Changes
 
- update in FHIR-Realeses: added Release notes for 01.01.2022 in “DAV” line
 
- updated version numbers of examples
 
- updated and fixed examples
 

# Release 1.1.2
- added close-Operation with several MedicationDispenses 
 
- minor version fixes on examples
 
- added some notes
 


# Release 1.1.1
- fixed examples of receipt Bundle
 
- updated endpoint names
 
- updated version number of KBV canonicals in examples
 
- updated information in versioning management
  
- updated request and response in chapter for VAU-authentication
 
- fixed response of get/Bundle as patient, the endpoint in signature.who was wrong
 
- style fixes for images
 

