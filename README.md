# Effects-of-COVID-19-Precautions-on-Traffic-Accidents-Taoyuan

  本專案感興趣的問題是中央政府應對新冠疫情實施二級警戒對於桃園市交通事故發生的外部效果為何？其交通事故肇事原因與駕駛人年齡、性別、是否酒駕等分布是否造成與以往不同之趨勢？在觀察跨期的事故發生資料時，二級警戒實施與否的資料樣本特徵會有明顯的不同，對於應變項的影響也會不一樣。對於這些變數篩選問題，模型採用斷點迴歸設計（Regression Discontinuity）測量二級警戒對於交通事故發生的影響。此外，不方便觀察的控制變數或中介變數，例如每天的車流量、尖峰離峰的時間等，則加入時間固定效果處理（Adding Time Fixed Effect with PanelOLS）。實證結果顯示，疫情警戒確實使交通事故大幅下降、超速案件比重亦確實上升，惟死亡案件比重未有顯著差異。

### Code and Visualization
- [資料蒐集(Retrieving Data)](01_Get_Data.ipynb)
- [斷點回歸建模(Regression Discontinuity Design)](02_RD_Model.ipynb)
- [分析輸出(Creating Classes and Objects for the Statistical Analysis)](03_Empirical.ipynb)
- [海報(Presentation Poster)](poster.pdf)
- [視覺化(Visualization Results)](plot_result)
- [書面報告(Paper Report)](report_paper.pdf)
- [使用資料(Raw Data)](data)
- [參考資料(Reference)](reference)
