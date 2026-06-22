# 直接上传 GitHub 版本：压缩视频内嵌版

这个版本用于你已经把视频压缩到 25MB 以下的情况。

上传 GitHub 时，请上传本文件夹里的全部内容：

```text
index.html
package.json
package-lock.json
vite.config.js
vercel.json
public/
README_UPLOAD_CN.md
```

其中 `public/media/C_part_video_materials/` 里面有 5 个压缩后的视频：

- `craft_shangxia.mp4`
- `aesthetic_icicle.mp4`
- `lifestyle_tosummer.mp4`
- `visible_shanghaitang.mp4`
- `global_songmont.mp4`

Vercel 设置：

- Framework Preset：Vite
- Build Command：`npm run build`
- Output Directory：`dist`
- Install Command：`npm install`
- Root Directory：如果这些文件在仓库最外层，就留空

这个版本保留：

- C 部分页面内直接播放视频
- E 部分上移/下移排序按钮
- G 部分 AI 润色功能
