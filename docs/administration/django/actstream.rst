Actstream (Activity Stream)
===========================

Actions
^^^^^^^

Exchange uses Django Activity Stream, which creates a list of activities generated by the actions on your site, and allows you to quickly visualize who is performing what actions. An action is a description of an action that was performed (Verb) at some instance in time by some Actor on some optional Target that results in an Action Object getting created/updated/deleted.

Action events are categorized by four main components.

  * Actor - The user who performed the activity.
  * Verb - The verb phrase that identifies the action of the activity, such as created or deleted.
  * Action Object - The object linked to the action itself, such as a layer or a map.
  * Target - The object to which the activity was performed. Currently, Exchange is not using this component.

For example: admin (actor) uploaded (verb) a layer (object) 12 hours ago.

1. Click Actions in the Actstream menu on the Django site administration page.

  .. figure:: img/actstream.png

All of the actions that have taken place within Exchange will be listed, along with who performed it (actor), and what they did (verb). The target and whether or not the action is public is also listed, but they are not used at this time.

2. Click on an action to view more details.

  .. figure:: img/actions.png