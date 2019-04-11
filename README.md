# files-copy

实现文件目录删除、文件目录复制

## 安装下载

- 下载地址 https://github.com/yinMrsir/files-copy/releases

- npm i files-copy

## 快速使用
```
var filesCopy = require('files-copy')

// 删除目录
filesCopy.deleteall(dist)

// 复制目录
filesCopy.copy(src, dist)

```

## 参数说明
<table>
  <thead>
    <tr>
      <th>参数</th>
      <th>说明</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>src</td>
      <td>需要复制的目录</td>
    </tr>
    <tr>
	  <td>dist</td>
	  <td>目标目录</td>
	</tr>
  </tbody>
</table>