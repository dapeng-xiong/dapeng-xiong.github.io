---
layout: default
title: 'news'
---
<style>
.index_news{
	    width: 100%;
	min-height: 20px;
    margin-bottom: 20px;
    /* background-color: #fafafa;
    border-radius: 4px;
    border: 1px solid #e7e7e7;
    -webkit-box-shadow: inset 0 2px 0 rgba(0, 0, 0, 0.05);
    box-shadow: inset 0 2px 0 rgba(0, 0, 0, 0.05); */
}

.index_news_header{
	margin-bottom: 10px;
	font-size: 22px;
	font-weight: bold;
	    /* font-weight: 400; */
	/* color: #333;
    background-color: #f5f5f5;
    border-color: #ddd;
    padding: 10px 15px;
    border-bottom: 1px solid transparent;
    border-top-left-radius: 3px;
    border-top-right-radius: 3px; */
}
	.index_news_content_c{
		    padding-bottom: 15px;
	}
	.index_news_content_c_date{
		    /* font-size: 20px;
    		padding: 5px 0 5px 0; */
	}

	.index_news_content_c_news{
		    /* font-size: 20px;
    		padding: 5px 0 5px 0; */
	}
	
/* .index_news>h4{
	margin-top: 15px;
    padding-left: 15px;
    text-align: left;
} */
</style>

<div style='width:100%;display:flex;'>
	
<div class="index_news" >
	<div class='index_news_header'> News </div>
	
	<div class='index_news_content'>
		{% for news in site.data.news %}
	    <div class='index_news_content_c'>
	        <div class='index_news_content_c_date'>{{ news.date }}</div>
	        <div class='index_news_content_c_news'>
	            {{ news.content }}
	        </div>
	    </div>
	    {% endfor %}
		
	</div>	
</div>

</div>
