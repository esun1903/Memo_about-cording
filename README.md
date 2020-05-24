# Memo_about-cording

20-05-24

최근 풀어본 문제에서 내가 문제를 이해하고 구현하는 부분에서 자주 막히는 것을 알게됨!

막혔던 문제는 그래프에 관한 문제.

### 그래프
  - 트리보다 더 큰 의미임.
  - 단방향 그래프 , 양방향 그래프 2가지의 종류가 있다 
  - 그래프에는 가중치가 있을 수 있다.
  
### 트리 
   - 그래프보단 작은 범주에 속함 
   - 싸이클이 없어야됨 ex) 8번으로 시작해서 8로 돌아오면 안됨 (트리의 조건)
   
   
   ------------------------------------------------------------------------------
   
   #### 해결방법 ( 총 3가지 ) 
   
    1) Node 클래스 구현 ( 3가지 방법 중 가장 어려운 방법, 그리고 내가 문제에서 이렇게 풀려다가 시간이 다감 ) -> 트리 구현
    
    2) 2차원 배열 [][] , 가장 쉬운 방법 (거의 모든 문제를 풀 수 있는 방법)
   
    3) LinkedList (적은 확률이지만 풀 수 있는 방법이고 내가 푼 그래프에선 LinkedList로 푸는 게 더 효율적인 방법이었다. )  ,BFS and DFS 1260문제가 대표적.
                            
   
