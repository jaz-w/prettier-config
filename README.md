# prettier-config-jaz

## Usage

### Install

```
pnpm add -D prettier prettier-config-jaz
```

### Edit `package.json`

```json
{
  "prettier": "prettier-config-jaz"
}
```

## Preview

| Name              | Value         | Description                                                                                                                                                                                                                                                                        |
| :---------------- | :------------ | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `printWidth`      | `90`          | 每行最多 多少个字符换行                                                                                                                                                                                                                                                            |
| `tabWidth`        | `2`           | **tab** 缩进大小                                                                                                                                                                                                                                                                   |
| `useTabs`         | `false`       | 使用 **tab** 缩进                                                                                                                                                                                                                                                                  |
| `semi`            | `false`       | 使用分号                                                                                                                                                                                                                                                                           |
| `singleQuote`     | `true`        | 使用单引号                                                                                                                                                                                                                                                                         |
| `jsxSingleQuote`  | `true`        | 在 **JSX** 使用单引号                                                                                                                                                                                                                                                              |
| `quoteProps`      | `"as-needed"` | 更改对象中的属性被引号包含的时机 <br> `as-needed`:仅在需要时在对象属性周围添加引号 <br> `consistent`:如果对象中至少有一个属性需要引号，则引用所有属性 <br>...                                                                                                                      |
| `trailingComma`   | `"all"`       | 尾随逗号                                                                                                                                                                                                                                                                           |
| `bracketSpacing`  | `true`        | 对象的间距 <br> `true` - Example: `{ foo: bar }` <br> `false` - Example: `{foo: bar}`                                                                                                                                                                                              |
| `bracketSameLine` | `false`       | 多行**HTML**时,`>` 放在最后一行的末尾，而不是单独放在下一行 <br> `true` - Example: <br><button <br> onClick={ this.handleClick }> <br> Click Here <br> </button> <br> `false` - Example: <br> <button <br> onClick={ this.handleClick } <br> > <br> Click Here <br> </button> <br> |
| `arrowParens`     | `"avoid"`     | 箭头函数只有一个参数时两边加上括号 <br> `"always"` - Example: `(x) => x` <br> `"avoid"` &nbsp; - Example: &nbsp; `x => x`                                                                                                                                                          |
| `endOfLine`       | `"lf"`        | 换行符类型                                                                                                                                                                                                                                                                         |
