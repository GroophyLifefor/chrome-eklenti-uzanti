# chrome-eklenti---uzantı-
uzantı yada eklenti nin temelini içerir

# nasıl kendi eklentimi yaparım
1) chrome://extensions/     bu linke git
2) geliştirici modunu aç
3) manifest.json'un içini düzelt
4) EKLENTİ klasörünü siteye sürükle
5) bitti.

# editlenmiş örnek
{

	"name": "deneme",
	"description": "açıklama",
	"version": "1.0",
	"manifest_version": 2,
	"browser_action":{
		"default_title": "deneme",
		"default_icon": "icon.png",
		"default_popup": "index.html"
		},

		"icons": {"150": "icon.png"}
}
