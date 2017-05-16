---
order: 4
title:
  zh-CN: 竖直方向的步骤条
  en-US: Vertical
---

## zh-CN

简单的竖直方向的步骤条。

## en-US

A simple step bar in the vertical direction.

````jsx
import { Steps } from 'antd';
const Step = Steps.Step;

ReactDOM.render(
  <Steps direction="vertical" current={1}>
    <Step title="立项" description="This is a description." />
    <Step title="专家会" description="This is a description." />
    <Step title="监理招标" description="This is a description." />
    <Step title="招标" description="This is a description." />
    <Step title="建设" description="This is a description." />
    <Step title="初验" description="This is a description." />
    <Step title="终验" description="This is a description." />
  </Steps>
, mountNode);
````
