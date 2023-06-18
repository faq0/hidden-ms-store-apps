name: Link Submission
description: Submit apps that does not appear in search results in Microsoft Store
title: "[newLink] "
labels: ["Link Submission"]
assignees:
  - faq0
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill out this link submission form! 
**Do not Submit:**
- *Services* (e.g.: [MSN Dial-Up Internet Access](https://www.microsoft.com/en-us/p/msn-premium/CFQ7TTC0KGVG), [Xbox Live Gold](https://www.microsoft.com/store/apps/CFQ7TTC0K5DJ
))
- *In-app-purchase products* (e.g.: gift cards, in-game currency)
- *Office subscriptions that may change over time* (e.g.: [Office Home & Student 2019](https://www.microsoft.com/store/apps/CFQ7TTC0K7C8) which redirects to Office21HomeStudent subscription)
- *Office apps* including [PowerPoint](https://www.microsoft.com/store/productId/CFQ7TTC0K7C6), [Excel](https://www.microsoft.com/store/productId/CFQ7TTC0K7DX), [Word](https://www.microsoft.com/store/productId/CFQ7TTC0K7C7), [Publisher](https://www.microsoft.com/store/productId/CFQ7TTC0HLKN), [Access](https://www.microsoft.com/store/productId/CFQ7TTC0HHMX), [Outlook](https://www.microsoft.com/store/productId/CFQ7TTC0HLKQ). However, Office apps that redirect to apps.microsoft.com are accepted. (e.g.: [Outlook for Windows](https://www.microsoft.com/store/productId/9NRX63209R7B))

  - type: input
    id: link
    attributes:
      label: Submit Link
      description: Enter productId or URL.
      placeholder: e.g.: https://www.microsoft.com/store/productId/9NDMKW4871M4 OR 9NDMKW4871M4
    validations:
      required: true
  - type: textarea
    id: other
    attributes:
      label: Others
      description: Got anything else to say?
      placeholder: 
      value: ""
    validations:
      required: false
