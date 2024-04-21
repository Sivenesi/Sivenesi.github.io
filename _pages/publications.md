---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
Subramoney, S, Joshi, S. H, Wedderburn, C.J., Lee, D., Roos, A., Woods, R.P., Zar, H.J., Narr, K.L., Stein, D.J., Donald, K.A. (2022) The impact of Prenatal Alcohol Exposure (PAE) on gray matter volume and cortical surface area of 2-3 year old children in a South African birth cohort.

Wedderburn, C. J., Subramoney, S., Yeung, S., Joshi, S. H., Narr, K. L., Rehman, A. M., Roos, A., Ipser, J., Robertson, F. C., Groenewold, N. A., Gibb, D. M., Zar, H. J., Stein, D. J., & Donald, K. A. (2020). Neuroimaging young children and associations with neurocognitive development in a South African birth cohort study. NeuroImage, 219, 116846. https://doi.org/10.1016/j.neuroimage.2020.116846.

Subramoney, S., Eastman, E., Adnams, C., Stein, D. J., & Donald, K. A. (2018). The early developmental outcomes of prenatal alcohol exposure: A review. Frontiers in neurology, 9, 1108. 

Meiring, L., Subramoney, S., Thomas, K. G., Decety, J., & Fourie, M. M. (2014). Empathy and helping: Effects of racial group membership and cognitive load. South African Journal of Psychology, 44(4), 426-438.



{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
