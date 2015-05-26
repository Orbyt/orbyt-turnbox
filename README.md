This is Turnbox (http://noht.co.jp/turnbox ) repackaged for [Meteor](meteor.com). To add this to your project, simply type `meteor add orbyt:turnbox` in your console and hit enter. 

Example use:
```
<div class="sample">
      <div class="turnBoxButton"></div>
      <div class="turnBoxButton"><p>hello</p></div>
      <div class="turnBoxButton"></div>
      <div class="turnBoxButton"></div>
</div>
```

Initiate with `$(".sample").turnBox();`

I have added the ability to define the dimensions of your item via percentages. To do this, initiate the box like: `$(".sample").turnBox({width: 50, percentage: true});`. By default, `percentage` is false, so the element needs to be inside another element that has a height, for a height percentage to be used. An example of setting height: `$(".sample").turnBox({width: 50, height: 75, percentage: true});`.

Full insctructions for use can be found at the main site.
