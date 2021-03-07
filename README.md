# Biquadjs
Just a simple adaptation of a set of useful Biquad filters from an obscure arachnoid.com python tutorial to javascript. See the example html for usage.

Features:
* Low pass
* High pass
* Band pass
* Notch
* Peak
* High shelf
* Low shelf

Set Q-factor and other parameters as needed, you will want to experiment a bit for the notch, peak, and bandpass filters, the defaults otherwise are butterworth (1/root(2)) Q factors while I set relatively effective values for the aforementioned special cases.

![capture](Capture.PNG)
