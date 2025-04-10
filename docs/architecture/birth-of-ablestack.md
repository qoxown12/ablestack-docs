ABLESTACK은 전통적인 기업 데이터센터가 고질적으로 가지고 있는 문제점과 빅데이터 등의 새로운 IT 환경의 발전으로 인해 발생하는 문제점을 효과적으로 해결하기 위해 고안되었습니다. 전통적인 기업 데이터센터가 가지는 문제점을 다시 한번 간단하게 요약하면 다음과 같습니다. 

* 인프라 구성의 어려움 및 복잡성 증가
* 경직된 인프라
* 고가용성 등의 안정성 제공을 위한 고비용투자
* 벤더별로 상이한 관리체계

이러한 기업 데이터센터의 문제점은 최신의 빅데이터 기반 환경에서 빠르게 변화하는 서비스에 대해 능동적으로 대응하는데 더 많은 어려움을 느끼게 합니다. 

ABLESTACK은 이러한 기업 데이터센터의 문제점에 대한 솔루션을 제공하고, 기업 데이터센터의 운영 형태와 상관 없이 동일한 수준의 IT 자산에 대한 소유, 관리 환경을 제공하는 것을 목표로 만들어진 HCI 소프트웨어 스택입니다.

## ABLESTACK : Virtualization & HCI Software Stack

ABLESTACK은 기업 데이터센터에 혁신적인 솔루션을 제공하면서, 기존의 데이터센터가 안고 있던 문제를 해결하기 위해 개발된 서버가상화 소프트웨어 스택입니다. ABLESTACK을 이용하면 전통적인 서버/스토리지 환경에서 일반적인 서버 가상화 환경을 구성할 수 있을 뿐 아니라, 서버 만을 이용해 고가용성 스토리지를 제공하는 HCI 환경을 구성할 수 있는 혁신적인 인프라 환경을 구성할 수 있습니다. ABLESTACK을 이해하기 위해서는 제품의 특성으로 정의된 가상화, HCI와 소프트웨어스택이라는 용어에 대해 이해해야 합니다. 

### 가상화란 무엇인가?

가상화는 컴퓨터가 만들어진 초창기 1960년대에 처음 등장했습니다. 하나의 집채만한 컴퓨터의 자원을 여러 사람이 나눠서 써야 했으므로, 컴퓨터의 활용도를 높이기 위해서 시작된 것입니다. 하지만 1980년대 이후 컴퓨팅 파워가 급속도로 성장하면서 가상화 기술에 대한 필요성이 줄어들어 정체되다가 1990년대 이후 데이터의 급증으로 인해 컴퓨팅 자원의 효율성을 높일 목적으로 다시 주목받게 되었습니다. 

가상화 기술을 이용하면 서버, 디스크, 메모리, 네트워크 등의 자원을 가상으로 만들 수 있습니다. 서버를 가상화 하여 제공하는 것을 '서버가상화'라고 부르고, 네트워크를 가상화하여 제공하는 것을 '네트워크 가상화', 사용자 PC를 가상화하여 제공하는 것을 '데스크톱 가상화' 라고 부릅니다. 모두 물리적인 자원을 효율적으로 사용하기 위해 적용하는 기술로 클라우드 환경의 핵심 기술이며 데이터센터에서 필수적으로 사용해야 하는 기술입니다. 

가상화 기술은 ‘하이퍼바이저’라는 소프트웨어를 통해 구현됩니다. 이 소프트웨어는 물리 리소스를 필요로 하는 가상 환경으로부터 물리 리소스를 분리합니다. 리소스는 필요에 따라 물리 환경에서 여러 가상 환경으로 파티셔닝됩니다. 사용자가 가상 환경(일반적으로 게스트 머신 또는 가상 머신이라고 함)과 상호 작용하고 가상 환경 내에서 계산을 실행합니다. 가상 머신은 단일 데이터 파일과 같이 기능합니다. 디지털 파일과 같이 한 컴퓨터에서 다른 컴퓨터로 이동(마이그레이션) 할 수 있고 어느 쪽 컴퓨터에서든 열어 동일하게 작동할 수 있습니다.

이 가상화 기술은 ABLESTACK의 기반이 되는 기술이며 핵심적인 기술입니다. 

### HCI란 무엇인가?

