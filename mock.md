## mock.js的语法

### 实现自增效果

```
"id|+1": 1,
```
tip:自增加一，初始值为1  ,初始值必须为数字

### 布尔值

```
"sign|1": true,
```
tip:true和false的几率为50%

### 实现状态为 0和1 

```
"state|0-1": 1,
```

### 日期  年月日

```
"starttime": "@date",
```

### 时间  时分秒

```
"tradeDate": "@time",
```

### 日期时间  年月日 时分秒

```
"tradeDate": "@datetime",
```

