# Continuum Pilot UI

Continuum이 고객 현장을 이해하고 운영 경험을 조직의 Intelligence로 연결하는 과정을 Client와 Hub 두 관점에서 경험할 수 있는 인터랙티브 Pilot입니다.

## 지금 체험하기

별도의 설치나 로그인 없이 브라우저에서 바로 실행됩니다.

| 시작점 | 이런 경우에 추천합니다 | Live Demo |
| --- | --- | --- |
| **Continuum Pilot Home** | Client와 Hub를 비교한 뒤 선택하고 싶을 때 | [Pilot 시작하기 →](https://buildupcommon.github.io/continuum/) |
| **Continuum Client** | 고객 현장 운영 담당자의 경험부터 살펴볼 때 | [Client 바로 열기 →](https://buildupcommon.github.io/continuum/prototypes/client/) |
| **Continuum Hub** | 본사에서 여러 고객과 운영 지식을 관리하는 경험을 살펴볼 때 | [Hub 바로 열기 →](https://buildupcommon.github.io/continuum/prototypes/hub/) |

> **처음 방문했다면 [Continuum Pilot Home](https://buildupcommon.github.io/continuum/)에서 시작하는 것을 권장합니다.**

## Continuum Client

고객 환경 내부에서 현장을 이해하고 운영 업무를 수행하는 화면입니다.

- 환경, Kubernetes와 설치 솔루션 현황 파악
- 로그·메트릭·이벤트를 연결한 운영 상태 확인
- Incident의 맥락과 진단 정보 탐색
- Solution Update와 Rollback을 포함한 Lifecycle 관리
- 고객이 데이터 수집과 실행 범위를 통제하는 정책 확인

**추천 탐색 순서**

`Overview → Environments → Solutions → Events → Incident Center → Lifecycle Center`

[Continuum Client 체험하기 →](https://buildupcommon.github.io/continuum/prototypes/client/)

## Continuum Hub

여러 고객 환경과 솔루션, 현장 경험을 중앙에서 연결하는 화면입니다.

- 고객과 환경별 운영 현황 비교
- SK AX 및 BP Solution Catalog와 버전 정보 탐색
- 여러 현장에서 발생한 Incident 통합 관리
- Customer·Environment·Solution·Incident 관계를 연결한 Ontology 탐색
- Lifecycle과 Operational Knowledge의 전사 활용 흐름 확인

**추천 탐색 순서**

`Overview → Customers → Environments → Solutions → Incidents → Lifecycle Center → Knowledge`

[Continuum Hub 체험하기 →](https://buildupcommon.github.io/continuum/prototypes/hub/)

## Demo 안내

- 화면과 상호작용 및 정보 구조를 검증하기 위한 Pilot입니다.
- 실제 Backend API와 연결되지 않은 정적 HTML입니다.
- 고객명과 운영 데이터는 제품 경험을 설명하기 위한 샘플입니다.
- HTML 안에 CSS, JavaScript와 이미지가 포함되어 있어 독립적으로 실행할 수 있습니다.

<details>
<summary><strong>로컬에서 실행하기</strong></summary>

저장소를 내려받은 뒤 각 HTML 파일을 브라우저에서 직접 열 수 있습니다.

```bash
open prototypes/client/index.html
open prototypes/hub/index.html
```

또는 저장소 루트에서 간단한 웹 서버를 실행합니다.

```bash
python3 -m http.server 8000
```

- Client: <http://localhost:8000/prototypes/client/>
- Hub: <http://localhost:8000/prototypes/hub/>

</details>
