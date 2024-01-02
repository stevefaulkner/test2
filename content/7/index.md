---
title: "Meta: SVG Images with missing text alternatives"
---

# Meta: Images with missing text alternatives

## WCAG Level

Level A

## Sub-issues

* [Linked list of sub-issues]

## Description

When images do not have a text description it means anyone who cannot see images properly will not know what the images are for.

## User impact

If an image does not have an appropriate text description, someone who is blind and uses a screen reader or someone who has images turned off in their browser to save on bandwidth will be completely unaware of the image's purpose. If the image conveys important information, like a graph, or is critical to the operation of a control like a link or a button, then a missing text description can prevent them from completing vital tasks.

## General solution

Make sure that every image that conveys information or is used to perform an action has an appropriate text description. The text description must be clear and relevant to the context in which the image is being used.

Refer to the related sub-issues identified in this ticket for specific implementation guidance.

## Test procedure(s)

Use these steps to confirm that the solution has been correctly applied to issues identified within the representative sample, and to test the rest of the website for instances of the same issue.

1. Check that all images have appropriate alternative text
2. Check that the alternative text acts as a suitable equivalent for the image

### Definition of done

Complete all of these tasks before closing this issue or indicating it is ready for retest:

* All issues/sub-issues identified within the representative sample have been resolved
* The rest of the website has been tested for the same type of issue
* All issues identified throughout the rest of the website have been resolved or filed as new issues

## Related standards

* [WCAG 2.2 Success Criterion 1.1.1 Non-text Content (Level A)](https://www.w3.org/TR/WCAG22/#non-text-content)

## More information

* [W3C: Image concepts](https://www.w3.org/WAI/tutorials/images/decision-tree/)
* [W3C: An alt decision tree](https://www.w3.org/WAI/tutorials/images/decision-tree/)
* [W3C: HTML 5.2 Requirements for providing text to act as an alternative for images](https://www.w3.org/TR/html52/semantics-embedded-content.html#alt-text)
