<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><p align="center" dir="auto">
  <a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/147384d5c3d2bab49bb6924b7008267ef93613631cb4270f77cb8b28819e9dff/687474703a2f2f692e696d6775722e636f6d2f6f65506e484a6e2e6a7067"><img src="https://camo.githubusercontent.com/147384d5c3d2bab49bb6924b7008267ef93613631cb4270f77cb8b28819e9dff/687474703a2f2f692e696d6775722e636f6d2f6f65506e484a6e2e6a7067" alt="扎帕摇滚！" data-canonical-src="http://i.imgur.com/oePnHJn.jpg" style="max-width: 100%;"></a>
</p>
<h2 tabindex="-1" dir="auto"><a id="user-content-zappa---serverless-python" class="anchor" aria-hidden="true" tabindex="-1" href="#zappa---serverless-python"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Zappa - 无服务器 Python</font></font></h2>
<p dir="auto"><a href="https://github.com/zappa/Zappa/actions/workflows/ci.yaml"><img src="https://github.com/zappa/Zappa/actions/workflows/ci.yaml/badge.svg?branch=master&amp;event=push" alt="CI" style="max-width: 100%;"></a>
<a href="https://coveralls.io/github/zappa/Zappa" rel="nofollow"><img src="https://camo.githubusercontent.com/6cfeaf11ebb95f1ea305b9c615a038199502226fc86316860a72fff8376e77c0/68747470733a2f2f696d672e736869656c64732e696f2f636f766572616c6c732f7a617070612f5a617070612e737667" alt="覆盖范围" data-canonical-src="https://img.shields.io/coveralls/zappa/Zappa.svg" style="max-width: 100%;"></a>
<a href="https://pypi.python.org/pypi/zappa" rel="nofollow"><img src="https://camo.githubusercontent.com/05550f1936e515b7a17a9f0b1c97bf0dd9c1bb17baf472a8330056c40e2a7451/68747470733a2f2f696d672e736869656c64732e696f2f707970692f762f5a617070612e737667" alt="皮伊" data-canonical-src="https://img.shields.io/pypi/v/Zappa.svg" style="max-width: 100%;"></a>
<a href="https://zappateam.slack.com/" rel="nofollow"><img src="https://camo.githubusercontent.com/3657c7983e4fdc7b72570541fd74f98e19d642a75208188b12bced614e25dd7f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f636861742d736c61636b2d6666363962342e737667" alt="松弛" data-canonical-src="https://img.shields.io/badge/chat-slack-ff69b4.svg" style="max-width: 100%;"></a></p>


<ul dir="auto">
<li><a href="#about"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">关于</font></font></a></li>
<li><a href="#installation-and-configuration"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装与配置</font></font></a>
<ul dir="auto">
<li><a href="#running-the-initial-setup--settings"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行初始设置/设置</font></font></a></li>
</ul>
</li>
<li><a href="#basic-usage"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基本用法</font></font></a>
<ul dir="auto">
<li><a href="#initial-deployments"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">初始部署</font></font></a></li>
<li><a href="#updates"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">更新</font></font></a>
<ul dir="auto">
<li><a href="#docker-workflows"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Docker 工作流程</font></font></a></li>
</ul>
</li>
<li><a href="#rollback"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">回滚</font></font></a></li>
<li><a href="#scheduling"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">调度</font></font></a>
<ul dir="auto">
<li><a href="#advanced-scheduling"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">高级调度</font></font></a>
<ul dir="auto">
<li><a href="#multiple-expressions"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">多重表达</font></font></a></li>
<li><a href="#disabled-event"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">残疾人活动</font></font></a></li>
</ul>
</li>
</ul>
</li>
<li><a href="#undeploy"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">取消部署</font></font></a></li>
<li><a href="#package"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">包裹</font></font></a>
<ul dir="auto">
<li><a href="#how-zappa-makes-packages"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Zappa 如何制作包装</font></font></a></li>
</ul>
</li>
<li><a href="#template"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模板</font></font></a></li>
<li><a href="#status"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">地位</font></font></a></li>
<li><a href="#tailing-logs"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">尾矿原木</font></font></a></li>
<li><a href="#remote-function-invocation"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">远程函数调用</font></font></a></li>
<li><a href="#django-management-commands"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Django 管理命令</font></font></a></li>
<li><a href="#ssl-certification"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SSL认证</font></font></a>
<ul dir="auto">
<li><a href="#deploying-to-a-domain-with-aws-certificate-manager"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 AWS Certificate Manager 部署到域</font></font></a></li>
<li><a href="#deploying-to-a-domain-with-a-lets-encrypt-certificate-dns-auth"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Let's Encrypt 证书部署到域（DNS 身份验证）</font></font></a></li>
<li><a href="#deploying-to-a-domain-with-a-lets-encrypt-certificate-http-auth"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Let's Encrypt 证书部署到域（HTTP 身份验证）</font></font></a></li>
<li><a href="#deploying-to-a-domain-with-your-own-ssl-certs"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用您自己的 SSL 证书部署到域</font></font></a></li>
</ul>
</li>
</ul>
</li>
<li><a href="#executing-in-response-to-aws-events"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">响应 AWS 事件而执行</font></font></a></li>
<li><a href="#asynchronous-task-execution"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">异步任务执行</font></font></a>
<ul dir="auto">
<li><a href="#catching-exceptions"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">捕获异常</font></font></a></li>
<li><a href="#task-sources"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">任务来源</font></font></a></li>
<li><a href="#direct-invocation"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">直接调用</font></font></a></li>
<li><a href="#remote-invocations"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">远程调用</font></font></a></li>
<li><a href="#restrictions"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">限制</font></font></a></li>
<li><a href="#running-tasks-in-a-vpc"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在VPC中运行任务</font></font></a></li>
<li><a href="#responses"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">回应</font></font></a></li>
</ul>
</li>
<li><a href="#advanced-settings"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">高级设置</font></font></a>
<ul dir="auto">
<li><a href="#yaml-settings"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">YAML 设置</font></font></a></li>
</ul>
</li>
<li><a href="#advanced-usage"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">高级用法</font></font></a>
<ul dir="auto">
<li><a href="#keeping-the-server-warm"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">保持服务器温暖</font></font></a>
<ul dir="auto">
<li><a href="#serving-static-files--binary-uploads"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提供静态文件/二进制上传服务</font></font></a></li>
</ul>
</li>
<li><a href="#enabling-cors"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">启用 CORS</font></font></a></li>
<li><a href="#large-projects"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">大型项目</font></font></a></li>
<li><a href="#enabling-bash-completion"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">启用 Bash 完成</font></font></a></li>
<li><a href="#enabling-secure-endpoints-on-api-gateway"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 API Gateway 上启用安全端点</font></font></a>
<ul dir="auto">
<li><a href="#api-key"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">API密钥</font></font></a></li>
<li><a href="#iam-policy"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">身份管理政策</font></font></a></li>
<li><a href="#api-gateway-lambda-authorizers"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">API 网关 Lambda 授权者</font></font></a></li>
<li><a href="#cognito-user-pool-authorizer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Cognito 用户池授权者</font></font></a></li>
<li><a href="#api-gateway-resource-policy"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">API网关资源策略</font></font></a></li>
</ul>
</li>
<li><a href="#setting-environment-variables"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置环境变量</font></font></a>
<ul dir="auto">
<li><a href="#local-environment-variables"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本地环境变量</font></font></a></li>
<li><a href="#remote-aws-environment-variables"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">远程AWS环境变量</font></font></a></li>
<li><a href="#remote-environment-variables"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">远程环境变量</font></font></a></li>
<li><a href="#remote-environment-variables-via-an-s3-file"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">远程环境变量（通过 S3 文件）</font></font></a></li>
</ul>
</li>
<li><a href="#api-gateway-context-variables"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">API网关上下文变量</font></font></a></li>
<li><a href="#catching-unhandled-exceptions"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">捕获未处理的异常</font></font></a></li>
<li><a href="#using-custom-aws-iam-roles-and-policies"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用自定义 AWS IAM 角色和策略</font></font></a>
<ul dir="auto">
<li><a href="#custom-aws-iam-roles-and-policies-for-deployment"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于部署的自定义 AWS IAM 角色和策略</font></font></a></li>
<li><a href="#custom-aws-iam-roles-and-policies-for-execution"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于执行的自定义 AWS IAM 角色和策略</font></font></a></li>
</ul>
</li>
<li><a href="#aws-x-ray"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AWS X射线</font></font></a></li>
<li><a href="#globally-available-server-less-architectures"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">全球可用的无服务器架构</font></font></a></li>
<li><a href="#raising-aws-service-limits"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提高 AWS 服务限制</font></font></a></li>
<li><a href="#dead-letter-queues"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">死信队列</font></font></a></li>
<li><a href="#unique-package-id"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">唯一的包裹ID</font></font></a></li>
<li><a href="#application-load-balancer-event-source"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">应用程序负载均衡器事件源</font></font></a></li>
<li><a href="#endpoint-configuration"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">端点配置</font></font></a>
<ul dir="auto">
<li><a href="#example-private-api-gateway-configuration"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">私有 API 网关配置示例</font></font></a></li>
</ul>
</li>
<li><a href="#cold-starts-experimental"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">冷启动（实验性）</font></font></a></li>
</ul>
</li>
<li><a href="#zappa-guides"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">扎帕指南</font></font></a></li>
<li><a href="#zappa-in-the-press"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">扎帕在媒体上</font></font></a></li>
<li><a href="#sites-using-zappa"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Zappa 的网站</font></font></a></li>
<li><a href="#related-projects"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">相关项目</font></font></a></li>
<li><a href="#hacks"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">黑客</font></font></a></li>
<li><a href="#contributing"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献</font></font></a>
<ul dir="auto">
<li><a href="#using-a-local-repo"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用本地存储库</font></font></a></li>
</ul>
</li>
</ul>

<h2 tabindex="-1" dir="auto"><a id="user-content-about" class="anchor" aria-hidden="true" tabindex="-1" href="#about"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">关于</font></font></h2>
<p align="center" dir="auto">
  <a href="https://htmlpreview.github.io/?https://raw.githubusercontent.com/Miserlou/Talks/master/serverless-sf/big.quickstart.html" rel="nofollow"><img src="https://camo.githubusercontent.com/34bd6b28fd7f47efed1d08af695abc0002dd77e1e92e9d61309c286fb16173e8/687474703a2f2f692e696d6775722e636f6d2f6332336b444e542e706e673f31" alt="Zappa 拖鞋" data-canonical-src="http://i.imgur.com/c23kDNT.png?1" style="max-width: 100%;"></a>
</p>
<p align="center" dir="auto">
  <i><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">匆忙？</font><font style="vertical-align: inherit;">单击查看</font></font><a href="https://htmlpreview.github.io/?https://raw.githubusercontent.com/Miserlou/Talks/master/serverless-sf/big.quickstart.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（现在有点过时）来自 Serverless SF 的幻灯片</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">！</font></font></i>
</p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Zappa</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使得在 AWS Lambda + API Gateway 上构建和部署无服务器、事件驱动的 Python 应用程序（包括但不限于 WSGI Web 应用程序）变得非常容易。</font><font style="vertical-align: inherit;">将其视为 Python 应用程序的“无服务器”网络托管。</font><font style="vertical-align: inherit;">这意味着</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">无限扩展</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">零停机</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">零维护</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">- 并且成本仅为当前部署的一小部分！</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您有一个 Python Web 应用程序（包括 Django 和 Flask 应用程序），则非常简单：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ pip install zappa
$ zappa init
$ zappa deploy
</code></pre><div class="zeroclipboard-container">
   
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">现在您无需服务器了！</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">哇！</font></font></em></p>
<blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">“无服务器”是什么意思？</font></font></p>
</blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">好吧，所以仍然有一个服务器 - 但它只有</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">40 毫秒的</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">生命周期！</font><font style="vertical-align: inherit;">在这种情况下，无服务器意味着</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">“没有任何永久性基础设施”。</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于传统的 HTTP 服务器，服务器全天候 (24/7) 在线，一一处理传入的请求。如果传入请求的队列变得太大，某些请求将超时。</font><font style="vertical-align: inherit;">借助 Zappa， Amazon API Gateway 为</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">每个请求提供了自己的虚拟 HTTP“服务器”</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">AWS 自动处理水平扩展，因此任何请求都不会超时。</font><font style="vertical-align: inherit;">然后，每个请求都会从 AWS Lambda 中的内存缓存调用您的应用程序，并通过 Python 的 WSGI 接口返回响应。</font><font style="vertical-align: inherit;">当你的应用程序返回后，“服务器”就死掉了。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">更好的是，使用 Zappa，您只需为您使用的服务器时间的毫秒数付费，因此它</font><font style="vertical-align: inherit;">比 Linode 或 Heroku 等 VPS/PaaS 主机</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">便宜很多数量级- 而且在大多数情况下，它是完全免费的。</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">另外，无需担心负载平衡或保持服务器再次在线。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">它非常适合使用 Flask 和 Bottle 等框架部署无服务器微服务，以及使用 Django 托管更大的 Web 应用程序和 CMS。</font><font style="vertical-align: inherit;">或者，您可以使用任何您喜欢的 WSGI 兼容应用程序！</font><font style="vertical-align: inherit;">您</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可能不需要更改现有的应用程序</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">即可使用它，并且您不会被限制使用它。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Zappa 还允许您构建混合事件驱动的应用程序，</font><font style="vertical-align: inherit;">每年可以扩展到</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数万亿个事件</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，而无需您付出</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">额外的努力！</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您还可以获得</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">免费的 SSL 证书</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">全局应用程序部署</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">API 访问管理</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自动安全策略生成</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">预编译 C 扩展</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自动保温</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">超大 Lambda 包</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以及</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">许多其他独家功能</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">！</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">最后，Zappa</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">非常易于使用</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">您可以使用开箱即用的单个命令来部署您的应用程序！</font></font></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">惊人的！</font></font></strong></p>
<p align="center" dir="auto">
  <animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/c0ccd9fc4460f20963a999c052c05a0d8b3f7d7e7585dd8e60611b3c7ae47e0d/687474703a2f2f692e696d6775722e636f6d2f6631504a7843512e676966" data-target="animated-image.originalLink"><img src="https://camo.githubusercontent.com/c0ccd9fc4460f20963a999c052c05a0d8b3f7d7e7585dd8e60611b3c7ae47e0d/687474703a2f2f692e696d6775722e636f6d2f6631504a7843512e676966" alt="Zappa 演示 Gif" data-canonical-src="http://i.imgur.com/f1PJxCQ.gif" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://camo.githubusercontent.com/c0ccd9fc4460f20963a999c052c05a0d8b3f7d7e7585dd8e60611b3c7ae47e0d/687474703a2f2f692e696d6775722e636f6d2f6631504a7843512e676966" target="_blank">
          
      
