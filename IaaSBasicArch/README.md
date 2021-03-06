# Azure IaaS 기본 권장 아키텍처 실습

이 문서는 2016년과 2017년에 걸쳐 고객사들의 개발자 및 엔지니어들을 대상으로 Azure 기술에 대한 이해도와 운영 수준을 높이기 위해서
성지용군과 함께 작성하고, 실제로 실습교재로 사용했던 "Azure IaaS 기본 아키텍처 실습" HOL(Hands on Lab) 문서입니다.
Azure의 신뢰높은 안정성과 확장성을 다양한 ISV 고객들에게 널리 이해시키기 위해서, 최소 99.95%의 가용성을 보장할 수 있는 기본적인 아키텍처를 제시하고 개발자들이 직접 실습할 수 있게끔 작성되었습니다.

이러한 문서를 작성하고, 실습을 진행했던 이유는 

1. Cloud 환경에 대한 이해도 부족으로 인해서 다양한 사건, 사고를 맞이하게 되는 것을 최소화 하기 위함이며
2. 안정적으로 IaaS를 운영하기 위한 Basic Architecture를 제시하여 기본 가용성 환경을 갖추도록 가이드하기 위함이고,
3. Azure Portal 만으로도 모든 구성이 가능하다는 것을 알려주어 Azure가 어렵다는 편견을 없애기 위함

이었습니다.

이 HOL에서 제시하는 기본 아키텍처는 99.95%의 가용성을 보장할 수 있는 최소한의 구성을 가지고 설계되었습니다. 

그리고, HOL의 Objective는 다음과 같습니다.

1. Azure IaaS 를 기반으로 하는 기본적인 실무 아키텍처를 제시한다
2. 모든 작업은 신규 Azure Portal만을 사용하여 구성한다
3. 각각의 필수 Azure 리소스의 역할을 자연스레 이해하고, 생성 순서를 이해시킨다.
4. 최종 산출물을 기반으로 고객의 업무를 확장하게끔 유도하여, 모든 고객이 공통적인 아키텍처 기반 하에서 운영을 시작하게 한다.
5. 기본 아키텍처의 비용을 근거로, 이를 확장한 고객들이 그들의 예상 사용금액을 유추해 볼 수 있게 한다.

전체 문서는 PDF로도 공개되어 있기에 https://docs.com/taeyokim/1345/azure-iaas-hol 에서 별도로 다운로드도 가능합니다만, 이 곳을 통해서도 쉽게 살펴볼 수 있도록 추가적으로 정리하여 공유하고자 합니다.
문서의 순서는 다음과 같습니다.

0.  [Azure IaaS 기본 권장 아키텍처 실습 개요 및 준비](https://github.com/taeyo/AzureIaaS/blob/master/IaaSBasicArch/0.md)
1.	[리소스 그룹 생성](https://github.com/taeyo/AzureIaaS/blob/master/IaaSBasicArch/1.md)
2.	[가상 네트워크와 서브넷](https://github.com/taeyo/AzureIaaS/blob/master/IaaSBasicArch/2.md)
3.	가용성 집합(Availability Set)
4.	저장소 계정(Storage Account) 
5.	가상 컴퓨터(VM)
6.	외부 부하분산 집합
7.	내부 부하분산 집합 
8.	네트워크 보안 그룹(NSG, Network Security Group)
9.	공용 IP 주소 (및 고정 IP)
10. 부록(IIS 웹 서버 설치 및 기본 홈페이지 구성)
