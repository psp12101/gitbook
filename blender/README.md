
# blender 快捷键

## UI pie menu

```
file => user Preferences => Add-ons => Pie Menu: UI pie menu
tab 键选择编辑模式
Q 键选择视图
```

## 切换到鼠标左键选择物体

```
file => user Preferences => input => select with: left

```
## 配置数字键盘和鼠标滚轮

```
file => user Preferences => input => emulate numberpad 

```

## object mode 3d 模式

```
 tab 
 shift + D 复制  
 alt + d 复制（linked）
 M 移动到另一个图层
 shift 选择两个物体 => ctrl +j 合成一个物体

```

### 数字键盘

```
	7: top 视图
	1: front 视图
	3: side 视图
	5: perspective 视图
	0: 选择相机后切换到相机视角

```

### 添加删除

```
	shift + A:  添加物体
	x: 选择物体如果删除
	space: 搜索

```

### 平移，放缩，旋转物体或者场景

```

	鼠标滚轮按下 旋转整个场景
	shift + 鼠标滚轮按下 平移整个场景
	+ 放大场景
	- 缩小场景
	S 放缩  用 ctrl 控制精度
	S => shift + x  只放缩 y, z 轴方向，不放缩 x 方向
	S => x  只放缩 x 方向
	G 平移  
	G => x 沿 x 移动  
	G => y 沿 y 移动
	G => z 沿 z 移动
	G => 鼠标滚轮 动态沿着轴移动
	R 旋转

```
### 调整绝对尺寸

```
  比如要把一个 2*2*2 的立方体的绝对尺寸缩小到 1*1*1
  直接调整dimension 或者 scale 是没有什么用的  
  N 调出调整尺寸dimension 的界面
  
  1. Object Mode ，选择你要修改的物体
  2. 按 N 调出调整尺寸dimension 的界面，调整 dimension 到 1 * 1 * 1 ， 这时候 scale 是 0.5 0.5 0.5 
  3. ctrl + a
  4. 选择 scale ，这个时候 dimension 到 1 * 1 * 1 ， 这时候 scale 是 1 1 1， 绝对尺寸调整完成了
```

### modifier 扳手

```

	add modifier

	subdivision surface 细分
	wave 波浪动画 => alt + a 查看效果
	space => quick smoke  => alt + a 查看效果
	立体化  add modifier  => solidify  建立一个面的时候，添加厚度

```

----------

## curve to mesh

```
	alt + c
```

## 去除父子关系

```
	object => parent => clear parent  
```

## edit mode 编辑模式 

```
 	Tab 
 	Ctrl + R  添加控制线  => 滚轮 => 添加多条控制线 => 右键确保的初始位置
 	Alt + 点击 => 选择控制线 => 双击 G => (E, F) 选择控制线移动方式
 	O => s (放缩) => shift + z( z 轴保持不变) 
 	编辑模式 => A => W => Remove doubles 去除重复的点
 	Shift + E => 拉升边界，由圆角变锐角
	i 多边形面内插控制线
 	对齐两个不齐的点（比如在 Z 轴方向对齐）
 		选择两个不齐的点 => E => Z => B (选择一条对齐的线) => S (放缩) => Z => 0(数值0)
	创建一个面： 选择4个顶点 => f
	
	删除重叠的顶点： a => w => Remove Doubles
	shift 选择两个面 => w => bridge edge loops 桥接两个面
	调整面的法向量 选择面 s => x(选择放缩的方向) => 0 角度 
	隔一个选一个或者隔两个选一个，选择一个 面loop => 菜单栏 select => checker deselect
	shift + ctrl + alt + c  => origin to 3d cursor 将物体的原点调整到世界坐标的原点; origin to geometry 将物体的原点设置在物体本身的原点上
	选择一条控制线 alt + 边 => ctrl + b 拖动 => 生成 bevel
	ctrl + 选择相邻的面，点或者边
	旋转阵列 => 编辑模式(选中要阵列的部分) => alt + r => 选中 Dupli 以及 step 设置步数
	去掉直线段多余的控制点 a => x => limited dissolve
	显示法向量和调整法向量方向：tab 进入 edit mode => N 进入数据面板 => mesh display => normals 选择点，线，面显示法向量 ； T => shading /UVS => normals => Flip direction 翻转法向量方向 
	
	shift + a => lattice => 右侧面板 切换到 lattice tab => lattice =>编辑 U V W的值, 用于调整lattice 的分格数 
	选中要变开的物体 => Add Modifer => lattice => 选择上一步建立的lattice => 进入lattice edit mode , 拖动lattice 的顶点，就可以对lattice 控制的物体进行变形了
	edit mode => 选择一条边 => ctrl + e => edge split => 移动一下面，这样就把边拆分开了
	file => user preferrence => Mesh F2   edit mode => f 用于三个点生成四边形
	选择一个物体 A 右侧 object Tab => Display => X-ray ;这样就可透过物体B看到物体A 了 
	片填充：选择一个loop => space => grid fill 
	edit mode => 选择一条边 ctrl + right click => 拉伸
	file => user preferrence => add On => add mesh + add curve 添加新的类型，单点，数学图形等
	
	alt + b => clipping border
```