</p>
<h2 tabindex="-1" dir="auto"><a id="user-content-installation-and-configuration" class="anchor" aria-hidden="true" tabindex="-1" href="#installation-and-configuration"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装与配置</font></font></h2>
<p dir="auto"><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在开始之前，请确保您运行的是 Python 3.8/3.9/3.10/3.11/3.12，并且拥有有效的 AWS 账户并且</font></font><a href="https://blogs.aws.amazon.com/security/post/Tx3D6U6WSFGOK2H/A-New-and-Standardized-Way-to-Manage-Credentials-in-the-AWS-SDKs" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AWS 凭证文件</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">已正确安装。</font></font></em></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Zappa</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可以通过 pip 轻松安装，如下所示：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ pip install zappa
</code></pre><div class="zeroclipboard-container">
   
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请注意，Zappa</font></font><em><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必须</font></font></strong></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装到您项目的</font></font><a href="http://docs.python-guide.org/en/latest/dev/virtualenvs/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">虚拟环境</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中。</font><font style="vertical-align: inherit;">虚拟环境名称不应与 Zappa 项目名称相同，否则可能会导致错误。</font></font></p>
<p dir="auto"><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（如果您使用</font></font><a href="https://github.com/yyuu/pyenv"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">pyenv并且喜欢使用</font></font></a><font style="vertical-align: inherit;"></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">pyenv-virtualenv</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">管理 virtualenv </font><font style="vertical-align: inherit;">，您只需调用</font></font><code>pyenv local [your_venv_name]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">它就可以了。Conda</font></font><a href="http://conda.pydata.org/docs/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用户</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">应该</font></font><a href="https://github.com/Miserlou/Zappa/pull/108" data-hovercard-type="pull_request" data-hovercard-url="/Miserlou/Zappa/pull/108/hovercard"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在此处</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">发表评论。）</font></font></em></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">接下来，您需要定义本地和服务器端设置。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-running-the-initial-setup--settings" class="anchor" aria-hidden="true" tabindex="-1" href="#running-the-initial-setup--settings"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行初始设置/设置</font></font></h3>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Zappa</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可以使用以下命令自动为您设置部署设置</font></font><code>init</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ zappa init
</code></pre><div class="zeroclipboard-container">
   
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这将自动检测您的应用程序类型（Flask/Django - Pyramid 用户</font></font><a href="https://github.com/Miserlou/Zappa/issues/278#issuecomment-241917956" data-hovercard-type="issue" data-hovercard-url="/Miserlou/Zappa/issues/278/hovercard"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅此处</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）并帮助您定义部署配置设置。</font><font style="vertical-align: inherit;">完成初始化后，您的项目目录中将有一个名为</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">zappa_settings.json</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的文件，用于定义基本部署设置。</font><font style="vertical-align: inherit;">对于大多数 WSGI 应用程序来说，它可能看起来像这样：</font></font></p>
<div class="highlight highlight-source-js notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-kos">{</span>
    <span class="pl-c">// The name of your stage</span>
    <span class="pl-s">"dev"</span>: <span class="pl-kos">{</span>
        <span class="pl-c">// The name of your S3 bucket</span>
        <span class="pl-s">"s3_bucket"</span>: <span class="pl-s">"lambda"</span><span class="pl-kos">,</span>

        <span class="pl-c">// The modular python path to your WSGI application function.</span>
        <span class="pl-c">// In Flask and Bottle, this is your 'app' object.</span>
        <span class="pl-c">// Flask (your_module.py):</span>
        <span class="pl-c">// app = Flask()</span>
        <span class="pl-c">// Bottle (your_module.py):</span>
        <span class="pl-c">// app = bottle.default_app()</span>
        <span class="pl-s">"app_function"</span>: <span class="pl-s">"your_module.app"</span>
    <span class="pl-kos">}</span>
<span class="pl-kos">}</span></pre><div class="zeroclipboard-container">
 
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或者对于姜戈：</font></font></p>
<div class="highlight highlight-source-js notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-kos">{</span>
    <span class="pl-s">"dev"</span>: <span class="pl-kos">{</span> <span class="pl-c">// The name of your stage</span>
       <span class="pl-s">"s3_bucket"</span>: <span class="pl-s">"lambda"</span><span class="pl-kos">,</span> <span class="pl-c">// The name of your S3 bucket</span>
       <span class="pl-s">"django_settings"</span>: <span class="pl-s">"your_project.settings"</span> <span class="pl-c">// The python path to your Django settings.</span>
    <span class="pl-kos">}</span>
<span class="pl-kos">}</span></pre><div class="zeroclipboard-container">
    
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注：如果您是第一次使用 Zappa 部署 Django 应用程序，您可能需要阅读 Edgar Roman 的</font></font><a href="https://edgarroman.github.io/zappa-django-guide/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Django Zappa 指南</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></em></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以根据需要定义任意多个阶段 - 我们建议有</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开发</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">登台</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">生产阶段</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">现在，您已准备好部署！</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-basic-usage" class="anchor" aria-hidden="true" tabindex="-1" href="#basic-usage"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基本用法</font></font></h2>
<h3 tabindex="-1" dir="auto"><a id="user-content-initial-deployments" class="anchor" aria-hidden="true" tabindex="-1" href="#initial-deployments"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">初始部署</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置完设置后，您可以使用单个命令打包应用程序并将其部署到名为“生产”的阶段：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ zappa deploy production
Deploying..
Your application is now live at: https://7k6anj0k99.execute-api.us-east-1.amazonaws.com/production
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ zappa deploy production
Deploying..
Your application is now live at: https://7k6anj0k99.execute-api.us-east-1.amazonaws.com/production" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">现在您的应用程序已</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上线！</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">多么酷啊？！</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为了解释发生了什么，当您调用 时</font></font><code>deploy</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，Zappa 会自动将您的应用程序和本地虚拟环境打包到 Lambda 兼容的存档中，将任何依赖项替换为与 lambda 兼容的轮子版本，设置函数处理程序和必要的 WSGI 中间件，上传将存档保存到 S3，创建和管理必要的 Amazon IAM 策略和角色，将其注册为新的 Lambda 函数，创建新的 API 网关资源，为其创建 WSGI 兼容的路由，将其链接到新的 Lambda 函数，最后删除S3 存储桶中的存档。</font><font style="vertical-align: inherit;">便利！</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请注意，为执行 Lambda 创建的默认 IAM 角色和策略应用一组自由的权限。</font><font style="vertical-align: inherit;">这些很可能不适合重要应用程序的生产部署。</font><font style="vertical-align: inherit;">有关更多详细信息，请参阅</font></font><a href="#custom-aws-iam-roles-and-policies-for-execution"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于执行的自定义 AWS IAM 角色和策略</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">部分
。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-updates" class="anchor" aria-hidden="true" tabindex="-1" href="#updates"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">更新</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您的应用程序已经部署，您只需要上传新的Python代码，而不需要触及底层路由，您可以简单地：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ zappa update production
Updating..
Your application is now live at: https://7k6anj0k99.execute-api.us-east-1.amazonaws.com/production
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ zappa update production
Updating..
Your application is now live at: https://7k6anj0k99.execute-api.us-east-1.amazonaws.com/production" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这会创建一个新存档，将其上传到 S3 并更新 Lambda 函数以使用新代码，但不会触及 API 网关路由。</font></font></p>
<h4 tabindex="-1" dir="auto"><a id="user-content-docker-workflows" class="anchor" aria-hidden="true" tabindex="-1" href="#docker-workflows"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Docker 工作流程</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><a href="https://github.com/zappa/Zappa/blob/master/CHANGELOG.md"><font style="vertical-align: inherit;">在0.53.0版本</font></a><font style="vertical-align: inherit;">中</font></font><a href="https://github.com/zappa/Zappa/blob/master/CHANGELOG.md"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中，添加了使用 Docker 部署和更新 Lambda 函数的支持。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"></font><code>--docker-image-uri</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以使用zappa 命令的选项来</font></font><code>deploy</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指定</font><font style="vertical-align: inherit;">ECR 映像</font></font><code>update</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">Zappa 期望构建镜像并将其推送到 Amazon ECR 存储库。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">部署示例：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ zappa deploy --docker-image-uri {AWS ACCOUNT ID}.dkr.ecr.{REGION}.amazonaws.com/{REPOSITORY NAME}:latest
</code></pre><div class="zeroclipboard-container">
   
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">更新示例：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ zappa update --docker-image-uri {AWS ACCOUNT ID}.dkr.ecr.{REGION}.amazonaws.com/{REPOSITORY NAME}:latest
</code></pre><div class="zeroclipboard-container">
    
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">参考</font></font><a href="https://ianwhitestone.work/zappa-serverless-docker/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">博文</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">了解有关如何利用此功能以及何时需要的更多详细信息。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您为 Lambda 运行时使用自定义 Docker 映像（例如，如果您想要使用 Lambda 开箱即用尚不支持的较新版本的 Python）并且您想绕过 Python 版本检查，则可以设置一个环境变量来执行此操作：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ export ZAPPA_RUNNING_IN_DOCKER=True
</code></pre><div class="zeroclipboard-container">
    
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您还可以将其添加到您的 Dockerfile 中，如下所示：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>ENV ZAPPA_RUNNING_IN_DOCKER=True
</code></pre><div class="zeroclipboard-container">
    
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-rollback" class="anchor" aria-hidden="true" tabindex="-1" href="#rollback"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">回滚</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您还可以</font></font><code>rollback</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过提供要返回的修订数量来将部署的代码恢复到先前版本。</font><font style="vertical-align: inherit;">例如，要回滚到 3 个版本之前部署的版本：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ zappa rollback production -n 3
</code></pre><div class="zeroclipboard-container">
   
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-scheduling" class="anchor" aria-hidden="true" tabindex="-1" href="#scheduling"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">调度</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Zappa 可用于轻松安排定期发生的功能。</font><font style="vertical-align: inherit;">这提供了比 Celery 更好、免维护的替代品！</font><font style="vertical-align: inherit;">这些函数将与您一起打包和部署，</font></font><code>app_function</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">并自动从处理程序中调用。</font><font style="vertical-align: inherit;">只需在</font><em><font style="vertical-align: inherit;">zappa_settings.json</font></em><font style="vertical-align: inherit;">文件中列出您的函数和表达式，以使用</font></font><a href="http://docs.aws.amazon.com/lambda/latest/dg/tutorial-scheduled-events-schedule-expressions.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">cron 或rate 语法</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来安排它们：</font></font><em><font style="vertical-align: inherit;"></font></em><font style="vertical-align: inherit;"></font></p>
<div class="highlight highlight-source-js notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-kos">{</span>
    <span class="pl-s">"production"</span>: <span class="pl-kos">{</span>
       ...
       <span class="pl-s">"events"</span>: <span class="pl-kos">[</span><span class="pl-kos">{</span>
           <span class="pl-s">"function"</span>: <span class="pl-s">"your_module.your_function"</span><span class="pl-kos">,</span> <span class="pl-c">// The function to execute</span>
           <span class="pl-s">"expression"</span>: <span class="pl-s">"rate(1 minute)"</span> <span class="pl-c">// When to execute it (in cron or rate format)</span>
       <span class="pl-kos">}</span><span class="pl-kos">]</span><span class="pl-kos">,</span>
       ...
    <span class="pl-kos">}</span>
<span class="pl-kos">}</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="{
    &quot;production&quot;: {
       ...
       &quot;events&quot;: [{
           &quot;function&quot;: &quot;your_module.your_function&quot;, // The function to execute
           &quot;expression&quot;: &quot;rate(1 minute)&quot; // When to execute it (in cron or rate format)
       }],
       ...
    }
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">进而：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ zappa schedule production
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ zappa schedule production" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">现在你的函数将每分钟执行一次！</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果你想取消这些，你可以简单地使用</font></font><code>unschedule</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">命令：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ zappa unschedule production
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ zappa unschedule production" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">现在您的预定活动规则已被删除。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="/zappa/Zappa/blob/master/example"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">示例</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">了解更多详细信息。</font></font></p>
<h4 tabindex="-1" dir="auto"><a id="user-content-advanced-scheduling" class="anchor" aria-hidden="true" tabindex="-1" href="#advanced-scheduling"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">高级调度</font></font></h4>
<h5 tabindex="-1" dir="auto"><a id="user-content-multiple-expressions" class="anchor" aria-hidden="true" tabindex="-1" href="#multiple-expressions"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">多重表达</font></font></h5>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有时，一个函数需要多个表达式来描述其调度。</font><font style="vertical-align: inherit;">要设置多个表达式，只需在</font><em><font style="vertical-align: inherit;">zappa_settings.json文件中列出您的函数以及使用</font></em></font><a href="http://docs.aws.amazon.com/lambda/latest/dg/tutorial-scheduled-events-schedule-expressions.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">cron 或rate 语法</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来调度它们的表达式列表</font><font style="vertical-align: inherit;">：</font></font><em><font style="vertical-align: inherit;"></font></em><font style="vertical-align: inherit;"></font></p>
<div class="highlight highlight-source-js notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-kos">{</span>
    <span class="pl-s">"production"</span>: <span class="pl-kos">{</span>
       ...
       <span class="pl-s">"events"</span>: <span class="pl-kos">[</span><span class="pl-kos">{</span>
           <span class="pl-s">"function"</span>: <span class="pl-s">"your_module.your_function"</span><span class="pl-kos">,</span> <span class="pl-c">// The function to execute</span>
           <span class="pl-s">"expressions"</span>: <span class="pl-kos">[</span><span class="pl-s">"cron(0 20-23 ? * SUN-THU *)"</span><span class="pl-kos">,</span> <span class="pl-s">"cron(0 0-8 ? * MON-FRI *)"</span><span class="pl-kos">]</span> <span class="pl-c">// When to execute it (in cron or rate format)</span>
       <span class="pl-kos">}</span><span class="pl-kos">]</span><span class="pl-kos">,</span>
       ...
    <span class="pl-kos">}</span>
<span class="pl-kos">}</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="{
    &quot;production&quot;: {
       ...
       &quot;events&quot;: [{
           &quot;function&quot;: &quot;your_module.your_function&quot;, // The function to execute
           &quot;expressions&quot;: [&quot;cron(0 20-23 ? * SUN-THU *)&quot;, &quot;cron(0 0-8 ? * MON-FRI *)&quot;] // When to execute it (in cron or rate format)
       }],
       ...
    }
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这可用于处理因 UTC 时区在您当地时区的工作时间内跨越午夜而引起的问题。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">应该注意的是，重叠表达式不会引发警告，并且应该进行检查，以防止重复触发函数。</font></font></p>
<h5 tabindex="-1" dir="auto"><a id="user-content-disabled-event" class="anchor" aria-hidden="true" tabindex="-1" href="#disabled-event"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">残疾人活动</font></font></h5>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有时应该安排某个事件，但将其禁用。</font><font style="vertical-align: inherit;">例如，也许一个事件应该只在生产环境中运行，而不是在沙箱中运行。</font><font style="vertical-align: inherit;">您可能仍希望将其部署到沙箱，以确保在部署到生产之前您的表达式没有问题。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在这种情况下，您可以通过在事件定义中设置</font></font><code>enabled</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为</font><font style="vertical-align: inherit;">来禁用它运行：</font></font><code>false</code><font style="vertical-align: inherit;"></font></p>
<div class="highlight highlight-source-js notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-kos">{</span>
    <span class="pl-s">"sandbox"</span>: <span class="pl-kos">{</span>
       ...
       <span class="pl-s">"events"</span>: <span class="pl-kos">[</span><span class="pl-kos">{</span>
           <span class="pl-s">"function"</span>: <span class="pl-s">"your_module.your_function"</span><span class="pl-kos">,</span> <span class="pl-c">// The function to execute</span>
           <span class="pl-s">"expression"</span>: <span class="pl-s">"rate(1 minute)"</span><span class="pl-kos">,</span> <span class="pl-c">// When to execute it (in cron or rate format)</span>
           <span class="pl-s">"enabled"</span>: <span class="pl-c1">false</span>
       <span class="pl-kos">}</span><span class="pl-kos">]</span><span class="pl-kos">,</span>
       ...
    <span class="pl-kos">}</span>
<span class="pl-kos">}</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="{
    &quot;sandbox&quot;: {
       ...
       &quot;events&quot;: [{
           &quot;function&quot;: &quot;your_module.your_function&quot;, // The function to execute
           &quot;expression&quot;: &quot;rate(1 minute)&quot;, // When to execute it (in cron or rate format)
           &quot;enabled&quot;: false
       }],
       ...
    }
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-undeploy" class="anchor" aria-hidden="true" tabindex="-1" href="#undeploy"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">取消部署</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您需要删除之前发布的 API Gateway 和 Lambda 函数，您可以简单地：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ zappa undeploy production
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ zappa undeploy production" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在执行之前，系统会要求您进行确认。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您为 API Gateway 服务启用了 CloudWatch Logs 并且不想保留这些日志，则可以指定参数</font></font><code>--remove-logs</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来清除 API Gateway 和 Lambda 函数的日志：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ zappa undeploy production --remove-logs
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ zappa undeploy production --remove-logs" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-package" class="anchor" aria-hidden="true" tabindex="-1" href="#package"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">包裹</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您想构建应用程序包而不实际将其上传并注册为 Lambda 函数，则可以使用以下</font></font><code>package</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">命令：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ zappa package production
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ zappa package production" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您</font></font><code>zip</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的设置中有回调</font></font><code>callbacks</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，它也会被调用。</font></font></p>
<div class="highlight highlight-source-js notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-kos">{</span>
    <span class="pl-s">"production"</span>: <span class="pl-kos">{</span> <span class="pl-c">// The name of your stage</span>
        <span class="pl-s">"callbacks"</span>: <span class="pl-kos">{</span>
            <span class="pl-s">"zip"</span>: <span class="pl-s">"my_app.zip_callback"</span><span class="pl-c">// After creating the package</span>
        <span class="pl-kos">}</span>
    <span class="pl-kos">}</span>
<span class="pl-kos">}</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="{
    &quot;production&quot;: { // The name of your stage
        &quot;callbacks&quot;: {
            &quot;zip&quot;: &quot;my_app.zip_callback&quot;// After creating the package
        }
    }
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您还可以使用以下命令指定包的输出文件名</font></font><code>-o</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ zappa package production -o my_awesome_package.zip
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ zappa package production -o my_awesome_package.zip" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-how-zappa-makes-packages" class="anchor" aria-hidden="true" tabindex="-1" href="#how-zappa-makes-packages"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Zappa 如何制作包装</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Zappa 会自动将您的活动虚拟环境打包成可在 AWS Lambda 上顺利运行的包。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在此过程中，它将用 AWS Lambda 兼容版本替换任何本地依赖项。</font><font style="vertical-align: inherit;">依赖项包含在此顺序中：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"></font><code>manylinux</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来自本地缓存的</font><font style="vertical-align: inherit;">Lambda 兼容轮子</font></font></li>
<li><font style="vertical-align: inherit;"></font><code>manylinux</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PyPI 的</font><font style="vertical-align: inherit;">Lambda 兼容轮</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来自活动虚拟环境的包</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来自本地项目目录的包</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">它还会跳过某些不必要的文件，并忽略任何 .py 文件（如果 .pyc 文件可用）。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此外，Zappa 还将自动设置正确的执行权限、配置包设置，并创建唯一的、可审核的包清单文件。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要进一步减小最终包文件的大小，您可以：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置</font></font><code>slim_handler</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为</font></font><code>True</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将一个小处理程序上传到 Lambda，并将包的其余部分上传到 S3。</font><font style="vertical-align: inherit;">有关更多详细信息，请参阅</font></font><a href="https://github.com/Miserlou/Zappa/pull/548" data-hovercard-type="pull_request" data-hovercard-url="/Miserlou/Zappa/pull/548/hovercard"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">合并的拉取请求</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://github.com/Miserlou/Zappa/issues/510" data-hovercard-type="issue" data-hovercard-url="/Miserlou/Zappa/issues/510/hovercard"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">原始问题中的讨论</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">另请参阅：</font></font><a href="#large-projects"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">大型项目</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用</font></font><code>exclude</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或</font></font><code>exclude_glob</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置并提供要从存档中排除的模式列表。</font><font style="vertical-align: inherit;">默认情况下，Zappa 将排除 Boto，因为</font></font><a href="http://docs.aws.amazon.com/lambda/latest/dg/current-supported-versions.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">它已经在 Lambda 执行环境中可用</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
</ul>
<h3 tabindex="-1" dir="auto"><a id="user-content-template" class="anchor" aria-hidden="true" tabindex="-1" href="#template"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模板</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">与 类似</font></font><code>package</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，如果您只需要 API Gateway CloudFormation 模板，请使用以下</font></font><code>template</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">命令：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ zappa template production --l your-lambda-arn -r your-role-arn
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ zappa template production --l your-lambda-arn -r your-role-arn" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请注意，在这种情况下，您必须提供自己的 Lambda ARN 和角色 ARN，因为它们可能不是为您创建的。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以使用 直接获取 JSON 输出</font></font><code>--json</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，并使用 指定输出文件</font></font><code>--output</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-status" class="anchor" aria-hidden="true" tabindex="-1" href="#status"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">地位</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您需要查看部署和事件计划的状态，只需使用该</font></font><code>status</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">命令即可。</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ zappa status production
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ zappa status production" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-tailing-logs" class="anchor" aria-hidden="true" tabindex="-1" href="#tailing-logs"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">尾矿原木</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以通过调用管理命令来查看部署的日志</font></font><code>tail</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ zappa tail production
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ zappa tail production" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认情况下，这将显示所有日志项。</font><font style="vertical-align: inherit;">除了 HTTP 和其他事件之外，任何</font></font><code>print</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">已编辑</font></font><code>stdout</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或</font></font><code>stderr</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将显示在日志中的内容。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以使用该参数</font></font><code>--http</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来过滤 HTTP 请求，该请求将采用 Apache 通用日志格式。</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ zappa tail production --http
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ zappa tail production --http" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">同样，您可以执行相反的操作，仅显示非 HTTP 事件和日志消息：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ zappa tail production --non-http
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ zappa tail production --non-http" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您不喜欢默认的日志颜色，可以使用 关闭它们</font></font><code>--no-color</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您还可以使用 限制尾部的长度</font></font><code>--since</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，它接受一个简单的持续时间字符串：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ zappa tail production --since 4h # 4 hours
$ zappa tail production --since 1m # 1 minute
$ zappa tail production --since 1mm # 1 month
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ zappa tail production --since 4h # 4 hours
$ zappa tail production --since 1m # 1 minute
$ zappa tail production --since 1mm # 1 month" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以使用 过滤掉日志的内容</font></font><code>--filter</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，如下所示：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ zappa tail production --http --filter "POST" # Only show POST HTTP requests
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ zappa tail production --http --filter &quot;POST&quot; # Only show POST HTTP requests" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请注意，这使用</font></font><a href="http://docs.aws.amazon.com/AmazonCloudWatch/latest/logs/FilterAndPatternSyntax.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CloudWatch Logs 过滤器语法</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要尾随日志而不跟随（在显示所请求日志的末尾后立即退出），请传递</font></font><code>--disable-keep-open</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ zappa tail production --since 1h --disable-keep-open
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ zappa tail production --since 1h --disable-keep-open" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-remote-function-invocation" class="anchor" aria-hidden="true" tabindex="-1" href="#remote-function-invocation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">远程函数调用</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以随时使用该</font></font><code>invoke</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">命令直接执行应用程序中的任何功能。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例如，假设您在名为“my_app.py”的文件中有一个基本应用程序，并且您想要调用其中名为“my_function”的函数。</font><font style="vertical-align: inherit;">部署应用程序后，您可以随时通过调用以下命令来调用该函数：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ zappa invoke production my_app.my_function
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ zappa invoke production my_app.my_function" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">所做的任何远程打印语句以及函数返回的值都将被打印到本地控制台。</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">漂亮！</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您还可以使用 直接调用可解释的 Python 3.8/3.9/3.10/3.11/3.12 字符串</font></font><code>--raw</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，如下所示：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ zappa invoke production "print(1 + 2 + 3)" --raw
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ zappa invoke production &quot;print(1 + 2 + 3)&quot; --raw" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例如，如果您想</font></font><code>superuser</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 VPC 中运行的 RDS 数据库（例如 Serverless Aurora）上创建第一个数据库，它会派上用场： $ zappa invoke staging "from django.contrib.auth import get_user_model; User = get_user_model(); User .objects.create_superuser('用户名', '电子邮件', '密码')" --raw</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-django-management-commands" class="anchor" aria-hidden="true" tabindex="-1" href="#django-management-commands"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Django 管理命令</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为了方便起见，Zappa 还可以使用该命令调用远程 Django 'manage.py' 命令</font></font><code>manage</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">例如，要执行基本的 Django 状态检查：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ zappa manage production showmigrations admin
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ zappa manage production showmigrations admin" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">显然，这只适用于正确定义设置的 Django 项目。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于有自己的参数的命令，您还可以将命令作为字符串传递，如下所示：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ zappa manage production "shell --version"
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ zappa manage production &quot;shell --version&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">需要用户直接输入的命令（例如</font></font><code>createsuperuser</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）应替换为</font><font style="vertical-align: inherit;">使用 的</font></font><a href="http://stackoverflow.com/a/26091252" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">命令</font></font></a><font style="vertical-align: inherit;"></font><code>zappa invoke &lt;env&gt; --raw</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关 Django 集成的更多信息，请查看</font></font><a href="https://github.com/Miserlou/zappa-django-utils"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">zappa-django-utils</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">项目。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-ssl-certification" class="anchor" aria-hidden="true" tabindex="-1" href="#ssl-certification"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SSL认证</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://aws.amazon.com/certificate-manager/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可以使用自定义 SSL 证书、Let's Encrypt 证书和AWS Certificate Manager</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> (ACM) 证书将 Zappa 部署到自定义域名和子域</font><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目前，其中最容易使用的是 AWS Certificate Manager 证书，因为它们是免费的、自我更新的，并且需要的工作量最少。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如下所述配置后，所有这些方法都使用相同的命令：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ zappa certify
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ zappa certify" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从 CI/CD 系统部署时，您可以使用：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ zappa certify --yes
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ zappa certify --yes" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">跳过确认提示。</font></font></p>
<h4 tabindex="-1" dir="auto"><a id="user-content-deploying-to-a-domain-with-aws-certificate-manager" class="anchor" aria-hidden="true" tabindex="-1" href="#deploying-to-a-domain-with-aws-certificate-manager"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 AWS Certificate Manager 部署到域</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Amazon 提供了自己的 Let's Encrypt 的免费替代方案，称为</font></font><a href="https://aws.amazon.com/certificate-manager/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AWS Certificate Manager</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> (ACM)。</font><font style="vertical-align: inherit;">要通过 Zappa 使用此服务：</font></font></p>
<ol dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 AWS Certificate Manager 控制台中验证您的域。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在控制台中，选择弗吉尼亚北部 (us-east-1) 区域并为您的域或子域请求证书 ( </font></font><code>sub.yourdomain.tld</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">)，或请求通配符域 ( </font></font><code>*.yourdomain.tld</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">)。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">复制该证书的整个 ARN 并将其放置在 Zappa 设置中</font></font><code>certificate_arn</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在设置中设置您想要的域名</font></font><code>domain</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">调用</font></font><code>$ zappa certify</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以使用该证书创建并关联 API Gateway 分配。</font></font></li>
</ol>
<h4 tabindex="-1" dir="auto"><a id="user-content-deploying-to-a-domain-with-a-lets-encrypt-certificate-dns-auth" class="anchor" aria-hidden="true" tabindex="-1" href="#deploying-to-a-domain-with-a-lets-encrypt-certificate-dns-auth"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Let's Encrypt 证书部署到域（DNS 身份验证）</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您想在具有免费 Let's Encrypt 证书并使用基于 Route 53 的 DNS 身份验证的域上使用 Zappa，您可以按照</font></font><a href="https://github.com/zappa/Zappa/blob/master/docs/domain_with_free_ssl_dns.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此便捷指南</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">进行操作。</font></font></p>
<h4 tabindex="-1" dir="auto"><a id="user-content-deploying-to-a-domain-with-a-lets-encrypt-certificate-http-auth" class="anchor" aria-hidden="true" tabindex="-1" href="#deploying-to-a-domain-with-a-lets-encrypt-certificate-http-auth"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Let's Encrypt 证书部署到域（HTTP 身份验证）</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您想在具有使用 HTTP 身份验证的免费 Let's Encrypt 证书的域上使用 Zappa，您可以按照</font></font><a href="https://github.com/zappa/Zappa/blob/master/docs/domain_with_free_ssl_http.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本指南</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">进行操作。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">但是，现在使用基于 Route 53 的 DNS 身份验证要容易得多，这将允许您通过单个命令使用 Let's Encrypt 证书</font></font><code>$ zappa certify</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<h4 tabindex="-1" dir="auto"><a id="user-content-deploying-to-a-domain-with-your-own-ssl-certs" class="anchor" aria-hidden="true" tabindex="-1" href="#deploying-to-a-domain-with-your-own-ssl-certs"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用您自己的 SSL 证书部署到域</font></font></h4>
<ol dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">第一步是创建自定义域并获取您的 SSL 证书/密钥/捆绑包。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">确保您已</font></font><code>domain</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 Zappa 设置 JSON 中设置该设置 - 这将避免自定义域和 API 调用 URL 之间的基本路径映射出现问题，该 URL 会在 URI 中附加阶段名称</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将 SSL 证书/密钥/包的路径</font><font style="vertical-align: inherit;">分别添加到 Zappa 设置 JSON 中的</font></font><code>certificate</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>certificate_key</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和设置</font></font><code>certificate_chain</code><font style="vertical-align: inherit;"></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置</font></font><code>route53_enabled</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">_</font></font><code>false</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您计划使用自己的 DNS 提供商而不是 AWS Route53 托管区域，</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Zappa 部署或更新您的应用程序</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行</font></font><code>$ zappa certify</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以上传您的证书并向您的 API 网关注册自定义域名。</font></font></li>
</ol>
<h2 tabindex="-1" dir="auto"><a id="user-content-executing-in-response-to-aws-events" class="anchor" aria-hidden="true" tabindex="-1" href="#executing-in-response-to-aws-events"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">响应 AWS 事件而执行</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">同样，您可以执行函数来响应 AWS 生态系统中发生的事件，例如 S3 上传、DynamoDB 条目、Kinesis 流、SNS 消息和 SQS 队列。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在您的</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">zappa_settings.json</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件中，定义您的</font></font><a href="http://docs.aws.amazon.com/lambda/latest/dg/invoking-lambda-function.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">事件源</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和您希望执行的函数。</font><font style="vertical-align: inherit;">例如，这将</font></font><code>your_module.process_upload_function</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">响应</font></font><code>my-bucket</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">S3 存储桶中的新对象而执行。</font><font style="vertical-align: inherit;">注意</font></font><code>process_upload_function</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必须接受</font></font><code>event</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><code>context</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">参数。</font></font></p>
<div class="highlight highlight-source-js notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-kos">{</span>
    <span class="pl-s">"production"</span>: <span class="pl-kos">{</span>
       ...
       <span class="pl-s">"events"</span>: <span class="pl-kos">[</span><span class="pl-kos">{</span>
            <span class="pl-s">"function"</span>: <span class="pl-s">"your_module.process_upload_function"</span><span class="pl-kos">,</span>
            <span class="pl-s">"event_source"</span>: <span class="pl-kos">{</span>
                  <span class="pl-s">"arn"</span>:  <span class="pl-s">"arn:aws:s3:::my-bucket"</span><span class="pl-kos">,</span>
                  <span class="pl-s">"events"</span>: <span class="pl-kos">[</span>
                    <span class="pl-s">"s3:ObjectCreated:*"</span> <span class="pl-c">// Supported event types: http://docs.aws.amazon.com/AmazonS3/latest/dev/NotificationHowTo.html#supported-notification-event-types</span>
                  <span class="pl-kos">]</span><span class="pl-kos">,</span>
                  <span class="pl-s">"key_filters"</span>: <span class="pl-kos">[</span><span class="pl-kos">{</span> <span class="pl-c">// optional</span>
                    <span class="pl-s">"type"</span>: <span class="pl-s">"suffix"</span><span class="pl-kos">,</span>
                    <span class="pl-s">"value"</span>: <span class="pl-s">"yourfile.json"</span>
                  <span class="pl-kos">}</span><span class="pl-kos">,</span>
                  <span class="pl-kos">{</span>
                    <span class="pl-s">"type"</span>: <span class="pl-s">"prefix"</span><span class="pl-kos">,</span>
                    <span class="pl-s">"value"</span>: <span class="pl-s">"prefix/for/your/object"</span>
                  <span class="pl-kos">}</span><span class="pl-kos">]</span>
               <span class="pl-kos">}</span>
            <span class="pl-kos">}</span><span class="pl-kos">]</span><span class="pl-kos">,</span>
       ...
    <span class="pl-kos">}</span>
<span class="pl-kos">}</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="{
    &quot;production&quot;: {
       ...
       &quot;events&quot;: [{
            &quot;function&quot;: &quot;your_module.process_upload_function&quot;,
            &quot;event_source&quot;: {
                  &quot;arn&quot;:  &quot;arn:aws:s3:::my-bucket&quot;,
                  &quot;events&quot;: [
                    &quot;s3:ObjectCreated:*&quot; // Supported event types: http://docs.aws.amazon.com/AmazonS3/latest/dev/NotificationHowTo.html#supported-notification-event-types
                  ],
                  &quot;key_filters&quot;: [{ // optional
                    &quot;type&quot;: &quot;suffix&quot;,
                    &quot;value&quot;: &quot;yourfile.json&quot;
                  },
                  {
                    &quot;type&quot;: &quot;prefix&quot;,
                    &quot;value&quot;: &quot;prefix/for/your/object&quot;
                  }]
               }
            }],
       ...
    }
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">进而：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ zappa schedule production
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ zappa schedule production" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">现在，每次新上传的内容出现在您的存储桶中时，您的函数都会执行！</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要访问应用程序上下文中的密钥信息，您需要</font></font><code>process_upload_function</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如下所示：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">import</span> <span class="pl-s1">boto3</span>
<span class="pl-s1">s3_client</span> <span class="pl-c1">=</span> <span class="pl-s1">boto3</span>.<span class="pl-en">client</span>(<span class="pl-s">'s3'</span>)

