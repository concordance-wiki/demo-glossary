---
aliases: [confidence score, score]
---
# Confidence

A value between 0 and 1 that expresses how reliable the method that produced a [link](link.md) is. A written link scores 1.00, a frontmatter reference 0.90, a mention in a mapped section 0.70, an [occurrence](occurrence.md) 0.60 and more, a co-occurrence 0.40. When several methods agree, their confidences combine. The first version stores the score, uses it to order mentions, and does not show it.
