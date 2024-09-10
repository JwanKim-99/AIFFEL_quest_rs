## AIFFEL Campus Online Code Peer Review Templete
- 코더 : 김소희
- 리뷰어 : 이치오

## PRT(Peer Review Template)
- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
    - 아웃포커싱 효과가 적용된 인물모드 사진과 동물 사진, 배경전환 크로마키사진을 각각 1장 이상 성공적으로 제작하였다.
    - ![image](https://github.com/user-attachments/assets/445502ad-9c1e-4951-b4f2-de8f67f2b0cb)
    - ![image](https://github.com/user-attachments/assets/1ef4c09b-bc71-4ea6-bf23-b708c91ac49e)
    - ![image](https://github.com/user-attachments/assets/4aee56c2-b2ab-44ac-83fb-10ffd7c937d3)
    - 인물사진에서 발생한 문제점을 정확히 지적한 사진을 제출하였다.
    - ![image](https://github.com/user-attachments/assets/121ea7f5-2489-496c-85c4-da0a0c60261d)
    - semantic segmentation mask의 오류를 보완할 수 있는 좋은 솔루션을 이유와 함께 제시하였다.
    - ![image](https://github.com/user-attachments/assets/e6cb3e4f-c5f6-4da9-b8dc-c7203ebb401c)
    
- [x]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
    - ![image](https://github.com/user-attachments/assets/81b47893-2829-4b5c-adf2-efeeda86d28f)
        
- [x]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나 새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 실험이 기록되어 있는지 확인
    - ![image](https://github.com/user-attachments/assets/59728cba-949f-4b02-bd85-f0793ea57011)
    - ![image](https://github.com/user-attachments/assets/2638979f-2abb-496d-b63c-1017472ef23d)

- [x]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해 배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
    - ![image](https://github.com/user-attachments/assets/29081aa6-b5c5-400f-b8c3-8638a8cd2556)

- [x]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
    - ![image](https://github.com/user-attachments/assets/eb713e4d-0508-4161-b7d5-dbb023941ced)

## 회고(참고 링크 및 코드 개선)
1. 코드 가독성이 좋고, 한줄 한줄 주석이 달려있어 이해하는데 도움이 되었다.
2. 특정 사진을 넣으면 sementation 결과가 회전해서 나오는 경우가 있었는데 dimension이 틀리면 회전하는 스텝을 구현해 문제를 잘 해결한 것 같다.
