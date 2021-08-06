<div align='center'>
<h1>random 🎲 nickname</h1>

A Library that makes fun random nicknames.

  <div display='flex'>
    <img src='https://img.shields.io/badge/license-MIT-green' />
    <img src='https://img.shields.io/badge/version-1.0.0-orange' />
  </div>
</div>

<br />

## Installation

```
  npm install @babble/random-nickname

  yarn add @babble/random-nickname
```

## Introduction

- You can choose type between animals, heroes, game characters, monsters and generate random nicknames! 🤩
- Generated nicknames are in the form of `adjective` + `noun`.

## Usage

#### `nickname type` - description

- `'animals'` - animal names
- `'heros'` - superheroes
- `'characters'` - game characters
- `'monsters'` - pokemons
  <br />

  ```javascript
  import { getRandomNickname } from '@babble/random-nickname';

  const type = 'animals'; // animals, heroes, characters, monsters
  const randomNickname = getRandomNickname(type);

  console.log(randomNickname); // 방구뀌는 다람쥐
  ```
