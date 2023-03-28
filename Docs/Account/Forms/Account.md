[[_TOC_]]
# Account
Business that represents a customer or potential customer. The company that is billed in business transactions.
# Account
Updated default Account form.
| Name | Type | Description |
| --- | --- | --- |
| <a id="SUMMARY_TAB">Summary</a><br> | Tab |  |
| <a id="section">ACCOUNT INFORMATION</a><br> | Section |  |
| <a id="name">Account Name 🔑</a><br>![Button](https://img.shields.io/badge/System%20Administrator-CREATE-blue)<br>![Button](https://img.shields.io/badge/System%20Administrator-UPDATE-blue)<br>![Button](https://img.shields.io/badge/System%20Administrator-READ-blue)<br> | StringType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Type the company or business name.<br>**Modern Flows:**<br>- [Account name change notification](#f2b66020-6a81-4c5c-b6e3-47e103a21a90)<br> |
| <a id="telephone1">Phone</a><br> | StringType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Type the main phone number for this account.<br> |
|  <span style="opacity: 0.4;"><a id="telephone1">Phone</a><br></span > |  <span style="opacity: 0.4;">StringType</span ><br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Type the main phone number for this account.<br> |
| <a id="fax">Fax</a><br> | StringType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Type the fax number for the account.<br> |
| <a id="websiteurl">Website</a><br> | StringType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Type the account's website URL to get quick details about the company profile.<br> |
| <a id="parentaccountid">Parent Account</a><br> | LookupType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Choose the parent account associated with this account to show parent and child businesses in reporting and analytics.<br> |
| <a id="tickersymbol">Ticker Symbol</a><br> | StringType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Type the stock exchange symbol for the account to track financial performance of the company. You can click the code entered in this field to access the latest trading information from MSN Money.<br> |
| <a id="section">ADDRESS</a><br> | Section |  |
| <a id="address1_composite">Address 1</a><br> | MemoType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Shows the complete primary address.<br> |
| <a id="section"></a><br> | Section |  |
| <a id="section">SOCIAL PANE</a><br> | Section |  |
| <a id="section">Assistant</a><br> | Section |  |
| <a id="section">Section</a><br> | Section |  |
| <a id="primarycontactid">Primary Contact</a><br> | LookupType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Choose the primary contact for the account to provide quick access to contact details.<br> |
| <a id="DETAILS_TAB">Details</a><br> | Tab |  |
| <a id="section">COMPANY PROFILE</a><br> | Section |  |
| <a id="industrycode">Industry</a><br> | PicklistType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Select the account's primary industry for use in marketing segmentation and demographic analysis.<br> |
| <a id="sic">SIC Code</a><br> | StringType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Type the Standard Industrial Classification (SIC) code that indicates the account's primary industry of business, for use in marketing segmentation and demographic analysis.<br> |
| <a id="ownershipcode">Ownership</a><br> | PicklistType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Select the account's ownership structure, such as public or private.<br> |
| <a id="section">Description</a><br> | Section |  |
| <a id="description">Description</a><br> | MemoType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Type additional information to describe the account, such as an excerpt from the company's website.<br> |
| <a id="section">MARKETING</a><br> | Section |  |
| <a id="originatingleadid">Originating Lead</a><br> | LookupType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Shows the lead that the account was created from if the account was created by converting a lead in Microsoft Dynamics 365. This is used to relate the account to data on the originating lead for use in reporting and analytics.<br> |
| <a id="lastusedincampaign">Last Date Included in Campaign 🔒</a><br> | DateTimeType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Shows the date when the account was last included in a marketing campaign or quick campaign.<br> |
| <a id="donotsendmm">Send Marketing Materials</a><br> | BooleanType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Select whether the account accepts marketing materials, such as brochures or catalogs.<br> |
| <a id="section">CONTACT PREFERENCES</a><br> | Section |  |
| <a id="preferredcontactmethodcode">Contact Method</a><br> | PicklistType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Select the preferred method of contact.<br> |
| <a id="donotemail">Email</a><br> | BooleanType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Select whether the account allows direct email sent from Microsoft Dynamics 365.<br> |
| <a id="followemail">Follow Email</a><br> | BooleanType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Information about whether to allow following email activity like opens, attachment views and link clicks for emails sent to the account.<br> |
| <a id="donotbulkemail">Bulk Email</a><br> | BooleanType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Select whether the account allows bulk email sent through campaigns. If Do Not Allow is selected, the account can be added to marketing lists, but is excluded from email.<br> |
| <a id="donotphone">Phone</a><br> | BooleanType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Select whether the account allows phone calls. If Do Not Allow is selected, the account will be excluded from phone call activities distributed in marketing campaigns.<br> |
| <a id="donotfax">Fax</a><br> | BooleanType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Select whether the account allows faxes. If Do Not Allow is selected, the account will be excluded from fax activities distributed in marketing campaigns.<br> |
| <a id="donotpostalmail">Mail</a><br> | BooleanType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Select whether the account allows direct mail. If Do Not Allow is selected, the account will be excluded from letter activities distributed in marketing campaigns.<br> |
| <a id="section">BILLING</a><br> | Section |  |
| <a id="transactioncurrencyid">Currency</a><br> | LookupType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Choose the local currency for the record to make sure budgets are reported in the correct currency.<br> |
| <a id="creditlimit">Credit Limit</a><br> | MoneyType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Type the credit limit of the account. This is a useful reference when you address invoice and accounting issues with the customer.<br> |
| <a id="creditonhold">Credit Hold</a><br> | BooleanType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Select whether the credit for the account is on hold. This is a useful reference while addressing the invoice and accounting issues with the customer.<br> |
| <a id="paymenttermscode">Payment Terms</a><br> | PicklistType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Select the payment terms to indicate when the customer needs to pay the total amount.<br> |
| <a id="section">SHIPPING</a><br> | Section |  |
| <a id="address1_shippingmethodcode">Shipping Method</a><br> | PicklistType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Select a shipping method for deliveries sent to this address.<br> |
| <a id="address1_freighttermscode">Freight Terms</a><br> | PicklistType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Select the freight terms for the primary address to make sure shipping orders are processed correctly.<br> |
| <a id="section">CHILD ACCOUNTS</a><br> | Section |  |
| <a id="urstab">Scheduling</a><br> | Tab |  |
| <a id="section">General</a><br> | Section |  |
| <a id="address1_latitude">Latitude</a><br> | DoubleType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Type the latitude value for the primary address for use in mapping and other applications.<br> |
| <a id="address1_longitude">Longitude</a><br> | DoubleType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Type the longitude value for the primary address for use in mapping and other applications.<br> |
| <a id="section">Section</a><br> | Section |  |
| <a id="section">Section</a><br> | Section |  |
| <a id="documents_sharepoint">Files</a><br> | Tab |  |
| <a id="section">Documents Section</a><br> | Section |  |
| <a id="AssetsAndLocationsTab">Assets and Locations</a><br> | Tab |  |
| <a id="section">Assets and Locations</a><br> | Section |  |
| <a id="name">Account Name</a><br> | StringType<br>![Button](https://img.shields.io/badge/Audited-👁-red)<br> | Type the company or business name.<br>**Modern Flows:**<br>- [Account name change notification](#f2b66020-6a81-4c5c-b6e3-47e103a21a90)<br> |

# Workflows
| Name | Type | Description |
| --- | --- | --- |
| <a id="f2b66020-6a81-4c5c-b6e3-47e103a21a90">[Account name change notification](https://make.powerautomate.com/flows/f2b66020-6a81-4c5c-b6e3-47e103a21a90/details) </a> | Modern Flows<br>![Button](https://img.shields.io/badge/Scope-Organization-brightgreen)<br>![Button](https://img.shields.io/badge/Calling%20User-red)<br>![Button](https://img.shields.io/badge/Message-UPDATE-yellow)<br>Trigger:<br>- When a row is added, modified or deleted<br> | **Triggers**:<br>- [name](#name)<br>**Trigger Conditions**:<br>- [statecode eq 0](#statecode eq 0)<br> |


