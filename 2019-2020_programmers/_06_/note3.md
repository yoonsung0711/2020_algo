## 조이스틱

https://programmers.co.kr/learn/courses/30/lessons/42860

### 풀이

| 문자 | 아스키코드 | ▲ | ▼ |
| :--- | :--- | ---: | ---: |
| A | 97 | 0 | 0 |
| B | 98 | 1 ||
| C | 99 | 2 ||
| D | 100 | 3 ||
| E | 101 | 4 ||
| F | 102 | 5 ||
| G | 103 | 6 ||
| H | 104 | 7 ||
| U | 105 | 8 ||
| J | 106 | 9 ||
| K | 107 | 10 ||
| L | 108 | 11 ||
| M | 109 | 12 ||
| N | 110 | 13 |13 |
| O | 111 || 12 |
| P | 112 || 11 |
| Q | 113 || 10 |
| R | 114 || 9 |
| S | 115 || 8 |
| T | 116 || 7 |
| U | 117 || 6 |
| V | 118 || 5 |
| W | 119 || 4 |
| X | 120 || 3 |
| Y | 121 || 2 |
| Z | 122 || 1 |


##### 예제 1

```ts
JEROEN: [9,4,9,12,4,13]

mov: *0, val: 9
route: [0]
pos: *5 *1
val: 09 13

mov: *1, val: 13
route: [0,1]
pos: *0 *2
val: -- 09

mov: *2, val: 9
route: [0,1,2]
pos: *1 *3
val: -- 12

mov: *3, val: 9
route: [0,1,2,3]
pos: *2 *4
val: -- 04

mov: *4, val: 4
route: [0,1,2,3,4]
pos: *3 *5
val: -- 13

mov: *5, val: 13
route: [0,1,2,3,4]
pos: *4 *1
val: -- --
```


##### 예제 2
```ts
JAN: [9,0,13]

mov: *0, val: 9
route: [0]
pos: *2 *1
val: 13 00

mov: *2, val: 13
route: [0, 2]
pos: *2 *1
val: 0
```

##### 예제 3

```ts
AACCAAACC: 002200002, 9
002200002

no.1
c_pos: 0, val: 0
intvl: 5678 1234
value: 0002 0220
go_to: 2

no.2
c_pos: 2, val: 0
intvl: 3456 7801 
value: 2000 0200

```