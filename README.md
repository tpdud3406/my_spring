# 나의봄 공연 사진 갤러리

QR코드로 접속하는 사진 전시 페이지입니다.

## 사진 추가하는 방법

1. `images` 폴더에 사진 파일을 넣습니다. (파일명은 영문/숫자 권장, 예: `photo1.jpg`)
2. `index.html` 파일을 열어 `const photos = [...]` 부분에 파일명을 추가합니다.
   ```js
   const photos = [
     "photo1.jpg",
     "photo2.jpg",
   ];
   ```
3. 변경사항을 GitHub에 올립니다 (커밋 & 푸시). 몇 초~1분 안에 실제 사이트에 반영됩니다.

## 배포 주소

https://tpdud3406.github.io/my_spring/

이 주소는 고정되어 있어서, QR코드는 한 번만 만들면 되고 사진/내용은 언제든 위 방법으로 업데이트하면 됩니다.

## GitHub Pages 설정 (최초 1회)

1. GitHub 저장소(tpdud3406/my_spring) 페이지에서 **Settings → Pages**로 이동
2. **Source**를 `Deploy from a branch`로, **Branch**를 `main` / `(root)`로 설정 후 저장
3. 몇 분 후 https://tpdud3406.github.io/my_spring/ 에서 확인 가능
