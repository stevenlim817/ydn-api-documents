# Stats
Statsオブジェクトは、統計情報を保持します。

### Service
+ [StatsService](../../services/StatsService.md)

### Namespace
[StatsService#Namespace](../../services/StatsService.md#namespace)
 
<table>
 <tr>
  <th>Field</th>
  <th>Type</th>
  <th>Description</th>
  <th>response</th>
 </tr>
 <tr>
  <td>imps</td>
  <td>xsd:long</td>
  <td>インプレッション数です。</td>
  <td>yes</td>
 </tr>
 <tr>
  <td>clickRate</td>
  <td>xsd:double</td>
  <td>クリック率です。</td>
  <td>yes</td>
 </tr>
 <tr>
  <td>totalClickCost</td>
  <td>xsd:double</td>
  <td>トータルコスト（クリックされた金額の合計）です。</td>
  <td>yes</td>
 </tr>
 <tr>
  <td>clickCnt</td>
  <td>xsd:long</td>
  <td>クリック数です。</td>
  <td>yes</td>
 </tr>
 <tr>
  <td>avgClickCost</td>
  <td>xsd:double</td>
  <td>平均クリックコスト（クリックされた金額の平均）です。</td>
  <td>yes</td>
 </tr>
 <tr>
  <td>conversions</td>
  <td>xsd:string</td>
  <td>コンバージョン数です。</td>
  <td>yes</td>
 </tr>
 <tr>
  <td>conversionRate</td>
  <td>xsd:double</td>
  <td>コンバージョン率です。</td>
  <td>yes</td>
 </tr>
 <tr>
  <td>cpa</td>
  <td>xsd:string</td>
  <td>コンバージョン単価です。<br>※デバイスをまたいだコンバージョンの値をを加味します。</td>
  <td>yes</td>
 </tr>
 <tr>
  <td>conversionValue</td>
  <td>xsd:string</td>
  <td>コンバージョンの価値です。</td>
  <td>yes</td>
 </tr>
 <tr>
  <td>valuePerConversions</td>
  <td>xsd:string</td>
  <td>価値/コンバージョン数です。</td>
  <td>yes</td>
 </tr>
 <tr>
  <td>allConversions</td>
  <td>xsd:long</td>
  <td>すべてのコンバージョン数です。</td>
  <td>yes</td>
 </tr>
 <tr>
  <td> allConversionRate</td>
  <td>xsd:double</td>
  <td>すべてのコンバージョン率です。</td>
  <td>yes</td>
 </tr>
 <tr>
  <td>allCpa</td>
  <td>xsd:string</td>
  <td>コスト/すべてのコンバージョン数です。</td>
  <td>yes</td>
 </tr>
 <tr>
  <td>allConversionValue</td>
  <td>xsd:string</td>
  <td>すべてのコンバージョンの価値です。</td>
  <td>yes</td>
 </tr>
 <tr>
  <td>valuePerAllConversions</td>
  <td>xsd:string</td>
  <td>価値/すべてのコンバージョン数です。</td>
  <td>yes</td>
 </tr>
 <tr>
 <tr>
  <td>avgDeliverRank</td>
  <td>xsd:double</td>
  <td>平均掲載順位（配信された時のeCPM順位の平均）です。</td>
  <td>yes</td>
 </tr>
 <tr>
  <td>totalVimps</td>
  <td>xsd:long</td>
  <td>ビュー計測対象インプレッション数です。</td>
  <td>yes</td>
 </tr>
 <tr>
  <td>vimps</td>
  <td>xsd:long</td>
  <td>ビューインプレッション数です。</td>
  <td>yes</td>
 </tr>
 <tr>
  <td>inViewClickCnt</td>
  <td>xsd:long</td>
  <td>ビュークリック数です。</td>
  <td>yes</td>
 </tr>
 <tr>
  <td>inViewRate</td>
  <td>xsd:double</td>
  <td>ビューインプレッション率です。</td>
  <td>yes</td>
 </tr>
 <tr>
  <td>inViewClickRate</td>
  <td>xsd:double</td>
  <td>ビュークリック率です。</td>
  <td>yes</td>
 </tr>
 <tr>
  <td>autoVideoPlays</td>
  <td>xsd:long</td>
  <td>動画自動再生数です。※動画広告のみ。</td>
  <td>yes</td>
 </tr>
 <tr>
  <td>clickVideoPlays</td>
  <td>xsd:long</td>
  <td>動画クリック再生数です。※動画広告のみ。</td>
  <td>yes</td>
 </tr>
 <tr>
  <td>videoViewedRate</td>
  <td>xsd:double</td>
  <td>動画再生率(動画再生数/インプレッション数)です。※動画広告のみ。</td>
  <td>yes</td>
 </tr>
 <tr>
  <td>paidVideoViews</td>
  <td>xsd:long</td>
  <td>課金が発生した動画再生数です。※動画広告のみ。</td>
  <td>yes</td>
 </tr>
 <tr>
  <td>paidVideoViewRate</td>
  <td>xsd:double</td>
  <td>課金が発生した動画再生率です。※動画広告のみ。</td>
  <td>yes</td>
 </tr>
 <tr>
  <td>averageCpv</td>
  <td>xsd:double</td>
  <td>平均CPVです。※動画広告のみ。</td>
  <td>yes</td>
 </tr>
 <tr>
  <td>videoPlays</td>
  <td>xsd:long</td>
  <td>動画が再生開始された回数です。※動画広告のみ。</td>
  <td>yes</td>
 </tr>
 <tr>
  <td>videoViews</td>
  <td>xsd:long</td>
  <td>動画再生数です。※動画広告のみ。</td>
  <td>yes</td>
 </tr>
 <tr>
  <td>videoViewsTo25</td>
  <td>xsd:long</td>
  <td>動画25％再生数です。※動画広告のみ。</td>
  <td>yes</td>
 </tr>
 <tr>
  <td>videoViewsTo50</td>
  <td>xsd:long</td>
  <td>動画50％再生数です。※動画広告のみ。</td>
  <td>yes</td>
 </tr>
<tr>
  <td>videoViewsTo75</td>
  <td>xsd:long</td>
  <td>動画75％再生数です。※動画広告のみ。</td>
  <td>yes</td>
 </tr>
 <tr>
  <td>videoViewsTo95</td>
  <td>xsd:long</td>
  <td>動画95％再生数です。※動画広告のみ。</td>
  <td>yes</td>
 </tr>
 <tr>
  <td>videoViewsTo100</td>
  <td>xsd:long</td>
  <td>動画100％再生数です。※動画広告のみ。</td>
  <td>yes</td>
 </tr>
 <tr>
  <td>videoViewsTo3Sec</td>
  <td>xsd:long</td>
  <td>動画が3秒以上再生された回数です。※動画広告のみ。</td>
  <td>yes</td>
 </tr> 
 <tr>
  <td>averageRateVideoViewed</td>
  <td>xsd:double</td>
  <td>動画の平均再生率（動画が全体の長さの何％まで再生されたかの平均値）です。※動画広告のみ。</td>
  <td>yes</td>
 </tr>
 <tr>
  <td>averageDurationVideoViewed</td>
  <td>xsd:double</td>
  <td>動画の平均再生時間です。※動画広告のみ。</td>
  <td>yes</td>
 </tr>
</table>

<a rel="license" href="http://creativecommons.org/licenses/by-nd/2.1/jp/"><img alt="クリエイティブ・コモンズ・ライセンス" style="border-width:0" src="https://i.creativecommons.org/l/by-nd/2.1/jp/88x31.png" /></a><br />この 作品 は <a rel="license" href="http://creativecommons.org/licenses/by-nd/2.1/jp/">クリエイティブ・コモンズ 表示 - 改変禁止 2.1 日本 ライセンスの下に提供されています。</a>