LOG HOME — WEB EDITION
======================



브라우저
- PC 로컬 파일 직접 저장에는 File System Access API가 필요합니다. 최신 Chrome, Edge, Whale 등 Chromium 계열 데스크톱 브라우저를 권장합니다.
- 지원하지 않는 브라우저에서는 몰래 localStorage로 대체 저장하지 않습니다.

주의
- 실제 loghome-data.json을 삭제/손상/덮어쓰거나 저장 드라이브를 초기화하면 데이터가 사라질 수 있습니다.
- 같은 데이터 파일을 여러 탭/창에서 동시에 편집하면 마지막 저장이 앞선 변경을 덮어쓸 수 있으므로 한 번에 한 창에서 사용하는 것을 권장합니다.
- JSX 템플릿은 실제 JavaScript로 실행됩니다. 신뢰할 수 있는 코드만 등록하세요.
