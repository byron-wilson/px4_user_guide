# Airframes Reference
> **Note** **This list is auto-generated from the source code**.
> 
> The **AUX** channels are only available on Pixhawk Boards (labeled with **AUX OUT**).
> 

This page lists all supported airframes and types including
 the motor assignment and numbering. The motors in **green** rotate clockwise,
 the ones in **blue** conterclockwise.

## Coaxial Helicopter

<div>
<img src="../images/airframes/types/HelicopterCoaxial.svg" width="29%" style="max-height: 180px;"/>
<table style="float: right; width: 70%; font-size:1.5rem;">
 <colgroup><col></colgroup>
 <thead>
   <tr><th>Common Outputs</th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;"><ul><li><b>MAIN1</b>: Left swashplate servomotor, pitch axis</li><li><b>MAIN2</b>: Right swashplate servomotor, roll axis</li><li><b>MAIN3</b>: Upper rotor (CCW)</li><li><b>MAIN4</b>: Lower rotor (CW)</li></ul></td>
</tr>
</tbody></table>
</div>

<table style="width: 100%; table-layout:fixed; font-size:1.5rem;">
 <colgroup><col style="width: 30%"><col style="width: 70%"></colgroup>
 <thead>
   <tr><th>Name</th><th></th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;">Esky (Big) Lama v4</td>
 <td style="vertical-align: top;"><p>Maintainer: Emmanuel Roussel</p><p><code>SYS_AUTOSTART</code> = 15001</p></td>

</tr>
</tbody></table>

## Flying Wing

<div>
<img src="../images/airframes/types/FlyingWing.svg" width="29%" style="max-height: 180px;"/>
<table style="float: right; width: 70%; font-size:1.5rem;">
 <colgroup><col></colgroup>
 <thead>
   <tr><th>Common Outputs</th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;"><ul><li><b>MAIN1</b>: left aileron</li><li><b>MAIN2</b>: right aileron</li><li><b>MAIN4</b>: throttle</li><li><b>AUX1</b>: feed-through of RC AUX1 channel</li><li><b>AUX2</b>: feed-through of RC AUX2 channel</li><li><b>AUX3</b>: feed-through of RC AUX3 channel</li></ul></td>
</tr>
</tbody></table>
</div>

<table style="width: 100%; table-layout:fixed; font-size:1.5rem;">
 <colgroup><col style="width: 30%"><col style="width: 70%"></colgroup>
 <thead>
   <tr><th>Name</th><th></th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;"><a href="https://pixhawk.org/platforms/planes/z-84_wing_wing">Phantom FPV Flying Wing</a></td>
 <td style="vertical-align: top;"><p>Maintainer: Simon Wilks <simon@px4.io></p><p><code>SYS_AUTOSTART</code> = 3031</p></td>

</tr>
<tr>
 <td style="vertical-align: top;"><a href="http://www.sparkletech.hk/">Sparkle Tech Pigeon</a></td>
 <td style="vertical-align: top;"><p>Maintainer: Simon Wilks <simon@px4.io></p><p><code>SYS_AUTOSTART</code> = 3036</p></td>

</tr>
<tr>
 <td style="vertical-align: top;">TBS Caipirinha</td>
 <td style="vertical-align: top;"><p>Maintainer: Lorenz Meier <lorenz@px4.io></p><p><code>SYS_AUTOSTART</code> = 3100</p></td>

</tr>
<tr>
 <td style="vertical-align: top;">FX-79 Buffalo Flying Wing</td>
 <td style="vertical-align: top;"><p>Maintainer: Simon Wilks <simon@px4.io></p><p><code>SYS_AUTOSTART</code> = 3034</p></td>

</tr>
<tr>
 <td style="vertical-align: top;"><a href="https://pixhawk.org/platforms/planes/z-84_wing_wing">Wing Wing (aka Z-84) Flying Wing</a></td>
 <td style="vertical-align: top;"><p>Maintainer: Lorenz Meier <lorenz@px4.io></p><p><code>SYS_AUTOSTART</code> = 3033</p></td>

</tr>
<tr>
 <td style="vertical-align: top;"><a href="https://pixhawk.org/platforms/planes/skywalker_x5">Skywalker X5 Flying Wing</a></td>
 <td style="vertical-align: top;"><p>Maintainer: Thomas Gubler <thomas@px4.io>, Julian Oes <julian@px4.io></p><p><code>SYS_AUTOSTART</code> = 3032</p></td>

</tr>
<tr>
 <td style="vertical-align: top;">Viper</td>
 <td style="vertical-align: top;"><p>Maintainer: Simon Wilks <simon@px4.io></p><p><code>SYS_AUTOSTART</code> = 3035</p></td>

</tr>
<tr>
 <td style="vertical-align: top;"><a href="https://pixhawk.org/platforms/planes/bormatec_camflyer_q">IO Camflyer</a></td>
 <td style="vertical-align: top;"><p>Maintainer: Simon Wilks <simon@px4.io></p><p><code>SYS_AUTOSTART</code> = 3030</p></td>

</tr>
</tbody></table>

## Helicopter

<div>
<img src="../images/airframes/types/Helicopter.svg" width="29%" style="max-height: 180px;"/>
<table style="float: right; width: 70%; font-size:1.5rem;">
 <colgroup><col></colgroup>
 <thead>
   <tr><th>Common Outputs</th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;"><ul><li><b>MAIN1</b>: main motor</li><li><b>MAIN2</b>: front swashplate servo</li><li><b>MAIN3</b>: right swashplate servo</li><li><b>MAIN4</b>: left swashplate servo</li><li><b>MAIN5</b>: tail-rotor servo</li></ul></td>
</tr>
</tbody></table>
</div>

<table style="width: 100%; table-layout:fixed; font-size:1.5rem;">
 <colgroup><col style="width: 30%"><col style="width: 70%"></colgroup>
 <thead>
   <tr><th>Name</th><th></th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;">Blade 130X</td>
 <td style="vertical-align: top;"><p>Maintainer: Bart Slinger <bartslinger@gmail.com></p><p><code>SYS_AUTOSTART</code> = 16001</p></td>

