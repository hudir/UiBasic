Flexbox

align-items: baseline;
items are aligned such as their baselines align (baseline for items' text content)

align-content
to group content and align them in crossaxis



flex-grow, when applied to an item will scale it relative to the sum of the size of all other items on the same row.

flex-shrink, which flex items bei schrink will shrink first and the minimal size, after the item shrink reach that size, all the row will shrink together

flex: 1; = flex-grow: 1;
flex: flex-grow flex-shrink flex-basis;  // by default 0 1 auto;