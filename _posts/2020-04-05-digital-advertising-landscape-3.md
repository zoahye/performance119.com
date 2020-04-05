---
layout: post
permalink: /digial-advertising-tech-landscape-3/
title: 'Digital Advertising Technology Landscape에 대해 알아보기 -3편-'
date: 2020-04-05 14:30:00 +09:00
feature: '/img/posts/04/bg-post-thumb-04.png'
background: '/img/posts/04/bg-post-header-04.png'
categories:
  - intro
tags:
  - Programmatic
  - AdTech
  - DigitalAdvertising
  - DSP
  - DMP
  - SSP
description: 'Programmatic Ad의 근간인 DSP, SSP, DMP(+Data Suppliers)에 대하여'
---



## Digital Advertising Technology Landscape에 대해 알아보기 –3편–

디지털 광고 기술 생태계 살펴보기, (드디어 대망의) 마지막!



디지털 랜드스케이프 마지막 포스팅인 이번편에서는 Programmatic Ad의 근간인 DSP, SSP 그리고 DMP와 Data provider들이 제공하는 오디언스 데이터의 종류에 대해 알아보고자 한다.

 

**>>DSP(Demand Side Platform)**

DSP, 즉 Demand Side Platform이라 함은 광고주 및 에이전시가 Digital Ad Marketplace(Ad exchanges, Ad networks, PMP, PG, etc.)상에서 디지털 광고 지면/인벤토리를 더 솝쉽게 구매할 수 있도록 도와주는 온라인 플랫폼이다. DSP는 하나의 플랫폼에서 A to Z까지 실행가능한 매우 똑똑하고 편리한 Ad Buying Platform이다. 

① DSP를 통해 국내외 광범위한 광고 인벤토리를 저렴한 가격에 손쉽게 구매할 수 있으며,

② 실시간으로 광고 성과를 모니터링할 수 있어, 광고주 KPI에 맞춘 캠페인 퍼포먼스 최적화 또한 가능하다.

③ 아울러 다양한 항목과 기준에 대한 맞춤 리포트 생성이 가능하기 때문에 광고 다방면의 광고 성과 측정이 가능하다.

이 모든 것들이 DSP라는 하나의 인터페이스로 구성되어 있으니 그야말로 일석삼조! (쏘리질러!)



![DSP](/img/posts/04/dsp.JPG)



정리해보자면 DSP는 RTB(Real Time Bidding) 환경에서 미디어 인벤토리를 구매할때 단 시간에 수 많은 Ad Exchange의 지면을 구매할 수 있게 도와주며, 비딩과 리포팅도 하나의 인터페이스로 확인할 수 있도록 지원한다.

Google의 AdX인 Doubleclick AdX를 비롯하여 OpenX, AppNexus와 같은 Ad exchange들은 광고주로 하여금 실시간으로 원하는 광고 인벤토리에 비딩하고 입찰에 참여할 수 있는 Marketplace를 제공한다.

이때 3rd party data provider들을 통해 수집된 데이터를 DSP에 연동하여 오디언스 데이터를 활용한 인벤토리 구매도 가능하다. (☜ 중요) 다양한 Dataset을 타겟 오디언스에 맞게 맞춤 조합하여 세그먼트화한 다음, 해당 오디언스로 식별되는 유저에게 광고를 노출하게 된다면 캠페인 효율은 훨씬 더 높아지게 될것이다.

ex. DSPs - DV360(Display & Video 360), TTD(The Trade Desk), AppNexus, MediaMath, Adobe DSP(구 Tubemogul), DataXu, etc.



**>>DMP(Data Management Platform)**

DMP는 다양한 Data Suppliers(데이터 공급자-쿠키 기반, 패널 데이터 기반 등등)로부터 제공되는 오디언스 데이터들을 수집하고, 저장하며, 개별 기준에 맞추어 패키지화 or 카테고리화 하는 데이터 기술 플랫폼이다. 이렇게 DMP 내 패키지화, 카테고리화된 데이터들은 다양한 Ad Tech 플랫폼과 기술적 연동이 가능하여, 각 파트너사들이 손 쉽게 해당 데이터를 목적에 맞게 활용할 수 있도록 도와준다.



