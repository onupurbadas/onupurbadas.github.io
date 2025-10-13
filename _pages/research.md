---
layout: page
title: Research
permalink: /research/
description: 
nav: false
nav_order: 2
display_categories: [research]
horizontal: false
---
  <p>My current research is guided by three central questions:</p>
  <ol>
  <li> (i) How does the representation of historically marginalized groups in local institutions influence environmental outcomes? </li>
  <li>(ii) Under what conditions do policies aimed at redistributing power lead to substantive changes environmental outcomes? </li>
  <li> and (iii) Reversing the lens: How do environmental stressors shape mental health and well-being?</li>
  </ol>

  <p> I continue to explore environmental justice in the context of local environmental governance. Broadly, I care about how environmental, social, and economic systems interact to shape well-being and inequality. Looking ahead, I aim to explore how environmental stressors affect mental health, how institutional norms shape behavior (especially in economics), and how global consumerism drives environmental harm. </p>

<h3>Current Papers</h3>

<h4>Job Market Paper</h4>
<h4><strong>Political Representation, Forest Cover, and Development in Rural India</strong></h4>

<p>
  <a href="/projects/representation-and-conservation">Read more →</a> |
  <a href="https://onupurbadas.github.io/assets/pdf/caste_development_and_forests_draft_onupurba_das.pdf" target="_blank">
    <i class="fas fa-file-pdf" title="Download PDF"></i>
  </a> |
  <a href="javascript:void(0);" onclick="toggleAbstract('abstract1')">
    <i class="fas fa-align-left"></i> Short Abstract
  </a>
</p>

<div id="abstract1" style="display: none; margin-top: 0.5em;">
  <p>This paper examines how political representation for historically marginalized communities shapes local economic activity and environmental stewardship. Leveraging the quasi‑random rotation of chairperson reservations for Scheduled Castes (SCs) and Scheduled Tribes (STs) across 5,000 village councils in Karnataka, India, over five election cycles (1994–2010), I estimate causal effects on satellite‑measured night‑time lights and forest cover. SC/ST-led councils see higher local economic activity but lower forest cover, with larger effects under ST leadership. These patterns reveal trade‑offs between development and conservation and point to the need for policies that enable marginalized leaders to pursue development without depleting the natural resources their communities depend on.</p>
</div>

<h4>Women's Leadership and Deforestation in Rural India</h4>
<p><strong>with <a href="https://people.umass.edu/jmullins/index.html" target="_blank">Jamie T. Mullins</a> (2025)</strong></p>

<p>
  <a href="https://onupurbadas.github.io/assets/pdf/women_and_forests_draft_onupurba_das.pdf" target="_blank">
    <i class="fas fa-file-pdf" title="Download PDF"></i>
  </a> |
  <a href="javascript:void(0);" onclick="toggleAbstract('abstract2')">
    <i class="fas fa-align-left"></i> Short Abstract
  </a>
</p>

<div id="abstract2" style="display: none; margin-top: 0.5em;">
  <p>This paper examines the impact of women’s leadership in village councils on forest conservation in rural India. Using randomized reservations for women chairs and vice-chairs in Karnataka's village councils from 1992 to 2010, we analyze changes in forest cover using satellite data. Forest cover shows the greatest improvement when both positions are held by women over multiple election terms, emphasizing the importance of sustained leadership and multiple positions of power. However, such instances occur less frequently than expected under randomization, raising questions about structural and societal barriers to real power transfer.</p>
</div>

<h4>Temperature, Particulate Matter, and Mental Health in India</h4>
<p><strong>with <a href="https://www.ashoka.edu.in/profile/kavita-sardana/" target="_blank">Kavita Sardana</a> and <a href="https://people.umass.edu/jmullins/index.html" target="_blank">Jamie T. Mullins</a> (2024)</strong></p>

<p>
  <a href="https://onupurbadas.github.io/assets/pdf/Temperature_PM_and_Mental_Health_in_India_onupurba_das.pdf" target="_blank">
    <i class="fas fa-file-pdf" title="Download PDF"></i>
  </a> |
  <a href="javascript:void(0);" onclick="toggleAbstract('abstract3')">
    <i class="fas fa-align-left"></i> Short Abstract
  </a>
</p>

<div id="abstract3" style="display: none; margin-top: 0.5em;">
  <p>This paper investigates the link between exposure to high temperatures and particulate matter and self-reported mental health in India. Using data from a massive nationwide survey, we find that environmental stressors are predictive of poorer mental well-being. Interestingly, harms from particulate matter exposure are lower on hot days, suggesting an adaptive spillover effect.</p>
</div>

<hr style="margin: 2em 0;">

<h3>Working Papers</h3>

<h4>Impact of Pneumonia Type on Mortality, Morbidity, and Resource Use in U.S. Hospitalized Patients</h4>
<p><strong>with <a href="https://www.umass.edu/nursing/about/directory/karen-giuliano" target="_blank">Karen Giuliano</a>, <a href="https://www.csus.edu/faculty/b/dibaker/" target="_blank">Dian Baker</a> and <a href="https://www.umass.edu/social-science-research/about/directory/jessica-pearlman" target="_blank"> Jessica Pearlman</a></strong></p>

<h4>Recognition and Reward in Economics</h4>
<p><strong> with <a href="https://umanitoba.ca/arts/arpita-biswas" target="_blank">Arpita Biswas</a> (2025)</strong></p>

{% assign categorized_projects = site.projects | where: "category", "research" %}
{% assign sorted_projects = categorized_projects | sort: "importance" %}
<div class="row row-cols-1 row-cols-md-3">
  {% for project in sorted_projects %}
    {% include projects.liquid %}
  {% endfor %}
</div>

<script>
  function toggleAbstract(id) {
    var el = document.getElementById(id);
    el.style.display = (el.style.display === "none") ? "block" : "none";
  }
</script>
