# k8s-client-go

一些调研k8s client-go用法的小demo

# 清单

* demo1: 连接k8s
* demo2: 解析yaml为json, 反序列化到deployment对象, 修改deployment.spec.replicas, 提交到k8s生效
* demo3: 更新deployment.Spec.Template.Spec.Containers, 升级镜像版本, 提交到k8s生效
* demo4: 更新deployment, 循环获取部署状态, 判定部署完成, 并获取最新pod列表与失败原因
* demo5: xterm.js的基本用法, 为后续web ssh访问k8s container做铺垫
* demo6: xterm.js+client-go remotecommand实现完美web ssh登录container

# 效果

<img src="web ssh.jpg">

# 参考

* [client-go doc](https://godoc.org/k8s.io/client-go/kubernetes)
