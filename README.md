# baidu-BoundaryData
百度地图 省级 市级边界数据


## init

```shell

npm i baidu-boundarydata 

```


## usage


```

import { ningxia, qinghai } from 'baidu-boundarydata'

// ningxia.cityCode , ningxia.provinceCode

```
```
//TS
import * as mapData from 'baidu-boundarydata'
const areaMap = {
  fujian: mapData.fujian.cityCode,
}
const provinceMap = {
  fujian: mapData.fujian.provinceCode,
}
export { areaMap, provinceMap }
```