<span class="pl-k">def</span> <span class="pl-en">process_upload_function</span>(<span class="pl-s1">event</span>, <span class="pl-s1">context</span>):
    <span class="pl-s">"""</span>
<span class="pl-s">    Process a file upload.</span>
<span class="pl-s">    """</span>

    <span class="pl-c"># Get the uploaded file's information</span>
    <span class="pl-s1">bucket</span> <span class="pl-c1">=</span> <span class="pl-s1">event</span>[<span class="pl-s">'Records'</span>][<span class="pl-c1">0</span>][<span class="pl-s">'s3'</span>][<span class="pl-s">'bucket'</span>][<span class="pl-s">'name'</span>] <span class="pl-c"># Will be `my-bucket`</span>
    <span class="pl-s1">key</span> <span class="pl-c1">=</span> <span class="pl-s1">event</span>[<span class="pl-s">'Records'</span>][<span class="pl-c1">0</span>][<span class="pl-s">'s3'</span>][<span class="pl-s">'object'</span>][<span class="pl-s">'key'</span>] <span class="pl-c"># Will be the file path of whatever file was uploaded.</span>

    <span class="pl-c"># Get the bytes from S3</span>
    <span class="pl-s1">s3_client</span>.<span class="pl-en">download_file</span>(<span class="pl-s1">bucket</span>, <span class="pl-s1">key</span>, <span class="pl-s">'/tmp/'</span> <span class="pl-c1">+</span> <span class="pl-s1">key</span>) <span class="pl-c"># Download this file to writable tmp space.</span>
    <span class="pl-s1">file_bytes</span> <span class="pl-c1">=</span> <span class="pl-en">open</span>(<span class="pl-s">'/tmp/'</span> <span class="pl-c1">+</span> <span class="pl-s1">key</span>).<span class="pl-en">read</span>()</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="import boto3
s3_client = boto3.client('s3')

def process_upload_function(event, context):
    &quot;&quot;&quot;
    Process a file upload.
    &quot;&quot;&quot;

    # Get the uploaded file's information
    bucket = event['Records'][0]['s3']['bucket']['name'] # Will be `my-bucket`
    key = event['Records'][0]['s3']['object']['key'] # Will be the file path of whatever file was uploaded.

    # Get the bytes from S3
    s3_client.download_file(bucket, key, '/tmp/' + key) # Download this file to writable tmp space.
    file_bytes = open('/tmp/' + key).read()" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">同样，对于</font></font><a href="https://aws.amazon.com/sns/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">简单通知服务</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">事件：</font></font></p>
<div class="highlight highlight-source-js notranslate position-relative overflow-auto" dir="auto"><pre>        <span class="pl-s">"events"</span>: <span class="pl-kos">[</span>
            <span class="pl-kos">{</span>
                <span class="pl-s">"function"</span>: <span class="pl-s">"your_module.your_function"</span><span class="pl-kos">,</span>
                <span class="pl-s">"event_source"</span>: <span class="pl-kos">{</span>
                    <span class="pl-s">"arn"</span>:  <span class="pl-s">"arn:aws:sns:::your-event-topic-arn"</span><span class="pl-kos">,</span>
                    <span class="pl-s">"events"</span>: <span class="pl-kos">[</span>
                        <span class="pl-s">"sns:Publish"</span>
                    <span class="pl-kos">]</span>
                <span class="pl-kos">}</span>
            <span class="pl-kos">}</span>
        <span class="pl-kos">]</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="        &quot;events&quot;: [
            {
                &quot;function&quot;: &quot;your_module.your_function&quot;,
                &quot;event_source&quot;: {
                    &quot;arn&quot;:  &quot;arn:aws:sns:::your-event-topic-arn&quot;,
                    &quot;events&quot;: [
                        &quot;sns:Publish&quot;
                    ]
                }
            }
        ]" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以选择添加</font></font><a href="http://docs.aws.amazon.com/sns/latest/dg/message-filtering.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SNS 消息过滤器</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<div class="highlight highlight-source-js notranslate position-relative overflow-auto" dir="auto"><pre>        <span class="pl-s">"events"</span>: <span class="pl-kos">[</span>
            <span class="pl-kos">{</span>
                <span class="pl-s">"function"</span>: <span class="pl-s">"your_module.your_function"</span><span class="pl-kos">,</span>
                <span class="pl-s">"event_source"</span>: <span class="pl-kos">{</span>
                    <span class="pl-s">"arn"</span>:  <span class="pl-s">"arn:aws:sns:::your-event-topic-arn"</span><span class="pl-kos">,</span>
                    <span class="pl-s">"filters"</span>: <span class="pl-kos">{</span>
                        <span class="pl-s">"interests"</span>: <span class="pl-kos">[</span><span class="pl-s">"python"</span><span class="pl-kos">,</span> <span class="pl-s">"aws"</span><span class="pl-kos">,</span> <span class="pl-s">"zappa"</span><span class="pl-kos">]</span><span class="pl-kos">,</span>
                        <span class="pl-s">"version"</span>: <span class="pl-kos">[</span><span class="pl-s">"1.0"</span><span class="pl-kos">]</span>
                    <span class="pl-kos">}</span><span class="pl-kos">,</span>
                    ...
                <span class="pl-kos">}</span>
            <span class="pl-kos">}</span>
        <span class="pl-kos">]</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="        &quot;events&quot;: [
            {
                &quot;function&quot;: &quot;your_module.your_function&quot;,
                &quot;event_source&quot;: {
                    &quot;arn&quot;:  &quot;arn:aws:sns:::your-event-topic-arn&quot;,
                    &quot;filters&quot;: {
                        &quot;interests&quot;: [&quot;python&quot;, &quot;aws&quot;, &quot;zappa&quot;],
                        &quot;version&quot;: [&quot;1.0&quot;]
                    },
                    ...
                }
            }
        ]" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><a href="http://docs.aws.amazon.com/lambda/latest/dg/with-ddb.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DynamoDB</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="http://docs.aws.amazon.com/lambda/latest/dg/with-kinesis.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Kinesis</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">略有不同，因为它不是基于事件，而是从流中提取：</font></font></p>
<div class="highlight highlight-source-js notranslate position-relative overflow-auto" dir="auto"><pre>       <span class="pl-s">"events"</span>: <span class="pl-kos">[</span>
           <span class="pl-kos">{</span>
               <span class="pl-s">"function"</span>: <span class="pl-s">"replication.replicate_records"</span><span class="pl-kos">,</span>
               <span class="pl-s">"event_source"</span>: <span class="pl-kos">{</span>
                    <span class="pl-s">"arn"</span>:  <span class="pl-s">"arn:aws:dynamodb:us-east-1:1234554:table/YourTable/stream/2016-05-11T00:00:00.000"</span><span class="pl-kos">,</span>
                    <span class="pl-s">"starting_position"</span>: <span class="pl-s">"TRIM_HORIZON"</span><span class="pl-kos">,</span> <span class="pl-c">// Supported values: TRIM_HORIZON, LATEST</span>
                    <span class="pl-s">"batch_size"</span>: <span class="pl-c1">50</span><span class="pl-kos">,</span> <span class="pl-c">// Max: 1000</span>
                    <span class="pl-s">"enabled"</span>: <span class="pl-c1">true</span> <span class="pl-c">// Default is false</span>
               <span class="pl-kos">}</span>
           <span class="pl-kos">}</span>
       <span class="pl-kos">]</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="       &quot;events&quot;: [
           {
               &quot;function&quot;: &quot;replication.replicate_records&quot;,
               &quot;event_source&quot;: {
                    &quot;arn&quot;:  &quot;arn:aws:dynamodb:us-east-1:1234554:table/YourTable/stream/2016-05-11T00:00:00.000&quot;,
                    &quot;starting_position&quot;: &quot;TRIM_HORIZON&quot;, // Supported values: TRIM_HORIZON, LATEST
                    &quot;batch_size&quot;: 50, // Max: 1000
                    &quot;enabled&quot;: true // Default is false
               }
           }
       ]" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><a href="https://docs.aws.amazon.com/lambda/latest/dg/with-sqs.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SQS</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">还从流中提取消息。</font><font style="vertical-align: inherit;">此时，</font></font><a href="https://docs.aws.amazon.com/lambda/latest/dg/with-sqs.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">只有“Standard”队列可以触发lambda事件，而“FIFO”队列则不能</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">请仔细阅读 AWS 文档，因为一旦您的函数成功完成，Lambda 就会代表您调用 SQS DeleteMessage API。</font></font></p>
<div class="highlight highlight-source-js notranslate position-relative overflow-auto" dir="auto"><pre>       <span class="pl-s">"events"</span>: <span class="pl-kos">[</span>
           <span class="pl-kos">{</span>
               <span class="pl-s">"function"</span>: <span class="pl-s">"your_module.process_messages"</span><span class="pl-kos">,</span>
               <span class="pl-s">"event_source"</span>: <span class="pl-kos">{</span>
                    <span class="pl-s">"arn"</span>:  <span class="pl-s">"arn:aws:sqs:us-east-1:12341234:your-queue-name-arn"</span><span class="pl-kos">,</span>
                    <span class="pl-s">"batch_size"</span>: <span class="pl-c1">10</span><span class="pl-kos">,</span> <span class="pl-c">// Max: 10. Use 1 to trigger immediate processing</span>
                    <span class="pl-s">"enabled"</span>: <span class="pl-c1">true</span> <span class="pl-c">// Default is false</span>
               <span class="pl-kos">}</span>
           <span class="pl-kos">}</span>
       <span class="pl-kos">]</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="       &quot;events&quot;: [
           {
               &quot;function&quot;: &quot;your_module.process_messages&quot;,
               &quot;event_source&quot;: {
                    &quot;arn&quot;:  &quot;arn:aws:sqs:us-east-1:12341234:your-queue-name-arn&quot;,
                    &quot;batch_size&quot;: 10, // Max: 10. Use 1 to trigger immediate processing
                    &quot;enabled&quot;: true // Default is false
               }
           }
       ]" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要配置 Lex Bot 的意图触发事件：</font></font></p>
<div class="highlight highlight-source-js notranslate position-relative overflow-auto" dir="auto"><pre>    <span class="pl-s">"bot_events"</span>: <span class="pl-kos">[</span>
        <span class="pl-kos">{</span>
            <span class="pl-s">"function"</span>: <span class="pl-s">"lexbot.handlers.book_appointment.handler"</span><span class="pl-kos">,</span>
            <span class="pl-s">"event_source"</span>: <span class="pl-kos">{</span>
                <span class="pl-s">"arn"</span>: <span class="pl-s">"arn:aws:lex:us-east-1:01234123123:intent:TestLexEventNames:$LATEST"</span><span class="pl-kos">,</span> <span class="pl-c">// optional. In future it will be used to configure the intent</span>
                <span class="pl-s">"intent"</span>:<span class="pl-s">"intentName"</span><span class="pl-kos">,</span> <span class="pl-c">// name of the bot event configured</span>
                <span class="pl-s">"invocation_source"</span>:<span class="pl-s">"DialogCodeHook"</span><span class="pl-kos">,</span> <span class="pl-c">// either FulfillmentCodeHook or DialogCodeHook</span>
            <span class="pl-kos">}</span>
        <span class="pl-kos">}</span>
    <span class="pl-kos">]</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="    &quot;bot_events&quot;: [
        {
            &quot;function&quot;: &quot;lexbot.handlers.book_appointment.handler&quot;,
            &quot;event_source&quot;: {
                &quot;arn&quot;: &quot;arn:aws:lex:us-east-1:01234123123:intent:TestLexEventNames:$LATEST&quot;, // optional. In future it will be used to configure the intent
                &quot;intent&quot;:&quot;intentName&quot;, // name of the bot event configured
                &quot;invocation_source&quot;:&quot;DialogCodeHook&quot;, // either FulfillmentCodeHook or DialogCodeHook
            }
        }
    ]
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">事件还可以采用关键字参数：</font></font></p>
<div class="highlight highlight-source-js notranslate position-relative overflow-auto" dir="auto"><pre>       <span class="pl-s">"events"</span>: <span class="pl-kos">[</span>
            <span class="pl-kos">{</span>
                <span class="pl-s">"function"</span>: <span class="pl-s">"your_module.your_recurring_function"</span><span class="pl-kos">,</span> <span class="pl-c">// The function to execute</span>
                <span class="pl-s">"kwargs"</span>: <span class="pl-kos">{</span><span class="pl-s">"key"</span>: <span class="pl-s">"val"</span><span class="pl-kos">,</span> <span class="pl-s">"key2"</span>: <span class="pl-s">"val2"</span><span class="pl-kos">}</span><span class="pl-kos">,</span>  <span class="pl-c">// Keyword arguments to pass. These are available in the event</span>
                <span class="pl-s">"expression"</span>: <span class="pl-s">"rate(1 minute)"</span> <span class="pl-c">// When to execute it (in cron or rate format)</span>
            <span class="pl-kos">}</span>
       <span class="pl-kos">]</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="       &quot;events&quot;: [
            {
                &quot;function&quot;: &quot;your_module.your_recurring_function&quot;, // The function to execute
                &quot;kwargs&quot;: {&quot;key&quot;: &quot;val&quot;, &quot;key2&quot;: &quot;val2&quot;},  // Keyword arguments to pass. These are available in the event
                &quot;expression&quot;: &quot;rate(1 minute)&quot; // When to execute it (in cron or rate format)
            }
       ]" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要获取关键字参数，您需要查看事件字典：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">def</span> <span class="pl-en">your_recurring_function</span>(<span class="pl-s1">event</span>, <span class="pl-s1">context</span>):
    <span class="pl-s1">my_kwargs</span> <span class="pl-c1">=</span> <span class="pl-s1">event</span>.<span class="pl-en">get</span>(<span class="pl-s">"kwargs"</span>)  <span class="pl-c"># dict of kwargs given in zappa_settings file</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="def your_recurring_function(event, context):
    my_kwargs = event.get(&quot;kwargs&quot;)  # dict of kwargs given in zappa_settings file
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以在此处找到更多</font></font><a href="http://docs.aws.amazon.com/lambda/latest/dg/eventsources.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">示例事件源</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-asynchronous-task-execution" class="anchor" aria-hidden="true" tabindex="-1" href="#asynchronous-task-execution"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">异步任务执行</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Zappa 现在还提供在完全独立的 AWS Lambda 实例中无缝异步执行函数的能力！</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例如，如果您有一个用于订购馅饼的 Flask API，您可以</font></font><code>bake</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用</font></font><code>zappa.asynchronous.task</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">装饰器在完全独立的 Lambda 实例中无缝调用您的函数，如下所示：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">from</span> <span class="pl-s1">flask</span> <span class="pl-k">import</span> <span class="pl-v">Flask</span>
<span class="pl-k">from</span> <span class="pl-s1">zappa</span>.<span class="pl-s1">asynchronous</span> <span class="pl-k">import</span> <span class="pl-s1">task</span>
<span class="pl-s1">app</span> <span class="pl-c1">=</span> <span class="pl-v">Flask</span>(<span class="pl-s1">__name__</span>)

<span class="pl-en">@<span class="pl-s1">task</span></span>
<span class="pl-k">def</span> <span class="pl-en">make_pie</span>():
    <span class="pl-s">""" This takes a long time! """</span>
    <span class="pl-s1">ingredients</span> <span class="pl-c1">=</span> <span class="pl-en">get_ingredients</span>()
    <span class="pl-s1">pie</span> <span class="pl-c1">=</span> <span class="pl-en">bake</span>(<span class="pl-s1">ingredients</span>)
    <span class="pl-en">deliver</span>(<span class="pl-s1">pie</span>)

<span class="pl-en">@<span class="pl-s1">app</span>.<span class="pl-en">route</span>(<span class="pl-s">'/api/order/pie'</span>)</span>
<span class="pl-k">def</span> <span class="pl-en">order_pie</span>():
    <span class="pl-s">""" This returns immediately! """</span>
    <span class="pl-en">make_pie</span>()
    <span class="pl-k">return</span> <span class="pl-s">"Your pie is being made!"</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="from flask import Flask
from zappa.asynchronous import task
app = Flask(__name__)

@task
def make_pie():
    &quot;&quot;&quot; This takes a long time! &quot;&quot;&quot;
    ingredients = get_ingredients()
    pie = bake(ingredients)
    deliver(pie)

@app.route('/api/order/pie')
def order_pie():
    &quot;&quot;&quot; This returns immediately! &quot;&quot;&quot;
    make_pie()
    return &quot;Your pie is being made!&quot;
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">就是这样！</font><font style="vertical-align: inherit;">您的 API 响应将立即返回，而该</font></font><code>make_pie</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">函数在完全不同的 Lambda 实例中执行。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">当对 @task 修饰函数或 zappa.asynchronous.run 命令的调用发生在 Lambda 外部（例如您的本地开发环境）时，这些函数将立即在本地执行。</font><font style="vertical-align: inherit;">zappa 异步功能仅在 Lambda 环境中或指定</font></font><a href="https://github.com/zappa/zappa#remote-invocations"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">远程调用</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">时才起作用。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-catching-exceptions" class="anchor" aria-hidden="true" tabindex="-1" href="#catching-exceptions"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">捕获异常</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在异步任务上放置 try.. except 块，如下所示：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-en">@<span class="pl-s1">task</span></span>
<span class="pl-k">def</span> <span class="pl-en">make_pie</span>():
    <span class="pl-k">try</span>:
        <span class="pl-s1">ingredients</span> <span class="pl-c1">=</span> <span class="pl-en">get_ingredients</span>()
        <span class="pl-s1">pie</span> <span class="pl-c1">=</span> <span class="pl-en">bake</span>(<span class="pl-s1">ingredients</span>)
        <span class="pl-en">deliver</span>(<span class="pl-s1">pie</span>)
    <span class="pl-k">except</span> <span class="pl-v">Fault</span> <span class="pl-k">as</span> <span class="pl-s1">error</span>:
        <span class="pl-s">"""send an email"""</span>
    ...
    <span class="pl-k">return</span> <span class="pl-v">Response</span>(<span class="pl-s">'Web services down'</span>, <span class="pl-s1">status</span><span class="pl-c1">=</span><span class="pl-c1">503</span>)</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="@task
def make_pie():
    try:
        ingredients = get_ingredients()
        pie = bake(ingredients)
        deliver(pie)
    except Fault as error:
        &quot;&quot;&quot;send an email&quot;&quot;&quot;
    ...
    return Response('Web services down', status=503)" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将导致同一错误发送两次电子邮件。</font><font style="vertical-align: inherit;">请参阅</font></font><a href="https://docs.aws.amazon.com/lambda/latest/dg/retries-on-errors.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AWS 上的异步重试</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">要解决此副作用，并使故障处理程序仅执行一次，请将返回值更改为：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-en">@<span class="pl-s1">task</span></span>
<span class="pl-k">def</span> <span class="pl-en">make_pie</span>():
    <span class="pl-k">try</span>:
        <span class="pl-s">"""code block"""</span>
    <span class="pl-k">except</span> <span class="pl-v">Fault</span> <span class="pl-k">as</span> <span class="pl-s1">error</span>:
        <span class="pl-s">"""send an email"""</span>
    ...
    <span class="pl-k">return</span> {} <span class="pl-c">#or return True</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="@task
def make_pie():
    try:
        &quot;&quot;&quot;code block&quot;&quot;&quot;
    except Fault as error:
        &quot;&quot;&quot;send an email&quot;&quot;&quot;
    ...
    return {} #or return True" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-task-sources" class="anchor" aria-hidden="true" tabindex="-1" href="#task-sources"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">任务来源</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认情况下，此功能使用直接 AWS Lambda 调用。</font><font style="vertical-align: inherit;">您可以使用</font></font><code>task_sns</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">装饰器将 AWS Simple Notification Service 作为任务事件源，如下所示：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">from</span> <span class="pl-s1">zappa</span>.<span class="pl-s1">asynchronous</span> <span class="pl-k">import</span> <span class="pl-s1">task_sns</span>
<span class="pl-en">@<span class="pl-s1">task_sns</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="from zappa.asynchronous import task_sns
@task_sns" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 SNS 还需要在您的 中进行以下设置</font></font><code>zappa_settings</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<div class="highlight highlight-source-js notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-kos">{</span>
  <span class="pl-s">"dev"</span>: <span class="pl-kos">{</span>
    <span class="pl-kos">.</span><span class="pl-kos">.</span>
      <span class="pl-s">"async_source"</span>: <span class="pl-s">"sns"</span><span class="pl-kos">,</span> <span class="pl-c">// Source of async tasks. Defaults to "lambda"</span>
      <span class="pl-s">"async_resources"</span>: <span class="pl-c1">true</span><span class="pl-kos">,</span> <span class="pl-c">// Create the SNS topic to use. Defaults to true.</span>
    <span class="pl-kos">.</span><span class="pl-kos">.</span>
    <span class="pl-kos">}</span>
<span class="pl-kos">}</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="{
  &quot;dev&quot;: {
    ..
      &quot;async_source&quot;: &quot;sns&quot;, // Source of async tasks. Defaults to &quot;lambda&quot;
      &quot;async_resources&quot;: true, // Create the SNS topic to use. Defaults to true.
    ..
    }
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这将自动创建并订阅您调用该命令时代码将使用的 SNS 主题</font></font><code>zappa schedule</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您需要跟踪您的调用，使用 SNS 还将返回消息 ID。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-direct-invocation" class="anchor" aria-hidden="true" tabindex="-1" href="#direct-invocation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">直接调用</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您还可以通过将函数传递给 来在不使用装饰器的情况下使用此功能</font></font><code>zappa.asynchronous.run</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，如下所示：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">from</span> <span class="pl-s1">zappa</span>.<span class="pl-s1">asynchronous</span> <span class="pl-k">import</span> <span class="pl-s1">run</span>

