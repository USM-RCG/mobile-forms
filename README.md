# ODK Forms
===========

Form definitions used by the CIMS Bioko software system. They define the tablet
data collection interface on the tablet, and are employed by the CIMS using ODK
Collect and ODK Aggregate as components.

While the structure of the form definitions are critical to the operation of the
CIMS, forms currently aren't known to any of the custom CIMS software, tablet or
server. Instead, they are deployed using stock ODK software and integration
tools transmit data collected to the custom CIMS software.


## Usage

To use these form definitions, you need to deploy them to the ODK Aggregate
server deployed along with the CIMS. Once deployed, tablet users can then
configure their ODK Collect applications to use that Aggregate server and
download them as empty forms. Once downloaded, the cims-tablet application can
successfully communicate with ODK Collect to orchestrate the data entry process.
