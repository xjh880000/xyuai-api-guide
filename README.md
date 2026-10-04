# AI 澶фā鍨?API 鎺ュ叆鎸囧崡

涓€浠界粰寮€鍙戣€呯殑瀹炵敤鎺ュ叆鎵嬪唽锛氭妸涓绘祦 AI 宸ュ叿鎺ュ埌缁熶竴鐨勫ぇ妯″瀷 API 缃戝叧銆?
閫傜敤鍦烘櫙锛氫綘鎵嬩笂鏈?Cursor銆丆line銆丏ify銆丆herry Studio銆丯extChat 杩欑被宸ュ叿锛屾兂鐢ㄤ竴涓?API 鍦板潃鍚屾椂璋冪敤 Gemini銆丆laude銆丟PT銆丟rok銆丏eepSeek 绛夊涓ā鍨嬶紝涓嶇敤涓€瀹朵竴瀹跺崟鐙敵璇枫€?
> 鏈枃绀轰緥缁熶竴浣跨敤 **灏忛奔API**锛?https://xyuai.cc>锛夛紝鎺ュ彛涓?OpenAI 鍏煎鍗忚銆?> 鎹㈡垚浠讳綍鍏朵粬 OpenAI 鍏煎缃戝叧锛屾妸 `base_url` 鏇挎崲鎺夊嵆鍙€?
---

## 涓€銆佸厛鐞嗚В锛氫粈涔堟槸銆孫penAI 鍏煎鍗忚銆?
澶ч儴鍒?AI 宸ュ叿閮芥敮鎸佽嚜瀹氫箟 API 鍦板潃锛屽垽鏂爣鍑嗗彧鏈変竴涓?鈥斺€?**瀹冭涓嶈 OpenAI 鐨勬帴鍙ｆ牸寮?*銆?
璁ょ殑璇濓紝浣犲彧闇€瑕佹敼涓や釜涓滆タ锛?
| 閰嶇疆椤?| 濉粈涔?|
|---|---|
| `base_url` / API 鍦板潃 | `https://xyuai.cc/v1` |
| `api_key` | 浣犺嚜宸辩敵璇风殑浠ょ墝锛坄sk-` 寮€澶达級 |

鏀瑰畬灏辫兘鐢紝宸ュ叿鏈韩涓嶇敤鍔ㄣ€?
**娉ㄦ剰**锛氬湴鍧€缁撳熬鐨?`/v1` 涓嶈兘灏戙€傚緢澶氬伐鍏锋姤 404锛屽氨鏄紡浜嗚繖涓€娈点€?
---

## 浜屻€佸悇宸ュ叿鍏蜂綋鎬庝箞濉?
### Cursor

`Settings` 鈫?`Models` 鈫?鎵撳紑 `OpenAI API Key` 寮€鍏?鈫?`Verify` 鏃佽竟濉細

```
Base URL:  https://xyuai.cc/v1
API Key:   sk-xxxxxxxx
```

鐒跺悗鍦?`Model names` 閲岀偣 `+` 娣诲姞浣犺鐢ㄧ殑妯″瀷鍚嶏紝渚嬪 `gemini-2.5-pro`銆乣claude-sonnet-4`銆?
> 甯歌鍧戯細Cursor 鍙妸璇锋眰鍙戠粰瀹冭璇嗙殑妯″瀷鍚嶃€傛ā鍨嬪悕鍐欓敊浼氱洿鎺ユ姤 `model not found`锛屽厛鍘绘ā鍨嬪垪琛ㄩ〉纭鍑嗙‘鎷煎啓銆?
### Cline锛圴S Code 鎻掍欢锛?
`Settings` 鈫?`API Provider` 閫?`OpenAI Compatible`锛?
```
Base URL:  https://xyuai.cc/v1
API Key:   sk-xxxxxxxx
Model ID:  gemini-2.5-pro
```

Cline 瀵逛笂涓嬫枃闀垮害鏁忔劅锛屽缓璁叧鎺?`Use compact prompt` 涔嬪鐨勮姳鍝ㄩ€夐」锛屽噺灏戞棤璋撶殑 token 娑堣€椼€?
### Dify

