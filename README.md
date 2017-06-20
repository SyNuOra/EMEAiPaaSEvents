# EMEAiPaaSEvents
Log and Track EMEA iPaaS Events

This project supports the development of a **iPaaS Event Tracking Application** for the EMEA region. The application should present a front end for data entry, reporting, visualizations such as calendar views, and be mobile accessible.

The current platform to host this with be **Oracle Application Express**

The application should support the following data capture:

**Campaigns** - Product Marketing Campaigns 
 * Code
 * Name
 * Description
 * Goals
 * Start Date
 * End Date
 * Region (optional)
 * Country (optional)
 
**Entities** - Customers, Partners or Organizations
 * Identifier
 * Name
 * Industry (code)
 * Type [Customer, Partner, User Group]
 * Country (code)
 
 **Contacts** - Contacts for an Entitiy, and contact information
 * Identifier
 * First Name
 * Last Name
 * Email
 * Telephone
 * Mobile
 * Country (code)
 * Prefered method of contact [Email, Tel., Mobile]
 
 **Products or Services** - List of Products or Cloud Services
 * Identifier
 * Name
 * Description
 * Type [Cloud, OnPremise]
 
 **Sessions** - A list of available sessions for Events
 * Identifier
 * Name
 * Status [Development, Live, Retired]
 
 **Events** - A list and time table of Events
 * Identifier
 * Name
 * Country (code)
 * Date (Start/End?)
 * Address
 
 **Event Sessions** - A list of sessions for an Event
 * Identifier
 * Event Identifier
 * Session Identifier
 
 **Event Attendees** - A list of contacts attending / registered for and event
 * Identifier
 * Event Identifier
 * Event Session Identifier (monitor at the session level or Event level?)
 * Contact Identifier
 
 **Attendess Interest** - A list of Products or Services that an attendess has shown interest for further information
 * Event Attendee Identifier
 * Product / Service Identifier
 * Prefereed Method of contact
