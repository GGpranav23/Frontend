What is conflict between selectors?
Answer: When there are multiple selectors targeting the same element, there is conflict as to which selector's style shall be applied to the selected element

**For that we have a precedence table: Highest Priority to lowest Priority**

1. Declarations marked as !important
2. inline styles
3. ID selectors            NOTE: If multiple, last selector applies
4. class selectors or pseudo class  NOTE: If multiple, last selector applies
5.  element selector NOTE: If multiple, last selector applies
6.  universal selector

NOTE: Use !important as the last option.