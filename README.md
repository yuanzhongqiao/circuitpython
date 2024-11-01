<div class="Box-sc-g0xbh4-0 QkQOb js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto" _msttexthash="6605976" _msthash="392">电路Python</h1><a id="user-content-circuitpython" class="anchor" aria-label="永久链接：CircuitPython" href="#circuitpython" _mstaria-label="558506" _msthash="393"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/14c8bc9dc8221428b647fe20e63b6fb7fb3083256aad374873d4b9e6d34be597/68747470733a2f2f73332e616d617a6f6e6177732e636f6d2f61646166727569742d636972637569742d707974686f6e2f43697263756974507974686f6e5f5265706f5f6865616465725f6c6f676f2e706e67"><img alt="https://s3.amazonaws.com/adafruit-circuit-python/CircuitPython_Repo_header_logo.png" src="https://camo.githubusercontent.com/14c8bc9dc8221428b647fe20e63b6fb7fb3083256aad374873d4b9e6d34be597/68747470733a2f2f73332e616d617a6f6e6177732e636f6d2f61646166727569742d636972637569742d707974686f6e2f43697263756974507974686f6e5f5265706f5f6865616465725f6c6f676f2e706e67" data-canonical-src="https://s3.amazonaws.com/adafruit-circuit-python/CircuitPython_Repo_header_logo.png" style="max-width: 100%;" _mstalt="5205941" _msthash="394"></a></p>
<p dir="auto"><a href="https://github.com/adafruit/circuitpython/actions?query=branch%3Amain"><img alt="构建状态" src="https://github.com/adafruit/circuitpython/workflows/Build%20CI/badge.svg" style="max-width: 100%;" _mstalt="181376" _msthash="395">
</a> <a href="http://circuitpython.readthedocs.io/" rel="nofollow"><img alt="文档状态" src="https://camo.githubusercontent.com/5b94ec195d5f2d5407cf2828223bd277c5fb87b6e4f6b61149c11ebfb1be9a7e/68747470733a2f2f72656164746865646f63732e6f72672f70726f6a656374732f63697263756974707974686f6e2f62616467652f3f76657273696f6e3d6c6174657374" data-canonical-src="https://readthedocs.org/projects/circuitpython/badge/?version=latest" style="max-width: 100%;" _mstalt="135148" _msthash="396"></a> <a href="https://choosealicense.com/licenses/mit/" rel="nofollow"><img alt="许可证" src="https://camo.githubusercontent.com/d4f493300e045e7cc47dd7020bded1957d2b15168b095f72585e4357371a7a31/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4c6963656e73652d4d49542d627269676874677265656e2e737667" data-canonical-src="https://img.shields.io/badge/License-MIT-brightgreen.svg" style="max-width: 100%;" _mstalt="93288" _msthash="397">
</a> <a href="https://adafru.it/discord" rel="nofollow"><img alt="不和" src="https://camo.githubusercontent.com/9a7ca2b8ddf566d76a764c2c55c2bc7bff22ace6342e3c3225254bd5626b95a0/68747470733a2f2f696d672e736869656c64732e696f2f646973636f72642f3332373235343730383533343131363335322e737667" data-canonical-src="https://img.shields.io/discord/327254708534116352.svg" style="max-width: 100%;" _mstalt="93990" _msthash="398">
</a> <a href="https://hosted.weblate.org/engage/circuitpython/?utm_source=widget" rel="nofollow"><img alt="Weblate 网站" src="https://camo.githubusercontent.com/7d9d8056cd8fa06a891a797366d2ee6540f76aa6a2ca2de03c06b1ac1b4ead7b/68747470733a2f2f686f737465642e7765626c6174652e6f72672f776964676574732f63697263756974707974686f6e2f2d2f7376672d62616467652e737667" data-canonical-src="https://hosted.weblate.org/widgets/circuitpython/-/svg-badge.svg" style="max-width: 100%;" _mstalt="92963" _msthash="399">
</a></p>
<p dir="auto" _msttexthash="340951715" _msthash="400"><a href="https://circuitpython.org" rel="nofollow" _istranslated="1">circuitpython.org</a> |<a href="#get-circuitpython" _istranslated="1">获取 CircuitPython</a> |<a href="#documentation" _istranslated="1">文档</a> |<a href="#contributing" _istranslated="1">贡献</a> |<a href="#branding" _istranslated="1">品牌推广</a> |<a href="#differences-from-micropython" _istranslated="1">与 Micropython 的区别</a> |<a href="#project-structure" _istranslated="1">项目结构</a></p>
<p dir="auto"><font _mstmutation="1" _msttexthash="7208861764" _msthash="401"><strong _mstmutation="1" _istranslated="1">CircuitPython</strong> 是一个<em _mstmutation="1" _istranslated="1">适合初学者</em>的开源 Python 版本，适用于小巧、廉价的
称为微控制器的计算机。微控制器是许多电子设备的大脑，包括
用于构建业余项目和原型的各种开发板。CircuitPython 中的
电子学是学习编码的最佳方式之一，因为它将代码与现实联系起来。只是
通常通过拖放将 CircuitPython 安装在支持的 USB 板上，然后在 CIRCUITPY 驱动器上编辑文件。代码将自动重新加载。无需安装软件
除了文本编辑器（我们建议初学者使用 <a href="https://codewith.mu/" rel="nofollow" _mstmutation="1" _istranslated="1">Mu</a>。</font><code>code.py</code></p>
<p dir="auto" _msttexthash="2153764665" _msthash="402">从 CircuitPython 7.0.0 开始，某些板可能只能通过低功耗蓝牙连接
（BLE） 的 BLE。这些板卡使用开放协议通过 BLE 而不是 USB 提供串行和文件访问。
（某些板可能同时使用 USB 和 BLE。BLE 访问可以通过各种应用程序完成，包括 <a href="https://code.circuitpython.org" rel="nofollow" _istranslated="1">code.circuitpython.org</a>。</p>
<p dir="auto" _msttexthash="810348357" _msthash="403">CircuitPython 具有统一的 Python 核心 API 和不断增长的 300+ 设备库和
与它一起工作的驱动程序。这些库也可以在具有常规
通过 <a href="https://github.com/adafruit/Adafruit_Blinka" _istranslated="1">Adafruit Blinka 库</a>的 Python。</p>
<p dir="auto" _msttexthash="1096794621" _msthash="404">CircuitPython 基于 <a href="https://micropython.org" rel="nofollow" _istranslated="1">MicroPython</a>。有关差异，请参阅<a href="#differences-from-micropython" _istranslated="1">下文</a>。大多数（但不是全部）CircuitPython
开发由 <a href="https://adafruit.com" rel="nofollow" _istranslated="1">Adafruit</a> 赞助，可在其 Educational 上使用
开发板。请同时支持 MicroPython 和 Adafruit。</p>
<a name="user-content-get-circuitpython"></a>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="5570318" _msthash="405">获取 CircuitPython</h2><a id="user-content-get-circuitpython" class="anchor" aria-label="永久链接：获取 CircuitPython" href="#get-circuitpython" _mstaria-label="679718" _msthash="406"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="943424391" _msthash="407">所有受支持主板的官方二进制文件均可通过 <a href="https://circuitpython.org/downloads" rel="nofollow" _istranslated="1">circuitpython.org/downloads</a> 获得。该网站包括 stable、unstable 和
持续构建。完整的发行说明也可通过 <a href="https://github.com/adafruit/circuitpython/releases" _istranslated="1">GitHub 版本</a>获得。</p>
<a name="user-content-documentation"></a>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="5144373" _msthash="408">文档</h2><a id="user-content-documentation" class="anchor" aria-label="永久链接： 文档" href="#documentation" _mstaria-label="559767" _msthash="409"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="909137307" _msthash="410">指南和视频可通过 <a href="https://learn.adafruit.com/" rel="nofollow" _istranslated="1">Adafruit Learning 获取
</a> <a href="https://learn.adafruit.com/category/circuitpython" rel="nofollow" _istranslated="1">CircuitPython 下的系统
类别</a>。一个 API
参考也可以在 <a href="http://circuitpython.readthedocs.io/en/latest/?" rel="nofollow" _istranslated="1">阅读文档</a> 中找到。一个很棒的集合
资源可以在 <a href="https://github.com/adafruit/awesome-circuitpython" _istranslated="1">Awesome CircuitPython</a> 中找到。</p>
<p dir="auto" _msttexthash="54239952" _msthash="411">开始时特别有用的文档：</p>
<ul dir="auto">
<li><a href="https://learn.adafruit.com/welcome-to-circuitpython" rel="nofollow" _msttexthash="12909780" _msthash="412">欢迎使用 CircuitPython</a></li>
<li><a href="https://learn.adafruit.com/circuitpython-essentials" rel="nofollow" _msttexthash="14494103" _msthash="413">CircuitPython 基础</a></li>
<li><a href="https://github.com/adafruit/Adafruit_Learning_System_Guides/tree/master/CircuitPython_Essentials" _msttexthash="11298391" _msthash="414">示例代码</a></li>
</ul>
<a name="user-content-contributing"></a>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="6354283" _msthash="415">贡献</h2><a id="user-content-contributing" class="anchor" aria-label="永久链接： 贡献" href="#contributing" _mstaria-label="521066" _msthash="416"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="1163095804" _msthash="417">请参阅 <a href="https://github.com/adafruit/circuitpython/blob/main/CONTRIBUTING.md" _istranslated="1">CONTRIBUTING.md</a> 以获取完整的指南，但请注意，为此做出贡献
您同意 <a href="https://github.com/adafruit/circuitpython/blob/main/CODE_OF_CONDUCT.md" _istranslated="1">Code of 的项目
行为</a>。
遵循 <a href="https://github.com/adafruit/circuitpython/blob/main/CODE_OF_CONDUCT.md" _istranslated="1">Code of
欢迎 Conduct</a> 提交 pull request，它们将得到及时审查
由 Project Admins。也请加入 <a href="https://adafru.it/discord" rel="nofollow" _istranslated="1">Discord</a>。</p>
<a name="user-content-branding"></a>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="5017467" _msthash="418">品牌</h2><a id="user-content-branding" class="anchor" aria-label="永久链接： 品牌推广" href="#branding" _mstaria-label="362882" _msthash="419"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="2262701753" _msthash="420">虽然我们很高兴看到 CircuitPython 被分叉和修改，但如果分叉发布，我们将不胜感激
不要使用名称 “CircuitPython” 或 Blinka 徽标。“CircuitPython” 的含义很特别
我们和那些了解它的人。因此，我们希望确保引用它的商品符合
一组常见的要求。</p>
<p dir="auto" _msttexthash="268068268" _msthash="421">如果您想为您的产品使用术语“CircuitPython”和 Blinka，我们要求以下内容：</p>
<ul dir="auto">
<li _msttexthash="539225258" _msthash="422">您的产品受主 <a href="https://github.com/adafruit/circuitpython" _istranslated="1">“adafruit/circuitpython”</a> 存储库支持。这样我们就可以
在更新 CircuitPython 内部时更新任何自定义代码。</li>
<li _msttexthash="618852702" _msthash="423">您的产品列在 <a href="https://circuitpython.org" rel="nofollow" _istranslated="1">circuitpython.org</a> 上（<a href="https://github.com/adafruit/circuitpython-org/" _istranslated="1">来源在这里</a>）。这是为了确保您的
product 始终可以从标准位置下载最新版本的 CircuitPython。</li>
<li><font _mstmutation="1" _msttexthash="210705521" _msthash="424">您的产品至少支持一个用于串行和文件访问的标准“<a href="https://docs.circuitpython.org/en/latest/docs/workflows.html" rel="nofollow" _mstmutation="1" _istranslated="1">工作流程</a>”：</font><ul dir="auto">
<li _msttexthash="152905077" _msthash="425">带有用户可访问的 USB 插头，插入时显示为 CIRCUITPY 驱动器。</li>
<li _msttexthash="175077916" _msthash="426">使用 BLE 工作流程通过低功耗蓝牙进行文件和串行访问。</li>
<li _msttexthash="296518274" _msthash="427">使用 WiFi 工作流程通过 WiFi 访问文件，并通过 USB 和/或 WebSocket 进行串行访问。</li>
</ul>
</li>
<li _msttexthash="91255125" _msthash="428">不支持 USB Workflow 的主板应清楚地标记。</li>
</ul>
<p dir="auto" _msttexthash="1572870312" _msthash="429">如果您选择不满足这些要求，那么我们要求您调用您的 CircuitPython 版本
其他内容（例如 SuperDuperPython），而不使用 Blinka 徽标。你可以说是
“CircuitPython 兼容”，如果大多数 CircuitPython 驱动程序都可以使用它。</p>
<hr>
<a name="user-content-differences-from-micropython"></a>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="20791303" _msthash="430">与 <a href="https://github.com/micropython/micropython" _istranslated="1">MicroPython</a> 的区别</h2><a id="user-content-differences-from-micropython" class="anchor" aria-label="永久链接：与 MicroPython 的区别" href="#differences-from-micropython" _mstaria-label="1191736" _msthash="431"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="19340646" _msthash="432">电路Python：</p>
<ul dir="auto">
<li _msttexthash="269050444" _msthash="433">在大多数主板上支持本机 USB，否则支持 BLE，无需特殊工具即可编辑文件。</li>
<li _msttexthash="91839371" _msthash="434">浮点数（又名小数）为所有构建启用。</li>
<li _msttexthash="63134708" _msthash="435">错误消息被翻译成 10+ 种语言。</li>
<li _msttexthash="1541943000" _msthash="436">Python 中的并发性没有得到很好的支持。中断和线程被禁用。
async/await 关键字在一些板上可用于协作多任务处理。一些并发
是通过本机模块实现的，用于需要它的任务，例如音频文件播放。</li>
</ul>
<a name="user-content-behavior"></a>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="5257876" _msthash="437">行为</h3><a id="user-content-behavior" class="anchor" aria-label="永久链接：行为" href="#behavior" _mstaria-label="366834" _msthash="438"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font _mstmutation="1" _msttexthash="389904346" _msthash="439">文件的运行顺序和共享的状态
他们。CircuitPython 的目标是阐明每个文件和
使每个文件彼此独立。</font><ul dir="auto">
<li><code>boot.py</code><font _mstmutation="1" _msttexthash="516726314" _msthash="440">在之前启动时仅运行一次
工作流已初始化。这为配置 USB 奠定了基础
启动而不是被修复。由于 serial 不可用，
output 被写入 。</font><code>boot_out.txt</code></li>
<li><code>code.py</code><font _mstmutation="1" _msttexthash="1666421640" _msthash="441">（或 ） 在每次重新加载后运行，直到它
完成或中断。运行完成后，vm 和
hardware 的 git 被重新初始化。<strong _mstmutation="1" _istranslated="1">这意味着您无法再从 REPL 中读取状态</strong><strong _mstmutation="1" _istranslated="1">，因为 REPL 是新的 VM。</strong>CircuitPython 的目标
更改包括减少对正在使用的 pin 和 memory 的混淆。</font><code>main.py</code><code>code.py</code></li>
<li><font _mstmutation="1" _msttexthash="1115832562" _msthash="442">主代码完成后，可以通过按任意键输入 REPL。
- 如果文件存在，则在显示 REPL 提示符之前执行该文件
- 在安全模式下，此功能被禁用，以确保始终可以访问 REPL 提示符</font><code>repl.py</code></li>
<li _msttexthash="102027107" _msthash="443">Autoreload 状态将在重新加载期间保持。</li>
</ul>
</li>
<li _msttexthash="1397418360" _msthash="444">添加一种安全模式，该模式在发生硬崩溃或断电后不运行用户代码。这使得
可以通过 Mass Storage 使其可用来修复导致严重崩溃的代码
崩溃。修复后需要重置 （按钮） 才能恢复正常模式。</li>
<li><font _mstmutation="1" _msttexthash="5873189231" _msthash="445">安全模式可以通过提供 . 如果进入安全模式导致开发板复位，则运行，除非
由用户通过按下按钮启动。
USB 不可用，因此无法打印任何内容。 可以确定出现安全模式的原因
，并采取适当的措施。例如
如果发生硬崩溃，则可以执行 A 操作，以便在发生崩溃时自动重启。
如果电池电量不足，但正在充电，可能会使开发板处于深度睡眠状态
有一段时间。或者它可能只是重置，并检查电压并进行睡眠。</font><code>safemode.py</code><code>safemode.py</code><code>safemode.py</code><code>supervisor.runtime.safe_mode_reason</code><code>safemode.py</code><code>microcontroller.reset()</code><code>safemode.py</code><code>code.py</code></li>
<li _msttexthash="1142975743" _msthash="446">RGB 状态 LED 指示 CircuitPython 状态。
- 绿色闪烁一次 - 代码完成且无误。
- 两次红灯闪烁 - 代码因异常而结束。
- 黄色闪烁三次 - 安全模式。可能是由于 CircuitPython 内部错误。</li>
<li><font _mstmutation="1" _msttexthash="172271372" _msthash="447">在工作流写入文件系统后重新运行或其他主文件。（禁用</font><code>code.py</code><code>supervisor.disable_autoreload()</code>)</li>
<li _msttexthash="167482159" _msthash="448">当 REPL 处于活动状态时，自动重新加载处于禁用状态。</li>
<li><code>code.py</code><font _mstmutation="1" _msttexthash="27202396" _msthash="449">也可以命名为 、 、 或 。</font><code>code.txt</code><code>main.py</code><code>main.txt</code></li>
<li><code>boot.py</code><font _mstmutation="1" _msttexthash="17513197" _msthash="450">也可以命名为 。</font><code>boot.txt</code></li>
<li><code>safemode.py</code><font _mstmutation="1" _msttexthash="17513197" _msthash="451">也可以命名为 。</font><code>safemode.txt</code></li>
</ul>
<a name="user-content-api"></a>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="19122688" _msthash="452">应用程序接口</h3><a id="user-content-api" class="anchor" aria-label="永久链接： API" href="#api" _mstaria-label="197821" _msthash="453"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li _msttexthash="49043982" _msthash="454">统一的硬件 API。记录在 <a href="https://circuitpython.readthedocs.io/en/latest/shared-bindings/index.html" rel="nofollow" _istranslated="1">ReadTheDocs</a> 上。</li>
<li><font _mstmutation="1" _msttexthash="56605289" _msthash="455">API 文档是 中 C 文件中的 Python 存根。</font><code>shared-bindings</code></li>
<li><font _mstmutation="1" _msttexthash="4156360" _msthash="456">无 API。</font><code>machine</code></li>
</ul>
<a name="user-content-modules"></a>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="4797715" _msthash="457">模块</h3><a id="user-content-modules" class="anchor" aria-label="永久链接： 模块" href="#modules" _mstaria-label="337571" _msthash="458"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font _mstmutation="1" _msttexthash="231510201" _msthash="459">没有模块别名。（ 和 不能分别作为 和 提供。相反，， ， 和 与 CPython 兼容。</font><code>uos</code><code>utime</code><code>os</code><code>time</code><code>os</code><code>time</code><code>random</code></li>
<li><font _mstmutation="1" _msttexthash="126683687" _msthash="460">管理文件系统挂载的新模块。
（MicroPython 中的功能。</font><code>storage</code><code>uos</code></li>
<li><font _mstmutation="1" _msttexthash="848857646" _msthash="461">具有 CPython 对应项的模块（例如 ， 和 ）是其 <a href="https://circuitpython.readthedocs.io/en/latest/shared-bindings/time/__init__.html" rel="nofollow" _mstmutation="1" _istranslated="1"></a> <a href="https://docs.python.org/3.4/library/time.html?highlight=time#module-time" rel="nofollow" _mstmutation="1" _istranslated="1">CPython 的严格子集
版</a>中。
因此，来自 CircuitPython 的代码可以在 CPython 上运行，但不能
必然相反。</font><code>time</code><code>os</code><code>random</code></li>
<li _msttexthash="114894416" _msthash="462">Tick Count 以 <a href="https://circuitpython.readthedocs.io/en/latest/shared-bindings/time/__init__.html#time.monotonic" rel="nofollow" _istranslated="1">time.monotonic（）</a> 的形式提供</li>
</ul>
<hr>
<a name="user-content-project-structure"></a>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="13962026" _msthash="463">项目结构</h2><a id="user-content-project-structure" class="anchor" aria-label="永久链接： 项目结构" href="#project-structure" _mstaria-label="693160" _msthash="464"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="66441882" _msthash="465">以下是顶级源代码目录的概述。</p>
<a name="user-content-core"></a>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="4977440" _msthash="466">核心</h3><a id="user-content-core" class="anchor" aria-label="永久链接：核心" href="#core" _mstaria-label="241904" _msthash="467"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="188621563" _msthash="468">共享 <a href="https://github.com/micropython/micropython" _istranslated="1">MicroPython</a> 的核心代码
在包括 CircuitPython 在内的端口中：</p>
<ul dir="auto">
<li><code>docs</code><font _mstmutation="1" _msttexthash="128776297" _msthash="469">Sphinx reStructuredText 中的高级用户文档
格式。</font></li>
<li><code>drivers</code><font _mstmutation="1" _msttexthash="85339150" _msthash="470">用 Python 编写的外部设备驱动程序。</font></li>
<li><code>examples</code><font _mstmutation="1" _msttexthash="26821509" _msthash="471">一些示例 Python 脚本。</font></li>
<li><code>extmod</code><font _mstmutation="1" _msttexthash="78363194" _msthash="472">在多个端口的模块中使用的共享 C 代码。</font></li>
<li><code>lib</code><font _mstmutation="1" _msttexthash="98622342" _msthash="473">共享核心 C 代码，包括外部开发的库
例如 FATFS。</font></li>
<li><code>logo</code><font _mstmutation="1" _msttexthash="17391894" _msthash="474">CircuitPython 徽标。</font></li>
<li><code>mpy-cross</code><font _mstmutation="1" _msttexthash="192581207" _msthash="475">将 Python 文件转换为字节的交叉编译器
代码。用于减少库
大小。</font></li>
<li><code>py</code><font _mstmutation="1" _msttexthash="124449845" _msthash="476">核心 Python 实现，包括编译器、运行时和
core 库。</font></li>
<li><code>shared-bindings</code><font _mstmutation="1" _msttexthash="291622500" _msthash="477">Python 模块的共享定义及其文档
和支持 C API。端口必须实现 C API 以支持
对应的模块。</font></li>
<li><code>shared-module</code><font _mstmutation="1" _msttexthash="132030509" _msthash="478">Python 模块的共享实现，这些模块可能是
基于。</font><code>common-hal</code></li>
<li><code>tests</code><font _mstmutation="1" _msttexthash="40074944" _msthash="479">测试框架和测试脚本。</font></li>
<li><code>tools</code><font _mstmutation="1" _msttexthash="47799453" _msthash="480">各种工具，包括 pyboard.py 模块。</font></li>
</ul>
<a name="user-content-ports"></a>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="4800237" _msthash="481">港口</h3><a id="user-content-ports" class="anchor" aria-label="永久链接：端口" href="#ports" _mstaria-label="280072" _msthash="482"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="93655484" _msthash="483">端口包括 microcontroller 线路独有的代码。</p>
<p dir="auto"><font _mstmutation="1" _msttexthash="39082641" _msthash="484">以下端口可用：、、、、</font><code>atmel-samd</code><code>cxd56</code><code>espressif</code><code>litex</code><code>mimxrt10xx</code><code>nordic</code><code>raspberrypi</code><code>renode</code><code>silabs</code><code>efr32</code><code>stm</code><code>unix</code></p>
<p dir="auto" _msttexthash="711648925" _msthash="485">但是，并非所有端口都功能齐全。有些功能有限，并且存在已知的严重错误。
有关详细信息，请参阅<a href="https://github.com/adafruit/circuitpython/releases/latest" _istranslated="1">最新版本</a>说明中的 <strong _istranslated="1">Port status</strong> 部分。</p>
<a name="user-content-boards"></a>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="2411045" _msthash="486">板</h3><a id="user-content-boards" class="anchor" aria-label="永久链接：板" href="#boards" _mstaria-label="301054" _msthash="487"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font _mstmutation="1" _msttexthash="158249598" _msthash="488">每个都有一个包含板的目录
它们属于特定的微控制器系列。</font><code>port</code><code>boards</code></li>
<li _msttexthash="106151383" _msthash="489">可以<a href="https://circuitpython.readthedocs.io/en/latest/shared-bindings/support_matrix.html" rel="nofollow" _istranslated="1">在此处</a>找到特定板支持的本机模块列表。</li>
</ul>
<p dir="auto"><a href="#circuitpython" _msttexthash="15341105" _msthash="490">返回页首</a></p>

</article></div>
