---
layout: post
title: Value
description:  A measurement of the aggregate __Preference__ of a particular __World State__.
---

Given an Agent's __Value__ system $$ s_A $$ and __World Model__ $$ W_A $$ with $$ N_{W,A} $$ __States__, __Value__ is defined as $$ 
\begin{equation}
V(s_A, w_{A,k}) = \frac{1}{N_{W,A} - 1} \sum_{i = 1}^{N_{W,A}} P(s, w_{A,k}, w_{A,i}) 
\end{equation}
$$

Note that __Value__ is an ordinal metric as opposed to a cardinal one.