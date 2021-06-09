# hexo-themes

[GIT-STORY](https://github.com/git-story/git-story) 에서 참조하는 테마 정보를 모아둔 레포지토리입니다.


## Index.yml

`index.yml`에 모든 테마의 정보가 들어있습니다.

```yml
- name: 테마 이름
  description: 테마 설명
  link: 테마 github 주소
  preview: 테마 미리보기 주소
  thumbnail: 테마 미리보기 이미지 주소
```

## 테마 설정 파일

`테마 이름.yml` 파일을 생성합니다. 파일이 없으면 별도의 설정을 하지 않습니다.

파일 이름은 무조건 소문자로 이루어져 있어야 합니다.

```yml
config:
  _config.yml 에 추가 및 수정될 설정
plugins:
  package.json dependency에 추가될 npm 플러그인
```
