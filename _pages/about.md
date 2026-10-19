---
layout: about
title: about
permalink: /about/
nav: true
nav_order: 1
# subtitle:

profile:
  align: right
  image:
  image_circular: false # crops the image to make it circular
  address:

news: false # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page
---

# Key Dates
- **Abstract & Submission deadline**: {{ site.deadline }}
  - [Submit to OpenReview](https://openreview.net/group?id=ICLR.cc/{{ site.year }}/BlogPosts)
  - Any modifications to your blog post, via a pull request on GitHub
- **Notification of acceptance**: {{ site.decisions }}
- **Camera-ready merge**: {{ site.camera_ready }}

## Contents

- [Key Dates](#key-dates)
  - [Contents](#contents)
- [ICLR Blogposts Track](#iclr-blogposts-track)
  - [A Blog Post Conference Track](#a-blog-post-conference-track)
  - [AI Usage](#ai-usage)
  - [Submission caps](#submission-caps)
  - [Blog posts discussing previously published work](#blog-posts-discussing-previously-published-work)
      - [Content](#content)
      - [Conflict of interest](#conflict-of-interest)
  - [Publication](#publication)
      - [Poster](#poster)
  - [Submissions](#submissions)
  - [Contact](#contact)
  - [Organizers](#organizers)
  - [References](#references)

# ICLR Blogposts Track

The Machine Learning community is currently experiencing a [reproducibility crisis](https://neuripsconf.medium.com/designing-the-reproducibility-program-for-neurips-2020-7fcccaa5c6ad), a reviewing crisis [[Littman, 2021]](#Litt), and submission crisis [[Shah 2026]](#Shah). Because of the highly competitive, noisy, and overwhelmed reviewing process of ML conferences [[Tran et al., 2020]](#Tran), researchers have an incentive to oversell their results, slowing down the progress and diminishing the integrity of the scientific community. Moreover with the growing number of papers published and submitted at the main ML conferences [[Lin et al., 2020]](#Lin), it has become more challenging to keep track of the latest advances in the field.

Blog posts are becoming an increasingly popular and useful way to talk about science [[Brown and Woolston, 2018]](#Brow). They offer substantial value to the scientific community by providing a flexible platform to foster open, **human**, and transparent discussions about new insights or limitations of a scientific publication. However, because they are not as recognized as standard scientific publications, only a minority of researchers manage to maintain an active blog and get visibility for their efforts. Many are well-established researchers ([Francis Bach](https://francisbach.com/), [Ben Recht](https://www.argmin.net/), [Ferenc Huszár](https://www.inference.vc/), [Lilian Weng](https://lilianweng.github.io/)) or big corporations that leverage entire teams of graphic designers and writers to polish their blogs ([Meta AI](https://ai.meta.com/blog/), [Google AI](https://research.google/blog/), [DeepMind](https://deepmind.google/blog/), [OpenAI](https://openai.com/news/)). As a result, the incentives for writing scientific blog posts are largely personal; it is unreasonable to expect a significant portion of the machine learning community to contribute to such an initiative when everyone is trying to establish themselves through publications.

**Submit** your blogpost on [OpenReview](https://openreview.net/group?id=ICLR.cc/{{ site.year }}/BlogPosts).

## A Blog Post Conference Track

Last year, we ran the **fifth** iteration of the [Blogpost track](https://iclr-blogposts.github.io/2026/about) at ICLR {{ site.last_year }}!

It was very successful, with accepted posts presented in person at the main conference.

Our goal is to create a formal call for blog posts at ICLR to incentivize and reward researchers to:

<!-- We invite all researchers and practitioners to submit a blog post which: -->


1. Review past work and summarize the outcomes, develop new intuitions, or highlight some shortcomings.
2. Present novel perspectives or interpretations of existing machine learning concepts or techniques.
3. Discuss important issues in machine learning, such as reproducibility, from a novel perspective.
4. Analyze the societal implications of recent advancements in machine learning and AI.
5. If you are unsure about the content of your post you can reach us at [iclr-blogpost-track@googlegroups.com](mailto:iclr-blogpost-track@googlegroups.com)


<!-- **We will not consider politically motivated blogposts for publication.**

If you are unsure about the content of your post you can reach us at [iclr-blogpost-track@googlegroups.com](mailto:iclr-blogpost-track@googlegroups.com). -->

{% include previous.md %}

A very influential initiative of this kind happened after the Second World War in France. Because of the lack of up-to-date textbooks, a collective of mathematicians under the pseudonym Nicolas Bourbaki [[Halmos 1957]](#Halm), decided to start a series of textbooks about the foundations of mathematics [[Bourbaki, 1939]](#Bour). In the same vein, we aim to provide a new way to summarize scientific knowledge in the ML community. We will not consider politically motivated blogposts for publication.


## AI Usage
The rise of AI agents has led to an increase in AI-generated submissions, ranging from minor help with figures or grammar to fully AI-generated content that the authors do not themselves understand [[Shah, 2026]](#Shah). Blog posts should distill complex ideas into clear, engaging, and accessible content. Thus, we expect all text to be written primarily by humans (grammar editing is fine), though we welcome AI-generated widgets or figures that interactively bring the material to the reader, as we understand they take significant time to create. AI-generated text will be part of the reviewer rubric, and we may desk-reject AI-generated blog posts. Thank you for your understanding.

## Submission caps

There is a cap of two submissions per person.

## Blog posts discussing previously published work

#### Content


Write a post on a subject that has been published at a top-tier venue (ICLR, ICML, NeurIPS, AAAI, UAI, CVPR, SIGGRAPH, ECCV, ICCV, etc.) relatively recently.


#### Conflict of interest

The authors of the blog posts will have to declare their conflicts of interest (positive or negative) with the paper (and the paper's authors) they write about. Conflicts of interest include:
-   Recent collaborators (less than 3 years)
-   Current institution ​: reviewers will be asked to judge if the submission is sufficiently critical and objective of the papers addressed in the blog post.
- **Blog Posts must not be used to highlight or advertise past publications of the authors or their lab**.

We will only ask the authors to report if they have a conflict of interest. If so, reviewers will be asked to judge if the submission is sufficiently critical and objective of the papers addressed in the blog post.

## Publication

The posts will be created and published under a unified template; see [the submission instructions]({{ '/submitting' | relative_url }}) and the [sample post]({% post_url 2027-04-30-distill-example %}) hosted on the blog of this website.

#### Poster

Additionally, accepted posts will have the option to present their work as a poster during the main poster session. For more information about the main poster session (time, poster format, etc.) please refer to the ICLR homepage.

## Submissions

Please check our [submission instructions]({{ '/submitting' | relative_url }}) for more details.
We accept submissions in both Markdown and HTML. We believe this is a good trade-off between complexity and flexibility.

**Submit** your blogpost on [OpenReview](https://openreview.net/group?id=ICLR.cc/2027/BlogPosts&referrer=%5BHomepage%5D(%2F))

## Contact

For any technical issues with the blog post repository (for example, blog posts not displaying correctly or issues while following the [submission instructions](https://iclr-blogposts.github.io/2027/submitting/#creating-a-blog-post)), please open an [issue in our GitHub repository](https://github.com/iclr-blogposts/2027/issues).

For other inquiries, reach us via email at: [iclr-blogpost-track@googlegroups.com](mailto:iclr-blogpost-track@googlegroups.com)


## Organizers

{% include team.md mode="photos" %}

## References

<a name="Litt"> <a href="https://dl.acm.org/doi/10.1145/3429776">Michael L Littman. Collusion rings threaten the integrity of computer science research</a>. Communications of the ACM, 2021.</a>

<a name="Tran"> <a href="https://arxiv.org/pdf/2010.05137v1">David Tran, Alex Valtchanov, Keshav Ganapathy, Raymond Feng, Eric Slud, Micah Goldblum, and Tom Goldstein. An open review of OpenReview: A critical analysis of the machine learning conference review process</a>. arXiv, 2020. </a>

<a name="Lin"> <a href="https://medium.com/@NeurIPSConf/what-we-learned-from-neurips-2020-reviewing-process-e24549eea38f">Hsuan-Tien Lin, Maria-Florina Balcan, Raia Hadsell, and Marc’Aurelio Ranzato. What we learned from NeurIPS 2020 reviewing process</a>. Medium, 2020. </a>

<a name="Brow"><a href="https://www.nature.com/articles/d41586-018-01414-6">Eryn Brown and Chris Woolston. Why science blogging still matters</a>. Nature, 2018.</a>

<a name="Halm">Paul R Halmos. Nicolas Bourbaki. Scientific American, 1957.</a>

<a name="Bour">Nicolas Bourbaki. Elements of mathematics. Éditions Hermann, 1939.</a>

<a name="Shah"> <a href="https://medium.com/@TmlrOrg/asking-authors-about-their-own-papers-3d2e04e5dee0">Nihar Shah. Asking authors about their own papers</a>. Medium, 2026. </a>
