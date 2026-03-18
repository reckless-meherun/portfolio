---
layout: post
title: Semantic Grading of Written Answers in Low-Resource Language Bangla Using a Fine-Tuned Lightweight Language Model
description: >
  CognifyQ is an AI-powered assessment platform designed to support content ingestion, question generation, and semantic grading in educational settings.
image: /assets/img/publications/cognifyq_method_horizontal_2.png
categories: [research]
permalink: /research/semantic-grading/
sitemap: false
---

**Venue:** Under Review at **ACL System Demonstration 2026** \\
**Authors:** **Meherun Farzana**, Aniket Joarder, Mahmudul Hasan, Md. Mosaddek Khan\\
**Links:** **Links:** [Paper]({{ '/assets/papers/cognifyq.pdf' | relative_url }}), [Website](https://cognifyq.com/)

## Abstract

Bangla is among the world’s most widely spoken languages, yet it remains underserved in educational NLP research. In many remote and rural regions, access to qualified subject teachers is limited, and written answers are consequently graded largely by hand, restricting timely and consistent feedback. Automatic assessment is challenging because semantically correct responses can vary substantially in surface form. We present a bilingual (Bangla-English) evaluation system designed for low-resource educational settings that prioritizes semantic correctness over lexical overlap.[^12] Our approach fine-tunes a lightweight language model to grade each response using the question, reference answer, and student answer, producing a numeric score and concise, context-grounded feedback suitable for classroom deployment. We also construct a synthetic bilingual dataset to enable controlled training and evaluation. Across proprietary and open-source LLMs evaluated under a unified protocol, our QLoRA-tuned Qwen3-8B confirms consistent improvement by producing the most leakage-resistant feedback (RoRa = 0.819) in synthetic evaluation and the strongest agreement with human scores (\rho = 0.936, MAE = 0.725) in a dedicated human study.

<!-- There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

There should be whitespace between paragraphs.

Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](another-page).

* toc
{:toc .large-only}

## Header 2

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

### Header 3

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![](https://assets-cdn.github.com/images/icons/emoji/octocat.png)

### Large image

![](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists

Name
: Godzilla

Born
: 1952

Birthplace
: Japan

Color
: Green

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this. Or is it?
```

```
The final element.
``` -->