<span class="pl-en">run</span>(<span class="pl-s1">your_function</span>, <span class="pl-s1">args</span>, <span class="pl-s1">kwargs</span>) <span class="pl-c"># Using Lambda</span>
<span class="pl-en">run</span>(<span class="pl-s1">your_function</span>, <span class="pl-s1">args</span>, <span class="pl-s1">kwargs</span>, <span class="pl-s1">service</span><span class="pl-c1">=</span><span class="pl-s">'sns'</span>) <span class="pl-c"># Using SNS</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="from zappa.asynchronous import run

run(your_function, args, kwargs) # Using Lambda
run(your_function, args, kwargs, service='sns') # Using SNS" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-remote-invocations" class="anchor" aria-hidden="true" tabindex="-1" href="#remote-invocations"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">远程调用</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认情况下，Zappa 将使用 lambda 的当前函数名称和当前 AWS 区域。</font><font style="vertical-align: inherit;">如果您希望使用不同的函数名称/区域调用 lambda 或从 lambda 外部调用 lambda，则必须指定 和
</font></font><code>remote_aws_lambda_function_name</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">参数</font></font><code>remote_aws_region</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，以便应用程序知道要使用哪个函数和区域。</font><font style="vertical-align: inherit;">例如，如果我们的披萨制作应用程序的某些部分必须驻留在 EC2 实例上，但我们希望在其自己的 Lambda 实例上调用 make_pie() 函数，我们将按如下方式执行：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-en">@<span class="pl-en">task</span>(<span class="pl-s1">remote_aws_lambda_function_name</span><span class="pl-c1">=</span><span class="pl-s">'pizza-pie-prod'</span>, <span class="pl-s1">remote_aws_region</span><span class="pl-c1">=</span><span class="pl-s">'us-east-1'</span>)</span>
<span class="pl-k">def</span> <span class="pl-en">make_pie</span>():
   <span class="pl-s">""" This takes a long time! """</span>
   <span class="pl-s1">ingredients</span> <span class="pl-c1">=</span> <span class="pl-en">get_ingredients</span>()
   <span class="pl-s1">pie</span> <span class="pl-c1">=</span> <span class="pl-en">bake</span>(<span class="pl-s1">ingredients</span>)
   <span class="pl-en">deliver</span>(<span class="pl-s1">pie</span>)</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="@task(remote_aws_lambda_function_name='pizza-pie-prod', remote_aws_region='us-east-1')
def make_pie():
   &quot;&quot;&quot; This takes a long time! &quot;&quot;&quot;
   ingredients = get_ingredients()
   pie = bake(ingredients)
   deliver(pie)
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果未使用这些 task() 参数，则 EC2 将在本地执行该函数。</font><font style="vertical-align: inherit;">这些相同的
</font></font><code>remote_aws_lambda_function_name</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><code>remote_aws_region</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">参数也可以用在 zappa.asynchronous.run() 函数上。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-restrictions" class="anchor" aria-hidden="true" tabindex="-1" href="#restrictions"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">限制</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此功能存在以下限制：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">函数必须有一个干净的导入路径——即没有闭包、lambda 或方法。</font></font></li>
<li><code>args</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">并且</font></font><code>kwargs</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必须是 JSON 可序列化的。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSON 序列化参数必须在 Lambda (256K) 或 SNS (256K) 事件的大小限制内。</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">所有这些代码仍然向后兼容非 Lambda 环境 - 它只是以阻塞方式执行并返回结果。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-running-tasks-in-a-vpc" class="anchor" aria-hidden="true" tabindex="-1" href="#running-tasks-in-a-vpc"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在VPC中运行任务</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您在虚拟私有云 (VPC) 中运行 Zappa，则需要配置子网以允许 lambda 与 VPC 内的服务以及公共 Internet 进行通信。</font><font style="vertical-align: inherit;">最小设置需要两个子网。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">子网 a</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">创建NAT</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">创建互联网网关</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在路由表中，创建一条将 Internet 网关指向 0.0.0.0/0 的路由。</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在子网-b</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中</font><font style="vertical-align: inherit;">：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">放置您的 lambda 函数</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在路由表中创建一条指向</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">subnet-a</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">所属NAT到0.0.0.0/0的路由。</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以将 lambda 放置在多个子网中，这些子网的配置方式与subnet-b</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">相同，</font><font style="vertical-align: inherit;">以实现高可用性。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一些有用的资源包括</font></font><a href="http://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/CHAP_Tutorials.WebServerDB.CreateVPC.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本教程</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="https://gist.github.com/reggi/dc5f2620b7b4f515e68e46255ac042a7"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">其他教程</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="http://docs.aws.amazon.com/lambda/latest/dg/vpc.html#vpc-internet" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AWS 文档页面</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-responses" class="anchor" aria-hidden="true" tabindex="-1" href="#responses"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">回应</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可以捕获异步任务的响应。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Zappa 使用 DynamoDB 作为这些的后端。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要捕获响应，您必须配置</font></font><code>async_response_table</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">in </font></font><code>zappa_settings</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">这是 DynamoDB 表名称。</font><font style="vertical-align: inherit;">然后，在用 装饰时</font></font><code>@task</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，传递</font></font><code>capture_response=True</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">异步响应被分配一个</font></font><code>response_id</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">. </font><font style="vertical-align: inherit;">它作为装饰器返回的</font></font><code>LambdaAsyncResponse</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">(或) 对象</font><font style="vertical-align: inherit;">的属性返回</font><font style="vertical-align: inherit;">。</font></font><code>SnsAsyncResponse</code><font style="vertical-align: inherit;"></font><code>@task</code><font style="vertical-align: inherit;"></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例子：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">from</span> <span class="pl-s1">zappa</span>.<span class="pl-s1">asynchronous</span> <span class="pl-k">import</span> <span class="pl-s1">task</span>, <span class="pl-s1">get_async_response</span>
<span class="pl-k">from</span> <span class="pl-s1">flask</span> <span class="pl-k">import</span> <span class="pl-v">Flask</span>, <span class="pl-s1">make_response</span>, <span class="pl-s1">abort</span>, <span class="pl-s1">url_for</span>, <span class="pl-s1">redirect</span>, <span class="pl-s1">request</span>, <span class="pl-s1">jsonify</span>
<span class="pl-k">from</span> <span class="pl-s1">time</span> <span class="pl-k">import</span> <span class="pl-s1">sleep</span>

<span class="pl-s1">app</span> <span class="pl-c1">=</span> <span class="pl-v">Flask</span>(<span class="pl-s1">__name__</span>)

<span class="pl-en">@<span class="pl-s1">app</span>.<span class="pl-en">route</span>(<span class="pl-s">'/payload'</span>)</span>
<span class="pl-k">def</span> <span class="pl-en">payload</span>():
    <span class="pl-s1">delay</span> <span class="pl-c1">=</span> <span class="pl-s1">request</span>.<span class="pl-s1">args</span>.<span class="pl-en">get</span>(<span class="pl-s">'delay'</span>, <span class="pl-c1">60</span>)
    <span class="pl-s1">x</span> <span class="pl-c1">=</span> <span class="pl-en">longrunner</span>(<span class="pl-s1">delay</span>)
    <span class="pl-k">return</span> <span class="pl-en">redirect</span>(<span class="pl-en">url_for</span>(<span class="pl-s">'response'</span>, <span class="pl-s1">response_id</span><span class="pl-c1">=</span><span class="pl-s1">x</span>.<span class="pl-s1">response_id</span>))

<span class="pl-en">@<span class="pl-s1">app</span>.<span class="pl-en">route</span>(<span class="pl-s">'/async-response/&lt;response_id&gt;'</span>)</span>
<span class="pl-k">def</span> <span class="pl-en">response</span>(<span class="pl-s1">response_id</span>):
    <span class="pl-s1">response</span> <span class="pl-c1">=</span> <span class="pl-en">get_async_response</span>(<span class="pl-s1">response_id</span>)
    <span class="pl-k">if</span> <span class="pl-s1">response</span> <span class="pl-c1">is</span> <span class="pl-c1">None</span>:
        <span class="pl-en">abort</span>(<span class="pl-c1">404</span>)

    <span class="pl-k">if</span> <span class="pl-s1">response</span>[<span class="pl-s">'status'</span>] <span class="pl-c1">==</span> <span class="pl-s">'complete'</span>:
        <span class="pl-k">return</span> <span class="pl-en">jsonify</span>(<span class="pl-s1">response</span>[<span class="pl-s">'response'</span>])

    <span class="pl-en">sleep</span>(<span class="pl-c1">5</span>)

    <span class="pl-k">return</span> <span class="pl-s">"Not yet ready. Redirecting."</span>, <span class="pl-c1">302</span>, {
        <span class="pl-s">'Content-Type'</span>: <span class="pl-s">'text/plain; charset=utf-8'</span>,
        <span class="pl-s">'Location'</span>: <span class="pl-en">url_for</span>(<span class="pl-s">'response'</span>, <span class="pl-s1">response_id</span><span class="pl-c1">=</span><span class="pl-s1">response_id</span>, <span class="pl-s1">backoff</span><span class="pl-c1">=</span><span class="pl-c1">5</span>),
        <span class="pl-s">'X-redirect-reason'</span>: <span class="pl-s">"Not yet ready."</span>,
    }

<span class="pl-en">@<span class="pl-en">task</span>(<span class="pl-s1">capture_response</span><span class="pl-c1">=</span><span class="pl-c1">True</span>)</span>
<span class="pl-k">def</span> <span class="pl-en">longrunner</span>(<span class="pl-s1">delay</span>):
    <span class="pl-en">sleep</span>(<span class="pl-en">float</span>(<span class="pl-s1">delay</span>))
    <span class="pl-k">return</span> {<span class="pl-s">'MESSAGE'</span>: <span class="pl-s">"It took {} seconds to generate this."</span>.<span class="pl-en">format</span>(<span class="pl-s1">delay</span>)}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="from zappa.asynchronous import task, get_async_response
from flask import Flask, make_response, abort, url_for, redirect, request, jsonify
from time import sleep

app = Flask(__name__)

@app.route('/payload')
def payload():
    delay = request.args.get('delay', 60)
    x = longrunner(delay)
    return redirect(url_for('response', response_id=x.response_id))

@app.route('/async-response/<response_id>')
def response(response_id):
    response = get_async_response(response_id)
    if response is None:
        abort(404)

    if response['status'] == 'complete':
        return jsonify(response['response'])

    sleep(5)

    return &quot;Not yet ready. Redirecting.&quot;, 302, {
        'Content-Type': 'text/plain; charset=utf-8',
        'Location': url_for('response', response_id=response_id, backoff=5),
        'X-redirect-reason': &quot;Not yet ready.&quot;,
    }

