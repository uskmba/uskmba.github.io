---
layout: default
title: "Review: Water conduction through the hydrophobic channel of a carbon nanotube"
categories: ["Paper Review", "CNT"]
---

# The seminal paper of nanofluidics

**Paper Title**: Water conduction through the hydrophobic channel of a carbon nanotube  
**Authors**: G. Hummer et al.

![CNT water permeation](/assets/images/CNT_water.png)


## Summary
This paper suggests that water molecules spontaneously and permeate through a carbon nanotube (CNT) channel. representing a hydrophobic nanochannel, with immensely high speed because of the unique string-like sturcture of water molecules inside the tube. 



## Critique
In 1990's, Whether water molecules could penetrate into a super confined space was a matter of ongoing debate. The majority of sicence community expressing skepticism, believing that the hydrogen bond network in the bulk reservoir would deter the spontaneous entry of water molecules. Atoms of a water molecule possess partial charge, which induce substantial electrostatic interaction to form hydrogen bond between water molecules. While water molecules is believed to have an average of 3.4 hydrogen bond in a quiescent condition, when the diameter of CNT reaches under 1 nm, water molecules inside the channel are expected to lose a part of bonding netwrok before entrance because they run out of physical space to interact with other molecules. 

However, with Molecular Dynamics (MD) simulation, Hummer et al. {% include cite.html id="hummer2001water" %} predicted that water molecules can voluntarily move inside sub-nanometer carbon nanotubes, forming single-file water chains. Later studies provided deeper thermodynamic explanations for this phenomenon. Notably, Pascal et al. {% include cite.html id="pascal2011entropy" %} demonstrated that the gain in translational and rotational entropy of confined water molecules compensates for the loss of hydrogen bonds, serving as a primary thermodynamic driver for spontaneous CNT filling.




## 한글 코멘트

첫 분석 글을 작성하며 한글로 짧게나마 내용을 덧붙이는 이유를 간단하게 설명드리고 싶습니다. Nanofluidics (나노유체)는 신생 분야로 그 역사가 매우 짧지만 에너지, 센싱, 컴퓨팅, 제염과 같이 새로운 메커니즘으로부터 기존의 한계를 돌파할 수 있는 돌파구가 필요한 분야에서 많은 관심을 받고 있습니다. 한국에서 이 분야에 관심을 가지는 분들이 쉽게 내용을 접할 수 있는 작은 기회를 만들고자 영어 버전의 내용을 모두 담지는 않지만 좀 더 제 주관이 담긴 한글 코멘트를 붙이고자 합니다. 영한 모두 제 주관이 포함되어 있으며 미천한 저의 연구 실력으로 정확한 정보가 담기지 않을 수 있습니다. 모든 내용을 너무 믿지 마시고 "이러한 분야가 있고, 어떠한 기작을 설명하는구나" 정도로 봐주시면 감사하겠습니다. 

## Korean

일반적으로 물 분자는 평형 상태에서 3.4개의 수소결합을 하고 있습니다. 그런데 유효공간을 따지면 *물 분자가 딱 1개* 들어갈 수 있는 지름의 크기를 가진 *"무려 소수성"*의 CNT 내부로 물 분자들이 수소 결합을 잃어가면서(내부 공간이 매우 좁으니 최대 2개의 물 분자랑 상호작용을 할 수 밖에 없을 것) 자발적으로 들어갈 것이라고 예상하기는 매우 어려웠습니다. 하지만 이 논문은 원자 수준의 모델링을 적용한 분자 동역학을 이용해서 물 분자가 *자발적으로* 직경 0.8 nm CNT 내부로 들어갈 수 있으며 이 CNT를 통해 물 분자가 미끌어지는 속도가 매우 빠르다는 것을 예측합니다. 이때 *CNT 내부 물 분자의 구조*가 화학적 포텐셜에 주요한 영향을 미치고, *소수성* 또한 주요한 요소 중 하나임을 보여줍니다. 

이 발표는 CNT를 물 분자 1개 수준의 크기를 가진 **채널**로 이용할 수 있는 가능성을 보여주고 nanofluidics하는 학문의 개시를 알려주는 기념비적 연구입니다. 재밌는 점은 저자인 Hummer는 유체역학을 전문으로 하는 연구자보다는 computational biology 연구에 집중하는 분이라는 것입니다. 사실 이렇게 극한으로 작은 크기를 가진 채널에서 물이나 이온(이후 리뷰에서 이온의 전달에 대한 연구가 포함될 것입니다)의 이동이 발생한다는 사실 자체는 알고 있었습니다. 바로 생명체의 막에 존재하는 물, 이온 채널이 나노미터 단위의 직경을 가지고 있기 때문이죠. 