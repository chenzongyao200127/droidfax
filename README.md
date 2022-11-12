~~~txt
DroidFax is a toolkit dedicated to offering an experimental framework for the dynamic characterization of Android apps. To help deliver a characterization more representative of the latest Android framework features, DroidFax targets the latest release of the Android SDK (version 6.0 / API level 23 / Marshmallow). Its core consists of a lightweight static analysis that mainly instruments the Dalvik bytecode of a given app for call profiling and ICC monitoring, and a lightweight dynamic analysis that collects and then analyzes generated call and ICC traces. It also includes a pre-processing phase taking charge of benchmark apps downloading and ICC-based app pairing based on the ICC resolution results obtained using a third-party tool. The last part of DroidFax computes three categories of metrics from the traces: general metrics, ICC metrics, and security metrics.

You can find usage information at https://chapering.github.io/droidfax/page_usage.html

For a quick guide on deploying DroidFax to your machine and use it, go to 'portable' and check out the README therein.
~~~