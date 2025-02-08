---
#
# By default, content added below the "---" mark will appear in the home page
# between the top bar and the list of recent posts.
# To change the home page layout, edit the _layouts/home.html file.
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
# <h3 class="blackpar_title">(Models, Training and Inference)</h3>
layout: home
---
<div style="display: flex; align-items: center; justify-content: center; background: url('images/header.jpg') no-repeat; background-size: cover; user-select: none; height: 600px; padding: 0;">
    <h1 class="blackpar_title" style="text-align: center; font-weight: bold; line-height: 1.2; text-shadow: 0px 0px 5px black;">The 2<sup>nd</sup> workshop on Generative AI and Biology</h1>
</div>



<br>
<p>
Welcome to the GenBio Workshop! Join us as we explore the exciting intersection of artificial intelligence and biology.
Discover how generative AI is revolutionizing protein research, RNA analysis, molecular design, drug discovery, and more.
This workshop is designed to be interactive and practical,
equipping you with the skills to utilize generative AI tools in your own biological research.
Engage in stimulating discussions and collaborate with experts from diverse backgrounds.
Together, let's unlock the potential of generative AI for biology.</p>

<p>
Stay tuned by following us on <a href="https://twitter.com/genbio_workshop">Twitter</a>.
</p>

<br>


<!--starts inverted colors-->
<div class="inverted">

<br><br>
<h2 class="blackpar_title" id="overview">Overview</h2>
<!--<p>
The revolutionary crossroads between artificial intelligence (AI) and biology
is one of the most exciting frontiers of our time.
In this workshop, we will dive deeply into the implications
of generative AI for biological discovery, drug discovery, and translational medicine.
</p>-->
<p>
Over the past year, generative AI models have led to tremendous breakthroughs,
from image and text generation, to protein folding and design.
These recent successes illustrate the incredible potential of generative AI not
only for digital applications, but also for basic science and healthcare.
We are now able to predict protein structure from sequence alone; to
characterize the function and interactions of biomolecules; to design such
molecules never-before-seen in nature; and more.
The impacts are profound: through generative AI, we can systematically
understand and reprogram biology at an unprecedented level.
</p>
<p>
The goals of this workshop are to bridge the gap between the machine learning and biological
communities;
to connect leading researchers from both industry and academia;
and to gain
critical insights into the future of generative-AI-driven biology.
We look forward to your participation in this exciting discourse on the future of biology and AI.
</p>

<!-- <h2 class="blackpar_title" id="deadlines">Important information</h2> -->
<!--<p>
All deadlines are 11:59 pm UTC -12h ("Anywhere on Earth"). All authors must have an OpenReview profile when submitting.
<p>
<ul>
    <del><li>Submission Deadline: October 3, 2023</li></del>
    <del><li>Review Bidding Period: October 8-10, 2023</li></del>
    <del><li>Reviewer Deadline: October 24, 2023</li></del>
    <li><del>Acceptance Notification (tentative): October 27, 2023</del>
    Decisions sent!</li>
    <li><del>Camera-Ready Submission: November 22, 2023</del></li>
    <li>Workshop Date: <b>Saturday, December 16, 2023</b> (in-person)</li>
</ul>
</p>

<!-- <p>
The workshop will be held on December 16 in
room MR265-268 at the
Ernest N. Morial Convention Center (900 Convention Center Blvd, New Orleans, LA 70130).
</p> -->

<!-- <p>
Please refer to the Neurips website regarding
<a href="https://neurips.cc/Register/view-registration">registration</a> and
<a href="https://neurips.cc/Conferences/2023/Hotels">hotels</a>. We would like to reiterate
that poster presentations will be in-person only.
</p>

<p>
The talks will be livestreamed for virtual attendees.
Please register via NeurIPS for a virtual pass for access.
</p> -->


<!-- Poster instructions -->
<!-- <h2 class="blackpar_title" id="instructions">Author Instructions</h2>

<p>
Posters should be 24W by 36H (vertical) and printed on lightweight paper,
as they will be affixed to the wall by tape.
Instructions regarding poster printing can be found
<a href="https://neurips.cc/FAQ/PosterInformation">here</a>.
</p> -->

<!-- <p>
Camera ready manuscripts are due on
<a href="https://openreview.net/group?id=NeurIPS.cc/2023/Workshop/GenBio">OpenReview</a>
by November 22, 2023.
Please update your submissions to 1) include author names and affiliations, and 2) incorporate any desired changes based on your reviews. Your camera-ready should follow the same Neurips style guide, and it may contain up to 5 pages of content (excluding references and appendices).
</p> -->

<!-- <p>
Papers should indicate that they are NeurIPS Generative AI and Biology
Workshop 2023 papers by using the stylesheet provided
<a href="https://www.overleaf.com/latex/templates/neurips-2023-genbio-workshop/tzsxwjkrxnrk">here</a>.
</p> -->

<!-- Schedule -->
<!-- <h2 class="blackpar_title" id="schedule">Schedule (UTC-6)</h2>
<p>
{% include schedule.html %}
</p> -->


<!-- Call for Papers -->
<h2 class="blackpar_title" id="call_for_papers">Call for Papers</h2>

<p>
We invite researchers, scientists, students, and industry professionals working in the domains of artificial intelligence, machine learning, computational biology, bioinformatics, and related areas to submit their original research or review papers.
The scope of this workshop includes, but not limited to, the following topics.
</p>

<h5>Designing and optimizing novel and useful biomolecules</h5>

