# rsshub-nuist

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/gylidian/rsshub-nuist) ![GitHub issues](https://img.shields.io/github/issues-raw/gylidian/rsshub-nuist) ![GitHub](https://img.shields.io/github/license/gylidian/rsshub-nuist) ![GitHub followers](https://img.shields.io/github/followers/gylidian?style=social) ![GitHub stars](https://img.shields.io/github/stars/gylidian/rsshub-nuist?style=social) 

> :cat: 近期将会
>
> - 针对学校新官网进行调整
> - 重构代码，独立成npm模块
> - 信息中心+基建+图书馆 等通知聚合
> - 支持webhook、cqhttp

RSSHub 南京信息工程大学官网公告爬虫 https://docs.rsshub.app/university.html#nan-jing-xin-xi-gong-cheng-da-xue

## 南京信息工程大学

> :cake: **提示**
>
> 路由地址全部按照 **学校官网域名和栏目编号** 设计
>
> 使用方法：
>
> 以[南信大信息公告栏](https://bulletin.nuist.edu.cn/)为例，点开任意一个栏目
>
> 获得 URL 中的**分域名**和**栏目编号（可选）**：https://`bulletin`.nuist.edu.cn/`791`/list.htm
>
> 将其替换到 RSS 路由地址中即可：
>
> https://rsshub.app/**nuist**/`bulletin` 或 https://rsshub.app/**nuist**/`bulletin`/`791`

### 南信大信息公告栏

作者: [@gylidian](https://github.com/gylidian)

举例: https://rsshub.app/nuist/bulletin/791

路由: `/universities/nuist/bulletin/:category?`

参数:

- category, 可选 - 默认为 `791`


| 全部    | 文件公告 | 学术报告 | 招标信息 | 会议通知 | 党政事务 | 组织人事 |
| ------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **791** | 792      | xsbgw    | 779      | 780      | 781      | 782      |

| 科研信息 | 招生就业 | 教学考试 | 专题讲座 | 校园活动 | 学院动态 | 其他 |
| -------- | -------- | -------- | -------- | -------- | -------- | ---- |
| 783      | 784      | 785      | 786      | 788      | 789      | qt   |

> :warning: **注意**
>
> 全文内容需使用 校园网或[VPN](http://vpn.nuist.edu.cn/) 获取
>

### NUIST CS（南信大计软院）

作者: [@gylidian](https://github.com/gylidian)

举例: https://rsshub.app/nuist/scs/2242

路由: `/universities/nuist/scs/:category?`

参数:

- category, 可选 - 默认为 `2242`


| 学院新闻 | 学生工作 | 通知公告 | 教务通知 | 科研动态 | 招生就业 |
| -------- | -------- | -------- | -------- | -------- | -------- |
| **2242** | 2237     | 2245     | 2246     | 2243     | 2244     |

### 南信大本科教学信息网

作者: [@gylidian](https://github.com/gylidian)

举例: https://rsshub.app/nuist/jwc/1

路由: `/universities/nuist/jwc/:category?`

参数:

- category, 可选 - 默认为 `1`


| 通知公告 | 教学新闻 | 规章制度 | 教学研究 | 教务管理 | 考试中心 |
| -------- | -------- | -------- | -------- | -------- | -------- |
| **1**    | 2        | 4        | 5        | 6        | 7        |

| 教材建设 | 实践教学 | 三百工程 | 创新创业 | 规章制度 | 业务办理 |
| -------- | -------- | -------- | -------- | -------- | -------- |
| 8        | 9        | 56       | 60       | 62       | 43       |

### 南信大研究生院学科建设处

作者: [@gylidian](https://github.com/gylidian)

举例: https://rsshub.app/nuist/yjs/11

路由: `/universities/nuist/yjs/:category?`

参数:

- category, 可选 - 默认为 `11`


| 招生工作 | 培养工作 | 学位工作 | 学生工作 | 就业工作 | 国际合作 | 文件下载 | 工作动态 | 通知公告 |
| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| 3        | 4        | 5        | 6        | 7        | 8        | 9        | 10       | **11**   |

### 南信大学生工作处

作者: [@gylidian](https://github.com/gylidian)

举例: https://rsshub.app/nuist/xgc

路由: `/universities/nuist/xgc`

参数: 无

### NUIST ESE（南信大环科院）

作者: [@gylidian](https://github.com/gylidian)

举例: https://rsshub.app/nuist/sese/11

路由: `/universities/nuist/sese/:category?`

参数:

- category, 可选 - 默认为 `11`


| 通知公告 | 新闻快讯 | 学术动态 | 学生工作 | 研究生教育 | 本科教育 |
| -------- | -------- | -------- | -------- | ---------- | -------- |
| **11**   | 10       | 12       | 6        | 4          | 3        |

### NUIST AS（南信大大气科学学院）

作者: [@gylidian](https://github.com/gylidian)

举例: https://rsshub.app/nuist/cas/12

路由: `/universities/nuist/cas/:category?`

参数:

- category, 可选 - 默认为 `12`


| 信息公告 | 新闻快讯 | 科学研究 | 网上公示 | 本科教育 | 研究生教育 |
| -------- | -------- | -------- | -------- | -------- | ---------- |
| **12**   | 11       | 3        | 110      | 4        | 5          |

### 南京信息工程大学图书馆

作者: [@gylidian](https://github.com/gylidian)

举例: https://rsshub.app/nuist/lib

路由: `/universities/nuist/library/lib`

参数: 无

> :cake: **提示**
>
> 学校图书馆官网提供了[新书通报](http://lib2.nuist.edu.cn/newbook/newbook_cls_browse.php)的订阅
>
> 由于图书馆通知频率过低(故只提供 3 条)，有待将其和 **网络信息中心**、**基建处**、**总务处** 等的通知整合起来