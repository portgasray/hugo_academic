---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: A novel distribution for representation of 6D pose uncertainty
subtitle: ''
summary: ''
authors:
- Lei Zhang
- Huiliang Shang
- Yandan Lin
tags: []
categories: []
date: '2022-01-01'
lastmod: 2022-07-30T15:42:30+08:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-07-30T07:42:30.537997Z'
publication_types:
- '2'
abstract: The 6D Pose estimation is a crux in many applications, such as visual perception,
  autonomous navigation, and spacecraft motion. For robotic grasping, the cluttered
  and self-occlusion scenarios bring new challenges to the this field. Currently,
  society uses CNNs to solve this problem. The CNN models will suffer high uncertainty
  caused by the environmental factors and the object itself. These models usually
  maintain a Gaussian distribution, which is not suitable for the underlying manifold
  structure of the pose. Many works decouple rotation from the translation and quantify
  rotational uncertainty. Only a few works pay attention to the uncertainty of the
  6D pose. This work proposes a distribution that can capture the uncertainty of the
  6D pose parameterized by the dual quaternions, meanwhile, the proposed distribution
  takes the periodic nature of the underlying structure into account. The presented
  results include the normalization constant computation and parameter estimation
  techniques of the distribution. This work shows the benefits of the proposed distribution,
  which provides a more realistic explanation for the uncertainty in the 6D pose and
  eliminates the drawback inherited from the planar rigid motion.
publication: '*Micromachines*'
doi: 10.3390/mi13010126
links:
- name: URL
  url: https://www.mdpi.com/2072-666X/13/1/126
---