@task(capture_response=True)
def longrunner(delay):
    sleep(float(delay))
    return {'MESSAGE': &quot;It took {} seconds to generate this.&quot;.format(delay)}
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h2 tabindex="-1" dir="auto"><a id="user-content-advanced-settings" class="anchor" aria-hidden="true" tabindex="-1" href="#advanced-settings"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">高级设置</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以在本地设置中定义其他设置来更改 Zappa 的行为。</font><font style="vertical-align: inherit;">使用这些需要您自担风险！</font></font></p>
<div class="highlight highlight-source-js notranslate position-relative overflow-auto" dir="auto"><pre> <span class="pl-kos">{</span>
    <span class="pl-s">"dev"</span>: <span class="pl-kos">{</span>
        <span class="pl-s">"additional_text_mimetypes"</span>: <span class="pl-kos">[</span><span class="pl-kos">]</span><span class="pl-kos">,</span> <span class="pl-c">// allows you to provide additional mimetypes to be handled as text when binary_support is true.</span>
        <span class="pl-s">"alb_enabled"</span>: <span class="pl-c1">false</span><span class="pl-kos">,</span> <span class="pl-c">// enable provisioning of application load balancing resources. If set to true, you _must_ fill out the alb_vpc_config option as well.</span>
        <span class="pl-s">"alb_vpc_config"</span>: <span class="pl-kos">{</span>
            <span class="pl-s">"CertificateArn"</span>: <span class="pl-s">"your_acm_certificate_arn"</span><span class="pl-kos">,</span> <span class="pl-c">// ACM certificate ARN for ALB</span>
            <span class="pl-s">"SubnetIds"</span>: <span class="pl-kos">[</span><span class="pl-kos">]</span><span class="pl-kos">,</span> <span class="pl-c">// list of subnets for ALB</span>
            <span class="pl-s">"SecurityGroupIds"</span>: <span class="pl-kos">[</span><span class="pl-kos">]</span> <span class="pl-c">// list of security groups for ALB</span>
        <span class="pl-kos">}</span><span class="pl-kos">,</span>
        <span class="pl-s">"api_key_required"</span>: <span class="pl-c1">false</span><span class="pl-kos">,</span> <span class="pl-c">// enable securing API Gateway endpoints with x-api-key header (default False)</span>
        <span class="pl-s">"api_key"</span>: <span class="pl-s">"your_api_key_id"</span><span class="pl-kos">,</span> <span class="pl-c">// optional, use an existing API key. The option "api_key_required" must be true to apply</span>
        <span class="pl-s">"apigateway_enabled"</span>: <span class="pl-c1">true</span><span class="pl-kos">,</span> <span class="pl-c">// Set to false if you don't want to create an API Gateway resource. Default true.</span>
        <span class="pl-s">"apigateway_description"</span>: <span class="pl-s">"My funky application!"</span><span class="pl-kos">,</span> <span class="pl-c">// Define a custom description for the API Gateway console. Default None.</span>
        <span class="pl-s">"assume_policy"</span>: <span class="pl-s">"my_assume_policy.json"</span><span class="pl-kos">,</span> <span class="pl-c">// optional, IAM assume policy JSON file</span>
        <span class="pl-s">"attach_policy"</span>: <span class="pl-s">"my_attach_policy.json"</span><span class="pl-kos">,</span> <span class="pl-c">// optional, IAM attach policy JSON file</span>
        <span class="pl-s">"apigateway_policy"</span>: <span class="pl-s">"my_apigateway_policy.json"</span><span class="pl-kos">,</span> <span class="pl-c">// optional, API Gateway resource policy JSON file</span>
        <span class="pl-s">"async_source"</span>: <span class="pl-s">"sns"</span><span class="pl-kos">,</span> <span class="pl-c">// Source of async tasks. Defaults to "lambda"</span>
        <span class="pl-s">"async_resources"</span>: <span class="pl-c1">true</span><span class="pl-kos">,</span> <span class="pl-c">// Create the SNS topic and DynamoDB table to use. Defaults to true.</span>
        <span class="pl-s">"async_response_table"</span>: <span class="pl-s">"your_dynamodb_table_name"</span><span class="pl-kos">,</span>  <span class="pl-c">// the DynamoDB table name to use for captured async responses; defaults to None (can't capture)</span>
        <span class="pl-s">"async_response_table_read_capacity"</span>: <span class="pl-c1">1</span><span class="pl-kos">,</span>  <span class="pl-c">// DynamoDB table read capacity; defaults to 1</span>
        <span class="pl-s">"async_response_table_write_capacity"</span>: <span class="pl-c1">1</span><span class="pl-kos">,</span>  <span class="pl-c">// DynamoDB table write capacity; defaults to 1</span>
        <span class="pl-s">"aws_endpoint_urls"</span>: <span class="pl-kos">{</span> <span class="pl-s">"aws_service_name"</span>: <span class="pl-s">"endpoint_url"</span> <span class="pl-kos">}</span><span class="pl-kos">,</span> <span class="pl-c">// a dictionary of endpoint_urls that emulate the appropriate service.  Usually used for testing, for instance with `localstack`.</span>
        <span class="pl-s">"aws_environment_variables"</span> : <span class="pl-kos">{</span><span class="pl-s">"your_key"</span>: <span class="pl-s">"your_value"</span><span class="pl-kos">}</span><span class="pl-kos">,</span> <span class="pl-c">// A dictionary of environment variables that will be available to your deployed app via AWS Lambdas native environment variables. See also "environment_variables" and "remote_env" . Default {}.</span>
        <span class="pl-s">"aws_kms_key_arn"</span>: <span class="pl-s">"your_aws_kms_key_arn"</span><span class="pl-kos">,</span> <span class="pl-c">// Your AWS KMS Key ARN</span>
        <span class="pl-s">"aws_region"</span>: <span class="pl-s">"aws-region-name"</span><span class="pl-kos">,</span> <span class="pl-c">// optional, uses region set in profile or environment variables if not set here,</span>
        <span class="pl-s">"binary_support"</span>: <span class="pl-c1">true</span><span class="pl-kos">,</span> <span class="pl-c">// Enable automatic MIME-type based response encoding through API Gateway. Default true.</span>
        <span class="pl-s">"callbacks"</span>: <span class="pl-kos">{</span> <span class="pl-c">// Call custom functions during the local Zappa deployment/update process</span>
            <span class="pl-s">"settings"</span>: <span class="pl-s">"my_app.settings_callback"</span><span class="pl-kos">,</span> <span class="pl-c">// After loading the settings</span>
            <span class="pl-s">"zip"</span>: <span class="pl-s">"my_app.zip_callback"</span><span class="pl-kos">,</span> <span class="pl-c">// After creating the package</span>
            <span class="pl-s">"post"</span>: <span class="pl-s">"my_app.post_callback"</span><span class="pl-kos">,</span> <span class="pl-c">// After command has executed</span>
        <span class="pl-kos">}</span><span class="pl-kos">,</span>
        <span class="pl-s">"cache_cluster_enabled"</span>: <span class="pl-c1">false</span><span class="pl-kos">,</span> <span class="pl-c">// Use APIGW cache cluster (default False)</span>
        <span class="pl-s">"cache_cluster_size"</span>: <span class="pl-c1">0.5</span><span class="pl-kos">,</span> <span class="pl-c">// APIGW Cache Cluster size (default 0.5)</span>
        <span class="pl-s">"cache_cluster_ttl"</span>: <span class="pl-c1">300</span><span class="pl-kos">,</span> <span class="pl-c">// APIGW Cache Cluster time-to-live (default 300)</span>
        <span class="pl-s">"cache_cluster_encrypted"</span>: <span class="pl-c1">false</span><span class="pl-kos">,</span> <span class="pl-c">// Whether or not APIGW Cache Cluster encrypts data (default False)</span>
        <span class="pl-s">"certificate"</span>: <span class="pl-s">"my_cert.crt"</span><span class="pl-kos">,</span> <span class="pl-c">// SSL certificate file location. Used to manually certify a custom domain</span>
        <span class="pl-s">"certificate_key"</span>: <span class="pl-s">"my_key.key"</span><span class="pl-kos">,</span> <span class="pl-c">// SSL key file location. Used to manually certify a custom domain</span>
        <span class="pl-s">"certificate_chain"</span>: <span class="pl-s">"my_cert_chain.pem"</span><span class="pl-kos">,</span> <span class="pl-c">// SSL certificate chain file location. Used to manually certify a custom domain</span>
        <span class="pl-s">"certificate_arn"</span>: <span class="pl-s">"arn:aws:acm:us-east-1:1234512345:certificate/aaaa-bbb-cccc-dddd"</span><span class="pl-kos">,</span> <span class="pl-c">// ACM certificate ARN (needs to be in us-east-1 region).</span>
        <span class="pl-s">"cloudwatch_log_level"</span>: <span class="pl-s">"OFF"</span><span class="pl-kos">,</span> <span class="pl-c">// Enables/configures a level of logging for the given staging. Available options: "OFF", "INFO", "ERROR", default "OFF".</span>
        <span class="pl-s">"cloudwatch_data_trace"</span>: <span class="pl-c1">false</span><span class="pl-kos">,</span> <span class="pl-c">// Logs all data about received events. Default false.</span>
        <span class="pl-s">"cloudwatch_metrics_enabled"</span>: <span class="pl-c1">false</span><span class="pl-kos">,</span> <span class="pl-c">// Additional metrics for the API Gateway. Default false.</span>
        <span class="pl-s">"cognito"</span>: <span class="pl-kos">{</span> <span class="pl-c">// for Cognito event triggers</span>
            <span class="pl-s">"user_pool"</span>: <span class="pl-s">"user-pool-id"</span><span class="pl-kos">,</span> <span class="pl-c">// User pool ID from AWS Cognito</span>
            <span class="pl-s">"triggers"</span>: <span class="pl-kos">[</span><span class="pl-kos">{</span>
                <span class="pl-s">"source"</span>: <span class="pl-s">"PreSignUp_SignUp"</span><span class="pl-kos">,</span> <span class="pl-c">// triggerSource from http://docs.aws.amazon.com/cognito/latest/developerguide/cognito-user-identity-pools-working-with-aws-lambda-triggers.html#cognito-user-pools-lambda-trigger-syntax-pre-signup</span>
                <span class="pl-s">"function"</span>: <span class="pl-s">"my_app.pre_signup_function"</span>
            <span class="pl-kos">}</span><span class="pl-kos">]</span>
        <span class="pl-kos">}</span><span class="pl-kos">,</span>
        <span class="pl-s">"context_header_mappings"</span>: <span class="pl-kos">{</span> <span class="pl-s">"HTTP_header_name"</span>: <span class="pl-s">"API_Gateway_context_variable"</span> <span class="pl-kos">}</span><span class="pl-kos">,</span> <span class="pl-c">// A dictionary mapping HTTP header names to API Gateway context variables</span>
        <span class="pl-s">"cors"</span>: <span class="pl-c1">false</span><span class="pl-kos">,</span> <span class="pl-c">// Enable Cross-Origin Resource Sharing. Default false. If true, simulates the "Enable CORS" button on the API Gateway console. Can also be a dictionary specifying lists of "allowed_headers", "allowed_methods", and string of "allowed_origin"</span>
        <span class="pl-s">"dead_letter_arn"</span>: <span class="pl-s">"arn:aws:&lt;sns/sqs&gt;:::my-topic/queue"</span><span class="pl-kos">,</span> <span class="pl-c">// Optional Dead Letter configuration for when Lambda async invoke fails thrice</span>
        <span class="pl-s">"debug"</span>: <span class="pl-c1">true</span><span class="pl-kos">,</span> <span class="pl-c">// Print Zappa configuration errors tracebacks in the 500. Default true.</span>
        <span class="pl-s">"delete_local_zip"</span>: <span class="pl-c1">true</span><span class="pl-kos">,</span> <span class="pl-c">// Delete the local zip archive after code updates. Default true.</span>
        <span class="pl-s">"delete_s3_zip"</span>: <span class="pl-c1">true</span><span class="pl-kos">,</span> <span class="pl-c">// Delete the s3 zip archive. Default true.</span>
        <span class="pl-s">"django_settings"</span>: <span class="pl-s">"your_project.production_settings"</span><span class="pl-kos">,</span> <span class="pl-c">// The modular path to your Django project's settings. For Django projects only.</span>
        <span class="pl-s">"domain"</span>: <span class="pl-s">"yourapp.yourdomain.com"</span><span class="pl-kos">,</span> <span class="pl-c">// Required if you're using a domain</span>
        <span class="pl-s">"base_path"</span>: <span class="pl-s">"your-base-path"</span><span class="pl-kos">,</span> <span class="pl-c">// Optional base path for API gateway custom domain base path mapping. Default None. Not supported for use with Application Load Balancer event sources.</span>
        <span class="pl-s">"environment_variables"</span>: <span class="pl-kos">{</span><span class="pl-s">"your_key"</span>: <span class="pl-s">"your_value"</span><span class="pl-kos">}</span><span class="pl-kos">,</span> <span class="pl-c">// A dictionary of environment variables that will be available to your deployed app. See also "remote_env" and "aws_environment_variables". Default {}.</span>
        <span class="pl-s">"events"</span>: <span class="pl-kos">[</span>
            <span class="pl-kos">{</span>   <span class="pl-c">// Recurring events</span>
                <span class="pl-s">"function"</span>: <span class="pl-s">"your_module.your_recurring_function"</span><span class="pl-kos">,</span> <span class="pl-c">// The function to execute (Pattern: [._A-Za-z0-9]+).</span>
                <span class="pl-s">"expression"</span>: <span class="pl-s">"rate(1 minute)"</span> <span class="pl-c">// When to execute it (in cron or rate format)</span>
            <span class="pl-kos">}</span><span class="pl-kos">,</span>
            <span class="pl-kos">{</span>   <span class="pl-c">// AWS Reactive events</span>
                <span class="pl-s">"function"</span>: <span class="pl-s">"your_module.your_reactive_function"</span><span class="pl-kos">,</span> <span class="pl-c">// The function to execute (Pattern: [._A-Za-z0-9]+).</span>
                <span class="pl-s">"event_source"</span>: <span class="pl-kos">{</span>
                    <span class="pl-s">"arn"</span>:  <span class="pl-s">"arn:aws:s3:::my-bucket"</span><span class="pl-kos">,</span> <span class="pl-c">// The ARN of this event source</span>
                    <span class="pl-s">"events"</span>: <span class="pl-kos">[</span>
                        <span class="pl-s">"s3:ObjectCreated:*"</span> <span class="pl-c">// The specific event to execute in response to.</span>
                    <span class="pl-kos">]</span>
                <span class="pl-kos">}</span>
            <span class="pl-kos">}</span>
        <span class="pl-kos">]</span><span class="pl-kos">,</span>
        <span class="pl-s">"endpoint_configuration"</span>: <span class="pl-kos">[</span><span class="pl-s">"EDGE"</span><span class="pl-kos">,</span> <span class="pl-s">"REGIONAL"</span><span class="pl-kos">,</span> <span class="pl-s">"PRIVATE"</span><span class="pl-kos">]</span><span class="pl-kos">,</span>  <span class="pl-c">// Specify APIGateway endpoint None (default) or list `EDGE`, `REGION`, `PRIVATE`</span>
        <span class="pl-s">"exception_handler"</span>: <span class="pl-s">"your_module.report_exception"</span><span class="pl-kos">,</span> <span class="pl-c">// function that will be invoked in case Zappa sees an unhandled exception raised from your code</span>
        <span class="pl-s">"exclude"</span>: <span class="pl-kos">[</span><span class="pl-s">"file.gz"</span><span class="pl-kos">,</span> <span class="pl-s">"tests"</span><span class="pl-kos">]</span><span class="pl-kos">,</span> <span class="pl-c">// A list of filename patterns to exclude from the archive (see `fnmatch` module for patterns).</span>
        <span class="pl-s">"exclude_glob"</span>: <span class="pl-kos">[</span><span class="pl-s">"*.gz"</span><span class="pl-kos">,</span> <span class="pl-s">"*.rar"</span><span class="pl-kos">,</span> <span class="pl-s">"tests/**/*"</span><span class="pl-kos">]</span><span class="pl-kos">,</span> <span class="pl-c">// A list of glob patterns to exclude from the archive. To exclude boto3 and botocore (available in an older version on Lambda), add "boto3*" and "botocore*".</span>
        <span class="pl-s">"extends"</span>: <span class="pl-s">"stage_name"</span><span class="pl-kos">,</span> <span class="pl-c">// Duplicate and extend another stage's settings. For example, `dev-asia` could extend from `dev-common` with a different `s3_bucket` value.</span>
        <span class="pl-s">"extra_permissions"</span>: <span class="pl-kos">[</span><span class="pl-kos">{</span> <span class="pl-c">// Attach any extra permissions to this policy. Default None</span>
            <span class="pl-s">"Effect"</span>: <span class="pl-s">"Allow"</span><span class="pl-kos">,</span>
            <span class="pl-s">"Action"</span>: <span class="pl-kos">[</span><span class="pl-s">"rekognition:*"</span><span class="pl-kos">]</span><span class="pl-kos">,</span> <span class="pl-c">// AWS Service ARN</span>
            <span class="pl-s">"Resource"</span>: <span class="pl-s">"*"</span>
        <span class="pl-kos">}</span><span class="pl-kos">]</span><span class="pl-kos">,</span>
        <span class="pl-s">"iam_authorization"</span>: <span class="pl-c1">false</span><span class="pl-kos">,</span> <span class="pl-c">// optional, use IAM to require request signing. Default false. Note that enabling this will override the authorizer configuration.</span>
        <span class="pl-s">"include"</span>: <span class="pl-kos">[</span><span class="pl-s">"your_special_library_to_load_at_handler_init"</span><span class="pl-kos">]</span><span class="pl-kos">,</span> <span class="pl-c">// load special libraries into PYTHONPATH at handler init that certain modules cannot find on path</span>
        <span class="pl-s">"authorizer"</span>: <span class="pl-kos">{</span>
            <span class="pl-s">"function"</span>: <span class="pl-s">"your_module.your_auth_function"</span><span class="pl-kos">,</span> <span class="pl-c">// Local function to run for token validation. For more information about the function see below.</span>
            <span class="pl-s">"arn"</span>: <span class="pl-s">"arn:aws:lambda:&lt;region&gt;:&lt;account_id&gt;:function:&lt;function_name&gt;"</span><span class="pl-kos">,</span> <span class="pl-c">// Existing Lambda function to run for token validation.</span>
            <span class="pl-s">"result_ttl"</span>: <span class="pl-c1">300</span><span class="pl-kos">,</span> <span class="pl-c">// Optional. Default 300. The time-to-live (TTL) period, in seconds, that specifies how long API Gateway caches authorizer results. Currently, the maximum TTL value is 3600 seconds.</span>
            <span class="pl-s">"token_header"</span>: <span class="pl-s">"Authorization"</span><span class="pl-kos">,</span> <span class="pl-c">// Optional. Default 'Authorization'. The name of a custom authorization header containing the token that clients submit as part of their requests.</span>
            <span class="pl-s">"validation_expression"</span>: <span class="pl-s">"^Bearer \\w+$"</span><span class="pl-kos">,</span> <span class="pl-c">// Optional. A validation expression for the incoming token, specify a regular expression.</span>
        <span class="pl-kos">}</span><span class="pl-kos">,</span>
        <span class="pl-s">"keep_warm"</span>: <span class="pl-c1">true</span><span class="pl-kos">,</span> <span class="pl-c">// Create CloudWatch events to keep the server warm. Default true. To remove, set to false and then `unschedule`.</span>
        <span class="pl-s">"keep_warm_expression"</span>: <span class="pl-s">"rate(4 minutes)"</span><span class="pl-kos">,</span> <span class="pl-c">// How often to execute the keep-warm, in cron and rate format. Default 4 minutes.</span>
        <span class="pl-s">"lambda_description"</span>: <span class="pl-s">"Your Description"</span><span class="pl-kos">,</span> <span class="pl-c">// However you want to describe your project for the AWS console. Default "Zappa Deployment".</span>
        <span class="pl-s">"lambda_handler"</span>: <span class="pl-s">"your_custom_handler"</span><span class="pl-kos">,</span> <span class="pl-c">// The name of Lambda handler. Default: handler.lambda_handler</span>
        <span class="pl-s">"layers"</span>: <span class="pl-kos">[</span><span class="pl-s">"arn:aws:lambda:&lt;region&gt;:&lt;account_id&gt;:layer:&lt;layer_name&gt;:&lt;layer_version&gt;"</span><span class="pl-kos">]</span><span class="pl-kos">,</span> <span class="pl-c">// optional lambda layers</span>
        <span class="pl-s">"lambda_concurrency"</span>: <span class="pl-c1">10</span><span class="pl-kos">,</span> <span class="pl-c">// Sets the maximum number of simultaneous executions for a function, and reserves capacity for that concurrency level. Default is None.</span>
        <span class="pl-s">"lets_encrypt_key"</span>: <span class="pl-s">"s3://your-bucket/account.key"</span><span class="pl-kos">,</span> <span class="pl-c">// Let's Encrypt account key path. Can either be an S3 path or a local file path.</span>
        <span class="pl-s">"log_level"</span>: <span class="pl-s">"DEBUG"</span><span class="pl-kos">,</span> <span class="pl-c">// Set the Zappa log level. Can be one of CRITICAL, ERROR, WARNING, INFO and DEBUG. Default: DEBUG</span>
        <span class="pl-s">"manage_roles"</span>: <span class="pl-c1">true</span><span class="pl-kos">,</span> <span class="pl-c">// Have Zappa automatically create and define IAM execution roles and policies. Default true. If false, you must define your own IAM Role and role_name setting.</span>
        <span class="pl-s">"memory_size"</span>: <span class="pl-c1">512</span><span class="pl-kos">,</span> <span class="pl-c">// Lambda function memory in MB. Default 512.</span>
        <span class="pl-s">"ephemeral_storage"</span>: <span class="pl-kos">{</span> <span class="pl-s">"Size"</span>: <span class="pl-c1">512</span> <span class="pl-kos">}</span><span class="pl-kos">,</span> <span class="pl-c">// Lambda function ephemeral_storage size in MB, Default 512, Max 10240</span>
        <span class="pl-s">"num_retained_versions"</span>:<span class="pl-c1">null</span><span class="pl-kos">,</span> <span class="pl-c">// Indicates the number of old versions to retain for the lambda. If absent, keeps all the versions of the function.</span>
        <span class="pl-s">"payload_compression"</span>: <span class="pl-c1">true</span><span class="pl-kos">,</span> <span class="pl-c">// Whether or not to enable API gateway payload compression (default: true)</span>
        <span class="pl-s">"payload_minimum_compression_size"</span>: <span class="pl-c1">0</span><span class="pl-kos">,</span> <span class="pl-c">// The threshold size (in bytes) below which payload compression will not be applied (default: 0)</span>
        <span class="pl-s">"prebuild_script"</span>: <span class="pl-s">"your_module.your_function"</span><span class="pl-kos">,</span> <span class="pl-c">// Function to execute before uploading code</span>
        <span class="pl-s">"profile_name"</span>: <span class="pl-s">"your-profile-name"</span><span class="pl-kos">,</span> <span class="pl-c">// AWS profile credentials to use. Default 'default'. Removing this setting will use the AWS_ACCESS_KEY_ID and AWS_SECRET_ACCESS_KEY environment variables instead.</span>
        <span class="pl-s">"project_name"</span>: <span class="pl-s">"MyProject"</span><span class="pl-kos">,</span> <span class="pl-c">// The name of the project as it appears on AWS. Defaults to a slugified `pwd`.</span>
        <span class="pl-s">"remote_env"</span>: <span class="pl-s">"s3://my-project-config-files/filename.json"</span><span class="pl-kos">,</span> <span class="pl-c">// optional file in s3 bucket containing a flat json object which will be used to set custom environment variables.</span>
        <span class="pl-s">"role_name"</span>: <span class="pl-s">"MyLambdaRole"</span><span class="pl-kos">,</span> <span class="pl-c">// Name of Zappa execution role. Default &lt;project_name&gt;-&lt;env&gt;-ZappaExecutionRole. To use a different, pre-existing policy, you must also set manage_roles to false.</span>
        <span class="pl-s">"role_arn"</span>: <span class="pl-s">"arn:aws:iam::12345:role/app-ZappaLambdaExecutionRole"</span><span class="pl-kos">,</span> <span class="pl-c">// ARN of Zappa execution role. Default to None. To use a different, pre-existing policy, you must also set manage_roles to false. This overrides role_name. Use with temporary credentials via GetFederationToken.</span>
        <span class="pl-s">"route53_enabled"</span>: <span class="pl-c1">true</span><span class="pl-kos">,</span> <span class="pl-c">// Have Zappa update your Route53 Hosted Zones when certifying with a custom domain. Default true.</span>
        <span class="pl-s">"runtime"</span>: <span class="pl-s">"python3.12"</span><span class="pl-kos">,</span> <span class="pl-c">// Python runtime to use on Lambda. Can be one of: "python3.8", "python3.9", "python3.10", "python3.11", or "python3.12". Defaults to whatever the current Python being used is.</span>
        <span class="pl-s">"s3_bucket"</span>: <span class="pl-s">"dev-bucket"</span><span class="pl-kos">,</span> <span class="pl-c">// Zappa zip bucket,</span>
        <span class="pl-s">"slim_handler"</span>: <span class="pl-c1">false</span><span class="pl-kos">,</span> <span class="pl-c">// Useful if project &gt;50M. Set true to just upload a small handler to Lambda and load actual project from S3 at runtime. Default false.</span>
        <span class="pl-s">"settings_file"</span>: <span class="pl-s">"~/Projects/MyApp/settings/dev_settings.py"</span><span class="pl-kos">,</span> <span class="pl-c">// Server side settings file location,</span>
        <span class="pl-s">"tags"</span>: <span class="pl-kos">{</span> <span class="pl-c">// Attach additional tags to AWS Resources</span>
            <span class="pl-s">"Key"</span>: <span class="pl-s">"Value"</span><span class="pl-kos">,</span>  <span class="pl-c">// Example Key and value</span>
            <span class="pl-s">"Key2"</span>: <span class="pl-s">"Value2"</span><span class="pl-kos">,</span>
            <span class="pl-kos">}</span><span class="pl-kos">,</span>
        <span class="pl-s">"timeout_seconds"</span>: <span class="pl-c1">30</span><span class="pl-kos">,</span> <span class="pl-c">// Maximum lifespan for the Lambda function (default 30, max 900.)</span>
        <span class="pl-s">"touch"</span>: <span class="pl-c1">true</span><span class="pl-kos">,</span> <span class="pl-c">// GET the production URL upon initial deployment (default True)</span>
        <span class="pl-s">"touch_path"</span>: <span class="pl-s">"/"</span><span class="pl-kos">,</span> <span class="pl-c">// The endpoint path to GET when checking the initial deployment (default "/")</span>
        <span class="pl-s">"use_precompiled_packages"</span>: <span class="pl-c1">true</span><span class="pl-kos">,</span> <span class="pl-c">// If possible, use C-extension packages which have been pre-compiled for AWS Lambda. Default true.</span>
        <span class="pl-s">"vpc_config"</span>: <span class="pl-kos">{</span> <span class="pl-c">// Optional Virtual Private Cloud (VPC) configuration for Lambda function</span>
            <span class="pl-s">"SubnetIds"</span>: <span class="pl-kos">[</span> <span class="pl-s">"subnet-12345678"</span> <span class="pl-kos">]</span><span class="pl-kos">,</span> <span class="pl-c">// Note: not all availability zones support Lambda!</span>
            <span class="pl-s">"SecurityGroupIds"</span>: <span class="pl-kos">[</span> <span class="pl-s">"sg-12345678"</span> <span class="pl-kos">]</span>
        <span class="pl-kos">}</span><span class="pl-kos">,</span>
        <span class="pl-s">"xray_tracing"</span>: <span class="pl-c1">false</span> <span class="pl-c">// Optional, enable AWS X-Ray tracing on your lambda function.</span>
    <span class="pl-kos">}</span>
<span class="pl-kos">}</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value=" {
    &quot;dev&quot;: {
        &quot;additional_text_mimetypes&quot;: [], // allows you to provide additional mimetypes to be handled as text when binary_support is true.
        &quot;alb_enabled&quot;: false, // enable provisioning of application load balancing resources. If set to true, you _must_ fill out the alb_vpc_config option as well.
        &quot;alb_vpc_config&quot;: {
            &quot;CertificateArn&quot;: &quot;your_acm_certificate_arn&quot;, // ACM certificate ARN for ALB
            &quot;SubnetIds&quot;: [], // list of subnets for ALB
            &quot;SecurityGroupIds&quot;: [] // list of security groups for ALB
        },
        &quot;api_key_required&quot;: false, // enable securing API Gateway endpoints with x-api-key header (default False)
        &quot;api_key&quot;: &quot;your_api_key_id&quot;, // optional, use an existing API key. The option &quot;api_key_required&quot; must be true to apply
        &quot;apigateway_enabled&quot;: true, // Set to false if you don't want to create an API Gateway resource. Default true.
        &quot;apigateway_description&quot;: &quot;My funky application!&quot;, // Define a custom description for the API Gateway console. Default None.
        &quot;assume_policy&quot;: &quot;my_assume_policy.json&quot;, // optional, IAM assume policy JSON file
        &quot;attach_policy&quot;: &quot;my_attach_policy.json&quot;, // optional, IAM attach policy JSON file
        &quot;apigateway_policy&quot;: &quot;my_apigateway_policy.json&quot;, // optional, API Gateway resource policy JSON file
        &quot;async_source&quot;: &quot;sns&quot;, // Source of async tasks. Defaults to &quot;lambda&quot;
        &quot;async_resources&quot;: true, // Create the SNS topic and DynamoDB table to use. Defaults to true.
        &quot;async_response_table&quot;: &quot;your_dynamodb_table_name&quot;,  // the DynamoDB table name to use for captured async responses; defaults to None (can't capture)
        &quot;async_response_table_read_capacity&quot;: 1,  // DynamoDB table read capacity; defaults to 1
        &quot;async_response_table_write_capacity&quot;: 1,  // DynamoDB table write capacity; defaults to 1
        &quot;aws_endpoint_urls&quot;: { &quot;aws_service_name&quot;: &quot;endpoint_url&quot; }, // a dictionary of endpoint_urls that emulate the appropriate service.  Usually used for testing, for instance with `localstack`.
        &quot;aws_environment_variables&quot; : {&quot;your_key&quot;: &quot;your_value&quot;}, // A dictionary of environment variables that will be available to your deployed app via AWS Lambdas native environment variables. See also &quot;environment_variables&quot; and &quot;remote_env&quot; . Default {}.
        &quot;aws_kms_key_arn&quot;: &quot;your_aws_kms_key_arn&quot;, // Your AWS KMS Key ARN
        &quot;aws_region&quot;: &quot;aws-region-name&quot;, // optional, uses region set in profile or environment variables if not set here,
        &quot;binary_support&quot;: true, // Enable automatic MIME-type based response encoding through API Gateway. Default true.
        &quot;callbacks&quot;: { // Call custom functions during the local Zappa deployment/update process
            &quot;settings&quot;: &quot;my_app.settings_callback&quot;, // After loading the settings
            &quot;zip&quot;: &quot;my_app.zip_callback&quot;, // After creating the package
            &quot;post&quot;: &quot;my_app.post_callback&quot;, // After command has executed
        },
        &quot;cache_cluster_enabled&quot;: false, // Use APIGW cache cluster (default False)
        &quot;cache_cluster_size&quot;: 0.5, // APIGW Cache Cluster size (default 0.5)
        &quot;cache_cluster_ttl&quot;: 300, // APIGW Cache Cluster time-to-live (default 300)
        &quot;cache_cluster_encrypted&quot;: false, // Whether or not APIGW Cache Cluster encrypts data (default False)
        &quot;certificate&quot;: &quot;my_cert.crt&quot;, // SSL certificate file location. Used to manually certify a custom domain
        &quot;certificate_key&quot;: &quot;my_key.key&quot;, // SSL key file location. Used to manually certify a custom domain
        &quot;certificate_chain&quot;: &quot;my_cert_chain.pem&quot;, // SSL certificate chain file location. Used to manually certify a custom domain
        &quot;certificate_arn&quot;: &quot;arn:aws:acm:us-east-1:1234512345:certificate/aaaa-bbb-cccc-dddd&quot;, // ACM certificate ARN (needs to be in us-east-1 region).
        &quot;cloudwatch_log_level&quot;: &quot;OFF&quot;, // Enables/configures a level of logging for the given staging. Available options: &quot;OFF&quot;, &quot;INFO&quot;, &quot;ERROR&quot;, default &quot;OFF&quot;.
        &quot;cloudwatch_data_trace&quot;: false, // Logs all data about received events. Default false.
        &quot;cloudwatch_metrics_enabled&quot;: false, // Additional metrics for the API Gateway. Default false.
        &quot;cognito&quot;: { // for Cognito event triggers
            &quot;user_pool&quot;: &quot;user-pool-id&quot;, // User pool ID from AWS Cognito
            &quot;triggers&quot;: [{
                &quot;source&quot;: &quot;PreSignUp_SignUp&quot;, // triggerSource from http://docs.aws.amazon.com/cognito/latest/developerguide/cognito-user-identity-pools-working-with-aws-lambda-triggers.html#cognito-user-pools-lambda-trigger-syntax-pre-signup
                &quot;function&quot;: &quot;my_app.pre_signup_function&quot;
            }]
        },
        &quot;context_header_mappings&quot;: { &quot;HTTP_header_name&quot;: &quot;API_Gateway_context_variable&quot; }, // A dictionary mapping HTTP header names to API Gateway context variables
        &quot;cors&quot;: false, // Enable Cross-Origin Resource Sharing. Default false. If true, simulates the &quot;Enable CORS&quot; button on the API Gateway console. Can also be a dictionary specifying lists of &quot;allowed_headers&quot;, &quot;allowed_methods&quot;, and string of &quot;allowed_origin&quot;
        &quot;dead_letter_arn&quot;: &quot;arn:aws:<sns/sqs>:::my-topic/queue&quot;, // Optional Dead Letter configuration for when Lambda async invoke fails thrice
        &quot;debug&quot;: true, // Print Zappa configuration errors tracebacks in the 500. Default true.
        &quot;delete_local_zip&quot;: true, // Delete the local zip archive after code updates. Default true.
        &quot;delete_s3_zip&quot;: true, // Delete the s3 zip archive. Default true.
        &quot;django_settings&quot;: &quot;your_project.production_settings&quot;, // The modular path to your Django project's settings. For Django projects only.
        &quot;domain&quot;: &quot;yourapp.yourdomain.com&quot;, // Required if you're using a domain
        &quot;base_path&quot;: &quot;your-base-path&quot;, // Optional base path for API gateway custom domain base path mapping. Default None. Not supported for use with Application Load Balancer event sources.
        &quot;environment_variables&quot;: {&quot;your_key&quot;: &quot;your_value&quot;}, // A dictionary of environment variables that will be available to your deployed app. See also &quot;remote_env&quot; and &quot;aws_environment_variables&quot;. Default {}.
        &quot;events&quot;: [
            {   // Recurring events
                &quot;function&quot;: &quot;your_module.your_recurring_function&quot;, // The function to execute (Pattern: [._A-Za-z0-9]+).
                &quot;expression&quot;: &quot;rate(1 minute)&quot; // When to execute it (in cron or rate format)
            },
            {   // AWS Reactive events
                &quot;function&quot;: &quot;your_module.your_reactive_function&quot;, // The function to execute (Pattern: [._A-Za-z0-9]+).
                &quot;event_source&quot;: {
                    &quot;arn&quot;:  &quot;arn:aws:s3:::my-bucket&quot;, // The ARN of this event source
                    &quot;events&quot;: [
                        &quot;s3:ObjectCreated:*&quot; // The specific event to execute in response to.
                    ]
                }
            }
        ],
        &quot;endpoint_configuration&quot;: [&quot;EDGE&quot;, &quot;REGIONAL&quot;, &quot;PRIVATE&quot;],  // Specify APIGateway endpoint None (default) or list `EDGE`, `REGION`, `PRIVATE`
        &quot;exception_handler&quot;: &quot;your_module.report_exception&quot;, // function that will be invoked in case Zappa sees an unhandled exception raised from your code
        &quot;exclude&quot;: [&quot;file.gz&quot;, &quot;tests&quot;], // A list of filename patterns to exclude from the archive (see `fnmatch` module for patterns).
        &quot;exclude_glob&quot;: [&quot;*.gz&quot;, &quot;*.rar&quot;, &quot;tests/**/*&quot;], // A list of glob patterns to exclude from the archive. To exclude boto3 and botocore (available in an older version on Lambda), add &quot;boto3*&quot; and &quot;botocore*&quot;.
        &quot;extends&quot;: &quot;stage_name&quot;, // Duplicate and extend another stage's settings. For example, `dev-asia` could extend from `dev-common` with a different `s3_bucket` value.
        &quot;extra_permissions&quot;: [{ // Attach any extra permissions to this policy. Default None
            &quot;Effect&quot;: &quot;Allow&quot;,
            &quot;Action&quot;: [&quot;rekognition:*&quot;], // AWS Service ARN
            &quot;Resource&quot;: &quot;*&quot;
        }],
        &quot;iam_authorization&quot;: false, // optional, use IAM to require request signing. Default false. Note that enabling this will override the authorizer configuration.
        &quot;include&quot;: [&quot;your_special_library_to_load_at_handler_init&quot;], // load special libraries into PYTHONPATH at handler init that certain modules cannot find on path
        &quot;authorizer&quot;: {
            &quot;function&quot;: &quot;your_module.your_auth_function&quot;, // Local function to run for token validation. For more information about the function see below.
            &quot;arn&quot;: &quot;arn:aws:lambda:<region>:<account_id>:function:<function_name>&quot;, // Existing Lambda function to run for token validation.
            &quot;result_ttl&quot;: 300, // Optional. Default 300. The time-to-live (TTL) period, in seconds, that specifies how long API Gateway caches authorizer results. Currently, the maximum TTL value is 3600 seconds.
            &quot;token_header&quot;: &quot;Authorization&quot;, // Optional. Default 'Authorization'. The name of a custom authorization header containing the token that clients submit as part of their requests.
            &quot;validation_expression&quot;: &quot;^Bearer \\w+$&quot;, // Optional. A validation expression for the incoming token, specify a regular expression.
        },
        &quot;keep_warm&quot;: true, // Create CloudWatch events to keep the server warm. Default true. To remove, set to false and then `unschedule`.
        &quot;keep_warm_expression&quot;: &quot;rate(4 minutes)&quot;, // How often to execute the keep-warm, in cron and rate format. Default 4 minutes.
        &quot;lambda_description&quot;: &quot;Your Description&quot;, // However you want to describe your project for the AWS console. Default &quot;Zappa Deployment&quot;.
        &quot;lambda_handler&quot;: &quot;your_custom_handler&quot;, // The name of Lambda handler. Default: handler.lambda_handler
        &quot;layers&quot;: [&quot;arn:aws:lambda:<region>:<account_id>:layer:<layer_name>:<layer_version>&quot;], // optional lambda layers
        &quot;lambda_concurrency&quot;: 10, // Sets the maximum number of simultaneous executions for a function, and reserves capacity for that concurrency level. Default is None.
        &quot;lets_encrypt_key&quot;: &quot;s3://your-bucket/account.key&quot;, // Let's Encrypt account key path. Can either be an S3 path or a local file path.
        &quot;log_level&quot;: &quot;DEBUG&quot;, // Set the Zappa log level. Can be one of CRITICAL, ERROR, WARNING, INFO and DEBUG. Default: DEBUG
        &quot;manage_roles&quot;: true, // Have Zappa automatically create and define IAM execution roles and policies. Default true. If false, you must define your own IAM Role and role_name setting.
        &quot;memory_size&quot;: 512, // Lambda function memory in MB. Default 512.
        &quot;ephemeral_storage&quot;: { &quot;Size&quot;: 512 }, // Lambda function ephemeral_storage size in MB, Default 512, Max 10240
        &quot;num_retained_versions&quot;:null, // Indicates the number of old versions to retain for the lambda. If absent, keeps all the versions of the function.
        &quot;payload_compression&quot;: true, // Whether or not to enable API gateway payload compression (default: true)
        &quot;payload_minimum_compression_size&quot;: 0, // The threshold size (in bytes) below which payload compression will not be applied (default: 0)
        &quot;prebuild_script&quot;: &quot;your_module.your_function&quot;, // Function to execute before uploading code
        &quot;profile_name&quot;: &quot;your-profile-name&quot;, // AWS profile credentials to use. Default 'default'. Removing this setting will use the AWS_ACCESS_KEY_ID and AWS_SECRET_ACCESS_KEY environment variables instead.
        &quot;project_name&quot;: &quot;MyProject&quot;, // The name of the project as it appears on AWS. Defaults to a slugified `pwd`.
        &quot;remote_env&quot;: &quot;s3://my-project-config-files/filename.json&quot;, // optional file in s3 bucket containing a flat json object which will be used to set custom environment variables.
        &quot;role_name&quot;: &quot;MyLambdaRole&quot;, // Name of Zappa execution role. Default <project_name>-<env>-ZappaExecutionRole. To use a different, pre-existing policy, you must also set manage_roles to false.
        &quot;role_arn&quot;: &quot;arn:aws:iam::12345:role/app-ZappaLambdaExecutionRole&quot;, // ARN of Zappa execution role. Default to None. To use a different, pre-existing policy, you must also set manage_roles to false. This overrides role_name. Use with temporary credentials via GetFederationToken.
        &quot;route53_enabled&quot;: true, // Have Zappa update your Route53 Hosted Zones when certifying with a custom domain. Default true.
        &quot;runtime&quot;: &quot;python3.12&quot;, // Python runtime to use on Lambda. Can be one of: &quot;python3.8&quot;, &quot;python3.9&quot;, &quot;python3.10&quot;, &quot;python3.11&quot;, or &quot;python3.12&quot;. Defaults to whatever the current Python being used is.
        &quot;s3_bucket&quot;: &quot;dev-bucket&quot;, // Zappa zip bucket,
        &quot;slim_handler&quot;: false, // Useful if project >50M. Set true to just upload a small handler to Lambda and load actual project from S3 at runtime. Default false.
        &quot;settings_file&quot;: &quot;~/Projects/MyApp/settings/dev_settings.py&quot;, // Server side settings file location,
        &quot;tags&quot;: { // Attach additional tags to AWS Resources
            &quot;Key&quot;: &quot;Value&quot;,  // Example Key and value
            &quot;Key2&quot;: &quot;Value2&quot;,
            },
        &quot;timeout_seconds&quot;: 30, // Maximum lifespan for the Lambda function (default 30, max 900.)
        &quot;touch&quot;: true, // GET the production URL upon initial deployment (default True)
        &quot;touch_path&quot;: &quot;/&quot;, // The endpoint path to GET when checking the initial deployment (default &quot;/&quot;)
        &quot;use_precompiled_packages&quot;: true, // If possible, use C-extension packages which have been pre-compiled for AWS Lambda. Default true.
        &quot;vpc_config&quot;: { // Optional Virtual Private Cloud (VPC) configuration for Lambda function
            &quot;SubnetIds&quot;: [ &quot;subnet-12345678&quot; ], // Note: not all availability zones support Lambda!
            &quot;SecurityGroupIds&quot;: [ &quot;sg-12345678&quot; ]
        },
        &quot;xray_tracing&quot;: false // Optional, enable AWS X-Ray tracing on your lambda function.
    }
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-yaml-settings" class="anchor" aria-hidden="true" tabindex="-1" href="#yaml-settings"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">YAML 设置</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您更喜欢 YAML 而不是 JSON，您也可以使用</font></font><code>zappa_settings.yml</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，如下所示：</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre>---
<span class="pl-ent">dev</span>:
  <span class="pl-ent">app_function</span>: <span class="pl-s">your_module.your_app</span>
  <span class="pl-ent">s3_bucket</span>: <span class="pl-s">your-code-bucket</span>
  <span class="pl-ent">events</span>:
  - <span class="pl-ent">function</span>: <span class="pl-s">your_module.your_function</span>
    <span class="pl-ent">event_source</span>:
      <span class="pl-ent">arn</span>: <span class="pl-s">arn:aws:s3:::your-event-bucket</span>
      <span class="pl-ent">events</span>:
      - <span class="pl-s">s3:ObjectCreated:*</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="---
