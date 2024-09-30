---
layout: default
title: Data
subtitle: Player Classification Data
---

# Player Classification Data

We conduct our experiments using the [SoccerNet-V2 dataset](https://www.soccer-net.org/data). SoccerNet-V2 is currently the most extensive dataset of its type, comprising 500 soccer broadcast videos totaling over 750 hours. We maintain the same data splits as originally introduce SoccerNet-V2, consisting of 300 games for training, 100 for validation, and 100 for testing. 

We extend the annotations of the 100 test games in the dataset. Specifically, we manually segment and label approximately 80K people in the field aided by [PointRend](https://ai.meta.com/research/publications/pointrend-image-segmentation-as-rendering/) and [Segment Anything](https://segment-anything.com/). The annotated classes correspond to player, goalkeeper, referee, or other (e.g. technical staff in the field).

## Annotated Test Matches

<style>
    .table-container {
        display: inline-block;
        margin-right: 20px; /* Add space between the tables */
        vertical-align: top;
    }
    table {
        width: 300px;
        border-collapse: collapse;
    }
    table, th, td {
        border: 1px solid black;
    }
    td {
        text-align: center;
        padding: 10px;
    }
</style>

<div class="table-container">
<table style="width:50px;">
  <tr>
    <th>Match</th>
    <th><center>Kits</center><embed src="../assets/kits/letters.svg" /></th>
  </tr>
  <tr>
  	<td>001</td>
    <td>
      <embed src="../assets/kits/001.svg" />
    </td>
  </tr>
  <tr>
  	<td>002</td>
    <td>
      <embed src="../assets/kits/002.svg" />
    </td>
  </tr>
  <tr>
  	<td>003</td>
    <td>
      <embed src="../assets/kits/003.svg" />
    </td>
  </tr>
  <tr>
  	<td>004</td>
    <td>
      <embed src="../assets/kits/004.svg" />
    </td>
  </tr>
  <tr>
  	<td>005</td>
    <td>
      <embed src="../assets/kits/005.svg" />
    </td>
  </tr>  
  <tr>
  	<td>006</td>
    <td>
      <embed src="../assets/kits/006.svg" />
    </td>
  </tr>
  <tr>
  	<td>007</td>
    <td>
      <embed src="../assets/kits/007.svg" />
    </td>
  </tr>
  <tr>
  	<td>008</td>
    <td>
      <embed src="../assets/kits/008.svg" />
    </td>
  </tr>
  <tr>
  	<td>009</td>
    <td>
      <embed src="../assets/kits/009.svg" />
    </td>
  </tr>
  <tr>
  	<td>010</td>
    <td>
      <embed src="../assets/kits/010.svg" />
    </td>
  </tr>
  <tr>
  	<td>011</td>
    <td>
      <embed src="../assets/kits/011.svg" />
    </td>
  </tr>
  <tr>
  	<td>012</td>
    <td>
      <embed src="../assets/kits/012.svg" />
    </td>
  </tr>
  <tr>
  	<td>013</td>
    <td>
      <embed src="../assets/kits/013.svg" />
    </td>
  </tr>
  <tr>
  	<td>014</td>
    <td>
      <embed src="../assets/kits/014.svg" />
    </td>
  </tr>
  <tr>
  	<td>015</td>
    <td>
      <embed src="../assets/kits/015.svg" />
    </td>
  </tr>  
  <tr>
  	<td>016</td>
    <td>
      <embed src="../assets/kits/016.svg" />
    </td>
  </tr>
  <tr>
  	<td>017</td>
    <td>
      <embed src="../assets/kits/017.svg" />
    </td>
  </tr>
  <tr>
  	<td>018</td>
    <td>
      <embed src="../assets/kits/018.svg" />
    </td>
  </tr>
  <tr>
  	<td>019</td>
    <td>
      <embed src="../assets/kits/019.svg" />
    </td>
  </tr>
  <tr>
  	<td>020</td>
    <td>
      <embed src="../assets/kits/020.svg" />
    </td>
  </tr>
  <tr>
  	<td>021</td>
    <td>
      <embed src="../assets/kits/021.svg" />
    </td>
  </tr>
  <tr>
  	<td>022</td>
    <td>
      <embed src="../assets/kits/022.svg" />
    </td>
  </tr>
  <tr>
  	<td>023</td>
    <td>
      <embed src="../assets/kits/023.svg" />
    </td>
  </tr>
  <tr>
  	<td>024</td>
    <td>
      <embed src="../assets/kits/024.svg" />
    </td>
  </tr>
  <tr>
  	<td>025</td>
    <td>
      <embed src="../assets/kits/025.svg" />
    </td>
  </tr>  
  <tr>
  	<td>026</td>
    <td>
      <embed src="../assets/kits/026.svg" />
    </td>
  </tr>
  <tr>
  	<td>027</td>
    <td>
      <embed src="../assets/kits/027.svg" />
    </td>
  </tr>
  <tr>
  	<td>028</td>
    <td>
      <embed src="../assets/kits/028.svg" />
    </td>
  </tr>
  <tr>
  	<td>029</td>
    <td>
      <embed src="../assets/kits/029.svg" />
    </td>
  </tr>
  <tr>
  	<td>030</td>
    <td>
      <embed src="../assets/kits/030.svg" />
    </td>
  </tr>
  <tr>
  	<td>031</td>
    <td>
      <embed src="../assets/kits/031.svg" />
    </td>
  </tr>
  <tr>
  	<td>032</td>
    <td>
      <embed src="../assets/kits/032.svg" />
    </td>
  </tr>
  <tr>
  	<td>033</td>
    <td>
      <embed src="../assets/kits/033.svg" />
    </td>
  </tr>
  <tr>
    <td>034</td>
    <td>
      <embed src="../assets/kits/034.svg" />
    </td>
  </tr>
</table>
</div>

<div class="table-container">
<table style="width:50px;">
  <tr>
    <th>Match</th>
    <th><center>Kits</center><embed src="../assets/kits/letters.svg" /></th>
  </tr>
  <tr>
    <td>035</td>
    <td>
      <embed src="../assets/kits/035.svg" />
    </td>
  </tr>  
  <tr>
    <td>036</td>
    <td>
      <embed src="../assets/kits/036.svg" />
    </td>
  </tr>
  <tr>
    <td>037</td>
    <td>
      <embed src="../assets/kits/037.svg" />
    </td>
  </tr>
  <tr>
    <td>038</td>
    <td>
      <embed src="../assets/kits/038.svg" />
    </td>
  </tr>
  <tr>
    <td>039</td>
    <td>
      <embed src="../assets/kits/039.svg" />
    </td>
  </tr>
  <tr>
    <td>040</td>
    <td>
      <embed src="../assets/kits/040.svg" />
    </td>
  </tr>
  <tr>
    <td>041</td>
    <td>
      <embed src="../assets/kits/041.svg" />
    </td>
  </tr>
  <tr>
    <td>042</td>
    <td>
      <embed src="../assets/kits/042.svg" />
    </td>
  </tr>
  <tr>
    <td>043</td>
    <td>
      <embed src="../assets/kits/043.svg" />
    </td>
  </tr>
  <tr>
    <td>044</td>
    <td>
      <embed src="../assets/kits/044.svg" />
    </td>
  </tr>
  <tr>
    <td>045</td>
    <td>
      <embed src="../assets/kits/045.svg" />
    </td>
  </tr>  
  <tr>
    <td>046</td>
    <td>
      <embed src="../assets/kits/046.svg" />
    </td>
  </tr>
  <tr>
    <td>047</td>
    <td>
      <embed src="../assets/kits/047.svg" />
    </td>
  </tr>
  <tr>
    <td>048</td>
    <td>
      <embed src="../assets/kits/048.svg" />
    </td>
  </tr>
  <tr>
    <td>049</td>
    <td>
      <embed src="../assets/kits/049.svg" />
    </td>
  </tr>
  <tr>
    <td>050</td>
    <td>
      <embed src="../assets/kits/050.svg" />
    </td>
  </tr>
  <tr>
    <td>051</td>
    <td>
      <embed src="../assets/kits/051.svg" />
    </td>
  </tr>
  <tr>
    <td>052</td>
    <td>
      <embed src="../assets/kits/052.svg" />
    </td>
  </tr>
  <tr>
    <td>053</td>
    <td>
      <embed src="../assets/kits/053.svg" />
    </td>
  </tr>
  <tr>
    <td>054</td>
    <td>
      <embed src="../assets/kits/054.svg" />
    </td>
  </tr>
  <tr>
    <td>055</td>
    <td>
      <embed src="../assets/kits/055.svg" />
    </td>
  </tr>  
  <tr>
    <td>056</td>
    <td>
      <embed src="../assets/kits/056.svg" />
    </td>
  </tr>
  <tr>
    <td>057</td>
    <td>
      <embed src="../assets/kits/057.svg" />
    </td>
  </tr>
  <tr>
    <td>058</td>
    <td>
      <embed src="../assets/kits/058.svg" />
    </td>
  </tr>
  <tr>
    <td>059</td>
    <td>
      <embed src="../assets/kits/059.svg" />
    </td>
  </tr>
  <tr>
    <td>060</td>
    <td>
      <embed src="../assets/kits/060.svg" />
    </td>
  </tr>
  <tr>
    <td>061</td>
    <td>
      <embed src="../assets/kits/061.svg" />
    </td>
  </tr>
  <tr>
    <td>062</td>
    <td>
      <embed src="../assets/kits/062.svg" />
    </td>
  </tr>
  <tr>
    <td>063</td>
    <td>
      <embed src="../assets/kits/063.svg" />
    </td>
  </tr>
  <tr>
    <td>064</td>
    <td>
      <embed src="../assets/kits/064.svg" />
    </td>
  </tr>
  <tr>
    <td>065</td>
    <td>
      <embed src="../assets/kits/065.svg" />
    </td>
  </tr>  
  <tr>
    <td>066</td>
    <td>
      <embed src="../assets/kits/066.svg" />
    </td>
  </tr>
  <tr>
    <td>067</td>
    <td>
      <embed src="../assets/kits/067.svg" />
    </td>
  </tr>
  <tr>
    <td>068</td>
    <td>
      <embed src="../assets/kits/068.svg" />
    </td>
  </tr>
</table>
</div>

<div class="table-container">
<table style="width:50px;">
  <tr>
    <th>Match</th>
    <th><center>Kits</center><embed src="../assets/kits/letters.svg" /></th>
  </tr>
  <tr>
    <td>069</td>
    <td>
      <embed src="../assets/kits/069.svg" />
    </td>
  </tr>
  <tr>
    <td>070</td>
    <td>
      <embed src="../assets/kits/070.svg" />
    </td>
  </tr>
    <tr>
    <td>071</td>
    <td>
      <embed src="../assets/kits/071.svg" />
    </td>
  </tr>
  <tr>
    <td>072</td>
    <td>
      <embed src="../assets/kits/072.svg" />
    </td>
  </tr>
  <tr>
    <td>073</td>
    <td>
      <embed src="../assets/kits/073.svg" />
    </td>
  </tr>
  <tr>
    <td>074</td>
    <td>
      <embed src="../assets/kits/074.svg" />
    </td>
  </tr>
  <tr>
    <td>075</td>
    <td>
      <embed src="../assets/kits/075.svg" />
    </td>
  </tr>  
  <tr>
    <td>076</td>
    <td>
      <embed src="../assets/kits/076.svg" />
    </td>
  </tr>
  <tr>
    <td>077</td>
    <td>
      <embed src="../assets/kits/077.svg" />
    </td>
  </tr>
  <tr>
    <td>078</td>
    <td>
      <embed src="../assets/kits/078.svg" />
    </td>
  </tr>
  <tr>
    <td>079</td>
    <td>
      <embed src="../assets/kits/079.svg" />
    </td>
  </tr>
  <tr>
    <td>080</td>
    <td>
      <embed src="../assets/kits/080.svg" />
    </td>
  </tr>
  <tr>
    <td>081</td>
    <td>
      <embed src="../assets/kits/081.svg" />
    </td>
  </tr>
  <tr>
    <td>082</td>
    <td>
      <embed src="../assets/kits/082.svg" />
    </td>
  </tr>
  <tr>
    <td>083</td>
    <td>
      <embed src="../assets/kits/083.svg" />
    </td>
  </tr>
  <tr>
    <td>084</td>
    <td>
      <embed src="../assets/kits/084.svg" />
    </td>
  </tr>
  <tr>
    <td>085</td>
    <td>
      <embed src="../assets/kits/085.svg" />
    </td>
  </tr>  
  <tr>
    <td>086</td>
    <td>
      <embed src="../assets/kits/086.svg" />
    </td>
  </tr>
  <tr>
    <td>087</td>
    <td>
      <embed src="../assets/kits/087.svg" />
    </td>
  </tr>
  <tr>
    <td>088</td>
    <td>
      <embed src="../assets/kits/088.svg" />
    </td>
  </tr>
  <tr>
    <td>089</td>
    <td>
      <embed src="../assets/kits/089.svg" />
    </td>
  </tr>
  <tr>
    <td>090</td>
    <td>
      <embed src="../assets/kits/090.svg" />
    </td>
  </tr>
  <tr>
    <td>091</td>
    <td>
      <embed src="../assets/kits/091.svg" />
    </td>
  </tr>
  <tr>
    <td>092</td>
    <td>
      <embed src="../assets/kits/092.svg" />
    </td>
  </tr>
  <tr>
    <td>093</td>
    <td>
      <embed src="../assets/kits/093.svg" />
    </td>
  </tr>
  <tr>
    <td>094</td>
    <td>
      <embed src="../assets/kits/094.svg" />
    </td>
  </tr>
  <tr>
    <td>095</td>
    <td>
      <embed src="../assets/kits/095.svg" />
    </td>
  </tr>  
  <tr>
    <td>096</td>
    <td>
      <embed src="../assets/kits/096.svg" />
    </td>
  </tr>
  <tr>
    <td>097</td>
    <td>
      <embed src="../assets/kits/097.svg" />
    </td>
  </tr>
  <tr>
    <td>098</td>
    <td>
      <embed src="../assets/kits/098.svg" />
    </td>
  </tr>
  <tr>
    <td>099</td>
    <td>
      <embed src="../assets/kits/099.svg" />
    </td>
  </tr>
  <tr>
    <td>100</td>
    <td>
      <embed src="../assets/kits/100.svg" />
    </td>
  </tr>      
</table>
</div>