</tr>
</tbody></table>

## Hexarotor +

<div>
<img src="../images/airframes/types/HexaRotorPlus.svg" width="29%" style="max-height: 180px;"/>
<table style="float: right; width: 70%; font-size:1.5rem;">
 <colgroup><col></colgroup>
 <thead>
   <tr><th>Common Outputs</th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;"><ul><li><b>MAIN1</b>: motor1</li><li><b>MAIN2</b>: motor2</li><li><b>MAIN3</b>: motor3</li><li><b>MAIN4</b>: motor4</li><li><b>MAIN5</b>: motor5</li><li><b>MAIN6</b>: motor6</li><li><b>AUX1</b>: feed-through of RC AUX1 channel</li><li><b>AUX2</b>: feed-through of RC AUX2 channel</li><li><b>AUX3</b>: feed-through of RC AUX3 channel</li></ul></td>
</tr>
</tbody></table>
</div>

<table style="width: 100%; table-layout:fixed; font-size:1.5rem;">
 <colgroup><col style="width: 30%"><col style="width: 70%"></colgroup>
 <thead>
   <tr><th>Name</th><th></th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;">Generic Hexarotor + geometry</td>
 <td style="vertical-align: top;"><p>Maintainer: Anton Babushkin <anton@px4.io></p><p><code>SYS_AUTOSTART</code> = 7001</p></td>

</tr>
</tbody></table>

## Hexarotor Coaxial

<div>
<img src="../images/airframes/types/Y6B.svg" width="29%" style="max-height: 180px;"/>
<table style="float: right; width: 70%; font-size:1.5rem;">
 <colgroup><col></colgroup>
 <thead>
   <tr><th>Common Outputs</th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;"><ul><li><b>MAIN1</b>: front right top, CW; angle:60; direction:CW</li><li><b>MAIN2</b>: front right bottom, CCW; angle:60; direction:CCW</li><li><b>MAIN3</b>: back top, CW; angle:180; direction:CW</li><li><b>MAIN4</b>: back bottom, CCW; angle:180; direction:CCW</li><li><b>MAIN5</b>: front left top, CW; angle:-60; direction:CW</li><li><b>MAIN6</b>: front left bottom, CCW;angle:-60; direction:CCW</li><li><b>AUX1</b>: feed-through of RC AUX1 channel</li><li><b>AUX2</b>: feed-through of RC AUX2 channel</li><li><b>AUX3</b>: feed-through of RC AUX3 channel</li></ul></td>
</tr>
</tbody></table>
</div>

<table style="width: 100%; table-layout:fixed; font-size:1.5rem;">
 <colgroup><col style="width: 30%"><col style="width: 70%"></colgroup>
 <thead>
   <tr><th>Name</th><th></th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;">Generic Hexa coaxial geometry</td>
 <td style="vertical-align: top;"><p>Maintainer: Lorenz Meier <lorenz@px4.io></p><p><code>SYS_AUTOSTART</code> = 11001</p></td>

</tr>
</tbody></table>

## Hexarotor x

<div>
<img src="../images/airframes/types/HexaRotorX.svg" width="29%" style="max-height: 180px;"/>
<table style="float: right; width: 70%; font-size:1.5rem;">
 <colgroup><col></colgroup>
 <thead>
   <tr><th>Common Outputs</th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;"><ul><li><b>MAIN1</b>: motor 1</li><li><b>MAIN2</b>: motor 2</li><li><b>MAIN3</b>: motor 3</li><li><b>MAIN4</b>: motor 4</li><li><b>MAIN5</b>: motor 5</li><li><b>MAIN6</b>: motor 6</li><li><b>AUX1</b>: feed-through of RC AUX1 channel</li><li><b>AUX2</b>: feed-through of RC AUX2 channel</li><li><b>AUX3</b>: feed-through of RC AUX3 channel</li></ul></td>
</tr>
</tbody></table>
</div>

<table style="width: 100%; table-layout:fixed; font-size:1.5rem;">
 <colgroup><col style="width: 30%"><col style="width: 70%"></colgroup>
 <thead>
   <tr><th>Name</th><th></th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;">Generic Hexarotor x geometry</td>
 <td style="vertical-align: top;"><p>Maintainer: Anton Babushkin <anton@px4.io></p><p><code>SYS_AUTOSTART</code> = 6001</p></td>

</tr>
</tbody></table>

## Octo Coax Wide

<div>
<img src="../images/airframes/types/OctoRotorXCoaxial.svg" width="29%" style="max-height: 180px;"/>
<table style="float: right; width: 70%; font-size:1.5rem;">
 <colgroup><col></colgroup>
 <thead>
   <tr><th>Common Outputs</th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;"><ul><li><b>MAIN1</b>: motor 1</li><li><b>MAIN2</b>: motor 2</li><li><b>MAIN3</b>: motor 3</li><li><b>MAIN4</b>: motor 4</li><li><b>MAIN5</b>: motor 5</li><li><b>MAIN6</b>: motor 6</li><li><b>MAIN7</b>: motor 7</li><li><b>MAIN8</b>: motor 8</li></ul></td>
</tr>
</tbody></table>
</div>

<table style="width: 100%; table-layout:fixed; font-size:1.5rem;">
 <colgroup><col style="width: 30%"><col style="width: 70%"></colgroup>
 <thead>
   <tr><th>Name</th><th></th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;">Steadidrone MAVRIK</td>
 <td style="vertical-align: top;"><p>Maintainer: Simon Wilks <simon@uaventure.com></p><p><code>SYS_AUTOSTART</code> = 12002</p></td>

</tr>
</tbody></table>

## Octorotor +

<div>
<img src="../images/airframes/types/OctoRotorPlus.svg" width="29%" style="max-height: 180px;"/>
<table style="float: right; width: 70%; font-size:1.5rem;">
 <colgroup><col></colgroup>
 <thead>
   <tr><th>Common Outputs</th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;"><ul><li><b>MAIN1</b>: motor 1</li><li><b>MAIN2</b>: motor 2</li><li><b>MAIN3</b>: motor 3</li><li><b>MAIN4</b>: motor 4</li><li><b>MAIN5</b>: motor 5</li><li><b>MAIN6</b>: motor 6</li><li><b>MAIN7</b>: motor 7</li><li><b>MAIN8</b>: motor 8</li><li><b>AUX1</b>: feed-through of RC AUX1 channel</li><li><b>AUX2</b>: feed-through of RC AUX2 channel</li><li><b>AUX3</b>: feed-through of RC AUX3 channel</li></ul></td>
