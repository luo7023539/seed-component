## 中后台项目组件库

### 目录结构

```
.
├── build      打包相关
├── examples   文档
├── lib        打包文件
    ├── vk-pc-component.common.js  commonjs
    ├── vk-pc-component.umd.js     umd
    ├── ...  		           单文件组件
├── packages          组件
├── src  			其他
    ├── directives  
    ├── mixins     
├── components.json  	组件JSON

```

### `scripts`说明

开发模式、端口`8085`
```bash
npm run dev
```

生成pages模版
```bash
npm run i18n
```

单独打包文档
```bash
npm run build:docs
```

单独组件
```bash
npm run build:dist
```

发布文档
```bash
npm run deploy:docs
```


