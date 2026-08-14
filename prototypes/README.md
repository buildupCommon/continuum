# Continuum Pilot UI

Continuum Client와 Hub의 사용자 경험 및 정보 구조를 검증하기 위한 정적 HTML Pilot입니다.

## Live Demo

- [Continuum Pilot Home](https://buildupcommon.github.io/continuum/)
- [Continuum Client](https://buildupcommon.github.io/continuum/prototypes/client/)
- [Continuum Hub](https://buildupcommon.github.io/continuum/prototypes/hub/)

## Pilot 목록

| Pilot | 경로 | 설명 |
| --- | --- | --- |
| Continuum Client | [`client/index.html`](client/index.html) | 고객 환경 안에서 운영 정보, Incident와 Lifecycle을 확인하는 화면 |
| Continuum Hub | [`hub/index.html`](hub/index.html) | 여러 고객, 환경, 솔루션과 운영 지식을 통합 관리하는 화면 |

## 실행 방법

별도의 설치나 빌드 과정은 필요하지 않습니다. 저장소를 내려받은 뒤 원하는 HTML 파일을 브라우저에서 엽니다.

macOS에서는 저장소 루트에서 다음 명령을 사용할 수 있습니다.

```bash
open prototypes/client/index.html
open prototypes/hub/index.html
```

또는 간단한 로컬 웹 서버를 실행할 수 있습니다.

```bash
python3 -m http.server 8000
```

서버를 실행한 뒤 다음 주소로 접속합니다.

- Client: <http://localhost:8000/prototypes/client/>
- Hub: <http://localhost:8000/prototypes/hub/>

## 유의사항

- 화면과 상호작용을 검증하기 위한 Pilot이며 실제 Backend API와 연결되지 않습니다.
- HTML 안에 CSS, JavaScript와 이미지가 포함된 독립 실행형 파일입니다.
- 표시되는 고객명과 운영 데이터는 데모 및 제품 설명을 위한 샘플 데이터입니다.