<ul>
    <li>
        <b>Rational protein design:</b>
        Prediction and
        optimization of protein sequences and/or structures,
        incorporating constraints and prior
        knowledge
    </li>
    <li>
        <b>Small molecule drug design:</b>
        Discovery and optimization of novel and
        effective small molecule therapeutics, incorporating information
        about the biological context
    </li>
    <li><b>Next frontiers of de-novo design:</b>
        Designing other biomolecules including
        peptides, oligonucleotides, antibodies, or targeted degraders
    </li>

</ul>

<h5>From first principles: generative modeling for biological data</h5>
<ul>
    <li><b>Sequence-based methods:</b>
        large language models for protein / genomic sequences,
        sequence-based molecular design
    </li>
    <li><b>Graph-based methods:</b>
        generative learning on biological graphs and networks,
        e.g., molecular graphs, protein-protein interaction networks,
        genome-wide association graphs
    </li>
    <li><b>Geometric deep learning:</b>
        generative modeling of biological structures as
        point clouds, surfaces, and other geometric objects
    </li>
</ul>

<h5>Open challenges in generative AI and biology (Special Track)</h5>
<ul>
    <li><b>Large language models for scientific discovery:</b>
    literature summarization, structured information extraction, identifying
    knowledge gaps and uncovering novel connections, formulation of scientific
    hypotheses</li>
    <li><b>Finding common ground:</b>
    systematic barriers, biological experiment
    design with GenerativeAI-in-the-loop</li>
    <li><b>Identifying the right problems:</b> pressing challenges in biology that
    are difficult to address via traditional means, gap between biological need
    and existing generative algorithms</li>
</ul>


<h2 class="blackpar_title">Submission Instructions</h2>
<p>
<span style="color:red">
We are inviting experienced researchers to participate in the review process as program committee members.
If you are interested, please submit your request <a href="https://docs.google.com/forms/d/e/1FAIpQLSc8WQEmqQzKaMXAQ5y-lXKObIE2wQlA41A3rR5NZYOK1CVYXA/viewform?usp=sf_link">here</a>!
</span>
</p>
<p>
You are invited to submit your papers in our OpenReview submission <a href="https://openreview.net/group?id=NeurIPS.cc/2023/Workshop/GenBio">portal</a>.
All submissions must be anonymous for double-blind review.
We expect each paper to be reviewed by at least three reviewers.
The content of the paper (excluding the references and supplementary materials) should not be longer than 4 pages,
with strict adherence to the NeurIPS template style,
which can be found <a href="https://neurips.cc/Conferences/2023/PaperInformation/StyleFiles">here</a>.
</p>
<p>
Authors may submit up to 100 MB of supplementary materials separately.
Authors are highly encouraged to submit their code for reproducibility.
</p>
<p>
According to the NeurIPS workshop guidelines, we do not encourage the
re-submission of already-published papers,
but you are allowed to submit ArXiv pre-prints or those currently under submission.
Moreover, a work that is presented at the NeurIPS main conference should not appear in a workshop.
Please be sure to indicate conflicts of interest for all authors on your paper.
</p>
<p>
To encourage higher quality submissions, outstanding submissions will also be selected for oral presentations.
Bear in mind that our workshop is not archival,
but accepted papers will be hosted on the workshop website.
</p>

<!-- # Confirmed Speakers & Panelists -->
<h2 class="blackpar_title" id="speakers">Confirmed (Tentative) Speaker</h2> 
<p>
{% include speakers.html %}
</p>


<!--<h2 class="blackpar_title" id="speakers">Panelists</h2>
<p>
{% include panelists.html %}
</p>-->

<!-- Organizers -->
<h2 class="blackpar_title" id="organizers">Organizers</h2>
<p>
{% include organizers.html %}
</p>

<!-- Moderators -->
<!-- <h2 class="blackpar_title" id="moderators">Moderators</h2>
<p>
{% include moderators.html %}
</p> -->

<h2 class="blackpar_title" id="sponsors">Sponsors</h2>
<p>
{% include sponsors.html %}
</p>

<br><br>

<!-- Technical Committee -->
<!--<h2 class="blackpar_title" id="technical_committee">Technical Committee</h2>
<p>
{% include technical_committee.html %}
</p>
-->
<br><br>

<!--
<h2 class="blackpar_title">Sponsor</h2>
<div class="row">
    <div class="col">
        <center>
            <img src="">
        </center>
    </div>
    <div class="col">
        <center>
            <img src="" width="250px">
        </center>
    </div>
</div>-->

<!-- <h2 class="blackpar_title">Gold Sponsor</h2>
<div class="row">
    <div class="col">
        <center>
            <img src="" width="250px">
        </center>
    </div>
    <div class="col">
        <center>
            <img src="" width="250px">
        </center>
    </div>
</div> -->

<!--ends inverted colors-->
<!-- Default Statcounter code for genbio
https://genbio-workshop.github.io/ -->
<script type="text/javascript">
var sc_project=12885210;
var sc_invisible=1;
var sc_security="21af2424";
</script>
<script type="text/javascript"
src="https://www.statcounter.com/counter/counter.js"
async></script>
<noscript><div class="statcounter"><a title="Web Analytics"
href="https://statcounter.com/" target="_blank"><img
class="statcounter"
src="https://c.statcounter.com/12885210/0/21af2424/1/"
alt="Web Analytics"
referrerPolicy="no-referrer-when-downgrade"></a></div></noscript>
<!-- End of Statcounter Code -->