### 选择模式 

```
ctrl + tab => v 选择顶点
ctrl + tab => f 选择面
ctrl + tab => e 选择边
```

### 顶点选择模式 vertice 

```
    alt + 点选两点之间选择圆环线
    shift + 点多次，选多个点
    滚轮按下 => 取消选择的点
    alt + shift 可以选多个圆环线
    alt + M 合并两个点到一个点
    k 添加线 => c 线的对齐方法 => enter 确定

```

### 边选择模式 edge

```
	alt + shift 可以选多个圆环线
	shift + 点多次，选多个边
```

### 面选择模式 face

```
	alt +  shift 选连续两个面 选择一个圆环面
	shift + 点多次，选多个面
```

### 范围选择

```
    b => 左建选择区域选中
    b => 鼠标滚轮取肖区域选中
    a 选择所有 或者取消选择所有
    c  圆环选择区域 => 左键 => 滚轮滚动（控制选择范围大小）
    c  圆环选择区域 => 滚轮按下取消选择范围 => 滚轮滚动（控制选择范围大小）

    切换可见不可见点的选择 limit selection to visible , 是否可以选中被挡住的点
    ctrl + 右键 => 选择自定义选区
    
```
> 同样的可以 

```
	G 移动
	S 放缩
	R 旋转


	O 联动  => 移动 + 滚轮（控制选择范围）
	联动的曲线效果有好几种
		smooth
		sphere
		root
		Inverse square
		sharp
		linear
		constant
		random

```

### 选择显示的模式

```
	z 切换模式
	solid 模式
	wireframe 模式
```

### 复制

```
	shift + d   => M 移动到另一个图层
	alt + d => linked copy
	复制后按 p => by selection  变成一个可选择的独立物体   

	如果重合在一起，
	选择一个重在一起的点，再 ctrl + L 就可以选择出重在一起的复制对像
	还有一个 remove doubles , 按下a 再点remove doubles 清除重复的点

```

### 显示,隐藏

```
	影藏物体   选中物体  h
	显示物体   alt + h 全部显示出来了
```

### 渲染模式rendered 和 3d 模式 切换 

```
	shift + z
```

### snap  

```
	shift + s => 
		cursor to center
		cursor to selected 
		cursor to grid 
		cursor to Active
		
		selection to grid
		selection to cursor
		selection to Active
		selection to cursor(offset)
```

## 渲染引擎

### blender render

### cycles render(用这个)

### Node editor 用于编辑各种光照模型, 注意是在 cycles render 渲染引擎下

```
	shift + a 添加
		Input
		Output
		Shader
			Mix shader 
			Glossy shader
			Diffuse BSDF
		Texture
			Image texture
			Gradient texture
		Color
		Vector
		Convertor
		Script
		Group
		Layout
    
```

## UV 贴图展开

```
	切换到 edit mode => 边框选择模式
	shift 选择多条边 
	ctrl + e => mark seam
	a(选中所有顶点) => U => unwrap 展开
	选择边 => v => enter 缝合 
	左侧 options => Live Unwrap 实时展开 
	ctrl + p => 分开 pack（铺满）
	reset => ctrl + p => 平均展开
	https://www.youtube.com/watch?v=brnaAL-QwhU
		
```

