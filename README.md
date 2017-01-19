选择buildsetting中的Windows Store 

你可以在场景中添加更多元素来创造自己的3D世界。场景布置完毕后，需要发布应用并使用模拟器测试。Unity支持多种发布目标平台。但Hololens只能与Windows Store（Windows商店）发布平台兼容。Windows Store是最新的Microsoft APIs（微软API）。在Windows Store发布的方式是点击File → Build Settings就会弹出如下的窗口。（如果Windows Store的选项的Build按钮是灰色的，无法按下并且提示No Windows Store Module loaded 意味着 UWP Runtime 的相应组件并没有被安装，请访问Unity Technical Preview页面下载相应的UWP Runtime文件。双击下载好的文件，并指定Unity所在目录，注意不是Unity Editor所在目录，安装完毕即可。）


设置如下


 然后在playersetting中设置

选择WindowsStore按钮图标

全部设置好了以后就可以点击build打包了,但是这个时候回出现这么一个问题,

这时你可以看一下unitywindows窗口下边的Holographic标签. 会提示我们的电脑需要windows14318或者更高的版本才支持


现在就需要去电脑里边查看一下自己电脑的版本了.
这么查看: win+R键输入 cmd 然后再输入winver 回车,当然这个需要的是英文状态下的输入.

出现的页面就是我们的版本号.如果系统要求低于我们的引擎要求.这时我们就需要升级我们的系统了.

电脑程序开始处→ 设置→更新和安全 → 检查更新,如果不能检查到更新,可以尝试看看系统里边的<win10企业版系统不能自动更新解决方法>  .  或者是借用腾讯电脑管家之类的系统工具
