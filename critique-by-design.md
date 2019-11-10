# Critique by Design

## The original visualizations

The original visualization I chose appeared in the [Desmog Blog](https://www.desmogblog.com/2019/10/31/consumer-energy-alliance-pennsylvania-air-quality-natural-gas) on October 31, 2019. This blog references a twitter post by Range Resources, which references [this post](https://consumerenergyalliance.org/2019/10/pennsylvanias-emissions-fell-92-energy-production-soared-3000/) by Consumer Energy Alliance (CEA), further referencing a [PDF report by CEA](https://consumerenergyalliance.org/cms/wp-content/uploads/2019/10/CEA_INFOGRAPHIC_PENNSYLVANIA.pdf). Shown here is the original tweet by Range Resources and another plot from the PDF.

![Range Resources Tweet Plot](range_resources_tweet_plot.png)

![CEA Plot of PA Natural Gas Production](cea_pdf_natural_gas_production.png)

### Why I selected this

I selected this visualization because there was quite a bit to work with! The data that the Consumer Energy Alliance is presenting came out after [The New York Times](https://www.nytimes.com/interactive/2019/10/24/climate/air-pollution-increase.html) published an article about the national rise in air pollution since 2016. The New York Times article references EPA data examined by researchers at Carnegie Mellon University.

The CEA is utlizing data from multiple sources (including the EPA) to argue a lack of relationship between natural gas production and harmful emissions. Choosing this visualization to redesign and critique provides an interesting insight into how data can be "used" to imply relationships beyond its scope.

## Re-Designed visualizations

### Process and wireframing

The redesign process began with critiquing the original visualization using Stephen Few's [Data Visualization Effectiveness Profile](http://www.perceptualedge.com/articles/visual_business_intelligence/data_visualization_effectiveness_profile.pdf) to determine what was effective and what could be improved. I ranked the orignial visualization at the low end of the scale for usefulness and perceptability. This was because the original graph did not show what the CEA was saying it did - a correlation between natural gas production and lowered emissions of various pollutants. I started with wireframing to improve some of the visual features of the graphs to enhance legibility and clarity. Then I planned an alternative approach to presenting the data to more effectively convey their message. Note that doing so does not improve the truthfulness of the narrative, but shows how improperly contextualized data can suggest certain take-aways.

The first main point to address was the time axis of the plot, as well as the use of proportions instead of percentage.

![New timeline range for gas production](new_timeline_range_for_gas_production.png)

This timeline will allow for a shared axis of gas production with the emissions data.

![Shared plot for emissions and gas production](shared_plot_for_emissions_and_gas_production.png)

To further stress the point that (though this is a horribly myopic perspective) that emissions and gas production are trending in opposite directions, we will plot the emissions **per** gas production.

![Normalized ratio of emissions to gas production](normalized_ratio_of_emissions_to_gas_production.png)

The opposite trends should compound to a starker trend.

### Feedback on wireframes



The next task at hand was to extract the raw data referenced in the CEA PDF.

### Approach with Infogram

<div class="infogram-embed" data-id="3b705b9c-fce7-4d8c-8c1e-6b87ccf99ce0" data-type="interactive" data-title="Blank template"></div><script>!function(e,i,n,s){var t="InfogramEmbeds",d=e.getElementsByTagName("script")[0];if(window[t]&&window[t].initialized)window[t].process&&window[t].process();else if(!e.getElementById(n)){var o=e.createElement("script");o.async=1,o.id=n,o.src="https://e.infogram.com/js/dist/embed-loader-min.js",d.parentNode.insertBefore(o,d)}}(document,0,"infogram-async");</script><div style="padding:8px 0;font-family:Arial!important;font-size:13px!important;line-height:15px!important;text-align:center;border-top:1px solid #dadada;margin:0 30px"><a href="https://infogram.com/3b705b9c-fce7-4d8c-8c1e-6b87ccf99ce0" style="color:#989898!important;text-decoration:none!important;" target="_blank">Blank template</a><br><a href="https://infogram.com" style="color:#989898!important;text-decoration:none!important;" target="_blank" rel="nofollow">Infogram</a></div>