HCI는 Hyper Converged Infrastructure의 약자입니다. 여기에서 Hyper는 Hypervisor, 즉 가상화 엔진이라는 용어에서 따온 단어입니다. 따라서 단어의 의미를 해석해 보면 가상화 기술을 이용해 통합된 인프라라는 의미입니다. 즉, 물리적인 서버를 가상화 기술을 이용해 스토리지, 서버, 네트워크 역할을 하는 가상머신을 만들고, 이를 통합하여 데이터센터에서 필요한 인프라를 제공하는 제품을 HCI로 통칭합니다. 

### Software Stack

소프트웨어 스택은 솔루션 스택이라고도 부르는데, 무엇인가를 구현하기 위해 필요한 소프트웨어를 모아서 솔루션을 제공하는 것을 의미합니다. 

HCI의 경우 스토리지를 제공하기 위해서는 스토리지 소프트웨어가 필요하고, 가상머신을 관리하기 위해서는 가상화 엔진과 가상화 관리 소프트웨어가 필요하며, 네트워크 기능을 제공하기 위해서는 네트워크 관련 소프트웨어가 필요합니다. 

이러한 소프트웨어를 각각 설치하여 구성하고 사용하는 일은 사용자에게 있어서 매우 복잡하고 어려운 일입니다. 소프트웨어 스택은 이러한 각각의 소프트웨어를 엔터프라이즈 환경에서 사용할 수 있도록 모아서 체계화하고, 통합하여 자동화하도록 만들어 놓은 집합체로 정의할 수 있습니다. 

## ABLESTACK의 미션

ABLESTACK은 기업이 데이터센터를 운영하는데 필요한 솔루션을 통합하여 제공하기 위한 서버가상화, 클라우드 플랫폼, HCI 소프트웨어 스택을 제공하는 것을 목적으로 개발된 제품입니다. ABLESTACK은 다음의 미션을 달성하기 위해 지속적으로 제품을 통합하고, 개발하며, 확장해 나갑니다. 

### 단순한 고성능 통합 인프라

기업의 데이터센터는 인프라의 복잡성으로 인해 구성, 관리에 어려움을 겪습니다. 이러한 문제를 해결하기 위해서 가장 간단한 방법은 서버와 네트워크, 스토리지를 하나의 장비로 통합하여 물리적인 인프라 구조를 단순화 시키는 것입니다. ABLESTACK은 범용 x86 서버를 이용해서 데이터센터에서 필요로 하는 모든 인프라, 즉 서버, 네트워크 장비, 스토리지를 통합하여 제공하는 것을 목표로 합니다. 

사용자는 물리적으로 단일 형태의 서버만을 바라보고 관리하게 됩니다. 물리적인 인프라에 대한 관리는 제조사에 맡기고, 나머지 인프라는 통합 인프라를 통해 소프트웨어적인 방식으로 제공받게 되며, 직접 통제할 수 있게 됩니다. 

또한 모든 워크로드에 대응할 수 있는 고성능의 범용 아키텍처를 제공함으로써 전통적인 IT 서비스 뿐 아니라, 빅데이터 및 AI 등의 서비스도 빠르게 대응할 수 있게 됩니다. 

### 확장성이 우수한 유연한 인프라

빅데이터, AI 등의 발전으로 인해 이제 기업 데이터센터는 인프라를 지속적으로 확장할 준비가 되어 있어야 합니다. 또한 이러한 확장을 최대한 시스템을 중단 시키지 않고 수행해야 합니다. ABLESTACK은 x86 서버를 기반으로 인프라를 제공하되, 구성되어 있는 서버를 추가하면 무중단으로 더 많은 서버를 만들 수 있고, 더 많은 저장 공간을 확보할 수 있도록 하는 것을 목표로 합니다. 

언제든 확장할 수 있는 인프라를 통해, 기업 데이터센터는 인프라를 효율적으로 도입할 수 있게 됩니다. 작은 단위로 확장할 수 있기 때문에 도입 의사결정도 쉽게 이루어질 수 있고, 그만큼 신속성도 높아집니다. 개발자는 언제든 개발서버를 만들어 응용프로그램 개발을 착수할 수 있으며, 서비스의 운영의 탄력성도 높아지게 됩니다. 

### 저비용의 고가용성 인프라

복잡한 인프라 구조면서 이중화가 되어 있지 않는 인프라에서 장애가 발생하면 서비스가 중지될 수 있으며, 장애를 파악하고 조치하는데 많은 시간을 쓰게 됩니다. 이러한 문제를 해결하기 위해 이중화를 하게 되면 더 많은 비용 투자가 필요합니다. 

