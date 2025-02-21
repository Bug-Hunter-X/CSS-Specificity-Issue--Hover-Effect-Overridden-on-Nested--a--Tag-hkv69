# CSS Specificity Issue: Hover Effect Overridden

This repository demonstrates a common CSS specificity problem. The hover effect on a nested `<a>` tag within an `<li>` element is unexpectedly overridden. The detailed explanation and solution are provided below.

## Problem
The hover style applied to the nested `<a>` tag is not working as expected due to CSS specificity rules. The parent `<li>` element's style has higher specificity and overrides the hover style of the nested `<a>` tag.

## Solution
The solution involves increasing the specificity of the nested `<a>` tag's hover style to override the parent `<li>` style. This can be done using more specific selectors or the `!important` flag (though the latter is generally discouraged). The repository demonstrates both approaches.