> 在现有项目根目录中执行

```base
npx sb@next init //预发布版本

npx sb init //稳定版本 推荐
```

> 启动

```base
yarn storybook
```

### Storybook 涉及到的非常规的Javascript

1. [Template.bind({}) 是一个可以用于复制函数的技术](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Global_Objects/Function/bind)

2. [decorators 装饰器](https://storybook.js.org/docs/react/writing-stories/decorators)
