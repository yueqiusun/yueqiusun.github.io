---
title: "Optimization-of-Responsive-Neurostimulation-RNS-Therapy-through-Data-Mining-Approaches"
collection: 'research'
permalink: /research/RNS
venue: "New York University, Department of Neurology"
date: 2018-06-01 - present
location: "New York, US"
---


"Optimization of Responsive Neurostimulation (RNS)" is a project that (aims to provide data-driven guidence to the physicians who examine patients with RNS devices) or (propose to help explore the optimzal settings for the electrical stimulation of the RNS device). We built a reliable classifier that classifier clinical performance based on available background EEG data and examine the neural science intuition behind the machine learning model. Also, we investigate how sleep influence the predicting accuracy of the classifier.



Methods
======




Diary
======
October: 
August:
Built
July: 
Got familer with the problem setting, formulate the methodology, read in EEG data, calculate relative band powers (delta, theta, alpha, beta, lowgamma, highgamma, all) of EEG signals. Identify scheduled EEG using Z scores(failed), flatline method(identify the start of the stimulation by the presense of a flat line in EEG segments) (partially failed, too few data left). The solution we used at that time was to regard the EEG segments in certain time intervals as scheduled EEGs.(not perfect, will contain false positive, but that's the best we can do at that time. Got the labeled data later).


Backgroung
======
Some patients with refractory epilepsy are implanted with a responsive neurostimulation device (RNS NeuroPace, Inc., Mountain View, CA).  The RNS is an FDA-approved device which delivers brief pulses of electrical stimulation upon detection of abnormal EEG patterns to terminate seizures. Physicians program RNS detection and stimulation parameters to potentially reduce seizure duration and frequency. Current practice is empirically driven, and physicians are limited by a lack of evidence for guiding stimulation settings.  A data-driven approach could help physicians reach optimal therapeutic stimulation parameters more quickly, and avoid seizure exacerbation.