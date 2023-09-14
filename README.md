# google cloud run 部署 nodejs express 應用

## steps

### 安裝 cloud cli

https://cloud.google.com/sdk/docs/install-sdk

### 在 cloud console 創建專案

https://console.cloud.google.com/cloud-resource-manager?hl=zh-cn

### 初始化流程

https://cloud.google.com/run/docs/quickstarts/build-and-deploy/deploy-nodejs-service?hl=zh-cn#whats-next

```
gcloud init
```

### 找到範例的 Dockerfile

這裡看起來也可已指定專案外的 Image 資源來建立，但參照範例，在專案內建立一個 Dockerfile 也可  
https://github.com/GoogleCloudPlatform/nodejs-docs-samples/blob/4000d1a341cbfcec12cc433c10b11d3fbd1a59df/run/helloworld/Dockerfile

### 部署

```
gcloud run deploy
```

### 部署結果

https://node-app-bkesfnmglq-de.a.run.app/

---

2023/SEP/14 整理
Jason Lien
