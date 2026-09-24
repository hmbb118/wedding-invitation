背景音乐导入目录
==================

把婚礼纯音乐文件命名为 wedding.mp3 放进这个目录即可自动生效。

用法：
1. 准备一首婚礼相关的舒缓纯音乐（mp3 格式）
2. 重命名为 wedding.mp3，放入本目录（public/audio/wedding.mp3）
3. 重新构建 + 部署，封面右上角音乐按钮即可播放

说明：
- 若未放入本地文件，按钮点击会自动 fallback 到线上免版税婚礼纯音乐
- 想换线上兜底链接，改 src/lib/constants.ts 里的 WEDDING_MUSIC_FALLBACK_URL
