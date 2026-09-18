---
layout: page
title: 'people'
permalink: /people/
active: People
---

<style>
 .page-content >.wrapper{
    margin-top: -30px;
  }
.people{
 width:100%;
 margin-bottom:15px;
 display:grid;
 grid-template-columns: 1fr 1fr;
 column-gap:5px;
 row-gap:15px;
}
 .person{
 width:100%;
 /* margin-bottom:10px; */ 
 display:flex;
 /* padding-right:5px; */
}
 .people_image{
  width:150px;
  min-width:150px;
  flex-shrink:0;
 }
 .people_content{
  flex:1;
 }
 .people_content_name{
  font-size:22px;
      /* margin-top: 15px; */
   margin-bottom:15px;

 }
 .people_content_text{
      margin-bottom: 10px;
 }

 @media screen and (max-width: 768px){
    .people{
        grid-template-columns: 1fr;
    }

    .person{
        width:100%;
    }

    .people_image{
        width:120px;
        flex-shrink:0;
    }
 }
 
</style>

<div class='people'>
   
 <div class='person'>
   <div class='people_image'>
    {% include image.html url="/images/JianghuiLi.png" align="left" %}
   </div>
   <div class='people_content'>
    <p class='people_content_name'>Jianghui Li</p>
    <p class='people_content_text'>PhD student in Biomedical Engineering @ Southeast University (2024-present, co-mentored with Dr. <a href='https://bme.seu.edu.cn/tj/main.htm' target='_blank'>Jing Tu</a> )</p>
    <p class='people_content_text'>Interests: Protein-RNA interactions</p>
   </div>
  </div>

  <div class='person'>
   <div class='people_image'>
    {% include image.html url="/images/JiafengWu.jpg" align="left" %}
   </div>
   <div class='people_content'>
    <p class='people_content_name'>Jiafeng Wu</p>
    <p class='people_content_text'>PhD student in Biomedical Engineering @ Southeast University (2026-present, co-mentored with Dr. <a href='https://bme.seu.edu.cn/tj/main.htm' target='_blank'>Jing Tu</a> )</p>
    <p class='people_content_text'>Interests: Protein-metal ion interactions and mutation pathogenecity</p>
   </div>
  </div>

  <div class='person'>
   <div class='people_image'>
    {% include image.html url="/images/XingyuWang.jpg" align="left" %}
   </div>
   <div class='people_content'>
    <p class='people_content_name'>Xingyu Wang</p>
    <p class='people_content_text'>MS student in Biomedical Engineering @ Southeast University (2026-present)</p>
    <p class='people_content_text'>Interests: Drug-drug interactions</p>
   </div>
  </div>
 
  <div class='person'>
   <div class='people_image'>
    {% include image.html url="/images/WeiTang.jpg" align="left" %}
   </div>
   <div class='people_content'>
    <p class='people_content_name'>Wei Tang</p>
    <p class='people_content_text'>MS student in Computer Science and Technology @ Xiangtan University (2024-present, co-mentored with Dr. <a href='https://jwxy.xtu.edu.cn/info/1147/2508.htm' target='_blank'>Kai Hu</a> )</p>
    <p class='people_content_text'>Interests: Mutaion impact on protein-protein interactions</p>
   </div>
  </div>

 <div class='person'>
   <div class='people_image'>
    {% include image.html url="/images/ZhijieJia.jpg" align="left" %}
   </div>
   <div class='people_content'>
    <p class='people_content_name'>Zhijie Jia</p>
    <p class='people_content_text'>MS student in Computer Science and Technology @ Xiangtan University (2025-present, co-mentored with Dr. <a href='https://jwxy.xtu.edu.cn/info/1147/2508.htm' target='_blank'>Kai Hu</a> )</p>
    <p class='people_content_text'>Interests: Protein-metal ion interactions</p>
   </div>
  </div>
   
  <div class='person'>
   <div class='people_image'>
    {% include image.html url="/images/ZeyuJin.jpg" align="left" %}
   </div>
   <div class='people_content'>
    <p class='people_content_name'>Zeyu Jin</p>
    <p class='people_content_text'>MS student in Computer Science and Technology @ Xiangtan University (2025-present, co-mentored with Dr. <a href='https://jwxy.xtu.edu.cn/info/1147/2508.htm' target='_blank'>Kai Hu</a> )</p>
    <p class='people_content_text'>Interests: Protein-small molecular binding affinity</p>
   </div>
  </div>
  
</div>
