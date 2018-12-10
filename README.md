# AI_Reading_Improvise_Commentary

## Product Requiremenets

<table>
    <tr>
        <td><b>Target release</b></td>
        <td>2018/11/30</td>
    </tr>
        <tr>
        <td><b>Epic</b></td>
        <td>&nbsp;</td>
    </tr>    
    <tr>
        <td><b>Document status</b></td>
        <td><b><code>DRAFT</code></b></td>
    </tr>    
    <tr>
        <td><b>TDocument owner</b></td>
        <td><a href="https://www.github.com/treeice">@林树斌</a></td>
    </tr>    
    <tr>
        <td><b>Designer</b></td>
        <td><a href="https://www.github.com/treeice">@林树斌</a></td>
    </tr> 
    <tr>
        <td><b>TDocument owner</b></td>
        <td><a href="https://www.github.com/treeice">@林树斌</a></td>
    </tr> 
    <tr>
        <td><b>Developer</b></td>
        <td>&nbsp;</td>
    </tr> 
    <tr>
        <td><b>QA</b></td>
        <td>&nbsp;</td>
    </tr> 
</table>


## Table of contents
- [Goal](#Goals)
- [Background and strategic fit](#Background-and-strategic-fit)
- [Assumptions](#Assumptions)
- [Rwquirements](#Rwquirements) 
- - [User Portrait](#User-Portrait)
- - [User Usage Scenarios](#User-Usage-Scenarios)
- [User intercaion and design](#User-intercaion-and-design)
- [Questions](#Questions)
- [Time and Team](#Time-and-Team)
- [Not doing](#Not-doing)
- [Attachment](#Attachment)

## Goals
解决大学生在本校图书馆看书的时刻需要分享个人评论的问题，为大学生在翻阅本校图书馆的图书的时候提供读书弹幕弹幕功能，满足用户在读书的某一时刻分享心得的需求。让用户记录阅读的过程种，那特定时刻所想所感，并分享发布，提供大学生提供本校的阅读评论分享浏览的互动平台。

## Background and strategic fit
根据中国统计局的数据显示：普通本专科招生人数从2013年的699.833万人，逐年增加，到2017已有761.489万人。本科和专科的在校学生占社会人口总比重不断上升和当当网与易观联合发布《2018 中国图书阅读市场专题分析报告》中指出在纸质图书阅读数据中 ,30 岁以下读者比例达到 52.3%，这个是巨大的年轻的大学生市场群体，大学生群体由于学业和身份的关系，本校的图书馆会是他们交流阅读和获取知识的主要场所，根据马斯洛需求原则的第三层社交需求，普遍的大学生在衣食住行等方面没有问题，在社交上，本校的学生总是难以找到陪伴的书友，这个平台会为他们提供在一定程度的社交交友的功能

## Assumptions
用户使用软件时候，使用带有拍摄，播放音频和具备连接网络功能的智能手机和平板设备


## Rwquirements

### User Portrait

<table>
<tr>
    <td><b>name</b></td>
    <td>胡胡</td>
    <td><b>性别</b></td>
    <td>男</td>
    <td rowspan="3"><img  src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1544244682541&di=5e1adf6978c2e1d0882ce4ac5734dc74&imgtype=0&src=http%3A%2F%2Fimgsrc.baidu.com%2Fimgad%2Fpic%2Fitem%2F5243fbf2b2119313d00c309d6e380cd791238d54.jpg" width="300px"></td>
</tr>
<tr>
    <td><b>age</b></td>
    <td>21</td>
    <td><b>Identity</b></td>
    <td>大三</td>
</tr>
<tr>
    <td><b>University Majors</b></td>
    <td>网络与新媒体专业</td>
    <td><b>location</b></td>
    <td>广州</td>
</tr>
<tr>
    <td><b>Hometown</b></td>
    <td>潮州</td>
    <td><b>hobby</b></td>
    <td colspan="2">打羽毛球，打电玩,喜欢科幻电影,看玄幻小说和动漫，看科幻小说和魔幻小说，学画画，学设计</td>
    </tr>
<tr>
    <td><b>Course</b></td>
    <td colspan="4">《互动设计》，《网站运营》，《大数据分析》，《自然模块-科学技术发展史》，《西方艺术史》，《批判性思维》，《品牌战略管理》，《批判性思维》，《管理学》，《品牌策划》，《人文-语文》</td>
</tr>
<tr>
    <td><b>Friends</b></td>
    <td colspan="2">同班同学和临近宿舍的朋友为主,经常一起打游戏和玩耍,交流多以学业和身边娱乐为主,会一起组队做课程作业,,也有因为打羽毛球而相识的球友,但和朋友之间不会主动提及任何小说等读书分享</td>
    <td><b>Roomaate</b></td>
    <td colspan="2">喜欢打电脑游戏,喜欢打球,埋头专研学课作业和兴趣,不爱看课外文学作品,喜欢追番和搞笑新闻,浏览各类社交平台,会一起吃饭</td>
</tr>
<tr>
    <td><b>Use of electronic equipment</b></td>
    <td colspan="2">使用智能手机和电脑,在宿舍内,以电脑为主,在宿舍就维持电脑开启状态,在外平常半小时打开手机一次,课堂上至少十五分钟打开手机一次,手机保持唤醒状态有至少四小时,</td>
    <td><b>Dating software usage</b></td>
    <td colspan="2">每天花费两个小时在微信聊天和朋友圈的浏览中,会浏览微博,知乎,哔哩哔哩等软件</td>
</tr>
<tr>
    <td><b>Rest and recuperation arrangements</b></td>
    <td colspan="2">周末,九点起床,九点半来图书馆看书,十二点吃饭,一点回宿舍打游戏或做作业,三点睡午觉,五点吃饭打球,晚上八点回宿舍,十二点至一点睡觉</td>
    <td><b>Reading situation</b></td>
    <td colspan="2">周末九点半后到中午十二点,一个人在图书馆看书.上课时在教室的课堂上看书,偶尔在宿舍看书</td>
</tr>
</table>

### User Usage Scenarios
<table>
    <tr>
      <th>&nbsp;</th>
      <th>Title</th>
      <th>User stroy</th>
      <th>Importance</th>
      <th>Notes</th>
    </tr>
    <tr>
        <td><b>1</b></td>
        <td>看小说的人</td>
        <td>小东在周末独自一个人来到学校图书馆查看小说消遣，找到小说后，通过扫描图书封面，来获取该书的网友评论资源，阅读小说的时候，看到情节的跌宕而收到影响，一时心急，想和他人分享这个心情，进入软件，在对应的书籍的对应页面上发布评论，留下评论，且查看到了很多同样评论的其他人,打开软件的播放评论功能,软件把通过筛选后的有意思的评论播放出来,小东听了心里得到满足</td>
        <td><b><code>Importance</code></b></td>
        <td>可使用筛选播放评论音频的方式来参与用户的阅读流程，使用到了语音合成，使用<a href="https://cloud.baidu.com/product/speech/tts">百度云API-语音合成</a></td>
    </tr>
    <tr>
        <td><b>2</b></td>
        <td>翻阅其它专业性强的书的人</td>
        <td>小西在学期选择了一门公选课叫做*企业战略管理*，老师要求他们在课外，阅读推荐书籍，她到学校的图书馆找到了《事业战略管理》来看，但是她是学设计的专业的，打开书的目录后，选择性挑着所需的章节翻阅，看到相关的章节中出现了“后一体化”，“低领导战略”等专业名词，她一点也不懂，她也不想再花时间翻阅前面的内容或去找第二本书等渠道来了解这词语的意思，她打开了软件。扫描书本封面，获取了该书的评论信息，进入到了这本书的页面后，她看到了早已有其他人和他一样评论了对专业词语的困惑，也看到了其它人对这个问题的解答并指出对应页码的解释等信息，她了解这个词汇之后，觉得得到了满意的解决</td>
        <td><b><code>general</code></b></td>
        <td>加入字体颜色变化，对解释性和科普性质的评论进行突出显示。和加入点赞的功能置顶部分用户觉得有价值的评论,消除不正当的评论,使用[阿里云API-文本风险内容识别]<a href="https://ai.aliyun.com/lvwang/text?spm=5176.8142029.artificialIntelligence.47.54216d3eQDorG9">阿里云API-文本风险内容识别</a>和<a href="https://cloud.baidu.com/product/ocr/general">百度云API-通用文字识别</a></td>
    </tr>
    <tr>
        <td><b>3</b></td>
        <td>读诗歌的人</td>
        <td>汉语言专业的小北在晚上上床之前，打开了白天在本校的图书馆借阅的《新宋词300首》，在阅读其中某一首诗后，觉得心里有话想说，她扫描书本封面，获取了该书的评论信息，进入到了这本书的页面后，她看到了很多之间借阅的人对这页诗的评论，或好或坏，她看到其中一条上个月的评论和自己心中所想一摸一样，十分开心并加入那个用户为好友，相互认识</td>
        <td><b><code>general</code></b></td>
        <td>可使用随机播放评论音频的方式来参与用户的阅读流程，使用到了语音合成，使用<a href="https://cloud.baidu.com/product/speech/tts">百度云API-语音合成</a></td>
    </tr>
    <tr>
        <td><b>4</b></td>
        <td>打卡的人</td>
        <td>小南最近想看金庸的套书，不知从何看起，所以找了一份金庸的系列小说的顺序清单，他于是去了图书馆，找到了着一本书，在课余时间慢慢借阅这一套图书来观看，《书剑恩仇录》，《碧血剑》......一直到《鹿鼎记》，，看完每一本书，他都会打开软件扫描书本封面，获取了该书的评论信息，进入书本的最后一页，留下评论“2018年11月30号，晚上8点看完，打卡(oﾟvﾟ)ノ”</td>
        <td><b><code>pend</code></b></td>
        <td>增加快速添加打卡信息（时间，位置，心情），功能和情绪类颜文字/表情</td>
    </tr>
</table>

## User intercaion and design
- 平静技术互动原则
- **输入**：图书封面（*OCR扫描技术*），文字评论（文本过滤）

    **输出**：图书信息（书名，出版社，版本号），语音播放（*语音合成*）
	
### 产品流程图 
![流程图](images/FLowchart.jpg)

### 产品信息框架图
以线性结构为主的信息架构,通过记录书籍信息后,在图书的对应页码中浏览或发布相关评论,在所需时候,使用语音功能,为用户提供个性化的评论播放,满足用户在阅读时候的自我表达需求
![产品信息框架图](images/Information_Framework.png)

### 主要功能的简单原型页面
![原型设计](images/simple-page.png)


## Questions

Questions|Qutcome
-|-
提供点赞，置顶，对特定的评论进行筛选强调突出,通过对文本风险内容识别帮助用户清除部分不良评论|辅助用户获取有价值和又有兴趣的信息
使用语音合成,播放语音|解决用户在特定情景无法看评论,却需要人陪同吐槽
拍照检测入口|辅助用户快速获取书籍信息
提供位置信息，切换地址位置|显示附近的评论提供用户交流等方式

## Time and Team
![开发流程](images/PRD01_Timeline.png)

## Not doing
- 对于评论的进一步细化过滤体系,有待商榷
- 部分图书封面设计新颖,使用各种不规则图形,超出OCR所能接受的文本格式,在扫描上可能准确度会比较低,或许有更好的书籍信息登记
- 播放语音,尝试使用[百度云API-情感倾向分析](https://cloud.baidu.com/product/nlp/sentiment_classify)帮助用户,播放用户可能会感兴趣的评论


## Attachment
- [软件流程图](https://raw.githubusercontent.com/treeice/API_ML_AI/master/images/FLowchart.jpg)
- [开发流程图](https://raw.githubusercontent.com/treeice/API_ML_AI/master/images/PRD01_Timeline.png)
- [产品信息框架图](https://raw.githubusercontent.com/treeice/API_ML_AI/master/images/Information_Framework.png)
- [原型图](https://raw.githubusercontent.com/treeice/API_ML_AI/master/images/simple-page.png )





