# UEImgui

在UE4中使用Imgui

### main分支即日起停止维护，所有疑难杂症预计会在Docking分支得到解决，Docking分支完成后将会替换主线 


**Example**: 将根目录下的[Examples](./Examples/)拷贝至任意Module下(需要引用Imgui和UEImgui模块)即可看到示例效果

**TODO**: 
- [ ] Color/Vector/Transform等基础类型的Editor支持

**疑难杂症**:
- [ ] ★ToolTip与Pop的位置校准
- [x] ★输入法接入
- [x] GlobalContext的Focus与UE不一致
- [ ] Imgui窗口重叠关系与Unreal不一致
- [ ] ~~★Modal窗口无法正常弹出~~(Unreal的窗口是阻塞的，对Imgui来说是致命伤)
- [ ] PopUp窗口偶现层级错乱
