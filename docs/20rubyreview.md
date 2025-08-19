---
title: 지금까지 푼 루비 문제 리뷰
nav_order: 1
layout: default
---

마지막 업데이트: 2025년 8월 20일

# 지금까지 푼 루비 문제 리뷰

[solved.ac](https://solved.ac)은 [백준](https://www.acmicpc.net/) 문제들의 난이도를 매겨 주는 프로젝트이다. 난이도는 <span class="text-bronze">**Bronze**</span>, <span class="text-silver">**Silver**</span>, <span class="text-gold">**Gold**</span>, <span class="text-platinum">**Platinum**</span>, <span class="text-diamond">**Diamond**</span>, <span class="text-ruby">**Ruby**</span>의 여섯 개로 크게 나누어져 있고(뒤로 갈수록 어렵다) 이들 각각이 **V**, **IV**, **III**, **II**, **I**로 세분화된다(작은 숫자가 더 어렵다).

당연히 최상위 난이도에 해당하는 <span class="text-ruby">**Ruby**</span> 난이도의 문제들은 그에 걸맞는 엄청난 난이도를 자랑한다. 한 문제 푸는 데 일 단위가 걸리는 것은 기본, 애초에 풀 수 있긴 할지를 걱정해야 하는 수준이다. 특히 <span class="text-ruby">**Ruby II**</span> 이상 문제는 아직 한 개도 풀어본 적 없다.

하지만 루비에도 하위권은 존재하고, 그리고 생각보다 많아서 어느덧 20문제나 풀게 되었다! ~~PS를 얼마나 한 거냐~~ 그래서 이들에 대한 리뷰를 작성해 보려고 한다. 스포일러는 최대한 없앴으니 안심하고 읽어도 된다.

태그는 문제를 읽기만 해도 알 수 있는 것을 제외하면 모두 `#???`로 가렸다.

체감 난이도에서 + 부호는 해당 티어 평균 이상, − 부호는 평균 이하를 나타내며 1.0은 한 티어 간격을 의미한다. 따라서 +0.0은 해당 티어 평균, +0.5는 해당 티어와 다음 티어 사이의 경계에 해당한다.

만족도는, 내가 이 문제를 푸는 과정을 얼마나 즐겼는지를 평가한 것으로 낮은 것부터 높은 것 순으로 F, D, C, B, A, S, V이다.

## Sightseeing in Kyoto

| 번호/링크 | [BOJ 24943](https://www.acmicpc.net/problem/24943) |
| 태그 | `#???` `#???` `#???` |
| 현재 난이도 | <span class="text-ruby">**Ruby V**</span> |
| 체감 난이도 | <span class="text-ruby">**Ruby V**</span> −0.2  |
| 맞힌 날짜 | 2024년 11월 12일 |
| 만족도 | A |

내 첫 루비 문제이다. solved.ac 디스코드를 살펴보다가 어쩌다 발견한 문제인데 문제가 매우 쉽게 이해됐기도 하고 무엇보다 태그에 이상한(?) 게 별로 없길래 도전해 봤다. 자체 난이도는 루비 값을 충분히 하는 문제긴 하지만, 태그가 풀이의 방향성을 잘 잡아주어서 루비 치고는 쉽게 풀지 않았나 싶다. 아이디어가 굉장히 참신하기 때문에 꽤나 추천한다.

## 이동하기 4

| 번호/링크 | [BOJ 18796](https://www.acmicpc.net/problem/18796) |
| 태그 | `#???` `#???` `#???` |
| 현재 난이도 | <span class="text-ruby">**Ruby V**</span> |
| 체감 난이도 | <span class="text-ruby">**Ruby V**</span> −0.2  |
| 맞힌 날짜 | 2024년 11월 12일 |
| 만족도 | — |

Sightseeing in Kyoto를 풀고 기여창에 들어갔더니 똑같은 문제가 있다길래 가봤는데 진짜 거의 똑같은 문제다. 써 둔 코드를 그냥 복붙 후 약간만 수정했기 때문에 만족도는 쓰지 않았다. 문제가 서술된 방식에 은근 차이가 있긴 해서 둘 다 레이팅을 주는 것 같다.

## Banks

| 번호/링크 | [BOJ 10350](https://www.acmicpc.net/problem/10350) |
| 태그 | `#math` `#ad_hoc` `#???` `#???` |
| 현재 난이도 | <span class="text-ruby">**Ruby V**</span> |
| 체감 난이도 | <span class="text-diamond">**Diamond I**</span> +0.4  |
| 맞힌 날짜 | 2024년 11월 14일 |
| 만족도 | C |

첫 루비로 정말 많이도 공략당하는 동네북 루비. 가려놓은 태그 둘 중 하나가 **너무 큰 힌트가 되므로** 완전한 자력솔을 원한다면 까지 말아야 한다. 나는 태그를 까고 풀었는데 정말이지 태그 하나 까면 난이도가 <span class="text-diamond">**Diamond II**</span> 상위권 수준으로 떡락한다. 그러니 첫 루비로 강추. 그거와는 별개로 풀이 자체가 매우 신박하고 아름답긴 하다. 만족도가 C인 이유는 그저 내가 태그를 까버렸기 때문이다. 그때는 내가 태그 까는 거를 막아줄 사람이 없었다.

## Min-Max Distance Game

| 번호/링크 | [BOJ 11757](https://www.acmicpc.net/problem/11757) |
| 태그 | `#game_theory` `#???` `#???` `#???` `#???` |
| 현재 난이도 | <span class="text-ruby">**Ruby V**</span> |
| 체감 난이도 | <span class="text-ruby">**Ruby V**</span> +0.3  |
| 맞힌 날짜 | 2024년 11월 25일 |
| 만족도 | D |

한 친구가 알려줘서 푼 문제다. 사실상 논문을 읽고 해석한 뒤 코드를 짜서 푼 문제라 내가 풀었다고 하기 좀 뭐하긴 하지만 어쨌든 해결은 해결이다. 역시나 태그가 꽤 큰 힌트를 주는 문제이며, 나는 친구로부터 풀이법의 요약을 듣고 직접 증명해 보기 위해 시간을 좀 썼다. 결국 증명 정도는 자력으로 했으니 나름 만족한다. 문제가 엄청 재밌진 않다.

## 제곱수의 합 2 (More Huge)

| 번호/링크 | [BOJ 17646](https://www.acmicpc.net/problem/17646) |
| 태그 | `#math` `#number_theory` `#primality_test` `#prime_factorization` `#pollard_rho` `#miller_rabin` |
| 현재 난이도 | <span class="text-ruby">**Ruby IV**</span> |
| 체감 난이도 | <span class="text-ruby">**Ruby IV**</span> −0.4  |
| 맞힌 날짜 | 2024년 11월 26일 |
| 만족도 | D |

태그를 다 보여드렸지만 이것만으로는 별 도움이 안 될 거다. 문제 자체는 [제곱수의 합 (More Huge)](https://www.acmicpc.net/problem/17633)의 상위호환인데, 개수만 구하는 게 아니라 어떤 제곱수의 합인지까지 구해야 해서 훨씬 어렵다. 자력솔은 사실상 불가능하고 구글링을 통해 해결했다. 때문에 만족도도 D.

## Magic Cards (Hard)

| 번호/링크 | [BOJ 25460](https://www.acmicpc.net/problem/25460) |
| 태그 | `#ad_hoc` |
| 현재 난이도 | <span class="text-ruby">**Ruby V**</span> |
| 체감 난이도 | <span class="text-ruby">**Ruby V**</span> −0.4  |
| 맞힌 날짜 | 2024년 11월 29일 |
| 만족도 | S |

한 후배의 추천으로 풀게 되었다. '미리 전략 짜서 항상 성공할 수 있게 하기' 류의 문제를 좋아한다면 한 번 보면 좋을 것 같다. 힌트 아예 없이 풀려고 해 봤는데 그건 너무 힘들어서 그 후배에게 약한 힌트를 요청했고 매우 약한 힌트를 받을 수 있었다(힌트 잘 주더라!). 아이디어가 굉장히 아름답고 찾아냈을 때 성취감이 대단했다. 이런 종류의 문제에 관심이 있다면 적극 추천. 여담으로 원래 <span class="text-diamond">**Diamond I**</span>였는데 나와 그 후배의 기여로 난이도가 올랐다.

## Black and White Boxes

| 번호/링크 | [BOJ 13409](https://www.acmicpc.net/problem/13409) |
| 태그 | `#game_theory` `#???` `#???` |
| 현재 난이도 | <span class="text-ruby">**Ruby V**</span> |
| 체감 난이도 | <span class="text-diamond">**Diamond I**</span> +0.2  |
| 맞힌 날짜 | 2024년 12월 23일 |
| 만족도 | A |

위의 문제를 풀고 나서 시험기간이라 루비는 한 달 정도 풀지 않았고, 방학 후 푼 첫 루비 문제다. 한 선배의 프로필에서 발견했고 재미있어 보이길래 태그를 까고 조사를 좀 했다. 그렇게 처음 보는 종류의 게임 하나를 알게 되었는데 꽤 재밌다! 이런 이론을 어떻게 처음 발견해낸 거지? 궁금하신 분은 저 문제의 태그를 까고 나오는 게임에 대해 구글링해 보도록 하자. 지금까지 게임 이론은 스프라그 그런디 비슷한 것만 계속 풀었는데 새로운 걸 배워서 기분이 좋았다. 그리고 숨겨진 태그가 하나 더 있는데 그 태그 관련 아이디어도 꽤 재밌다. 원래 난이도는 <span class="text-ruby">**Ruby IV**</span>였으나 시간이 흘러 해당 태그가 더 잘 알려지며 난이도가 내려가게 되었다. 아직도 좀 고평가라고 생각하긴 한다.

## 조작된 ㄱ 폭탄 게임

| 번호/링크 | [BOJ 18945](https://www.acmicpc.net/problem/18945) |
| 태그 | `#game_theory` `#???` `#???` `#???` |
| 현재 난이도 | <span class="text-ruby">**Ruby IV**</span> |
| 체감 난이도 | <span class="text-ruby">**Ruby V**</span> −0.4  |
| 맞힌 날짜 | 2024년 12월 24일 |
| 만족도 | S |

위의 문제를 풀면서 배운 바로 그 게임에 대한 응용 문제이다. 확실히 그 게임에 대한 제대로 된 이해를 요구하므로 비교적 어렵다. 원래 <span class="text-ruby">**Ruby III**</span> 였기 때문에, 이 문제를 풀면서 내가 백준에서 푼 최고난도 문제와 동시에 최고난도 자력솔이었지만 이후 난이도가 내려가며 타이틀을 뺏겼다. 다행히 이제는 해당 난이도의 다른 문제를 두 개 더 풀었다.

## Hey, Better Bettor

| 번호/링크 | [BOJ 8878](https://www.acmicpc.net/problem/8878) |
| 태그 | `#math` `#combinatorics` `#probability` `#calculus` |
| 현재 난이도 | <span class="text-ruby">**Ruby V**</span> |
| 체감 난이도 | <span class="text-diamond">**Diamond II**</span> +0.3  |
| 맞힌 날짜 | 2024년 12월 25일 |
| 만족도 | B |

루비치고 너무 쉬웠던 문제다. 풀고 나서 기여창과 구글링 결과를 보았더니 다들 어렵게 푼 것 같고 그래서 루비로 기여하지 않았다 싶다. 아무튼 식을 찾고 이름을 밝히지 않을 특정 테크닉만 쓰면 루비라기엔 지나치게 쉽게 풀린다. 첫 루비로 추천할 만한 것 같다.

## Radioactive Islands (Small)

| 번호/링크 | [BOJ 14346](https://www.acmicpc.net/problem/14346) |
| 태그 | `#math` `#calculus` `#numerical_analysis` `#???` |
| 현재 난이도 | <span class="text-ruby">**Ruby IV**</span> |
| 체감 난이도 | <span class="text-ruby">**Ruby V**</span> −0.5  |
| 맞힌 날짜 | 2025년 1월 23일 |
| 만족도 | C |

역시 유명한 동네북 루비다. 변분법 문제라, 그냥 식 세우고 정리한 다음 코드에 넣기. 사실상 변분법을 안다는 것 자체의 난이도 때문에 난이도가 올라간 케이스다. 이미 공부했다면 날먹하러 가보자. 그런 면에서, 루비 최하위라 생각한다.

## Radioactive Islands (Large)

| 번호/링크 | [BOJ 14347](https://www.acmicpc.net/problem/14347) |
| 태그 | `#math` `#calculus` `#numerical_analysis` `#???` |
| 현재 난이도 | <span class="text-ruby">**Ruby IV**</span> |
| 체감 난이도 | <span class="text-ruby">**Ruby V**</span> −0.4  |
| 맞힌 날짜 | 2025년 1월 24일 |
| 만족도 | F |

사실상 위 Small과 똑같지만 계산이 살짝 더 귀찮은 문제이다. 난이도 차이는 매우 작기 때문에 Small을 풀었다면 안 풀 이유가 없는 문제지만, 주의할 점이라면 계산 과정이 꽤 복잡한지라 실수하기 쉽다는 점. 맞힌 날짜가 Small과 하루 차이가 나는데 그건 자고 일어나서 풀었기 때문이 아니라 실수를 고치고 나니까 자정이 넘어 버렸기 때문이다(시간 단위로 걸렸다). 만족도가 F인 이유는 순수하게 내 실수를 발견하는 과정이 너무 고통스러웠기 때문. 절대 안 좋은 문제라서가 아니다.

## Xormites

| 번호/링크 | [BOJ 19054](https://www.acmicpc.net/problem/19054) |
| 태그 | `#game_theory` |
| 현재 난이도 | <span class="text-ruby">**Ruby IV**</span> |
| 체감 난이도 | <span class="text-ruby">**Ruby V**</span> +0.1  |
| 맞힌 날짜 | 2025년 1월 25일 |
| 만족도 | C |

이 문제는 솔직히 내가 어떻게 푼건지도 모르겠고 다시 풀라 하면 풀 수 있을지도 모르겠다. 그만큼 어거지로 비벼서 푼 문제로, 증명은 전혀 하지 않았으며 정말 규칙찾기와 직관만으로 때려맞혔다. 그래서 이 문제는 딱히 내 기억에 잘 남아있지 않다.

## N의 배수 (3)

| 번호/링크 | [BOJ 18792](https://www.acmicpc.net/problem/18792) |
| 태그 | `#math` `#number_theory` `#???` `#???` `#???` |
| 현재 난이도 | <span class="text-ruby">**Ruby V**</span> |
| 체감 난이도 | — |
| 맞힌 날짜 | 2025년 1월 27일 |
| 만족도 | — |

티어 날먹을 원하던 나는 N의 배수 시리즈를 공략하기로 결정한다. 4만 풀면 2, 3이 따라오기 때문에 꽤 많은 점수를 날먹할 수 있기 때문. 당연히 자력솔할 생각은 하지 않았고 풀이가 적힌 논문을 읽었다. 논문을 완벽히(아님) 이해한 다음 코딩을 했는데 최적화를 잘못했는지 4가 시간초과가 나서 풀지 못했고, 제한이 작은 3이나 풀었다. 그래서 나는 이 문제의 정해를 모른다. 따라서 난이도도 당연히 모른다.

## N의 배수 (4)

| 번호/링크 | [BOJ 25448](https://www.acmicpc.net/problem/19054) |
| 태그 | `#math` `#ad_hoc` `#number_theory` `#???` |
| 현재 난이도 | <span class="text-ruby">**Ruby III**</span> |
| 체감 난이도 | <span class="text-ruby">**Ruby III**</span> +0.2  |
| 맞힌 날짜 | 2025년 1월 27일 |
| 만족도 | B |

그리고 자고 일어나서 낮에 4를 풀었다. 개인적인 감상으로는 정말 천재적인 아이디어 같다. 보통 풀이를 보고 풀면 만족도를 낮게 주는데, 이 문제만큼은 그 풀이가 정말 인상깊었기 때문에 B를 주었다.

## Harder Satisfiability

| 번호/링크 | [BOJ 16667](https://www.acmicpc.net/problem/16667) |
| 태그 | `#implementation` `#graphs` `#scc` `#2_sat` |
| 현재 난이도 | <span class="text-ruby">**Ruby V**</span> |
| 체감 난이도 | <span class="text-diamond">**Diamond I**</span> −0.1  |
| 맞힌 날짜 | 2025년 3월 4일 |
| 만족도 | S |

이제 개강 후로 점프! 개인적으로 2-SAT과 SCC를 좋아하기 때문에 자연스럽게 꽤 오랫동안 관심을 가졌던 문제이다. 의외로 풀이 자체도 일반 2-SAT에서 아주 크게 벗어나지 않기 때문에, 해당 문제에 관심을 가지고 있다면 추천한다.

## 위수는 쿼리입니까?

| 번호/링크 | [BOJ 30913](https://www.acmicpc.net/problem/30913) |
| 태그 | `#math` `#implementation` `#number_theory` `#primality_test` `#prime_factorization` `#euler_phi` `#pollard_rho` `#miller_rabin` `#???` `#???` `#???` `#???` |
| 현재 난이도 | <span class="text-ruby">**Ruby IV**</span> |
| 체감 난이도 | <span class="text-ruby">**Ruby V**</span> +0.5  |
| 맞힌 날짜 | 2025년 3월 16일 |
| 만족도 | V |

엄청난 문제다. 단연 지금까지 PS하면서 푼 만족도 최상의 문제로, 반 학기 분량의 정수론 지식을 전부 다 쏟아넣어야 하는 문제다! 정수론을 좋아한다면 반드시 시도해 볼 가치가 있을 것이다. 풀이 구상에 1~2주 정도를 썼고, 구현에도 시간 단위로 걸렸다. 그만큼 알아야 하는 것도 많고 구현할 것도 많으며, 아이디어도 적지 않게 사용하는 문제. 실로 물량공세 루비라 할만 하다.

## 보물찾기

| 번호/링크 | [BOJ 1868](https://www.acmicpc.net/problem/1868) |
| 태그 | `#graphs` `#trees` `#graph_traversal` `#???` `#???` `#???` |
| 현재 난이도 | <span class="text-ruby">**Ruby V**</span> |
| 체감 난이도 | <span class="text-diamond">**Diamond II**</span> +0.1  |
| 맞힌 날짜 | 2025년 3월 26일 |
| 만족도 | A |

나름 유명한 문제로, 루비 치고 매우 쉽게 풀 수 있기 때문에 꽤나 추천! 사전 지식도 그다지 많이 필요하지 않다. 문제 붙잡아 두고 시간 단위로 고민하다 보면 언젠가 풀려 있을지도?

## Output Limit Exceeded

| 번호/링크 | [BOJ 21085](https://www.acmicpc.net/problem/21085) |
| 태그 | `#ad_hoc` `#bipartite_matching` `#graphs` `#dfs` `#graph_traversal` `#math` `#number_theory` `#???` `#???` `#???` `#???` |
| 현재 난이도 | <span class="text-ruby">**Ruby V**</span> |
| 체감 난이도 | <span class="text-ruby">**Ruby V**</span> −0.4 |
| 맞힌 날짜 | 2025년 4월 30일 |
| 만족도 | S |

루비 자력솔은 이전에도 꽤 많이 했지만, 태그도 없이 루비를 거의 완전히 자력으로 푼 건 이 문제가 처음이라 꽤나 인상깊게 기억나는 문제. 이 많은 태그를 전부 내가 직접 달았다! 이분 매칭 관련 지식을 배워간 다음 도전해 보면 루비 하위권 수준의 난이도로 풀릴 문제이므로 도전해 보면 좋을 수도 있다.

## 야유회

| 번호/링크 | [BOJ 27511](https://www.acmicpc.net/problem/27511) |
| 태그 | `#math` `#ad_hoc` `#constructive` |
| 현재 난이도 | <span class="text-ruby">**Ruby V**</span> |
| 체감 난이도 | <span class="text-ruby">**Ruby IV**</span> -0.3 |
| 맞힌 날짜 | 2025년 6월 4일 |
| 만족도 | B |

선배가 알려준 문제. 풀이를 사실상 다 들어 버렸지만, 생각할수록 굉장히 참신한 풀이 같다. 태그에서 보이듯 사전지식은 거의 필요 없지만 아이디어 자체의 난이도가 많이 높아서 혼자 풀기는 꽤 어려웠을 것 같다. 이런 종류의 문제가 마음에 든다.

## 공 옮기기

| 번호/링크 | [BOJ 22872](https://www.acmicpc.net/problem/22872) |
| 태그 | `#ad_hoc` `#constructive` `#???` `#???` |
| 현재 난이도 | <span class="text-ruby">**Ruby III**</span> |
| 체감 난이도 | <span class="text-ruby">**Ruby IV**</span> +0.1 |
| 맞힌 날짜 | 2025년 6월 4일 |
| 만족도 | V |

역시 선배가 알려준 문제로, 승급전 문제이기도 했다. 풀이가 아름답진 않지만, 어떻게든 풀이를 완성하는 과정 하나하나가 정말 기억에 잘 남는 문제다. 규칙 자체는 하노이탑에서 살짝 변형한 수준인데 그 하나의 변화로 난이도가 수직상승한 케이스. 현재 내 최고난도 문제이자 최고난도 자력솔이다. 끝내 풀이를 찾아냈을 때의 쾌감은 절대 잊지 못할 것 같다. 역시나 배경지식 요구량은 사실상 0이므로 아주 도전적인 문제를 원한다면 강력 추천한다.