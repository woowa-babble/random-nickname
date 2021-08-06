<div align='center'>
<h1>random 🎲 nickname</h1>

A Library that makes fun random nicknames.

  <div display='flex'>
    <img src='https://img.shields.io/badge/license-MIT-green' />
    <img src='https://img.shields.io/badge/version-1.0.0-orange' />
  </div>
</div>

[🇺🇸 Read in English!]('./README.en.md')

- English version in progress
  <br />

## Installation

```
  npm install @babble/random-nickname

  yarn add @babble/random-nickname
```

## Introduction

- 동물, 히어로, 게임 캐릭터, 몬스터 중 타입을 선택하여 랜덤 닉네임을 생성할 수 있습니다! 🤩
- 닉네임은 `형용사` + `명사`의 형태로 구성됩니다.

## Usage

#### `닉네임 타입` - 설명

- `'animals'` - 동물들
- `'heros'` - 슈퍼 히어로들
- `'characters'` - 게임 캐릭터들
- `'monsters'` - 주머니 괴물들

  <br />

  ```javascript
  import { getRandomNickname } from '@babble/random-nickname';

  const type = 'animals'; // animals, heroes, characters, monsters
  const randomNickname = getRandomNickname(type);

  console.log(randomNickname); // 방구뀌는 다람쥐
  ```
