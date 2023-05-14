---
layout: post
title: "Understanding Diffusion Models: A Unified Perspective 논문 리뷰"
subtitle: Diffusion Models 이해하기
categories: 
    - paper review
tags: 
    - Diffusion model
use_math: true
---

여러분은 Text를 입력하면 그림을 그려주는 DALL-E라는 AI 모델을 접해본 적이 있으신가요?  

딥러닝 연구를 하는 분이시라면 아마 한번쯤은 들어본 분들이 많을거라고 예상이 되는데요. 해당 논문에서 주어진 Text에 해당하는 Image를 생성하기 위해 사용된 Generative model이 바로 diffusion models입니다. 제가 처음 DALL-E를 접했을 때 조만간 음성쪽 도메인에서도 논문이 쏟아져 나오겠구나..라고 생각했었는데... 생각보다 더 빠르게 diffusion models를 도입하는 연구들이 쏟아져 나오고 있어서 언제 한번 Diffusion model을 대대적으로 정리하는 시간을 가져야겠다는 생각이 들었습니다. 그렇게 생각을 행동으로 옮기기까지 약 1년 반이 지난 것 같...(크흠);;  

어쨋든! 칼을 뽑았으니 무라도 베어보자는 심정으로 오늘은 Diffusion models의 전반적인 흐름(?)을 정리해놓은, 무려 CVPR에 나온 "Understanding Diffusion Models: A Unified Perspective" 논문을 리뷰해보려합니다. :)

### Introduction
Deep learning에서 generative model이라고 하면 보통 주어진 혹은 관측된 데이터 $x$의 분포 $p(x)$를 근사(approximation)하는 Neural Network를 학습한 후 해당 분포로부터 새로운 데이터 $\hat{x}$을 생성할 수 있는 모델을 의미하는데요. 데이터의 분포를 어떤 알려진 분포(e.g. Gaussian Distribution)로 가정하는 모델을 explicit density model이라고 하고 그렇지 않은 모델들은 implicit density model이라고 합니다. explicit density model의 대표적인 예는 Generative Adversarial Networks (GANs)으로 diffusion



### Reference
[Text-to-Image Diffusion Models in Generative AI: A Survey](https://arxiv.org/pdf/2303.07909.pdf)
[Understanding Diffusion Models: A Unified Perspective](https://arxiv.org/pdf/2208.11970.pdf)