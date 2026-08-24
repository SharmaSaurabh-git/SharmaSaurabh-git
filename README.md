<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,100:16213e&height=180&section=header&text=SAURABH%20SHARMA&fontSize=42&fontColor=00d9ff&animation=fadeIn&fontAlignY=38&desc=Signals%20%2B%20Systems%20%2B%20Silicon&descAlignY=58&descSize=16&descColor=888888" width="100%"/>

</div>

<div align="center">

```
┌─────────────────────────────────────────────────────────┐
│  x(t) ──▶ [ECE Undergrad] ──▶ [DSP] ──▶ [VLSI] ──▶ y(t)  │
│                    HPTU · Class of 2028                   │
└─────────────────────────────────────────────────────────┘
```

</div>

<br>

## `>` about

I'm an Electronics & Communication Engineering student building toward
**Verification Engineering** in the VLSI industry. My path runs through
signal processing first — filters, spectral analysis, modulation — because
that's where the intuition for "what a signal actually looks like" comes
from before you're staring at RTL and waveforms all day.

I build things that run, not things that just look like they run. Every
repo below has a real test suite and I can walk through any line of it.

<br>

## `>` currently

```diff
+ Building out a Verilog/SystemVerilog foundation
+ Maintaining 3 verified hardware/DSP repos, test suites passing on all
+ Following an 18-month roadmap toward VLSI verification internships
```

<br>

## `>` projects

<table>
<tr>
<td width="50%" valign="top">

### 🔲 [ai-hardware-accelerator](https://github.com/SharmaSaurabh-git/ai-hardware-accelerator)

An output-stationary systolic array for matrix multiplication in
SystemVerilog — the core computational pattern behind TPU/Tensor-Core
style AI accelerators.

**What's in it:**
- Parameterizable N×N array, each PE owns and accumulates one output
  element independently
- Correctly time-skewed input feed (documented cycle-by-cycle derivation)
- Verified: 32/32 output elements correct across 2 test cases, run in
  Icarus Verilog — see `doc/architecture.md` for the full design writeup,
  including why an earlier version was architecturally wrong and how it
  was fixed

`SystemVerilog` `Icarus Verilog` `Digital Design`

</td>
<td width="50%" valign="top">

### 🧮 [picosrv32](https://github.com/SharmaSaurabh-git/picosrv32)

A 5-stage pipelined RISC-V CPU core (RV32I subset) — real forwarding,
a load-use stall, and branches that resolve and flush correctly.

**What's in it:**
- Full EX/MEM + MEM/WB forwarding, same-cycle register-file bypass
- R-type/I-type ALU ops, loads, stores, BEQ/BNE branches
- Verified: 14/14 checks correct on a 16-instruction test program
  covering every hazard type it handles, run in Icarus Verilog — see
  `doc/architecture.md` for why the earlier version never even compiled

`SystemVerilog` `Icarus Verilog` `Computer Architecture`

</td>
</tr>
</table>

<table>
<tr>
<td width="50%" valign="top">

### 📡 [signal-processing-toolkit](https://github.com/SharmaSaurabh-git/signal-processing-toolkit)

A Python DSP library built from the ground up — not a wrapper, an actual
toolkit with validated math.

**What's in it:**
- FIR filter design (low-pass/high-pass/band-pass/band-stop) + both causal and zero-phase filtering
- Spectral analysis: FFT, Welch PSD, spectrogram, STFT
- AM/FM analog modulation, BPSK/QPSK digital modulation
- 46-test suite, CI on every push

`Python` `NumPy` `SciPy` `Matplotlib` `pytest`

</td>
<td width="50%" valign="top">

### 📶 2.4 GHz Microstrip Patch Antenna

Designed and simulated a patch antenna for the 2.4 GHz ISM band as a
team B.Tech project — full workflow from geometry design through
S-parameter validation.

**What it involved:**
- RF simulation and structure design in Ansys HFSS
- Return loss / bandwidth / radiation pattern analysis
- Team project — built and validated with 3 collaborators

`Ansys HFSS` `RF Design` `Antenna Theory`

</td>
</tr>
</table>

<br>

## `>` toolchain

<table>
<tr>
<td valign="top" width="33%">

**Languages**
```
Python    ████████░░  
MATLAB    ██████░░░░  
C         █████░░░░░  
Verilog   ███░░░░░░░  learning
```

</td>
<td valign="top" width="33%">

**Tools**
```
Git & GitHub
Scilab
Ansys HFSS
Linux / Termux
```

</td>
<td valign="top" width="33%">

**Focus areas**
```
Digital Signal
  Processing
RF / Antenna
  Design
VLSI
  Verification
```

</td>
</tr>
</table>

<br>

## `>` metrics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=SharmaSaurabh-git&show_icons=true&hide_border=true&theme=tokyonight&hide_title=true&count_private=true" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SharmaSaurabh-git&layout=compact&hide_border=true&theme=tokyonight&hide_title=true" height="165"/>

</div>

<br>

<div align="center">

<a href="https://www.linkedin.com/in/YOUR-LINKEDIN"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:YOUR-EMAIL"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>

<br><br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:16213e,100:1a1a2e&height=100&section=footer" width="100%"/>

</div>
