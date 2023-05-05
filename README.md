Download Link: https://assignmentchef.com/product/solved-ece380-lab-08-code-converters
<br>
<strong>Code Converters </strong>

<h1>Design A</h1>

Implement Design A (for the Cyclone® V device) of the pre-lab.  Verify the design correctness by simulating it in Quartus Prime.

Download and test Design A on the Cyclone® V device. <strong><u>Have the TA verify your results.</u></strong>

<ul>

 <li>Use inputs SW[3..0] (Note: SW[0] is the LSB) for the input <em>h</em><sub>3</sub>–<em>h</em><sub>0</sub>.</li>

 <li>Use seven-digit display HEX0 [6..0] (note: HEX1 [0] is the MSB( <em>led</em><sub>0 </sub>) and HEX0[6] is the</li>

</ul>

LSB(<em><sup>led</sup></em><sub>6 </sub>)) for the LED’s outputs (<em><sup>led</sup></em><sub>0</sub> –<em><sup>led</sup></em><sub>6 </sub>).

<h1>Design B</h1>

Implement Design B (for the Cyclone® V device) of the pre-lab.  Verify the design correctness by simulating it in Quartus Prime. Download and test Design B on the Cyclone® V device. You can decide on the pin assignments yourself.

<ul>

 <li>Use inputs SW [3..0] (note: SW[0] is the LSB) for the inputs (<em>h</em><sub>3</sub>–<em>h</em><sub>0</sub>).</li>

</ul>

<table width="525">

 <tbody>

  <tr>

   <td width="48"><strong> </strong></td>

   <td width="54"> </td>

   <td width="54"><strong> </strong></td>

   <td colspan="3" width="132"><strong>EXPECTED </strong></td>

   <td colspan="3" width="114"><strong>SIMULATED </strong></td>

   <td colspan="3" width="123"><strong>DE1 Board </strong></td>

  </tr>

  <tr>

   <td width="48"><strong> </strong></td>

   <td width="54"><strong>A </strong></td>

   <td width="54"><strong>B </strong></td>

   <td width="48"><strong>S </strong></td>

   <td width="42"><strong>fo </strong></td>

   <td width="42"><strong>co </strong></td>

   <td width="42"><strong>S </strong></td>

   <td width="36"><strong>Fo </strong></td>

   <td width="36"><strong>co </strong></td>

   <td width="36"><strong>S </strong></td>

   <td width="42"><strong>fo </strong></td>

   <td width="45"><strong>co </strong></td>

  </tr>

  <tr>

   <td width="48">ADD</td>

   <td width="54">5</td>

   <td width="54">2</td>

   <td width="48"> </td>

   <td width="42"> </td>

   <td width="42"> </td>

   <td width="42"> </td>

   <td width="36"> </td>

   <td width="36"> </td>

   <td width="36"> </td>

   <td width="42"> </td>

   <td width="45"> </td>

  </tr>

  <tr>

   <td width="48">ADD</td>

   <td width="54">8</td>

   <td width="54">F</td>

   <td width="48"> </td>

   <td width="42"> </td>

   <td width="42"> </td>

   <td width="42"> </td>

   <td width="36"> </td>

   <td width="36"> </td>

   <td width="36"> </td>

   <td width="42"> </td>

   <td width="45"> </td>

  </tr>

  <tr>

   <td width="48">ADD</td>

   <td width="54">7</td>

   <td width="54">E</td>

   <td width="48"> </td>

   <td width="42"> </td>

   <td width="42"> </td>

   <td width="42"> </td>

   <td width="36"> </td>

   <td width="36"> </td>

   <td width="36"> </td>

   <td width="42"> </td>

   <td width="45"> </td>

  </tr>

  <tr>

   <td width="48">ADD</td>

   <td width="54">9</td>

   <td width="54">E</td>

   <td width="48"> </td>

   <td width="42"> </td>

   <td width="42"> </td>

   <td width="42"> </td>

   <td width="36"> </td>

   <td width="36"> </td>

   <td width="36"> </td>

   <td width="42"> </td>

   <td width="45"> </td>

  </tr>

  <tr>

   <td width="48">SUB</td>

   <td width="54">E</td>

   <td width="54">F</td>

   <td width="48"> </td>

   <td width="42"> </td>

   <td width="42"> </td>

   <td width="42"> </td>

   <td width="36"> </td>

   <td width="36"> </td>

   <td width="36"> </td>

   <td width="42"> </td>

   <td width="45"> </td>

  </tr>

  <tr>

   <td width="48">SUB</td>

   <td width="54">7</td>

   <td width="54">3</td>

   <td width="48"> </td>

   <td width="42"> </td>

   <td width="42"> </td>

   <td width="42"> </td>

   <td width="36"> </td>

   <td width="36"> </td>

   <td width="36"> </td>

   <td width="42"> </td>

   <td width="45"> </td>

  </tr>

  <tr>

   <td width="48">SUB</td>

   <td width="54">7</td>

   <td width="54">E</td>

   <td width="48"> </td>

   <td width="42"> </td>

   <td width="42"> </td>

   <td width="42"> </td>

   <td width="36"> </td>

   <td width="36"> </td>

   <td width="36"> </td>

   <td width="42"> </td>

   <td width="45"> </td>

  </tr>

  <tr>

   <td width="48">SUB</td>

   <td width="54">E</td>

   <td width="54">4</td>

   <td width="48"> </td>

   <td width="42"> </td>

   <td width="42"> </td>

   <td width="42"> </td>

   <td width="36"> </td>

   <td width="36"> </td>

   <td width="36"> </td>

   <td width="42"> </td>

   <td width="45"> </td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Use two seven-digit displays HEX1 [6] and HEX0 [6..0] (Note: HEX1 [6] is the MSB and HEX0[6] is the LSB) for the LED’s outputs (<em>led</em><sub>0</sub> –<em>leds</em><sub>7</sub>).</li>

