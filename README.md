# jkkim809.github.io

Personal research site — https://jkkim809.github.io

## 내용을 고치는 법

거의 모든 수정은 `_data/` 안의 세 파일에서 끝납니다.

| 하고 싶은 일 | 고칠 파일 |
|---|---|
| 논문 추가 | `_data/publications.yml` 맨 위에 항목 추가 |
| 발표 추가 | `_data/talks.yml` 맨 위에 항목 추가 |
| 경력·학력·수상·기술 | `_data/cv.yml` |
| 이름, 소속, 링크 | `_config.yml` |
| 자기소개 문단 | `index.html` |

수정 후 커밋하고 push 하면 1~2분 뒤 사이트에 반영됩니다.

```
git add .
git commit -m "Add ICIP 2026 paper"
git push
```

## 로컬 미리보기 (선택)

Ruby 가 설치되어 있어야 합니다.

```
bundle install
bundle exec jekyll serve
```

http://localhost:4000 에서 확인할 수 있습니다.
