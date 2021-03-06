## 1. 接口描述
 
域名: eip.api.qcloud.com
接口名: DeleteEip

释放弹性公网IP。

 

## 2. 输入参数
 

<table class="t"><tbody><tr>
<th><b>参数名称</b></th>
<th><b>必选</b></th>
<th><b>类型</b></th>
<th><b>描述</b></th>
<tr>
<td> eipIds.n  <td> 是 <td> String <td> EIP实例ID列表，数组下标从0开始，可通过<a href="http://www.qcloud.com/doc/api/229/%E6%9F%A5%E8%AF%A2%E5%BC%B9%E6%80%A7%E5%85%AC%E7%BD%91IP%E5%88%97%E8%A1%A8" title="DescribeEip">DescribeEip</a>接口返回字段中的eipId获取
</tbody></table>

 

## 3. 输出参数
 

<table class="t"><tbody><tr>
<th><b>参数名称</b></th>
<th><b>类型</b></th>
<th><b>描述</b></th>
<tr>
<td> code <td> Int <td> 错误码, 0: 成功, 其他值: 失败，具体含义可以参考<a href="/doc/api/229/1234" title="错误码">错误码</a>。
<tr>
<td> message <td> String <td> 错误信息
</tbody></table>

 

## 4. 示例
 
输入
```

  https://eip.api.qcloud.com/v2/index.php?
  &<公共请求参数>
  &eipIds.0=eip-gzc5rgr2

```

输出
```

{
    "code": 0,
    "message": ""
}

```

