
# ConditionalBuilder

The `ConditionalBuilder` widget allows you to dynamically display different widgets based on certain conditions (either [single](/advanced-functionality/conditional-logic#single-condition) or [multiple](/advanced-functionality/conditional-logic#multiple-conditions-and-or)). Using this widget, you can define different conditions, each associated with a specific widget to be displayed when that condition is true. It's like having a switch that shows different things depending on what's happening in your app.

For example, displaying different charts based on user roles. For team members, an individual progress chart can be shown. Team leads can view the overall progress of the entire team, while project managers can see over project progress chart. Just like the below:

![img.png](../../resources/ui-building-blocks/components/built-in-components/img.png)

## Adding ConditionalBuilder widget

To add the `ConditionalBuilder` widget to your app:

1. Add the **ConditionalBuilder** widget (from the **Base Elements**) to where you want to display dynamic widgets.
5. Move to the **Properties Panel** **>** **Conditional Builder Properties,** andUnder the **First Condition**, provide the **IF** [condition](/advanced-functionality/conditional-logic) by clicking on **UNSET**.
8. Now, besides the **THEN**, click **Empty**. This will automatically select the **IF** widget in the widget tree. Inside that, add a widget that you want to display if this condition is true.
11. To add one more condition-based widget, click on the "+" button, add a condition for the **ELSE IF** section, and add a widget inside the **Else If** widget in the widget tree.
14. If none of the conditions are satisfied, add a default widget to display inside the **Else** widget.
17. Use the **Show In UI Builder** option to see that particular widget in the [canvas area](/getting-started/ui-builder/canvas-area). You can see only one widget at a time.

<div class="video-container"><iframe src="https://www.loom.
com/embed/fe8edb48bdf744abab13f3ba7f925c5c?sid=85533669-195d-4f5e-aeae-029ceee40cb5" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></div>

