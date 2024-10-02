---
layout: default
title: Data
subtitle: Player Classification Data
---

# Player Classification Data

We conduct our experiments using the [SoccerNet-V2 dataset](https://www.soccer-net.org/data). SoccerNet-V2 is currently the most extensive dataset of its type, comprising 500 soccer broadcast videos totaling over 750 hours. We maintain the same data splits as originally introduce SoccerNet-V2, consisting of 300 games for training, 100 for validation, and 100 for testing. 

We extend the annotations of the 100 test games in the dataset. Specifically, we manually segment and label approximately 80K people in the field aided by [PointRend](https://ai.meta.com/research/publications/pointrend-image-segmentation-as-rendering/) and [Segment Anything](https://segment-anything.com/). The annotated classes correspond to player, goalkeeper, referee, or other (e.g. technical staff in the field).

## Download

You can download the annotated test matches <a target="_blank" href="https://drive.google.com/file/d/1p8SzA92HBJ-02awAEYNbJb2ukL-0F9ND/view?usp=sharing">here</a>.

## Annotated Test Matches

The annotated playing kits of the test matches are the following:

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
<table style="width:470px;">
  <tr>
    <th>ID</th>
    <th>Match</th>
    <th><center>Kits</center><embed src="../assets/kits/letters.svg" /></th>
  </tr>
  <tr>
    <td>001</td>      
    <td>EN_15-05-17_MUN_1-1_ARS</td>
    <td>
      <embed src="../assets/kits/001.svg" />
    </td>
  </tr>
  <tr>
    <td>002</td>
    <td>EN_15-08-16_MCI_3-0_CHE</td>
    <td>
      <embed src="../assets/kits/002.svg" />
    </td>
  </tr>
  <tr>
    <td>003</td>
    <td>EN_15-08-23_WBA_2-3_CHE</td>
    <td>
      <embed src="../assets/kits/003.svg" />
    </td>
  </tr>
  <tr>
    <td>004</td>
    <td>EN_15-08-29_LIV_0-3_WHU</td>
    <td>
      <embed src="../assets/kits/004.svg" />
    </td>
  </tr>
  <tr>
    <td>005</td>
    <td>EN_15-09-20_SOU_2-3_MUN</td>
    <td>
      <embed src="../assets/kits/005.svg" />
    </td>
  </tr>
  <tr>
  	<td>006</td>
    <td>EN_15-09-26_NEW_2-2_CHE</td>
    <td>
      <embed src="../assets/kits/006.svg" />
    </td>
  </tr>
  <tr>
  	<td>007</td>
    <td>EN_15-10-03_CHE_1-3_SOU</td>
    <td>
      <embed src="../assets/kits/007.svg" />
    </td>
  </tr>
  <tr>
  	<td>008</td>
    <td>EN_15-10-24_WHU_2-1_CHE</td>
    <td>
      <embed src="../assets/kits/008.svg" />
    </td>
  </tr>
  <tr>
  	<td>009</td>
    <td>EN_15-11-07_STK_1-0_CHE</td>
    <td>
      <embed src="../assets/kits/009.svg" />
    </td>
  </tr>
  <tr>
  	<td>010</td>
    <td>EN_15-11-08_ARS_1-1_TOT</td>
    <td>
      <embed src="../assets/kits/010.svg" />
    </td>
  </tr>
  <tr>
  	<td>011</td>
    <td>EN_15-12-28_MUN_0-0_CHE</td>
    <td>
      <embed src="../assets/kits/011.svg" />
    </td>
  </tr>
  <tr>
  	<td>012</td>
    <td>EN_16-02-03_WAT_0-0_CHE</td>
    <td>
      <embed src="../assets/kits/012.svg" />
    </td>
  </tr>
  <tr>
  	<td>013</td>
    <td>EN_16-03-01_NOR_1-2_CHE</td>
    <td>
      <embed src="../assets/kits/013.svg" />
    </td>
  </tr>
  <tr>
  	<td>014</td>
    <td>EN_16-08-27_TOT_1-1_LIV</td>
    <td>
      <embed src="../assets/kits/014.svg" />
    </td>
  </tr>
  <tr>
  	<td>015</td>
    <td>EN_16-09-24_MUN_4-1_LEI</td>
    <td>
      <embed src="../assets/kits/015.svg" />
    </td>
  </tr>  
  <tr>
  	<td>016</td>
    <td>EN_16-10-15_CHE_3-0_LEI</td>
    <td>
      <embed src="../assets/kits/016.svg" />
    </td>
  </tr>
  <tr>
  	<td>017</td>
    <td>EN_17-01-21_LIV_2-3_SWA</td>
    <td>
      <embed src="../assets/kits/017.svg" />
    </td>
  </tr>
  <tr>
  	<td>018</td>
    <td>EN_17-05-06_LEI_3-0_WAT</td>
    <td>
      <embed src="../assets/kits/018.svg" />
    </td>
  </tr>
  <tr>
  	<td>019</td>
    <td>CL_14-11-04_ZEN_1-2_B04</td>
    <td>
      <embed src="../assets/kits/019.svg" />
    </td>
  </tr>
  <tr>
  	<td>020</td>
    <td>CL_15-02-24_MCI_1-2_BAR</td>
    <td>
      <embed src="../assets/kits/020.svg" />
    </td>
  </tr>
  <tr>
  	<td>021</td>
    <td>CL_15-03-10_RMD_3-4_S04</td>
    <td>
      <embed src="../assets/kits/021.svg" />
    </td>
  </tr>
  <tr>
  	<td>022</td>
    <td>CL_15-03-17_MON_0-2_ARS</td>
    <td>
      <embed src="../assets/kits/022.svg" />
    </td>
  </tr>
  <tr>
  	<td>023</td>
    <td>CL_15-04-15_FCP_3-1_BAY</td>
    <td>
      <embed src="../assets/kits/023.svg" />
    </td>
  </tr>
  <tr>
  	<td>024</td>
    <td>CL_15-04-22_RMD_1-0_ATM</td>
    <td>
      <embed src="../assets/kits/024.svg" />
    </td>
  </tr>
  <tr>
  	<td>025</td>
    <td>CL_15-05-05_JUV_2-1_RMD</td>
    <td>
      <embed src="../assets/kits/025.svg" />
    </td>
  </tr>  
  <tr>
  	<td>026</td>
    <td>CL_15-09-29_BAY_5-0_DIN</td>
    <td>
      <embed src="../assets/kits/026.svg" />
    </td>
  </tr>
  <tr>
  	<td>027</td>
    <td>CL_15-11-03_RMD_1-0_PSG</td>
    <td>
      <embed src="../assets/kits/027.svg" />
    </td>
  </tr>
  <tr>
  	<td>028</td>
    <td>CL_15-11-03_SEV_1-3_MCI</td>
    <td>
      <embed src="../assets/kits/028.svg" />
    </td>
  </tr>
  <tr>
  	<td>029</td>
    <td>CL_15-11-03_SHA_4-0_MFF</td>
    <td>
      <embed src="../assets/kits/029.svg" />
    </td>
  </tr>
  <tr>
  	<td>030</td>
    <td>CL_15-11-25_SHA_3-4_RMD</td>
    <td>
      <embed src="../assets/kits/030.svg" />
    </td>
  </tr>
  <tr>
  	<td>031</td>
    <td>CL_16-04-05_BAY_1-0_BEN</td>
    <td>
      <embed src="../assets/kits/031.svg" />
    </td>
  </tr>
  <tr>
  	<td>032</td>
    <td>CL_16-11-01_BES_1-1_NAP</td>
    <td>
      <embed src="../assets/kits/032.svg" />
    </td>
  </tr>
  <tr>
  	<td>033</td>
    <td>CL_16-11-01_MCI_3-1_BAR</td>
    <td>
      <embed src="../assets/kits/033.svg" />
    </td>
  </tr>
  <tr>
    <td>034</td>
    <td>CL_16-11-23_ARS_2-2_PSG</td>
    <td>
      <embed src="../assets/kits/034.svg" />
    </td>
  </tr>
  <tr>
    <td>035</td>
    <td>CL_17-03-08_BAR_6-1_PSG</td>
    <td>
      <embed src="../assets/kits/035.svg" />
    </td>
  </tr>  
  <tr>
    <td>036</td>
    <td>CL_17-04-12_BAY_1-2_RMD</td>
    <td>
      <embed src="../assets/kits/036.svg" />
    </td>
  </tr>
  <tr>
    <td>037</td>
    <td>CL_17-05-02_RMD_3-0_ATM</td>
    <td>
      <embed src="../assets/kits/037.svg" />
    </td>
  </tr>
  <tr>
    <td>038</td>
    <td>FR_16-08-28_MON_3-1_PSG</td>
    <td>
      <embed src="../assets/kits/038.svg" />
    </td>
  </tr>
  <tr>
    <td>039</td>
    <td>FR_16-11-30_PSG_2-0_ANG</td>
    <td>
      <embed src="../assets/kits/039.svg" />
    </td>
  </tr>
  <tr>
    <td>040</td>
    <td>GE_15-05-09_BAY_0-1_FCA</td>
    <td>
      <embed src="../assets/kits/040.svg" />
    </td>
  </tr>
  <tr>
    <td>041</td>
    <td>GE_15-08-29_BAY_3-0_B04</td>
    <td>
      <embed src="../assets/kits/041.svg" />
    </td>
  </tr>
  <tr>
    <td>042</td>
    <td>GE_15-09-12_BAY_2-1_FCA</td>
    <td>
      <embed src="../assets/kits/042.svg" />
    </td>
  </tr>
  <tr>
    <td>043</td>
    <td>GE_15-10-24_BAY_4-0_FCK</td>
    <td>
      <embed src="../assets/kits/043.svg" />
    </td>
  </tr>
  <tr>
    <td>044</td>
    <td>GE_15-11-08_BVB_3-2_S04</td>
    <td>
      <embed src="../assets/kits/044.svg" />
    </td>
  </tr>
  <tr>
    <td>045</td>
    <td>GE_16-09-10_RBL_1-0_BVB</td>
    <td>
      <embed src="../assets/kits/045.svg" />
    </td>
  </tr>  
  <tr>
    <td>046</td>
    <td>GE_16-10-01_B04_2-0_BVB</td>
    <td>
      <embed src="../assets/kits/046.svg" />
    </td>
  </tr>
  <tr>
    <td>047</td>
    <td>GE_16-11-05_HSV_2-5_BVB</td>
    <td>
      <embed src="../assets/kits/047.svg" />
    </td>
  </tr>
  <tr>
    <td>048</td>
    <td>GE_16-11-19_BVB_1-0_BAY</td>
    <td>
      <embed src="../assets/kits/048.svg" />
    </td>
  </tr>
  <tr>
    <td>049</td>
    <td>GE_16-12-16_HOF_2-2_BVB</td>
    <td>
      <embed src="../assets/kits/049.svg" />
    </td>
  </tr>
  <tr>
    <td>050</td>
    <td>GE_17-01-21_SVW_1-2_BVB</td>
    <td>
      <embed src="../assets/kits/050.svg" />
    </td>
  </tr>
</table>
</div>

<div class="table-container">
<table style="width:470px;">
  <tr>
    <th>ID</th>
    <th>Match</th>
    <th><center>Kits</center><embed src="../assets/kits/letters.svg" /></th>
  </tr>

  <tr>
    <td>051</td>
    <td>GE_17-01-29_M05_1-1_BVB</td>
    <td>
      <embed src="../assets/kits/051.svg" />
    </td>
  </tr>
  <tr>
    <td>052</td>
    <td>GE_17-03-04_BVB_6-2_B04</td>
    <td>
      <embed src="../assets/kits/052.svg" />
    </td>
  </tr>
  <tr>
    <td>053</td>
    <td>GE_17-04-29_BVB_0-0_FCK</td>
    <td>
      <embed src="../assets/kits/053.svg" />
    </td>
  </tr>
  <tr>
    <td>054</td>
    <td>IT_15-04-29_JUV_3-2_FIO</td>
    <td>
      <embed src="../assets/kits/054.svg" />
    </td>
  </tr>
  <tr>
    <td>055</td>
    <td>IT_15-08-29_ACM_2-1_EMP</td>
    <td>
      <embed src="../assets/kits/055.svg" />
    </td>
  </tr>  
  <tr>
    <td>056</td>
    <td>IT_15-09-20_GEN_0-2_JUV</td>
    <td>
      <embed src="../assets/kits/056.svg" />
    </td>
  </tr>
  <tr>
    <td>057</td>
    <td>IT_15-09-27_INT_1-4_FIO</td>
    <td>
      <embed src="../assets/kits/057.svg" />
    </td>
  </tr>
  <tr>
    <td>058</td>
    <td>IT_16-08-27_NAP_4-2_ACM</td>
    <td>
      <embed src="../assets/kits/058.svg" />
    </td>
  </tr>
  <tr>
    <td>059</td>
    <td>IT_16-09-11_ACM_0-1_UDI</td>
    <td>
      <embed src="../assets/kits/059.svg" />
    </td>
  </tr>
  <tr>
    <td>060</td>
    <td>IT_16-09-20_ACM_2-0_LAZ</td>
    <td>
      <embed src="../assets/kits/060.svg" />
    </td>
  </tr>
  <tr>
    <td>061</td>
    <td>IT_16-09-24_NAP_2-0_CHI</td>
    <td>
      <embed src="../assets/kits/061.svg" />
    </td>
  </tr>
  <tr>
    <td>062</td>
    <td>IT_16-09-25_TOR_3-1_ASR</td>
    <td>
      <embed src="../assets/kits/062.svg" />
    </td>
  </tr>
  <tr>
    <td>063</td>
    <td>IT_16-09-25_FIO_0-0_ACM</td>
    <td>
      <embed src="../assets/kits/063.svg" />
    </td>
  </tr>
  <tr>
    <td>064</td>
    <td>IT_16-10-02_ASR_2-1_INT</td>
    <td>
      <embed src="../assets/kits/064.svg" />
    </td>
  </tr>
  <tr>
    <td>065</td>
    <td>IT_16-11-20_ATA_2-1_ASR</td>
    <td>
      <embed src="../assets/kits/065.svg" />
    </td>
  </tr>  
  <tr>
    <td>066</td>
    <td>IT_16-11-26_EMP_1-4_ACM</td>
    <td>
      <embed src="../assets/kits/066.svg" />
    </td>
  </tr>
  <tr>
    <td>067</td>
    <td>IT_16-12-04_LAZ_0-2_ASR</td>
    <td>
      <embed src="../assets/kits/067.svg" />
    </td>
  </tr>
  <tr>
    <td>068</td>
    <td>IT_17-01-08_GEN_0-1_ASR</td>
    <td>
      <embed src="../assets/kits/068.svg" />
    </td>
  </tr>
  <tr>
    <td>069</td>
    <td>IT_17-01-29_SAM_3-2_ASR</td>
    <td>
      <embed src="../assets/kits/069.svg" />
    </td>
  </tr>
  <tr>
    <td>070</td>
    <td>IT_17-02-07_ASR_4-0_FIO</td>
    <td>
      <embed src="../assets/kits/070.svg" />
    </td>
  </tr>
    <tr>
    <td>071</td>
    <td>IT_17-02-25_NAP_0-2_ATA</td>
    <td>
      <embed src="../assets/kits/071.svg" />
    </td>
  </tr>
  <tr>
    <td>072</td>
    <td>IT_17-02-26_INT_1-3_ASR</td>
    <td>
      <embed src="../assets/kits/072.svg" />
    </td>
  </tr>
  <tr>
    <td>073</td>
    <td>IT_17-04-01_ASR_2-0_EMP</td>
    <td>
      <embed src="../assets/kits/073.svg" />
    </td>
  </tr>
  <tr>
    <td>074</td>
    <td>IT_17-04-30_INT_0-1_NAP</td>
    <td>
      <embed src="../assets/kits/074.svg" />
    </td>
  </tr>
  <tr>
    <td>075</td>
    <td>IT_17-05-20_NAP_4-1_FIO</td>
    <td>
      <embed src="../assets/kits/075.svg" />
    </td>
  </tr>  
  <tr>
    <td>076</td>
    <td>SP_15-02-14_RMD_2-0_DEP</td>
    <td>
      <embed src="../assets/kits/076.svg" />
    </td>
  </tr>
  <tr>
    <td>077</td>
    <td>SP_15-04-18_RMD_3-1_MAL</td>
    <td>
      <embed src="../assets/kits/077.svg" />
    </td>
  </tr>
  <tr>
    <td>078</td>
    <td>SP_15-04-25_ESP_0-2_BAR</td>
    <td>
      <embed src="../assets/kits/078.svg" />
    </td>
  </tr>
  <tr>
    <td>079</td>
    <td>SP_15-04-29_RMD_3-0_ALM</td>
    <td>
      <embed src="../assets/kits/079.svg" />
    </td>
  </tr>
  <tr>
    <td>080</td>
    <td>SP_15-05-02_COR_0-8_BAR</td>
    <td>
      <embed src="../assets/kits/080.svg" />
    </td>
  </tr>
  <tr>
    <td>081</td>
    <td>SP_15-05-09_BAR_2-0_RSO</td>
    <td>
      <embed src="../assets/kits/081.svg" />
    </td>
  </tr>
  <tr>
    <td>082</td>
    <td>SP_15-08-29_RMD_5-0_BET</td>
    <td>
      <embed src="../assets/kits/082.svg" />
    </td>
  </tr>
  <tr>
    <td>083</td>
    <td>SP_15-09-19_RMD_1-0_GCF</td>
    <td>
      <embed src="../assets/kits/083.svg" />
    </td>
  </tr>
  <tr>
    <td>084</td>
    <td>SP_15-11-08_BAR_3-0_VIL</td>
    <td>
      <embed src="../assets/kits/084.svg" />
    </td>
  </tr>
  <tr>
    <td>085</td>
    <td>SP_15-12-05_RMD_4-1_GET</td>
    <td>
      <embed src="../assets/kits/085.svg" />
    </td>
  </tr>  
  <tr>
    <td>086</td>
    <td>SP_15-12-30_RMD_3-1_RSO</td>
    <td>
      <embed src="../assets/kits/086.svg" />
    </td>
  </tr>
  <tr>
    <td>087</td>
    <td>SP_16-02-27_RMD_0-1_ATM</td>
    <td>
      <embed src="../assets/kits/087.svg" />
    </td>
  </tr>
  <tr>
    <td>088</td>
    <td>SP_16-03-02_LEV_1-3_RMD</td>
    <td>
      <embed src="../assets/kits/088.svg" />
    </td>
  </tr>
  <tr>
    <td>089</td>
    <td>SP_16-05-08_RMD_3-2_VAL</td>
    <td>
      <embed src="../assets/kits/089.svg" />
    </td>
  </tr>
  <tr>
    <td>090</td>
    <td>SP_16-05-14_DEP_0-2_RMD</td>
    <td>
      <embed src="../assets/kits/090.svg" />
    </td>
  </tr>
  <tr>
    <td>091</td>
    <td>SP_16-09-10_BAR_1-2_ALV</td>
    <td>
      <embed src="../assets/kits/091.svg" />
    </td>
  </tr>
  <tr>
    <td>092</td>
    <td>SP_16-09-21_RMD_1-1_VIL</td>
    <td>
      <embed src="../assets/kits/092.svg" />
    </td>
  </tr>
  <tr>
    <td>093</td>
    <td>SP_16-09-24_PAL_2-2_RMD</td>
    <td>
      <embed src="../assets/kits/093.svg" />
    </td>
  </tr>
  <tr>
    <td>094</td>
    <td>SP_16-11-26_RMD_2-1_GIJ</td>
    <td>
      <embed src="../assets/kits/094.svg" />
    </td>
  </tr>
  <tr>
    <td>095</td>
    <td>SP_16-12-18_BAR_4-1_ESP</td>
    <td>
      <embed src="../assets/kits/095.svg" />
    </td>
  </tr>  
  <tr>
    <td>096</td>
    <td>SP_17-02-11_OSA_1-3_RMD</td>
    <td>
      <embed src="../assets/kits/096.svg" />
    </td>
  </tr>
  <tr>
    <td>097</td>
    <td>SP_17-03-12_RMD_2-1_BET</td>
    <td>
      <embed src="../assets/kits/097.svg" />
    </td>
  </tr>
  <tr>
    <td>098</td>
    <td>SP_17-04-02_RMD_3-0_ALV</td>
    <td>
      <embed src="../assets/kits/098.svg" />
    </td>
  </tr>
  <tr>
    <td>099</td>
    <td>SP_17-04-08_MAL_2-0_BAR</td>
    <td>
      <embed src="../assets/kits/099.svg" />
    </td>
  </tr>
  <tr>
    <td>100</td>
    <td>SP_17-04-26_BAR_7-1_OSA</td>
    <td>
      <embed src="../assets/kits/100.svg" />
    </td>
  </tr>      
</table>
</div>
