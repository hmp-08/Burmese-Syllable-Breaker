# Syllable Break with Regular Expressions (re)
mm-syllable-break

This Python library provides a syllable segmentation functionality using regular expressions (re) to break text into syllables. It is designed to be a simple and efficient tool for segmenting words or sentences into syllables based on predefined rules.

# Features
Breaks text into syllables based on specific rules.

Handles various types of characters, including letters, numbers, special characters, and specific character ranges.

# Installation
Ensure that Python 3.x is installed on your system.

Clone the repository or download the source code files.

# Usage
```
from SyllableSegmenter import SyllableSegmenter
segmenter = SyllableSegmenter()
input_text = "သေတ္တာလေးကိုဆက်သွယ်Boxin999၉၉၉(#) ပြီးတော့ တရုတ် နဲ့လည်း ချစ်ကြည်ရင်းနှီးတဲ့ ဆက်ဆံရေး ရှိတယ် အဲ့ဒီ ဝေဖန်မှုတွေ နဲ့ ပတ်သက် လို့ ဘယ်လို တုံ့ပြန်ချင်ပါသလဲ မမီ မွေးဖွားနေတဲ့ အချိန် မှာတော့ ဘုရား ဂုဏ်တော် ကိုပဲ တောက်လျှောက် ရွတ်နေခဲ့ပါတယ် ခင်ဦးသာ နှင့် နန်းလွင်နှင်းပွင့် ပူးပေါင်း ရေးသားသည် ကြည့်ရသည်မှာ မြန်မာ နိုင်ငံ တွင် သူ့ အတွက် ခိုလှုံရာ တခု တွေ့ခဲ့ပုံ ရပါသည် မမဖွေးဖွေး နဲ့ တွေ့ရ တော့ တအား ပျော်တယ် လို့ ပြောပါတယ် အထူးသဖြင့် နိုင်ငံရေး လောက ကို စုစည်းနိုင်ခဲ့သည် ဟု ဆိုနိုင်ပါသည် ကဖင်း မပါဝင်သော ကော်ဖီ သောက်ပါကောလင်း မြို့နယ် ရေကြီးတာ က ဆည်ကျိုး လို့ မဟုတ်ဘူး ကျွန်မ အလုပ် ကို လေးလေးစားစား လုပ်ပါတယ်"
syllables = segmenter.sylseg(input_text)
print(syllables)

# output --> သေတ္တာ လေး ကို ဆက် သွယ် 9 9 9 ၉ ၉ ၉ ( # ) ပြီး တော့ တ ရုတ် နဲ့ လည်း ချစ် ကြည် ရင်း နှီး တဲ့ ဆက် ဆံ ရေး ရှိ တယ် အဲ့ ဒီ ဝေ ဖန် မှု တွေ နဲ့ ပတ် သက် လို့ ဘယ် လို တုံ့ ပြန် ချင် ပါ သ လဲ မ မီ မွေး ဖွား နေ တဲ့ အ ချိန် မှာ တော့ ဘု ရား ဂုဏ် တော် ကို ပဲ တောက် လျှောက် ရွတ် နေ ခဲ့ ပါ တယ် ခင် ဦး သာ နှင့် နန်း လွင် နှင်း ပွင့် ပူး ပေါင်း ရေး သား သည် ကြည့် ရ သည် မှာ မြန် မာ နိုင် ငံ တွင် သူ့ အ တွက် ခို လှုံ ရာ တ ခု တွေ့ ခဲ့ ပုံ ရ ပါ သည် မ မ ဖွေး ဖွေး နဲ့ တွေ့ ရ တော့ တ အား ပျော် တယ် လို့ ပြော ပါ တယ် အ ထူး သ ဖြင့် နိုင် ငံ ရေး လော က ကို စု စည်း နိုင် ခဲ့ သည် ဟု ဆို နိုင် ပါ သည် က ဖင်း မ ပါ ဝင် သော ကော် ဖီ သောက် ပါ ကော လင်း မြို့ နယ် ရေ ကြီး တာ က ဆည် ကျိုး လို့ မ ဟုတ် ဘူး ကျွန် မ အ လုပ် ကို လေး လေး စား စား လုပ် ပါ တယ်
```







