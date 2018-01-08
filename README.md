# ODK Forms

Form definitions used by the CIMS Bioko software system. They define the primary
data collection interface on the tablets and they are employed by the CIMS using
ODK Collect.  

Forms are deployed using CIMS server, which provides a compatible protocol that
allows stock ODK tools like Briefcase and Collect to download forms and submit
form instances from/to the custom CIMS server software.

## Usage

To use these form definitions, you need to deploy them to CIMS server. Once
deployed, tablet users can configure their ODK Collect applications to use that
server and download them as empty forms. Once downloaded, the cims-tablet
application will be able to communicate with ODK Collect to orchestrate the data
entry process.
