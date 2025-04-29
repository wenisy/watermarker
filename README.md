# 图片水印生成器

本项目为纯前端图片水印生成工具，支持自定义打卡时间、日期、地点等信息，适用于考勤、拍照打卡等场景。

## 使用方法

1. 打开 [GitHub Pages 部署地址](https://wenisy.github.io/watermarker/)（首次部署后生效）。
2. 上传图片，填写打卡信息，点击“应用水印”。
3. 预览并下载带水印的图片。

## 本地开发

直接用浏览器打开 `index.html` 即可，无需后端。

## 部署到 GitHub Pages

1. 推送代码到 main 分支：
   ```bash
   git remote add origin git@github.com:wenisy/watermarker.git
   git branch -M main
   git push -u origin main
   ```
2. 在 GitHub 仓库设置中启用 Pages，分支选择 main，目录选择根目录（/）。