</tr>
</tbody></table>
</div>

<table style="width: 100%; table-layout:fixed; font-size:1.5rem;">
 <colgroup><col style="width: 30%"><col style="width: 70%"></colgroup>
 <thead>
   <tr><th>Name</th><th></th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;">Generic Octocopter + geometry</td>
 <td style="vertical-align: top;"><p>Maintainer: Anton Babushkin <anton@px4.io></p><p><code>SYS_AUTOSTART</code> = 9001</p></td>

</tr>
</tbody></table>

## Octorotor Coaxial

<div>
<img src="../images/airframes/types/OctoRotorXCoaxial.svg" width="29%" style="max-height: 180px;"/>
<table style="float: right; width: 70%; font-size:1.5rem;">
 <colgroup><col></colgroup>
 <thead>
   <tr><th>Common Outputs</th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;"><ul><li><b>MAIN1</b>: motor 1</li><li><b>MAIN2</b>: motor 2</li><li><b>MAIN3</b>: motor 3</li><li><b>MAIN4</b>: motor 4</li><li><b>MAIN5</b>: motor 5</li><li><b>MAIN6</b>: motor 6</li><li><b>MAIN7</b>: motor 7</li><li><b>MAIN8</b>: motor 8</li></ul></td>
</tr>
</tbody></table>
</div>

<table style="width: 100%; table-layout:fixed; font-size:1.5rem;">
 <colgroup><col style="width: 30%"><col style="width: 70%"></colgroup>
 <thead>
   <tr><th>Name</th><th></th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;">Generic 10" Octo coaxial geometry</td>
 <td style="vertical-align: top;"><p>Maintainer: Lorenz Meier <lorenz@px4.io></p><p><code>SYS_AUTOSTART</code> = 12001</p></td>

</tr>
</tbody></table>

## Octorotor x

<div>
<img src="../images/airframes/types/OctoRotorX.svg" width="29%" style="max-height: 180px;"/>
<table style="float: right; width: 70%; font-size:1.5rem;">
 <colgroup><col></colgroup>
 <thead>
   <tr><th>Common Outputs</th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;"><ul><li><b>MAIN1</b>: motor 1</li><li><b>MAIN2</b>: motor 2</li><li><b>MAIN3</b>: motor 3</li><li><b>MAIN4</b>: motor 4</li><li><b>MAIN5</b>: motor 5</li><li><b>MAIN6</b>: motor 6</li><li><b>MAIN7</b>: motor 7</li><li><b>MAIN8</b>: motor 8</li><li><b>AUX1</b>: feed-through of RC AUX1 channel</li><li><b>AUX2</b>: feed-through of RC AUX2 channel</li><li><b>AUX3</b>: feed-through of RC AUX3 channel</li></ul></td>
</tr>
</tbody></table>
</div>

<table style="width: 100%; table-layout:fixed; font-size:1.5rem;">
 <colgroup><col style="width: 30%"><col style="width: 70%"></colgroup>
 <thead>
   <tr><th>Name</th><th></th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;">Generic Octocopter X geometry</td>
 <td style="vertical-align: top;"><p>Maintainer: Anton Babushkin <anton@px4.io></p><p><code>SYS_AUTOSTART</code> = 8001</p></td>

</tr>
</tbody></table>

## Plane A-Tail

<div>
<img src="../images/airframes/types/PlaneATail.svg" width="29%" style="max-height: 180px;"/>
<table style="float: right; width: 70%; font-size:1.5rem;">
 <colgroup><col></colgroup>
 <thead>
   <tr><th>Common Outputs</th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;"><ul><li><b>MAIN1</b>: aileron right</li><li><b>MAIN2</b>: aileron left</li><li><b>MAIN3</b>: v-tail right</li><li><b>MAIN4</b>: v-tail left</li><li><b>MAIN5</b>: throttle</li><li><b>MAIN6</b>: wheel</li><li><b>MAIN7</b>: flaps right</li><li><b>MAIN8</b>: flaps left</li><li><b>AUX1</b>: feed-through of RC AUX1 channel</li><li><b>AUX2</b>: feed-through of RC AUX2 channel</li><li><b>AUX3</b>: feed-through of RC AUX3 channel</li></ul></td>
</tr>
</tbody></table>
</div>

<table style="width: 100%; table-layout:fixed; font-size:1.5rem;">
 <colgroup><col style="width: 30%"><col style="width: 70%"></colgroup>
 <thead>
   <tr><th>Name</th><th></th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;">Applied Aeronautics Albatross</td>
 <td style="vertical-align: top;"><p>Maintainer: Andreas Antener <andreas@uaventure.com></p><p><code>SYS_AUTOSTART</code> = 2106</p></td>

</tr>
</tbody></table>

## Quadrotor +

<div>
<img src="../images/airframes/types/QuadRotorPlus.svg" width="29%" style="max-height: 180px;"/>
<table style="float: right; width: 70%; font-size:1.5rem;">
 <colgroup><col></colgroup>
 <thead>
   <tr><th>Common Outputs</th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;"><ul><li><b>MAIN1</b>: motor 1</li><li><b>MAIN2</b>: motor 2</li><li><b>MAIN3</b>: motor 3</li><li><b>MAIN4</b>: motor 4</li><li><b>MAIN5</b>: feed-through of RC AUX1 channel</li><li><b>MAIN6</b>: feed-through of RC AUX2 channel</li><li><b>AUX1</b>: feed-through of RC AUX1 channel</li><li><b>AUX2</b>: feed-through of RC AUX2 channel</li><li><b>AUX3</b>: feed-through of RC AUX3 channel</li><li><b>AUX4</b>: feed-through of RC FLAPS channel</li></ul></td>
