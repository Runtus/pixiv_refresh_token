## 获取Pixiv Refreshtoken

```shell
# 安装
yarn

# 运行
yarn go
```
* 随后根据命令行提示进行操作。


### 代理 Proxy
* 代理设置直接进入`src/index.ts`修改proxy对象即可。
* 如果不需要代理，将`work`字段改为false即可。
```typescript
const proxy: AxiosProxyConfig = {
  work: true,
  host: '127.0.0.1',
  port: 7890
}
```