`璁剧疆` 鈫?`妯″瀷渚涘簲鍟哷 鈫?閫?`OpenAI` 鈫?娣诲姞鑷畾涔夋ā鍨嬶細

```
API Base URL:  https://xyuai.cc/v1
API Key:       sk-xxxxxxxx
```

Dify 闇€瑕佹墜鍔ㄥ～ `Model Name` 鍜?`Model Type`锛圠LM / Text Embedding / Rerank 瑕佸垎寮€鍔狅級锛屽姞閿欎簡浼氭姤绫诲瀷涓嶅尮閰嶃€?
### Cherry Studio

`璁剧疆` 鈫?`妯″瀷鏈嶅姟` 鈫?娣诲姞 `OpenAI` 绫诲瀷渚涘簲鍟嗭細

```
API 鍦板潃:  https://xyuai.cc/v1
API 瀵嗛挜:  sk-xxxxxxxx
```

鐒跺悗鍦ㄨ渚涘簲鍟嗕笅閫愪釜銆屾坊鍔犳ā鍨嬨€嶃€侰herry Studio 鏀寔涓€閿媺鍙栨ā鍨嬪垪琛紝鐪佷簨銆?
### NextChat

鐜鍙橀噺鎴栬缃〉濉細

```
BASE_URL=https://xyuai.cc/v1
OPENAI_API_KEY=sk-xxxxxxxx
CUSTOM_MODELS=+gemini-2.5-pro,+claude-sonnet-4
```

`CUSTOM_MODELS` 鍓嶉潰鐨?`+` 鏄€岃拷鍔犮€嶇殑鎰忔€濓紝鍘绘帀 `+` 浼氬彉鎴愩€屽彧淇濈暀杩欎簺銆嶃€?
---

## 涓夈€佹帴瀹屽悗甯歌鐨勫嚑涓姤閿?
**1. `404 Not Found`**
涔濇垚鏄?`base_url` 鍐欓敊銆傜‘璁や笁鐐癸細鏈夋病鏈?`https://`銆佺粨灏炬湁娌℃湁 `/v1`銆佹湁娌℃湁澶氫綑鏂滄潬锛坄/v1//chat/completions`锛夈€?
**2. `401 Unauthorized`**
浠ょ墝涓嶅鎴栨病鐢熸晥銆傛鏌ユ湁娌℃湁澶嶅埗鍒板浣欑┖鏍硷紝浠ュ強浠ょ墝鏄惁杩樺湪鏈夋晥鏈熷唴銆?
**3. `429 Too Many Requests`**
骞跺彂瓒呬簡銆傝涔堥檷浣庡苟鍙戯紙宸ュ叿閲屼竴鑸湁 `max concurrency` 璁剧疆锛夛紝瑕佷箞鍦ㄤ唬鐮侀噷鍔犳寚鏁伴€€閬块噸璇曘€?
**4. `model not found`**
妯″瀷鍚嶆嫾鍐欏拰瀹為檯涓嶄竴鑷淬€備互妯″瀷鍒楄〃椤电殑鍑嗙‘鍚嶇О涓哄噯锛屾敞鎰忔湁鐨勬ā鍨嬪甫鐗堟湰鍙枫€佹湁鐨勪笉甯︺€?
**5. 鍥炲涓€旀柇鎺?*
閫氬父鏄祦寮忥紙stream锛夎繛鎺ヨ涓棿鐜妭鎺愭柇銆傚厛璇曞叧鎺夋祦寮忥紱濡傛灉鍏虫帀灏辨甯革紝璇存槑鏄綉缁滈摼璺棶棰樸€?
---

## 鍥涖€佽嚜宸卞啓浠ｇ爜璋冪敤

Python锛?
```python
from openai import OpenAI

client = OpenAI(
    api_key="sk-xxxxxxxx",
    base_url="https://xyuai.cc/v1",
)

resp = client.chat.completions.create(
    model="gemini-2.5-pro",
    messages=[{"role": "user", "content": "浣犲ソ"}],
)
print(resp.choices[0].message.content)
```

Node.js锛?
```js
import OpenAI from "openai";

const client = new OpenAI({
  apiKey: "sk-xxxxxxxx",
  baseURL: "https://xyuai.cc/v1",
});

const resp = await client.chat.completions.create({
  model: "gemini-2.5-pro",
  messages: [{ role: "user", content: "浣犲ソ" }],
});
console.log(resp.choices[0].message.content);
```

鍏抽敭灏变竴鍙ワ細**`base_url` 鎸囧悜缃戝叧锛屽叾浣欎唬鐮佸拰鐢ㄥ畼鏂?SDK 瀹屽叏涓€鏍枫€?*

---

## 浜斻€佹垚鏈帶鍒?
鍑犱釜鑳芥槑鏄剧渷閽辩殑鍋氭硶锛?
1. **缁欎笉鍚岀敤閫斿垎閰嶄笉鍚屼护鐗?* 鈥斺€?璋冭瘯鐢ㄧ殑浠ょ墝鍗曠嫭涓€涓紝鏂逛究鐪嬬敤閲忥紝涔熸柟渚块殢鏃跺仠鎺夈€?2. **浼樺厛鐢ㄤ究瀹滄ā鍨嬪仛绮楃瓫** 鈥斺€?姣斿鍏堣灏忔ā鍨嬪垽鏂棶棰樼被鍨嬶紝鍐嶅喅瀹氳涓嶈浜ょ粰澶фā鍨嬨€?3. **鎺у埗涓婁笅鏂囬暱搴?* 鈥斺€?澶у鏁拌垂鐢ㄨ姳鍦ㄩ噸澶嶅彂閫佸巻鍙插璇濅笂锛岃兘瑁佸壀灏辫鍓€?4. **鎵归噺浠诲姟鐢ㄩ潪娴佸紡** 鈥斺€?娴佸紡閫傚悎浜や簰锛屾壒閲忚窇鏁版嵁鐢ㄩ潪娴佸紡鏇寸渷銆?
---

## 鐩稿叧閾炬帴

- 瀹樼綉锛?https://xyuai.cc>
- 妯″瀷涓庝环鏍硷細<https://xyuai.cc/products>
- 瀹屾暣鏁欑▼锛?0+ 绡囷級锛?https://xyuai.cc/guide/>
- 浣跨敤鏂囨。锛?https://xyuai.cc/docs/>

## 璁稿彲

鏈枃妗ｅ唴瀹瑰彲鑷敱杞浇锛屾敞鏄庡嚭澶勫嵆鍙€