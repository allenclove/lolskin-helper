# lolskin-helper
Can't find champion? The lolskin-helper can help you use Lolskin.

# 我为什么要做这个小程序
1. 当我使用lolskin的时候，我时常找不到我选择的英雄（我喜欢每把都玩不一样的英雄）
2. 我认为那些可以在游戏中换肤的软件读写了游戏内存，是容易违规（封号）的操作
3. 那些换肤软件一定是有利可图的，免费的有广告（病毒？）/ 收费的要钱

# 为什么使用易语言
因为我觉得易语言可以很轻松就制作一个可执行的exe窗口程序

1. 我曾经使用过python制作exe程序,效果并不好。首先是样式不好看而且组件位置也不好调整。现在可能有其他方式进行调整组件布局方便很多,我没有继续学习和研究了
2. 听说C#很适合用来制作exe程序,但是由于本人非C#程序员,暂时没有时间去学习和制作
3. ui方面，对于易语言本人了解的其实不多，所以这个界面是我所能做到的比较美观的界面了。
4. 了解了electron,未来有可能使用这个技术进行重置


# 使用方式
### 代码方面
- 2.4版本之前的代码未进行版本控制,本程序从2020.10.01日开始研发

1. (开发工具)易语言单文件版可静态编译.rar  -->这个是开发工具,**来源:吾爱破解。优点:单文件,可以静态编译**
2. 然后用解压出来的开发工具打开e语言代码文件(.e结尾的文件):**lolskin皮肤助手3.0自动开启lolskin.e**
3. 注意模块(.ec结尾的文件)和e语言代码文件需要在同一目录下。

#### 编译
1. 上面步骤操作完之后,点击【编译】->【静态编译】-->**选择保存路径和命名**
得到exe文件
### 【为了避免出问题，打开开发工具的时候**请使用管理员打开**，运行编译出来的程序也**请使用管理员打开**】

### 程序方面
 1. **lolskin皮肤助手**程序必须放到C:\Fraps目录下，也就是和lolskin同一目录下
 2. 点击第一个按钮后会自动打开lolskin，如果游戏客户端打开了会自动开启自动选择 英雄功能
 3. 按esc可以直接退出程序，本助手退出后，lolskin将不具有自动选择英雄功能， 请确保先打开lol客户端后通过**lolskin助手**打开lolskin

# 更新日志
### 调用百度文字识别api（较麻烦，对客户端大小有限制，bug较多）
- 1.0~1.2版本，初版
- 1.3版本，联网令牌和UI
- 1.4版本，去自动选择英雄加识别皮肤

### 调用lolApi实现
- 2.0版本，添加api自动选择英雄去除百度文字识别
- 2.2版本，新增先获取一次当前英雄
- 2.3版本，修复lolAPI调用功能
- 2.4版本，修复识别大乱斗英雄
- 3.0版本，添加自动开启lolskin，修复重复开启lolskin，修复获取到相同英雄后lolskin页面不刷新

# 程序使用相关教程


# 注意事项
1. 易语言程序，众所周知很容易报病毒。害怕请互尝试
2. win10，win11亲测可用。win7未测试（如果不能用，我也没办法（检查一下是否赋予了管理员权限））
3. 游戏运行期间请勿开启lolskin（可能有检测机制）


# 学习推荐


# 后续计划
1. 由于本人时间有限，后续可能不再更新易语言版本，随缘了。有需要的可以自行下载代码修改编译【代码比较简单，认真研究就能上手修改了】。
2. 后续以后机会可能使用eletron重置【小概率】。

# 声明
- **本程序仅用于学习程序练习，并且免费，不应该用于其他场合，如有问题，责任由 使用者承担**
- **使用者不应该使用相关成品或者代码进行牟利**

其中还参考了部分调用lolapi的易语言程序(来源于网络),这部分程序在【参考程序】文件夹中可以看到
整个流程基于**原作者Virace**基础(来源于吾爱破解)，本人对自动选择英雄等功能进行了二次开发,对于实现的功能,代码可能略显冗余

# 感谢
- 【吾爱破解乐于分享技术的各位】
- 【来自网络的易语言知识分享者】
