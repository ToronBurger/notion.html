<div class="tradingview-widget-container">
  <div id="technical-analysis-chart-demo"></div>
  <div class="tradingview-widget-copyright"><a href="https://tw.tradingview.com/" rel="noopener nofollow" target="_blank"><span class="blue-text">追蹤TradingView上的所有市場</span></a></div>
  <script type="text/javascript" src="https://s3.tradingview.com/tv.js"></script>
  <script type="text/javascript">
  new TradingView.widget(
  {
  "container_id": "technical-analysis-chart-demo",
  "width": "100%",
  "height": "100%",
  "autosize": true,
  "symbol": "AAPL",
  "interval": "D",
  "timezone": "exchange",
  "theme": "light",
  "style": "1",
  "withdateranges": true,
  "hide_side_toolbar": false,
  "allow_symbol_change": true,
  "save_image": false,
  "studies": [
    "ROC@tv-basicstudies",
    "StochasticRSI@tv-basicstudies",
    "MASimple@tv-basicstudies"
  ],
  "show_popup_button": true,
  "popup_width": "1000",
  "popup_height": "650",
  "locale": "zh_TW"
}
  );
  </script>
</div>
