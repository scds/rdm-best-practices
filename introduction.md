---
layout: default
title: Introduction
nav_order: 3
---
<!-- 
This page will go over introductory content to the workshop. 
If your workshop has an introduction sequence, whether it be history, "Why should you use __", or anything of that matter, this is where it goes! If your workshop doesn't need this, delete introduction.md from the repository. 
Add, edit, or remove any content below for the workshop in question. 
-->

# Workshop Introduction 
<!-- Follow along with the introductory video, slides, or text below. -->

<!-- If your page has a video to go along with it, put it here. -->
<!-- <iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/a65689c0-c35c-4f33-9c12-f0ac97883f54/public?autoplay=false&automute=false"></iframe>
[View original here.](https://echo360.ca/media/a65689c0-c35c-4f33-9c12-f0ac97883f54/public?autoplay=false&automute=false) -->

<!-- If your page has slides/PDFs/worksheets to go along with it, put it here. -->
<!-- <embed width="100%" height="466" src="assets/docs/examplePDF.pdf" style="border:none;">
[Download slides here.](assets/docs/examplePDF.pdf) -->

<!-- Below the video/slides, this is where you put the text version of the page. -->
## What is Research Data Management?

Research Data Management (RDM) is the active process of organization and maintenance of data throughout its life cycle. You can think of it as an umbrella term of different practices and things you do as a researcher to ensure your data is secure, accessible, usable, and remains intact over time.

RDM comprises of a number of activities throughout your project's lifecycle.

<img src="assets/img/introduction/lifecycle.png" alt="" width="90%" style="margin: auto; display: block">

### Planning

In the planning phase, you might create a data management plan (DMP). You might also have to talk about how you're going to manage your data as part of a grant application, an ethics application, or a research proposal.

### Data Collection

Once you start data collection, you need to manage the data. This can include things like managing who has access to the data, how it's documented, how it's directly managed, where you're putting your files, how you're organizing the your folders and data, what kind of metadata you're keeping, and if you're working with sensitive data, how you're doing the identification of data.

### Analysis

Analysis is such a complex phase in the project life cycle that it has its own entirely different support system. Because of that, we don't do talk too much about the data analysis phase.

### Publication and Sharing

Once you're finished your data analysis, you head into the publication and sharing phase. Many journalists now require data deposits. Researchers are actively sharing data openly online in data repositories or through data publications. It's also important to think about long term preservation of your data, and how you're going to connect data sets that you publish to your research profile using persistent identifiers.

### Discovery and Reuse

Then comes the discovery and reuse phase, which cover concepts like reproducibility, open access, data repositories, places for you to access new data sets from other researchers.

### Manage

Throughout the whole process, you have to keep your data stored and secure.

## Why is Research Data Management important?

### Data Vulnerability

Is your data vulnerable?

- In a year or two, will you be able to remember all the details of your experiments?
- What will happen to your data when you graduate, move, or retire?
- How much work would you have to do if you lost your data?
- If you need to share your data with a collaborator, would they be able to understand it without your help?

<img src="assets/img/introduction/lost1.png" alt="" width="56%">
<img src="assets/img/introduction/lost2.png" alt="" width="43%">

We've all posters like these, or perhaps online posts on Twitter or Reddit. If you're storing your data on your laptop, and your data gets stolen or lost, you might be in a lot of trouble.

<img src="assets/img/introduction/fire.png" alt="" width="90%" style="margin: auto; display: block">

Even if you have your data stored on campus, things do happen. For example, a few years ago, the National Museum of Brazil burnt down and many researchers lost not only their data, but their physical specimans that they were collecting data from.

In cases like these, it's really difficult to recover or recollect data.

<img src="assets/img/introduction/fire2.png" alt="" width="60%" style="margin: auto; display: block">

A few years prior to that, the University of Manitoba had a large fire in the psychology building which destroyed several labs. The university had to spend several million dollars over the span of a couple of years on forensic data recovery and were able to recover a lot of the data from the destroyed computers. As a masters or PhD student, you can't afford to wait that long for your data sets to be recovered, you need to graduate.

<img src="assets/img/introduction/missing.png" alt="" width="60%" style="margin: auto; display: block">

The last thing to mention is that, as time passes, research data becomes less available or entirely lost. We're relying on these publications as a foundation for our research and it's impotant to be able to verify what people have done in the past.

It's important for you to be mindful of storing your data in such a way that it will let it be accessible and preserved over the long term.

## Let's take a look at Dave

"Dave" is a graduate student working in Biomedical Science, focused on x-ray imaging of bone tissue samples. Dave's data is made up of 3 major components:
- Image files - x-ray images, microscope images
- Software and hardware configuration files - instrument specific files, scripts, text files
- Measurement data files - spreadsheet files, tabular data

Dave's data is stored seperately in a few places:
- Image files are quite large (2+ TB) and stored on lab computers and a collection of miscellaneous external hard drives accumulated over the years.
- The other files are smaller (~10 GB) and stored on a personal laptop and a cloud storage platform (OwnCloud)

The data is not consistently documented. Dave's lab is under a lot of pressure, and so rather than doing consistent documentation, it's always onto the next experiment and the next data collection. The data is also not published or shared outside the research group except by direct request. No time or energy is put into archiving the research data.

### What went wrong for Dave

This is a normal practice for a lot of researchers, where the research is so intense that we don't think we have time to do documentation and focus on preservation. 

In Dave's case, one of his external drives fails, leading to the loss of some of Dave's data. This data loss is not discovered for several weeks and there is no back up of this data. Since there's so much data and it's not well documented, Dave isn't sure which data sets he lost.

This leaves Dave with two options:
- Extend his degree while he recollects that data, or
- Publish what he can, even though the explanatory and statistical power of the study has been reduced

### What could Dave do better in the future?

1. Dave could make a plan for his data.
    - A data management plan could help Dave avoid duplication of research and increase use of existing data.
    - It can also save time and resources.
2. Dave could organize and document his data consistently.
    - It would help Dave remember what he does.
3. Dave could store and back-up his data securely.
    - Backing-up his data would prevent data loss.
    - Securing data would protect research participants.
4. Dave could make sure his data is ready for archival and sharing.
    - Getting his data ready will help meet funder & journal requirements.
    - This will also increase visibility and citation credits.

The rest of this workshop will go through these four major topics: data manangement planning, data organization and documentation, data storage and security, and finally data sharing and archival.
 