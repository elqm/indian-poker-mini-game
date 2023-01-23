# [프로그램 제목]


- 인디언 포커




# [프로그램 요약]


- 유저1과 유저2가 딜러에게 각각 카드 10장(1~10)을 받고 그 중 1개를 랜덤으로 뽑아 숫자가 큰 카드를 뽑은 사람이 이기는 게임이다.




# [요구사항]


- 딜러가 유저1과 유저2에게 각각 1~10까지 숫자 카드 10장을 나눠준다.

- 유저1과 유저2가 각각 10장 중 카드 1장을 랜덤으로 뽑는다.

- 유저1과 유저2가 각각 서로에게 카드를 공개한다.

- 유저2가 유저1의 카드를 확인하고 반응을 보인다.

        예) 입꼬리 살짝 올리기.(상대의 카드 범위 1~2 || 9~10)
            포커페이스 유지.(상대의 카드 범위 3~8)

- 유저1는 유저2의 반응을 확인하고 승부할지, 다이(die/죽을지)할지 결정한다.

- 승부 시, 딜러와 유저가 각각 자신의 카드를 공개하고 이후 게임 결과(승리 or 패배)가 나온다.

- 다이 시, 딜러가 회심의 미소를 날리며 유저를 조롱한다.

- 게임 한 판이 종료되고, 다시 게임을 할지 물어본다.

- 다시 게임을 시작할 경우, 처음으로 되돌아가 다시 카드 10장을 받는다.

- 그렇지 않을 경우, 그대로 카드 게임을 종료한다.




# [커뮤니케이션 다이어그램]



![1  베트](https://user-images.githubusercontent.com/121847260/214047467-b591a513-a2c3-49b7-af97-6c4dd12ef3ee.png)


![2  카드 배분](https://user-images.githubusercontent.com/121847260/214047468-0c16cb9c-c8ce-4ca9-a3a3-83332acd1671.png)


![3  카드 선택](https://user-images.githubusercontent.com/121847260/214047470-d7df5f98-3289-4704-bf04-c1891d9ede7a.png)


![4  카드 공개](https://user-images.githubusercontent.com/121847260/214047480-a5da2639-27c1-459c-add4-ba62c9ca268d.png)


![5  레이즈](https://user-images.githubusercontent.com/121847260/214047486-03165ca4-fe0e-4c4c-b6a9-cdff3dbf59d3.png)


![6  게임 포기](https://user-images.githubusercontent.com/121847260/214047492-84ddd053-65a9-420b-ab01-0576d90381b2.png)


![7  게임 승부](https://user-images.githubusercontent.com/121847260/214047498-67dc09ab-e9de-4489-8d4a-d49e9636f29f.png)


![8  게임 계속 진행](https://user-images.githubusercontent.com/121847260/214047500-63a7c50f-27ed-4eb2-bd73-27eb8b8159f8.png)


![9  게임 초기화](https://user-images.githubusercontent.com/121847260/214047505-8a3c1676-0ab5-4372-87ab-9f50c1a9526d.png)


![10  게임 종료](https://user-images.githubusercontent.com/121847260/214047507-a8c9c767-f304-41fe-8917-d582891f340e.png)





# [클래스 다이어그램]



![인디언 포커 클래스 다이어그램](https://user-images.githubusercontent.com/121847260/214047624-c1553bc0-bb26-460b-b3fd-f9478d51473f.png)