</tr>
</tbody></table>
</div>

<table style="width: 100%; table-layout:fixed; font-size:1.5rem;">
 <colgroup><col style="width: 30%"><col style="width: 70%"></colgroup>
 <thead>
   <tr><th>Name</th><th></th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;">Generic 10" Quad + geometry</td>
 <td style="vertical-align: top;"><p>Maintainer: Anton Babushkin <anton@px4.io></p><p><code>SYS_AUTOSTART</code> = 5001</p></td>

</tr>
</tbody></table>

## Quadrotor Wide

<div>
<img src="../images/airframes/types/QuadRotorWide.svg" width="29%" style="max-height: 180px;"/>
<table style="float: right; width: 70%; font-size:1.5rem;">
 <colgroup><col></colgroup>
 <thead>
   <tr><th>Common Outputs</th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;"><ul><li><b>AUX1</b>: feed-through of RC AUX1 channel</li><li><b>AUX2</b>: feed-through of RC AUX2 channel</li><li><b>AUX3</b>: feed-through of RC AUX3 channel</li><li><b>AUX4</b>: feed-through of RC FLAPS channel</li></ul></td>
</tr>
</tbody></table>
</div>

<table style="width: 100%; table-layout:fixed; font-size:1.5rem;">
 <colgroup><col style="width: 30%"><col style="width: 70%"></colgroup>
 <thead>
   <tr><th>Name</th><th></th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;">Team Blacksheep Discovery Endurance</td>
 <td style="vertical-align: top;"><p>Maintainer: Simon Wilks <simon@px4.io></p><p><code>SYS_AUTOSTART</code> = 10018</p><p><b>Specific Outputs:</b><ul><li><b>MAIN1</b>: motor 1</li><li><b>MAIN2</b>: motor 2</li><li><b>MAIN3</b>: motor 3</li><li><b>MAIN4</b>: motor 4</li><li><b>MAIN5</b>: feed-through of RC AUX1 channel</li><li><b>MAIN6</b>: feed-through of RC AUX2 channel</li></ul></p></td>

</tr>
<tr>
 <td style="vertical-align: top;">3DR Iris Quadrotor</td>
 <td style="vertical-align: top;"><p>Maintainer: Anton Babushkin <anton@px4.io></p><p><code>SYS_AUTOSTART</code> = 10016</p><p><b>Specific Outputs:</b><ul><li><b>MAIN1</b>: motor 1</li><li><b>MAIN2</b>: motor 2</li><li><b>MAIN3</b>: motor 3</li><li><b>MAIN4</b>: motor 4</li></ul></p></td>

</tr>
<tr>
 <td style="vertical-align: top;">Team Blacksheep Discovery</td>
 <td style="vertical-align: top;"><p>Maintainer: Anton Babushkin <anton@px4.io>, Simon Wilks <simon@px4.io></p><p><code>SYS_AUTOSTART</code> = 10015</p><p><b>Specific Outputs:</b><ul><li><b>MAIN1</b>: motor 1</li><li><b>MAIN2</b>: motor 2</li><li><b>MAIN3</b>: motor 3</li><li><b>MAIN4</b>: motor 4</li><li><b>MAIN5</b>: feed-through of RC AUX1 channel</li><li><b>MAIN6</b>: feed-through of RC AUX2 channel</li></ul></p></td>

</tr>
<tr>
 <td style="vertical-align: top;">Steadidrone QU4D</td>
 <td style="vertical-align: top;"><p>Maintainer: Thomas Gubler <thomas@px4.io></p><p><code>SYS_AUTOSTART</code> = 10017</p><p><b>Specific Outputs:</b><ul><li><b>MAIN1</b>: motor 1</li><li><b>MAIN2</b>: motor 2</li><li><b>MAIN3</b>: motor 3</li><li><b>MAIN4</b>: motor 4</li><li><b>MAIN5</b>: feed-through of RC AUX1 channel</li><li><b>MAIN6</b>: feed-through of RC AUX2 channel</li></ul></p></td>

</tr>
</tbody></table>

## Quadrotor asymmetric

<div>
<table style="float: right; width: 70%; font-size:1.5rem;">
 <colgroup><col></colgroup>
 <thead>
   <tr><th>Common Outputs</th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;"><ul><li><b>MAIN1</b>: motor1 (front right: CCW)</li><li><b>MAIN2</b>: motor2 (back left: CCW)</li><li><b>MAIN3</b>: motor3 (front left: CW)</li><li><b>MAIN4</b>: motor4 (back right: CW)</li><li><b>MAIN5</b>: feed-through of RC AUX1 channel</li><li><b>MAIN6</b>: feed-through of RC AUX2 channel</li></ul></td>
</tr>
</tbody></table>
</div>

<table style="width: 100%; table-layout:fixed; font-size:1.5rem;">
 <colgroup><col style="width: 30%"><col style="width: 70%"></colgroup>
 <thead>
   <tr><th>Name</th><th></th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;">Spedix S250AQ</td>
 <td style="vertical-align: top;"><p>Maintainer: Mark Whitehorn <kd0aij@gmail.com></p><p><code>SYS_AUTOSTART</code> = 4051</p></td>

</tr>
</tbody></table>

## Quadrotor x

<div>
<img src="../images/airframes/types/QuadRotorX.svg" width="29%" style="max-height: 180px;"/>
<table style="float: right; width: 70%; font-size:1.5rem;">
 <colgroup><col></colgroup>
 <thead>
   <tr><th>Common Outputs</th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;"><ul><li><b>MAIN1</b>: motor 1</li><li><b>MAIN2</b>: motor 2</li><li><b>MAIN3</b>: motor 3</li><li><b>MAIN4</b>: motor 4</li><li><b>MAIN5</b>: feed-through of RC AUX1 channel</li><li><b>MAIN6</b>: feed-through of RC AUX2 channel</li></ul></td>
</tr>
</tbody></table>
</div>

