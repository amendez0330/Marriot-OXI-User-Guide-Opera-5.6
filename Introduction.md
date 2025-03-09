
This Guide provides instructions on how to make the necessary configuration changes in the OXI Interface to meet the standards set for by Marriott for OPERA version 5.6.
The purpose of this document is to ensure a consistent and concise OXI configuration for the MARSHA Interface, the Marriott SGI Interface, and the Marriott MIMPG Interface. Most of the OXI configuration will come pre-defined with the OXI Shell/Insert scripts.
The MARSHA, SGI, and MIMPG interfaces must be marked as Inactive until the day the hotel is scheduled to go live, or until the property is opened. 
This will prevent unnecessary business events from being created and filling up the business event queues. 
These queues have been known to not start properly if there are too many pending events. If this is the case, Oracle will need to purge this table and delete the pending business events.
This guide will make distinctions between settings when there is a difference between on property OPERA (OPO) and above property OPERA (APO).
