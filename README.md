# HTML test

マークダウンでなくて、HTMLを書いてもある程度解釈されるみたいですね。このテーブルはマークダウンではありません。HTMLを(マークダウンの代わりに)貼り付けてあるだけです。衝撃的でしょ？

## 01😀 02😬 03😁 04😂 05😃 06😄 07😅 08😆 09😇 10😉 11😊 12🙂 13☺️ 14😋 15😌 16😍 17😘 19😗 19😙 20😚 21😜 22😝 23😛 24😎 25😏 26😶 27😐 28😑 29😒 30😳 31😞 32😟 33😠 34😡 35😔 36😕 37🙁 38☹️ 39😣 40😖 41😫 42😩 43😤 44😮 45😱 46😨 47😰 48😯 49😦 50😧 51😢 52😥 53😪 54😓 55😭 56😵 57😲 58😷 59😴 60💤 61💩 62😈 64👿 65👹 65👺 66💀 67👻 68👽

<table>
<thead>
<tr>
<td>Name of the feature</td>
<td>Example</td>
<td>Default</td>
</tr>
</thead>
<tbody>
<tr>
<td>Remove inline styles</td>
<td><img src="https://qiita-image-store.s3.amazonaws.com/0/140610/d4184ea0-0c21-3b78-5154-90bae839a05f.png">You <strong style="color: blue; text-decoration: underline;">should never</strong>&nbsp;use inline styles!</td>
<td><strong style="font-size: 17px; color: #2b2301;">x</strong></td>
</tr>
<tr>
<td>Remove classes and IDs</td>
<td><span id="demoId">Use classes to <strong class="demoClass">style everything</strong>.</span></td>
<td><strong style="font-size: 17px; color: #2b2301;">x</strong></td>
</tr>
<tr>
<td>Remove all tags</td>
<td>This leaves <strong style="color: blue;">only the plain</strong> <em>text</em>.</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>Remove successive &amp;nbsp;s</td>
<td>Never use non-breaking spaces&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;to set margins.</td>
<td><strong style="font-size: 17px; color: #2b2301;">x</strong></td>
</tr>
<tr>
<td>Remove empty tags</td>
<td>Empty tags should go!</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>Remove tags with one &amp;nbsp;</td>
<td>This makes&nbsp;no sense!</td>
<td><strong style="font-size: 17px; color: #2b2301;">x</strong></td>
</tr>
<tr>
<td>Remove span tags</td>
<td>Span tags with <span style="color: green; font-size: 13px;">all styles</span></td>
<td><strong style="font-size: 17px; color: #2b2301;">x</strong></td>
</tr>
<tr>
<td>Remove links</td>
<td><a href="https://html-online.com">This is</a> a link.</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>Remove tables</td>
<td>Takes everything out of the table.</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>Replace table tags with structured divs</td>
<td>This text is inside a table.</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>Remove comments</td>
<td>This is only visible in the source editor <!-- HELLO! --></td>
<td><strong style="font-size: 17px; color: #2b2301;">x</strong></td>
</tr>
<tr>
<td>Encode special characters</td>
<td><span style="color: red; font-size: 17px;">&hearts;</span> <strong style="font-size: 20px;">☺ ★</strong> &gt;&lt;</td>
<td><strong style="font-size: 17px; color: #2b2301;">x</strong></td>
</tr>
<tr>
<td>Set new lines and text indents</td>
<td>Organize the tags in a nice tree view.</td>
<td>&nbsp;</td>
</tr>
</tbody>
</table>
