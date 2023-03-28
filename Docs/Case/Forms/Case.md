[[_TOC_]]
# Case
Service request case associated with a contract.
# Case
Updated default Case form.
| Name | Type | Description |
| --- | --- | --- |
| <a id="general">Summary</a><br> | Tab |  |
| <a id="section">CASE DETAILS</a><br> | Section |  |
| <a id="title">Case Title</a><br> | StringType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Type a subject or descriptive name, such as the request, issue, or company name, to identify the case in Microsoft Dynamics 365 views.<br>**Modern Flows:**<br>- [Notify case handlers that a case is created](#87cf621d-337e-4e4f-9dd7-905f6eddb4a0)<br> |
| <a id="ticketnumber">ID 🔒</a><br> | StringType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Shows the case number for customer reference and searching capabilities. This cannot be modified.<br> |
| <a id="subjectid">Subject</a><br> | LookupType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Choose the subject for the case, such as catalog request or product complaint, so customer service managers can identify frequent requests or problem areas. Administrators can configure subjects under Business Management in the Settings area.<br> |
| <a id="customerid"><div>Customer <span style="color: red;">*</span></div></a><br> | CustomerType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Select the customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.<br> |
| <a id="caseorigincode">Origin</a><br> | PicklistType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Select how contact about the case was originated, such as email, phone, or web, for use in reporting and analysis.<br> |
| <a id="primarycontactid">Contact</a><br> | LookupType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Select a primary contact for this case.<br> |
| <a id="entitlementid">Entitlement</a><br> | LookupType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Choose the entitlement that is applicable for the case.<br> |
| <a id="productid">Product</a><br> | LookupType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Choose the product associated with the case to identify warranty, service, or other product issues and be able to report the number of incidents for each product.<br> |
| <a id="section">DESCRIPTION</a><br> | Section |  |
| <a id="description">Description</a><br> | MemoType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Type additional information to describe the case to assist the service team in reaching a resolution.<br> |
| <a id="section">APPLICABLE SLA</a><br> | Section |  |
| <a id="responseby">First Response By 🔒</a><br> | DateTimeType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | For internal use only.<br> |
| <a id="resolveby">Resolve By 🔒</a><br> | DateTimeType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Enter the date by when the case must be resolved.<br> |
| <a id="section">Route Case</a><br> | Section |  |
|  <span style="opacity: 0.4;"><a id="routecase">Route Case 🔒</a><br></span > |  <span style="opacity: 0.4;">BooleanType</span ><br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Tells whether the incident has been routed to queue or not.<br> |
| <a id="section">TABS CONTROL</a><br> | Section |  |
| <a id="section">Assistant</a><br> | Section |  |
| <a id="section">CUSTOMER DETAILS</a><br> | Section |  |
| <a id="CASERELATIONSHIP_TAB">Case Relationships</a><br> | Tab |  |
| <a id="section"></a><br> | Section |  |
| <a id="section">RESEARCH</a><br> | Section |  |
| <a id="section"></a><br> | Section |  |
| <a id="section"></a><br> | Section |  |
| <a id="AssociatedKnowledgeBaseRecords">Associated Knowledge Records</a><br> | Tab |  |
| <a id="section"></a><br> | Section |  |
| <a id="section"></a><br> | Section |  |
| <a id=" Enhanced_SLA_Details_Tab">Enhanced SLA Details</a><br> | Tab |  |
| <a id="section">APPLICABLE SLA</a><br> | Section |  |
| <a id="section"></a><br> | Section |  |
| <a id="ADDITIONALDETAILS_TAB">Additional Details</a><br> | Tab |  |
| <a id="section"></a><br> | Section |  |
| <a id="casetypecode">Type</a><br> | PicklistType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Select the type of case to identify the incident for use in case routing and analysis.<br> |
| <a id="parentcaseid">Parent Case</a><br> | LookupType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Choose the parent case for a case.<br> |
| <a id="section"></a><br> | Section |  |
| <a id="isescalated">Escalated</a><br> | BooleanType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Indicates if the case has been escalated.<br> |
| <a id="escalatedon">Escalated On</a><br> | DateTimeType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Indicates the date and time when the case was escalated.<br> |
| <a id="section"></a><br> | Section |  |
| <a id="followupby">Follow Up By</a><br> | DateTimeType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Enter the date by which a customer service representative has to follow up with the customer on this case.<br> |
| <a id="firstresponsesent">First Response Sent</a><br> | BooleanType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Indicates if the first response has been sent.<br> |
| <a id="SOCIALDETAILS_TAB">Social Details</a><br> | Tab |  |
| <a id="section"></a><br> | Section |  |
| <a id="socialprofileid">Social Profile 🔒</a><br> | LookupType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Unique identifier of the social profile with which the case is associated.<br> |
| <a id="messagetypecode">Received As 🔒</a><br> | PicklistType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Shows whether the post originated as a public or private message.<br> |
| <a id="section"></a><br> | Section |  |
| <a id="influencescore">Influence Score 🔒</a><br> | DoubleType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Will contain the Influencer score coming from NetBreeze.<br> |
| <a id="sentimentvalue">Sentiment Score 🔒</a><br> | DoubleType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Value derived after assessing words commonly associated with a negative, neutral, or positive sentiment that occurs in a social post. Sentiment information can also be reported as numeric values.<br> |
| <a id="section"></a><br> | Section |  |
| <a id="blockedprofile">Blocked Profile 🔒</a><br> | BooleanType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Details whether the profile is blocked or not.<br> |
| <a id="KBARTICLE_TAB">Articles and Contract Information</a><br> | Tab |  |
| <a id="section">ARTICLES</a><br> | Section |  |
| <a id="kbarticleid">Knowledge Base Article</a><br> | LookupType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Choose the article that contains additional information or a resolution for the case, for reference during research or follow up with the customer.<br> |
| <a id="section">CONTRACT</a><br> | Section |  |
| <a id="contractid">Contract</a><br> | LookupType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Choose the service contract that the case should be logged under to make sure the customer is eligible for support services.<br> |
| <a id="contractdetailid">Contract Line</a><br> | LookupType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Choose the contract line that the case should be logged under to make sure the customer is charged correctly.<br> |
| <a id="productserialnumber">Serial Number</a><br> | StringType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Type the serial number of the product that is associated with this case, so that the number of cases per product can be reported.<br> |
| <a id="contractservicelevelcode">Service Level</a><br> | PicklistType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Select the service level for the case to make sure the case is handled correctly.<br> |

# Business process flows
## <a id="0ffbcde4-61c1-4355-aa89-aa1d7b2b8792">Phone to Case Process</a>
| Identify | Resolve | Research |
| --- | --- | --- |
| -[customerid](#customerid)<br>-[primarycontactid](#primarycontactid)<br>-[existingcase](#existingcase)<br>-[](#)<br>-[ownerid](#ownerid) || -[customerid](#customerid)<br>-[primarycontactid](#primarycontactid)<br>-[existingcase](#existingcase)<br>-[](#)<br>-[ownerid](#ownerid) || -[customerid](#customerid)<br>-[primarycontactid](#primarycontactid)<br>-[existingcase](#existingcase)<br>-[](#)<br>-[ownerid](#ownerid) |

# Workflows
| Name | Type | Description |
| --- | --- | --- |
| <a id="87cf621d-337e-4e4f-9dd7-905f6eddb4a0">[Notify case handlers that a case is created](https://make.powerautomate.com/flows/87cf621d-337e-4e4f-9dd7-905f6eddb4a0/details) </a> | Modern Flows<br>![Button](https://img.shields.io/badge/Scope-Organization-brightgreen)<br>![Button](https://img.shields.io/badge/Calling%20User-red)<br>![Button](https://img.shields.io/badge/Message-UPDATE-yellow)<br>Trigger:<br>- When a row is added, modified or deleted<br> |  |


