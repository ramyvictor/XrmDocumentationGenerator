::: mermaid
classDiagram
Case
Case *-- Case : incidentid-existingcase
Case *-- Case : incidentid-masterid
Case *-- Case : incidentid-parentcaseid
Case *-- Account : accountid-customerid
Case *-- Contact : contactid-responsiblecontactid
Case *-- Contact : contactid-customerid
Case *-- Contact : contactid-primarycontactid
Case *-- Case : incidentid-existingcase
Case *-- Case : incidentid-masterid
Case *-- Case : incidentid-parentcaseid
class Account{
accountid
primarycontactid
masterid
parentaccountid
}
class Contact{
contactid
masterid
parentcustomerid
}
class Case{
incidentid
customerid
responsiblecontactid
primarycontactid
existingcase
masterid
parentcaseid
}

