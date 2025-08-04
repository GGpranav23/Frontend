1. What is conflict between selectors?
Answer: When there are multiple selectors targeting the same element, there is conflict as to which selector's style shall be applied to the selected element

**For that we have a precedence table: Highest Priority to lowest Priority**

6. Declarations marked as !important
7. inline styles
8. ID selectors            NOTE: If multiple, last selector applies
9. class selectors or pseudo class  NOTE: If multiple, last selector applies
10. element selector NOTE: If multiple, last selector applies
11. universal selector

NOTE: Use !important as the last option.