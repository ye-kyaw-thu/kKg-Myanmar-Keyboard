### Still preparing English README file and not finished yet! Please wait!

# kKg-Myanmar-Keyboard
kKg Myanmar (Unicode) Keyboard Layout that I designed for lazy users (actually, I was the 1st user :).  
I do hope it will be useful for non Myanmar native users who are studying Myanmar (Burmese) language.  

# Introduction to kKg Keyboard Layout

Although I love Myanmar characters, I was so lazy for practising Myanmar text typing with existing Myanmar keyboard layouts. Actually, most of the Myanmar keyboard layouts are based on old Myanmar typewriter layout and they have similar key mappings. In 2004, I have to type Myanmar text for my master thesis research relating to __Myanmar text typing on mobile phone__. I hope you can guess the situation ... He Hee.. :) And thus, I did self-study on changing keyboard layout on Linux OS with XKB and this is the history of my "kKg Keyboard Layout". 

My idea is mapping Myanmar characters on English QWERTY keyboard based on their phonetic similarites with English characters such as Myanmar consonant "က" (Ka) on k key, "ခ" (Kha) on K (Shift+K) key. Here, I have to consider which character should I put on shifted keys. Generally, frequently used characters were put on unshifted keys. Refer following key mapping:


* က on k key, ခ on K (shift+k) key  
* ဂ on g key, ဃ on G (Shift+g) key  
* စ on s key, ဆ on S (Shift+s) key  
* ဇ on z key, ဈ on  Z (Shift+z) key  
* ဒ on d key, ဓ on D (Shift+d) key  
* န on n key, ဏ on N (Shift+n) key  
* ပ on p key, ဖ on P (Shift+p) key  
* ဗ on B (Shift+b)key, ဘ on b key  
* မ on m key  
* ယ on (Shift+y), ရ on y key   
* လ on l key, ဠ on (Shift+l) key ... 

Now, finished key mapping for almost all of the Myanmar consonant, right?  
However, there are 33 Myanmar consonants and 26 keys of English is not enough for mapping all Myanmar consonants. Moreover, some Myanmar consonants have same or similar pronunciation such as တ (ta) and သ (tha), ဒ (da), ဓ (da), ဋ (ta), ဍ (da) and ဎ (da), ထ (hta) and ဌ (hta). And thus, some Myanmar characters are mapped on English keys who pronunciations are totally different with Myanmar such as ည (nya) is mapping on q, ဋ (ta) is mapping on  v, ဌ is mapping on X, ဍ is mapping on V and ဦ is mapping on M.

One more concept that I applied is key mapping based on similar shape of characters.  
For examples:  

Myanmar consonant "င" (Nga) is mapping to English "c" (small c)    
Myanmar  ့ (sign dot below) and ံ (sign anusvara) are mapping on . (full stop) key  
Myanmar consonant sign medial ya " ျ " is mapping to "j" key  

Some character mappings are based on similarity of usage between Myanmar and English.  
For example:  

Myanmar sign little section "၊" is mapping on English "," (comma) key  

Based on above concepts, the following is the kKg keyboard mapping according to Myanmar characters order:

 * For Myanmar Consonant  
 
   | က<br>k | ခ<br>K | ဂ<br>g | ဃ<br>G | င<br>c |
   | :-------------: |:-------------: |:-------------: |:-------------: |:-------------: |
   | စ<br>**s** | ဆ<br>**S** |ဇ<br>**z**  |ဈ<br>**Z**  |ည<br>**q** |
   | ဋ<br>**v** | ဌ<br>**X** |ဍ<br>**V**  |ဎ<br>**~**  |ဏ<br>**N** |
   | တ<br>**T** | ထ<br>**x** |ဒ<br>**d**  |ဓ<br>**D**  |န<br>**n** |
   | ပ<br>**p** | ဖ<br>**P** |ဗ<br>**B**  |ဘ<br>**b**  |မ<br>**m** |
   | ယ<br>**Y** | ရ<br>**y** | လ<br>**l** | ဝ<br>**w**  | သ<br>**t** |
   || ဟ<br>**h** | ဠ<br>**L** |အ<br>**a** ||

* For Myanmar vowels   

   | ာ<br>r | ါ<br>R | ိ<br>i | ီ<br>I |
   | :-------------: |:-------------: |:-------------: |:-------------: |
   | ု<br>**u** | ူ<br>**U** | ေ<br>**A**  | ဲ<br>**e**  |
   | ဩ<br>**O** | ဪ<br>**o** | ့<br>**.**  | ံ<br>**>**  |
   | း<br>**;** |
   

