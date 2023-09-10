<p align="center">
  <a href="#build-framework">
  <img src="https://raw.githubusercontent.com/armbian/build/master/.github/armbian-logo.png" alt="Armbian logo" width="144">
  </a><br>
  <strong>Armbian Linux Runners Infrastructure</strong><br>
<br>
<a href=https://github.com/armbian/build/actions/workflows/build-train.yml><img alt="GitHub Workflow Status" src="https://img.shields.io/github/actions/workflow/status/armbian/build/build-train.yml?logo=githubactions&label=Kernel%20compile&logoColor=white&style=for-the-badge&branch=master"></a>
<img alt="GitHub Workflow Status" src="https://img.shields.io/badge/dynamic/json?label=CPU%20COUNT&query=CPU&cacheSeconds=10&style=for-the-badge&url=https%3A%2F%2Fgithub.com%2Farmbian%2Fscripts%2Freleases%2Fdownload%2Fstatus%2Frunners_capacity.json"> <img alt="GitHub Workflow Status" src="https://img.shields.io/badge/dynamic/json?label=MEMORY%20in%20MB&query=MEM&cacheSeconds=10&style=for-the-badge&url=https%3A%2F%2Fgithub.com%2Farmbian%2Fscripts%2Freleases%2Fdownload%2Fstatus%2Frunners_capacity.json">
</p>
<p align=center>
<a href=https://armbian.com/download><img alt="Armbian Linux stable" src="https://img.shields.io/badge/dynamic/json?label=Armbian%20Linux%20current&query=CURRENT&color=f71000&cacheSeconds=600&style=for-the-badge&url=https%3A%2F%2Fgithub.com%2Farmbian%2Fscripts%2Freleases%2Fdownload%2Fstatus%2Frunners_capacity.json"></a>
<a href=https://github.com/armbian/community><img alt="Armbian Linux rolling" src="https://img.shields.io/badge/dynamic/json?label=Armbian%20Linux%20edge&query=EDGE&color=34be5b&cacheSeconds=600&style=for-the-badge&url=https%3A%2F%2Fgithub.com%2Farmbian%2Fscripts%2Freleases%2Fdownload%2Fstatus%2Frunners_capacity.json"></a>
</p>


|Donated by &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| Virtual CPU cores |Memory&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|
|--|--:|--:|
|Cats|12|15 Gb|
|GitHub|40|136 Gb|
|Hristov|16|15 Gb|
|Igor|232|433 Gb|
|JetHub|12|64 Gb|
|Lane|32|31 Gb|
|Werner|16|62 Gb|
|Xogium|12|7 Gb|
## Donating Virtual Machine to Armbian?

Our CI engine is hungry for CPU and memory resources. In case you have spare resources and you would like to donate it to Armbian, you can do it this way:

We divide runners by arhitecture (ARM64 or X86) and size (big/small).

1. Memory = 6Gb for "small", 16Gb for "big"
3. Core count = 4 for "small", 12 + for "big"
4. Space = 64Gb