ABLESTACK은 범용의 장애조치 클러스터링 기술 및 스토리지 기술을 이용해 물리적인 인프라 중 일부의 장애가 발생해도 서비스가 중단되지 않으며, 일정 시간 경과 후에도 인프라가 복구되지 않으면 자가 복구를 실시하여 서비스가 연속성을 유지할 수 있도록 합니다. 즉, 인프라 전 구성요소에 대한 SPOF(단일실패지점, Single Point of Failure) 방지를 목표로 합니다. 

사용자는 ABLESTACK이 제공하는 기본 기능만으로 인프라가 이중화 되어 있는 환경을 제공받을 수 있을 뿐 아니라 장애를 스스로 복구하여 제품 구성요소 중 일부가 사용불능이 되어도 지속적으로 서비스가 운영되도록 함으로써 장애를 방지하고, 장애 조치를 위한 충분한 시간을 확보할 수 있게 됩니다. 

### 웹기반의 통합 관리 플랫폼

복잡한 인프라 패브릭 환경에서 관리 인터페이스 마저 Serial Console, SSH CLI, 웹 기반 등 다양한 형태의 인터페이스를 통해 인프라를 관리해야 하는 기업 데이터센터의 문제를 해결하기 위해, ABLESTACK은 모든 구성요소에 대해 웹 기반으로 인프라를 관리할 수 있는 통합 인터페이스를 제공하는 것을 목표로 합니다. 

사용자는 이제 복잡한 CLI 명령이나 API Call 등을 통하지 않고, 웹 기반 관리 인터페이스를 통해 서버 및 스토리지, 그리고 네트워크를 관리할 수 있고, 직관적으로 인프라의 상태를 확인할 수 있기 때문에 데이터센터의 인프라를 빠르게 모니터링할 수 있고 통제할 수 있게 됩니다.

## 적용 기술의 이해

ABLESTACK은 위에서 제시한 목표를 달성하기 위해 다양한 기술을 적용하였습니다. 위에서 소개한 핵심기술인 가상화 기술과 함께 ABLESTACK에 적용된 기술에 대한 기본적인 이해를 위해 각각의 기술에 대한 개념을 설명하면 다음과 같습니다. 

### 소프트웨어정의 스토리지

SDS(소프트웨어 정의 스토리지)는 하드웨어에서 스토리지 소프트웨어를 분리하는 스토리지 아키텍처입니다. 전통적인 NAS(네트워크 연결 스토리지) 또는 SAN(스토리지 영역 네트워크) 시스템과 달리 SDS는 일반적으로 스토리지 벤더가 제공하는 독점 하드웨어에 대한 소프트웨어의 종속성을 제거하여, 모든 업계 표준 또는 x86 시스템에서 동작하도록 설계됩니다. 

하드웨어에서 스토리지 소프트웨어가 분리되므로 사용자가 벤더 독점적 하드웨어를 급히 추가하는 것이 아니라 일반적인 x86서버를 이용해 필요할 때 스토리지 용량을 적절히 확장할 수 있으며, 필요에 따라 하드웨어를 업그레이드하거나 다운그레이드할 수도 있습니다. 기본적으로 SDS는 뛰어난 유연성을 제공합니다.

예를 들어 보겠습니다. x86 서버가 여러 대 있다고 가정합시다. 각 서버는 스토리지 용량이 서로 다르며 작동하는 데에도 서로 다른 종류의 스토리지 소프트웨어가 필요합니다. SDS를 사용하면 유연성이 떨어지는 각각의 하드웨어에서 디스크를 따로 떼내어 유연성이 높고 확장 가능한 논리적 장소에 통합하여 배치할 수 있습니다. 이렇게 하면 각각의 하드웨어 있는 디스크 용량이 통합된 스토리지로 제공되고 용량도 모든 디스크의 용량을 합한 값이 됩니다. 또한 필요에 따라 스토리지 용량을 거의 즉각적으로 확장할 수 있기 때문에 유연성과 확장성을 제공함은 물론 비용 효율성도 실현할 수 있습니다. 

### 소프트웨어정의 네트워크

