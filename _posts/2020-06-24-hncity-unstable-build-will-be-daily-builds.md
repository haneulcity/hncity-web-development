---
layout: post
title: "오늘부터, 하늘마을의 불안정 빌드가 일간 빌드 체제로 바뀝니다."
category: ['news', 'server']
---

안녕하세요, 하늘마을 프로젝트의 관리자 겸 개발자 종이상자입니다.

오늘부터 하늘마을 맵의 클라우드 이전이 완료되어, 앞으로는 크론탭을 이용한 자동화가 이뤄지게 됩니다.

이번 변경으로 체감할 수 있는 사항은 다음과 같습니다.

- 매일 오전 8시 30분, 그날의 일간 빌드(일자명 + Daily Build)라는 이름으로 하루치 맵 작업물이 올라옵니다. 작업량이 전혀 없을 경우에는 변동사항이 없으므로 올라오지 않을 수 있습니다.
- 기존에 Commits 탭에서 제공했던 각종 변경사항에 대한 기록을 더이상 하지 않습니다. 자동화로 인해 변경사항을 기록하기 까다로워졌을 뿐더러, 7월 중순 이후 다른 분들께도 개방되기 때문에 변동사항에 대한 취합이 어렵기 때문입니다.

내부적으로는 서버 운영에 앞서 테스트 차원에서 콘텐츠 백업 및 주기적인 백업 저장물 삭제가 이뤄집니다. 비록 예산 상의 문제로 이중화는 하지 못했으나, 적어도 서버 구조물 테러로 인한 작업물 리셋 문제를 최대한 줄이기 위함입니다.

현재 내부적으로는 거의 서버 인원을 모집하기만 하면 되는 상태에 놓여있습니다. Mojang이 1.16의 BE 출시와 동시에  Vanilla 서버도 같이 출시하여 이미 적용해 두었고, 서버 테스트는 이미 개별 자동화 스크립트의 동작 여부 확인을 마쳤기에  crontab의 정상 작동 여부만 확인하면 모든 작업이 마무리됩니다.

다만 제 개인적인 사정으로 인해 서버 운영이 7월 중순까지 어려울 것 같아, 신청을 제대로 받지 않고 있는 것뿐입니다.

만약 신청 기간(7월 1일~)에 앞서 지원 이메일을 보내고자 하시는 분이 있다면 보내주셔도 괜찮습니다. 이와 관련하여 불이익을 적용하지는 않을 것입니다.

하늘마을 프로젝트와 함께하여 주셔서 감사합니다.