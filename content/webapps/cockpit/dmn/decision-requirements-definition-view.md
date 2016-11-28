---

title: 'Decision Requirements Definition View'
weight: 10

menu:
  main:
    identifier: "user-guide-cockpit-drd-definition"
    parent: "user-guide-cockpit-dmn"
    pre: "Gain an aggregated overview over all instances of a deployed decision requirement definition"

---

{{< img src="../../img/cockpit-decision-requirements-definition-view.png" title="Decision Requirements Definition View" >}}

On the decision requirements definition view, you can find a diagram of the deployed decision requirements definition.
Use the mouse to navigate through the diagram.
By turning the mouse wheel you can zoom in out.
Hold the left mouse button to pan the diagram in the desired direction.
By clicking on decision definition you can filter instances in table below by key of selected definition. 
You can also select multiple decision definition while holding control key.

When decision definition is either decision table or literal expression
green icon is displayed in top left corner of decision definition element on diagram.
By clicking it you can navigate to [decision-definition-view]({{< relref "webapps/cockpit/dmn/decision-definition-view.md" >}}).

Furthermore, the decision requirements definition view provides you with information about
the definition. On the left side you can easily survey the versions of the definition requirements definition.
The version of the decision requirements definition can be changed in the dropdown menu. The diagram is then updated accordingly.
Clicking on the deployment ID will take you to the [deployment view]({{< relref "webapps/cockpit/deployment-view.md" >}}).

Below the diagram you find a decision instances tab and decision requirements definition instances tab.

{{< img src="../../img/cockpit-decision-definition-requirement-decision-instances-tab.png" title="Decision Instances Tab" >}}

In decision instances tab you find listing of all decision instances for this definition. 
If the decision instance was executed in the context of a process, you can also find 
the process definition as well as the process instance id that executed that specific 
decision instance. Clicking on the links takes you to the respective pages.
Same principle applies also to cases definition and case instance.
Clicking on the id of the decision instance takes you to the [decision instance view]({{< relref "webapps/cockpit/dmn/decision-instance-view.md" >}}).
Clicking on the decision definition takes you to the [decision definition view]({{< relref "webapps/cockpit/dmn/decision-definition-view.md" >}})

{{< img src="../../img/cockpit-decision-definition-requirement-decision-drd-tab.png" title="Decision Requirements Definition Instances Tab" >}}

In decision requirements definition instances tab you find listing of all instances of current decision requirements definition. 
If the instance was executed in the context of a process, you can also find 
the process definition as well as the process instance id that executed that specific 
decision instance. Clicking on the links takes you to the respective pages.
Same principle applies also to cases definition and case instance.
Clicking on the id of the instance takes you to the [decision requirements definition instance view]({{< relref "webapps/cockpit/dmn/decision-requirements-instance-view.md" >}}).
Clicking on the decision definition takes you to the [decision definition view]({{< relref "webapps/cockpit/dmn/decision-definition-view.md" >}})