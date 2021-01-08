# antd-custom-icon
lib to make it possible to create your own lib of icons for antd, without having to import all @ ant-desing


## Install 
`npm i antd-custom-icon -D`

## How to use

```javascript
import React from 'react';
import Icon from 'antd-custom-icon';

export const CustomIcon = ({ component, onClick, fontSize = '20px', fontColor, rest }) => (
    <Icon component={component} onClick={onClick} style={{ fontSize: fontSize, color: fontColor }} {...rest} />
);
```
