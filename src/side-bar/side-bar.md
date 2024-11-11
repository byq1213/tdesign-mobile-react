:: BASE_DOC ::

## API

### SideBar Props

名称 | 类型 | 默认值 | 描述 | 必传
-- | -- | -- | -- | --
className | String | - | 类名 | N
style | Object | - | 样式，TS 类型：`React.CSSProperties` | N
children | TNode | - | 侧边导航内容。TS 类型：`TNode`。[通用类型定义](https://github.com/Tencent/tdesign-mobile-react/blob/develop/src/common.ts) | N
defaultValue | String / Number | undefined | 选项值。非受控属性 | N
value | String / Number | - | 选项值 | N
onChange | Function |  | TS 类型：`(value: number \| string) => void`<br/>选项值发生变化时触发 | N
onClick | Function |  | TS 类型：`(value: number \| string, label: string) => void`<br/>点击选项时触发 | N


### SideBarItem Props

名称 | 类型 | 默认值 | 描述 | 必传
-- | -- | -- | -- | --
className | String | - | 类名 | N
style | Object | - | 样式，TS 类型：`React.CSSProperties` | N
badgeProps | Object | - | 透传至 Badge 组件。TS 类型：`BadgeProps`，[Badge API Documents](./badge?tab=api)。[详细类型定义](https://github.com/Tencent/tdesign-mobile-react/tree/develop/src/side-bar/type.ts) | N
disabled | Boolean | false | 是否禁用 | N
icon | TElement | - | 图标。TS 类型：`TNode`。[通用类型定义](https://github.com/Tencent/tdesign-mobile-react/blob/develop/src/common.ts) | N
label | String | - | 展示的标签 | N
value | String / Number | - | 当前选项的值 | N

### CSS Variables

组件提供了下列 CSS 变量，可用于自定义样式。
名称 | 默认值 | 描述 
-- | -- | --
--td-side-bar-active-color | @brand-color | - 
--td-side-bar-bg-color | @bg-color-secondarycontainer | - 
--td-side-bar-bg-color | @bg-color-secondarycontainer | - 
--td-side-bar-border-radius | 9px | - 
--td-side-bar-color | @font-gray-1 | - 
--td-side-bar-disabled-color | @font-gray-4 | - 
--td-side-bar-font-size | 16px | - 
--td-side-bar-height | 100% | - 
--td-side-bar-icon-size | 20px | - 
--td-side-bar-item-height | 56px | - 
--td-side-bar-item-line-height | 24px | - 
--td-side-bar-width | 103px | -