# Map-Making Principles:
* Plotting data is nothing.
* Communication; not data.
* Plot for action.
* Merge observations and models.
* Binaries are sharp.
* Probabilities are fuzzy.
* Grids are pixeled.
* Threshold is singular.
* Interpolate contours, sparingly.
* Objectify subjective claims.
* Favor observations.

## Expansion on these ideas.
* **Plotting data is nothing.** Merely taking data you got from somewhere else, plotting it on a map, and giving it a basic colorscale and title is little more than a hello world script. Your first plot like this is important. But you should aim to improve beyond this.

* **Communication; not data.** If merely putting data on a map is nothing, improving that plot means making it easier to communicate the intended message. Good science communication requires a balance of words and data. A good plot can help minimize the number of words it takes to communicate the message, though this should not be confused with a goal of "fewer is better." 
> Facts generally take a long time to say. Good communication requires us to be faster than that.

* **Plot for action.** Communication is not for awareness. People must take action. But remember: Fear is not action. Fear paralyzes.

* **Merge observations and models.** The purpose of models is to inform us what the observations will be. But once the actual day begins, it's hard to know if models were an accurate depiction of the reality being revealed. This is partially because the plotting of models and observations are different. Also, models and observations are kept as separate as church and state. For example, it is often said that if a model's initialization is bad, or if its early time steps aren't matching reality, then it will affect the rest of its calculations. But where are the plots that allow us to easily and directly compare the observations and models? No model is 100% accurate; all models can be tools. Being able to quickly know where the differences lie can be important. 

* **Binaries are sharp.** A tornado warning is a binary. Inside the polygon, you are being warned for a tornado (and probably severe wind and hail, too). Outside the polygon, you are not being warned for those hazards. It is important to know who is in the polygon and who is not. The boundary should be sharp.

* **Probabilities are fuzzy.** We often depict probabilistic information through contours or areas of changing colors. But those are often drawn with sharp lines that appear similar to binary information. How we depict probabilistic information needs to work with our human biases. If we see sharp lines, we are predisposed to see precision. But if precision is not what is intended, plots need to reflect that.

* **Grids are pixeled.** In the beginning, computer models had to have large pixels. Grid locations 80km apart were not uncommon. Smoothing this data helped make more intuitive sense of what the observations might look like. In 2020, the High Resolution Rapid Refresh (HRRR) has grids locations 3km apart. Even the Global Forecast System (GFS) is 28km. Zooming in on a region of the US, smoothed data can once again present a false sense of precision and overconfidence in the outcome. In the days of 80km grids, unsmoothed data was uninterpretable. In the days of 3km grid, smoothed data looks too much like reality. If you forget that you're looking at a model, you forget to use the data properly. 

* **Threshold is singular.** The significant tornado parameter (STP) was created to identify environments most likely to produce EF2+ tornadoes. This is identified when the STP is above its threshold value. If the STP is less than the threshold, then it is less likely for a significant tornado to occur. The threshold is one unit. Many websites show the raw value of STP on a continuous scale from zero to a number higher than one. But an STP of 6 doesn't mean anything. Its only significance is that it's higher than 1. It's a threshold. Treat it as such.

* **Contours are context.** Color-filled areas draw attention to what is being communicated; contours provide context or clarification to the colors. But contours aren't an excuse to avoid the other rules.

* **Objectify subjective claims.** Listen to what people say when interpreting data. "Model A is trending toward model B's solution." "Model A has a wet bias." "This is the most consistent I've seen models this far out." Can we objectively determine these things?

* **Favor observations.** Ahead of each day, we can look at model forecasts some five or seven days ahead. But we can only look at observations for that day on that day. This imbalance has made us skilled at looking at models, but unskilled at translating what we've been seeing to the physical world when it starts to unfold. If we design our models to give us a look at what the observations might look like, and how the observations are differing from the modeled forecasts, we might be surprised less or see the key features sooner. Models should save lives, not just be a bunch of data.