![DSP](/img/posts/04/dmp.JPG)



이처럼 DSP는 여러 Data supplier들로부터 수집 및 가공한 데이터를 광고주, 매체사, 그리고 다른 여러 Ad Tech 회사들에게 일정의 수수료를 받고 이용할 수 있도록 한다.  이렇게 패키지화된 오디언스 데이터는 맞춤 타겟을 만들고 디지털 캠페인 성과를 최적화하기 위해서 사용되게 된다. 

국내 굴지의 매체사/애드 네트워크사들이 자체적으로 보유한 DMP(SK planet-11번가 구매 데이터 보유, 와이더플래닛-신한카드 데이터 보유) 외에도, 글로벌리 프로그래매틱 광고에 자주 사용하고 있는 DMP는 Eyeota, Oracle(Bluekai), Adobe, Data allience, LiveRamp 등이 있으며 이 외 글로벌 광고주의 경우 자체적으로 보유한 DMP들이 있어 해당 DMP를 광고 운영에 쓰이는 DSP에 연동하여 캠페인을 진행하기도 한다. 

Global DMP를 통해 타겟팅 가능한 오디언스 데이터 항목들은 성별/연령별로 나누어진 Demographic 데이터를 포함해 소득 수준, 직업(Professional), 관심사(Interest), 구매의도(Intent), 생애주기(며칠 이내, 몇 개월 이내 비행기 티켓을 구매한, 기저귀를 구매한 사람) 등 아주 세밀한 분야 및 단위까지도 타겟팅 가능하다. 

반면, 광고주 DMP를 연동하여 오디언스 타겟팅을 진행하는 경우에는 주로 1st party data(사이트 방문자, CRM data 등)를 집중 타겟팅하거나, 1st party data를 기반으로 Look-alike(유사 고객) 세그먼트를 형성하여 타겟팅하는 경우가 많다. 이 경우 주로 퍼포먼스형(Lead 생성, CPA 캠페인) 캠페인에서 사용되는 Dataset들이다. *- 사담: 글로벌 광고주 DMP로는 Adobe나 Saleforce DMP를 주로 사용하는 것 같다. (아 물론, 제 광고주만 그럴수도 있습니다..ㅎ..)*



**>>SSP(Supply Side Platform)**

SSP, Supply Side Platform은 광고주가 아닌 매체사를 위한 기술 플랫폼으로 매체사들이 여러 Ad Exchange와 Ad Network에 그들이 보유한 인벤토리를 손 쉽게 판매하고 운영할 수 있도록 도와준다.



![SSP](/img/posts/04/ssp.JPG)



SSP는 매체사들이 저마다의 수익을 최적화할 수 있도록 돕는 툴이다. 즉, 매체사들로 하여금 Ad Exchange 및 Ad Network에  자사의 인벤토리를 내놓을 때 보다 효율적으로 판매할 수 있는 플랫폼을 제공해준다. 

좀 더 풀어서 설명하자면, 매체사가 그들의 가용 인벤토리를 SSP에 내놓을 때 ⒜최저 입찰 금액(floor price), ⒝인벤토리 구매 대상자 뿐만 아니라 ⒞자신의 매체에 실릴 광고주 혹은 광고물 유형등을 선택하여 자사 인벤토리의 판매 선호도를 설정할 수 있게 한다.

글로벌 SSP로는 Rubicon, PubMatic, Freewheel 등이 있으며, 국내 SSP로는 ADOP가 있다. *- 사담: 이전 회사에서 일할 때, Freewheel로 Dailymotion 비디오 인벤토리를 구매해본 적이 있는데, SSP 인터페이스는 전체적인 UI가 DSP랑은 또 사알짝 달라서 헤맸던 기억이 있다...SSP는.... 아직도 어려워....*



이상으로 Digital Advertising Landscape 리뷰는 끝!

물론 KTX만큼 (어쩌면 더)빨리 변하는 디지털 광고 환경이라, 추후 중요 플랫폼이나 벤더가 나타나게 된다면 지속적으로 업데이트 할 예정이다. 일단 오늘은.... 여기까지....



