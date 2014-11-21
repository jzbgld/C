C
=
I am LD, and this is for my c code!
你也许不懂如何造一辆凯迪拉克，但你可以驾驶凯迪拉克。
你也许不懂Evernote是用什么技术做出来的，但你也可以使用Evernote。
你也许不懂Git，但你可以使用Github。

作为想要1小时学会大体使用Github的刚刚学习前端10天的技术盲，我是这样做的：

了解Github的基本功能：也就是为什么用Github。
Repository：你和我一起做“知乎首页”，“知乎首页”就是Repository，即项目或者”未来武器T2级425mm磁轨炮“之类，怎么叫随你，你只需知道Repository是个放项目的地方就行。有时候会出现Repositories，是多个Repository的意思。
Folk：我们把制作“知乎首页“的工作分开，你负责美工，我负责前端开发，但我们还需要数据服务器高手。你找来了一位php大牛，这位大牛很快搞定了服务器端，闲来无事，就看了看我的前端代码，一看，“我靠，这怎么一点也不语义化呢？全是尼玛的清一色的<div>啊，将来做交互js还搞不搞dom了……”于是这大牛在Repository中找到了我写的“zhi.html”，Folk了一份，也就是授权拷贝。
Branch：Fork之后，在大牛的Github上出现了一个同样叫做“知乎首页”的Repository，但是这个Repository是复制品，只归他，这就是他的Branch，也就是分支。
Pull Request：大牛做完了一份全新的高端zhi.html，点了Pull Request，也就是推送请求。我接受了，看了一眼，顿时惊讶爆表，“中国足球——高，实在是高！”
现在你懂了，Github的结构是Repository-Branch-(获取/推送)文件。你又发现Github可以比较两个文件的异同，新增的部分用绿色标记，删除的部分用红色标记。Pull Request还可以控制，甚至可以合并Branch，这就是团队合作利器啊，真乃高大上也，手痒了吧？心动了吧？
请注册Github并登录。
下载客户端并登录，客户端负责你硬盘上的数据与Github服务器数据的交互，然后设置存储目录。为了表现你的才华，你决定将此目录命名为“诸神之爹”。
既然有这么多的国外开源项目，我们国内哪有不自主的道理。必须要实践一下这个顶好赞的Folk功能。现在你来到了Fadeoc/frontend · GitHub，你看到了这是用户Fadeoc的一个叫做“frontend”的Repository，你笑了，这家伙学习前端知识不过十天，代码一片渣，竟然有的代码里只写了“土豆”和“二狗子”几个汉字。你点了一下右上角的Folk，然后clone in desktop，保存到“诸神之爹”，哇！文件已经在你电脑里了，完全免费耶！+10086！
一个小时后，你对Fadeoc的渣代码颇有心得，决定帮他改良，不然他这项目就完了。你改好之后，Pull Request，这丫的竟然说你的代码太渣，不吸收。贱人！老子自己做，抢你市场份额！
你点了右上角自己头像后面的+号，选择了第一个New repository，即新建repository，并且起了个名字，叫做“完爆Fadeoc”，然后点击绿色按钮set up in desktop，弹出保存框，选择“诸神之爹”。于是“诸神之爹”下出现了一个“完爆Fadeoc”的文件夹。
你自己写了一份“神爹首页.html”，把它放在了“完爆Fadeoc”文件夹下。
你打开了客户端，看到客户端界面中master Branch（主人分支，这名字太云端了）出现了一个Uncommitted changes，即未提交的变动，也就是你刚写的“神爹首页.html”。你点开show按钮，在summary（摘要）的部分添上“滚你丫的Fadeoc”，在Description（细节描述）的位置是没必要写的，但你还是决定添上“爆你菊花”四个大字。然后选择“Commit to 你的用户名”。
为了把这个提交上传到Github上让贱人Fadeoc看到，你点击了客户端右上角的后面显示了一个“+1”的Sync，即同步，过了几秒，Sync前的两个曲线箭头停止了转动，同步成功了，“+1”消失，表示一个文件成功上传。
你来到Github，刷新自己的个人页，“完爆Fadeoc”这个Repository出现在页面上，点开它，在里面你看到了”神爹首页.html”。
为了让这个项目的初始目的更加浅显易懂，你决定添加一个Readme.txt，虽然从前下载的N多软件的文件夹里总是有一个Readme.txt，你一个都没打开过。但在圈里混，就得混的人模狗样的，于是你在“完爆Fadeoc”下新建了一个Readme.txt，里面写上，“Fadeoc，没错，说的就是你，看我口型，你个贱人！”
同样使用客户端commit，然后sync，过了几秒，刷新github，你看到又多出了一个readme.txt。而且在下面又多出一个文字显示框，里面显示的就是readme.txt里面的内容“Fadeoc，没错，说的就是你，看我口型，你个贱人！”，避免了Fadeoc这个贱人不想打开readme.txt也就看不到你亲切问候的尴尬局面。Github真是贴心呐。
你复制了这个Repository的地址，Email给了Fadeoc。
Fadeoc不是那么容易被打败的，于是他Folk了你的Repository，修改了readme.txt，然后pull request，你看到fadeoc新生成的branch下的readme.txt被改成了“你才是贱人”。你拒绝了合并请求。
Fadeoc再次pull request，readme.txt改成了“敢不做恶吗？”
你有点烦了，这他妈的怎么才能不让他pull request，将来大项目N多陌生人菜鸟pull request烦不烦，就不能不开源，转私有吗？你终于找到了Github的升级服务，你笑了，将这个Repository从Public转成了Private。Fadeoc肯定会继续pull request，得不到你回应的他只会渐渐被复仇的怒火烧尽理智，可是，谁在乎呢？
Github还有更多细节功能，在使用过程中，你会慢慢发现，慢慢学会。但是不管如何，现在你会使用Github的基本功能了。
