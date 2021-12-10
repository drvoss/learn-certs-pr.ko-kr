---
title: 'Microsoft Exams에 수행 테스트 도입 예정: 알아야 할 사항 | Microsoft Docs'
description: 'Microsoft Exams에 수행 테스트 도입 예정: 알아야 할 사항'
documentationcenter: NA
author: micsullivan
ms.topic: article
ms.tgt_pltfrm: NA
ms.workload: NA
ms.date: 07/30/2019
ms.author: msulliv
ms.prod: non-product-specific
ms.openlocfilehash: 3e2248e8ba5508c80c3def38c4743f86807562f1
ms.sourcegitcommit: 9732383406c868d1279ca5ca79d423c5b99be073
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/14/2021
ms.locfileid: "132111948"
---
# <a name="performance-testing-is-coming-to-microsoft-exams-here-is-what-you-should-know"></a>Microsoft Exams에 수행 테스트 도입 예정: 알아야 할 사항

게시: 2019년 4월 15일 **Liberty Munson(Microsoft)**

___

많은 분들이 아시겠지만, Microsoft에서는 시험에 수행 작업을 추가하기 시작했습니다(이러한 작업을 “랩”이라고 합니다). 이제 시험 도중 클라우드나 온-프레미스에서 실시간 환경이 제시되고, 이 환경에서 작업을 수행해야 합니다. 지금은 아주 흥미로운 시기인데, 얼마 지나지 않아 새 역할 기반 인증을 얻으려면 하나 이상의 시험에서 수행 작업을 완수해야 하기 때문입니다. 많은 분들이 작업을 수행하는 능력을 평가해야 한다고 말했고, 실제로 그렇게 하기로 했습니다. 그러나 Microsoft에서는 랩 전달 방법의 한계를 확장하고 있습니다. 이 정도로 복잡하거나 대규모인 랩 환경을 보유한 인증 프로그램은 없습니다. 랩은 응시자의 기술과 능력을 제대로 시험할 실제 시나리오를 제공할 수 있을 정도로 복잡하며, Microsoft에서는 이러한 시험은 전 세계 거의 모든 국가에 전달하고 있습니다.

2018년 9월 Microsoft에서는 Azure Administrator 시험(AZ100 & AZ101--곧 AZ-103으로 변경됨)에 랩을 도입했습니다. 이후 이 환경에 관한 정보와 응시자들이 잘하는 점(과 못하는 점), 그리고 전반적인 랩 환경 개선 방안을 알게 되었습니다. Microsoft에서는 시험 응시자가 가장 자주 직면하는 문제(대기 시간, 다시 시작 등)를 계속 처리하고 있으며, 다음은 랩 환경에 대한 기대와 환경을 탐색하는 방법을 이해하는 데 도움이 되는 정보입니다.

1. 클라우드에서 시험 환경을 준비하는 데는 다소의 시간이 소요되며, 응시자가 과제 완료를 위해 접속하는 환경은 모든 리소스가 전부 준비되는 경우에만 로딩 가능합니다. 그 결과, 시험은 일련의 기존 항목(선택형, 드래그 앤 드롭, 빌드 목록 등) 풀이로 시작되며, 문제를 푸는 시간에 시험 환경에 랩을 준비하고 로딩합니다. 만약 문제 세트를 너무 빨리 완료하는 경우에는, 랩이 로딩되는 동안 기다려야 할 수 있습니다.
2. 완료한 시험 섹션을 떠나고 나면, 다시 돌아갈 수 없습니다. 그러나, 각 섹션의 마지막에는 답변을 검토할 기회가 주어집니다. **답변을 검토하는 동안에도 시험 시간은 중단되지 않습니다. 시간 관리를 하세요.** 시간과 남은 문제 수에 유의해야 합니다. 
3. 각 시험에는 필수로 완료해야 하는 한 두개의 수행 섹션/다수 과제 랩이 있습니다. 해당 섹션 또는 랩이 끝나면 랩을 채점하는 동안 기존 방식의 문항 풀이를 계속하게 되며, 시험이 끝나는 즉시 합격/불합격 결과를 알 수 있습니다. 다시 강조하지만, 시간 관리에 유념하십시오. 랩이 끝나면 몇 가지 문제를 풀어야 합니다.

    *  시험에 포함된 랩의 수는 첫 번째 랩이 시작되기 전에 개요 페이지에서 알 수 있습니다. 반드시 정독하시기 바랍니다! 그리고, 그에 따라 시간을 적절히 관리하시기 바랍니다.
    *  이러한 시험은 기존 항목, 랩, 기존 항목이라는 패턴으로 진행된다는 점에 유의하세요. 대부분의 기존 항목은 시험 시작 부분에 배치되지만, 모든 시험은 기존 항목에 응답하는 것으로 종료됩니다.
