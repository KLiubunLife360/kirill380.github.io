# Language comparision 


## Data structures and types 

<table>
  <thead>
  <tr style="height:20px;">
    <td class="s0" dir="ltr">Datastructures / Language</td>
    <td align="center" colspan="3">Array</td>
    <td align="center"  colspan="3">Map/Dictionary</td>
  </tr>
  </thead>
  <tbody>
  <tr style="height:20px;">
    <td class="s0" dir="ltr">Java 9</td>
    <td class="s2" dir="ltr">  
       <pre lang="java">Type[] arr; Type arr[];</pre>
    </td>
    <td class="s2" dir="ltr">
      <pre lang="java">{a, b, c}</pre>
    </td>
    <td class="s2" dir="ltr">
      <pre lang="java">new Type[] {a, b, c}</pre>
    </td>
    <td class="s2" dir="ltr">Map&lt;K, V&gt; map;</td>
    <td class="s2" dir="ltr">Map.of(key, value, key2, value2)</td>
    <td class="s2" dir="ltr">new HashMap&lt;K, V&gt;()</td>
  </tr>
  <tr style="height:20px;" style="background-color:#FFF">
    <td class="s3" dir="ltr">Kotlin</td>
    <td class="s2" dir="ltr">
      <pre lang="Kotlin"> var arr: Array&lt;T&gt; </pre>
    </td>
    <td class="s2" dir="ltr">
      <pre lang="Kotlin">  arrayOf(a, b, c)</td>  </pre>
    <td class="s2" dir="ltr"></td>
    <td class="s2" dir="ltr">
      <pre lang="Kotlin"> val map: Map&lt;K, V&gt; </pre>
    </td>
    <td class="s2" dir="ltr">
      <pre lang="Kotlin">  mapOf(key to value, key1 to value2) </pre>
    </td>
    <td class="s2" dir="ltr">
       <pre lang="Kotlin">  HashMap&lt;K, V&gt;() </pre>
    </td>
  </tr>
  <tr style="height:20px;">
    <td class="s0" dir="ltr">JS</td>
    <td class="s4" dir="ltr"></td>
    <td class="s2" dir="ltr"> 
       <pre lang="javascript"> [a, b, c] </pre>
    </td>
    <td class="s2" dir="ltr"> Array(a, b, c)</td>
    <td class="s4" dir="ltr"></td>
    <td class="s2" dir="ltr">{ "k" : v, "k1" : v }</td>
    <td class="s2" dir="ltr"></td>
  </tr>
  <tr style="height:20px;">
    <td class="s0" dir="ltr">Python 3.8</td>
    <td class="s4" dir="ltr"></td>
    <td class="s2" dir="ltr">array([a, b, c])</td>
    <td class="s2" dir="ltr"></td>
    <td class="s2" dir="ltr"></td>
    <td class="s2" dir="ltr">{ k : v, k1 : v }</td>
    <td class="s2" dir="ltr"></td>
  </tr>
  <tr style="height:20px;">
    <td class="s3" dir="ltr">C/C++ 11</td>
    <td class="s2" dir="ltr">Type arr[];</td>
    <td class="s2" dir="ltr">{a, b, c}</td>
    <td class="s2" dir="ltr">(Type[]) { a, b, c }</td>
    <td class="s2" dir="ltr">std::map&lt;k, v&gt; map</td>
    <td class="s2" dir="ltr"> {{k, v}, {k, v}}</td>
    <td class="s2" dir="ltr"></td>
  </tr>
  <tr style="height:20px;">
    <td class="s3" dir="ltr">Bash</td>
    <td class="s5" dir="ltr"></td>
    <td class="s6" dir="ltr">(a, b, c)</td>
    <td class="s6" dir="ltr"></td>
    <td class="s7" dir="ltr" colspan="3">N/A</td>
  </tr>
  </tbody>
</table>
