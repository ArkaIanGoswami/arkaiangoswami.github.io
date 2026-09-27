---
layout: page
title: "Research Interests"
permalink: /research/
---
I am primarily interested in sequential decision making under uncertainty, both theory and applications, particularly, in engineering systems (robotics, grids, networks, etc.) and, more recently, healthcare. Sequential decision making under uncertainty is a broad topic and encapsulates several channels, each with their own distinction. My focus is mainly on Reinforcement Learning. I would say I partition my engagement as 70% theory and 30% applications

Theory:
- I am pretty interested in the use of techniques from computer vision, diffusion, and geometry processing for Reinforcement Learning. A lot of work has been done in measuring dissimilarities (and thereby similarities) between shapes, objects, motion, patterns, etc. An important tool used in many such works is the use of Optimal Transport which studies the economics of transferring probability masses between distributions. My work has accounted for cases, where state and action spaces (or their product spaces) are the objects being compared to measure the extent of task dissimilarity in RL to enable policy reuse between arbitrarily incomparable spaces. The benefit of being able to do that is to reduce the data hungriness of RL as a consequence of repeated exploration - if one trains a model on a \emph{source task} then will that learned policy also perform well in a \emph{related task} or a \emph{completely different task}. The caveat is, however, that one does not have a holistic view of either set in its entirety for most non-trivial RL tasks. Our only window into the structure/geometry/topology of the sapces is through the deployment of policies. The more the policy \emph{covers}, the more detailed is our understanding of the structure. Some of our main goals are to
- Attach mathematically qualitative meaning to what related tasks mean and, in general, what do we understand by task similarity 
- Describe how much suboptimality is (or isn't) incurred when policies are transferred based on the previous point
- Is it possible for one to continue where the transported policy left off? As in, a monotone policy improvement to learn and correct the residual optimality slack?
- If all of the above are answered to at least a somewhat satisfactory standard, can we also go a step further to define a canonical source task given a suite? 
