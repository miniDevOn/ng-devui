# 如何使用

在 module 中引入：

```ts
import { CardModule } from 'ng-devui/card';
```

在页面中使用：

```xml
<d-card>
  <d-card-header>
    <d-card-title></d-card-title>
    <d-card-subtitle></d-card-subtitle>
  </d-card-header>
  <d-card-content> </d-card-content>
  <d-card-actions></d-card-actions>
</d-card>
```

## d-card

### d-card 区块划分

|      标签      |                                              描述                                              |
| :------------: | :--------------------------------------------------------------------------------------------: |
| d-card-header  | 标题区域，作为概览使用，通常包含标题`d-card-title`,副标题`d-card-subtitle`,头像`dAvatar`等元素 |
|  [dCardMeta]   |                      媒体信息区域，可放置多种媒体，包括图片、图形、视频。                      |
| d-card-content |                     辅助信息区，分析和支撑标题作用，可以包含摘要或者说明。                     |
| d-card-actions |                            决策作用，可以包含操作文本或者操作图标。                            |

### d-card 参数

|    参数     |   类型    | 默认值 |         描述         | 跳转 Demo                                 | 全局配置项 |
| :---------: | :-------: | :----: | :------------------: | :---------------------------------------- | ---------- |
| interactive | `boolean` |   --   | 可选，卡片是否可交互 | [可交互卡片](demo#card-interactive-usage) |            |

### d-card-header 区块划分

|      标签       |                  描述                  |
| :-------------: | :------------------------------------: |
|  d-card-title   | 卡片的主要内容描述，一般定义为卡片名称 |
|  [dCardAvatar]  |      头像区域，用作头像等图片展示      |
| d-card-subtitle |     对标题的补充，可包含标签等信息     |

### d-card-actions 参数

| 参数  |                类型                 | 默认值  |                             描述                             |          跳转 Demo          | 全局配置项 |
| :---: | :---------------------------------: | :-----: | :----------------------------------------------------------: | :-------------------------: | ---------- |
| align | `'start' \| 'end' \|'spaceBetween'` | 'start' | 可选，操作区域对齐方式，分别对应起始对齐，尾部对齐，拉伸对齐 | [基本用法](demo#card-basic) |
