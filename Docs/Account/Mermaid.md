::: mermaid
classDiagram
Account
Account *-- Account : accountid-parentaccountid
Contact *-- Account : accountid-parentcustomerid
Account *-- Account : accountid-masterid
Case *-- Account : accountid-customerid
Account *-- Contact : contactid-primarycontactid
Account *-- Account : accountid-masterid
Account *-- Account : accountid-parentaccountid
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
customerid
responsiblecontactid
primarycontactid
}

