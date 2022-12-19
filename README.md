# Fivem egzoz patlatma
Gereksinimler : 
Torpak-Notify ( https://www.fivemturk.com/threads/ucretsiz-edrp-exrp-inspired-notify-standalone.43067/#post-317211 )<br>
QbCore Progressbar ( https://github.com/Project-Sloth/progressbar )<br>
QbCore Paket
<br>
not : Yazılan gereksinimler script dosyasının içerisinde bulunmakta haberin olsun
<br>
script in orjisi bu knk : https://forum.cfx.re/t/release-standalone-2-step-als-anti-lag-system/1057327
<br>
script videosu bu : https://streamable.com/mrkams
## \qb-core\shared\items.lua
```lua
	['egzozkumandasi'] 			 	 = {['name'] = 'egzozkumandasi',     			['label'] = 'Egzoz kumandası', 			['weight'] = 500, 		['type'] = 'item', 		['image'] = 'egzozkumandasi.png', 		['unique'] = true, 		['useable'] = true, 	['shouldClose'] = true,    ['combinable'] = nil,   ['description'] = 'çatarapatara dolasicam itemi'},
```
## Whitelist sistemi
Egzoz patlatma sistemini istediğiniz araca ayarlamak için Config.lua sına bakman lazım ordan araç kodunu whitelist e ekelemn gerek
