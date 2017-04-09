# So Simple Theme

Looking for a simple, responsive, theme for your Jekyll powered blog? Well look no further. Here be **So Simple Theme**, the followup to [**Minimal Mistakes**](http://mmistakes.github.io/minimal-mistakes/) -- by designer slash illustrator [Michael Rose](http://mademistakes.com).

## Notable features:

* Compatible with Jekyll 3 and GitHub Pages.
* Responsive templates. Looks good on mobile, tablet, and desktop devices.
* Gracefully degrading in older browsers. Compatible with Internet Explorer 9+ and all modern browsers.
* Minimal embellishments and subtle animations.
* Optional large feature images for posts and pages.
* [Custom 404 page](http://mmistakes.github.io/so-simple-theme/404.html) to get you started.
* Basic [search capabilities](https://github.com/mathaywarduk/jekyll-search)
* Support for Disqus Comments

![screenshot of So Simple Theme](http://mmistakes.github.io/so-simple-theme/images/so-simple-theme-preview.jpg)

See a [live version of So Simple](http://mmistakes.github.io/so-simple-theme/) hosted on GitHub.

---

## Getting Started

So Simple takes advantage of Sass and data files to make customizing easier and requires Jekyll 3.x.

To learn how to install and use this theme check out the [Setup Guide](http://mmistakes.github.io/so-simple-theme/theme-setup/) for more information.

[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/mmistakes/so-simple-theme/trend.png)](https://bitdeli.com/free "Bitdeli Badge")


## Generate data for example

We generate data such that the confounders, a1 and a2, affect both the features, x1 and x2, as well as the class labels, d.


N.B. If some of the estimated weights are extremely large, one may consider truncating the predicted probabilities (e.g., at the 5th percentile) or using stabilized weights. Define $S_i = pr(d_i=1 | a1_i, a2_i)$ and $M_i = pr(d_i=1)$ as well as corresponding estimates \hat{S}_i = \hat{pr}(d_i=1 | a1_i, a2_i) and \hat{M}_i = \hat{pr}(d_i=1), Then, stabilized weights and their corresponding estimates are defined, respectively, as:
$$
W*_i = d_{i}*(M_i/S_i) + (1-d_{i})*(1-M_i)/(1-S_i) 
$$
and fun
$$
\hat{W*}_i = d_{i}*(\hat{M}_i/\hat{S}_i) + (1-d_{i})*(1-\hat{M}_i)/(1-\hat{S}_i) 
$$

## Train the inverse probability weighted SVM (IPW-SVM)
