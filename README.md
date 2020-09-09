# mcb
Multi Connectors Board for benchmarking

The idea is to use open-source tools to automate the benchmarks. There is possibility to use separate small and simple tools or use one specialized board designed by Łukasiewicz-PIAP called MCB (Multi Connectors Board).

Main features of the board are listed below:

* Allows sniffing SWO trace line
* Automates current measurements
  * Contains set of shunt resitors (many possible ranges)
  * Newest version of the board contains module to measure current on it
  * All versions allow to trigger external oscilloscope for very accurate observation of current changes
* Addtional connectors for Saleae/Sigrok logic analyzers
  * JTAG/SWD sniffing
  * SWO trace output decoding
* All trace pins decoding (D0, D1, D2, D3 and CLK)
* Easy configuration on jumpers

# LICENSE

mcb is to be open-sourced under the Apache-2.0 license. See the
[LICENSE](./LICENSE.md) file for details.
