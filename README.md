# Uperf-Game-Turbo-888plus 调度模块配置
需要已加载Uperf-Game-Turbo 性能调度模块 
https://github.com/yinwanxi/Uperf-Game-Turbo/releases

优化888plus 日常体验 兼顾性能和功耗

简介:

    将888plus 
    performance 模式的大核最高频率固定到2.49Ghz 中核最高频率固定到 2.34Ghz 能耗比最佳频率
    fast 模式大核频率调整到到 2.99Ghz
    调整细节性能调度
  
    实测日常使用体验几乎无卡顿 非常丝滑
  
使用方法 

    把uperf.json 直接复制替换文件  路径:Android > yc > uperf
    正常的话应该会立刻生效
    cur_powermode.txt 确保为auto 默认调度为performance模式 后台为 powersave模式
    perapp_powermode 可以自定义每个应用的调度模式
喜欢的话请给个Star哦