dev:
  app_function: your_module.your_app
  s3_bucket: your-code-bucket
  events:
  - function: your_module.your_function
    event_source:
      arn: arn:aws:s3:::your-event-bucket
      events:
      - s3:ObjectCreated:*" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您还可以随时使用</font></font><code>-s</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">参数提供自定义设置文件，例如：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ zappa deploy dev -s my-custom-settings.yml
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ zappa deploy dev -s my-custom-settings.yml" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">同样，您可以提供一个</font></font><code>zappa_settings.toml</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件：</font></font></p>
<div class="highlight highlight-source-toml notranslate position-relative overflow-auto" dir="auto"><pre>[<span class="pl-en">dev</span>]
  <span class="pl-smi">app_function</span> = <span class="pl-s"><span class="pl-pds">"</span>your_module.your_app<span class="pl-pds">"</span></span>
  <span class="pl-smi">s3_bucket</span> = <span class="pl-s"><span class="pl-pds">"</span>your-code-bucket<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="[dev]
  app_function = &quot;your_module.your_app&quot;
  s3_bucket = &quot;your-code-bucket&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h2 tabindex="-1" dir="auto"><a id="user-content-advanced-usage" class="anchor" aria-hidden="true" tabindex="-1" href="#advanced-usage"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">高级用法</font></font></h2>
<h3 tabindex="-1" dir="auto"><a id="user-content-keeping-the-server-warm" class="anchor" aria-hidden="true" tabindex="-1" href="#keeping-the-server-warm"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">保持服务器温暖</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Zappa 将自动设置定期执行您的应用程序，以保持 Lambda 函数的正常运行。</font><font style="vertical-align: inherit;">可以通过设置禁用此功能</font></font><code>keep_warm</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<h4 tabindex="-1" dir="auto"><a id="user-content-serving-static-files--binary-uploads" class="anchor" aria-hidden="true" tabindex="-1" href="#serving-static-files--binary-uploads"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提供静态文件/二进制上传服务</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Zappa 现在能够提供和接收二进制文件，如通过其 MIME 类型检测到的。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">但是，一般来说，Zappa 是为运行应用程序代码而设计的，而不是为提供静态 Web 资产而设计的。</font><font style="vertical-align: inherit;">如果您计划在 Web 应用程序中提供自定义静态资产（CSS/JavaScript/图像/等），您可能需要结合使用 AWS S3 和 AWS CloudFront。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您的 Web 应用程序框架可能能够自动为您处理此问题。</font><font style="vertical-align: inherit;">对于 Flask，有</font></font><a href="https://github.com/e-dard/flask-s3"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Flask-S3</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，对于 Django，有</font></font><a href="https://django-storages.readthedocs.io/en/latest/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Django-Storages</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">同样，您可能希望设计您的应用程序，以便静态二进制文件上传</font></font><a href="http://docs.aws.amazon.com/AWSJavaScriptSDK/guide/browser-examples.html#Uploading_a_local_file_using_the_File_API" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">直接到 S3</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，然后触发您设置中定义的事件响应</font></font><code>events</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">！</font><font style="vertical-align: inherit;">这就是无服务器思维！</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-enabling-cors" class="anchor" aria-hidden="true" tabindex="-1" href="#enabling-cors"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">启用 CORS</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为 Zappa 应用程序启用 CORS（跨源资源共享）的最简单方法是在 Zappa 设置文件中设置</font></font><code>cors</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">并</font></font><code>true</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">更新，这相当于在 AWS API Gateway 控制台中按下“启用 CORS”按钮。</font><font style="vertical-align: inherit;">默认情况下此功能处于禁用状态，但您可能希望为从其他域等访问的 API 启用它。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您还可以直接在应用程序中直接处理 CORS。</font><font style="vertical-align: inherit;">您的 Web 框架可能会有一个扩展来执行此操作，例如</font></font><a href="https://github.com/ottoyiu/django-cors-headers"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">django-cors-headers</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或</font></font><a href="https://github.com/corydolphin/flask-cors"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Flask-CORS</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">使用这些将使您的代码更加可移植。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-large-projects" class="anchor" aria-hidden="true" tabindex="-1" href="#large-projects"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">大型项目</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AWS 目前将 Lambda zip 大小限制为 50 MB。</font><font style="vertical-align: inherit;">如果您的项目大于该值，请</font></font><code>slim_handler: true</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在您的</font></font><code>zappa_settings.json</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">. </font><font style="vertical-align: inherit;">在这种情况下，您的胖应用程序包将被替换为仅包含处理程序的小型包。</font><font style="vertical-align: inherit;">然后，处理程序文件在运行时从 S3 中拉取大型项目的其余部分！</font><font style="vertical-align: inherit;">大型项目的初始负载可能会增加启动开销，但在热 lambda 函数上差异应该很小。</font><font style="vertical-align: inherit;">请注意，这也会占用应用程序功能的存储空间。</font><font style="vertical-align: inherit;">请注意，AWS</font></font><a href="https://aws.amazon.com/blogs/compute/using-larger-ephemeral-storage-for-aws-lambda/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持</font></font></a><font style="vertical-align: inherit;"></font><code>/tmp</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">512 - 10240 MB 范围内的</font><font style="vertical-align: inherit;">自定义目录存储大小。</font><font style="vertical-align: inherit;">如果您的项目大于默认的 512 MB，</font><font style="vertical-align: inherit;">请使用</font></font><code>ephemeral_storage</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">in来调整您的需求。</font></font><code>zappa_settings.json</code><font style="vertical-align: inherit;"></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-enabling-bash-completion" class="anchor" aria-hidden="true" tabindex="-1" href="#enabling-bash-completion"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">启用 Bash 完成</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可以通过将以下内容添加到 .bashrc 来启用 Bash 补全：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>  <span class="pl-c1">eval</span> <span class="pl-s"><span class="pl-pds">"</span><span class="pl-s"><span class="pl-pds">$(</span>register-python-argcomplete zappa<span class="pl-pds">)</span></span><span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="  eval &quot;$(register-python-argcomplete zappa)&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><code>register-python-argcomplete</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">由 argcomplete Python 包提供。</font><font style="vertical-align: inherit;">如果此软件包安装在 virtualenv 中，则必须在那里运行该命令。</font><font style="vertical-align: inherit;">或者您可以执行：</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">activate-global-python-argcomplete --dest=-&gt; 文件</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该文件的内容应该来自于例如~/.bashrc。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-enabling-secure-endpoints-on-api-gateway" class="anchor" aria-hidden="true" tabindex="-1" href="#enabling-secure-endpoints-on-api-gateway"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 API Gateway 上启用安全端点</font></font></h3>
<h4 tabindex="-1" dir="auto"><a id="user-content-api-key" class="anchor" aria-hidden="true" tabindex="-1" href="#api-key"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">API密钥</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以使用该</font></font><code>api_key_required</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置为 API 网关的所有路由生成 API 密钥。</font><font style="vertical-align: inherit;">流程如下：</font></font></p>
<ol dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">部署/重新部署（更新不起作用）并记下</font><font style="vertical-align: inherit;">已创建密钥的</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">id</font></font></em><font style="vertical-align: inherit;"></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">转到 AWS 控制台 &gt; Amazon API Gateway 并
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">选择“API Keys”并找到键值</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例如</font></font><code>key_value</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">选择“使用计划”，创建新的使用计划并链接 API 密钥和 Zappa 为您创建的 API</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">发送一个请求，您将键值作为标头传递，</font></font><code>x-api-key</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以访问受限端点（例如使用curl:）</font></font><code>curl --header "x-api-key: key_value"</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">请注意，如果没有 x-api-key 标头，您将收到 403。</font></font></li>
</ol>
<h4 tabindex="-1" dir="auto"><a id="user-content-iam-policy" class="anchor" aria-hidden="true" tabindex="-1" href="#iam-policy"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">身份管理政策</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"></font><code>iam_authorization</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以通过将设置设置为</font><font style="vertical-align: inherit;">来在 API 上启用基于 IAM（v4 签名）的授权</font></font><code>true</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><a href="https://docs.aws.amazon.com/apigateway/latest/developerguide/api-gateway-iam-policy-examples.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">然后，您的 API 将需要签名请求，并且可以通过IAM 策略</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">控制访问</font><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">未签名的请求将收到 403 响应，无权访问 API 的请求者也会收到 403 响应。</font><font style="vertical-align: inherit;">启用此功能将覆盖授权者配置（见下文）。</font></font></p>
<h4 tabindex="-1" dir="auto"><a id="user-content-api-gateway-lambda-authorizers" class="anchor" aria-hidden="true" tabindex="-1" href="#api-gateway-lambda-authorizers"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">API 网关 Lambda 授权者</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您使用 Zappa 部署 API 端点，则可以利用</font></font><a href="https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-use-lambda-authorizer.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">API Gateway Lambda 授权程序</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来实现基于令牌的身份验证 - 您所需要做的就是提供一个函数来创建所需的输出，Zappa 会处理其余的事情。</font></font><a href="https://github.com/awslabs/aws-apigateway-lambda-authorizer-blueprints/blob/master/blueprints/python/api-gateway-authorizer-python.py"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AWS 实验室蓝图示例</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是该功能的良好开端</font><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您想知道如何使用授权者，以下是一些潜在的用例：</font></font></p>
<ol dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">调用 OAuth 提供商</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">内联解码 JWT 令牌</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在自我管理的数据库（例如 DynamoDB）中查找</font></font></li>
</ol>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Zappa 可以配置为调用代码内的函数来进行授权，或者调用其他一些现有的 lambda 函数（它允许您在多个 lambda 之间共享授权者）。</font></font><code>arn</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以通过指定或</font></font><code>function_name</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中的值</font><font style="vertical-align: inherit;">来控制行为</font></font><code>authorizer</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例如，要获取 Cognito 身份，请将其添加到</font></font><code>zappa_settings.yaml</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre>  <span class="pl-ent">context_header_mappings</span>:
    <span class="pl-ent">user_id</span>: <span class="pl-s">authorizer.user_id</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="  context_header_mappings:
    user_id: authorizer.user_id" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">现在可以像这样在 Flask 中访问它：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">from</span> <span class="pl-s1">flask</span> <span class="pl-k">import</span> <span class="pl-s1">request</span>

<span class="pl-en">@<span class="pl-en">route</span>(<span class="pl-s">'/hello'</span>)</span>
<span class="pl-k">def</span> <span class="pl-s1">hello_world</span>:
   <span class="pl-k">print</span>(<span class="pl-s1">request</span>.<span class="pl-s1">headers</span>.<span class="pl-s1">get</span>(<span class="pl-s">'user_id'</span>))</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="from flask import request

@route('/hello')
def hello_world:
   print(request.headers.get('user_id'))" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-cognito-user-pool-authorizer" class="anchor" aria-hidden="true" tabindex="-1" href="#cognito-user-pool-authorizer"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Cognito 用户池授权者</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您还可以通过添加以下内容来使用 AWS Cognito 用户池授权程序：</font></font></p>