I think now you can guess the name of kKg is representing frst three Myanmar consonants "က", "ခ" and "ဂ". Although, I don't think my keyboard mapping kKg is the best for Myanmar text typing, it is really useful for me. I am using it and I hope it will be useful someone who don't want to practise current Myanmar keyboard layouts. Especially for non native Myanmar who just want to type some Myanmar words for his/her works. Current kKg keyboard layout (version 1.0) is as follow:  

![kKg Keyboard Layout Version.1](https://github.com/ye-kyaw-thu/kKg-Myanmar-Keyboard/blob/master/ver1/kKg-Keyboard-Layout-Ver1.png)

စာရိုက်နည်း (သို့) ရိုက်ရတဲ့အစီအစဉ်က လက်ရှိ Unicode ကီးဘုတ်တွေရဲ့ ရိုက်နည်းနဲ့ အတူတူပါပဲ။  
ဥပမာ။ ။
* ကေဆိုတဲ့ ဗျည်းတွဲကိုရိုက်မယ်ဆိုရင် က ကိုအရင်ရိုက်ပြီးမှ ေ ကိုရိုက်ပါ။  
* ကုံ ကိုရိုက်မယ်ဆိုရင် က + ု + ံ (ku>) အစီအစဉ်အတိုင်း ရိုက်ရပါမယ်။
* ပါဌ်ဆင့် က္က (ကကြီး နှစ်လုံးဆင့်) ကို ရိုက်မယ်ဆိုရင် က + ္ + က (kFk) အစီအစဉ်အတိုင်း ရိုက်ရပါမယ်။


# Installation လုပ်ပုံလုပ်နည်း

kKg ကီးဘုတ်လက်ကွက်က Linux OS တွေပေါ်မှာပဲသုံးဖို့ ရည်ရွယ်ထားတာမဟုတ်ပါဘူး။ ကျွန်တော့်မှာ Windows OS အဟောင်းတွေအတွက် Installer လုပ်ထားခဲ့တာတွေရှိပါတယ်။ အချိန်ရတဲ့အခါ လက်ရှိ Windows OS တွေအတွက် ပြင်ဆင်ပြီး တင်ပေးနိုင်အောင် ကြိုးစားပါမယ်။ လက်ရှိတော့ Linux OS ပေါ်မှာ ဘယ်လို install လုပ်ရမလဲဆိုတာကိုရေးပါမယ်။

## Ubuntu OS အတွက် Installation

အကြမ်းမျဉ်းအားဖြင့် Installation လုပ်နည်း ၂မျိုးရှိပါတယ်။ ဘယ်နည်းမဆို လက်ရှိရှိပြီးသား default mm (မြန်မာဘာသာ) ကီးဘုတ်လက်ကွက်ကို မဖျက်ပစ်ပါဘူး။ X windows ရဲ့ GUI Setup Menu ဖြစ်တဲ့ Text Entry Settings ရဲ့ Choose an input source ဆိုတဲ့ dialogue box မှာ မြန်မာစာကီးဘုတ်လက်ကွက်အနေနဲ့ ၂ခုပေါ်ချင်သလား၊ ၁ခုတည်းပဲ ပေါ်မလားဆိုတာပဲ ကွာသွားမှာပါ။ လက်ရှိသုံးနေတဲ့ Ubuntu OS ရဲ့ ဗားရှင်း (သို့) X Windows Desktop အမျိုးအစားအပေါ်မူတည်ပြီး လုပ်ရတာမှာ အဆင်မပြေတာမျိုးတွေရှိတတ်လို့၊ Linux OSနဲ့ သိပ်အကျွမ်းတဝင် မရှိသေးတဲ့ အသုံးပြုသူများအတွက် Installation နည်း ၂ မျိုးအနေနဲ့ ဖော်ပြပေးထားတာပါ။ 

Installation လုပ်နည်းအမှတ်(၁)
kKg လက်ကွက်ကို လက်ရှိ ရှိပြီးသား default မြန်မာစာ ကီးဘုတ်လက်ကွက်နေရာမှာ အစားထိုးမယ်ဆိုရင် အောက်ပါအစီအစဉ်အတိုင်း လုပ်ဆောင်ပါ။

 1. kkg ဖိုင်ကို ...
 2. /bla/bla/bla
 3. [3 character country code](http://www.loc.gov/standards/iso639-2/php/English_list.php)
 4. 
 5. 

Installation လုပ်နည်းအမှတ်(၂)
kKg  ကီးဘုတ်ကို မြန်မာစာ ကီးဘုတ်လက်ကွက်အသစ်တခုအနေနဲ့ ထည့်ချင်တယ် ဆိုရင် အောက်ပါအစီအစဉ်အတိုင်း လုပ်ဆောင်ပါ။

 1. kkg ဖိုင်ကို ...
 2. /bla/bla/bla
 3. 
 4. 
 5. 

# ပထမဆုံး kKg ကီးဘုတ်ကို သုံးတဲ့အခါ
* လေ့ကျင့်ပုံ၊ လေ့ကျင့်နည်းနဲ့ ပတ်သက်ပြီး ကျွန်တော့်အကြံပေးချင်တာက အရင်ဆုံး ကီးဘုတ်မှာ မြန်မာစာလုံးတွေကို ဘယ်လို concept နဲ့ နေရာချထားတယ်ဆိုတာကို သဘောပေါက်အောင် ကြိုးစားပါ။ မြန်မာလူမျိုးတယောက်အနေနဲ့က မြန်မာစာလုံးတွေရဲ့ အသံထွက်ကိုလည်း သိထားပြီးသားပါ။ အဲဒီစာလုံးတွေကို အင်္ဂလိပ်လို စာလုံးပေါင်းတဲ့ အခါမှာလည်း ငယ်စဉ်ကတည်းက လူနာမည်တွေ၊ လမ်းနာမည်တွေကို Romanization လုပ်ပြီးရေးခဲ့ကြတဲ့ အတွေကြုံတွေကလည်း ရှိတော့ "မ" စာလုံးက "m" ကီးနေရာမှာမယ်၊ "နငယ်" တို့ "ဏကြီး" တို့က "n" စာလုံးနေရာမှာရှိမယ်၊ "ရကောက်" "ယပက်လက်" လို စာလုံးမျိုးတွေက "y" ကီးမှာရှိမယ်ဆိုတာကို အထူးတလည်မှတ်နေစရာမလိုပါဘူး။ သို့သော် စစချင်းမှာက shift-key နဲ့ တွဲရိုက်ရမှာလား၊ shift-key မလိုဘူးလားဆိုတာကိုတော့ လေ့ကျင့်ဖို့လိုအပ်ပါတယ်။

   အထက်မှာ ဇယားနဲ့ရှင်းပြခဲ့တဲ့ အတိုင်း သရတွေကလည်း အသံထွက်အတိုင်းယူထားတာမို့ ရေးချ၊ မောက်ချက "r" ကီးနေရာမှာ၊ တစ်ချောင်းငင်၊ နှစ်ချောင်းငင်က "u" ကီးနေရာမှာဆိုတာလည်း သုံးလေးငါးခေါက်လောက် စမ်းရိုက်ကြည့်ရင်း မှတ်မိသွားပါလိမ့်မယ်။ သူငယ်ချင်း တချို့ကို kKg ကီးဘုတ်ကို စမ်းရိုက်ခိုင်းကြည့်တော့ အားလုံးက ၁၅မိနစ်၊ မိနစ်၂၀လောက် လေ့ကျင့်ပြီးတာနဲ့ စာကြောင်းတွေကို စမ်းရိုက်လို့ရနေပါပြီ။ ၄၅မိနစ်လောက် အကြာမှာ တော်တော်ခပ်သွက်သွက်ကို ရိုက်နိုင်ကြောင်း တွေ့ရှိခဲ့ရပါတယ်။ သူတို့ရဲ့ဘေးမှာ ကီးဘုတ် လက်ကွက်စာရွက်ကို ချထားပေးခဲ့ပါတယ်။ သူတို့ကို kKg ကီးဘုတ်ကို စပြီး သုံးတဲ့အခါမှာ စမ်းရိုက်ခိုင်းတဲ့ စာသားအစီအစဉ် ပုံစံကတော့ အောက်ပါအတိုင်းဖြစ်ပါတယ်။ 
   
* အသုံးများတဲ့ ဗျည်း  
   ```
   က   ခ   ဂ   ဃ   င
   စ   ဆ   ဇ   ဈ   ည
   ဌ   ဏ
   တ   ထ   ဒ   ဓ   န
   ပ   ဖ   ဗ   ဘ   မ
   ယ   ရ   လ   ဝ  သ
   ဟ   အ
      
    ဝ   ထ   က   လ   သ
  ```
 * သရသင်္ကေတများ  
    ```
    ာ   ါ   ိ   ီ   ု   ူ   ေ   ဲ  ့  ်   ံ   း
    ```
    (သရသင်္ကေတများကို ငယ်ငယ်တုန်းက မြန်မာစာအတန်းမှာလို ပါးစပ်ကနေပါ အ၊ အာ၊ အိ၊ အီ၊ အု၊ အူ၊ အေ၊ အဲ၊ အော့၊ အော်၊ အံ၊ အား ရွတ်ဆိုရင်း စမ်းရိုက်ကြည့်ပါ။)
    
  * ဗျည်းနဲ့ သရတွဲများ  
  
    ```
    က၊ ကာ၊ ကိ၊ ကီ၊ ကု၊ ကူ၊ ကေ၊ ကဲ ကော့၊ ကော်၊ ကံ၊ ကား
    ခ၊ ခါ၊ ခိ၊ ခီ၊ ခု၊ ခူ၊ ခေ၊ ခဲ၊ ခေါ့၊ ခေါ်၊ ခံ၊ ခါး
    ဂ၊ ဂါ၊ ဂိ၊ ဂီ၊ ဂု၊ ဂူ၊ ဂေ၊ ဂဲ၊ ဂေါ့၊ ဂေါ်၊ ဂံ၊ ဂါး
    စ၊ စာ၊ စိ၊ စီ၊ စု၊ စူ၊ စေ၊ စဲ၊ စော့၊ စော်၊ စံ၊ စါး
    ပ၊ ပါ၊ ပိ၊ ပီ၊ ပု၊ ပူ၊ ပေ၊ ပဲ၊ ပေါ့၊ ပေါ်၊ ပံ၊ ပါး
    မ၊ မာ၊ မိ၊ မီ၊ မု၊ မူ၊ မေ၊ မဲ၊ မော့၊ မော်၊ မံ၊ မား
    အ၊ အာ၊ အိ၊ အီ၊ အု၊ အူ၊ အေ၊ အဲ၊ အော့၊ အော်၊ အံ၊ အား
    ```
  * ပင့်ရစ်ဆွဲထိုးကိုပါ တွဲလေ့ကျင့်ခြင်း  
  
    ```
    ကွ၊ ပွ၊ မွ၊ လွ၊
    ကျ၊ ကျွ၊ ကြ၊ ကြွ၊
    ကျွဲ၊ ကြွဲ၊ ချွဲ၊ ဂျွဲ
    မွဲ၊ ပွဲ၊ ဆွဲ၊ ရွဲ
    မမ လှလှ
    နွှဲ၊ နွှဲ၊ ကျွဲ၊ ကျွဲ
    မျ၊ မြ၊ မျာ၊ များ
    ကျောင်းသား၊ ကျောင်းသူ၊ ဆရာမ၊ ကျောင်းသွား၊ 
    ရောင်းကောင်း၊ စားကောင်း၊ ကောင်းမှကောင်း၊
    မသိ၊ တယောက်၊ နှစ်ယောက်၊ သုံးလေးယောက်
    ```
   
   * စာကြောင်းအလွယ်များ၊ စာကြောင်းတိုများနဲ့ ပုဒ်ထီး၊ ပုဒ်မများ  
   
     ```
     မမ ဝဝ ထထ က
     အက ပထမ
     ကပါ ကပါ မမရာ
     ညည လသာသာ
    
     ကျောင်းမှန်မှန်တက်၊ စာမခက်။
     မအိပ်မနေ၊ အသက်ရှည်။
     မေးပါများ၊ စကားရ။
    
     ရန်ကုန်မှာ၊ လူများတယ်။
     နယ်မှာက၊ လူနည်းတယ်။
     ```
    
  * ပါဌ်ဆင့်ကို စာလုံးတချို့  
  
     ```
     တက္ကသိုလ်၊ မိတ္တီလာ၊ ပုပ္ပါး၊ သမ္မတ၊ ပြဿနာ၊ ပစ္စည်းများ။
     ```
   
  * နောက်ဆုံး အဆင့်အနေနဲ့ ကိုယ်ရိုက်ချင်တာ၊ ခေါင်းထဲမှာ ပေါ်လာသော မြန်မာစာကြောင်းများကို စမ်းရိုက်တာမျိုး၊ website တခုခုက မြန်မာစာကြောင်းတွေကို စမ်းရိုက်တာမျိုး လုပ်ကြည့်ပါ။
     အစမှာ နှေးတော့ နှေးပါလိမ့်မယ်။ မှားလို့ ပြင်ရတာတွေလဲ ရှိမှာပါ။
     သို့သော် တခြားသော မြန်မာစာကီးဘုတ်လက်ကွက်တွေကို လေ့ကျင့်တာနဲ့ နှိုင်းယှဉ်ကြည့်ရင် အရမ်းကို မြန်တာတွေ့ရပါလိမ့်မယ်။
     Enjoy! kKg keyboard!

