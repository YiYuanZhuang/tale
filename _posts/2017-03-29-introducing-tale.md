---
layout: post
title:  " Policing Smarter, Not Harder "
author: "YiYuan, JiaNan, lingYu"
comments: true
tags: Tale
excerpt_separator: <!--more-->
sticky: true
hidden: true
---

Welcome to our webpage about the San Francisco Crime Dataset, where we delve into interesting criminal activity patterns in San Francisco, with a focus on the distribution of theft related crimes over the five-year period from 2013 to 2017. Through a detailed analysis of existing crime data, the aim is to elucidate the general trend of theft and provide thoughtful recommendations.<!--more-->

## Around the Clock Caution: Understanding SF's Theft Cycle
A comprehensive investigation in San Francisco found that the incidence of theft is shocking, affecting more than half of the city's residents. These incidents involve an astonishing number of blatant car intrusions, often occurring in areas popular with tourists. This unsettling reality resonates deeply with the widespread civic disillusionment in this city. [1] To improve this situation, we first analyzed the distribution of theft in SF during a 24-hour cycle.

<figure>
    <img src="/assets/image/time-plot.png" width=650 height=500>
    <figcaption>Figure 1: Visualisation of the 24-hour cycle of thelft crimes in San Francisco using a polar chart.</figcaption>
</figure>

The data represented by the polar bar chart shows a sharp increase in theft/theft cases around 6 pm, indicating that theft is more frequent when people may be returning home from work or there is still a lot of pedestrian traffic. On the contrary, the incidence rate is lowest in the early morning around 5am, and gradually increases to the evening peak after noon.

For the entire community, as theft/theft incidents peak in the evening, individuals should be particularly vigilant when going out at dusk, especially in areas known to be crowded or with high pedestrian traffic. It is important to be more careful in protecting personal belongings and raising awareness of the surrounding environment. Consider scheduling errands at lower risk times (such as in the morning) to reduce the chances of becoming a victim of theft.

Law enforcement agencies can better protect these peak hours by allocating additional resources and patrols to prevent theft. In addition, community outreach activities can play a crucial role in educating the public to protect themselves from theft. Strategically deploying monitoring infrastructure in key areas, especially those with high incidence during peak hours, can serve both as a deterrent and an investigative role.

## Browser Support
Tale works on most if not all modern browsers, including Chrome, Safari and Firefox 👍🏼
<iframe src="/assets/image/map.html" style="width: 100%; height: 600px; border: none;"></iframe>

<iframe src="/assets/image/type.html" style="width: 100%; height: 600px; border: none;"></iframe>

## Download or Contribute

