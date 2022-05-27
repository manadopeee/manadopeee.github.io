---
layout: post
title:  "Dataset Agumentation"
author: kei
categories: [ 머신러닝, 기초 ]
<!-- image: assets/images/17.jpg -->
---
Dataset
> 데이터셋은 기본적으로 Train dataset과 Test dataset으로 나눠짐\
> 여기서 Train dataset은 다시 Train, Validation으로 나눔\
> Validation과 Test의 차이는 Loss값을 보고 안 보고의 차이\
> Validation은 Train의 과적합을 막기 위해 Loss를 계산함(update는 안함)

Augmentation
> 데이터가 부족할 경우 데이터를 증강하기 위함
> Train dataset에만 적용(validation, test에는 적용하지 않음)
