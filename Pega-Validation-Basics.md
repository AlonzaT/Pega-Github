# Pega - Validations Basics - Validate Rule Syntax

**Obj—Validate** - Use the Obj-Validate method in an activity to reference validate rules and cause the Pega Platform to run them.
Use this method to apply a validate rule ( Rule-Obj-Validate rule type) for the object identified on the primary page or step page.

**Validate rules and Primary pages.**

- When an activity executes the Obj—Validate method, the activity does not update the primary page. During Validate execution, the keyword "Primary" references the page the Activity was executed against.
- When a validate rule calls another validate rule, the calling rule does update the primary page.
  - If the Property column is blank, the page the Validate rule executed against becomes the primary page.
  - If the Property column references a page (the step page), the referenced page becomes the primary page.
