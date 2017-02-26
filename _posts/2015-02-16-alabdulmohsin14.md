---
title: Support vector machines with indefinite kernels
abstract: 'Training support vector machines (SVM) with indefinite kernels has recently
  attracted attention in the machine learning community. This is partly due to the
  fact that many similarity functions that arise in practice are not symmetric positive
  semidefinite, i.e. the Mercer condition is not satisfied, or the Mercer condition
  is difficult to verify. Previous work on training SVM with indefinite kernels has
  generally fallen into three categories: (1) positive semidefinite kernel approximation,
  (2) non-convex optimization, and (3) learning in Krein spaces. All approaches are
  not fully satisfactory. They have either introduced sources of inconsistency in
  handling training and test examples using kernel approximation, settled for approximate
  local minimum solutions using non-convex optimization, or produced non-sparse solutions.
  In this paper, we establish both theoretically and experimentally that the 1-norm
  SVM, proposed more than 10 years ago for embedded feature selection, is a better
  solution for extending SVM to indefinite kernels. More specifically, 1-norm SVM
  can be interpreted as a structural risk minimization method that seeks a decision
  boundary with large similarity margin in the original space. It uses a linear programming
  formulation that remains convex even if the kernel matrix is indefinite, and hence
  can always be solved quite efficiently. Also, it uses the indefinite similarity
  function (or distance) directly without any transformation, and, hence, it always
  treats both training and test examples consistently. Finally, it achieves the highest
  accuracy among all methods that train SVM with indefinite kernels with a statistically
  significant evidence while also retaining sparsity of the support vector set.'
layout: inproceedings
series: Proceedings of Machine Learning Research
id: alabdulmohsin14
month: 0
tex_title: Support vector machines with indefinite kernels
firstpage: 32
lastpage: 47
page: 32-47
order: 32
cycles: false
author:
- given: Ibrahim
  family: Alabdulmohsin
- given: Xin
  family: Gao
- given: Xiangliang Zhang
  family: Zhang
date: 2015-02-16
address: Nha Trang City, Vietnam
publisher: PMLR
container-title: Proceedings of the Sixth Asian Conference on Machine Learning
volume: '39'
genre: inproceedings
issued:
  date-parts:
  - 2015
  - 2
  - 16
pdf: http://proceedings.mlr.press/v39/alabdulmohsin14.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
