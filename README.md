# react-router-config learning

### 如果没有子路由的情况，建议大家配都加一个exact；如果有子路由，建议在子路由中加exact，父路由不加； 而strict是针对是否有斜杠的，一般可以忽略不配置。

#TODO: 替换成 `import { renderRoutes } from "react-router-config";`

## path都为空，它会命中任何的路由，不能放在前面
