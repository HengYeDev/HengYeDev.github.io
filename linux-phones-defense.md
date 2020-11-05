# Defense of Linux Phones

On privacy forums, I often see https://madaidans-insecurities.github.io/linux-phones.html be recommended if linux mobile operating systems such as Ubuntu Touch, Mobian, or postmarketOS are proposed. This website states some security deficiencies of linux mobile operating systems. However, linux phones still have better privacy then stock android which this website recommends.

Security != privacy. This website shows valid security problems, not privacy problems. Security does affect privacy as it makes it easier for attackers to read data, but security measures do not prevent leaking data by design. Stock android sends lots of data to Google and phone makers. Security measures do not prevent this - security measures don't fix built in spyware.  A example is Google Play Services.

>  They do not have security features such as full system MAC policies, verified boot, hardened kernels, strong app sandboxing etc. that modern Android phones do. 

Verified boot is something that locks yourself out of control of your own phone. Android verified boot only allows booting the kernel provided by the vendor, which prevents you from controlling your phone's kernel. Android verified boot would be acceptable if you could add your own keys and remove the vendor keys. Hardened kernels do not prevent Google from collecting data about you and neither does sandboxing. Why should we trust Google's app sandboxing for preventing their own software from phoning home?

> The microphone kill switch is useless since audio can still be gotten via the sensors (such as the gyroscope). While the Librem 5 does have a "lockdown mode" that disables the sensors, it also requires flipping all of the other switches, including the network ones which effectively turns your device into a brick just to prevent audio recording. 

Turning your device into a brick is useful when you are not using it. This is the purpose of the kill switches: to turn your device into a brick because bricks can't be hacked. 

> The network kill switch is useless since the attacker will just wait until you turn them back on again to exfiltrate data. If you need to disable network access, you can use airplane mode. 

Airplane mode can be disabled via software, while hardware kill switches cannot.

This essay's security claims may be true, but cannot be applied to privacy.
