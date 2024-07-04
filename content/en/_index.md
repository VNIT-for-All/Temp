---
title: Goldydocs
---

{{< blocks/cover title="Welcome to VNIT-for-All" image_anchor="top" height="full" >}}
<a class="btn btn-lg btn-primary me-3 mb-4" href="/docs/">
  Learn More <i class="fas fa-arrow-alt-circle-right ms-2"></i>
</a>
<a class="btn btn-lg btn-secondary me-3 mb-4" href="https://github.com/google/docsy-example">
  Download <i class="fab fa-github ms-2 "></i>
</a>
<p class="lead mt-5">Porridge temperature assessment &mdash; in the cloud!</p>
{{< blocks/link-down color="info" >}}
{{< /blocks/cover >}}


{{% blocks/lead color="primary" %}}
# Welcome to VNIT For All
Quick Note:
## Microsoft:
https://github.com/VNIT-for-All  
[Github Pages - Trang Này](https://vnit-for-all.github.io)  
↳ OverView 
↳ Repositories
  ↳ IT Talks 1102
  ↳ IT Leadership and Governance
  ↳ General IT Controls	
↳ Projects

## Google
[Google Groups](https://groups.google.com/g/vnitforall/about)
[Google Site](https://sites.google.com/view/vnit-for-all)
VNIT For All 
↳ Home
↳ Projects
  ↳ IT Talks 1102
  ↳ IT Leadership and Governance
  ↳ General IT Controls	
↳ Contacts

### Tài liệu nội bộ
[Google Drive VNIT for ALL](https://drive.google.com/drive/folders/1_C4BUP3GatJ8kU0_kp7_eN7UHs4E76A_).

## Meta
[Facebook Group](https://www.facebook.com/groups/vietnamittalks)

## Other 
| Slack & Gitbook vẫn đang đợi hết Trial rồi đánh giá tiếp. Github

> You can find more information about **StackEdit Tool**  [here](https://stackedit.io/app#).


## UML diagrams

You can render UML diagrams using [Mermaid](https://mermaidjs.github.io/). For example, this will produce a sequence diagram:

<script type="module">
  import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs';
  mermaid.initialize({ startOnLoad: true });
</script>

```mermaid
sequenceDiagram
Alice ->> Bob: Hello Bob, how are you?
Bob-->>John: How about you John?
Bob--x Alice: I am good thanks!
Bob-x John: I am good thanks!
Note right of John: Bob thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

Bob-->Alice: Checking with John...
Alice->John: Yes... John, how are you?
```

And this will produce a flow chart:

```mermaid
graph LR
A[Square Rect] -- Link text --> B((Circle))
A --> C(Round Rect)
B --> D{Rhombus}
C --> D
```


(Sadly, Goldydocs isn't a real project, but you can use this site as an example
to create your own real websites with [Docsy](https://docsy.dev))
{{% /blocks/lead %}}


{{% blocks/section color="dark" type="row" %}}
{{% blocks/feature icon="fa-lightbulb" title="New chair metrics!" %}}
The Goldydocs UI now shows chair size metrics by default.

Please follow this space for updates!
{{% /blocks/feature %}}


{{% blocks/feature icon="fab fa-github" title="Contributions welcome!" url="https://github.com/google/docsy-example" %}}
We do a [Pull Request](https://github.com/google/docsy-example/pulls) contributions workflow on **GitHub**. New users are always welcome!
{{% /blocks/feature %}}


{{% blocks/feature icon="fab fa-twitter" title="Follow us on Twitter!" url="https://twitter.com/docsydocs" %}}
For announcement of latest features etc.
{{% /blocks/feature %}}


{{% /blocks/section %}}


{{% blocks/section %}}
This is the second section
{.h1 .text-center}
{{% /blocks/section %}}


{{% blocks/section type="row" %}}

{{% blocks/feature icon="fab fa-app-store-ios" title="Download **from AppStore**" %}}
Get the Goldydocs app!
{{% /blocks/feature %}}

{{% blocks/feature icon="fab fa-github" title="Contributions welcome!"
    url="https://github.com/google/docsy-example" %}}
We do a [Pull Request](https://github.com/google/docsy-example/pulls)
contributions workflow on **GitHub**. New users are always welcome!
{{% /blocks/feature %}}

{{% blocks/feature icon="fab fa-twitter" title="Follow us on Twitter!"
    url="https://twitter.com/GoHugoIO" %}}
For announcement of latest features etc.
{{% /blocks/feature %}}

{{% /blocks/section %}}


{{% blocks/section %}}
This is the another section
{.h1 .text-center}
{{% /blocks/section %}}
