---
layout: post
title: Gen-1 : Diffusion model now can make vids!
---



Gen-1은 Stable Diffusion의 architecture인 latent diffusion을 세상의 내놓은 runways의 새 diffusion model 이다.
비디오는 결국 시간에 따라 연속하는 frame들의 집합이다.
그렇다면 초당 10frame이라면 10초짜리 동영상은 결국 100 frames 즉, 100장의 사진인 셈이다.

예를들어 최초 1frame과 11frame은 정확히 1초간격에 있는 사진이자 영상의 재료가 된다.

이 모델의 핵심 input은 두가지가 된다.
Structure representation과 Content representation 두가지가 모델에 들어가게 된다.



Training 과정과 Inference 과정을 자세히 살펴보자.