<table style="width: 100%; table-layout:fixed; font-size:1.5rem;">
 <colgroup><col style="width: 30%"><col style="width: 70%"></colgroup>
 <thead>
   <tr><th>Name</th><th></th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;">Generic Quadrotor X config</td>
 <td style="vertical-align: top;"><p>Maintainer: Lorenz Meier <lorenz@px4.io></p><p><code>SYS_AUTOSTART</code> = 4001</p><p><b>Specific Outputs:</b><ul><li><b>AUX1</b>: feed-through of RC AUX1 channel</li><li><b>AUX2</b>: feed-through of RC AUX2 channel</li><li><b>AUX3</b>: feed-through of RC AUX3 channel</li><li><b>AUX4</b>: feed-through of RC FLAPS channel</li></ul></p></td>

</tr>
<tr>
 <td style="vertical-align: top;">Lumenier QAV250</td>
 <td style="vertical-align: top;"><p>Maintainer: Mark Whitehorn <kd0aij@gmail.com></p><p><code>SYS_AUTOSTART</code> = 4009</p></td>

</tr>
<tr>
 <td style="vertical-align: top;">DJI Matrice 100</td>
 <td style="vertical-align: top;"><p>Maintainer: James Goppert <james.goppert@gmail.com></p><p><code>SYS_AUTOSTART</code> = 4060</p></td>

</tr>
<tr>
 <td style="vertical-align: top;">H4 680mm with Z1 Tiny2 Gimbal</td>
 <td style="vertical-align: top;"><p>Maintainer: Leon Mueller <thedevleon></p><p><code>SYS_AUTOSTART</code> = 10021</p></td>

</tr>
<tr>
 <td style="vertical-align: top;">3DR Solo</td>
 <td style="vertical-align: top;"><p>Maintainer: Andreas Antener <andreas@uaventure.com></p><p><code>SYS_AUTOSTART</code> = 4030</p></td>

</tr>
<tr>
 <td style="vertical-align: top;">Lumenier QAV-R (raceblade) 5" arms</td>
 <td style="vertical-align: top;"><p>Maintainer: James Goppert <james.goppert@gmail.com></p><p><code>SYS_AUTOSTART</code> = 4003</p></td>

</tr>
<tr>
 <td style="vertical-align: top;">DJI Flame Wheel F330</td>
 <td style="vertical-align: top;"><p>Maintainer: Lorenz Meier <lorenz@px4.io></p><p><code>SYS_AUTOSTART</code> = 4010</p></td>

</tr>
<tr>
 <td style="vertical-align: top;">3DR DIY Quad</td>
 <td style="vertical-align: top;"><p>Maintainer: Lorenz Meier <lorenz@px4.io></p><p><code>SYS_AUTOSTART</code> = 10020</p></td>

</tr>
<tr>
 <td style="vertical-align: top;">Generic Quadrotor X config with mount (e.g. gimbal)</td>
 <td style="vertical-align: top;"><p>Maintainer: Leon Mueller <thedevleon></p><p><code>SYS_AUTOSTART</code> = 4002</p><p><b>Specific Outputs:</b><ul><li><b>AUX1</b>: Mount pitch</li><li><b>AUX2</b>: Mount roll</li><li><b>AUX3</b>: Mount yaw</li><li><b>AUX4</b>: Mount mode</li><li><b>AUX5</b>: Mount retract</li></ul></p></td>

</tr>
<tr>
 <td style="vertical-align: top;">Intel Aero RTF</td>
 <td style="vertical-align: top;"><p>Maintainer: John Doe <john@example.com></p><p><code>SYS_AUTOSTART</code> = 4070</p></td>

</tr>
<tr>
 <td style="vertical-align: top;">Crazyflie 2.0</td>
 <td style="vertical-align: top;"><p>Maintainer: John Doe <john@example.com></p><p><code>SYS_AUTOSTART</code> = 4900</p></td>

</tr>
<tr>
 <td style="vertical-align: top;">NanoMind 110 Quad</td>
 <td style="vertical-align: top;"><p>Maintainer: Henry Zhang <zhanghui629@gmail.com></p><p><code>SYS_AUTOSTART</code> = 4090</p></td>

</tr>
<tr>
 <td style="vertical-align: top;">F450-sized quadrotor with CAN</td>
 <td style="vertical-align: top;"><p>Maintainer: Pavel Kirienko <pavel@px4.io></p><p><code>SYS_AUTOSTART</code> = 4012</p></td>

</tr>
<tr>
 <td style="vertical-align: top;">Generic 250 Racer</td>
 <td style="vertical-align: top;"><p>Maintainer: Mark Whitehorn <kd0aij@gmail.com></p><p><code>SYS_AUTOSTART</code> = 4050</p></td>

</tr>
<tr>
 <td style="vertical-align: top;">AR.Drone Frame</td>
 <td style="vertical-align: top;"><p>Maintainer: Lorenz Meier <lorenz@px4.io></p><p><code>SYS_AUTOSTART</code> = 4008</p></td>

</tr>
<tr>
 <td style="vertical-align: top;">Parrot Bebop Frame</td>
 <td style="vertical-align: top;"><p>Maintainer: Michael Schaeuble</p><p><code>SYS_AUTOSTART</code> = 4013</p></td>

</tr>
<tr>
 <td style="vertical-align: top;">Hobbyking Micro PCB</td>
 <td style="vertical-align: top;"><p>Maintainer: Thomas Gubler <thomas@px4.io></p><p><code>SYS_AUTOSTART</code> = 4020</p></td>

</tr>
<tr>
 <td style="vertical-align: top;">DJI Flame Wheel F450</td>
 <td style="vertical-align: top;"><p>Maintainer: Lorenz Meier <lorenz@px4.io></p><p><code>SYS_AUTOSTART</code> = 4011</p></td>

</tr>
<tr>
 <td style="vertical-align: top;">ZMR250 Racer</td>
 <td style="vertical-align: top;"><p>Maintainer: Anton Matosov <anton.matosov@gmail.com></p><p><code>SYS_AUTOSTART</code> = 4080</p></td>

</tr>
<tr>
 <td style="vertical-align: top;">Reaper 500 Quad</td>
 <td style="vertical-align: top;"><p>Maintainer: Blankered</p><p><code>SYS_AUTOSTART</code> = 4040</p></td>

