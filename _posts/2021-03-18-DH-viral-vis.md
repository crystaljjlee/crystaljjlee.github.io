---
layout: post
title: "Visualizing Misinformation: Digital Ethnography and Computational Methods in a Pandemic"
---

{{ page.title }}
================
<p class="meta">18 March 2021</p>

Huge thanks specifically to the DH Lab, Scharzman College of Computing, NSF, and SSRC for funding this research, and of course to Stephanie and Erica for such a generous invitation! 

I'm really excited to be presenting project that's been a year in the making on COVID-related misinformation. I think the general principles we've been able to distill here will continue to be relevant moving forward, when we're talking about other domains like climate change and the future of democracy. 

**[Slide]** Before I get started, I want to flag the racial valences of the pandemic that have led to violence against Asian communities in the US, and I say this very specifically as an Asian-American woman doing research on coronavirus misinformation. Please be attentive about the act of domestic terrorism in Atlanta and across the US. While you should absolutely donate to Asian American mutual aid orgs if you have the means, there is an excellent, free online course on bystander intervention. This one is only 1 hour, includes concrete examples of what you can do, and is offered by Hollaback and Asian Americans Advancing Justice. If you take anything away from this talk today, please learn how to de-escalate violence that has been magnified due to misinformation, especially against Asian communities. 

**[Slide]** To the research: I also wanted to clarify a bit about what I mean when I say "project." One of the most exciting things about working on this is that we've been able to turn the academic research -- which will appear at Computer Human Interaction in May, and won Honorable Mention for Best Paper -- into an interactive data storytelling project. And, as you might have seen on Twitter, I've also created a 30 second trailer of a much longer explainer video: in other words, we've really tried to give this research the NYT Graphics and Vox Media treatment in hopes of translating our computational and ethnographic research for a public audience, and I'm happy to talk more about that in the Q&A. 

**[Slide]** To that end, I'll split this talk into two sections: I want to share our research insights -- what did we find, what did we do? -- *and* pull back the curtain a bit to show you how the sausage was made, so to speak. (How did we do this? Where do we go from here?)

## Results 
**[Slide]** As many of us no doubt know, data visualizations like "Flatten the Curve" have shaped public health responses to COVID in critical ways. For some, it's about **fighting coronavirus with big data** or creating **interactive, data-driven models.** Importantly, there seems to be a collective intuition that **bigger data, better uses of technology, higher literacy, and greater capacities to scale** will pave the way to ending the crisis. These graphs -- and the impulse to use data for good -- has been critical for both experts and the broader public to make sense of the pandemic. 

**[Slide]** But what does it mean to be "data driven?" What kinds of work can or should data visualizations do? What we've really done with this project is to try and track the social life of information. How do these charts morph as they leave the hands of a journalist at the *Financial Times* and show up on your Twitter timeline? 

**[Slide]** We did this by combining tools in **[build]** computational social science so that we have a sense for how information circulates at a larger scale (half a million tweets, 41k visualizations). We combined that with **[build]** digital ethnography, so that we can identify the phenomena in a more granular fashion (by tracking the dynamics that persist in Facebook Groups). We chose these methods for two reasons: first, in order to really get a sense for how prevalent these phenomena really are in terms of **scale,** but also to find ecologically appropriate methods for the datasets we have available to us. Social media researchers among us know that studying Twitter is exciting because the API gives you so much data -- to the point where Zeynep Tufekci calls it the "model organism" of quantitative social media research. Facebook is famously more tight-fisted with their quantitative data, and everything you use is mediated through their platform called CrowdTangle, which is a fantastic content discovery tool that academics and industry professionals alike can use to track trends across Facebook's ecosystem (e.g. Facebook Groups, Pages, and Instagram). 

To answer these questions more concretely, we took a bird's eye view by studying half a million tweets and 41,000 visualizations computationally. On a more granular level, we analyzed group dynamics by closely following five Facebook groups over the course of six months. 

Ultimately, we wanted to get a sense for how data about the pandemic circulates on social media. How did we actually do this? 

## Methods 
**[Slide]** Let's be concrete here. 

When it came to the computational social science, we first collected all tweets mentioning some combination of the words "COVID" and "data," and if they included an image. Then, we created a network of Twitter users and classified the communities using the Louvain method. Concurrently, we classified all of the images that were attached to these tweets using a a computer vision model trained by computer scientists Jorge Poco and Jeff Heer, to ask: **what kinds of data visualizations do different groups use?** Do anti-mask groups tend to use 3D bar charts compared to the NYT Graphics section? 

We also conducted a digital ethnography using an interative process: we collected posts where people talk about COVID-related data, then posts where people do their own COVID-related data analysis, their angry posts where people who hate masks talk about science and data. We ultimately asked: **what does "follow the data" mean for anti-mask communities?** 

**[Slide]** What we really tried to introduce here, particularly for computer science researchers, was a way to talk about the iterative process that we went through in order to collect this data. To analyze this, we use **grounded theory**, which describes an iterative method of data collection, coding and analysis, where your research questions *change with new data.* We also adapted this to think about **deep lurking,** which we based on anthropologist Clifford Geertz's injunction to employ "deep hanging out," where the most significant insights come from informal settings, not formal interviews. To this end, I spent hundreds of hours poring through these Facebook groups, going to live streams, and filing through the videos and images they share. 

## Network graph 
**[Slide]** So we ended up with two things on the computational side. Let's first talk about the network visualization of the Twitter users. 

## Reflection 
Ultimately, what I'm trying to do today is not just about sharing the results of our work, but to take advantage of this forum and use this as an opportunity to pull back the curtain and show how this kind of project is made. 

The core research team for this work consists of myself, my 2 advisors -- in computer science and anthropology -- and 2 undergraduate research assistants who were split between the two disciplines. 





