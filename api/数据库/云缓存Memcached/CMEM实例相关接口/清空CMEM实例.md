## 1. 接口描述
 
域名: cmem.api.qcloud.com
接口名: ClearCmem

清空CMEM实例
可调用地域：广州、上海、北美
单个实例每天清空次数限制为5次

 

## 2. 输入参数
 

<table class="t"><tbody><tr>
<th><b>参数名称</b></th>
<th><b>必选</b></th>
<th><b>类型</b></th>
<th><b>描述</b></th>
<tr>
<td> cmemName <td> 是 <td> String <td> 实例名称
</tbody></table>

 

## 3. 输出参数
 

<table class="t"><tbody><tr>
<th><b>参数名称</b></th>
<th><b>类型</b></th>
<th><b>描述</b></th>
<tr>
<td> code <td> Int <td> 错误码, 0: 成功, 其他值: 失败
<tr>
<td> message <td> String <td> 错误信息
</tbody></table>

 

## 4. 示例
 
输入
```
  https://cmem.api.qcloud.com/v2/index.php?Action=ClearCmem
  &<公共请求参数>
  &cmemName=9003_TE

```

输出
```

{
    "code": 0,
    "message": ""
}

```

