<div align="center">
<h1>React-tooltip</h1>

<a href="https://www.emojione.com/emoji/1f300">
<img height="128" width="128" alt="Portal" src="docs/portal.png" />
</a>

<p>Light-weight tooltip component for react powered by portals</p>
</div>

[![jest](https://jestjs.io/img/jest-badge.svg)](https://github.com/facebook/jest)

## Installation

```bash
npm install
```

## Usage

```js
import Tooltip from 'tooltip';

<Tooltip render="Hi, I'm a tooltip">
    Hover me
</Tooltip>

<Tooltip render={() => <div>Hi I am a tooltip</div>}>
    Hover me
</Tooltip>
```
