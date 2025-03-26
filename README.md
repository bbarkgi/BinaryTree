# 이진트리 순회 (Binary Tree Traversal)

이 저장소는 자바(Java)를 사용하여 이진 트리를 전위(preorder), 중위(inorder), 후위(postorder) 순회하는 프로그램을 구현한 코드입니다.

## 🔍 문제 설명

- 루트 노드로부터 시작하여 이진 트리를 순회합니다.
- 입력 형식: 각 노드와 그 자식 노드 정보 ('.'은 자식 노드가 없음을 의미)
- 출력:  
  - 전위 순회 결과  
  - 중위 순회 결과  
  - 후위 순회 결과  

## 🧠 순회 방식

- **전위 순회 (Preorder)**: 루트 → 왼쪽 → 오른쪽  
- **중위 순회 (Inorder)**: 왼쪽 → 루트 → 오른쪽  
- **후위 순회 (Postorder)**: 왼쪽 → 오른쪽 → 루트

## 💻 실행 예시

입력:7
A B C
B D .
C E F
E . .
F . G
D . .
G . .

출력:
ABDCEFG
DBAECFG
DBEGFCA
