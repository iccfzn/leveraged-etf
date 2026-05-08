# leveraged-etf
记录美股的个股与杠杆ETF的对应关系

## 数据格式
| 字段 | 说明 |
|---|---|
| code | 标的代码 |
| bullLeverageCode | 做多代码 |
| bearLeverageCode | 做空代码 |

示例
```
{
    "code": "QQQ",
    "bullLeverageCode": "TQQQ",
    "bearLeverageCode": "SQQQ"
}
```

如果存在有多个杠杆ETF，则取成交量最大的ETF

## 有兴趣的伙伴可以一起添加
