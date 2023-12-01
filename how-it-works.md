# How It Works

Stadium applications consist of inter-related components that are arranged and connected in such a way that specific user objectives can be achieved.

***

### Stadium applications

Stadium applications have three main areas of responsibility:

1. [_Pages_](broken-reference) contain [_controls_](.gitbook/assets/Controls) that display data and that users interact with.
2. [_Connectors_](.gitbook/assets/Connectors) connect to data sources to fetch, add or change data.
3. [_Event handlers_](broken-reference) and [_scripts_](broken-reference) (Javascript) are the glue between page controls and the connectors.
   * Event handlers and scripts use _actions_ to:
     1. Assign data from connectors to controls
     2. Retrieve data from controls to pass on to connectors
     3. Dynamically change control properties and data
   * Event handlers are triggered by [_events_](broken-reference). When events fire, they run their event handlers. Examples of events:
     * Load
     * Click
     * Change

Stadium applications are designed in [Stadium Designer](broken-reference) and hosted on [Stadium Application Manager](broken-reference).
