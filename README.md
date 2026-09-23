## Manual Execution of Account Territory Assignment

Salesforce territory assignment does not provide a convenient way for users to rerun assignment for an individual Account on demand; the existing process required a REST `PATCH` request. This enhancement gives users a way to trigger the assignment from Salesforce when an Account needs to be reevaluated, without preparing and sending the API request manually.

The use case is an Account whose details have changed and may now qualify for a different territory. A user initiates the action, Salesforce runs the configured territory assignment logic, and the Account’s territory assignment can be reviewed afterward.
