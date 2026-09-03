Chen Qiqian Homepage
====================

Static personal homepage published at https://www.cqqqwq.com/.

Local preview
-------------

Open the Run and Debug view in VS Code and launch "Preview Homepage". The
configuration opens Homepage/index.html directly in Microsoft Edge; no build
step or development server is required.

Updating public resumes
-----------------------

Run these commands from the personal workspace root:

    typst compile resume/resume_en_pub.typ Homepage/cv_en.pdf
    typst compile resume/resume_cn_pub.typ Homepage/cv_cn.pdf

Only the public resume variants belong on this site. Never copy the private or
direct-application variants into Homepage.

Deployment and indexing
-----------------------

GitHub Pages publishes the main branch with the custom domain declared in
CNAME. Keep canonical URLs, robots.txt, and sitemap.xml on
https://www.cqqqwq.com/. Update sitemap.xml's lastmod value when public page
content changes. The public resume PDFs are downloadable from the page but are
excluded from crawler access in robots.txt.

Credits
-------

Based on the Read Only template by HTML5 UP (html5up.net), licensed under CCA
3.0. Uses Font Awesome, jQuery, Scrollex, and Responsive Tools.