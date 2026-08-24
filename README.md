<h2>Project Description</h2>

<p>
  This practical work focuses on the study and analysis of the performance of
  two types of inverter configurations: <strong>single-phase and three-phase
  inverters</strong>. Several control techniques are investigated, including
  <strong>square-wave (full-wave) control, phase-shifted control, and Pulse
  Width Modulation (PWM)</strong>.
</p>

<p>
  The practical study examines the operation of these control methods and
  their influence on the characteristics and quality of the generated AC
  voltage.
</p>

<h2>Objectives</h2>

<p>The main objectives of this practical work are to:</p>

<ul>
  <li>
    Experimentally study the performance of
    <strong>three-phase inverters</strong> and their
    different modulation techniques.
  </li>
  <li>
    Understand the operating principles of the investigated control methods.
  </li>
  <li>
    Analyze their influence on the <strong>quality of the generated AC voltage</strong>.
  </li>
  <li>
    Evaluate the impact of the different modulation techniques on the overall
    <strong>performance of the inverter system</strong>.
  </li>
</ul>
<h2>Theoretical Background</h2>
<h3>Three-Phase Inverter Configuration</h3>

<p>
  The basic bridge structure consists of three legs. Each leg is composed of
  two switches that are reversible in both current and voltage:
</p>

<div style="text-align: center;">
  <img src="image46.png" alt="Three-phase bridge configuration" style="width: 100%; height: auto;">
</div>
<h3>Full-Wave Control</h3>

<p>
  In this technique, the switches <strong>(K1, K3)</strong> and
  <strong>(K2, K4)</strong> are controlled simultaneously to obtain
  sequences 1 and 2. The duration of each sequence is
  <strong>T/2</strong>.
</p>

<p>
  The output voltage <strong>v<sub>o</sub></strong> is a waveform with a
  single pulse during each half-cycle.
</p>

<p>
  For an inductive load, the output current <strong>i<sub>o</sub></strong>
  varies between <strong>I<sub>min</sub></strong> and
  <strong>I<sub>max</sub></strong>.
</p>

<p>
  The RMS value of the output voltage is given by:
  <p>
  \[
  V_{\mathrm{rms}} = V_{\mathrm{dc}}
  \]
</p>
</p>
<div style="text -align: center;">
  <img src="image61.png" alt="Full-wave control waveform" style="width: 100%; height: auto;">
</div>
<p>For a square-wave output voltage, only odd harmonics are present.</p>

<h4>Phase-Shifted Control</h4>

<p>
  In full-wave control, the RMS voltage across the load is constant and equal to
  <strong>V<sub>dc</sub></strong>. To regulate the output voltage, phase-shifted control is used.
</p>

<p>
  This control strategy introduces zero-voltage intervals across the load. The RMS value
  of the output voltage is given by:
</p>

<div style="text-align: center;">
  <img src="image37.png" alt="Phase-shifted control waveform" style="width: 100%; height: auto;">
</div>
<p>
  In particular, the <strong>amplitude of the fundamental frequency (n = 1)</strong>
  can be controlled by adjusting the <strong>phase-shift angle &alpha;</strong>.
  The harmonic content can also be controlled by adjusting the angle
  <strong>&alpha;</strong>.
</p>
<h3>Sinusoidal-Triangular PWM Control Techniques</h3>

<p>
  These control techniques are based on the <strong>comparison</strong> of a
  sinusoidal waveform, called the <strong>modulating wave</strong> or
  <strong>reference</strong>, with a high-frequency triangular waveform called
  the <strong>carrier</strong>.
</p>

<p>
  <strong>Pulse-width modulation (PWM)</strong> reduces the
  <strong>total harmonic distortion (THD)</strong> of the load current.
  Although the unfiltered PWM output voltage has a relatively high THD,
  its harmonics are shifted to much higher frequencies,
  <strong>making them easier to filter</strong>.
</p>
<div style="text-align: center;">
  <img src="image24.png" alt="Sinusoidal-triangular PWM control waveform" style="width: 100%; height: auto;">
</div>
<h2> Experimental Setup</h2>
<table>
  <thead>
    <tr>
      <th>Equipment</th>
      <th>Image</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>DC Voltage Source</td>
      <td>
        <img src="image35.jpg" alt="DC Voltage Source" width="150">
      </td>
    </tr>
    <tr>
      <td>Driver and Arduino Uno Board</td>
      <td>
        <img src="image99.jpg" alt="Driver and Arduino Uno Board" width="150">
      </td>
    </tr>
    <tr>
      <td>Inverter Setup</td>
      <td>
        <img src="image72.jpg" alt="Inverter Setup" width="150">
      </td>
    </tr>
    <tr>
      <td>RL Load</td>
      <td>
        <img src="image92.jpg" alt="RL Load" width="150">
      </td>
    </tr>
    <tr>
      <td>Oscilloscope</td>
      <td>
        <img src="image83.jpg" alt="Oscilloscope" width="150">
      </td>
    </tr>
  </tbody>
</table>