## 隐藏左右侧菜单

```
	隐藏显示左侧菜单  T
	隐藏显示右侧菜单  N

```

## 材质

```

	noise texture  
		diffuse BSDF
		glossy BSDF
		emission
			mix shader
				material Output 


	matcap 材质显示方法
		N => shading => matcap
```

# 合并，交集，相减

```

	Add modifier => Boolean 

	动态查看两个模型人boolean 操作，一个 soid , 另一个 线框显示
	display => maxium display type => type

	合并两个物体
		按住“shift”选中两个物体，然后“ctrl+j”进行合并
	拆分一个物体
		如果我们想把个一个“特征”拆分成另一个物体，可以进入“编辑模式”，选中这个“特征”，然后我们按“p”键，选择“选中项  P”。
		再次回到“物体模式”，我们发现现在已经是两个物体了，“特征”也是单个物体了。
```

# 同时显示多个图层

```
按 shift 并点选多个图层，多个图层里的物体就会同时显示出来 
```

# 阵列
[ 方法2参考视频](https://www.youtube.com/watch?v=TN52oH2WxjU&list=PLOs8m1ECfMkhhGXVMbcz5GIs52jlE1zV-&index=19)
```
 方法1：
 ctrl + a => empty => cube 新建一个空的立方体
 选择要阵列的物体 => Add Modifers => Array => Object Offset (选择empty cube) => 选中 empty cube 旋转一下
 
 方法2：
 先对一个物体进行阵列,比如一个立方体 Add Modifer => Array => Relative Offset:20 
 再建一个 shift + a => Curve => circle 
 选择 立方体阵列 => Add Modifer => curve => object => Beziercircle => 然后 s 放缩 
 
 
```

# 动画
```
 i 添加关键帧数据点
 
```

# 绘制贴图
[参考地址](https://www.youtube.com/watch?v=LcCQKuWPhXk)

### 创建模型

	shift + a 创建一个立方体
	切换到 cycles render 渲染引擎

### 展开 UV 贴图

    tab 切换到 edit mode
    shift 选择要切开的边
    ctrl + e => mark seam
    然后 按 a 全选 => u => smart uv project
    选择面 => p => pinning uv  ;   alt + p => unpinning uv
    https://www.youtube.com/watch?v=brnaAL-QwhU

### 导出 UV layout

	拉出一个视口 => 切换到 UV/Image Editor
	在前一个 edit mode 视口 => a 全选所有顶点
	在当前UV/Image Editor视口下方菜单栏 => UVs => Export UV Layout => uv.png

### 创建手绘目标图片
	
	在当前UV/Image Editor视口下方菜单栏 => Image => New Image 
	创建一张新的手绘图片 => paintImage

### 创建立方体材质 paintTexture

	再拉出一个新视口 => 切换到 Node Editor
	在最右侧新建一个材质(不要用之前的材质) => 命名为 paintTexture
	选中 use Nodes， 面板上出现 Diffuse BSDF(shader)

### 将手绘图片(paintImage) 关联到 paintTexture

	在 Node Editor 下方菜单栏
	Add => Texture => Image Texture(color 连接上 Diffuse BSDF 的color)
	Image Texture 下拉选择 paintImage;

### 将 edit mode 视口 => 切换到 Texture paint 
	左边出现绘制菜单栏, 如果没有出现, 按 T
	就可以开始绘制了
	
## 从高精度模型向低精度模型的法向贴图

[参考视频](https://www.youtube.com/watch?v=0r-cGjVKvGw&t=29s)
	
### 建模型
	
	在图层1建一个立方体1(high poly)
	在图层2也建一个立方体2(low poly)

### 展开立方体2(low poly)的UV贴图

	选中立方体2 => tab => 选择边 => mark seam => smart uv project

### 组合两个模型的位置

	shift 选中两个图层中的模型 => Alt + G
	这样两个模型位置对齐了

### 创建 normal 图片

	选中立方体2(low poly)模型， 进入 UV/Image Editor视口下方菜单栏 => Image => New Image 
	创建一个图片, 命名为 normal, 去掉alpha 通道

### 创建材质
	
	将渲染引擎切换为cycles render,  选中立方体2(low poly)模型
	新建一个材质, 并关联上 normal 图片

### bake normal 贴图

	找到 render tab 下的 bake 栏
	Bake Type： noraml
	space: tangent
	选中 select to active => 先选中 立方体1(high poly) => 再选中 立方体2(low poly)
	ray distance: 0.2(根据需要设置值)
	点 bake 出 法向图 => 保存
	
## blender 导出 obj 

### 渲染引擎设置

```
	只能使用 Blender Render, 才能导出 mtl材质; 使用Cycles Render 则不可以。

```

### 材质建立过程例子

#### 立方体

```
	1. Ctrl + A => Mesh => Cube 
	2. 右则选择 Material 面板 => New => 改名为 'cubeMaterial'
	3. 切换到 Texture 面板 
		3.1 New => 改名为 'diffuseTexture'(不改也可以)  => image => open => 选择一张 diffuseMap 图片 => Influence => diffuse => color
		3.2 New => 改名为 'normalTexture'(不改也可以)  => image => open => 选择一张 normalMap 图片 => Influence => Geometry => normal
		3.3 New => 改名为 'reflectionTexture'(不改也可以)  => image => open => 选择一张 reflectionMap 图片 => Influence => Specular => color

```

#### 球体

```
	1. Ctrl + A => Mesh => UV Sphere 
	2. 右则选择 Material 面板 => New => 改名为 'sphereMaterial'
	3. 切换到 Texture 面板 
		3.1 New => 改名为 'diffuseTexture'(不改也可以)  => image => open => 选择一张 diffuseMap 图片 => Influence => diffuse => color
		3.2 New => 改名为 'normalTexture'(不改也可以)  => image => open => 选择一张 normalMap 图片 => Influence => Geometry => normal
		3.3 New => 改名为 'reflectionTexture'(不改也可以)  => image => open => 选择一张 reflectionMap 图片 => Influence => Specular => color

```
### mtl 中的值在 blender Material 面板中如何设置

```
	Ns(specular highlight, 取值 0 到 1000) => Material 面板 => Specular => Hardness  
		"exponent" is the value for the specular exponent.  A high exponent 
		results in a tight, concentrated highlight.  Ns values normally range 
		from 0 to 1000. 在blender 里面 hardness 的取值在 1 ~ 512之间, 跟 Ns 的关系为 0.512 * Ns = hardness
		
 
	Ka(ambient color) => Material 面板 => Shading => Ambient
	Kd(diffuse color) => Material 面板 => Diffuse => 颜色 + Intensity
	Ks(specular color) => Material 面板 => Specular => 颜色 + Intensity
	Ke => Material 面板 => Shading => Emit
	Ni => Material 面板 => ??
	d(alpha) => Material 面板 => Transparency => Alpha

```

### 导出选项

```
 	file => export => wavefront(.obj)

 	选中项

 	-z Forward
 	Y Up
 	Write Normals
 	Include UVs
 	Write Materails
 	Triangulate Faces
 	Objects as OBJ Objects
 	Auto / Copy(复制到当前路径位置)

```

### 模型 unlink 和重新确定中心位置

```
unlink: object => Relations => Make single user => Object & data
origin: object => set origin => Origin to Geometry

```

### blender 2.8 阴影贴图

```
   0. 选择 cycles render (右则 scene => Render Engine)
   1. 创建一个平面做为地面
   2. 创建一个立方体
   3. 给平面一个贴图 (展开贴图=> 新建材质 => use node => 添加 base color => image1)
   4. 调整光源，将源放置在合理的位置
   5. 将阴影bake 到 平面(rendering => 右侧的scene => Bake => Bake Type => shadow => 点击 bake)
```

### blender 2.8 Eevee 透明材质

```
   1. material properties  => settings => Blend Mode:Alpha Clip; Clip Threshold 0.5 
   2. 顶部选择 shading => 右侧Scene Collection 选择物体 进入 Nodes 编辑页面
```
