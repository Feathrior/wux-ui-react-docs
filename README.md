<div align="center">

<div>
<img src="https://react.wux-ui.tk/icon.svg" width="150px" height="150px" alt="icon" title="WuX-UI for React.js" />
<h2>WuX-UI-React</h2>
</div>

[![Release Version](https://shields.io/github/v/release/wux-ui/wux-ui-react?color=78aeff)](https://github.com/wux-ui/wux-ui-react/releases/latest)
![GitHub Repo size](https://shields.io/github/repo-size/wux-ui/wux-ui-react?color=78aeff)

</div>

---

# WuX-UI-React - All WuX-UI React components.

Use WuX-UI-React to write WuX-UI components elegantly

# Install

You need to create a react application using [`create-react-app`](https://github.com/facebook/create-react-app) and clone the repo [`WuX-UI-React`](https://github.com/wux-ui/wux-ui-react) in the `src` folder
```sh
create-react-app wux-ui
cd .\wux-ui\src
gh repo clone wux-ui/wux-ui-react
```

# Usage

```jsx
import WuX from './wux-ui-react';
```

# Quick start

Copy this file to index.js in the `src` folder

```jsx
import React from "react";
import { createRoot } from "react-dom/client";
import WuX from "./wux-ui-react";

createRoot(document.getElementById('root')).render(
    <WuX.Header
        title='WuX-UI-React Debug Page'
        small='Menu'
        option={[
            { title: 'Github', link: 'https://github.com/wux-ui/wux-ui-react-docs' },
            { title: 'Offical Page', link: 'https://react.wux-ui.tk/', bold: true },
            <JsxElement />
        ]}
    />
);
```

Then use `npm start` in the `src` folder to start the React project