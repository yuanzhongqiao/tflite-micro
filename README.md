<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text">
<ul dir="auto">
<li><a href="#tensorflow-lite-for-microcontrollers"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">适用于微控制器的 TensorFlow Lite</font></font></a></li>
<li><a href="#build-status"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建状态</font></font></a>
<ul dir="auto">
<li><a href="#official-builds"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">官方版本</font></font></a></li>
<li><a href="#community-supported-tflm-examples"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">社区支持的 TFLM 示例</font></font></a></li>
<li><a href="#community-supported-kernels-and-unit-tests"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">社区支持的内核和单元测试</font></font></a></li>
</ul>
</li>
<li><a href="#contributing"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献</font></font></a></li>
<li><a href="#getting-help"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">寻求帮助</font></font></a></li>
<li><a href="#additional-documentation"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">附加文档</font></font></a></li>
<li><a href="#rfcs"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RFC</font></font></a></li>
</ul>


<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">适用于微控制器的 TensorFlow Lite</font></font></h1><a id="user-content-tensorflow-lite-for-microcontrollers" class="anchor" aria-label="永久链接：适用于微控制器的 TensorFlow Lite" href="#tensorflow-lite-for-microcontrollers"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">适用于微控制器的 TensorFlow Lite 是 TensorFlow Lite 的一个端口，旨在在 DSP、微控制器和其他内存有限的设备上运行机器学习模型。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">附加链接：</font></font></p>
<ul dir="auto">
<li><a href="https://github.com/tensorflow/tensorflow/"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">张量流 github 存储库</font></font></a></li>
<li><a href="https://www.tensorflow.org/lite/microcontrollers" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TFLM，位于tensorflow.org</font></font></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建状态</font></font></h1><a id="user-content-build-status" class="anchor" aria-label="永久链接：构建状态" href="#build-status"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="https://www.githubstatus.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GitHub 状态</font></font></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">官方版本</font></font></h2><a id="user-content-official-builds" class="anchor" aria-label="永久链接：官方版本" href="#official-builds"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建类型</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">地位</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">持续集成（Linux）</font></font></td>
<td><a href="https://github.com/tensorflow/tflite-micro/actions/workflows/run_ci.yml"><img src="https://github.com/tensorflow/tflite-micro/actions/workflows/run_ci.yml/badge.svg" alt="CI" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">代码同步</font></font></td>
<td><a href="https://github.com/tensorflow/tflite-micro/actions/workflows/sync.yml"><img src="https://github.com/tensorflow/tflite-micro/actions/workflows/sync.yml/badge.svg" alt="从上游 TF 同步" style="max-width: 100%;"></a></td>
</tr>
</tbody>
</table>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">社区支持的 TFLM 示例</font></font></h2><a id="user-content-community-supported-tflm-examples" class="anchor" aria-label="永久链接：社区支持的 TFLM 示例" href="#community-supported-tflm-examples"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此表捕获了 TFLM 已移植到的平台。</font><font style="vertical-align: inherit;">请参阅
</font></font><a href="/tensorflow/tflite-micro/blob/main/tensorflow/lite/micro/docs/new_platform_support.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">新平台支持</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以获取其他文档。</font></font></p>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">平台</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">地位</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Arduino</font></font></td>
<td><a href="https://github.com/tensorflow/tflite-micro-arduino-examples/actions/workflows/ci.yml"><img src="https://github.com/tensorflow/tflite-micro-arduino-examples/actions/workflows/ci.yml/badge.svg" alt="Arduino" style="max-width: 100%;"></a> <a href="https://github.com/antmicro/tensorflow-arduino-examples/actions/workflows/test_examples.yml"><img src="https://github.com/antmicro/tensorflow-arduino-examples/actions/workflows/test_examples.yml/badge.svg" alt="蚂蚁微" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><a href="https://coral.ai/products/dev-board-micro" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Coral 开发板微型</font></font></a></td>
<td><a href="https://github.com/google-coral/coralmicro"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Coral Dev Board Micro 的 TFLM + EdgeTPU 示例</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">乐鑫系统开发板</font></font></td>
<td><a href="https://github.com/espressif/tflite-micro-esp-examples/actions/workflows/ci.yml"><img src="https://github.com/espressif/tflite-micro-esp-examples/actions/workflows/ci.yml/badge.svg" alt="ESP 开发板" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">瑞萨主板</font></font></td>
<td><a href="https://github.com/renesas/tflite-micro-renesas"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Renesas 主板的 TFLM 示例</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Silicon Labs 开发套件</font></font></td>
<td><a href="https://github.com/SiliconLabs/tflite-micro-efr32-examples"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Silicon Labs 开发套件的 TFLM 示例</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">斯帕克芬边缘</font></font></td>
<td><a href="https://github.com/advaitjain/tflite-micro-sparkfun-edge-examples/actions/workflows/ci.yml"><img src="https://github.com/advaitjain/tflite-micro-sparkfun-edge-examples/actions/workflows/ci.yml/badge.svg?event=schedule" alt="斯帕克芬边缘" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">德州仪器 (TI) 开发板</font></font></td>
<td><a href="https://github.com/TexasInstruments/tensorflow-lite-micro-examples/actions/workflows/ci.yml"><img src="https://github.com/TexasInstruments/tensorflow-lite-micro-examples/actions/workflows/ci.yml/badge.svg?event=status" alt="德州仪器 (TI) 开发板" style="max-width: 100%;"></a></td>
</tr>
</tbody>
</table>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">社区支持的内核和单元测试</font></font></h2><a id="user-content-community-supported-kernels-and-unit-tests" class="anchor" aria-label="永久链接：社区支持的内核和单元测试" href="#community-supported-kernels-and-unit-tests"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这是已优化内核实现和/或使用软件仿真或指令集模拟器运行 TFLM 单元测试的目标列表。</font></font></p>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建类型</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">地位</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">皮质-M</font></font></td>
<td><a href="https://github.com/tensorflow/tflite-micro/actions/workflows/cortex_m.yml"><img src="https://github.com/tensorflow/tflite-micro/actions/workflows/cortex_m.yml/badge.svg" alt="皮质-M" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">六边形</font></font></td>
<td><a href="https://github.com/tensorflow/tflite-micro/actions/workflows/run_hexagon.yml"><img src="https://github.com/tensorflow/tflite-micro/actions/workflows/run_hexagon.yml/badge.svg" alt="六边形" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RISC-V</font></font></td>
<td><a href="https://github.com/tensorflow/tflite-micro/actions/workflows/riscv.yml"><img src="https://github.com/tensorflow/tflite-micro/actions/workflows/riscv.yml/badge.svg" alt="RISC-V" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">克滕萨</font></font></td>
<td><a href="https://github.com/tensorflow/tflite-micro/actions/workflows/run_xtensa.yml"><img src="https://github.com/tensorflow/tflite-micro/actions/workflows/run_xtensa.yml/badge.svg" alt="克滕萨" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">生成集成测试</font></font></td>
<td><a href="https://github.com/tensorflow/tflite-micro/actions/workflows/generate_integration_tests.yml"><img src="https://github.com/tensorflow/tflite-micro/actions/workflows/generate_integration_tests.yml/badge.svg" alt="生成集成测试" style="max-width: 100%;"></a></td>
</tr>
</tbody>
</table>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献</font></font></h1><a id="user-content-contributing" class="anchor" aria-label="永久链接：贡献" href="#contributing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅我们的</font></font><a href="/tensorflow/tflite-micro/blob/main/CONTRIBUTING.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献文档</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">寻求帮助</font></font></h1><a id="user-content-getting-help" class="anchor" aria-label="永久链接：获取帮助" href="#getting-help"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Github</font></font><a href="https://github.com/tensorflow/tflite-micro/issues/new/choose"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">问题</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
应该是与 TensorFlow Lite Micro (TFLM) 团队取得联系的主要方法。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下资源也可能有用：</font></font></p>
<ol dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SIG 微</font></font><a href="https://groups.google.com/a/tensorflow.org/g/micro" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">电子邮件小组</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
和
</font></font><a href="http://doc/1YHq9rmhrOUdcZnrEnVCWvd87s2wQbq4z17HbeRl-DBc" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">每月会议</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SIG Micro </font></font><a href="https://gitter.im/tensorflow/sig-micro" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">gitter 聊天室</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于非 TFLM 特有的问题，请咨询更广泛的 TensorFlow 项目，例如：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><a href="https://discuss.tensorflow.org" rel="nofollow"><font style="vertical-align: inherit;">在TensorFlow Discourse 论坛</font></a><font style="vertical-align: inherit;">上创建主题</font></font><a href="https://discuss.tensorflow.org" rel="nofollow"><font style="vertical-align: inherit;"></font></a></li>
<li><font style="vertical-align: inherit;"><a href="https://groups.google.com/a/tensorflow.org/g/tflite" rel="nofollow"><font style="vertical-align: inherit;">向TensorFlow Lite 邮件列表</font></a><font style="vertical-align: inherit;">发送电子邮件</font></font><a href="https://groups.google.com/a/tensorflow.org/g/tflite" rel="nofollow"><font style="vertical-align: inherit;"></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">创建</font></font><a href="https://github.com/tensorflow/tensorflow/issues/new/choose"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TensorFlow 问题</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">创建</font></font><a href="https://github.com/tensorflow/model-optimization"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型优化工具包</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">问题</font></font></li>
</ul>
</li>
</ol>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">附加文档</font></font></h1><a id="user-content-additional-documentation" class="anchor" aria-label="固定链接：附加文档" href="#additional-documentation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="/tensorflow/tflite-micro/blob/main/docs/continuous_integration.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">持续集成</font></font></a></li>
<li><a href="/tensorflow/tflite-micro/blob/main/tensorflow/lite/micro/benchmarks/README.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基准测试</font></font></a></li>
<li><a href="/tensorflow/tflite-micro/blob/main/tensorflow/lite/micro/docs/profiling.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">分析</font></font></a></li>
<li><a href="/tensorflow/tflite-micro/blob/main/tensorflow/lite/micro/docs/memory_management.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">内存管理</font></font></a></li>
<li><a href="/tensorflow/tflite-micro/blob/main/tensorflow/lite/micro/docs/logging.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">记录</font></font></a></li>
<li><a href="/tensorflow/tflite-micro/blob/main/tensorflow/lite/micro/docs/porting_reference_ops.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将参考内核从 TfLite 移植到 TFLM</font></font></a></li>
<li><a href="/tensorflow/tflite-micro/blob/main/tensorflow/lite/micro/docs/optimized_kernel_implementations.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">优化的内核实现</font></font></a></li>
<li><a href="/tensorflow/tflite-micro/blob/main/tensorflow/lite/micro/docs/new_platform_support.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">新平台支持</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">平台/IP支持
</font></font><ul dir="auto">
<li><a href="/tensorflow/tflite-micro/blob/main/tensorflow/lite/micro/docs/arm.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ARM IP 支持</font></font></a></li>
</ul>
</li>
<li><a href="/tensorflow/tflite-micro/blob/main/tensorflow/lite/micro/docs/renode.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Renode 进行软件模拟</font></font></a></li>
<li><a href="/tensorflow/tflite-micro/blob/main/tensorflow/lite/micro/docs/qemu.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 QEMU 进行软件仿真</font></font></a></li>
<li><a href="/tensorflow/tflite-micro/blob/main/docs/python.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Python 开发指南</font></font></a></li>
<li><a href="/tensorflow/tflite-micro/blob/main/docs/automatically_generated_files.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自动生成的文件</font></font></a></li>
<li><a href="/tensorflow/tflite-micro/blob/main/python/tflite_micro/README.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Python 解释器指南</font></font></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RFC</font></font></h1><a id="user-content-rfcs" class="anchor" aria-label="永久链接：RFC" href="#rfcs"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ol dir="auto">
<li><a href="/tensorflow/tflite-micro/blob/main/tensorflow/lite/micro/docs/rfc/001_preallocated_tensors.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">预分配张量</font></font></a></li>
<li><a href="/tensorflow/tflite-micro/blob/main/tensorflow/lite/micro/docs/rfc/002_16x8_quantization_port.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">适用于微控制器的 TensorFlow Lite 16x8 量化运算符端口</font></font></a></li>
</ol>
</article></div>
