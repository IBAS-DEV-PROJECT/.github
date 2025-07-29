# IBAS GitHub Overview 관리 가이드

이 문서는 `IBAS-DEV-PROJECT` Organization의 **GitHub Overview에 표시되는 README**를  
어떻게 관리하고 작성하는지 설명하기 위한 내부 가이드입니다.

---

## 폴더 구조

```
.github/
├── README.md ← 현재 파일 (내부 가이드 문서)
└── profile/
└── README.md ← GitHub Organization Overview에 표시되는 공개 문서
```

## `profile/README.md` 역할

- Organization의 대표 소개 페이지로, 외부인 또는 신입 팀원을 위한 문서입니다.
- 현재 IBAS 개발팀의 성격, 사이드 프로젝트, 운영진, 기여자 등을 요약해 소개합니다.
- 마크다운 / HTML만으로 작성되며, 이미지/링크/표/배지 등 시각 요소 활용 가능합니다.

## 작성 및 수정 가이드

- **톤앤매너**: 친근하지만 신뢰감 있게 (공식 문서 느낌 + 감성 한 스푼)
- **정기 점검**: 운영진 변경, 프로젝트 추가 시 최신화
- **사진 링크**: GitHub 프로필 이미지 사용 (`https://avatars.githubusercontent.com/깃허브아이디`)
- **기여자**: 사진만, 링크 포함 / 간결한 갤러리 스타일

## 수정 방법

1. `.github/profile/README.md` 파일을 열고 마크다운 / HTML을 활용해 수정합니다.
2. 커밋 후 푸시하면, Organization Overview에 약 30초~1분 내 반영됩니다.
3. **반드시 내용 검토 후 커밋해 주세요.**

## 참고 사항

- `README.md`가 아닌 다른 파일은 Overview에 반영되지 않습니다.
- `profile/` 폴더 구조를 바꾸면 표시되지 않으니 위치 주의해 주세요.
- Organization이 **Public**이어야 외부에서도 표시됩니다.

## 문의

공식 README 수정 또는 신규 프로젝트 반영이 필요한 경우,  
운영진에게 문의하거나 PR을 등록해 주세요.
