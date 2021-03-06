---
published: true
title: An Open Review of Niko Kriegeskorte
layout: post
author: Bradley C. Love
image: /images/blog/neural_similarity.png
comments: false

---

Imagine you think and work carefully on an [ambitious paper for a few years](https://www.biorxiv.org/content/early/2018/10/12/439893), trying to answer fundamental questions the field has overlooked. Now, imagine after a very long wait you receive negative reviews that completely missed the main point. Instead, the reviews project a certain person's pet concerns, goals, and interests onto your work, which are only tangentially related to your central questions. Worst yet, this person has acolytes whose capacity to miss the broader picture is only surpassed by their self-righteousness. That would be frustrating and potentially career-changing for some.

Now, let's add to this scenario that this reviewer personally emails you moments after your rejection absent kind words (he got the memo that empathy is passé), but demands that you agree with his viewpoint and alerts you that he will post an [open review of your work](https://nikokriegeskorte.org/2019/01/09/whats-the-best-measure-of-representational-dissimilarity/). This is inhuman.

But, open is good right? It can be, but it can also be incredibly self-serving. The review is of course open when Niko wants it to be and it serves him. Was the review posted before the editor made the reject decision? Of course not, because then we could respond and potentially affect the decision. Was it posted after we had time to publish elsewhere? Of course not. It was posted at the darkest time for my team when we are in our most vulnerable position when there's little time to respond and we have more important things to worry about. Nevertheless, we are obliged to respond because Niko has poisoned the well for our project. "Open" here is not to serve the community or the authors but to provide a cheap blog and attention for Niko for the limited number of manuscripts that it serves Niko to review. The reinforcing power structure here should be apparent to anyone clued in.

[Our paper itself](https://www.biorxiv.org/content/early/2018/10/12/439893), which I encourage you to read and form your own opinion, is about the nature of neural similarity, namely what makes two brain states similar. The main questions are whether the brain's preferred notion of similarity is different across regions and tasks. We find that the preferred similarity measures are common across regions but differ across tasks. This is cool. Of course, as we discuss, whatever measure is "best" (whatever that means and it does mean different things to different people) will depend on many issues, including data quality and quantity. We muse a bit on how these higher-level measures of similarity relate to underlying computations and representations. There's been a ton of work in Psychology on what makes two stimuli similar, but in Neuroscience people largely default to a few options without any real evaluation. Thus, our work is very needed in the field and timely. We get traction on this neglected problem by using a decoding approach to approximate the information available in a brain state. We discuss how much this approximation should be trusted in light of our central questions, namely does the brain use the same similarity measure across regions and tasks.

<figure class="fig">
<img src="{{ site.baseurl }}/images/blog/neural_similarity.png" title="Figure 1 from Bobadilla-Suarez et al. (2018) on families of similarity measures." class="u-max-full-width centered">
<figcaption>
  <div class="inner-caption centered">
  From  Figure 1, <a href=" https://doi.org/10.1101/439893">Bobadilla-Suarez et al. (2018)</a>:
Families of similarity measures. (left panel) Similarity measures divide into
those concerned with angle vs. magnitude differences between vectors. Pearson correlation
whereas Euclidean distance are common angle and magnitude measures, respectively. The
magnitude family further subdivides according to distributional assumptions. Measures
like Mahalanobis are distributional in that they are sensitive to co-variance such that
similarity falls more rapidly along low variance directions. (right panel) The choice of
similarity measure can strongly affect inferences about neural representational spaces. In
this example, stimuli <b>a</b>, <b>b</b>, and <b>c</b> elicit different patterns of activity across two voxels.
When Pearson correlation is used, stimulus <b>a</b> is more similar to <b>b</b> than to <b>c</b>. However,
when the Euclidean measure is used, the pattern reverses such that stimulus <b>a</b> is more
similar to <b>c</b> than <b>b</b>.
</div>
</figcaption>
</figure>

Decidedly what we are not trying to do is determine which neural similarity measure has the best properties by some metric, such as split-half reliability, bias, whatever small methodological point is of interest to some. Of course, that is what primarily interests some, such as Niko, but these points are minor and largely inconsequential to our goals and conclusions. Niko provided a top-down reading of our work strictly through the lens of his interests that fails to engage with the main ideas of the paper. I leave it to the acolytes to review his papers, of which I am familiar. Again, please read [our paper](https://www.biorxiv.org/content/early/2018/10/12/439893), rather than parrot Niko's views.

As these sideshows entertain, fundamental questions about how to bridge from neurons to voxels to compact higher-level descriptions to computations remain unanswered. To make progress, the field needs leaders who are open to ideas and are broader thinkers. Of course, instead we have a system that entrenches and amplifies those in positions of power within the field. Rather than fall in line, my lab is trying to address these difficult and subtle questions. However, how can we make progress in the field when we are reviewed by people like Niko who doesn't believe the brain has representations?
<blockquote class="twitter-tweet"><p lang="en" dir="ltr">true, the brain does not need representations. it also doesn&#39;t need information or causality. it&#39;s a dynamical system after all. it&#39;s *us* who need causality, and information theory, and representational interpretations to understand the brain. <a href="https://t.co/8JatZUo1yt">https://t.co/8JatZUo1yt</a></p>&mdash; Kriegeskorte Lab (@KriegeskorteLab) <a href="https://twitter.com/KriegeskorteLab/status/1028669449484816385?ref_src=twsrc%5Etfw">August 12, 2018</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

While we can all laugh at the occasional pseudo profound cringe-inducing tweets by celebrities like Elon Musk, we should expect more from the leaders of our field. It's intolerable for our scientific fate to be controlled by someone who is a [Cartesian Dualist](https://en.wikipedia.org/wiki/Mind%E2%80%93body_dualism) or is profoundly confused by levels of analysis. I am glad that Niko and others picked up on ideas from Roger Shepard and others from 1970 on [second-order isomorphism](https://www.sciencedirect.com/science/article/pii/0010028570900022) and that they popularised others' efforts to apply related ideas to the [analysis of fMRI data](http://science.sciencemag.org/content/293/5539/2425). They have made a career out of correlating the upper diagonal of matrices and plodding through attendant concerns. Now it's time to allow others to make progress and introduce new ideas into the literature.


**Postscript**: [Lots](https://twitter.com/ProfData/status/1083004240711307265) [of](https://twitter.com/ProfData/status/1083053727701970944) [discussion](https://twitter.com/INM7_ISN/status/1083019074215600129) [on](https://twitter.com/djnavarro/status/1083034770982858752) [Twitter](https://twitter.com/IrisVanRooij/status/1083048770147897346). To be clear, we are not against the eLife model of publishing reviews upon acceptance, nor are we against leaving comments on preprints, which can allow the authors to respond and perhaps make edits. We are against using the existence of a preprint as a pretext to write journal reviews which are really self-serving blog posts, especially when they are posted the moment one's paper is rejected by the editor. This take on open reviewing is open to abuse and is not really open as the reviewer decides what, where, when and how.  Furthermore, existing models of open review involve consent from all parties.

Also see the post by the first author too, here: [Sebastian's Thoughts on Open Review](http://bradlove.org/blog/open-review-2).
