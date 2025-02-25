---
title: 2022 11~12 月份閱讀
description: 📚 Storytelling with Data | The 5 Love Languages Singles Edition
date: 2022-12-31
slug: 
image: read_2.jpg
categories:
    - reading
tags:
    - books
    - data science
---

## Storytelling with Data
作者部落格：[storytellingwithdata.com](https://www.storytellingwithdata.com/)

這本幾乎是 data scientist 人手一本的案頭書，內容十分精鍊且容易應用。在研究所時期，我的指導老師就耳提面命要我們避開圓餅圖，本書作者也指出圓餅圖和立體圖是最要避免的資料呈現方式。原以為我的視覺化能力大約有中上程度，總是恪守文字對齊、色彩統一，還有在折線圖尾端加上資料標籤。但閱讀本書後，發現自己還是在不經意間製作了許多爛圖表，舉例如下：

1. 呈現資料時要用「解釋型分析」  
這應該是我在工作時犯的第一個錯誤。為了報告做了許多探索型分析，因此想將全部的結果都塞給觀眾，證明自己的用心，卻使得重點失焦。作者把探索型分析比喻成「一百顆牡蠣」，解釋型分析比喻成「兩顆珍珠」。報告時應該呈現去蕪存菁的珍珠，避免拖著觀眾陪你一起扒開一百顆牡蠣。

2. 投影片標題位置寫上結論  
剛開始做投影片時，老闆提醒我要在投影片的標題位置加上圖表的結論。我原先有些不解，因為研究所時做的投影片標題都是寫 Introduction, Methods, Conclusion 之類的字眼。作者提到觀眾在看投影片時，是以「之」字型方向由左上至右下瀏覽，如果能先看到結論再搭配圖表，可以大幅提升溝通效率。

3. 堆疊長條圖 (Stacked bar chart) 避免太多顏色  
之前在做不同類別變項的比較時，畫了一張堆疊長條圖，但是因為種類繁多，整張圖大概有五六種顏色，直接被老闆說太花了。作者在書中提出解方，以下圖左方為例，顏色花花綠綠包含太多雜訊，沒辦法一眼看到重點。此時應思考我們要引導觀眾注意哪裡，並且只在該處使用色彩，其餘部分則以灰階呈現，如下圖右方所示。

![堆疊長條圖修正方式 (Knaflic, 2015)](stacked_bar_chart.png "Stacked bar chart") 

4. 折線圖 (Line chart) 不要變成麵條圖  
所謂麵條圖，就是像麵條一樣堆疊在一起的折線圖。之前在呈現不同時段的物料量趨勢時，畫出了一張麵條圖，導致報告時需要更多時間解釋。圖片中許多雜亂的線條，讓重點難以呈現。作者提出了幾種解決方式，包括以顏色強調重點線條，或將各折線以空間分開呈現等。下圖呈現書中強調線條的範例，與堆疊長條圖的修正方式類似，都是減少雜訊讓重點突出，以達到資料溝通的效率。

![麵條圖修正方式 (Knaflic, 2015)](line_chart.png "Line chart") 

作者強調如何藉由人類視覺的特性，掌握觀眾的注意力，包括將[格式塔視覺法則](https://uiclub.tw/2015/09/05/visual-principles-gestalt-principles/)以及[前注意特徵](http://daydreamingnumbers.com/blog/preattentive-attributes-example/)運用在圖表製作中。除了視覺呈現外，如何用資料說出好故事也十分重要。作者借用了文學及戲劇中的敘事結構 [setup-conflict-resolution](https://towardsdatascience.com/how-to-build-a-narrative-from-data-85e327940c13) 來解釋如何描述資料故事。除了按照時間順序，也可以用結尾開頭，直接開門見山說明結論與解決行動。

> 題外話：讀到這一段時，我剛好接受了台大新聞所助理的訪問，有一題是跨域求職者的優勢。我想對於外文背景的人來說，storytelling 是個可以大放異采的舞台。

## The 5 Love Languages Singles Edition

本書的前身 The 5 Love Languages 主要是寫給已婚夫婦，但有許多單身者也想知道愛之語 (Love Languages) 該如何應用在婚姻以外的日常生活中，促使作者寫了這本書。作者所提出的五種愛的語言分別是：

1. 肯定的言語 (Words of Affirmation)：例如稱讚、鼓勵或感謝。

1. 服務的行動 (Acts of Service)：例如幫對方跑腿、分擔工作或家事等。

1. 真心的禮物 (Gifts)：根據對方的需要和喜好準備禮物，價格並非重點。

1. 精心的時刻 (Quality Time)：雙方一起從事活動，並給予對方完整的注意力。

1. 身體的接觸 (Physical Touch)：牽手、擊掌或擁抱等表達親密感的身體接觸。

除了浪漫關係外，這五項愛之語也適用於職場、友情、親情等任何需要與人互動的場合。作者指出每個人都有主要的愛之語，只要最主要的部分被滿足了，就能感受到愛。先滿足對方的主要愛之語，再適度加入其他項，可以提升關係的滿意度。反之若沒有接收到主要的愛之語，則不會感受到愛。例如：小明的主要愛之語是「精心的時刻」，但他的爸媽因工作繁忙無法陪伴而以物質滿足孩子。小明就算收到許多禮物，心靈依然無法得到滿足。

想判斷自己的主要愛之語，可以思考自己最常表示愛的方式為何。例如：如果你經常以「服務的行動」來表示愛，你的主要愛之語很有可能也是服務的行動。想要怎麼被對待，就會以同樣的方式對待別人。如果不容易判斷，作者也設計了[愛之語測驗](https://5lovelanguages.com/quizzes/love-language)，讓我們探索自己的主要愛之語，如此一來就能與重要他人溝通自己的需要。這些題目也可以幫助我們判斷重要他人的主要愛之語，讓關係更加融洽。

雖然書中並未提到，但我認為面對不同的對象，主要愛之語也會有所變化。例如，面對父母，「肯定的言語」最能讓我感覺被愛，但面對朋友，「服務的行動」重要性則排到第一。愛之語應該不是固定的，會根據相處的人調整不同的優先順序。

Photo by <a href="https://unsplash.com/@rumandraisin?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Lilly Rum</a> on <a href="https://unsplash.com/photos/iyKVGRu79G4?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>