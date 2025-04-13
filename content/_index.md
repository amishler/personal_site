---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/cv_alan_mishler.pdf
    design:
      columns: '1'
      background:
        color: '#ffffff'  # White
  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Senior Researcher
          company: J.P. Morgan AI Research
          company_url: 'https://www.jpmorgan.com/technology/artificial-intelligence'
          # company_logo: org-gc
          location: New York, NY
          date_start: '2021-06-28'
          date_end: ''
          # description: |2-
          #     Responsibilities include:

          #     * Analysing
          #     * Modelling
          #     * Deploying
        - title: Data Scientist Intern
          company: Google
          company_url: ''
          # company_logo: org-x
          location: Mountain View, CA
          date_start: '2019-06-01'
          date_end: '2019-08-31'
          description: Developed improved methodology to estimate ads lift/incrementality using combined experimental and observational data.
        - title: Data Scientist Intern
          company: Google
          company_url: ''
          # company_logo: org-x
          location: New York, NY
          date_start: '2018-05-01'
          date_end: '2018-08-31'
          description: Built a machine learning pipeline to probabilistically match entities in text with entries in a database.
        - title: Data Science Intern, Business Analytics
          company: Box, Inc.
          company_url: ''
          # company_logo: org-x
          location: Redwood City, CA
          date_start: '2017-05-01'
          date_end: '2017-08-31'
          description: Built a machine learning pipeline to automatically identify new marketing and sales leads.
        - title: Senior Faculty Research Specialist
          company: University of Maryland Center for Advanced Study of Language
          company_url: ''
          # company_logo: org-x
          location: College Park, MD
          date_start: '2010-09-01'
          date_end: '2016-08-01'
          description: Designed, conducted, and analyzed experiments in areas such as psycholinguistics, speech perception, and signal detection.          
    design:
      columns: '2'
      background:
        color: '#f9f9f9'  # Light warm gray
  - block: markdown
    id: news
    content:
      title: News &amp; Events
      # subtitle: My subtitle
      text: |-
        - <strong>12/2023</strong> <a href="https://openreview.net/forum?id=xfj5jjpOaL">Paper</a> presentation by colleague/former intern <a href="https://www.umass.edu/mathematics-statistics/directory/graduate-students/thomas-cook">Tom Cook</a> at the NeurIPS workshop <a href="https://realworldml.github.io/neurips2023/">Adaptive Experimental Design and Active Learning in the Real World</a> in New Orleans, LA.
        - <strong>12/2023</strong> Presentation (<a href="https://openreview.net/forum?id=CzdSCFOG1n">paper</a>/<a href="">poster</a>) at the NeurIPS workshop <a href="https://realworldml.github.io/neurips2023/">Adaptive Experimental Design and Active Learning in the Real World</a> in New Orleans, LA.
        - <strong>08/2023</strong> <a href="https://sites.google.com/view/epi-workshop-uai-2023/calls?authuser=0">Paper</a> presentation at the UAI workshop <a href="https://sites.google.com/view/epi-workshop-uai-2023/">Epistemic Uncertainty in Artificial Intelligence (E-pi UAI)</a> in Pittsburgh, PA.
        - <strong>06/2023</strong> Reviewer for the <a href="https://sites.google.com/view/ewaf23/home">European Workshop on Algorithmic Fairness</a> in Winterthur, Switzerland.
        - <strong>12/2022</strong> <a href="https://nips.cc/virtual/2022/workshop/49967#collapse58462">Paper</a> presentation at the NeurIPS workshop <a href="https://www.afciworkshop.org/afcp2022/home">Algorithmic Fairness through the Lens of Causuality and Privacy</a> (virtual).
        - <strong>12/2022</strong> Reviewer for the NeurIPS workshop <a href="https://www.afciworkshop.org/afcp2022/home">Algorithmic Fairness through the Lens of Causuality and Privacy</a> (virtual).
        - <strong>12/2022</strong> Attending the <a href="https://ai-finance.org/icaif22/">ACM International Conference on AI in Finance (ICAIF)</a> in New York, NY.
        - <strong>12/2022</strong> <a href="https://arxiv.org/abs/2311.00109">Paper</a> accepted to <a href="https://aaai.org/aaai-conference/">AAAI 2024</a> in Vancouver, CA.
        - <strong>11/2022</strong> Our <a href="https://openreview.net/forum?id=xfj5jjpOaL">paper</a> was nominated was for a Best Paper award at the  NeurIPS workshop <a href="https://realworldml.github.io/neurips2023/">Adaptive Experimental Design and Active Learning in the Real World</a> in New Orleans, LA.
        - <strong>10/2022</strong> <a href="https://eaamo2022.eaamo.org/posters/59_fabris.pdf">Poster</a> presentation by colleague <a href="https://scholar.google.com/citations?user=WjJVK94AAAAJ&hl=en">Alessandro Fabris</a> at the <a href="https://eaamo2022.eaamo.org/">ACM Conference on Equity and Access in Algorithms, Mechanisms, and Optimization (EEAMO)</a> in Arlington, VA.
        - <strong>08/2022</strong> <a href="https://dshealthkdd.github.io/dshealth-2022/#papers">Paper</a> presentation by colleague Raphael Sonabend at the <a href="https://dshealthkdd.github.io/dshealth-2022/">KKD Workshop on Applied Data Science for Healthcare</a> in Washington, DC.
        - <strong>06/2022</strong> <a href="https://dl.acm.org/doi/10.1145/3531146.3533167">Paper</a> presentation at the ACM conference on <a href="https://facctconference.org/2021/index.html">Fairness, Accountability, and Transparency</a> (FAcct) in Seoul, South Korea.
        - <strong>06/2022</strong> Reviewer for the ACM conference on <a href="https://facctconference.org/2021/index.html">Fairness, Accountability, and Transparency</a> (FAcct) in Seoul, South Korea.
        - <strong>06/2022</strong> <a href="https://sites.google.com/view/ewaf22/accepted-papers?authuser=0">Paper</a> presentation by colleague <a href="https://scholar.google.com/citations?user=WjJVK94AAAAJ&hl=en">Alessandro Fabris</a> at the <a href="https://sites.google.com/view/ewaf22/home?authuser=0">European Workshop on Algorithmic Fairness</a> in Zurich, Switzerland.
        - <strong>12/2021</strong> &lsquo;Fair and accurate risk assessment for healthcare decision making.&rsquo;: Invited talk given at the 14th International Conference of the ERCIM Working Group on Computational and Methodological Statistics (virtual).
        - <strong>12/2021</strong> Poster presentation at NeurIPS workshop <a hred="https://www.afciworkshop.org/afcr2021/accepted-papers">Algorithmic Fairness through the Lens of Causality and Robustness</a> (virtual).
        - <strong>12/2021</strong> Reviewer for the NeurIPS workshop <a href="https://www.afciworkshop.org/afcr2021#">Algorithmic Fairness through the Lens of Causality and Robustness</a> (virtual).
        - <strong>12/2021</strong> Program Committee/Reviewer for the NeurIPS workshop <a href="https://ml4d.notion.site/548251eab3df4517819c4742c2e5c853">ML for the Developing World (ML4D)</a> (virtual).
        - <strong>12/2021</strong> Reviewer for the NeurIPS <a href="https://neurips.cc/Conferences/2021/CallForDatasetsBenchmarks">Datasets and Benchmarks</a> track.
        - <strong>03/2021</strong> <a href="https://dl.acm.org/doi/10.1145/3442188.3445902">Paper</a> presentation at the ACM conference on <a href="https://facctconference.org/2021/index.html">Fairness, Accountability, and Transparency</a> (FAcct) (virtual).
        - <strong>03/2021</strong> Reviewer for the ACM conference on <a href="https://facctconference.org/2021/index.html">Fairness, Accountability, and Transparency</a> (FAcct) (virtual).
        - <strong>12/2020</strong> <a href="https://www.afciworkshop.org/afci-2020/accepted-papers">Paper</a> presentation at the NeurIPS workshop <a href="https://www.afciworkshop.org/">Algorithmic Fairness through the Lens of Causality and Interpretability</a> (virtual).
        - <strong>12/2020</strong> Program Committee/Reviewer for the NeurIPS workshop <a href="https://nips.cc/virtual/2020/protected/workshop_16139.html">ML for the Developing World (ML4D)</a> (virtual).
        - <strong>08/2020</strong> Paper presentation at the <a href="https://ww2.amstat.org/meetings/jsm/2020/index.cfm">Joint Statistical Meetings</a> (virtual).
        - <strong>04/2020</strong> Presentation at the <a href="https://sites.google.com/view/aiandsocialgood/aisoc20">CMU Symposium on AI and Social Good</a> in Pittsburgh, PA.
        - <strong>01/2020</strong> <a href="https://dl.acm.org/doi/abs/10.1145/3351095.3372851">Paper</a> presentation by colleague <a href="https://scholar.google.com/citations?user=8U7d-_MAAAAJ&hl=en">Amanda Coston</a> at the <a href="https://facctconference.org/2020/">ACM Conference on Fairness, Accountability, and Transparency (FAT*)</a> in Barcelona, Spain.
        - <strong>12/2019</strong> <a href="https://cpb-us-w2.wpmucdn.com/sites.coecis.cornell.edu/dist/a/238/files/2019/12/Id_92_final.pdf">Paper</a>/<a href="/files/NeurIPS_CausalML_2019_poster.pdf">poster</a> presentation at NeurIPS workshop <a href="https://tripods.cis.cornell.edu/neurips19_causalml/"> &lsquo;&lsquo;Do the Right Thing&rsquo;: Machine Learning and Causal Inference for Improved Decision Making</a> in Vancouver, CA.
        - <strong>12/2019</strong> <a href="https://sites.google.com/view/ml4d/team?authuser=0">Program Committee/Reviewer</a> for the NeurIPS workshop <a href="https://sites.google.com/view/ml4d/home">ML for the Developing World (ML4D)</a> in Vancouver, CA.
        - <strong>12/2019</strong> Travel grant for NeurIPS in Vancouver, CA.
        - <strong>05/2019&mdash;08/2019:</strong> Data Scientist internship at Google in Mountain View, CA.
        - <strong>05/2019</strong> <a href="/files/ACIC_2019_poster.pdf">Poster</a> presentation at the <a href="https://www.mcgill.ca/epi-biostat-occh/seminars-events/atlantic-causal-inference-conference-2019">Atlantic Causal Inference Conference</a> in Montreal, CA.
        - <strong>04/2019</strong> <a href="/files/SIGBOVIK_2019_paper.pdf">Paper</a> presentation at <a href="http://sigbovik.org/2019/">SIGBOVIK</a> in Pittsburgh, PA.
        - <strong>01/2019:</strong> <a href="/files/AIES_2019_poster.pdf">Poster</a> presentation at the <a href="https://www.aies-conference.com/2019/index.html">AAAI/ACM Conference on Artificial Intelligence, Ethics, and Society (AIES)</a> in Honolulu, HA.
        - <strong>01/2019:</strong> Travel grant for the <a href="https://www.aies-conference.com/2019/index.html">AAAI/ACM Conference on Artificial Intelligence, Ethics, and Society (AIES)</a> in Honolulu, HA.
        - <strong>07/2018:</strong> <a href="/files/EDM_2018_paper.pdf">Paper</a> presentation at the Doctoral Consortium at the <a href="https://educationaldatamining.org/EDM2018/">Educational Data Mining</a> conference in Buffalo, NY.
        - <strong>06/2018&mdash;08/2018:</strong> Data Scientist internship at Google in New York City.
        - <strong>06/2018:</strong> <a href="/files/Classification_Society_2018_poster.pdf">Poster</a> presentation at the <a href="https://tcs.wildapricot.org/event-2841576">Classification Society Meeting</a> in Stony Brook NY.
        - <strong>05/2018&mdash;08/2018:</strong> Data Science internship at Box in Redwood City, CA.
        - <strong>05/2018:</strong> <a href="/files/ACIC_2018_poster.pdf">Poster</a> presentation at the <a href="https://www.cmu.edu/acic2018/">Atlantic Causal Inference Conference</a> in Pittsburgh, PA.
        - <strong>11/2017:</strong> National finalist at the <a href="https://www.citadel.com/careers/the-data-open/">Citadel Data Open</a> in New York, NY.
        - <strong>09/16/2017:</strong> <a href="https://www.cmu.edu/dietrich/news/news-stories/2017/november/statistics-datathons.html">Winner</a> of the Citadel Data Open datathon at Carnegie Mellon, with fellow students <a href="https://www.niccolodalmasso.com">Nic Dalmasso</a>, <a href="https://www.linkedin.com/in/kwangho-joshua-kim/">Kwangho Kim</a>, and <a href="https://www.linkedin.com/in/chirag-nagpal-a0248562/">Chirag Nagpal</a>. (550+ student applications, around 125 students selected to compete)
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
      background:
        color: '#ffffff'  # White
---
