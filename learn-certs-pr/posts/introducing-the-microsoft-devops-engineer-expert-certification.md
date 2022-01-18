---
title: 'Microsoft DevOps Engineer Expert 인증 소개: 알아야 할 사항 | Microsoft Docs'
description: 'Microsoft DevOps Engineer Expert 인증 소개: 알아야 할 사항'
documentationcenter: NA
author: micsullivan
ms.topic: article
ms.tgt_pltfrm: NA
ms.workload: NA
ms.date: 07/30/2019
ms.author: msulliv
ms.prod: non-product-specific
ms.openlocfilehash: 69baf14ab86556841937918909df50a5a062ebdb
ms.sourcegitcommit: b69fd4d0c808e4780010278f0cb189c2246f8dc0
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 12/28/2021
ms.locfileid: "132111445"
---
# <a name="introducing-the-microsoft-devops-engineer-expert-certification-what-you-need-to-know"></a>Microsoft DevOps Engineer Expert 인증 소개: 알아야 할 사항

게시: 2019년 2월 26일, **Liberty Munson(Microsoft)**

___

아시다시피 Microsoft는 2018년 11월 4일에 시험 [AZ-400: Microsoft Azure DevOps Solutions](https://www.microsoft.com/learning/exam-AZ-400.aspx)를 베타 버전으로 출시했습니다. 베타 기간 동안 우리는 많은 핵심(그리고 열정적인) 내부 및 외부 관련자로부터 놀라울 정도로 많은 의견과 피드백을 받았으므로 몇 가지 핵심 문제를 조사하는 동안 베타 시험을 일시적으로 중단했습니다. 많은 분들이 알고 계시겠지만, 우리는 지난 몇 년 동안 DevOps 시험/인증을 게시하려고 여러 번 시도했지만 그렇게 하지 못했습니다. (가장 최근 사례는 2018년 Ignite에서 이 콘텐츠 영역을 다루기 위한 시험 70-537 및 70-538에 기반한 인증을 발표한 것입니다. 나는 여전히 그 시험에 무슨 일이 일어났는지에 대한 질문을 받습니다. 역할 기반 인증으로의 전환과 AZ-400이 그 시험에 일어난 일입니다. AZ-400은 537 및 538에 있었던 콘텐츠를 다룹니다.) 그러므로 AZ-400 베타를 일시 중지하고 시간을 내어 제기된 문제를 해결했는지 확인했습니다. 이 시험과 인증이 Azure DevOps Engineer 직무를 반영하는지 확인하고 싶습니다. 시험을 준비할 때 알아야 할 몇 가지 사항은 다음과 같습니다.

1. DevOps는 매우 광범위한 영역이기 때문에 시험 범위가 넓습니다. Dev와 Ops는 모두 이미 규모가 크므로 둘을 결합하면 광범위할 것입니다. 이 시험은 DevOps 엔지니어가 DevOps를 통한 디지털 혁신에 대해 유능하게 조언할 수 있을 만큼 충분히 숙련되어 있음을 신뢰하기 위해 주요 고용주가 알아야 하는 DevOps 엔지니어를 평가하기 위해 고안되었습니다.

    공간이 넓기 때문에 시험 자체는 다음과 같은 몇 가지 영역에서만 진행됩니다.

    - Azure DevOps(이전 VSTS 및 TFS)
    - 버전 제어(Git에 초점을 맞추지만 TFVC를 터치)
    - ARM(Azure 자동화를 다룰 때 기본적인 자동화 개념)
    - PowerShell(Unix/Bash 배경에서 온 경우에도 Azure 사람들이 인식하기를 바라는 또 다른 기본 개념)

    결과적으로 객관적인 영역의 많은 영역에 대해 기본 수준의 지식이 필요합니다. 기술과 전체 환경에서 해당 기술이 어디에 속하는지 이해해야 하지만 세부적으로 구체적으로 테스트되지는 않습니다. Bash 스크립트에 대한 전문 지식이나 C#, C++ 또는 Java 등으로 코딩하는 방법은 필요하지 않지만 이러한 스크립트, 코드 또는 지식을 사용하는 데 필요한 조건이 무엇인지 알아야 합니다.

    시험을 검토한 모든 SME(주제 전문가)는 Dev와 Ops 간 균형이 잘 맞았다고 말했습니다. Microsoft 고객이 Azure에서 DevOps에 대해 Microsoft 인증을 받은 사람을 인증할 수 있도록 Microsoft 관련 기술에 대한 충분한 깊이를 다루면서 이기종 환경을 가지고 있다는 사실의 균형을 맞췄습니다.

    **DevOps 엔지니어는 다양한 영역에 대해 알아야 합니다. 우리는 시험의 범위가 객관적인 영역에 정확하게 반영되고 항목이 다른 방식으로 평가할 수 있는 것보다 더 높은 수준에서 이러한 영역을 다루도록 했습니다.**

2. 성공적인 DevOps 엔지니어가 되려면 타사 도구를 사용하는 방법과 시기를 알아야 합니다. 다시 말하지만, SME는 자격을 갖춘 응시자와 궁극적으로 DevOps 전문가가 타사 도구와 이러한 도구의 사용 사례 및 제한 사항에 대해 알고 있지만 타사 도구 및 구현 세부 정보에 대한 깊은 이해가 부족하다고 말했습니다. 즉, 우리가 질문한 모든 내부 및 외부 SME는 타사 기술의 사용이 공정하고 합리적이라고 말했습니다.

    **DevOps 엔지니어는 타사 도구에 대해 어느 정도 알고 있어야 합니다. 이러한 항목이 적절한 수준에 있고 타사 도구에 대한 높은 수준의 이해가 있을 것이라는 기대가 객관적인 영역에 반영되도록 했습니다.**

이제 DevOps에 대한 Microsoft의 접근 방식을 더 잘 이해했습니다. 그렇다면 [Microsoft Certified: DevOps Engineer Expert](https://www.microsoft.com/learning/azure-devops.aspx)가 되는 것은 어떠신가요? 수행할 작업은 다음과 같습니다.

1. [Microsoft Certified: Azure Administrator Associate](https://www.microsoft.com/learning/azure-administrator.aspx) 또는 [Microsoft Certified: Azure Developer Associate](https://www.microsoft.com/learning/azure-developer.aspx) 인증을 취득하세요.

2. [AZ-400: Microsoft Azure DevOps Solutions](https://www.microsoft.com/learning/exam-AZ-400.aspx) 시험을 통과하세요.

이 인증은 취득하기가 어렵지만 취득하고 나면 모든 노력에 그만한 가치가 있을 것입니다. 당신은 최고급 인력이 될 것입니다. 인증 여정에 행운을 빕니다.

[![Azure Devops 학습 경로](images/azuredevops-feb25-2019-375197.jpg)](images/azuredevops-feb25-2019-375197.jpg)

**시험 EZ-400을 위한 강사 진행 교육**

| 과정 제목/교육 제목 | 과정 ID | 과정 시간 |
| --- | --- | --- |
| DevOps 개발 프로세스 구현 |   [AZ-400T01](https://www.microsoft.com/learning/course.aspx?cid=AZ-400T01) | 1일 |
| 지속적 통합 구현 |   [AZ-400T02](https://www.microsoft.com/learning/course.aspx?cid=AZ-400T02) | 1일 |
| 지속적 배포 구현 |   [AZ-400T03](https://www.microsoft.com/learning/course.aspx?cid=AZ-400T03) | 1일 |
| 의존성 관리 구현 |   [AZ-400T04](https://www.microsoft.com/learning/course.aspx?cid=AZ-400T04) | 1일 |
| 애플리케이션 인프라 구현 |   [AZ-400T05](https://www.microsoft.com/learning/course.aspx?cid=AZ-400T05) | 1일 |
| 지속적인 피드백 구현 |   [AZ-400T06](https://www.microsoft.com/learning/course.aspx?cid=AZ-400T06) | 1일 |
| DevOps 전략 설계 |   [AZ-400T07](https://www.microsoft.com/learning/course.aspx?cid=AZ-400T07) | 1일 |

**관련 공지**

[새로운 역할 기반 교육과 인증을 통해 기술을 습득하고 두각을 나타내세요.](https://www.microsoft.com/en-us/learning/community-blog-post.aspx?BlogId=8&Id=375161)

[최신 소식: 새로운 역할 기반 인증 및 교육을 통해 여정 계속하기](https://www.microsoft.com/en-us/learning/community-blog-post.aspx?BlogId=8&Id=375200)

[새로운 역할 기반 인증 및 교육이 출시되었으며 이제 막 시작되었습니다.](https://www.microsoft.com/en-us/learning/community-blog-post.aspx?BlogId=8&Id=375159)

[Azure Solutions Architect인가요? 지금 새 역할 기반 인증 시험에 응시하세요.](https://www.microsoft.com/en-us/learning/community-blog-post.aspx?BlogId=8&Id=375157)

[시험 및 인증 폐지 요약, 2018년 12월](https://www.microsoft.com/en-us/learning/community-blog-post.aspx?BlogId=8&Id=375189)

[Microsoft Azure 및 Microsoft 365를 대상으로 새로운 Fundamentals 인증 프로그램 시작](https://www.microsoft.com/en-us/learning/community-blog-post.aspx?BlogId=8&Id=375158)

[AZ-900: Microsoft Azure Fundamentals 사용 가능 - 지금 등록하세요.](https://www.microsoft.com/en-us/learning/community-blog-post.aspx?BlogId=8&Id=375190)

[Azure 개발자에게 좋은 소식입니다. Microsoft는 인증을 받는 경로를 간소화하고 있습니다.](https://www.microsoft.com/en-us/learning/community-blog-post.aspx?BlogId=8&Id=375185)

[새로운 시험 제안: 자신감을 가지고 인증하세요.](https://www.microsoft.com/en-us/learning/community-blog-post.aspx?BlogId=8&Id=375201)

[2019년 1월에 시작된 모든 시험 및 인증 요약](https://www.microsoft.com/en-us/learning/community-blog-post.aspx?BlogId=8&Id=375204)

[![경력을 발전시키는 기술 습득](images/microsoft-certified-banner.png)](https://www.microsoft.com/learning/azure-training-certification.aspx?WT.icid=mva_bnr_lexawareness_usen_asi_rightrail_oct2017)