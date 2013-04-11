# Greek layout for hardware keyboards on Android #

This project adds an Extended Greek layout to Android for use with physical keyboards.

I used tialaramex's [BritishKeyboard](https://github.com/tialaramex/BritishKeyboard) as a skeleton.

Since the original code does not come with a license, I do not think I can give my code under any license, so consider it as-is.


If you want to learn more about the app itself, you can visit [its page at Google Play](https://play.google.com/store/apps/details?id=com.andmarios.greekhwkeyboard).

If you want to learn more about physical keyboard layouts in Android 4.1+, have a look at [keyboard_layout_el_gr](res/raw/keyboard_layout_el_gr.kcm).


Easiest way to get an apk:

    $ git clone git@github.com:andmarios/GreekHWKeyboard.git
    $ cd GreekHWKeyboard
    $ android update project -p .
    $ ant debugboard_layout_el_gr.kcm).