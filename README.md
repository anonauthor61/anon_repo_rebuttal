# Results on real images
* We demonstrate the results of our approach for real images sampled from the Celeb-A dataset. Our encoder was only trained 
on generated data, we use the real data only for calibration. More details in Section 3.3.2 in the paper.
* In each example below, we show our results in two separate parts.
    1. We visualize the model prediction along with the quantiles for easy and hard cases. Here, the changes are visualized
    when we change all the semantic factors together. Order of display: `Ground truth | Corrupt Input | Prediction | Lower Q | Upper Q`
    2.  To really show the power of our approach, in this part we visualize the uncertainty intervals separately 
    by semantic factor. Order of display: `Lower Q | Upper Q`
* In both cases, we visualize the effect of calbration on the quantile edges by drawing a colored box representing calibration:
    1. ![#c5f015](https://via.placeholder.com/15/c5f015/c5f015.png) `Green box` around the image represents calibrated intervals. 
    2. ![#f03c15](https://via.placeholder.com/15/f03c15/f03c15.png) `Red box` around the image represents uncalibrated intervals.

> Each example below is a clickable / collapsed section that contains several gifs in nested blocks that can be visualized separately. Please click on the 
title of each bullet point to view the content inside.


<details><summary><b> Example 1: This image is illustrated in the main manuscript in Figure 4. </b></summary>
<blockquote>
  <details><summary>Easy / hard results</summary>
  <blockquote>
    
|                  |            | 
| ---              |     ---    |  
| Easy  |![](assets/change_gifs/1745/easy/all_attributes.gif)  
| Hard  |![](assets/change_gifs/1745/hard/all_attributes.gif)  
    
  </blockquote>
  </details>
  <details><summary>Uncertainty intervals per semantic factor</summary>
  <blockquote>
  <details><summary>Smile</summary>
  <blockquote>
    
|      Easy            |       Hard     | 
| ---              |     ---    |  
|![](assets/change_gifs/1745/easy/Mouth_Smile.gif) |![](assets/change_gifs/1745/hard/Mouth_Smile.gif) 
    
  </blockquote>
  </details>
  <details><summary>Glasses</summary>
  <blockquote>
    
|      Easy            |       Hard     | 
| ---              |     ---    |  
|![](assets/change_gifs/1745/easy/Eye_Glasses.gif) |![](assets/change_gifs/1745/hard/Eye_Glasses.gif) 
    
  </blockquote>
  </details>
  <details><summary>Hair</summary>
  <blockquote>
    
|      Easy            |       Hard     | 
| ---              |     ---    |  
|![](assets/change_gifs/1745/easy/all_hair.gif) |![](assets/change_gifs/1745/hard/all_hair.gif) 
    
  </blockquote>
  </details>
    
  </blockquote>
  </details>
</blockquote>
</details>


<details><summary><b> Example 2 </b></summary>
<blockquote>
  <details><summary>Easy / hard results</summary>
  <blockquote>
    
|                  |            | 
| ---              |     ---    |  
| Easy  |![](assets/change_gifs/1849/easy/all_attributes.gif)  
| Hard  |![](assets/change_gifs/1849/hard/all_attributes.gif)  
    
  </blockquote>
  </details>
  <details><summary>Uncertainty intervals per semantic factor</summary>
  <blockquote>
  <details><summary>Perceived gender</summary>
  <blockquote>
    
|      Easy            |       Hard     | 
| ---              |     ---    |  
|![](assets/change_gifs/1849/easy/Gender.gif) |![](assets/change_gifs/1849/hard/Gender.gif) 
    
  </blockquote>
  </details>
  <details><summary>Glasses</summary>
  <blockquote>
    
|      Easy            |       Hard     | 
| ---              |     ---    |  
|![](assets/change_gifs/1849/easy/Eye_Glasses.gif) |![](assets/change_gifs/1849/hard/Eye_Glasses.gif) 
    
  </blockquote>
  </details>
  <details><summary>Hair</summary>
  <blockquote>
    
|      Easy            |       Hard     | 
| ---              |     ---    |  
|![](assets/change_gifs/1849/easy/all_hair.gif) |![](assets/change_gifs/1849/hard/all_hair.gif) 
    
  </blockquote>
  </details>
    
  </blockquote>
  </details>
</blockquote>
</details>

<details><summary><b> Example 3 </b></summary>
<blockquote>
  <details><summary>Easy / hard results</summary>
  <blockquote>
    
|                  |            | 
| ---              |     ---    |  
| Easy  |![](assets/change_gifs/2235/easy/all_attributes.gif)  
| Hard  |![](assets/change_gifs/2235/hard/all_attributes.gif)  
    
  </blockquote>
  </details>
  <details><summary>Uncertainty intervals per semantic factor</summary>
  <blockquote>
  <details><summary>Perceived Gender</summary>
  <blockquote>
    
|      Easy            |       Hard     | 
| ---              |     ---    |  
|![](assets/change_gifs/2235/easy/Gender.gif) |![](assets/change_gifs/2235/hard/Gender.gif) 
    
  </blockquote>
  </details>
  <details><summary>Hair</summary>
  <blockquote>
    
|      Easy            |       Hard     | 
| ---              |     ---    |  
|![](assets/change_gifs/2235/easy/all_hair.gif) |![](assets/change_gifs/2235/hard/all_hair.gif) 
    
  </blockquote>
  </details>
  <details><summary>Expression</summary>
  <blockquote>
    
|      Easy            |       Hard     | 
| ---              |     ---    |  
|![](assets/change_gifs/2235/easy/Mouth_Smile.gif) |![](assets/change_gifs/2235/hard/Mouth_Smile.gif) 
    
  </blockquote>
  </details>
    
  </blockquote>
  </details>
</blockquote>
</details>

<details><summary><b> Example 4 </b></summary>
<blockquote>
  <details><summary>Easy / hard results</summary>
  <blockquote>
    
|                  |            | 
| ---              |     ---    |  
| Easy  |![](assets/change_gifs/2269/easy/all_attributes.gif)  
| Hard  |![](assets/change_gifs/2269/hard/all_attributes.gif)  
    
  </blockquote>
  </details>
  <details><summary>Uncertainty intervals per semantic factor</summary>
  <blockquote>
  <details><summary>Hair</summary>
  <blockquote>
    
|      Easy            |       Hard     | 
| ---              |     ---    |  
|![](assets/change_gifs/2269/easy/all_hair.gif) |![](assets/change_gifs/2269/hard/all_hair.gif) 
    
  </blockquote>
  </details>
  <details><summary>Glasses</summary>
  <blockquote>
    
|      Easy            |       Hard     | 
| ---              |     ---    |  
|![](assets/change_gifs/2269/easy/Eye_Glasses.gif) |![](assets/change_gifs/2269/hard/Eye_Glasses.gif) 
    
  </blockquote>
  </details>
  <details><summary>Perceived Gender</summary>
  <blockquote>
    
|      Easy            |       Hard     | 
| ---              |     ---    |  
|![](assets/change_gifs/2269/easy/Gender.gif) |![](assets/change_gifs/2269/hard/Gender.gif) 
    
  </blockquote>
  </details>
    
  </blockquote>
  </details>
</blockquote>
</details>




