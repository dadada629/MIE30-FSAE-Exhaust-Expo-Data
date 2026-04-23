<div align="center">
<h1>🏁 UIC FSAE Exhaust System Data</h1>
<h3>Team 30 Powertrain Engineering Dashboard</h3>
<i>Interactive simulation telemetry and Finite Element Analysis (FEA) data for the UIC FSAE 4-2-1 Exhaust System.</i>
</div>

## 👨‍💻 Meet the Team

*Click our names to connect with us on LinkedIn!*

| [**Jacob Schifrin**](https://www.linkedin.com/in/jacobschifrin) | [**Aiden Avalos**](https://www.linkedin.com/in/aiden-avalos-279285220/) | [**Michal Potok**](https://www.linkedin.com/in/michal-potok-86bb84227/) | [**Eduardo Escobar**](https://www.linkedin.com/in/eduardo-escobar-1469ba21a/) | [**Thomas Dicke**](https://www.linkedin.com/in/thomas-dicke-93599524b/) |

## ⚙️ 1D Simulation Model Setup (Ricardo WAVE)

*The foundation of the exhaust design relies on a complete one-dimensional acoustic and thermodynamic model of the Honda CBR600 engine. The following diagrams detail the specific system components and boundary conditions configured prior to optimization.*

<details open>
<summary><b>🛠️ Full Engine Topology</b> <i>(Click to Collapse)</i></summary>

<p align="center">
<img src="Model Screenshots/Figure 3 Complete Ricardo WAVE 1D engine topology including custom intake restrictor, 4-2-1 exhaust routing, and simulated muffler..png" width="90%"/>
<br><i>Complete 1D engine topology mapping the intake restrictor, engine block, 4-2-1 exhaust routing, and simulated muffler.</i>
</p>

</details>

<details>
<summary><b>🔍 Sub-System Configurations</b> <i>(Click to Expand)</i></summary>

<table>
<tr>
<td align="center"><b>Intake & ITB Flow</b><br>
<img src="Model Screenshots/Figure 4 Intake restrictor and equivalent ITB flow area approximation within the 1D model..png" width="100%"/><br>
<i>Intake restrictor and equivalent individual throttle body (ITB) flow area approximation.</i></td>

<td align="center"><b>Exhaust Collectors</b><br>
<img src="Model Screenshots/Figure 5 Exhaust 4-2-1 primary pipe pairing and collector junction topology..png" width="100%"/><br>
<i>Exhaust 4-2-1 primary pipe pairing and collector junction topology.</i></td>

<td align="center"><b>Muffler Capacitance</b><br>
<img src="Model Screenshots/Figure 6 Helmholtz resonator geometry simulating physical muffler capacitance and flow resistance..png" width="100%"/><br>
<i>Helmholtz resonator geometry simulating physical muffler capacitance and flow resistance.</i></td>
</tr>
</table>

</details>

## 📊 Interactive Telemetry Dashboards

*Experience our data live. Tap the links below to interact with the 3D models and custom charting tools.*

* 🚀 [**Phase 1: Acoustic Length Optimization Heatmap**](Length%20Simulation%20Results.html)

* 📈 [**Phase 2: Final Geometry Performance Data**](Design%20Comparison%20Charts.html)

## 🔬 Finite Element Analysis (FEA) Validations

*Select a category below to expand and view the Fluent analysis data. This data displays exhaust gas velocity, temperature, pressure, and turbulence through the 4-2-1 merges.*

<details>
<summary><b>💨 Velocity & Streamlines</b> <i>(Click to Expand)</i></summary>

<table>
<tr>
<td align="center"><b>Velocity Vector SS</b>

<img src="Fluent/Velocity%20Vector%20SS.png" width="100%"/></td>
<td align="center"><b>Velocity Vector BACK SS</b>

<img src="Fluent/Velocity%20Vector%20BACK%20SS.png" width="100%"/></td>
</tr>
<tr>
<td align="center"><b>Streamline Velocity SS</b>

<img src="Fluent/Streamline%20Velocity%20SS.png" width="100%"/></td>
<td align="center"><b>Streamline Velocity BACK SS</b>

<img src="Fluent/Streamline%20Velocity%20BACK%20SS.png" width="100%"/></td>
</tr>
</table>
</details>

<details>
<summary><b>⏱️ Pressure Analysis</b> <i>(Click to Expand)</i></summary>

<table>
<tr>
<td align="center"><b>Pressure Wall SS</b>

<img src="Fluent/Pressure%20Wall%20SS.png" width="100%"/></td>
<td align="center"><b>Pressure Wall BACK SS</b>

<img src="Fluent/Pressure%20Wall%20BACK%20SS.png" width="100%"/></td>
</tr>
</table>
</details>

<details>
<summary><b>🌡️ Temperature Distribution</b> <i>(Click to Expand)</i></summary>

<table>
<tr>
<td align="center"><b>Temperature Wall SS</b>

<img src="Fluent/Temperature%20Wall%20SS.png" width="100%"/></td>
<td align="center"><b>Temperature Wall BACK SS</b>

<img src="Fluent/Temperature%20Wall%20BACK%20SS.png" width="100%"/></td>
</tr>
</table>
</details>

<details>
<summary><b>🌪️ Turbulence Analysis</b> <i>(Click to Expand)</i></summary>

<table>
<tr>
<td align="center"><b>Turbulence SS</b>

<img src="Fluent/Turbulence%20SS.png" width="100%"/></td>
<td align="center"><b>Turbulence BACK SS</b>

<img src="Fluent/Turbulence%20BACK%20SS.png" width="100%"/></td>
</tr>
</table>
</details>

<details>
<summary><b>🏗️ Structural Analysis</b> <i>(Click to Expand)</i></summary>

<table>
<tr>
<td align="center"><b>Equivalent Stress Front</b>

<img src="Structual/EquivalentStreeFront.png" width="100%"/></td>
<td align="center"><b>Equivalent Stress Back</b>

<img src="Structual/EquivalentStressBack.png" width="100%"/></td>
</tr>
<tr>
<td align="center"><b>Safety Factor Front</b>

<img src="Structual/SafetyFactorFront.png" width="100%"/></td>
<td align="center"><b>Safety Factor Back</b>

<img src="Structual/SafetyFactorBack.png" width="100%"/></td>
</tr>
<tr>
<td align="center"><b>Total Deformation Front</b>

<img src="Structual/totalDeformationFront.png" width="100%"/></td>
<td align="center"><b>Total Deformation Back</b>

<img src="Structual/TotalDeformationBack.png" width="100%"/></td>
</tr>
</table>
</details>

<details>
<summary><b>🔥 Thermal Analysis</b> <i>(Click to Expand)</i></summary>

<table>
<tr>
<td align="center"><b>Heat Flux Front</b>

<img src="Thermal/HeatFluxFront.png" width="100%"/></td>
<td align="center"><b>Heat Flux Back</b>

<img src="Thermal/HeatFluxBack.png" width="100%"/></td>
</tr>
<tr>
<td align="center"><b>Temperature Front</b>

<img src="Thermal/TempFront.png" width="100%"/></td>
<td align="center"><b>Temperature Back</b>

<img src="Thermal/Temp%20Back.png" width="100%"/></td>
</tr>
<tr>
<td align="center"><b>Thermal Error Front</b>

<img src="Thermal/ThermalErrorFront.png" width="100%"/></td>
<td align="center"><b>Thermal Error Back</b>

<img src="Thermal/ThermalErrorBack.png" width="100%"/></td>
</tr>
</table>
</details>

<hr>
<p align="center"><i>University of Illinois Chicago (UIC) • MIE 397 Senior Design Expo</i></p>