</tr>
</tbody></table>

## Rover

<div>
<img src="../images/airframes/types/Rover.svg" width="29%" style="max-height: 180px;"/>
<table style="float: right; width: 70%; font-size:1.5rem;">
 <colgroup><col></colgroup>
 <thead>
   <tr><th>Common Outputs</th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;"><ul><li><b>MAIN1</b>: pass-through of control group 0, channel 0</li><li><b>MAIN2</b>: pass-through of control group 0, channel 1</li><li><b>MAIN3</b>: pass-through of control group 0, channel 2</li><li><b>MAIN4</b>: pass-through of control group 0, channel 3</li><li><b>MAIN5</b>: pass-through of control group 0, channel 4</li><li><b>MAIN6</b>: pass-through of control group 0, channel 5</li><li><b>MAIN7</b>: pass-through of control group 0, channel 6</li><li><b>MAIN8</b>: pass-through of control group 0, channel 7</li></ul></td>
</tr>
</tbody></table>
</div>

<table style="width: 100%; table-layout:fixed; font-size:1.5rem;">
 <colgroup><col style="width: 30%"><col style="width: 70%"></colgroup>
 <thead>
   <tr><th>Name</th><th></th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;">Axial Racing AX10</td>
 <td style="vertical-align: top;"><p>Maintainer: John Doe <john@example.com></p><p><code>SYS_AUTOSTART</code> = 50001</p></td>

</tr>
</tbody></table>

## Simulation

<div>
<img src="../images/airframes/types/AirframeSimulation.svg" width="29%" style="max-height: 180px;"/>
<table style="float: right; width: 70%; font-size:1.5rem;">
 <colgroup><col></colgroup>
 <thead>
   <tr><th>Common Outputs</th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;"><ul><li><b>MAIN1</b>: aileron</li><li><b>MAIN2</b>: elevator</li><li><b>MAIN3</b>: rudder</li><li><b>MAIN4</b>: throttle</li></ul></td>
</tr>
</tbody></table>
</div>

<table style="width: 100%; table-layout:fixed; font-size:1.5rem;">
 <colgroup><col style="width: 30%"><col style="width: 70%"></colgroup>
 <thead>
   <tr><th>Name</th><th></th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;">HIL Quadcopter X</td>
 <td style="vertical-align: top;"><p>Maintainer: Anton Babushkin <anton@px4.io></p><p><code>SYS_AUTOSTART</code> = 1001</p></td>

</tr>
<tr>
 <td style="vertical-align: top;">HILStar (XPlane)</td>
 <td style="vertical-align: top;"><p>Maintainer: Lorenz Meier <lorenz@px4.io></p><p><code>SYS_AUTOSTART</code> = 1000</p></td>

</tr>
<tr>
 <td style="vertical-align: top;">HIL Quadcopter +</td>
 <td style="vertical-align: top;"><p>Maintainer: Anton Babushkin <anton@px4.io></p><p><code>SYS_AUTOSTART</code> = 1003</p></td>

</tr>
</tbody></table>

## Standard Plane

<div>
<img src="../images/airframes/types/Plane.svg" width="29%" style="max-height: 180px;"/>
<table style="float: right; width: 70%; font-size:1.5rem;">
 <colgroup><col></colgroup>
 <thead>
   <tr><th>Common Outputs</th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;"><ul><li><b>AUX1</b>: feed-through of RC AUX1 channel</li><li><b>AUX2</b>: feed-through of RC AUX2 channel</li><li><b>AUX3</b>: feed-through of RC AUX3 channel</li></ul></td>
</tr>
</tbody></table>
</div>

<table style="width: 100%; table-layout:fixed; font-size:1.5rem;">
 <colgroup><col style="width: 30%"><col style="width: 70%"></colgroup>
 <thead>
   <tr><th>Name</th><th></th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;">Standard AETR Plane</td>
 <td style="vertical-align: top;"><p>Maintainer: Lorenz Meier <lorenz@px4.io></p><p><code>SYS_AUTOSTART</code> = 2104</p><p><b>Specific Outputs:</b><ul><li><b>MAIN1</b>: aileron</li><li><b>MAIN2</b>: elevator</li><li><b>MAIN3</b>: throttle</li><li><b>MAIN4</b>: rudder</li><li><b>MAIN5</b>: flaps</li></ul></p></td>

</tr>
<tr>
 <td style="vertical-align: top;">Multiplex Easystar</td>
 <td style="vertical-align: top;"><p>Maintainer: Lorenz Meier <lorenz@px4.io></p><p><code>SYS_AUTOSTART</code> = 2100</p><p><b>Specific Outputs:</b><ul><li><b>MAIN1</b>: aileron</li><li><b>MAIN2</b>: elevator</li><li><b>MAIN3</b>: rudder</li><li><b>MAIN4</b>: throttle</li></ul></p></td>

</tr>
<tr>
 <td style="vertical-align: top;">Bormatec Maja</td>
 <td style="vertical-align: top;"><p>Maintainer: Andreas Antener <andreas@uaventure.com></p><p><code>SYS_AUTOSTART</code> = 2105</p><p><b>Specific Outputs:</b><ul><li><b>MAIN1</b>: aileron</li><li><b>MAIN2</b>: aileron</li><li><b>MAIN3</b>: elevator</li><li><b>MAIN4</b>: rudder</li><li><b>MAIN5</b>: throttle</li><li><b>MAIN6</b>: wheel</li><li><b>MAIN7</b>: flaps</li></ul></p></td>

</tr>
<tr>
 <td style="vertical-align: top;">Skyhunter 1800</td>
 <td style="vertical-align: top;"><p>Maintainer: Lorenz Meier <lorenz@px4.io></p><p><code>SYS_AUTOSTART</code> = 2103</p><p><b>Specific Outputs:</b><ul><li><b>MAIN1</b>: aileron</li><li><b>MAIN2</b>: elevator</li><li><b>MAIN4</b>: throttle</li></ul></p></td>