소프트웨어 정의 네트워킹(Software-Defined Networking, SDN)은 네트워킹 리소스를 가상화된 시스템으로 추상화하는 IT 인프라에 대한 하나의 접근 방식입니다. 일반적으로 네트워크 장비는 네트워크 포워딩과 제어가 하나의 장비에 통합되어 있습니다. SDN은 중앙에서 관리하고 프로그래밍할 수 있는 네트워크를 구축하기 위해 네트워크 포워딩 기능을 네트워크 제어 기능에서 분리합니다. SDN은 IT 운영팀이 각 네트워크 기기를 수동으로 처리하는 대신, 중앙화된 패널을 통해 복잡한 네트워킹 토폴로지의 네트워크 트래픽을 제어할 수 있도록 해줍니다.

소프트웨어 정의 네트워크 인프라는 비용이 많이 드는 단일 목적의 어플라이언스가 아닌 일반 오프더쉘프(off-the-shelf) 서버에서 구동되기 때문에 하드웨어 네트워크 인프라에 비해 저렴합니다. 또한, 단일 서버에서 다수의 기능이 구동되므로 차지하는 공간도 작습니다. 이는 물리 하드웨어가 덜 필요함을 의미하므로 리소스를 통합하여 물리적 공간, 전력 및 전체 비용을 절감할 수 있습니다. 

네트워크 인프라를 가상화하면 또 다른 독점 하드웨어를 추가하지 않아도, 원하는 대로 필요한 시기에 네트워크 리소스를 확장하거나 축소할 수 있습니다. 소프트웨어 정의 네트워크는 네트워크 리소스의 셀프 서비스 프로비저닝을 지원하기 때문에 유연성 또한 탁월합니다. 

소프트웨어 정의 네트워크는 매우 숙련된 네트워크 전문가가 아니어도 관리할 수 있기 때문에, 전반적으로 운영하기 쉬운 인프라를 구축할 수 있습니다. 

### 고가용성 클러스터링

고가용성(HA, High Availability)이란 서버와 네트워크, 프로그램 등의 정보 시스템이 상당히 오랜 기간 동안 지속적으로 정상 운영이 가능한 성질을 말합니다. 고가용성은 "가용성이 높다" 라는 뜻으로 "쉽게 고장나지 않음"을 의미합니다. 고가용성을 제공하기 위해서 주로 2개 이상의 서버를 연결하는 방식을 사용하는데 이러한 서버 연결을 ‘고가용성 클러스터링’이라고 합니다. 

클러스터링된 서버 중 1대의 서버에서 장애가 발생하면, 다른 서버가 즉시 그 업무를 대신 수행하도록 설정되며, 이러한 설정을 하게 되면 서버의 시스템 장애를 불과 몇 초만에 복구, 즉 다른 서버로 마이그레이션되도록 하여 고가용성을 제공하게 됩니다. 

### 클라우드 컴퓨팅 기술

클라우드란 물리적인 서버의 위치에 상관 없이 인터넷, 네트워크를 통해 다양한 서버 리소스를 사용할 수 있도록 하는 컴퓨팅 리소스 제공 형태를 말합니다. 클라우드 컴퓨팅이란 이러한 클라우드 환경에서 컴퓨팅 자원을 만들고, 애플리케이션을 구축 운영하는 일련의 행위를 의미합니다. 

물리적인 컴퓨터와 다른 점은 서버를 가상화 하여 기능을 제공하여, 이 기능을 서비스 형태로 만들어 제공한다는 점입니다. 일반적으로 이 서비스는 웹 기반으로 사용자가 직접 사용하고 제어할 수 있도록 제공됩니다. 

사용자가 직접 사용하고 제어하는 것을 Self Service라고 부릅니다. 클라우드 컴퓨팅 환경에서는 서버만 제공하는 것이 아니라, 사용자가 직접 가상머신을 생성하거나 삭제합니다. 뿐만 아니라 가상머신에 디스크를 추가하고, NIC를 추가하며, 가상머신을 백업하고 복제하는 등의 다양한 작업을 직접 할 수 있습니다. 

클라우드는 인프라를 제공하는 IaaS, 소프트웨어를 제공하는 SaaS, 플랫폼을 제공하는 PaaS, 기능을 제공하는 FaaS, 컨테이너를 제공하는 CaaS 등으로 나눌 수 있습니다. 또 서비스 하는 방식에 따라 Public Cloud Service, Private Cloud Service, Hybrid Cloud, Multi Cloud, Community Cloud 등으로 나눌 수 있습니다.  