4. 현재 모든 랩 기반 시험의 시험 시간을 180분으로 늘리고 있어, 작업을 완료할 시간이 늘어날 것입니다. (작업은 기존 항목 대비 완료 시간이 3배 정도 더 걸립니다.) 작업을 완료하는 동안 랩 환경을 다시 시작하느라 “손실된” 시간은 전체 시험 시간에서 차감되지 않습니다.
5. 랩에 빈 화면으로 시작한다면 새로운 탭을 열고 [https://portal.azure.com](https://portal.azure.com)으로 이동하세요. 새 탭을 열면 대부분의 경우 문제가 해결됩니다.  
6. 온라인 감독을 통한 시험 응시를 고려해보세요. 이렇게 하면 대부분의 경우 전반적인 환경이 개선되며, 응시자는 모니터 크기(작은 모니터는 시험 응시자들이 항상 불만을 제기하는 요소였습니다. Microsoft에서는 화면 크기를 극대화하고 환경을 개선할 방법을 찾고 있지만, 직장이나 가정에서 큰 모니터를 사용한다면 이러한 시험에 사용하는 방안을 고려해보세요)를 비롯한 하드웨어를 온전히 제어할 수 있습니다. 시험 센터에서 시험을 친다면 응대 담당자/감독관에게 가장 큰 모니터를 요청하세요. VUE에서는 Microsoft 시험용으로 가장 큰 모니터를 예약하도록 시험 센터에 권유하지만, 요청한다고 해서 손해볼 일은 없습니다. [온라인 감독 요구 사항에 대해 자세히 알아보세요](https://www.microsoft.com/learning/online-proctored-exams.aspx). 
7. 다른 과제로 이동하기 전에 수행할 과제를 기다리지 마십시오. (드물지만) 어떤 경우에는, 다른 과제를 완료하기 전에 다른 할 일이 있을 수도 있지만, 해당 과제를 붙잡고 있기 보다는 수행해야 할 다른 과제가 더 있을 것입니다. **과제 실행을 기다리느라 시간을 낭비하지 마세요.** 시험 시간을 최대한 활용할 수 있도록 해당 과제와 무관한 것으로 옮겨가십시오. 경우에 따라, 과제를 시작하는 것만으로 점수를 얻기에 충분한 경우(예: Azure에서 리소스 생성하기)가 있습니다. 해당 과제는 다른 과제를 수행하는 동안 백그라운드에서 실행되도록 둘 수 있습니다. 과제 목록에는 과제 시작에 필요한 것만을 기재한 메모가 포함되어 있습니다. 불이익 없이 다른 과제로 이동하거나, 섹션을 벗어나는 것(시험의 다음 부분으로 이동)도 가능합니다. **작업을 주의 깊게 읽으세요. 놀랍게도 많은 시험 응시자가 지침을 읽지 않습니다(정말 충격적인 일이죠). 랩을 이용할 때는 모든 내용을 주의 깊게 읽어야 합니다.**
8. 특정한 방법으로 과제를 수행할 것을 요구하지는 않습니다. 응시자가 GUI가 아닌 PowerShell이나 CLI를 사용하는 것이 더 편하다면 사용하여도 좋습니다. 시험은 과제를 수행하는 데 사용한 방법이 아닌 과제 수행의 최종 결과를 테스트하여 올바로 응시자가 올바로 수행했는지를 판단합니다.
9. 랩과 관련한 문제가 발생하는 경우 [시험 문항 이의 제기 절차](https://www.microsoft.com/learning/certification-exam-policies.aspx#policies-5)를 통해 전달해주시기 바랍니다. 해당 경험에 관해 구체적인 설명을 제공해드릴 수는 없지만, 그에 대한 조사를 통해 근본적인 원인을 파악하고 모두의 경험을 개선하는 솔루션을 찾는 데 도움이 될 것입니다.
10. 무엇보다도, 기술 수준 확인 방법을 개선하려는 Microsoft의 여정에 동참해 주셔서 진심으로 감사드립니다. 현재 [AZ-100](https://www.microsoft.com/learning/exam-AZ-100.aspx), [AZ-101](https://www.microsoft.com/learning/exam-AZ-101.aspx)(곧 [AZ-103](https://www.microsoft.com/learning/exam-AZ-103.aspx)으로 변경 예정), [AZ-300](https://www.microsoft.com/learning/exam-AZ-300.aspx), [AZ-302](https://www.microsoft.com/learning/exam-AZ-302.aspx)에서 랩이 실행되며 5월 말/6월 초에 더 많은 랩이 제공될 예정입니다. Microsoft는 인증 업계의 선도 주자이며(과장이 아니며 사실입니다), 현상 유지를 거부하고, 모든 일에 최선을 다하고 있습니다. 우리의 모든 여정에 여러분이 함께하기 때문입니다.

랩 기반 시험을 준비하고 응시할 때 이러한 팁과 요령이 도움이 되기를 바랍니다. 행운을 빕니다!


[![경력 증진을 이끄는 기술 습득](images/microsoft-certified-banner.png)](https://www.microsoft.com/learning/azure-training-certification.aspx?WT.icid=mva_bnr_lexawareness_usen_asi_rightrail_oct2017)