# Automated-Error-Handling
This project focuses on streamlining incident response by mapping naming conventions across CTWO workflows and Jira process names. The goal was to support a Power Automate solution that monitors error email alerts, automatically creates Jira tickets with relevant information, and triggers a restart of the associated CTWO workflow.

🔧 Key Features:

Analyzed naming inconsistencies across CTWO and Jira to build a unified mapping.

Designed a Power Automate flow that:

Listens for error emails,

Auto-generates Jira tickets with mapped details,

Attempts to restart the failed workflow via a CTWO custom connector.

Implements a feedback loop: If the automation fails again, it updates the Jira ticket to flag for manual review.

This automation significantly reduces the time spent by operations teams manually scanning emails and handling routine restarts, enabling faster and more consistent incident response.
