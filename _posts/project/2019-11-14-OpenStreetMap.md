---
layout: single
title: OSM(OpenStreetMap)
toc: true
toc_sticky: true
toc_label: 목차
author_profile: true
read_time: true
comments: true
share: true
related: true
categories:
- Project
tags: [mapapi]
---

# GoogleMap 대신 OpenStreetMap 사용하기

***

### 계기


기획과 개발을 혼자서 하기 때문에, 바로 개발을 시작했다.

앵귤러/아이오닉 기반으로 프로젝트를 세팅했고, 서버사이드는 화면단이 어느 정도

구성됐을 때 작업을 시작할 생각이다. 

처음 반기는 화면을 슬라이드로 구성하고, 메인 페이지는 사용자에 위치에 기반한

맵을 출력하고 싶었다. 따라서 구글 맵을 적용할 생각이었으나, 구글 맵의 놀라운

지형지물 재현력들은 내 장난감같은 컨셉의 스터디 앱에 어울리지 않아보였다.

따라서 구글맵 커스터마이징(https://mapstyle.withgoogle.com/) 사이트를

찾았으나, 한국의 지도만 스타일링이 안되는 것을 보고 깔끔하게 포기한다.

커스터마이징할 수 있는 지도를 찾고 찾다가, OpenStreetMap에 대한 정보를 발견한다.

![osm](../assets/img/project/osm.png)

위키사전과 같이 모두가 만들어나가는 지도이기 떄문에, 정확도가 단점이라고 할 수 있지만,

내 프로젝트는 활동 반경에 대한 위치 정보가 필요하기 때문에 이 정도의 정확도면 훌륭하다.