Tale is publicly hosted on GitHub, so go ahead and download or fork it at the [GitHub repository](https://github.com/chesterhow/tale). If you spot any bugs or have any suggestions, feel free to create an issue or make a pull request.

Thanks for checking out Tale!

<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>Bokeh Plot</title>
    <script type="text/javascript" src="https://cdn.bokeh.org/bokeh/release/bokeh-2.4.3.min.js"></script>
    <script type="text/javascript">
        Bokeh.set_log_level("info");
    </script>
  </head>
  <body>
    <div class="bk-root" id="c735d63c-cfa8-481f-96d2-6fdc7d0ff7e9" data-root-id="1261"></div>
  
    <script type="application/json" id="1451">
      {"fe4dfd6f-4159-46f8-b714-d97eb4c4fc54":{"defs":[],"roots":{"references":[{"attributes":{"axis":{"id":"1274"},"coordinates":null,"dimension":1,"group":null,"ticker":null},"id":"1277","type":"Grid"},{"attributes":{"source":{"id":"1259"}},"id":"1297","type":"CDSView"},{"attributes":{"label":{"value":"OTHERS"},"renderers":[{"id":"1308"}]},"id":"1319","type":"LegendItem"},{"attributes":{},"id":"1267","type":"CategoricalScale"},{"attributes":{"fill_alpha":{"value":0.1},"fill_color":{"value":"#1f77b4"},"hatch_alpha":{"value":0.1},"hatch_color":{"value":"#1f77b4"},"line_alpha":{"value":0.1},"line_color":{"value":"#1f77b4"},"top":{"field":"ATTEMPTED"},"width":{"value":0.8},"x":{"field":"Hour"}},"id":"1295","type":"VBar"},{"attributes":{},"id":"1278","type":"PanTool"},{"attributes":{"fill_alpha":{"value":0.1},"fill_color":{"value":"#1f77b4"},"hatch_alpha":{"value":0.1},"hatch_color":{"value":"#1f77b4"},"line_alpha":{"value":0.1},"line_color":{"value":"#1f77b4"},"top":{"field":"ATTEMPTED"},"width":{"value":0.8},"x":{"field":"Hour"}},"id":"1294","type":"VBar"},{"attributes":{"axis_label":"Normalized LARCENY/THEFT type Count","coordinates":null,"formatter":{"id":"1323"},"group":null,"major_label_policy":{"id":"1324"},"ticker":{"id":"1275"}},"id":"1274","type":"LinearAxis"},{"attributes":{"click_policy":"mute","coordinates":null,"group":null,"items":[{"id":"1317"},{"id":"1318"},{"id":"1319"},{"id":"1320"}],"location":[0,0]},"id":"1316","type":"Legend"},{"attributes":{"overlay":{"id":"1284"}},"id":"1280","type":"BoxZoomTool"},{"attributes":{"coordinates":null,"data_source":{"id":"1259"},"glyph":{"id":"1293"},"group":null,"hover_glyph":null,"muted":true,"muted_glyph":{"id":"1295"},"nonselection_glyph":{"id":"1294"},"view":{"id":"1297"}},"id":"1296","type":"GlyphRenderer"},{"attributes":{"axis_label":"Hour of Day","coordinates":null,"formatter":{"id":"1326"},"group":null,"major_label_policy":{"id":"1327"},"ticker":{"id":"1272"}},"id":"1271","type":"CategoricalAxis"},{"attributes":{"label":{"value":"PETTY_THEFT"},"renderers":[{"id":"1314"}]},"id":"1320","type":"LegendItem"},{"attributes":{"bottom_units":"screen","coordinates":null,"fill_alpha":0.5,"fill_color":"lightgrey","group":null,"left_units":"screen","level":"overlay","line_alpha":1.0,"line_color":"black","line_dash":[4,4],"line_width":2,"right_units":"screen","syncable":false,"top_units":"screen"},"id":"1284","type":"BoxAnnotation"},{"attributes":{"axis":{"id":"1271"},"coordinates":null,"group":null,"ticker":null},"id":"1273","type":"Grid"},{"attributes":{},"id":"1265","type":"DataRange1d"},{"attributes":{"below":[{"id":"1271"}],"center":[{"id":"1273"},{"id":"1277"}],"height":400,"left":[{"id":"1274"}],"renderers":[{"id":"1296"},{"id":"1302"},{"id":"1308"},{"id":"1314"}],"right":[{"id":"1316"}],"title":{"id":"1262"},"toolbar":{"id":"1285"},"width":1000,"x_range":{"id":"1260"},"x_scale":{"id":"1267"},"y_range":{"id":"1265"},"y_scale":{"id":"1269"}},"id":"1261","subtype":"Figure","type":"Plot"},{"attributes":{"fill_color":{"value":"#aec7e8"},"hatch_color":{"value":"#aec7e8"},"line_color":{"value":"#aec7e8"},"top":{"field":"GRAND_THEFT"},"width":{"value":0.8},"x":{"field":"Hour"}},"id":"1299","type":"VBar"},{"attributes":{},"id":"1272","type":"CategoricalTicker"},{"attributes":{"fill_alpha":{"value":0.1},"fill_color":{"value":"#aec7e8"},"hatch_alpha":{"value":0.1},"hatch_color":{"value":"#aec7e8"},"line_alpha":{"value":0.1},"line_color":{"value":"#aec7e8"},"top":{"field":"GRAND_THEFT"},"width":{"value":0.8},"x":{"field":"Hour"}},"id":"1300","type":"VBar"},{"attributes":{},"id":"1275","type":"BasicTicker"},{"attributes":{"coordinates":null,"group":null,"text":"Normalized LARCENY/THEFT type by Hour"},"id":"1262","type":"Title"},{"attributes":{},"id":"1279","type":"WheelZoomTool"},{"attributes":{},"id":"1282","type":"ResetTool"},{"attributes":{},"id":"1327","type":"AllLabels"},{"attributes":{"fill_alpha":{"value":0.1},"fill_color":{"value":"#ff7f0e"},"hatch_alpha":{"value":0.1},"hatch_color":{"value":"#ff7f0e"},"line_alpha":{"value":0.1},"line_color":{"value":"#ff7f0e"},"top":{"field":"OTHERS"},"width":{"value":0.8},"x":{"field":"Hour"}},"id":"1306","type":"VBar"},{"attributes":{"tools":[{"id":"1278"},{"id":"1279"},{"id":"1280"},{"id":"1281"},{"id":"1282"},{"id":"1283"}]},"id":"1285","type":"Toolbar"},{"attributes":{"data":{"ATTEMPTED":{"__ndarray__":"8qo1QCgwnj+uL8Kj0TqdP6EcedUaIJQ/RNqyI8aalD/ml+xxcRWVP12hBTnEKpM/dmhYTsK6kT8LcohVJsCMP9nj4ioqoJ8/dmhYTsK6oT+748vqGLCiP/zxfLUdSKY/sZyEdSOYqj/ml+xxcRWlP2+O06oeAKc/U1q+w84Sqz+aXHOFFuSwPybAHJAVLLA/t3YJGcdStT+BlSBwGFSyP2AOyAoWiLA/C3KIVSbArD/gvWfOzVqqP9A9XC7F4qM/","dtype":"float64","order":"little","shape":[24]},"GRAND_THEFT":{"__ndarray__":"wMg95IKjoj/QCrMImtKYPxk2Sh7rz48/pb2++wKhhD+TfdmvoY55P04jaIETcXo/hbgCDoh0hD8K8tbAXLeMP805VnF2DJg/TCUvCip0nj+LMdzO95ykPxKUx58EKqc/qmE/s2Awqj9ekPL82dOnPxve/feXGKg/gmYLgnjGqD+7Tq7W9h+rP86NSzb9o7A/GYu+fy3ctj/lcvklF9S2P9Tx2RnzbLQ/MtorrgN4sD+4UfT7yJetP0PasMU796c/","dtype":"float64","order":"little","shape":[24]},"Hour":[0,1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21,22,23],"OTHERS":{"__ndarray__":"vQsr89CotT9LEkNLadeVPwl1AgkheZE/+ONDTnSqiz/TWqKov76AP51AQkheBIA/SxJDS2nXhT/f3YKKpmKUP23kmuI+kaQ/AKlrNRkHqj+UdKt0VpKoPxX44uoHHaU/Cc3vGV8Huz/PTMTP+ZOuP6i8sz3ikqo/rXpsOCTarz9gYboAWO2wP8PJ4+0S8Ko/Lv6jrtVkrD+BLKOrypGmP1LXajIONKQ/WZySGbOQoj9gYboAWO2gP+pZ9H8q8Z4/","dtype":"float64","order":"little","shape":[24]},"PETTY_THEFT":{"__ndarray__":"8nnc8Z+Ooj8drrMk1n6aP+UuGMmXZY0/PBJXvGJ4gz+RtWQHJ6F7P9noJWM+3n0/XLUBomwIhj98kwttzuCQPxYmAQN+Dpw/mleWsFfloj8/Q9e8dyWoP4pVuLoP7qo/iGM/CHjXrz8O/OHYDwKuPzmoy4oIKq8/SSK8/xJZsD+j0uve0L+wP/a9tQLMxrE/+3v1Rs3dsj/iiS2y5c6wPw2/Lj+lEq0/KRysX3DDpz+GJDi6+kCmP15XbqqCpKU/","dtype":"float64","order":"little","shape":[24]}},"selected":{"id":"1329"},"selection_policy":{"id":"1328"}},"id":"1259","type":"ColumnDataSource"},{"attributes":{"source":{"id":"1259"}},"id":"1309","type":"CDSView"},{"attributes":{"fill_color":{"value":"#ff7f0e"},"hatch_color":{"value":"#ff7f0e"},"line_color":{"value":"#ff7f0e"},"top":{"field":"OTHERS"},"width":{"value":0.8},"x":{"field":"Hour"}},"id":"1305","type":"VBar"},{"attributes":{"fill_alpha":{"value":0.1},"fill_color":{"value":"#ff7f0e"},"hatch_alpha":{"value":0.1},"hatch_color":{"value":"#ff7f0e"},"line_alpha":{"value":0.1},"line_color":{"value":"#ff7f0e"},"top":{"field":"OTHERS"},"width":{"value":0.8},"x":{"field":"Hour"}},"id":"1307","type":"VBar"},{"attributes":{},"id":"1269","type":"LinearScale"},{"attributes":{"coordinates":null,"data_source":{"id":"1259"},"glyph":{"id":"1299"},"group":null,"hover_glyph":null,"muted":true,"muted_glyph":{"id":"1301"},"nonselection_glyph":{"id":"1300"},"view":{"id":"1303"}},"id":"1302","type":"GlyphRenderer"},{"attributes":{},"id":"1283","type":"HelpTool"},{"attributes":{},"id":"1323","type":"BasicTickFormatter"},{"attributes":{},"id":"1326","type":"CategoricalTickFormatter"},{"attributes":{"label":{"value":"ATTEMPTED"},"renderers":[{"id":"1296"}]},"id":"1317","type":"LegendItem"},{"attributes":{"fill_alpha":{"value":0.1},"fill_color":{"value":"#ffbb78"},"hatch_alpha":{"value":0.1},"hatch_color":{"value":"#ffbb78"},"line_alpha":{"value":0.1},"line_color":{"value":"#ffbb78"},"top":{"field":"PETTY_THEFT"},"width":{"value":0.8},"x":{"field":"Hour"}},"id":"1313","type":"VBar"},{"attributes":{},"id":"1328","type":"UnionRenderers"},{"attributes":{"coordinates":null,"data_source":{"id":"1259"},"glyph":{"id":"1311"},"group":null,"hover_glyph":null,"muted":true,"muted_glyph":{"id":"1313"},"nonselection_glyph":{"id":"1312"},"view":{"id":"1315"}},"id":"1314","type":"GlyphRenderer"},{"attributes":{"coordinates":null,"data_source":{"id":"1259"},"glyph":{"id":"1305"},"group":null,"hover_glyph":null,"muted":true,"muted_glyph":{"id":"1307"},"nonselection_glyph":{"id":"1306"},"view":{"id":"1309"}},"id":"1308","type":"GlyphRenderer"},{"attributes":{"fill_alpha":{"value":0.1},"fill_color":{"value":"#ffbb78"},"hatch_alpha":{"value":0.1},"hatch_color":{"value":"#ffbb78"},"line_alpha":{"value":0.1},"line_color":{"value":"#ffbb78"},"top":{"field":"PETTY_THEFT"},"width":{"value":0.8},"x":{"field":"Hour"}},"id":"1312","type":"VBar"},{"attributes":{},"id":"1329","type":"Selection"},{"attributes":{"fill_alpha":{"value":0.1},"fill_color":{"value":"#aec7e8"},"hatch_alpha":{"value":0.1},"hatch_color":{"value":"#aec7e8"},"line_alpha":{"value":0.1},"line_color":{"value":"#aec7e8"},"top":{"field":"GRAND_THEFT"},"width":{"value":0.8},"x":{"field":"Hour"}},"id":"1301","type":"VBar"},{"attributes":{"fill_color":{"value":"#1f77b4"},"hatch_color":{"value":"#1f77b4"},"line_color":{"value":"#1f77b4"},"top":{"field":"ATTEMPTED"},"width":{"value":0.8},"x":{"field":"Hour"}},"id":"1293","type":"VBar"},{"attributes":{"fill_color":{"value":"#ffbb78"},"hatch_color":{"value":"#ffbb78"},"line_color":{"value":"#ffbb78"},"top":{"field":"PETTY_THEFT"},"width":{"value":0.8},"x":{"field":"Hour"}},"id":"1311","type":"VBar"},{"attributes":{},"id":"1324","type":"AllLabels"},{"attributes":{"label":{"value":"GRAND_THEFT"},"renderers":[{"id":"1302"}]},"id":"1318","type":"LegendItem"},{"attributes":{},"id":"1281","type":"SaveTool"},{"attributes":{"source":{"id":"1259"}},"id":"1315","type":"CDSView"},{"attributes":{"source":{"id":"1259"}},"id":"1303","type":"CDSView"},{"attributes":{"factors":["0","1","2","3","4","5","6","7","8","9","10","11","12","13","14","15","16","17","18","19","20","21","22","23"]},"id":"1260","type":"FactorRange"}],"root_ids":["1261"]},"title":"Bokeh Application","version":"2.4.3"}}
    </script>
    <script type="text/javascript">
      (function() {
        const fn = function() {
          Bokeh.safely(function() {
            (function(root) {
              function embed_document(root) {
              const docs_json = document.getElementById('1451').textContent;
              const render_items = [{"docid":"fe4dfd6f-4159-46f8-b714-d97eb4c4fc54","root_ids":["1261"],"roots":{"1261":"c735d63c-cfa8-481f-96d2-6fdc7d0ff7e9"}}];
              root.Bokeh.embed.embed_items(docs_json, render_items);
              }
              if (root.Bokeh !== undefined) {
                embed_document(root);
              } else {
                let attempts = 0;
                const timer = setInterval(function(root) {
                  if (root.Bokeh !== undefined) {
                    clearInterval(timer);
                    embed_document(root);
                  } else {
                    attempts++;
                    if (attempts > 100) {
                      clearInterval(timer);
                      console.log("Bokeh: ERROR: Unable to run BokehJS code because BokehJS library is missing");
                    }
                  }
                }, 10, root)
              }
            })(window);
          });
        };
        if (document.readyState != "loading") fn();
        else document.addEventListener("DOMContentLoaded", fn);
      })();
    </script>
  </body>
</html>
