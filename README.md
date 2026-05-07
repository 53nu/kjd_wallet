# Wallet 3D Viewer

GitHub Pages 배포용 파일 구성입니다.

## 파일 구조

```
index.html
models/
  wallet_mint.glb
  wallet_pink.glb
```

## GitHub Pages 업로드 방법

1. 레포지토리에 `index.html`과 `models` 폴더를 그대로 업로드합니다.
2. GitHub 레포지토리에서 `Settings > Pages`로 이동합니다.
3. `Build and deployment`에서 `Deploy from a branch`를 선택합니다.
4. Branch는 `main`, Folder는 `/root`로 설정하고 Save 합니다.
5. 몇 분 뒤 `https://계정명.github.io/레포명/` 주소로 접속합니다.

## 모델 교체 방법

새 GLB 파일을 같은 이름으로 덮어씁니다.

- 민트: `models/wallet_mint.glb`
- 핑크: `models/wallet_pink.glb`

파일명을 바꾸고 싶으면 `index.html` 안의 `MODEL_URLS` 값을 같이 수정하면 됩니다.