<div class="highlight highlight-source-js notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-kos">{</span>
    <span class="pl-s">"authorizer"</span>: <span class="pl-kos">{</span>
        <span class="pl-s">"type"</span>: <span class="pl-s">"COGNITO_USER_POOLS"</span><span class="pl-kos">,</span>
        <span class="pl-s">"provider_arns"</span>: <span class="pl-kos">[</span>
            <span class="pl-s">"arn:aws:cognito-idp:{region}:{account_id}:userpool/{user_pool_id}"</span>
        <span class="pl-kos">]</span>
    <span class="pl-kos">}</span>
<span class="pl-kos">}</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="{
    &quot;authorizer&quot;: {
        &quot;type&quot;: &quot;COGNITO_USER_POOLS&quot;,
        &quot;provider_arns&quot;: [
            &quot;arn:aws:cognito-idp:{region}:{account_id}:userpool/{user_pool_id}&quot;
        ]
    }
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-api-gateway-resource-policy" class="anchor" aria-hidden="true" tabindex="-1" href="#api-gateway-resource-policy"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">API网关资源策略</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您还可以使用 API 网关资源策略。</font><font style="vertical-align: inherit;">IP白名单示例：</font></font></p>
<div class="highlight highlight-source-js notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-kos">{</span>
    <span class="pl-s">"Version"</span>: <span class="pl-s">"2012-10-17"</span><span class="pl-kos">,</span>
    <span class="pl-s">"Statement"</span>: <span class="pl-kos">[</span>
        <span class="pl-kos">{</span>
            <span class="pl-s">"Effect"</span>: <span class="pl-s">"Allow"</span><span class="pl-kos">,</span>
            <span class="pl-s">"Principal"</span>: <span class="pl-s">"*"</span><span class="pl-kos">,</span>
            <span class="pl-s">"Action"</span>: <span class="pl-s">"execute-api:Invoke"</span><span class="pl-kos">,</span>
            <span class="pl-s">"Resource"</span>: <span class="pl-s">"execute-api:/*"</span><span class="pl-kos">,</span>
            <span class="pl-s">"Condition"</span>: <span class="pl-kos">{</span>
                <span class="pl-s">"IpAddress"</span>: <span class="pl-kos">{</span>
                    <span class="pl-s">"aws:SourceIp"</span>: <span class="pl-kos">[</span>
                        <span class="pl-s">"1.2.3.4/32"</span>
                    <span class="pl-kos">]</span>
                <span class="pl-kos">}</span>
            <span class="pl-kos">}</span>
        <span class="pl-kos">}</span>
    <span class="pl-kos">]</span>
<span class="pl-kos">}</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="{
    &quot;Version&quot;: &quot;2012-10-17&quot;,
    &quot;Statement&quot;: [
        {
            &quot;Effect&quot;: &quot;Allow&quot;,
            &quot;Principal&quot;: &quot;*&quot;,
            &quot;Action&quot;: &quot;execute-api:Invoke&quot;,
            &quot;Resource&quot;: &quot;execute-api:/*&quot;,
            &quot;Condition&quot;: {
                &quot;IpAddress&quot;: {
                    &quot;aws:SourceIp&quot;: [
                        &quot;1.2.3.4/32&quot;
                    ]
                }
            }
        }
    ]
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-setting-environment-variables" class="anchor" aria-hidden="true" tabindex="-1" href="#setting-environment-variables"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置环境变量</font></font></h3>
<h4 tabindex="-1" dir="auto"><a id="user-content-local-environment-variables" class="anchor" aria-hidden="true" tabindex="-1" href="#local-environment-variables"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本地环境变量</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您想为部署阶段设置本地环境变量，您可以简单地在您的</font></font><code>zappa_settings.json</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<div class="highlight highlight-source-js notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-kos">{</span>
    <span class="pl-s">"dev"</span>: <span class="pl-kos">{</span>
        ...
        <span class="pl-s">"environment_variables"</span>: <span class="pl-kos">{</span>
            <span class="pl-s">"your_key"</span>: <span class="pl-s">"your_value"</span>
        <span class="pl-kos">}</span>
    <span class="pl-kos">}</span><span class="pl-kos">,</span>
    ...
<span class="pl-kos">}</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="{
    &quot;dev&quot;: {
        ...
        &quot;environment_variables&quot;: {
            &quot;your_key&quot;: &quot;your_value&quot;
        }
    },
    ...
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">然后，您可以通过以下方式在应用程序中访问这些内容：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">import</span> <span class="pl-s1">os</span>
<span class="pl-s1">your_value</span> <span class="pl-c1">=</span> <span class="pl-s1">os</span>.<span class="pl-s1">environ</span>.<span class="pl-en">get</span>(<span class="pl-s">'your_key'</span>)</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="import os
your_value = os.environ.get('your_key')" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您的项目需要了解部署到的环境类型，您还可以获取</font></font><code>SERVERTYPE</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">(AWS Lambda)、</font></font><code>FRAMEWORK</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">(Zappa)、</font></font><code>PROJECT</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">(您的项目名称) 和</font></font><code>STAGE</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">( </font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">dev</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">production</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">等) 变量随时。</font></font></p>
<h4 tabindex="-1" dir="auto"><a id="user-content-remote-aws-environment-variables" class="anchor" aria-hidden="true" tabindex="-1" href="#remote-aws-environment-variables"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">远程AWS环境变量</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您想使用本机 AWS Lambda 环境变量，您可以使用</font></font><code>aws_environment_variables</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置设置。</font><font style="vertical-align: inherit;">这些非常有用，因为您可以在运行时通过 AWS Lambda 控制台或 cli 轻松更改它们。</font><font style="vertical-align: inherit;">它们对于存储敏感凭据和利用环境变量的 KMS 加密也很有用。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在开发过程中，您可以将 Zappa 定义的变量添加到本地运行的应用程序中，例如，使用以下内容（对于 Django，请管理.py）。</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">import</span> <span class="pl-s1">json</span>
<span class="pl-k">import</span> <span class="pl-s1">os</span>

<span class="pl-k">if</span> <span class="pl-s1">os</span>.<span class="pl-s1">environ</span>.<span class="pl-en">get</span>(<span class="pl-s">'AWS_LAMBDA_FUNCTION_NAME'</span>) <span class="pl-c1">is</span> <span class="pl-c1">None</span>: <span class="pl-c"># Ensures app is NOT running on Lambda</span>
    <span class="pl-s1">json_data</span> <span class="pl-c1">=</span> <span class="pl-en">open</span>(<span class="pl-s">'zappa_settings.json'</span>)
    <span class="pl-s1">env_vars</span> <span class="pl-c1">=</span> <span class="pl-s1">json</span>.<span class="pl-en">load</span>(<span class="pl-s1">json_data</span>)[<span class="pl-s">'dev'</span>][<span class="pl-s">'environment_variables'</span>]
    <span class="pl-s1">os</span>.<span class="pl-s1">environ</span>.<span class="pl-en">update</span>(<span class="pl-s1">env_vars</span>)</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="import json
import os

if os.environ.get('AWS_LAMBDA_FUNCTION_NAME') is None: # Ensures app is NOT running on Lambda
    json_data = open('zappa_settings.json')
    env_vars = json.load(json_data)['dev']['environment_variables']
    os.environ.update(env_vars)" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-remote-environment-variables" class="anchor" aria-hidden="true" tabindex="-1" href="#remote-environment-variables"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">远程环境变量</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您在 Zappa 外部设置的任何环境变量（通过 AWS Lambda 控制台或 cli）将保持运行时的原样</font></font><code>update</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，除非它们也在 中</font></font><code>aws_environment_variables</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，在这种情况下，远程值将被设置文件中的值覆盖。</font><font style="vertical-align: inherit;">如果您使用 KMS 加密的 AWS 环境变量，则可以在</font></font><code>aws_kms_key_arn</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置中设置 KMS 密钥 ARN。</font><font style="vertical-align: inherit;">在这种情况下，请确保您设置的值已加密。</font></font></p>
<p dir="auto"><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注意：如果您依赖这些以及</font></font><code>environment_variables</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，并且具有相同的键名称，那么 中 的键名称</font></font><code>environment_variables</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将优先，因为它们被注入到 lambda 处理程序中。</font></font></em></p>
<h4 tabindex="-1" dir="auto"><a id="user-content-remote-environment-variables-via-an-s3-file" class="anchor" aria-hidden="true" tabindex="-1" href="#remote-environment-variables-via-an-s3-file"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">远程环境变量（通过 S3 文件）</font></font></h4>
<p dir="auto"><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 AWS 为 Lambda 引入本机环境变量（通过控制台和 cli）之前，S3 远程环境变量已添加到 Zappa。</font><font style="vertical-align: inherit;">在走这条路线之前，请检查上述内容是否对您的用例更有意义。</font></font></em></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您想使用远程环境变量来配置您的应用程序（这对于敏感凭证等内容特别有用），您可以创建一个文件并将其放置在您的 Zappa 应用程序可以访问的 S3 存储桶中。</font><font style="vertical-align: inherit;">为此，请添加</font></font><code>remote_env</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">键添加到 zappa_settings 中，指向包含平面 JSON 对象的文件，以便每当新的 lambda 实例启动时，该对象上的每个键值对都将被设置为环境变量和值。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例如，为了确保您的应用程序可以访问数据库凭据而不将其存储在版本控制中，您可以使用连接字符串将文件添加到 S3，并使用配置设置将其加载到 lambda 环境中</font></font><code>remote_env</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">super-secret-config.json（上传到 my-config-bucket）：</font></font></p>
<div class="highlight highlight-source-js notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-kos">{</span>
    <span class="pl-s">"DB_CONNECTION_STRING"</span>: <span class="pl-s">"super-secret:database"</span>
<span class="pl-kos">}</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="{
    &quot;DB_CONNECTION_STRING&quot;: &quot;super-secret:database&quot;
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">zappa_settings.json：</font></font></p>
<div class="highlight highlight-source-js notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-kos">{</span>
    <span class="pl-s">"dev"</span>: <span class="pl-kos">{</span>
        ...
        <span class="pl-s">"remote_env"</span>: <span class="pl-s">"s3://my-config-bucket/super-secret-config.json"</span><span class="pl-kos">,</span>
    <span class="pl-kos">}</span><span class="pl-kos">,</span>
    ...
<span class="pl-kos">}</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="{
    &quot;dev&quot;: {
        ...
        &quot;remote_env&quot;: &quot;s3://my-config-bucket/super-secret-config.json&quot;,
    },
    ...
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">现在在您的应用程序中您可以使用：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">import</span> <span class="pl-s1">os</span>
<span class="pl-s1">db_string</span> <span class="pl-c1">=</span> <span class="pl-s1">os</span>.<span class="pl-s1">environ</span>.<span class="pl-en">get</span>(<span class="pl-s">'DB_CONNECTION_STRING'</span>)</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="import os
db_string = os.environ.get('DB_CONNECTION_STRING')" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-api-gateway-context-variables" class="anchor" aria-hidden="true" tabindex="-1" href="#api-gateway-context-variables"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">API网关上下文变量</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您想要将 API Gateway 上下文变量 ( </font></font><a href="http://docs.aws.amazon.com/apigateway/latest/developerguide/api-gateway-mapping-template-reference.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://docs.aws.amazon.com/apigateway/latest/developerguide/api-gateway-mapping-template-reference.html</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ) 映射到 HTTP 标头，您可以设置映射于</font></font><code>zappa_settings.json</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<div class="highlight highlight-source-js notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-kos">{</span>
    <span class="pl-s">"dev"</span>: <span class="pl-kos">{</span>
        ...
        <span class="pl-s">"context_header_mappings"</span>: <span class="pl-kos">{</span>
            <span class="pl-s">"HTTP_header_name"</span>: <span class="pl-s">"API_Gateway_context_variable"</span>
        <span class="pl-kos">}</span>
    <span class="pl-kos">}</span><span class="pl-kos">,</span>
    ...
<span class="pl-kos">}</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="{
    &quot;dev&quot;: {
        ...
        &quot;context_header_mappings&quot;: {
            &quot;HTTP_header_name&quot;: &quot;API_Gateway_context_variable&quot;
        }
    },
    ...
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例如，如果您想要将 $context.identity.cognitoIdentityId 变量公开为 HTTP 标头 CognitoIdentityId，并将 $context.stage 公开为 APIStage，则需要：</font></font></p>
<div class="highlight highlight-source-js notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-kos">{</span>
    <span class="pl-s">"dev"</span>: <span class="pl-kos">{</span>
        ...
        <span class="pl-s">"context_header_mappings"</span>: <span class="pl-kos">{</span>
            <span class="pl-s">"CognitoIdentityId"</span>: <span class="pl-s">"identity.cognitoIdentityId"</span><span class="pl-kos">,</span>
            <span class="pl-s">"APIStage"</span>: <span class="pl-s">"stage"</span>
        <span class="pl-kos">}</span>
    <span class="pl-kos">}</span><span class="pl-kos">,</span>
    ...
<span class="pl-kos">}</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="{
    &quot;dev&quot;: {
        ...
        &quot;context_header_mappings&quot;: {
            &quot;CognitoIdentityId&quot;: &quot;identity.cognitoIdentityId&quot;,
            &quot;APIStage&quot;: &quot;stage&quot;
        }
    },
    ...
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-catching-unhandled-exceptions" class="anchor" aria-hidden="true" tabindex="-1" href="#catching-unhandled-exceptions"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">捕获未处理的异常</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认情况下，如果</font><font style="vertical-align: inherit;">代码中发生</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">未处理的异常，Zappa 只会将堆栈跟踪打印到 CloudWatch 日志中。</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您希望使用外部报告工具来记录这些异常，则可以使用</font></font><code>exception_handler</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置选项。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">zappa_settings.json：</font></font></p>
<div class="highlight highlight-source-js notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-kos">{</span>
    <span class="pl-s">"dev"</span>: <span class="pl-kos">{</span>
        ...
        <span class="pl-s">"exception_handler"</span>: <span class="pl-s">"your_module.unhandled_exceptions"</span><span class="pl-kos">,</span>
    <span class="pl-kos">}</span><span class="pl-kos">,</span>
    ...
<span class="pl-kos">}</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="{
    &quot;dev&quot;: {
        ...
        &quot;exception_handler&quot;: &quot;your_module.unhandled_exceptions&quot;,
    },
    ...
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该函数必须接受三个参数：异常、事件和上下文：</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">你的模块.py</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">def</span> <span class="pl-en">unhandled_exceptions</span>(<span class="pl-s1">e</span>, <span class="pl-s1">event</span>, <span class="pl-s1">context</span>):
    <span class="pl-en">send_to_raygun</span>(<span class="pl-s1">e</span>, <span class="pl-s1">event</span>)  <span class="pl-c"># gather data you need and send</span>
    <span class="pl-k">return</span> <span class="pl-c1">True</span> <span class="pl-c"># Prevent invocation retry</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="def unhandled_exceptions(e, event, context):
    send_to_raygun(e, event)  # gather data you need and send
    return True # Prevent invocation retry" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您的应用程序中可能仍然需要类似的异常处理程序，这只是捕获 Zappa/WSGI 层发生的异常（通常是基于事件的调用、错误配置的设置、错误的 Lambda 包和权限问题）的一种方法。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认情况下，如果引发异常，AWS Lambda 将尝试重试基于事件（非 API 网关，例如 CloudWatch）的调用。</font><font style="vertical-align: inherit;">但是，您可以通过返回 True 来防止这种情况，如上例所示，这样 Zappa 就不会重新引发未捕获的异常，从而阻止 AWS Lambda 重试当前调用。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-using-custom-aws-iam-roles-and-policies" class="anchor" aria-hidden="true" tabindex="-1" href="#using-custom-aws-iam-roles-and-policies"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用自定义 AWS IAM 角色和策略</font></font></h3>
<h4 tabindex="-1" dir="auto"><a id="user-content-custom-aws-iam-roles-and-policies-for-deployment" class="anchor" aria-hidden="true" tabindex="-1" href="#custom-aws-iam-roles-and-policies-for-deployment"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于部署的自定义 AWS IAM 角色和策略</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以</font><font style="vertical-align: inherit;">通过定义设置来指定用于部署 Zappa 应用程序的</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本地</font></font></em><font style="vertical-align: inherit;"></font><code>profile_name</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置文件，该设置将与您的 AWS 凭证文件中的配置文件相对应。</font></font></p>
<h4 tabindex="-1" dir="auto"><a id="user-content-custom-aws-iam-roles-and-policies-for-execution" class="anchor" aria-hidden="true" tabindex="-1" href="#custom-aws-iam-roles-and-policies-for-execution"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于执行的自定义 AWS IAM 角色和策略</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Zappa 创建的用于执行 Lambda 的默认 IAM 策略非常宽松。</font><font style="vertical-align: inherit;">它授予对 CloudWatch、S3、Kinesis、SNS、SQS、DynamoDB 和 Route53 类型的所有资源的所有操作的访问权限；</font><font style="vertical-align: inherit;">lambda:所有Lambda资源的InvokeFunction；</font><font style="vertical-align: inherit;">放入所有 X-Ray 资源；</font><font style="vertical-align: inherit;">以及对所有 EC2 资源的所有网络接口操作。</font><font style="vertical-align: inherit;">虽然这允许大多数 Lambda 无需额外权限即可正常工作，但对于大多数持续集成管道或生产部署来说，这通常不是可接受的一组权限。</font><font style="vertical-align: inherit;">相反，您可能需要手动管理您的 IAM 策略。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要手动定义 Lambda 执行角色的策略，您必须将</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">manage_roles</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置为 false 并在 Zappa 设置文件中</font><font style="vertical-align: inherit;">定义</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">role_name</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">role_arn 。</font></font></em><font style="vertical-align: inherit;"></font></p>
<div class="highlight highlight-source-js notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-kos">{</span>
    <span class="pl-s">"dev"</span>: <span class="pl-kos">{</span>
        ...
        <span class="pl-s">"manage_roles"</span>: <span class="pl-c1">false</span><span class="pl-kos">,</span> <span class="pl-c">// Disable Zappa client managing roles.</span>
        <span class="pl-s">"role_name"</span>: <span class="pl-s">"MyLambdaRole"</span><span class="pl-kos">,</span> <span class="pl-c">// Name of your Zappa execution role. Optional, default: &lt;project_name&gt;-&lt;env&gt;-ZappaExecutionRole.</span>
        <span class="pl-s">"role_arn"</span>: <span class="pl-s">"arn:aws:iam::12345:role/app-ZappaLambdaExecutionRole"</span><span class="pl-kos">,</span> <span class="pl-c">// ARN of your Zappa execution role. Optional.</span>
        ...
    <span class="pl-kos">}</span><span class="pl-kos">,</span>
    ...
<span class="pl-kos">}</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="{
    &quot;dev&quot;: {
        ...
        &quot;manage_roles&quot;: false, // Disable Zappa client managing roles.
        &quot;role_name&quot;: &quot;MyLambdaRole&quot;, // Name of your Zappa execution role. Optional, default: <project_name>-<env>-ZappaExecutionRole.
        &quot;role_arn&quot;: &quot;arn:aws:iam::12345:role/app-ZappaLambdaExecutionRole&quot;, // ARN of your Zappa execution role. Optional.
        ...
    },
    ...
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关 Zappa 部署所需的最低策略要求的持续讨论</font></font><a href="https://github.com/Miserlou/Zappa/issues/244" data-hovercard-type="issue" data-hovercard-url="/Miserlou/Zappa/issues/244/hovercard"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可以在此处找到</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">管理这些权利的更强大的解决方案可能很快就会实施。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要将权限添加到默认 Zappa 执行策略，请使用以下</font></font><code>extra_permissions</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置：</font></font></p>
<div class="highlight highlight-source-js notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-kos">{</span>
    <span class="pl-s">"dev"</span>: <span class="pl-kos">{</span>
        ...
        <span class="pl-s">"extra_permissions"</span>: <span class="pl-kos">[</span><span class="pl-kos">{</span> <span class="pl-c">// Attach any extra permissions to this policy.</span>
            <span class="pl-s">"Effect"</span>: <span class="pl-s">"Allow"</span><span class="pl-kos">,</span>
            <span class="pl-s">"Action"</span>: <span class="pl-kos">[</span><span class="pl-s">"rekognition:*"</span><span class="pl-kos">]</span><span class="pl-kos">,</span> <span class="pl-c">// AWS Service ARN</span>
            <span class="pl-s">"Resource"</span>: <span class="pl-s">"*"</span>
        <span class="pl-kos">}</span><span class="pl-kos">]</span>
    <span class="pl-kos">}</span><span class="pl-kos">,</span>
    ...
<span class="pl-kos">}</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="{
    &quot;dev&quot;: {
        ...
        &quot;extra_permissions&quot;: [{ // Attach any extra permissions to this policy.
            &quot;Effect&quot;: &quot;Allow&quot;,
            &quot;Action&quot;: [&quot;rekognition:*&quot;], // AWS Service ARN
            &quot;Resource&quot;: &quot;*&quot;
        }]
    },
    ...
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-aws-x-ray" class="anchor" aria-hidden="true" tabindex="-1" href="#aws-x-ray"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AWS X射线</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Zappa 可以通过配置设置为您的函数</font><font style="vertical-align: inherit;">启用</font></font><a href="https://aws.amazon.com/xray/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AWS X-Ray支持：</font></font></a><font style="vertical-align: inherit;"></font></p>
<div class="highlight highlight-source-js notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-kos">{</span>
    <span class="pl-s">"dev"</span>: <span class="pl-kos">{</span>
        ...
        <span class="pl-s">"xray_tracing"</span>: <span class="pl-c1">true</span>
    <span class="pl-kos">}</span><span class="pl-kos">,</span>
    ...
<span class="pl-kos">}</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="{
    &quot;dev&quot;: {
        ...
        &quot;xray_tracing&quot;: true
    },
    ...
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这将在 Lambda 函数上启用它，并允许您使用 X-Ray 检测代码。</font><font style="vertical-align: inherit;">例如，使用 Flask：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">from</span> <span class="pl-s1">aws_xray_sdk</span>.<span class="pl-s1">core</span> <span class="pl-k">import</span> <span class="pl-s1">xray_recorder</span>

<span class="pl-s1">app</span> <span class="pl-c1">=</span> <span class="pl-v">Flask</span>(<span class="pl-s1">__name__</span>)

<span class="pl-s1">xray_recorder</span>.<span class="pl-en">configure</span>(<span class="pl-s1">service</span><span class="pl-c1">=</span><span class="pl-s">'my_app_name'</span>)

<span class="pl-en">@<span class="pl-en">route</span>(<span class="pl-s">'/hello'</span>)</span>
<span class="pl-en">@<span class="pl-s1">xray_recorder</span>.<span class="pl-en">capture</span>(<span class="pl-s">'hello'</span>)</span>
<span class="pl-k">def</span> <span class="pl-s1">hello_world</span>:
    <span class="pl-k">return</span> '<span class="pl-v">Hello</span>'</pre><div class="zeroclipboard-container">
   

xray_recorder.configure(service='my_app_name')

@route('/hello')
@xray_recorder.capture('hello')
def hello_world:
    return 'Hello'" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"></font><code>xray_recorder.begin_subsegment('subsegment_name')</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以使用捕获装饰器在函数周围或</font></font><code>xray_recorder.end_subsegment()</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">函数内</font><font style="vertical-align: inherit;">创建子段。</font><font style="vertical-align: inherit;">Python 的官方</font></font><a href="http://docs.aws.amazon.com/xray-sdk-for-python/latest/reference/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">X-Ray 文档</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提供了有关如何在代码中使用它的更多信息。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请注意，您可以在代码中创建子段，但如果您尝试创建段，则会引发异常，因为它是</font></font><a href="https://github.com/aws/aws-xray-sdk-python/issues/2" data-hovercard-type="issue" data-hovercard-url="/aws/aws-xray-sdk-python/issues/2/hovercard"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">由 lambda worker 创建的</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">这也意味着，如果您使用 Flask，则不得使用</font></font><a href="https://docs.aws.amazon.com/xray/latest/devguide/xray-sdk-python-middleware.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档建议的 XRayMiddleware</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-globally-available-server-less-architectures" class="anchor" aria-hidden="true" tabindex="-1" href="#globally-available-server-less-architectures"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">全球可用的无服务器架构</font></font></h3>
<p align="center" dir="auto">
  <a href="https://htmlpreview.github.io/?https://github.com/Miserlou/Talks/blob/master/serverless-london/global.html#0" rel="nofollow"><img src="https://camo.githubusercontent.com/8786ab0eec9f121174752d4470e43dfaf94b27f9b9de360d79826acf90370217/687474703a2f2f692e696d6775722e636f6d2f6f5236315161752e706e67" alt="全球 Zappa 拖鞋" data-canonical-src="http://i.imgur.com/oR61Qau.png" style="max-width: 100%;"></a>
</p>
<p align="center" dir="auto">
  <i><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">单击查看</font></font><a href="https://htmlpreview.github.io/?https://github.com/Miserlou/Talks/blob/master/serverless-london/global.html#0" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">伦敦 ServerlessConf 的幻灯片</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">！</font></font></i>
</p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在此</font></font><code>init</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">过程中，您将可以选择“全球”部署您的应用程序。</font><font style="vertical-align: inherit;">这将允许您同时将应用程序部署到所有可用的 AWS 区域，以提供一致的全球速度、增强的冗余、数据隔离和法律合规性。</font><font style="vertical-align: inherit;">您还可以选择仅部署到“主要”位置，即</font></font><code>-1</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">名称中包含的 AWS 区域。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要了解有关这些功能的更多信息，请参阅</font><font style="vertical-align: inherit;">伦敦 ServerlessConf 的</font></font><a href="https://htmlpreview.github.io/?https://github.com/Miserlou/Talks/blob/master/serverless-london/global.html#0" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这些幻灯片。</font></font></a><font style="vertical-align: inherit;"></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-raising-aws-service-limits" class="anchor" aria-hidden="true" tabindex="-1" href="#raising-aws-service-limits"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提高 AWS 服务限制</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AWS 开箱即用，为您的函数设置</font></font><a href="http://docs.aws.amazon.com/lambda/latest/dg/limits.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1000 个并发执行</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的限制。</font><font style="vertical-align: inherit;">如果您开始违反这些限制，您可能会开始看到类似的错误</font></font><code>ClientError: An error occurred (LimitExceededException) when calling the PutTargets.."</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或类似的内容。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为了避免这种情况，您可以向 Amazon 提交</font></font><a href="https://console.aws.amazon.com/support/home#/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">服务票证</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，将限制提高到您可能需要的数万个并发执行。</font><font style="vertical-align: inherit;">这是亚马逊相当常见的做法，旨在防止您意外创建极其昂贵的错误报告。</font><font style="vertical-align: inherit;">因此，在提高服务限制之前，请确保您没有任何恶意脚本，这些脚本可能会意外创建数万个您不想付费的并行执行。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-dead-letter-queues" class="anchor" aria-hidden="true" tabindex="-1" href="#dead-letter-queues"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">死信队列</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您想利用</font></font><a href="http://docs.aws.amazon.com/lambda/latest/dg/dlq.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AWS Lambda 的死信队列功能，</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">只需将键</font></font><code>dead_letter_arn</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（值为完整的 ARN）添加到您的</font></font><code>zappa_settings.json</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您必须已创建相应的 SNS/SQS 主题/队列，并且必须已为 Lambda 函数执行角色配置对 DLQ 资源的读取/发布/sendMessage 访问权限。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-unique-package-id" class="anchor" aria-hidden="true" tabindex="-1" href="#unique-package-id"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">唯一的包裹ID</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"></font><code>package_info.json</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为了监控不同的部署，应用程序包的根目录中</font><font style="vertical-align: inherit;">提供了每个包的唯一 UUID 。</font><font style="vertical-align: inherit;">您可以使用此信息或此文件的哈希值来执行以下操作：跟踪不同部署之间的错误、监控部署状态以及 Sentry 和 New Relic 等服务上的其他操作。</font><font style="vertical-align: inherit;">该包裹将包含：</font></font></p>
<div class="highlight highlight-source-json notranslate position-relative overflow-auto" dir="auto"><pre>{
  <span class="pl-ent">"build_platform"</span>: <span class="pl-s"><span class="pl-pds">"</span>darwin<span class="pl-pds">"</span></span>,
  <span class="pl-ent">"build_user"</span>: <span class="pl-s"><span class="pl-pds">"</span>frank<span class="pl-pds">"</span></span>,
  <span class="pl-ent">"build_time"</span>: <span class="pl-s"><span class="pl-pds">"</span>1509732511<span class="pl-pds">"</span></span>,
  <span class="pl-ent">"uuid"</span>: <span class="pl-s"><span class="pl-pds">"</span>9c2df9e6-30f4-4c0a-ac4d-4ecb51831a74<span class="pl-pds">"</span></span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="{
  &quot;build_platform&quot;: &quot;darwin&quot;,
  &quot;build_user&quot;: &quot;frank&quot;,
  &quot;build_time&quot;: &quot;1509732511&quot;,
  &quot;uuid&quot;: &quot;9c2df9e6-30f4-4c0a-ac4d-4ecb51831a74&quot;
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-application-load-balancer-event-source" class="anchor" aria-hidden="true" tabindex="-1" href="#application-load-balancer-event-source"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">应用程序负载均衡器事件源</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Zappa 可用于处理由应用程序负载均衡器 (ALB) 触发的事件。</font><font style="vertical-align: inherit;">这在某些情况下很有用：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">由于 API Gateway 在超时前有 30 秒的硬限制，因此您可以使用 ALB 来处理运行时间较长的请求。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">API网关按请求计费；</font><font style="vertical-align: inherit;">因此，高吞吐量服务的成本可能会变得过高。</font><font style="vertical-align: inherit;">如果您预计 Lambda 会有大量流量，那么 ALB 定价模型在财务上更有意义。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ALB 可以放置在 VPC 内，这对于私有终端节点来说可能比使用 API Gateway 的私有模型（使用 AWS PrivateLink）更有意义。</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">与 API Gateway 一样，Zappa 可以自动为您配置 ALB 资源。</font><font style="vertical-align: inherit;">您需要将以下内容添加到您的</font></font><code>zappa_settings</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>"alb_enabled": true,
"alb_vpc_config": {
    "CertificateArn": "arn:aws:acm:us-east-1:[your-account-id]:certificate/[certificate-id]",
    "SubnetIds": [
        // Here, you'll want to provide a list of subnets for your ALB, eg. 'subnet-02a58266'
    ],
    "SecurityGroupIds": [
        // And here, a list of security group IDs, eg. 'sg-fbacb791'
    ]
}
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="&quot;alb_enabled&quot;: true,
&quot;alb_vpc_config&quot;: {
    &quot;CertificateArn&quot;: &quot;arn:aws:acm:us-east-1:[your-account-id]:certificate/[certificate-id]&quot;,
    &quot;SubnetIds&quot;: [
        // Here, you'll want to provide a list of subnets for your ALB, eg. 'subnet-02a58266'
    ],
    &quot;SecurityGroupIds&quot;: [
        // And here, a list of security group IDs, eg. 'sg-fbacb791'
    ]
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关使用 ALB 作为 Lambda 事件源的更多信息，请参阅</font></font><a href="https://docs.aws.amazon.com/elasticloadbalancing/latest/application/lambda-functions.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此处</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">重要提示</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：目前，Zappa 将为一个负载均衡器提供一个 lambda，这意味着</font></font><code>base_path</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">当前不支持与 ALB 配置一起使用。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-endpoint-configuration" class="anchor" aria-hidden="true" tabindex="-1" href="#endpoint-configuration"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">端点配置</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">API网关可以配置为只能在VPC中访问。</font><font style="vertical-align: inherit;">为了启用此功能；</font></font><a href="https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-private-apis.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置您的 VPC 以支持</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">API 网关，然后设置</font></font><code>endpoint_configuration</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">并</font></font><code>PRIVATE</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置资源策略。</font><font style="vertical-align: inherit;">关于此的注释；</font><font style="vertical-align: inherit;">如果您使用的是专用端点，Zappa 将无法判断 API 在部署或更新时是否返回成功的状态代码，因此您必须手动检查它以确保您的设置正常工作。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关端点配置选项的完整列表，请参阅</font></font><a href="https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-properties-apigateway-restapi-endpointconfiguration.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">API Gateway EndpointConfiguration 文档</font></font></a></p>
<h4 tabindex="-1" dir="auto"><a id="user-content-example-private-api-gateway-configuration" class="anchor" aria-hidden="true" tabindex="-1" href="#example-private-api-gateway-configuration"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">私有 API 网关配置示例</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">zappa_settings.json：</font></font></p>
<div class="highlight highlight-source-json notranslate position-relative overflow-auto" dir="auto"><pre>{
    <span class="pl-ent">"dev"</span>: {
        <span class="pl-ii">...</span>
        <span class="pl-ent">"endpoint_configuration"</span>: [<span class="pl-s"><span class="pl-pds">"</span>PRIVATE<span class="pl-pds">"</span></span>],
        <span class="pl-ent">"apigateway_policy"</span>: <span class="pl-s"><span class="pl-pds">"</span>apigateway_resource_policy.json<span class="pl-pds">"</span></span>,
        <span class="pl-ii">...</span>
    },
    <span class="pl-ii">...</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="{
    &quot;dev&quot;: {
        ...
        &quot;endpoint_configuration&quot;: [&quot;PRIVATE&quot;],
        &quot;apigateway_policy&quot;: &quot;apigateway_resource_policy.json&quot;,
        ...
    },
    ...
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">apigateway_resource_policy.json：</font></font></p>
<div class="highlight highlight-source-json notranslate position-relative overflow-auto" dir="auto"><pre>{
    <span class="pl-ent">"Version"</span>: <span class="pl-s"><span class="pl-pds">"</span>2012-10-17<span class="pl-pds">"</span></span>,
    <span class="pl-ent">"Statement"</span>: [
        {
            <span class="pl-ent">"Effect"</span>: <span class="pl-s"><span class="pl-pds">"</span>Deny<span class="pl-pds">"</span></span>,
            <span class="pl-ent">"Principal"</span>: <span class="pl-s"><span class="pl-pds">"</span>*<span class="pl-pds">"</span></span>,
            <span class="pl-ent">"Action"</span>: <span class="pl-s"><span class="pl-pds">"</span>execute-api:Invoke<span class="pl-pds">"</span></span>,
            <span class="pl-ent">"Resource"</span>: <span class="pl-s"><span class="pl-pds">"</span>execute-api:/*<span class="pl-pds">"</span></span>,
            <span class="pl-ent">"Condition"</span>: {
                <span class="pl-ent">"StringNotEquals"</span>: {
                    <span class="pl-ent">"aws:sourceVpc"</span>: <span class="pl-s"><span class="pl-pds">"</span>{{vpcID}}<span class="pl-pds">"</span></span> <span class="pl-ii">// UPDATE ME</span>
                }
            }
        },
        {
            <span class="pl-ent">"Effect"</span>: <span class="pl-s"><span class="pl-pds">"</span>Allow<span class="pl-pds">"</span></span>,
            <span class="pl-ent">"Principal"</span>: <span class="pl-s"><span class="pl-pds">"</span>*<span class="pl-pds">"</span></span>,
            <span class="pl-ent">"Action"</span>: <span class="pl-s"><span class="pl-pds">"</span>execute-api:Invoke<span class="pl-pds">"</span></span>,
            <span class="pl-ent">"Resource"</span>: <span class="pl-s"><span class="pl-pds">"</span>execute-api:/*<span class="pl-pds">"</span></span>
        }
    ]
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="{
    &quot;Version&quot;: &quot;2012-10-17&quot;,
    &quot;Statement&quot;: [
        {
            &quot;Effect&quot;: &quot;Deny&quot;,
            &quot;Principal&quot;: &quot;*&quot;,
            &quot;Action&quot;: &quot;execute-api:Invoke&quot;,
            &quot;Resource&quot;: &quot;execute-api:/*&quot;,
            &quot;Condition&quot;: {
                &quot;StringNotEquals&quot;: {
                    &quot;aws:sourceVpc&quot;: &quot;{{vpcID}}&quot; // UPDATE ME
                }
            }
        },
        {
            &quot;Effect&quot;: &quot;Allow&quot;,
            &quot;Principal&quot;: &quot;*&quot;,
            &quot;Action&quot;: &quot;execute-api:Invoke&quot;,
            &quot;Resource&quot;: &quot;execute-api:/*&quot;
        }
    ]
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-cold-starts-experimental" class="anchor" aria-hidden="true" tabindex="-1" href="#cold-starts-experimental"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">冷启动（实验性）</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Lambda 可能会提供比冷启动初始化期间配置的额外资源。</font><font style="vertical-align: inherit;">设置</font></font><code>INSTANTIATE_LAMBDA_HANDLER_ON_IMPORT=True</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为在导入时实例化 lambda 处理程序。</font><font style="vertical-align: inherit;">这是一项实验性功能 - 如果启动时间很关键，请考虑使用预置并发。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-zappa-guides" class="anchor" aria-hidden="true" tabindex="-1" href="#zappa-guides"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">扎帕指南</font></font></h2>
<ul dir="auto">
<li><a href="https://www.youtube.com/watch?v=plUrbPN0xc8&amp;feature=youtu.be" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Django-Zappa 教程（截屏视频）</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><a href="https://serverlesscode.com/post/zappa-wsgi-for-python/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Django-Zappa，第 1 部分</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><a href="https://serverlesscode.com/post/zappa-wsgi-for-python-pt-2/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Django-Zappa，第 2 部分：VPC</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><a href="https://gun.io/blog/serverless-microservices-with-zappa-and-flask/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Zappa 和 Flask 构建无服务器微服务</font></font></a></li>
<li><a href="http://qiita.com/satoshi_iwashita/items/505492193317819772c7" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Zappa で Hello World するまで（日语）</font></font></a></li>
<li><a href="https://jinwright.net/how-deploy-serverless-wsgi-app-using-zappa/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何使用 CloudFront、RDS 和 VPC 部署 Zappa</font></font></a></li>
<li><a href="http://blog.stratospark.com/secure-serverless-file-uploads-with-aws-lambda-s3-zappa.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 AWS Lambda、S3 和 Zappa 保护“无服务器”文件上传</font></font></a></li>
<li><a href="https://docs.google.com/presentation/d/1aYeOMgQl4V_fFgT5VNoycdXtob1v6xVUWlyxoTEiTw0/edit#slide=id.p" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Zappa、CloudFront、RDS 和 VPC 部署无服务器 WSGI 应用程序</font></font></a></li>
<li><a href="https://developer.amazon.com/blogs/post/8e8ad73a-99e9-4c0f-a7b3-60f92287b0bf/New-Alexa-Tutorial-Deploy-Flask-Ask-Skills-to-AWS-Lambda-with-Zappa" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AWS：使用 Flask-Ask 和 Zappa 部署 Alexa Ask 技能</font></font></a></li>
<li><a href="https://edgarroman.github.io/zappa-django-guide/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将 Django 与 Zappa 结合使用的指南</font></font></a></li>
<li><a href="https://seancoates.com/blogs/zappa-and-lambci/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Zappa 和 LambCI</font></font></a></li>
<li><a href="https://medium.com/99serverless/building-a-serverless-image-processing-saas-9ef68b594076" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Zappa 构建无服务器图像处理 SaaS</font></font></a></li>
<li><a href="https://renzo.lucioni.xyz/serverless-slash-commands-with-python/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Python 和 Zappa 的无服务器 Slack Slash 命令</font></font></a></li>
<li><a href="https://www.contentful.com/blog/2018/03/07/bringing-tokusatsu-to-aws-using-python-flask-zappa-and-contentful/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Python、Flask、Zappa 和 Contentful 将 Tokusatsu 引入 AWS</font></font></a></li>
<li><a href="https://www.slideshare.net/YunSeopSong/zappa-serverless-microservice-94410308/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AWS 峰会 2018 首尔 - Zappa와 함께하는 无服务器微服务</font></font></a></li>
<li><a href="https://github.com/PacktPublishing/Building-Serverless-Python-Web-Services-with-Zappa"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">书籍 - 使用 Zappa 构建无服务器 Python Web 服务</font></font></a></li>
<li><a href="http://free_zed.gitlab.io/articles/2019/11/vider-sa-flask-dans-une-lambda/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Vider sa Bottle dans une lambda</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> [法语]</font></font></li>
<li><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">你的向导在吗？</font></font></em></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-zappa-in-the-press" class="anchor" aria-hidden="true" tabindex="-1" href="#zappa-in-the-press"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">扎帕在媒体上</font></font></h2>
<ul dir="auto">
<li><em><a href="http://www.infoworld.com/article/3031665/application-development/zappa-serves-python-web-apps-minus-the-servers.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Zappa 为 Python 提供服务，但无需服务器</font></font></a></em></li>
<li><em><a href="http://computersweden.idg.se/2.2683/1.649895/zappa-lyfter-python" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Zappa lyfter 服务器采用 Python 的应用程序</font></font></a></em></li>
<li><em><a href="https://serverlesscode.com/post/rich-jones-interview-django-zappa/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">采访：里奇·琼斯 (Rich Jones) 的 Zappa</font></font></a></em></li>
<li><a href="https://tryolabs.com/blog/2016/12/20/top-10-python-libraries-of-2016/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2016 年 10 佳 Python 库</font></font></a></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-sites-using-zappa" class="anchor" aria-hidden="true" tabindex="-1" href="#sites-using-zappa"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Zappa 的网站</font></font></h2>
<ul dir="auto">
<li><a href="https://github.com/sasha42/Mailchimp-utility"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Mailchimp 注册实用程序</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">- 一种微服务，用于通过 API 将人员添加到邮件列表。</font></font></li>
<li><a href="https://github.com/Miserlou/zappa-slack-inviter"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Zappa Slack Inviter</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 一种小型、无服务器的服务，用于邀请新用户加入您的 Slack 频道。</font></font></li>
<li><a href="https://github.com/Miserlou/serverless-imagehost"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Serverless Image Host</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 使用 Flask、Zappa 和 Pillow 的缩略图服务。</font></font></li>
<li><a href="https://github.com/Miserlou/zappa-bittorrent-tracker"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Zappa BitTorrent Tracker</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 一个实验性的无服务器 BitTorrent 跟踪器。</font><font style="vertical-align: inherit;">工作正在进行中。</font></font></li>
<li><a href="https://github.com/Miserlou/JankyGlance"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JankyGlance</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 无服务器的 Yahoo! </font><font style="vertical-align: inherit;">管道更换。</font></font></li>
<li><a href="https://github.com/tryolabs/lambda-mailer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LambdaMailer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 用于处理联系表单的无服务器端点。</font></font></li>
<li><a href="https://topics.arlingtonva.us/2016/11/voter-registration-search-microservice/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">选民登记微服务</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">- 弗吉尼亚选举部门户的官方备份。</font></font></li>
<li><a href="https://www.freepoll.online" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">FreePoll Online</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 一种简单而令人敬畏的方式，供团体做出决定。</font></font></li>
<li><a href="https://paste.ofcode.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PasteOfCode</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - Zappa 驱动的粘贴箱。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">还有更多，包括银行、政府、初创公司、企业和学校！</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">你用的是扎帕吗？</font><font style="vertical-align: inherit;">让我们知道，我们将在这里列出您的网站！</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-related-projects" class="anchor" aria-hidden="true" tabindex="-1" href="#related-projects"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">相关项目</font></font></h2>
<ul dir="auto">
<li><a href="http://github.com/Miserlou/Mackenzie"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Mackenzie</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - AWS Lambda 感染工具包</font></font></li>
<li><a href="https://github.com/Miserlou/NoDB"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">NoDB</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 一个基于 S3 的简单、无服务器、Pythonic 对象存储。</font></font></li>
<li><a href="http://github.com/Miserlou/zappa-cms"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">zappa-cms</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 一个小型的无服务器 CMS，适合忙碌的黑客。</font><font style="vertical-align: inherit;">工作正在进行中。</font></font></li>
<li><a href="https://github.com/Miserlou/zappa-django-utils"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">zappa-django-utils</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 帮助 Django 部署的实用命令。</font></font></li>
<li><a href="https://github.com/johnwheeler/flask-ask"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">烧瓶询问</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 用于构建 Amazon Alexa 应用程序的框架。</font><font style="vertical-align: inherit;">使用 Zappa 进行部署。</font></font></li>
<li><a href="https://github.com/anush0247/zappa-file-widget"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">zappa-file-widget</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 一个 Django 插件，用于支持 Zappa 上 Django 中的二进制文件上传。</font></font></li>
<li><a href="https://github.com/bjinwright/zops"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">zops</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 使用 Zappa 进行团队和持续集成的实用程序。</font></font></li>
<li><a href="https://github.com/narfman0/cookiecutter-mobile-backend/"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">cookiecutter-mobile-backend</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 一个</font></font><code>cookiecutter</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持 Zappa 和 S3 上传的 Django 项目。</font></font></li>
<li><a href="https://github.com/narfman0/zappa-examples/"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">zappa-examples</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - Flask、Django、图像上传等等！</font></font></li>
<li><a href="https://github.com/mcrowson/zappa-hug-example"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">zappa-hug-example</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 使用 Zappa 的 Hug 应用程序示例.</font></font></li>
<li><a href="https://github.com/danielwhatmuff/zappa"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Zappa Docker Image</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 基于 Lambda Docker 的用于在本地运行 Zappa 的 Docker 映像。</font></font></li>
<li><a href="https://github.com/nikos/zappa-dashing"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">zappa-dashing</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 使用 Zappa 和 CloudWatch 监控您的 AWS 环境（运行状况/指标）.</font></font></li>
<li><a href="https://github.com/cameronmaske/s3env"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">s3env</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 通过 CLI 操作 S3 存储桶中的远程 Zappa 环境变量键/值 JSON 对象文件。</font></font></li>
<li><a href="https://github.com/wobeng/zappa_resize_image_on_fly"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">zappa_resize_image_on_fly</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 使用 Flask、Zappa、Pillow 和 OpenCV-python 动态调整图像大小。</font></font></li>
<li><a href="https://github.com/ubergarm/zappa-ffmpeg"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">zappa-ffmpeg</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 在 lambda 内运行 ffmpeg 以进行无服务器转换。</font></font></li>
<li><a href="https://github.com/richiverse/gdrive-lambda"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">gdrive-lambda</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 将 json 数据传递到 csv 文件，供在整个组织中使用 Gdrive 的最终用户使用。</font></font></li>
<li><a href="https://github.com/bcongdon/travis-build-repeat"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">travis-build-repeat</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 重复 TravisCI 构建以避免过时的测试结果.</font></font></li>
<li><a href="https://github.com/mcrowson/wunderlist-alexa-skill"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">wunderskill-alexa-skill</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 用于添加到奇妙清单的 Alexa 技能.</font></font></li>
<li><a href="https://github.com/mathom/xrayvision"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">xrayvision</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 将 AWS X-Ray 与 Zappa 结合使用的实用程序和包装器.</font></font></li>
<li><a href="https://github.com/dpetzold/terraform-aws-zappa"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">terraform-aws-zappa</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 用于创建 VPC、RDS 实例、ElastiCache Redis 和 CloudFront Distribution 以与 Zappa 一起使用的 Terraform 模块.</font></font></li>
<li><a href="https://github.com/jneves/zappa-sentry"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">zappa-sentry</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 与 Zappa 和 Sentry 集成</font></font></li>
<li><a href="https://github.com/iopipe/iopipe-python#zappa"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">IOpipe</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 监控、分析和分析您的 Zappa 应用程序。</font></font></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-hacks" class="anchor" aria-hidden="true" tabindex="-1" href="#hacks"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">黑客</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Zappa 远远超出了 Lambda 和 API Gateway 的预期处理范围。</font><font style="vertical-align: inherit;">因此，这里有很多技巧可以让它发挥作用。</font><font style="vertical-align: inherit;">其中一些包括但不限于..</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 VTL 将正文、标头、方法、参数和查询字符串映射为 JSON，然后将其转换为有效的 WSGI。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将响应代码附加到响应主体，对整个内容进行 Base64 编码，将其用作正则表达式来路由响应代码，在 VTL 中解码主体，并将响应主体映射到该主体。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将多个 cookie打包并</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Base58</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">编码为单个 cookie，因为我们只能映射一种。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">强制“Set-Cookie”的大小写排列，以便同时返回多个标头。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将 cookie 设置 301/302 响应转换为 HTML 重定向的 200 响应，因为我们无法在重定向上设置标头。</font></font></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-contributing" class="anchor" aria-hidden="true" tabindex="-1" href="#contributing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">非常欢迎您的贡献！</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请在提交补丁之前提交讨论票。</font><font style="vertical-align: inherit;">Pull 请求应该有针对性</font></font><code>master</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，并且如果合并，Zappa 应该处于“可交付”状态。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您要添加大量新代码，请在 PR 中包含功能测试。</font><font style="vertical-align: inherit;">对于 AWS 调用，我们使用该库，您可以</font><a href="https://github.com/garnaat/placebo#usage-as-a-decorator"><font style="vertical-align: inherit;">在其 README 中</font></a></font><code>placebo</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">学习如何使用该库</font><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">一旦您打开拉取请求，</font><font style="vertical-align: inherit;">测试套件将由</font><a href="https://travis-ci.org/zappa/Zappa" rel="nofollow"><font style="vertical-align: inherit;">Travis CI运行。</font></a></font><a href="https://github.com/garnaat/placebo#usage-as-a-decorator"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font><a href="https://travis-ci.org/zappa/Zappa" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请包含 GitHub 问题或拉取请求 URL，其中包含与您的更改相关的讨论作为代码中的注释（</font></font><a href="https://github.com/zappa/Zappa/blob/fae2925431b820eaedf088a632022e4120a29f89/zappa/zappa.py#L241-L243"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">示例</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）。</font><font style="vertical-align: inherit;">这极大地有助于项目的可维护性，因为它使我们能够追溯用例并解释决策。</font></font><a href="https://raw.githubusercontent.com/zappa/Zappa/master/.github/PULL_REQUEST_TEMPLATE.md" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">同样，请确保您满足拉取请求模板</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中列出的所有要求</font><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请随意处理任何未处理的请求，尤其是任何标有“需要帮助”标签的请求。</font><font style="vertical-align: inherit;">如果您遇到困难或想进一步讨论某个问题，请加入</font></font><a href="https://zappateam.slack.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们的 Slack 频道</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，在这里您会发现一个由聪明而有趣的人组成的社区，他们正在努力解决难题。
</font></font><a href="https://slackautoinviter.herokuapp.com" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Zappa Slack 自动邀请</font></font></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Zappa 并不打算遵守 PEP8，隔离您的提交，以便通过 linter 所做的更改来更改功能。</font></font></p>
<h4 tabindex="-1" dir="auto"><a id="user-content-using-a-local-repo" class="anchor" aria-hidden="true" tabindex="-1" href="#using-a-local-repo"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用本地存储库</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要使用 git HEAD，您</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可能无法</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用</font></font><code>pip install -e </code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">. </font><font style="vertical-align: inherit;">相反，您应该将存储库克隆到您的计算机，然后</font></font><code>pip install /path/to/zappa/repo</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">复制</font></font><code>ln -s /path/to/zappa/repo/zappa zappa</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">到您的本地项目中。</font></font></p>
</article></div>