</ul>

<h1>Design C</h1>

Implement Design C (for the Cyclone® V device) of the pre-lab.  Verify the design correctness by simulating it in Quartus Prime. Download and test Design C on the Cyclone® V device. You can decide on the pin assignments yourself. Fill out the form below.

<ul>

 <li>Use inputs SW [9..6] (note: SW[6] is the LSB) for the X input (<em>X</em><sub>3</sub>–<em>X</em><sub>0</sub>).</li>

 <li>Use inputs SW [5..2] (note: SW[2] is the LSB) for the Y input (<em>Y</em><sub>3</sub>–<em>Y</em><sub>0</sub>).</li>

 <li>Use inputs SW [0] for ADD_SUB.</li>

 <li>Use inputs LEDR [3..0] (note: LEDR[0] is the LSB) for the S output (<em>S</em><sub>3</sub>–<em>S</em><sub>0</sub>).</li>

 <li>Use inputs LEDR [9], LEDR[8] for overflow and Cout.</li>

 <li>Use two seven digit display HEX5 [6] and HEX4 [6..0] (note: HEX5 [6] is the MSB and HEX4[6] is the LSB) for the outputs (<em>hexx</em><sub>0</sub> –<em>hexx</em><sub>7</sub>). Use two seven-digit displays HEX3</li>

</ul>

[6] and HEX2 [6..0] (again, HEX3 [6] is the MSB and HEX2[6] is the LSB) for the outputs (<em>hexy</em><sub>0</sub> –<em>hexy</em><sub>7</sub>). Use two seven-digit displays HEX1 [6] and HEX0 [6..0] (again, HEX1 [6] is the MSB and HEX0[6] is the LSB) for the outputs (<em>hexs</em><sub>0</sub> –<em>hexs</em><sub>7 </sub>).

<ul>

 <li><strong> </strong>Draw two implementations of gated SR latches and their characteristic table.</li>

 <li>Draw a D latch and its characteristic table.</li>

 <li>Draw a negative-edge-triggered D flip-flop using the master-slave configuration. Draw its characteristic table.</li>

 <li>Draw a positive-edge-triggered D flip-flop using the master-slave configuration. Draw its characteristic table.</li>

 <li><strong>Explain the difference between the following pair of concepts:</strong></li>

</ul>

<ol>

 <li>D latches versus D flip-flops</li>

 <li>Basic latches versus gated latches</li>

 <li>Asynchronous clear versus synchronous clear</li>

 <li>Level sensitive devices versus edge-triggered devices</li>

</ol>


