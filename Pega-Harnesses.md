# Pega-Harnesses

**Harnesses organize the content and structure of a portal**
Harnesses are instances of the Rule-HTML-Harness and define the run-time form of your UI. In a user portal, Harnesses define the layout of the screen that the user
sees. For example a harness can divide the portal into three separate areas (header,navigation pane, and large content pane for displaying documents).

Each Area of Harness references a section. Even if you update the section the harness doesn't change.

There are several OOTB Harnesses to choose from to define an Optimal interface for
processing work items.

**Auto-close**
Empty Harness that closes automatically

**New**
Harness for new work items

**Perform**
Harness for updating and completing an assignment

**Review**
Harness for reviewing a work item in read-only mode

**NewCovered**
Harness for new work items that are associated with an existing cover work item.

**Confirm**
Confirmation form harness

---------------------------------------------------------------------

## Creating Harnesses

**Define layout of the screen that the user sees in a browser window by using a harness.**

  1. In the header of **Dev Studio** click **Create > User Interface > Harness.**
  2. In the **Create Harness** tab, in the **Label** field give a name for the harness.
  3. To override a standard harness, in the **Label** field, enter the harness you want to override
     **Example**
     Overriding the **Review Harness** which is **Read-Only Mode**
  4. In the **Context** section define the application, class, and target ruleset. As a best practice, select the name of the work class that contains the work items that the harness supports.
  **Choose the class that is most specific to the application and its work items, rather than a general class**
  5. click **Create and Open**

### Configuring Screen Layout

  1. click **Screen Layout** then click the **View Properties** icon
  2. in the **General Tab** explore screen layout formats.
