---
layout: post
title: "My Heart in 3 Months"
date: 2020-05-24
description: "An analysis of 3 months of personal heart rate data."
image: "/assets/blog/briheart/07_26_scatter_plot.png"
---

Two years ago, a close friend of mine gifted me with a [Motiv Ring](https://mymotiv.com/) for my birthday. I was excited to be able to record my heart rate 24/7 since a ring seemed much easier wear all day than [a](https://www.samsung.com/us/mobile/wearables/smartwatches/) [freaking](https://www.fitbit.com/us/home) [watch](https://www.apple.com/watch/). I wore it every day for 3 months (Jul - Oct, 2018) and amassed a huge dataset of \~1M records. What follows are a few interesting tidbits I could find in the data as well some personal reflections on them.

<br>

## The New Guy in Town

I think most would agree that starting your first job straight out of college can be unreasonably stressful. My experience certainly was. On my first day, at my first job, July 26th, 2018, I was absolutely *terrified*:

<div class="small-plot-div">
	<img src="/assets/blog/briheart/07_26_scatter_plot.png" class="img-fluid small-plot">
</div>

Now, if the scatterplot looks like a mess - that's because it is. But here are the things I noticed:

- My heart rate and stress peaked as I arrived at the office around 9am.
- As I grew more and more comfortable throughout the day my heart rate slowed.
- After clocking out at 5pm, my heart rate stabilized around a healthy 65bpm.
- Hitting the gym (7pm - 9pm) got my heart racing just as much as the stress of the first day - typical.

Looking back after two years in that very role, all of that stress seems so silly, if not a little embarrassing. I was so concerned that [I wasn't actually skilled enough](https://en.wikipedia.org/wiki/Impostor_syndrome). Most of my dev experience was through pet projects and start-up like internships. I didn't really know what enterprise software development looked like. In the end, I never needed to. As it turns out, most managers have reasonable expectations of new grads as well as a pretty good idea of where they need to be trained. 

I don't know who you are, dear reader, but if you're about to enter your first job and are similarly stressed, I hope you know that you're probably going to be just fine too. Your company went to great lengths to hire you and they'd be foolish to deprive you now of the tools and resources to succeed in that role. Don't stress and definitely don't let your heart rate spike to exercise levels like I did. You got this.

<br>

Anyway, *back to the heart data*.

<br>

## Fitness Gurus Hate Him - This One Weird Trick Will Lower Your Heart Rate

My workout buddies can attest that I am *terrible* at going to the gym consistently. But I can proudly say that during these 3 months, I was actually going to gym fairly regularly. I was also eating healthier portions and making cleaner decisions at mealtime \-\- like incorporating more greens and choosing white meats over the vastly superior, delicious red variety. In addition to losing 10lbs, which I have since gained back, I noticed that these choices seemed to have caused my average heart rate to improve during this time:

<img src="/assets/blog/briheart/avg_HR_over_time.png" class="img-fluid">

There are certainly lots of extraneous factors, [confounders](https://en.wikipedia.org/wiki/Confounding), that likely render this correlation moot, but I'm going to keep believing that my decisions and self-discipline mattered. In all seriousness, while I am fairly certain my decisions had *some effect* on this decreased heart rate, I can't actually draw any conclusions from this data \-\- [correlation is not causation](https://en.wikipedia.org/wiki/Correlation_does_not_imply_causation) and all that. 

However, I did want to note that exercising and a healthy diet is worth it for so much more than a decreased heart rate. Exercise has been proven to do some [pretty incredible things](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1402378/pdf/20060314s00023p801.pdf) for us and, even if we can't see it in this data, my experience was entirely in line with that. Anecdotally though, my mind was the clearest it had ever been during this time and my mood was consistently elevated. In fact, just from this experience I've made it a personal goal of mine to instill lifelong habits that involve exercise and a healthier diet. I hope that you, dear reader, plan to do so as well, if you haven't already. You absolutely deserve to take care of yourself!


<br>

## 194 Beats Per Minute

I was curious to see exactly when my heart rate was at its highest. There were two days that I suspected in particular. July 26th, 2018, the aforementioned first day on the job, and August 2nd, 2018, the day I had to give a [huge research presentation](https://www.microsoft.com/en-us/research/video/data-science-summer-school-2018-exploring-the-reliability-of-the-nyc-subway-system/). Both of these dates showed elevated heart rate distributions, with their medians close to 100 bpm:

<!-- all three images in a row together -->

<div class="row small-plot-div">
	<div class="col-lg">
		<img src="/assets/blog/briheart/07_26_density_plot.png" class="img-fluid small-plot">
	</div>
	<div class="col-lg">
		<img src="/assets/blog/briheart/08_02_density_plot.png" class="img-fluid small-plot">
	</div>
</div>

As stressful as these days were, neither of their max heart rates even came close to the highest I experienced during these 3 months \-\- a heart rate of 194 bpm. That honor belongs to August 30th, 2018, an unsuspecting Thursday in the middle of a work week no less:

<div class="row small-plot-div">
	<div class="col-lg">
		<img src="/assets/blog/briheart/08_30_density_plot.png" class="img-fluid small-plot">
	</div>
	<div class="col-lg">
		<img src="/assets/blog/briheart/08_30_scatter_plot.png" class="img-fluid small-plot">
	</div>
</div>

I had no idea what could have possibly happened on that day. From the scatterplot I could see that the spike happened around 12pm, so it couldn't have been from the gym. Lunchtime is usually more exciting than sitting at my desk, but it wasn't *that* exciting. Confused, I consulted my phone's camera roll to see if there was perhaps a photo from that day. Surely if there was something notable, I would have snapped a picture of it. I scrolled and scrolled until I finally reached the day in question. I was met with a group photo of me with my esteemed peers.

*It was the day of a new-hire party cruise*

Suddenly everything made sense. This heart rate came from me attempting to breakdance in front of my peers in the middle of the dreaded dance circle. Here was a potent combination of some of the top factors that could spike my heart rate.
Alcohol, physical activity, social pressure \-\- it was all there, and the end result was a heart rate of 194 bpm. A heart rate over double the median for that day.

I ended up getting props for the "breakdancing" I did. Albeit a small sample size of feedback (\~3 people said they were impressed), I was relieved to hear it. Looking back, it's times like these that always remind me that I really shouldn't take myself too seriously, especially at parties. It's okay to let loose from time to time and it's almost always better to try to have fun than worry about my image. 

With that said, I really need to re-watch some tutorials on backspins because, frankly, I disrespected breakdancing as a whole that day.

\-\-


This ended up being more of a reflection on 2018 than I thought it would be \-\- probably because heart rate data isn't really that interesting by itself \-\- but I still had a lot of fun writing this and looking into the data. I hope that you enjoyed, and I hope that you found something of value from either the analysis or my musings. If you're interested in collecting data like I did, then definitely check out the Motiv Ring or other smart rings. All of the code for the data cleaning and analysis can be found [here](https://github.com/bhernandev/BriHeart).

If you enjoyed, feel free to [subscribe](https://tinyletter.com/bhernandev) for email updates on my latest posts. Thanks so much for reading and an even greater thanks to my friend Maxi for the awesome gift!