</tr>
<tr>
 <td style="vertical-align: top;">Skywalker (3DR Aero)</td>
 <td style="vertical-align: top;"><p>Maintainer: Lorenz Meier <lorenz@px4.io></p><p><code>SYS_AUTOSTART</code> = 2102</p><p><b>Specific Outputs:</b><ul><li><b>MAIN1</b>: aileron</li><li><b>MAIN2</b>: elevator</li><li><b>MAIN3</b>: throttle</li><li><b>MAIN4</b>: rudder</li><li><b>MAIN5</b>: flaps</li></ul></p></td>

</tr>
<tr>
 <td style="vertical-align: top;">Standard AERT Plane</td>
 <td style="vertical-align: top;"><p>Maintainer: Lorenz Meier <lorenz@px4.io></p><p><code>SYS_AUTOSTART</code> = 2101</p><p><b>Specific Outputs:</b><ul><li><b>MAIN1</b>: aileron</li><li><b>MAIN2</b>: elevator</li><li><b>MAIN3</b>: rudder</li><li><b>MAIN4</b>: throttle</li><li><b>MAIN5</b>: flaps</li></ul></p></td>

</tr>
</tbody></table>

## Standard VTOL

<div>
<img src="../images/airframes/types/VTOLPlane.svg" width="29%" style="max-height: 180px;"/>
<table style="float: right; width: 70%; font-size:1.5rem;">
 <colgroup><col></colgroup>
 <thead>
   <tr><th>Common Outputs</th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;"><ul><li><b>MAIN1</b>: motor 1</li><li><b>MAIN2</b>: motor 2</li><li><b>MAIN3</b>: motor 3</li><li><b>MAIN4</b>: motor 4</li></ul></td>
</tr>
</tbody></table>
</div>

<table style="width: 100%; table-layout:fixed; font-size:1.5rem;">
 <colgroup><col style="width: 30%"><col style="width: 70%"></colgroup>
 <thead>
   <tr><th>Name</th><th></th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;">Sparkle Tech Ranger VTOL</td>
 <td style="vertical-align: top;"><p>Maintainer: Andreas Antener <andreas@uaventure.com></p><p><code>SYS_AUTOSTART</code> = 13009</p></td>

</tr>
<tr>
 <td style="vertical-align: top;">Generic AAVVT v-tail plane airframe with Quad VTOL.</td>
 <td style="vertical-align: top;"><p>Maintainer: Sander Smeets <sander@droneslab.com></p><p><code>SYS_AUTOSTART</code> = 13007</p></td>

</tr>
<tr>
 <td style="vertical-align: top;">DeltaQuad</td>
 <td style="vertical-align: top;"><p>Maintainer: Sander Smeets <sander@droneslab.com></p><p><code>SYS_AUTOSTART</code> = 13013</p><p><b>Specific Outputs:</b><ul><li><b>AUX1</b>: Right elevon</li><li><b>AUX2</b>: Left elevon</li><li><b>AUX3</b>: Motor</li></ul></p></td>

</tr>
<tr>
 <td style="vertical-align: top;">QuadRanger</td>
 <td style="vertical-align: top;"><p>Maintainer: Sander Smeets <sander@droneslab.com></p><p><code>SYS_AUTOSTART</code> = 13008</p></td>

</tr>
<tr>
 <td style="vertical-align: top;">Fun Cub Quad VTOL</td>
 <td style="vertical-align: top;"><p>Maintainer: Simon Wilks <simon@uaventure.com></p><p><code>SYS_AUTOSTART</code> = 13005</p><p><b>Specific Outputs:</b><ul><li><b>AUX1</b>: Aileron 1</li><li><b>AUX2</b>: Aileron 2</li><li><b>AUX3</b>: Elevator</li><li><b>AUX4</b>: Rudder</li><li><b>AUX5</b>: Throttle</li></ul></p></td>

</tr>
<tr>
 <td style="vertical-align: top;">Generic quad delta VTOL</td>
 <td style="vertical-align: top;"><p>Maintainer: Simon Wilks <simon@uaventure.com></p><p><code>SYS_AUTOSTART</code> = 13006</p><p><b>Specific Outputs:</b><ul><li><b>AUX1</b>: Right elevon</li><li><b>AUX2</b>: Left elevon</li><li><b>AUX3</b>: Motor</li></ul></p></td>

</tr>
</tbody></table>

## Tricopter Y+

<div>
<img src="../images/airframes/types/YPlus.svg" width="29%" style="max-height: 180px;"/>
<table style="float: right; width: 70%; font-size:1.5rem;">
 <colgroup><col></colgroup>
 <thead>
   <tr><th>Common Outputs</th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;"><ul><li><b>MAIN1</b>: motor 1</li><li><b>MAIN2</b>: motor 2</li><li><b>MAIN3</b>: motor 3</li><li><b>MAIN4</b>: yaw servo</li></ul></td>
</tr>
</tbody></table>
</div>

<table style="width: 100%; table-layout:fixed; font-size:1.5rem;">
 <colgroup><col style="width: 30%"><col style="width: 70%"></colgroup>
 <thead>
   <tr><th>Name</th><th></th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;">Generic Tricopter Y+ Geometry</td>
 <td style="vertical-align: top;"><p>Maintainer: Trent Lukaczyk <aerialhedgehog@gmail.com></p><p><code>SYS_AUTOSTART</code> = 14001</p></td>

</tr>
</tbody></table>

## Tricopter Y-

<div>
<img src="../images/airframes/types/YMinus.svg" width="29%" style="max-height: 180px;"/>
<table style="float: right; width: 70%; font-size:1.5rem;">
 <colgroup><col></colgroup>
 <thead>
   <tr><th>Common Outputs</th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;"><ul><li><b>MAIN1</b>: motor 1</li><li><b>MAIN2</b>: motor 2</li><li><b>MAIN3</b>: motor 3</li><li><b>MAIN4</b>: yaw servo</li></ul></td>
</tr>
</tbody></table>
</div>

