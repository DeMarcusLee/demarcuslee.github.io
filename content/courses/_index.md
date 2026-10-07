---
title: Courses
summary: My courses
type: landing

cascade:
  - target:
      path: '{/courses/*/**}'
    type: docs
    params:
      show_breadcrumb: true
sections:
  - block: markdown
    content:
      text: |
        ## Courses

        非参数统计

        {{< cards >}}
          {{< card url="/courses/non-parametric/" title="non-parametric statistics" icon="academic-cap" subtitle="非参数检验交互演示：正态计分、符号检验与 KS 检验。" >}}
        {{< /cards >}}
---
