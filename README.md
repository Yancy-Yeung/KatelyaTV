## 📰 项目声明

本项目自「KatelyaTV」演进而来，为其三创/继承版本，持续维护与改进功能与体验。保留并致谢原作者与社区贡献者。

> **🔔 重要变更**：将播放历史去重，不喜欢一大堆重复的播放历史，只保留相同片名的最后一个播放源

```
docker run -itd \
--name katelyatv \
--restart=always \
-p 3000:3000 \
-e USERNAME=adminstrator \
-e PASSWORPASSWORDRD \
-e NEXT_PUBLIC_STORAGE_TYPE=redis \
-e REDIS_URL=redis://REDDOMAIN:PORT \
-e REDIS_PASSWORD=REDISPASSWORD \
-e REDIS_DATABASE=1 \
ghcr.io/yancy-yeung/katelyatv:latest
```