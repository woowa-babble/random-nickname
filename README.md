<div align='center'>
<h1>random π² nickname</h1>

A Library that makes fun random nicknames.

  <div display='flex'>
    <img src='https://img.shields.io/badge/license-MIT-green' />
    <img src='https://img.shields.io/badge/version-1.0.0-orange' />
  </div>
</div>

[πΊπΈ Read in English!]('./README.en.md')

- English version in progress
  <br />

## Installation

```
  npm install @babble/random-nickname

  yarn add @babble/random-nickname
```

## Introduction

- λλ¬Ό, νμ΄λ‘, κ²μ μΊλ¦­ν°, λͺ¬μ€ν° μ€ νμμ μ ννμ¬ λλ€ λλ€μμ μμ±ν  μ μμ΅λλ€! π€©
- λλ€μμ `νμ©μ¬` + `λͺμ¬`μ ννλ‘ κ΅¬μ±λ©λλ€.

## Usage

#### `λλ€μ νμ` - μ€λͺ

- `'animals'` - λλ¬Όλ€
- `'heros'` - μνΌ νμ΄λ‘λ€
- `'characters'` - κ²μ μΊλ¦­ν°λ€
- `'monsters'` - μ£Όλ¨Έλ κ΄΄λ¬Όλ€

  <br />

  ```javascript
  import { getRandomNickname } from '@babble/random-nickname';

  const type = 'animals'; // animals, heroes, characters, monsters
  const randomNickname = getRandomNickname(type);

  console.log(randomNickname); // λ°©κ΅¬λλ λ€λμ₯
  ```
