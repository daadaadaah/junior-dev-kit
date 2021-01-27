# junior-dev-kit

- 주니어 개발자를 위한 개발 키트로 코딩테스트와 TIL 작성을 손쉽게 도와주는 VSCode Extension

## Features

1. 코딩테스트 연습을 할 수 있습니다.
2. TIL 작성을 편리하게 할 수 있습니다.

### [방법 1] 명령어로 이용하기

- MacOS: `Cmd + shift + p`
- Window: `Ctrl + shift + p`

<img width="500" alt="명령어로 이용하기4" src="https://user-images.githubusercontent.com/60481383/105630887-e547ff80-5e8e-11eb-8ae9-e224b21656f9.png">

### [방법 2] 단축키로 이용하기

#### (1) 코딩테스트 연습하기

- MacOS: `Cmd + Shift + j`
- Window: `Ctrl + Shift + j`

#### (2) TIL 작성하기

- MacOS: `Cmd + Ctrl +l`
- Window: `Ctrl + Window + l`

## Tutorial

> [Junior-dev-kit Tutorial Notion](https://www.notion.so/junior-dev-kit-Tutorial-2903b9d0c767481f8f5920a7e27e196f)

## Extension Settings

- `junior-dev-kit.codingdojoTargetPath`: 코딩테스트 결과 저장하는 폴더 경로
- `junior-dev-kit.tilTargetPath`: TIL 저장하는 폴더 경로

```js
{
  // ...
  "junior-dev-kit.codingdojoTargetPath": "<Your Path>",
  "junior-dev-kit.tilTargetPath": "<Your Path>",
}
```

> 경로 입력하실 때, 반드시 맨 뒤에 '/' 없이 입력해주세요~

```js
- 올바른 예) /User/daadaadaah/daily-coding
- 틀린 예) /User/daadaadaah/daily-coding/
```

## Release Notes

### 0.0.5

- Fix bug([#11](https://github.com/daadaadaah/junior-dev-kit/issues/11))

### 0.0.4

- Fix bug([#6](https://github.com/daadaadaah/junior-dev-kit/issues/6), [#7](https://github.com/daadaadaah/junior-dev-kit/issues/7))

### 0.0.3

- Fix bug([#2](https://github.com/daadaadaah/junior-dev-kit/issues/2))

### 0.0.2

- Open New Window

### 0.0.1

- Initial release of Translator.
