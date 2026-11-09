# mystery-game

웹 브라우저에서 플레이하는 조사형 추리 게임입니다.
장소를 조사해 단서를 모으고, 용의자를 심문한 뒤, 증거를 근거로 범인을 지목하세요.

- 설계 문서: [docs/DESIGN.md](docs/DESIGN.md)

## 실행
빌드 과정은 없습니다. ES Modules를 쓰기 때문에 로컬 서버로 열어야 합니다.

```bash
python3 -m http.server 8000
```
브라우저에서 http://localhost:8000 을 엽니다.
