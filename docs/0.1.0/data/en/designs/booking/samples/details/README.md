# Details

## Description
A booking details component

## Screen

![Detail](screenshots/details.png)

## Source Code

```typescript(source/index.tsx)
import {  Module, Container, customModule } from "@ijstech/components";
import DetailsMain from "./details";

@customModule
export default class Details extends Module {

  constructor(parent?: Container, options?: any) {
    super(parent, options);
  }

  init() {
    super.init();
  }

  render() {
    return <i-panel width='100%'>
      <i-details display='block' width='100%' />
    </i-panel>
  }
}
```