https://www.armbian.com/contact/
<!--START_SECTION:data-section-->
<table width="100%"><tr><td align="left"><a id=Board ID href=#Board ID><b>Board name</b></a></td><td align=left><b>Logs</b></td><td align=right><b>Kernel version</b></td><td align=right><b>Iperf</b></td><td align=right><b>7z -b</b></td></tr><tr><td align="left"><a id=uefi-x86 href=#uefi-x86>UEFI x86</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=uefi-x86 href=#uefi-x86>UEFI x86</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=uefi-x86 href=#uefi-x86>UEFI x86</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=uefi-x86 href=#uefi-x86>UEFI x86</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=uefi-x86 href=#uefi-x86>UEFI x86</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=uefi-x86 href=#uefi-x86>UEFI x86</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=clearfogpro href=#clearfogpro>Clearfog Pro</a></td><td align=left>https://paste.armbian.com/</td><td align=right>6.1.52-current-mvebu</td><td align=right>895</td><td align=right>2221</td></tr><tr><td align="left"><a id=clearfogpro href=#clearfogpro>Clearfog Pro</a></td><td align=left>https://paste.armbian.com/</td><td align=right>6.1.50-current-mvebu</td><td align=right>890</td><td align=right>2225</td></tr><tr><td align="left"><a id=clearfogpro href=#clearfogpro>Clearfog Pro</a></td><td align=left>https://paste.armbian.com/</td><td align=right>6.2.16-edge-mvebu</td><td align=right>890</td><td align=right>2226</td></tr><tr><td align="left"><a id=clearfogpro href=#clearfogpro>Clearfog Pro</a></td><td align=left>https://paste.armbian.com/</td><td align=right>6.2.16-edge-mvebu</td><td align=right>829</td><td align=right>2223</td></tr><tr><td align="left"><a id=khadas-vim3 href=#khadas-vim3>Khadas VIM3</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=khadas-vim3 href=#khadas-vim3>Khadas VIM3</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=khadas-vim3 href=#khadas-vim3>Khadas VIM3</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=khadas-vim3 href=#khadas-vim3>Khadas VIM3</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=zeropi href=#zeropi>ZeroPi</a></td><td align=left>https://paste.armbian.com/dozeyidefi</td><td align=right>5.15.130-legacy-sunxi</td><td align=right>538</td><td align=right>2689</td></tr><tr><td align="left"><a id=zeropi href=#zeropi>ZeroPi</a></td><td align=left>https://paste.armbian.com/qupikicija</td><td align=right>5.15.127-legacy-sunxi</td><td align=right>535</td><td align=right>2688</td></tr><tr><td align="left"><a id=zeropi href=#zeropi>ZeroPi</a></td><td align=left>https://paste.armbian.com/qowayiqefu</td><td align=right>6.1.51-current-sunxi</td><td align=right>606</td><td align=right>2707</td></tr><tr><td align="left"><a id=zeropi href=#zeropi>ZeroPi</a></td><td align=left>https://paste.armbian.com/evawoqiniq</td><td align=right>6.1.47-current-sunxi</td><td align=right>598</td><td align=right>2704</td></tr><tr><td align="left"><a id=zeropi href=#zeropi>ZeroPi</a></td><td align=left>https://paste.armbian.com/rezapocebi</td><td align=right>6.5.1-edge-sunxi</td><td align=right>545</td><td align=right>2698</td></tr><tr><td align="left"><a id=zeropi href=#zeropi>ZeroPi</a></td><td align=left>https://paste.armbian.com/boruliluta</td><td align=right>6.4.12-edge-sunxi</td><td align=right>459</td><td align=right>2698</td></tr><tr><td align="left"><a id=orangepiwin href=#orangepiwin>Orange Pi Win</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=orangepiwin href=#orangepiwin>Orange Pi Win</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=orangepiwin href=#orangepiwin>Orange Pi Win</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=orangepiwin href=#orangepiwin>Orange Pi Win</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=nanopineo2black href=#nanopineo2black>NanoPi Neo 2 Black</a></td><td align=left>https://paste.armbian.com/hukihaxiga</td><td align=right>5.15.130-legacy-sunxi64</td><td align=right>851</td><td align=right>2836</td></tr><tr><td align="left"><a id=nanopineo2black href=#nanopineo2black>NanoPi Neo 2 Black</a></td><td align=left>https://paste.armbian.com/gijawutivu</td><td align=right>5.15.127-legacy-sunxi64</td><td align=right>835</td><td align=right>2481</td></tr><tr><td align="left"><a id=nanopineo2black href=#nanopineo2black>NanoPi Neo 2 Black</a></td><td align=left>https://paste.armbian.com/radatavavo</td><td align=right>6.1.51-current-sunxi64</td><td align=right>760</td><td align=right>2686</td></tr><tr><td align="left"><a id=nanopineo2black href=#nanopineo2black>NanoPi Neo 2 Black</a></td><td align=left>https://paste.armbian.com/eduzuhumip</td><td align=right>6.1.47-current-sunxi64</td><td align=right>820</td><td align=right>2621</td></tr><tr><td align="left"><a id=nanopineo2black href=#nanopineo2black>NanoPi Neo 2 Black</a></td><td align=left>https://paste.armbian.com/woraqiyihe</td><td align=right>6.5.1-edge-sunxi64</td><td align=right>824</td><td align=right>2582</td></tr><tr><td align="left"><a id=nanopineo2black href=#nanopineo2black>NanoPi Neo 2 Black</a></td><td align=left>https://paste.armbian.com/esevafupaj</td><td align=right>6.4.12-edge-sunxi64</td><td align=right>826</td><td align=right>2583</td></tr><tr><td align="left"><a id=cubietruck href=#cubietruck>Cubietruck</a></td><td align=left>https://paste.armbian.com/avefapeled</td><td align=right>6.1.51-current-sunxi</td><td align=right>158</td><td align=right>823</td></tr><tr><td align="left"><a id=cubietruck href=#cubietruck>Cubietruck</a></td><td align=left>https://paste.armbian.com/jofiruligi</td><td align=right>6.1.47-current-sunxi</td><td align=right>215</td><td align=right>824</td></tr><tr><td align="left"><a id=orangepizero href=#orangepizero>Orange Pi Zero</a></td><td align=left>https://paste.armbian.com/kuqegusera</td><td align=right>5.15.130-legacy-sunxi</td><td align=right>90</td><td align=right>2578</td></tr><tr><td align="left"><a id=orangepizero href=#orangepizero>Orange Pi Zero</a></td><td align=left>https://paste.armbian.com/hijadegayo</td><td align=right>5.15.127-legacy-sunxi</td><td align=right>90</td><td align=right>2471</td></tr><tr><td align="left"><a id=orangepizero href=#orangepizero>Orange Pi Zero</a></td><td align=left>https://paste.armbian.com/lenibucohu</td><td align=right>6.1.51-current-sunxi</td><td align=right>90</td><td align=right>2604</td></tr><tr><td align="left"><a id=orangepizero href=#orangepizero>Orange Pi Zero</a></td><td align=left>https://paste.armbian.com/enoqizumet</td><td align=right>6.1.47-current-sunxi</td><td align=right>90</td><td align=right>2541</td></tr><tr><td align="left"><a id=orangepizero href=#orangepizero>Orange Pi Zero</a></td><td align=left>https://paste.armbian.com/movasewoyi</td><td align=right>6.5.1-edge-sunxi</td><td align=right>89</td><td align=right>2366</td></tr><tr><td align="left"><a id=orangepizero href=#orangepizero>Orange Pi Zero</a></td><td align=left>https://paste.armbian.com/oxekiwelap</td><td align=right>6.4.12-edge-sunxi</td><td align=right>90</td><td align=right>2427</td></tr><tr><td align="left"><a id=orangepizeroplus href=#orangepizeroplus>Orange Pi Zero Plus</a></td><td align=left>https://paste.armbian.com/onuzoyadek</td><td align=right>6.1.51-current-sunxi64</td><td align=right>837</td><td align=right>2557</td></tr><tr><td align="left"><a id=orangepizeroplus href=#orangepizeroplus>Orange Pi Zero Plus</a></td><td align=left>https://paste.armbian.com/acutisicaz</td><td align=right>6.1.47-current-sunxi64</td><td align=right>852</td><td align=right>2590</td></tr><tr><td align="left"><a id=orangepizeroplus href=#orangepizeroplus>Orange Pi Zero Plus</a></td><td align=left>https://paste.armbian.com/ewajuqiyiy</td><td align=right>6.5.1-edge-sunxi64</td><td align=right>834</td><td align=right>2678</td></tr><tr><td align="left"><a id=orangepizeroplus href=#orangepizeroplus>Orange Pi Zero Plus</a></td><td align=left>https://paste.armbian.com/joholicoqo</td><td align=right>6.4.12-edge-sunxi64</td><td align=right>835</td><td align=right>2580</td></tr><tr><td align="left"><a id=rockpi-e href=#rockpi-e>Rockpi E</a></td><td align=left>https://paste.armbian.com/ibupibukey</td><td align=right>6.1.52-current-rockchip64</td><td align=right>90</td><td align=right>3406</td></tr><tr><td align="left"><a id=rockpi-e href=#rockpi-e>Rockpi E</a></td><td align=left>https://paste.armbian.com/vejemamuji</td><td align=right>6.1.50-current-rockchip64</td><td align=right>93</td><td align=right>3381</td></tr><tr><td align="left"><a id=rockpi-e href=#rockpi-e>Rockpi E</a></td><td align=left>https://paste.armbian.com/bibukekenu</td><td align=right>6.5.2-edge-rockchip64</td><td align=right>90</td><td align=right>3294</td></tr><tr><td align="left"><a id=rockpi-e href=#rockpi-e>Rockpi E</a></td><td align=left>https://paste.armbian.com/idozapebix</td><td align=right>6.4.13-edge-rockchip64</td><td align=right>89</td><td align=right>3352</td></tr><tr><td align="left"><a id=rockpi-4b href=#rockpi-4b>Rockpi 4B</a></td><td align=left>https://paste.armbian.com/ayadamadix</td><td align=right>6.1.52-current-rockchip64</td><td align=right>850</td><td align=right>6434</td></tr><tr><td align="left"><a id=rockpi-4b href=#rockpi-4b>Rockpi 4B</a></td><td align=left>https://paste.armbian.com/tigatagaro</td><td align=right>6.1.50-current-rockchip64</td><td align=right>880</td><td align=right>6405</td></tr><tr><td align="left"><a id=rockpi-4b href=#rockpi-4b>Rockpi 4B</a></td><td align=left>https://paste.armbian.com/loxireseju</td><td align=right>6.5.2-edge-rockchip64</td><td align=right>890</td><td align=right>6336</td></tr><tr><td align="left"><a id=rockpi-4b href=#rockpi-4b>Rockpi 4B</a></td><td align=left>https://paste.armbian.com/meyaxirugi</td><td align=right>6.4.13-edge-rockchip64</td><td align=right>910</td><td align=right>6316</td></tr><tr><td align="left"><a id=orangepi-r1plus-lts href=#orangepi-r1plus-lts>Orange Pi R1 Plus LTS</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=orangepi-r1plus-lts href=#orangepi-r1plus-lts>Orange Pi R1 Plus LTS</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=orangepi-r1plus-lts href=#orangepi-r1plus-lts>Orange Pi R1 Plus LTS</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=orangepi-r1plus-lts href=#orangepi-r1plus-lts>Orange Pi R1 Plus LTS</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=orangepi-r1 href=#orangepi-r1>Orange Pi R1</a></td><td align=left>https://paste.armbian.com/amuyebohaj</td><td align=right>6.1.51-current-sunxi</td><td align=right>90</td><td align=right>2810</td></tr><tr><td align="left"><a id=orangepi-r1 href=#orangepi-r1>Orange Pi R1</a></td><td align=left>https://paste.armbian.com/yiriwikupa</td><td align=right>6.1.47-current-sunxi</td><td align=right>90</td><td align=right>2775</td></tr><tr><td align="left"><a id=orangepi-r1 href=#orangepi-r1>Orange Pi R1</a></td><td align=left>https://paste.armbian.com/wozijaveci</td><td align=right>6.5.1-edge-sunxi</td><td align=right>89</td><td align=right>2453</td></tr><tr><td align="left"><a id=orangepi-r1 href=#orangepi-r1>Orange Pi R1</a></td><td align=left>https://paste.armbian.com/bucukeyate</td><td align=right>6.4.12-edge-sunxi</td><td align=right>90</td><td align=right>2444</td></tr><tr><td align="left"><a id=pineh64 href=#pineh64>Pine H64</a></td><td align=left>https://paste.armbian.com/nukujituca</td><td align=right>6.1.51-current-sunxi64</td><td align=right>836</td><td align=right>4057</td></tr><tr><td align="left"><a id=pineh64 href=#pineh64>Pine H64</a></td><td align=left>https://paste.armbian.com/xawesagufi</td><td align=right>6.1.47-current-sunxi64</td><td align=right>908</td><td align=right>3924</td></tr><tr><td align="left"><a id=pineh64 href=#pineh64>Pine H64</a></td><td align=left>https://paste.armbian.com/uqasupupum</td><td align=right>6.5.1-edge-sunxi64</td><td align=right>881</td><td align=right>3871</td></tr><tr><td align="left"><a id=pineh64 href=#pineh64>Pine H64</a></td><td align=left>https://paste.armbian.com/kacovelofo</td><td align=right>6.4.12-edge-sunxi64</td><td align=right>678</td><td align=right>3813</td></tr><tr><td align="left"><a id=rockpro64 href=#rockpro64>RockPro 64</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=rockpro64 href=#rockpro64>RockPro 64</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=rockpro64 href=#rockpro64>RockPro 64</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=rockpro64 href=#rockpro64>RockPro 64</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=odroidc2 href=#odroidc2>Odroid C2</a></td><td align=left>https://paste.armbian.com/ewezerupob</td><td align=right>6.1.52-current-meson64</td><td align=right>890</td><td align=right>3957</td></tr><tr><td align="left"><a id=odroidc2 href=#odroidc2>Odroid C2</a></td><td align=left>https://paste.armbian.com/paqulawime</td><td align=right>6.1.50-current-meson64</td><td align=right>881</td><td align=right>3890</td></tr><tr><td align="left"><a id=odroidc2 href=#odroidc2>Odroid C2</a></td><td align=left>https://paste.armbian.com/ibekahoyaf</td><td align=right>6.5.2-edge-meson64</td><td align=right>890</td><td align=right>4006</td></tr><tr><td align="left"><a id=odroidc2 href=#odroidc2>Odroid C2</a></td><td align=left>https://paste.armbian.com/iqohijabun</td><td align=right>6.4.13-edge-meson64</td><td align=right>890</td><td align=right>4067</td></tr><tr><td align="left"><a id=orangepi5 href=#orangepi5>Orange Pi 5</a></td><td align=left>https://paste.armbian.com/amocomayex</td><td align=right>5.10.160-legacy-rk35xx</td><td align=right>950</td><td align=right>15769</td></tr><tr><td align="left"><a id=orangepi5 href=#orangepi5>Orange Pi 5</a></td><td align=left>https://paste.armbian.com/yayecuhima</td><td align=right>5.10.160-legacy-rk35xx</td><td align=right>890</td><td align=right>15805</td></tr><tr><td align="left"><a id=orangepi5 href=#orangepi5>Orange Pi 5</a></td><td align=left>https://paste.armbian.com/yayecuhima</td><td align=right>5.10.160-legacy-rk35xx</td><td align=right>890</td><td align=right>15805</td></tr><tr><td align="left"><a id=orangepi5 href=#orangepi5>Orange Pi 5</a></td><td align=left>https://paste.armbian.com/yayecuhima</td><td align=right>5.10.160-legacy-rk35xx</td><td align=right>890</td><td align=right>15805</td></tr><tr><td align="left"><a id=nanopi-r6s href=#nanopi-r6s>NanoPi R6S</a></td><td align=left>https://paste.armbian.com/gugasupiji</td><td align=right>5.10.160-legacy-rk35xx</td><td align=right>880</td><td align=right>15694</td></tr><tr><td align="left"><a id=nanopi-r6s href=#nanopi-r6s>NanoPi R6S</a></td><td align=left>https://paste.armbian.com/evaliluqez</td><td align=right>5.10.160-legacy-rk35xx</td><td align=right>890</td><td align=right>15657</td></tr><tr><td align="left"><a id=orangepi3-lts href=#orangepi3-lts>Orange Pi 3 LTS</a></td><td align=left>https://paste.armbian.com/acemubapar</td><td align=right>6.1.51-current-sunxi64</td><td align=right>877</td><td align=right>4015</td></tr><tr><td align="left"><a id=orangepi3-lts href=#orangepi3-lts>Orange Pi 3 LTS</a></td><td align=left>https://paste.armbian.com/alotipevit</td><td align=right>6.1.47-current-sunxi64</td><td align=right>870</td><td align=right>3929</td></tr><tr><td align="left"><a id=orangepi3-lts href=#orangepi3-lts>Orange Pi 3 LTS</a></td><td align=left>https://paste.armbian.com/kogogehese</td><td align=right>6.5.1-edge-sunxi64</td><td align=right>820</td><td align=right>3890</td></tr><tr><td align="left"><a id=orangepi3-lts href=#orangepi3-lts>Orange Pi 3 LTS</a></td><td align=left>https://paste.armbian.com/ukerovuyez</td><td align=right>6.4.12-edge-sunxi64</td><td align=right>870</td><td align=right>3869</td></tr><tr><td align="left"><a id=odroidc4 href=#odroidc4>Odroid C4</a></td><td align=left>https://paste.armbian.com/ufinutoqoc</td><td align=right>6.1.52-current-meson64</td><td align=right>800</td><td align=right>5634</td></tr><tr><td align="left"><a id=odroidc4 href=#odroidc4>Odroid C4</a></td><td align=left>https://paste.armbian.com/lugiyolori</td><td align=right>6.1.50-current-meson64</td><td align=right>890</td><td align=right>5665</td></tr><tr><td align="left"><a id=odroidc4 href=#odroidc4>Odroid C4</a></td><td align=left>https://paste.armbian.com/dedeqewutu</td><td align=right>6.5.2-edge-meson64</td><td align=right>890</td><td align=right>5671</td></tr><tr><td align="left"><a id=odroidc4 href=#odroidc4>Odroid C4</a></td><td align=left>https://paste.armbian.com/sesahabilu</td><td align=right>6.4.13-edge-meson64</td><td align=right>890</td><td align=right>5655</td></tr><tr><td align="left"><a id=nanopim4 href=#nanopim4>NanoPi M4</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=nanopim4 href=#nanopim4>NanoPi M4</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=nanopim4 href=#nanopim4>NanoPi M4</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=nanopim4 href=#nanopim4>NanoPi M4</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=nanopi-r4s href=#nanopi-r4s>NanoPi R4S</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=nanopi-r4s href=#nanopi-r4s>NanoPi R4S</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=nanopi-r4s href=#nanopi-r4s>NanoPi R4S</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=nanopi-r4s href=#nanopi-r4s>NanoPi R4S</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=odroidn2 href=#odroidn2>Odroid N2</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=odroidn2 href=#odroidn2>Odroid N2</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=odroidn2 href=#odroidn2>Odroid N2</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=odroidn2 href=#odroidn2>Odroid N2</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=orangepi3 href=#orangepi3>Orange Pi 3</a></td><td align=left>https://paste.armbian.com/qabikolimu</td><td align=right>6.1.51-current-sunxi64</td><td align=right>943</td><td align=right>4474</td></tr><tr><td align="left"><a id=orangepi3 href=#orangepi3>Orange Pi 3</a></td><td align=left>https://paste.armbian.com/uzifujopoz</td><td align=right>6.1.47-current-sunxi64</td><td align=right>864</td><td align=right>4275</td></tr><tr><td align="left"><a id=orangepi3 href=#orangepi3>Orange Pi 3</a></td><td align=left>https://paste.armbian.com/uloporuhun</td><td align=right>6.5.1-edge-sunxi64</td><td align=right>870</td><td align=right>4198</td></tr><tr><td align="left"><a id=orangepi3 href=#orangepi3>Orange Pi 3</a></td><td align=left>https://paste.armbian.com/wunopibido</td><td align=right>6.4.12-edge-sunxi64</td><td align=right>840</td><td align=right>4110</td></tr><tr><td align="left"><a id=nanopineo3 href=#nanopineo3>NanoPi Neo 3</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=nanopineo3 href=#nanopineo3>NanoPi Neo 3</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=nanopineo3 href=#nanopineo3>NanoPi Neo 3</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=nanopineo3 href=#nanopineo3>NanoPi Neo 3</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=lime-a64 href=#lime-a64>A64 OLinuXino</a></td><td align=left>https://paste.armbian.com/ilekojugir</td><td align=right>5.15.130-legacy-sunxi64</td><td align=right>939</td><td align=right>2878</td></tr><tr><td align="left"><a id=lime-a64 href=#lime-a64>A64 OLinuXino</a></td><td align=left>https://paste.armbian.com/gacasoseyi</td><td align=right>5.15.127-legacy-sunxi64</td><td align=right>673</td><td align=right>2547</td></tr><tr><td align="left"><a id=lime-a64 href=#lime-a64>A64 OLinuXino</a></td><td align=left>https://paste.armbian.com/opelitefex</td><td align=right>6.1.51-current-sunxi64</td><td align=right>885</td><td align=right>2868</td></tr><tr><td align="left"><a id=lime-a64 href=#lime-a64>A64 OLinuXino</a></td><td align=left>https://paste.armbian.com/jasanohezu</td><td align=right>6.1.47-current-sunxi64</td><td align=right>888</td><td align=right>2801</td></tr><tr><td align="left"><a id=lime-a64 href=#lime-a64>A64 OLinuXino</a></td><td align=left>https://paste.armbian.com/ejalofogik</td><td align=right>6.5.1-edge-sunxi64</td><td align=right>878</td><td align=right>2837</td></tr><tr><td align="left"><a id=odroidm1 href=#odroidm1>ODROID M1</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=odroidm1 href=#odroidm1>ODROID M1</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=tinkerboard-2 href=#tinkerboard-2>Tinker Board 2</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=tinkerboard-2 href=#tinkerboard-2>Tinker Board 2</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=tinkerboard-2 href=#tinkerboard-2>Tinker Board 2</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=tinkerboard-2 href=#tinkerboard-2>Tinker Board 2</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=orangepi4-lts href=#orangepi4-lts>Orange Pi 4 LTS</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=orangepi4-lts href=#orangepi4-lts>Orange Pi 4 LTS</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=orangepi4-lts href=#orangepi4-lts>Orange Pi 4 LTS</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=orangepi4-lts href=#orangepi4-lts>Orange Pi 4 LTS</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=lepotato href=#lepotato>Le potato</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=lepotato href=#lepotato>Le potato</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=lepotato href=#lepotato>Le potato</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=lepotato href=#lepotato>Le potato</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=bananapim2ultra href=#bananapim2ultra>Banana Pi M2 Ultra</a></td><td align=left>https://paste.armbian.com/ihubihusof</td><td align=right>6.1.51-current-sunxi</td><td align=right>838</td><td align=right>2725</td></tr><tr><td align="left"><a id=bananapim2ultra href=#bananapim2ultra>Banana Pi M2 Ultra</a></td><td align=left>https://paste.armbian.com/ziruwubafu</td><td align=right>6.1.47-current-sunxi</td><td align=right>808</td><td align=right>2725</td></tr><tr><td align="left"><a id=bananapicm4io href=#bananapicm4io>Banana Pi CM4IO</a></td><td align=left>https://paste.armbian.com/uwuwukatez</td><td align=right>6.1.52-current-meson64</td><td align=right>890</td><td align=right>9046</td></tr><tr><td align="left"><a id=bananapicm4io href=#bananapicm4io>Banana Pi CM4IO</a></td><td align=left>https://paste.armbian.com/hajogojepi</td><td align=right>6.1.50-current-meson64</td><td align=right>890</td><td align=right>8569</td></tr><tr><td align="left"><a id=bananapicm4io href=#bananapicm4io>Banana Pi CM4IO</a></td><td align=left>https://paste.armbian.com/abaqeqizar</td><td align=right>6.5.2-edge-meson64</td><td align=right>890</td><td align=right>8541</td></tr><tr><td align="left"><a id=bananapicm4io href=#bananapicm4io>Banana Pi CM4IO</a></td><td align=left>https://paste.armbian.com/mijutelaha</td><td align=right>6.4.13-edge-meson64</td><td align=right>800</td><td align=right>8546</td></tr><tr><td align="left"><a id=bananapim5 href=#bananapim5>Banana Pi M5</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=bananapim5 href=#bananapim5>Banana Pi M5</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=bananapim5 href=#bananapim5>Banana Pi M5</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=bananapim5 href=#bananapim5>Banana Pi M5</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=tinkerboard href=#tinkerboard>Tinker Board</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=tinkerboard href=#tinkerboard>Tinker Board</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=tinkerboard href=#tinkerboard>Tinker Board</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=tinkerboard href=#tinkerboard>Tinker Board</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=bigtreetech-cb1 href=#bigtreetech-cb1>BigTreeTech CB1</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=bigtreetech-cb1 href=#bigtreetech-cb1>BigTreeTech CB1</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=orangepi5-plus href=#orangepi5-plus>Orange Pi 5 Plus</a></td><td align=left>https://paste.armbian.com/abemufajaj</td><td align=right>5.10.160-legacy-rk35xx</td><td align=right>890</td><td align=right>15623</td></tr><tr><td align="left"><a id=orangepi5-plus href=#orangepi5-plus>Orange Pi 5 Plus</a></td><td align=left>https://paste.armbian.com/apafefukuh</td><td align=right>5.10.160-legacy-rk35xx</td><td align=right>890</td><td align=right>15577</td></tr><tr><td align="left"><a id=orangepi5-plus href=#orangepi5-plus>Orange Pi 5 Plus</a></td><td align=left>https://paste.armbian.com/apafefukuh</td><td align=right>5.10.160-legacy-rk35xx</td><td align=right>890</td><td align=right>15577</td></tr><tr><td align="left"><a id=orangepi5-plus href=#orangepi5-plus>Orange Pi 5 Plus</a></td><td align=left>https://paste.armbian.com/apafefukuh</td><td align=right>5.10.160-legacy-rk35xx</td><td align=right>890</td><td align=right>15577</td></tr><tr><td align="left"><a id=udoo href=#udoo>Udoo</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=udoo href=#udoo>Udoo</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=udoo href=#udoo>Udoo</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=udoo href=#udoo>Udoo</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=khadas-vim2 href=#khadas-vim2>Khadas VIM2</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=khadas-vim2 href=#khadas-vim2>Khadas VIM2</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=khadas-vim2 href=#khadas-vim2>Khadas VIM2</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=khadas-vim2 href=#khadas-vim2>Khadas VIM2</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=khadas-vim1 href=#khadas-vim1>Khadas VIM1</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=khadas-vim1 href=#khadas-vim1>Khadas VIM1</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=khadas-vim1 href=#khadas-vim1>Khadas VIM1</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=khadas-vim1 href=#khadas-vim1>Khadas VIM1</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=nanopi-r2s href=#nanopi-r2s>Nanopi R2S</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=nanopi-r2s href=#nanopi-r2s>Nanopi R2S</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=nanopi-r2s href=#nanopi-r2s>Nanopi R2S</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=nanopi-r2s href=#nanopi-r2s>Nanopi R2S</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=nanopi-r1 href=#nanopi-r1>NanoPi R1</a></td><td align=left>https://paste.armbian.com/odeyoqukig</td><td align=right>5.15.130-legacy-sunxi</td><td align=right>90</td><td align=right>2775</td></tr><tr><td align="left"><a id=nanopi-r1 href=#nanopi-r1>NanoPi R1</a></td><td align=left>https://paste.armbian.com/ihudesilum</td><td align=right>5.15.127-legacy-sunxi</td><td align=right>90</td><td align=right>2774</td></tr><tr><td align="left"><a id=nanopi-r1 href=#nanopi-r1>NanoPi R1</a></td><td align=left>https://paste.armbian.com/isifevumoj</td><td align=right>6.1.51-current-sunxi</td><td align=right>90</td><td align=right>2777</td></tr><tr><td align="left"><a id=nanopi-r1 href=#nanopi-r1>NanoPi R1</a></td><td align=left>https://paste.armbian.com/wukunetidi</td><td align=right>6.1.47-current-sunxi</td><td align=right>90</td><td align=right>2777</td></tr><tr><td align="left"><a id=nanopi-r1 href=#nanopi-r1>NanoPi R1</a></td><td align=left>https://paste.armbian.com/adovemohol</td><td align=right>6.5.1-edge-sunxi</td><td align=right>91</td><td align=right>2763</td></tr><tr><td align="left"><a id=nanopi-r1 href=#nanopi-r1>NanoPi R1</a></td><td align=left>https://paste.armbian.com/ekiyonisoj</td><td align=right>6.4.12-edge-sunxi</td><td align=right>90</td><td align=right>2772</td></tr><tr><td align="left"><a id=orangepizero2 href=#orangepizero2>Orange Pi Zero2</a></td><td align=left>https://paste.armbian.com/ruvilobeje</td><td align=right>6.1.51-current-sunxi64</td><td align=right>841</td><td align=right>3139</td></tr><tr><td align="left"><a id=orangepizero2 href=#orangepizero2>Orange Pi Zero2</a></td><td align=left>https://paste.armbian.com/ijiyutikar</td><td align=right>6.1.47-current-sunxi64</td><td align=right>90</td><td align=right>3151</td></tr><tr><td align="left"><a id=orangepizero2 href=#orangepizero2>Orange Pi Zero2</a></td><td align=left>https://paste.armbian.com/erugolojin</td><td align=right>6.5.1-edge-sunxi64</td><td align=right>828</td><td align=right>3084</td></tr><tr><td align="left"><a id=orangepizero2 href=#orangepizero2>Orange Pi Zero2</a></td><td align=left>https://paste.armbian.com/uqubupitah</td><td align=right>6.4.12-edge-sunxi64</td><td align=right>826</td><td align=right>3134</td></tr><tr><td align="left"><a id=orangepioneplus href=#orangepioneplus>Orange Pi One+</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=orangepioneplus href=#orangepioneplus>Orange Pi One+</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=orangepioneplus href=#orangepioneplus>Orange Pi One+</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=orangepioneplus href=#orangepioneplus>Orange Pi One+</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=orangepioneplus href=#orangepioneplus>Orange Pi One+</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr><tr><td align="left"><a id=orangepioneplus href=#orangepioneplus>Orange Pi One+</a></td><td align=left>n/a</td><td align=right>n/a</td><td align=right>n/a</td><td align=right>n/a</td></tr></table>
<!--END_SECTION:data-section-->
