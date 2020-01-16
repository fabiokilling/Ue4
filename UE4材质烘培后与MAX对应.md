首先在UE4引擎里面复制模型（骨架网格体）放入Test文件夹

然后将材质球复制到Test文件夹

然后选择骨架网格体，点击烘培出材质，Blend Mode选择Opaque，在下方Properties里添加满所有的数组元素。

Texture Size 一般选择 2048X2048

然后将所有贴图保存。

贴图对应关系：
AmbientOcclusion(AO)----环境光颜色
BaseColor----漫反射颜色
Specular（高光）----高光颜色&高光级别
Roughness（粗糙）----光泽度
EmissiveColor(自发光)----自发光
OpacityMass(透明遮罩)----不透明度
Normal（法线）----凹凸
Metallic(金属)----反射
