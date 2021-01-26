---
title: Go
nav:
  title: 收藏
  order: 2
---

```jsx
/**
 * inline: true
 */
import React from 'react';
import RepoCardList from '../../components/List/RepoCardList';
import { common } from './Go';

export default () => {
  return <RepoCardList data={common} />;
};
```

## CLI

```jsx
/**
 * inline: true
 */
import React from 'react';
import RepoCardList from '../../components/List/RepoCardList';
import { cli } from './Go';

export default () => {
  return <RepoCardList data={cli} />;
};
```
