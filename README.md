# 2023-Fall-NTU-Soc-Design-Laboratory-Lab3
## Files Description
| File         | Description |
| --------     | ----------- |
| fir.v                         | Verilog design  |
| fir_tb.v                      | Testbench for fir.v  |
| fir_utilization_synth.rpt     | Synthesis report  |
| runme.log                     | Synthesis log  |
| simulate.log                  | Behavioral simulation log  |
| timing_report.txt             | Timing report  |
| SoC_Lab3.pdf                  | Lab report |

## Waveform
**Configuraion write (AXI-Lite)**
![configuration_write](https://github.com/gene5487/2023-Fall-NTU-Soc-Design-Laboratory-Lab3/assets/58682521/7c715a15-1912-48a3-b947-b10be37afefd)

**Tap read back (AXI-Lite)**
![tap_readback](https://github.com/gene5487/2023-Fall-NTU-Soc-Design-Laboratory-Lab3/assets/58682521/19f8794a-a5b4-4170-9db9-b0766d8edb4d)

**ap_start (ap_config_reg[0]) asserted @965ns**
![ap_start](https://github.com/gene5487/2023-Fall-NTU-Soc-Design-Laboratory-Lab3/assets/58682521/fccd8bf3-2beb-4de1-bbad-7674e595e969)

**ap_done (ap_config_reg[1]) asserted @78,975ns**
![ap_done](https://github.com/gene5487/2023-Fall-NTU-Soc-Design-Laboratory-Lab3/assets/58682521/8a5ae03a-c2d7-4841-b999-e5b06ddfbec3)

\#cycle from ap_start to ap_done = (78,975-965)/cycle time(10ns) = 7801 cycles

**X[n] stream in(AXI-Stream Slave)**
![stream_in](https://github.com/gene5487/2023-Fall-NTU-Soc-Design-Laboratory-Lab3/assets/58682521/951c72f5-5bda-4538-bcbf-61bc85ebabe4)

**Y[n] stream out(AXI-Stream Master)**
![stram_out](https://github.com/gene5487/2023-Fall-NTU-Soc-Design-Laboratory-Lab3/assets/58682521/cd4be7c2-a036-4384-aca4-6e6f26592fa6)

