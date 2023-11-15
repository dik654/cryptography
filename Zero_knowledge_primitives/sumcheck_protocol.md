## 사용하는 이유
prover가 어떤 다변수 다항식을 제대로 알고 있는지 검사하기 위해<br/> 
다항식에서 나올 수 있는 모든 경우의 수의 합을 prover가 계산하고, 이를 verifier가 검증하는 과정에서<br/>
verifier도 모든 경우의 수를 계산하는 경우 verify에 너무 많은 컴퓨팅 파워를 요하는 것이므로<br/>
prover가 각 변수들에 대해 차례대로 단변수 다항식을 만들어서, 차례대로 검증하여<br/>
적은 컴퓨팅 파워로 전체 다항식의 합을 검증하는 프로토콜이다

## 동작 방식

<img width="1372" alt="image" src="https://github.com/dik654/cryptography/assets/33992354/b0de73ae-7fef-44b3-86aa-136dda4733f9">
