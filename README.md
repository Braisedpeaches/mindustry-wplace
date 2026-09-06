# Mindustry 图纸 → Wplace 像素图

贴一段游戏里复制的图纸代码，导出一张 8 像素/格、颜色已对齐 Wplace 64 色表的成品 PNG。
倍数可以设成 1–8（1 = 每格 8 像素，即 Wplace 一格；N = 每格 8N 像素，占 N×N 格）。

**所有计算都在你自己的浏览器里完成，不联网、不上传任何东西。** 页面本身也只依赖这一个文件。

## 用法

1. 游戏里选中建筑 `Ctrl+C`（或在图纸列表里复制代码）。
2. 粘进页面，按需调倍数 / 炮塔朝向 / 是否裁掉四周留白，点「生成」。
3. 下载 PNG，对着它在 Wplace 上画。

## 离线使用

仓库根目录的 `index.html` 就是全部程序（约 1.7 MB，图集和色表都内嵌在里面）。
把它下载下来双击打开即可，不需要网络。

## 许可与署名

- 图纸解析与渲染：[mindustry-schematic-parser](https://github.com/JeanJPNM/mindustry-schematic-parser) © JeanJPNM，MIT License。
- 建筑像素图：Mindustry 原版素材的手工改绘。Mindustry 素材与代码 © Anuke，**CC BY-NC-SA 4.0**
  （署名 · 非商业性使用 · 相同方式共享）。
- 因此本项目同样按 **非商业** 分发：不要把它做成收费服务或用于商业推广；再分发时请保留以上署名与许可。

Wplace 是第三方协作像素画平台，与 Mindustry、Anuke 无隶属关系。