<table style="width: 100%; table-layout:fixed; font-size:1.5rem;">
 <colgroup><col style="width: 30%"><col style="width: 70%"></colgroup>
 <thead>
   <tr><th>Name</th><th></th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;">Generic Tricopter Y- Geometry</td>
 <td style="vertical-align: top;"><p>Maintainer: Trent Lukaczyk <aerialhedgehog@gmail.com></p><p><code>SYS_AUTOSTART</code> = 14002</p></td>

</tr>
</tbody></table>

## VTOL Duo Tailsitter

<div>
<img src="../images/airframes/types/VTOLDuoRotorTailSitter.svg" width="29%" style="max-height: 180px;"/>
<table style="float: right; width: 70%; font-size:1.5rem;">
 <colgroup><col></colgroup>
 <thead>
   <tr><th>Common Outputs</th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;"><ul><li><b>MAIN1</b>: motor right</li><li><b>MAIN2</b>: motor left</li><li><b>MAIN5</b>: elevon right</li><li><b>MAIN6</b>: elevon left</li></ul></td>
</tr>
</tbody></table>
</div>

<table style="width: 100%; table-layout:fixed; font-size:1.5rem;">
 <colgroup><col style="width: 30%"><col style="width: 70%"></colgroup>
 <thead>
   <tr><th>Name</th><th></th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;">Caipiroshka Duo Tailsitter</td>
 <td style="vertical-align: top;"><p>Maintainer: Roman Bapst <roman@px4.io></p><p><code>SYS_AUTOSTART</code> = 13001</p></td>

</tr>
</tbody></table>

## VTOL Quad Tailsitter

<div>
<img src="../images/airframes/types/VTOLQuadRotorTailSitter.svg" width="29%" style="max-height: 180px;"/>
<table style="float: right; width: 70%; font-size:1.5rem;">
 <colgroup><col></colgroup>
 <thead>
   <tr><th>Common Outputs</th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;"><ul><li><b>MAIN1</b>: motor 1</li><li><b>MAIN2</b>: motor 2</li><li><b>MAIN3</b>: motor 4</li><li><b>MAIN4</b>: motor 5</li><li><b>MAIN5</b>: elevon left</li><li><b>MAIN6</b>: elevon right</li><li><b>MAIN7</b>: canard surface</li><li><b>MAIN8</b>: rudder</li></ul></td>
</tr>
</tbody></table>
</div>

<table style="width: 100%; table-layout:fixed; font-size:1.5rem;">
 <colgroup><col style="width: 30%"><col style="width: 70%"></colgroup>
 <thead>
   <tr><th>Name</th><th></th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;">Quadrotor + Tailsitter</td>
 <td style="vertical-align: top;"><p>Maintainer: Roman Bapst <roman@px4.io></p><p><code>SYS_AUTOSTART</code> = 13004</p></td>

</tr>
<tr>
 <td style="vertical-align: top;">Quadrotor X Tailsitter</td>
 <td style="vertical-align: top;"><p>Maintainer: Roman Bapst <roman@px4.io></p><p><code>SYS_AUTOSTART</code> = 13003</p></td>

</tr>
</tbody></table>

## VTOL Tiltrotor

<div>
<img src="../images/airframes/types/VTOLTiltRotor.svg" width="29%" style="max-height: 180px;"/>
<table style="float: right; width: 70%; font-size:1.5rem;">
 <colgroup><col></colgroup>
 <thead>
   <tr><th>Common Outputs</th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;"><ul><li><b>AUX1</b>: Tilt servo</li><li><b>AUX2</b>: Elevon 1</li><li><b>AUX3</b>: Elevon 2</li><li><b>AUX4</b>: Gear</li></ul></td>
</tr>
</tbody></table>
</div>

<table style="width: 100%; table-layout:fixed; font-size:1.5rem;">
 <colgroup><col style="width: 30%"><col style="width: 70%"></colgroup>
 <thead>
   <tr><th>Name</th><th></th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;">E-flite Convergence</td>
 <td style="vertical-align: top;"><p>Maintainer: Andreas Antener <andreas@uaventure.com></p><p><code>SYS_AUTOSTART</code> = 13012</p><p><b>Specific Outputs:</b><ul><li><b>MAIN1</b>: Motor right</li><li><b>MAIN2</b>: Motor left</li><li><b>MAIN3</b>: Motor back</li><li><b>MAIN4</b>: empty</li><li><b>MAIN5</b>: Tilt servo right</li><li><b>MAIN6</b>: Tilt servo left</li><li><b>MAIN7</b>: Elevon right</li><li><b>MAIN8</b>: Elevon left</li></ul></p></td>

</tr>
<tr>
 <td style="vertical-align: top;">CruiseAder Claire</td>
 <td style="vertical-align: top;"><p>Maintainer: Samay Siga <samay_s@icloud.com></p><p><code>SYS_AUTOSTART</code> = 13010</p></td>

</tr>
<tr>
 <td style="vertical-align: top;">BirdsEyeView Aerobotics FireFly6</td>
 <td style="vertical-align: top;"><p>Maintainer: Roman Bapst <roman@uaventure.com></p><p><code>SYS_AUTOSTART</code> = 13002</p><p><b>Specific Outputs:</b><ul><li><b>MAIN1</b>: Front right motor bottom</li><li><b>MAIN2</b>: Front right motor top</li><li><b>MAIN3</b>: Back motor bottom</li><li><b>MAIN4</b>: Back motor top</li><li><b>MAIN5</b>: Front left motor bottom</li><li><b>MAIN6</b>: Front left motor top</li></ul></p></td>

</tr>
</tbody></table>

## custom

<div>
</div>

<table style="width: 100%; table-layout:fixed; font-size:1.5rem;">
 <colgroup><col style="width: 30%"><col style="width: 70%"></colgroup>
 <thead>
   <tr><th>Name</th><th></th></tr>
 </thead>
<tbody>
<tr>
 <td style="vertical-align: top;">Passthrough mode for Snapdragon</td>
 <td style="vertical-align: top;"><p>Maintainer: Julian Oes <julian@oes.ch>
This startup can be used on Pixhawk/Pixfalcon/Pixracer for the
passthrough of RC input and PWM output.</p><p><code>SYS_AUTOSTART</code> = 20000</p></td>

</tr>
</tbody></table>

