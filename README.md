<p align="center"><img src="https://github.com/ABPindo/indonesianadblockrules/raw/master/src/ABPindo%202.png" width="240"></p>

# ABPindo
ABPindo merupakan filter tambahan untuk melengkapi [EasyList](https://subscribe.adblockplus.org/?location=https://easylist.to/easylist/easylist.txt&title=Easylist) memblokir iklan mengganggu di situs berbahasa Indonesia dan Malaysia. ABPindo menggunakan sintak [Adblock Plus](https://help.eyeo.com/en/adblockplus/how-to-write-filters), dan kompatibel dengan pengaya/ekstensi [uBlock](https://github.com/gorhill/uBlock#installation), [AdGuard](https://adguard.com/en/adguard-browser-extension/overview.html), atau adblocker sejenisnya.

## Keuntungan
- Tampilan lebih bersih </br>
Kita bisa lebih fokus terhadap konten website, tanpa risih atau terganggu oleh iklan.
- Terjaga dari penipuan </br>
Banyak iklan yang membaur bahkan menyamar menjadi tombol pembaruan program/ tombol download, setidaknya kita dapat terhindar dari penipuan.
- Lebih cepat </br>
Iklan animasi/video menjadi masalah bagi pengguna internet dengan akses terbatas. Tanpa iklan tersebut waktu membuka laman web menjadi lebih singkat.

## Cara Menggunakan
- Jalankan peramban web favoritmu (Firefox, Chrome, Opera, Safari, ...).
- Pasang pengaya/ekstensi [uBlock](https://github.com/gorhill/uBlock#installation), [AdGuard](https://adguard.com/en/adguard-browser-extension/overview.html), [Adblock Plus](https://adblockplus.org/en/), atau adblocker sejenisnya.
- Klik [subscribe ABPindo](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/ABPindo/indonesianadblockrules/master/subscriptions/abpindo.txt&title=ABPindo) atau pilih variasi sesuai kebutuhan.

## Langganan Filter utama
| Langganan|Keterangan|
| ------------- |-------------|
| [ABPindo](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/ABPindo/indonesianadblockrules/master/subscriptions/abpindo.txt&title=ABPindo)|Filter lengkap sebagai default [uBlock Origin](https://github.com/gorhill/uBlock#installation), [Adblock Plus](https://adblockplus.org/en/) regional Indonesia dan Malaysia|
| [ABPindo_noannoyance](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/ABPindo/indonesianadblockrules/master/subscriptions/abpindo_noannoyance.txt&title=ABPindo_noannoyance)|ABPindo tanpa filter annoyance (judi) |
| [ABPindo_noelementhide](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/ABPindo/indonesianadblockrules/master/subscriptions/abpindo_noelemhide.txt&title=ABPindo_noelementhide)|ABPindo tanpa filter element hide|

## Variasi filter ABPindo untuk DNS
|Sintak|ABPindo*|ABPindo_noannoyance**|
| ------------- |-------------|-------------|
|Hosts ([pi-hole](https://github.com/pi-hole/pi-hole)) |[link](https://raw.githubusercontent.com/ABPindo/indonesianadblockrules/master/subscriptions/hosts.txt)|[link](https://raw.githubusercontent.com/ABPindo/indonesianadblockrules/master/subscriptions/hosts_noannoyance.txt)|
|Domain|[link](https://raw.githubusercontent.com/ABPindo/indonesianadblockrules/master/subscriptions/domain.txt)|[link](https://raw.githubusercontent.com/ABPindo/indonesianadblockrules/master/subscriptions/domain_noannoyance.txt)|
|[AdGuard Home](https://github.com/AdguardTeam/AdGuardHome)|[link](https://raw.githubusercontent.com/ABPindo/indonesianadblockrules/master/subscriptions/abpindo_aghome.txt)|[link](https://raw.githubusercontent.com/ABPindo/indonesianadblockrules/master/subscriptions/abpindo_aghome_noannoyance.txt)|
|[Dnsmasq address=/](http://thekelleys.org.uk/gitweb/?p=dnsmasq.git)|[link](https://raw.githubusercontent.com/ABPindo/indonesianadblockrules/master/subscriptions/dnsmasq.txt)|[link](https://raw.githubusercontent.com/ABPindo/indonesianadblockrules/master/subscriptions/dnsmasq_noannoyance.txt)|
|[Dnsmasq server=/](http://thekelleys.org.uk/gitweb/?p=dnsmasq.git)|[link](https://raw.githubusercontent.com/ABPindo/indonesianadblockrules/master/subscriptions/dnsmasq_server.txt)|[link](https://raw.githubusercontent.com/ABPindo/indonesianadblockrules/master/subscriptions/dnsmasq_noannoyance_server.txt)|

keterangan
- *Filter lengkap sebagai default regional Indonesia dan Malaysia
- **ABPindo tanpa filter annoyance (judi)

## Ingin berkontribusi
Masih ada situs yang terlewat, entah karena situsnya telah diperbarui atau karena situsnya belum dijangkau ABPindo. Jika menemukan hal-hal tersebut bisa berkontribusi langsung melalui:
- [GitHub issue tracker](https://github.com/ABPindo/indonesianadblockrules/issues)
- [Submit a pull request](https://github.com/ABPindo/indonesianadblockrules/pulls)

## Pengaturan standar
Lingkungan pengujian Kami sebagai berikut:
- Peramban [Firefox](https://www.mozilla.org/id/firefox/).
- Pengaya [uBlock](https://github.com/gorhill/uBlock#installation).
- Filter : [EasyList](https://subscribe.adblockplus.org/?location=https://easylist.to/easylist/easylist.txt&title=Easylist), [EasyPrivacy](https://subscribe.adblockplus.org/?location=https://easylist.to/easylist/easyprivacy.txt&title=EasyPrivacy), [ABPindo](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/ABPindo/indonesianadblockrules/master/subscriptions/abpindo.txt&title=ABPindo) dan [uBlock filters](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/filters.txt&title=uBlock%20filters).

## Bagi pengembang
- [Kebijakan ABPindo tentang iklan](https://easylist.to/pages/policy.html)
- [Adblock Plus filters explained](https://adblockplus.org/filter-cheatsheet)
- [How to write filters | Adblock Plus Help Center](https://help.eyeo.com/en/adblockplus/how-to-write-filters)
- [How to create your own custom filter list : AdBlock Help](https://help.getadblock.com/support/solutions/articles/6000165012-how-to-create-your-own-personal-filter-list)
- [DNS filtering rules syntax | AdGuard Knowledgebase](https://kb.adguard.com/en/general/dns-filtering-syntax)
- [uBlock Static filter syntax](https://github.com/gorhill/uBlock/wiki/Static-filter-syntax)
- [Python-abp : utilities untuk rendering filter ABPindo](https://github.com/adblockplus/python-abp)
- Prasyarat: [Python](https://www.python.org/downloads/), [pip](https://pypi.org/project/pip/)

## Mirror
- [ABPindo GitLab](https://gitlab.com/ABPindo)
- [ABPindo GitLab Subscription](https://subscribe.adblockplus.org/?location=https://gitlab.com/ABPindo/indonesianadblockrules/raw/master/subscriptions/abpindo.txt&title=ABPindo)
