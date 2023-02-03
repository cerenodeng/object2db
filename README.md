# Object2db
Create or update the rows of HubDB if the custom object records of HubSpot are created or updated.

## Requirements
### Custom Object
In this example, the custom object for the events has 5 properties: topic, details, date, speakers, location. The topic is the primary display property.
### HubDB
The table of HubDB should have the respective columns like the properties of the custom object.
### Worflow
Create a workflow to have a enrollment trigger for the custome object and set triggering worflow when topic is known OR details is known and so on. And add custome code action below this trigger. In this action the secret and the property to include in code including Record ID and those 5 properties should be set.  

