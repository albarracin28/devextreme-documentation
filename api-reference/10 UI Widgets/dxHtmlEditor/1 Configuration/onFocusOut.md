---
EventForAction: ..\4 Events\focusOut.md
default: null
type: function(e)
---
---
##### shortDescription
A function that is executed when the widget loses focus.

##### param(e): Object
Information about the event that caused the function execution.

##### field(e.component): {WidgetName}
The widget's instance.

##### field(e.element): dxElement
The widget's container. It is an [HTML Element](https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement) or a [jQuery Element](https://api.jquery.com/Types/#jQuery) when you use jQuery.

##### field(e.model): Object
The model data. Available only if you use Knockout.

##### field(e.event): event
The event that caused the function execution. It is a [dxEvent](/api-reference/50%20Common/Object%20Structures/dxEvent '/Documentation/ApiReference/Common/Object_Structures/dxEvent/') or a [jQuery.Event](https://api.jquery.com/category/events/event-object) when you use jQuery.

---
#####See Also#####
- [onFocusIn](/api-reference/10%20UI%20Widgets/dxHtmlEditor/1%20Configuration/onFocusIn.md '/Documentation/ApiReference/UI_Widgets/dxHtmlEditor/Configuration/#onFocusIn')