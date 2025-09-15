---
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


I am a **Human–Computer Interaction education researcher**. My work explores how **diary studies** and **focus group discussions** can serve as pedagogical tools to foster **empathy, reflection, and collaborative design skills** in computing education. I pursue ways to make HCI concepts more tangible for students by bridging individual lived experience with group-based learning. Drawing from computer science education research, design theory, psychology of empathy, and learning sciences, I develop frameworks and tools—such as DiaryQuest—that integrate qualitative methods with computational analysis to support both teaching and research. I often collaborate with faculty and undergraduate researchers to design, evaluate, and refine these approaches, creating equitable learning environments where students learn to see technology through the eyes of diverse users.

I am a **leading instructor** with experience teaching **Professionalism in Computing (CS3604)** for two semesters, guiding nearly 200 undergraduate students in exploring ethical, social, and professional dimensions of computing. In addition, I have served as a Teaching Assistant for twelve semesters across a wide range of undergraduate and graduate computer science courses, including introductory programming (CS1 and CS2), data structures and algorithms, and advanced courses in Human–Computer Interaction. I hold the **Future Professoriate Certificate** from the Virginia Tech Graduate School and am an active member of the Virginia Tech Academy for Graduate Teaching Assistant Excellence (VT GrATE). My teaching philosophy emphasizes cultivating **enthusiasm for computing** while fostering reflective thinking, professional growth, and long-term career development.

I am expected to graduate in **2026** and am actively seeking **postdoctoral** or **academic opportunities**. I would be delighted to connect about potential openings, collaborations, or shared research interests. Please feel free to reach out to me at [jfan12@vt.edu](mailto:jfan12@vt.edu).

---


<h2 style="border-bottom:0; padding-bottom:0; margin-bottom:.25rem;">News &amp; Talks</h2>

<div class="news-box"
     style="height:200px; overflow-y:auto; padding:0.25rem 0.5rem;
            border-top:0; border-bottom:2px solid #333;">
  <dl class="news-list" style="margin:.5rem 0;">
    <dt style="font-weight:700; margin-top:.6rem;">Aug 2025</dt>
    <dd style="margin:0 0 .6rem 0; line-height:1.45;">
      With DU colleague <a href="#">Laurel Taylor</a>, I presented my paper
      <em>Design as Translation, Translation as Design: Toward Critical, Creative, and Ethical Pedagogies</em>
      at EduCHI 2025. Read the event recap <a href="#">here</a>.
    </dd>

    <dt style="font-weight:700; margin-top:.6rem;">July 2025</dt>
    <dd style="margin:0 0 .6rem 0; line-height:1.45;">
      I will be at the <a href="#">ACM RESPECT 2025</a> doctoral consortium as a discussant. Say hello :)
    </dd>

    <dt style="font-weight:700; margin-top:.6rem;">April 2025</dt>
    <dd style="margin:0 0 .6rem 0; line-height:1.45;">
      Invited talk at the <a href="#">ATLAS Colloquium</a>, CU Boulder:
      <em>Toward Critical, Ethical, Reflective, and Creative HCI Education Futures</em>.
    </dd>

    <dt style="font-weight:700; margin-top:.6rem;">Jan 2025</dt>
    <dd style="margin:0 0 .6rem 0; line-height:1.45;">
      In collaboration with <a href="#">AiiCE</a>, I moderated a <a href="#">panel</a> on developing accessibility content knowledge for computing educators.
    </dd>
  </dl>
</div>




















A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
