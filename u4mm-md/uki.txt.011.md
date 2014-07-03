##FireFTP for Firefox

FireFTP (http://fireftp.mozdev.org/) သည္ Firefox extension တြင္ FTP transfers အတြက္ျဖစ္သည္။

##Firefox Widgets

Firefox တြင္ browser bar ရွိ drop-down list အားပိတ္ထားရန္။

၎သည္ Firefox တြင္ တစ္ခါတစ္ရံမွသာ ျဖစ္ေပၚတတ္ေသာ ျပႆနာျဖစ္သည္။ drop-down list ရွိ location browser bar အား ပိတ္ထားရန္ (http://kb.mozillazine.org/Browser.urlbar.maxRichResults) (ထိုသို႕ျပဳလုပ္ျခင္းျဖင့္ သင့္ browsing history အားျပသေတာ့မည္မဟုတ္ပါ)

Firefox -  about:config (in the location browser bar) - browser.urlbar.maxRichResults-right-click-Modify-set value to 0

##IceCat

IceCat (http://en.wikipedia.org/wiki/GNU_IceCat) သည္ Mozilla ၏ ကုန္အမွတ္တံဆိပ္ မူပိုင္ခြင့္၊ တားျမစ္ခ်က္မ်ားမရွိေသာ Firefox အေျချပဳ Browser တစ္ခုျဖစ္သည္။Debian project မွေထာက္ပံ႕ေပးသည္။ ယခင္က IceWeasel နာမည္ႏွင့္ျဖစ္ၿပီး၊ယခု IceApe Browser နာမည္သို႕ ေျပာင္းလိုက္သည္။ေနာက္ဆံုး version ကို Install လုပ္ေဆာင္ရန္ Terminal တြင္ ေအာက္ပါအတိုင္းရိုက္ထည့္ပါ။

    sudo apt-get install iceape-browser

##SeaMonkey

SeaMonkey (http://www.seamonkey-project.org/) သည္ web browser, IM (IRC) client, Email client,RSS/News reader ႏွင့္ အျခား web development tools မ်ားပါ၀င္ေသာ အင္တာနက္ application တစ္ခုျဖစ္ပါသည္။Mozilla ၏ ထုတ္ကုန္မ်ားကို အေျခခံထားၿပီး၊ Mozilla ၏ မူပိုင္ခြင့္၊ ျဖန္႕ေ၀သံုးစြဲခြင့္မ်ားႏွင့္ ဆက္စပ္ေနသည္။ Thunderbird ႏွင့္ Firefox ကဲ့သို႕ Seamonkey အတြက္ Plugins အေျမာက္အမ်ားရွိသည္။ Seamonkey ကို Install လုပ္ေဆာင္ရန္ Terminal တြင္ ေအာက္ပါအတိုင္းရိုက္ထည့္ပါ။

    sudo apt-get install seamonkey

##IceApe

IceApe (http://en.wikipedia.org/wiki/Naming_conflict_between_Debian_and_Mozilla) သည္ web browser, IM (IRC) client, Email client, RSS/News reader ႏွင့္ web development tools မ်ားပါ၀င္ေသာ open-source အင္တာနက္ application တစ္ခုျဖစ္သည္။ Seamonkey ကို အေျခခံထားၿပီး၊ မူပိုင္ခြင့္ ကန္႕သတ္ထားျခင္းမ်ားမရွိေပ။ Debian project မွေထာက္ပံ႕ေပးထားေသာ application ျဖစ္သည္။ ေနာက္ဆံုး version ကို Install လုပ္ေဆာင္ရန္ Terminal တြင္ ေအာက္ပါအတိုင္းရိုက္ထည့္ပါ။

    sudo apt-get install iceape

##Opera

Opera (http://www.opera.com/) သည္ မူပိုင္ခြင့္ကန္႕သတ္ခ်က္ရွိေသာ proprietary browser, internet suite တစ္ခုျဖစ္သည္။ Mobile devices အခ်ိဳ႕ႏွင့္ game consoles မ်ားတြင္လဲ အသံုးျပဳႏိုင္သည္။ Email, address book, IRC chat, integrated BitTorrent ႏွင့္ webfeeds မ်ားပါ၀င္သည္။ Plugins အနည္းငယ္လဲရွိသည္။ Install လုပ္ေဆာင္ရန္ Opera ၏ website မွ Download (http://www.opera.com/browser/download/) လုပ္ၿပီး၊ လမ္းညႊန္ခ်က္မ်ား ဆက္လုပ္ပါ။ သို႕မဟုတ္ ေအာက္ပါ command မ်ားကို အသံုးျပဳၿပီး Opera repository မွတဆင့္ Install လုပ္ႏိုင္သည္။

	echo "deb http://deb.opera.com/opera/ stable non-free" | sudo tee /etc/apt/sources.list.d/opera.list
	wget -O - http://deb.opera.com/archive.key | sudo apt-key add -
	sudo apt-get install opera

##Chromium

Chromium (http://dev.chromium.org/) သည္ Google Chrome browser ကို အေျခခံထားေသာ open- source browser တစ္ခုျဖစ္သည္။ Chromium ကို Install လုပ္ရန္ Terminal တြင္ ေအာက္ပါအတိုင္း ရိုက္ထည့္ပါ။

    sudo apt-get install chromium-browser

Chromium ကို အသံုးျပဳရန္ ေအာက္ပါအတိုင္းသြားပါ။

Menu - Applications - Internet - Chromium Web Browser

##Google Chrome

Google Chrome (http://www.google.com/chrome) သည္ Google မွထုတ္ေသာ browser တစ္ခုျဖစ္သည္။ Chromium browser ကိုအေျခခံထားၿပီး၊ Google ၏ နာမည္၊ လိုဂိုအမွတ္တံဆိပ္၊ GoogleUpdate ဟုေခၚသည့္ အလိုအေလ်ာက္ Update စနစ္၊RZL ႏွင့္ အျခား Google add-ons မ်ားပါ၀င္သည္။ Google Chrome ကို ဤေနရာမွ (http://www.google.com/chrome/eula.html) ေဒါင္းလုတ္လုပ္ၿပီး၊ install လုပ္ပါ။

##Download Managers

Browsers မ်ားထက္ ေဒါင္းလုတ္လုပ္ငန္းစဥ္ လြယ္ကူၿပီး၊ပိုမိုျမန္ဆန္ေစရန္၊ အမွားနည္းေစရန္ ျပဳလုပ္ထားေသာ ေဆာ့လ္၀ဲမ်ားျဖစ္သည္။အခ်ိဳ႕ Download Managers မ်ားတြင္ အင္တာနက္ ကြန္နက္ရွင္မေကာင္းပါက ခဏရပ္တန္႕ထားၿပီး၊ ေနာင္ ကြန္နက္ရွင္ျပန္ေကာင္းမွ ဆက္လက္ေဒါင္းလုတ္ႏိုင္ေသာ Resuming Downloads Option လဲပါ၀င္သည္။

##MultiGet

MultiGet (http://multiget.sourceforge.net/) သည္ ေဒါင္းလုတ္လုပ္ငန္းစဥ္မ်ား လြယ္ကူေစရန္ အသံုးျပဳႏိုင္သည့္ Download Manager တစ္ခုျဖစ္သည္။ GTK ကို အေျခခံထားၿပီး GUI (Graphical User Interface) ႏွင့္ျဖစ္သည္။ HTTP/FTP စနစ္တို႕ကို ေထာက္ပံ႕ၿပီး၊ Resuming Downloads ကိုလဲ လုပ္ေဆာင္ႏိုင္သည္။ SOCKS 4,4a,5 proxy, ftp proxy, http proxy တို႕ႏွင့္လဲ အသံုးျပဳႏိုင္သည္။ MultiGet ကို Install လုပ္ေဆာင္ရန္ Terminal တြင္ ေအာက္ပါ command ကိုရိုက္ထည့္ပါ။

    sudo apt-get install multiget

##Usenet Clients

Usenet Clients ဆိုသည္မွာ ယခင္တုန္းက အသံုးျပဳႀကေသာ အင္တာနက္ေပၚရွိ Discussions Group တစ္ခုျဖစ္သည္။ယခုေခတ္ အသံုးမ်ားႀကေသာ ဖိုရမ္မ်ား၏ ေရွ႕ေဆာင္လမ္းျပတစ္ခုျဖစ္သည္။ ဖိုရမ္မ်ားကဲ့သို႕ပင္ ပို႕စ္မ်ားတင္ျခင္း၊ အျခားသူမ်ားတင္ထားေသာ ပို႕စ္မ်ားကိုဖတ္႐ႈျခင္းမ်ား ျပဳလုပ္ႏိုင္သည္။ေဆြးေႏြးခ်က္မ်ား၊ ပို႕စ္မ်ားကိုသက္ဆိုင္ရာ က႑အသီးသီးအလိုက္ စုစည္းထားၿပီး newsgroupဟုေခၚသည္။ ေဆြးေႏြးခ်က္မ်ားကိုလည္း Threads မ်ားခြဲထားသည္။ Usenet Discussion Group မွ ေဆြးေႏြးခ်က္မ်ားကို ဖတ္႐ႈရန္ Usenet Clients ဟုေခၚေသာ ေဆာ့လ္၀ဲမ်ားသံုးရန္ လိုအပ္သည္။

##Pan
Pan (http://pan.rebelbase.com/) Pan သည္ Usenet မွ ေဆြးေႏြးခ်က္မ်ားကို ဖတ္႐ႈရန္ အသံုးျပဳႏိုင္
