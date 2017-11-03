
# blender 快捷键

## object mode 3d 模式

```
 tab 

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

## edit mode 编辑模式 

```
 tab 
 
```

### 顶点选择模式 vertice 

```
	alt + 点选两点之间选择圆环线
    shift + 点多次，选多个点
    alt + shift 可以选多个圆环线
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
	shift + d   
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

## UV 展开

```
	切换到 edit mode => 边框选择模式
	shift 选择多条边 
	ctrl + e => mark seam
	U => unwrap 展开
```
