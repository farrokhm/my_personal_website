---
abstract: Introduction) About 30% of epilepsy patients are resistant to treatment with antiepileptic drugs, and   only a minority of these are surgical candidates. A recent therapeutic approach is the application of electrical   stimulation in the early phases of a seizure to interrupt its spread across the brain. To accomplish this,       energy-efficient seizure detectors are required that are able to detect a seizure in its early stages. Methods)   Three patient-specific, energy-efficient seizure detectors are proposed in this study (i) random forest (RF);   (ii) long short-term memory (LSTM) recurrent neural network (RNN); and (iii) convolutional neural network (CNN).   Performance evaluation was based on EEG data (n = 40 patients) derived from a selected set of surface EEG
  electrodes, which mimic the electrode layout of an implantable neurostimulation system. As for the RF input, 16   features in the time- and frequency-domains were selected. Raw EEG data were used for both CNN and RNN. Energy   consumption was estimated by a platform-independent model based on the number of arithmetic operations (AOs)     and memory accesses (MAs). To validate the estimated energy consumption, the RNN classifier was implemented on   an ultra-low-power microcontroller. Results) The RNN seizure detector achieved a slightly better level of       performance, with a median area under the precision-recall curve score of 0.49, compared to 0.47 for CNN and     0.46 for RF. In terms of energy consumption, RF was the most efficient algorithm, with a total of 67k AOs and     67k MAs per classification. This was followed by CNN (488k AOs and 963k MAs) and RNN (772k AOs and 978k MAs),   whereby MAs contributedmore to total energy consumption. Measurements derived from the hardware implementation   of the RNN algorithm demonstrated a significant correlation between estimations and actual measurements.         Discussion) All three proposed seizure detection algorithms were shown to be suitable for application in         implantable devices. The applied methodology for a platform-independent energy estimation was proven to be       accurate by way of hardware implementation of the RNN algorithm. These findings show that seizure detection can   be achieved using just a few channels with limited spatial distribution. The methodology proposed in this study   can therefore be applied when designing new models for responsive neurostimulation.
author_notes:
- Equal contribution
- Equal contribution
authors:
- admin
- Marc Zöllin
date: "2022-03-04T00:00:00Z"
doi: ""
featured: false
image:
  focal_point: ""
  preview_only: false
# caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
projects: []
publication: '*Frontiers in Neurology*'
publication_short: ""
publication_types:
- "2"
publishDate: "2017-01-01T00:00:00Z"
#slides: example
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus
#  ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.
tags:
#- Source Themes
title: A Comparison of Energy-Efficient Seizure Detectors for Implantable Neurostimulation Devices
#url_code: https://github.com/wowchemy/wowchemy-hugo-themes
#url_dataset: ""
url_pdf: https://www.frontiersin.org/articles/10.3389/fneur.2021.703797/full
#url_poster: ""
#url_project: ""
#url_slides: ""
#url_source: ""
#url_video: ""
---

<!---{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).--->
