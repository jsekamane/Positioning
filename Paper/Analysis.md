We are now ready to investigate the first models. We start with the all-sticker, all-aggregator, all-hunter and all-maxcov models. In each of these models all the firms use the same decision rule. Unlike Fowler and Laver (2008) that run a tournament to determine the best preforming decision rules, we want to analyse the underlying dynamics of each decision rule and how these different decision rules affect the location behaviour of firm. By comparing results across the four different models, we see how the location behaviour of the decision rules differ. We start with a symmetric unimodal distribution of consumers. The peak of the consumer distribution function coincides with the mean ideal point of all consumers. There is no polarisation of the mean ideal points of the two subpopulations and the subpopulations are equally large ($\mu=0$ and $n_l/n_r=1$). Thus there is the only one free parameter in each model; the number of firms $N$. We use the grid sweep method to set this parameter value.

## 4.1 Baseline model and decision rules

![Mean eccentricity for respectively all-sticker, all-aggregator, all-hunter and all-maxcov model. Where $\mu=0$ and $n_l/n_r=1$. Bands indicate +/- standard deviation.](Graphics/fig21a.png)

In the all-sticker model the firms remain at their initial position. They never relocate. Figure _[##]_ plots the mean eccentricity for each of the models. As expected we see that the average distance to the population centre is 1.5 standard deviation in the all-sticker model. This result reflects how the initial positions of firms are drawn, i.e. uniformly random from a circle with radius of 3 standard deviations and centre at (0,0). And thus we find that on average a *sticker* firm will be located 1.5 standard deviations from the centre of the population -- irrespective of the number of firms in the market. 

In the three remaining models mean eccentricity is significantly lower. The initial position of the firms in these models are drawn from exactly the same distribution, but the firms clearly moved towards the population centre. 

In the all-aggregator model the firms aim to please their current customer base. The firms choose to locate 0.4-0.8 standard deviations away from the population centre with the distance increasing along with number of firms in the market. In the all-hunter model, where all firms constantly seek higher market shares, the firms choose to locate in closer proximity to the population centre than in the all-aggregator model. Hunter firms locate around 0.2 standard deviation closer to the centre than aggregator firms.

Despite the fact that the population centre has the largest density of consumers of any point in the market, firms consistently locate at a distance to this point — even *hunter* firms that constantly seek larger market shares. This suggests that locating too close to the population centre is suboptimal (Laver and Sergenti 2011 chapter 5). For a *hunter*-firm there is a short-run gain by moving closer to the high density population area. However the response from competing firms quickly erodes this gain, leading to the long-run location that lies at a distance to the population centre. Our estimate of mean eccentricity for five hunter firms is 0.44. Compare this to figure _[##]_, where we for each of the five *hunter* firms plot eccentricity against market share. When the individual firm locates 0.44 standard deviations from the population centre, its share of the market is around 21%. Locations closer to the population centre is associated with a higher share of the market for each individual firm, i.e. a short-run gain. However all firms use the same disunion rule and thus no one firm has a long-run competitive advantage over its competitors. In the long-run the firm cannot sustain the larger market share, leading to the long-run location at a distance to the population centre.

![Eccentricity against market share for each firm. This shows the results from a single repetition with 5 *hunter* firms. At each iteration we record the eccentricity and market share of each firm. We smoothed the data. The estimate of mean eccentricity for five *hunter* firms is 0.44 standard deviations, which is illustrated with vertical red line.](Graphics/fig3ms.png)

_[Compare results to Eaton and Lipsey (1975) / equilibrium predictions (two firms).]_

In the all-maxcov model the firms deliberately attempt to maximise their market share. And the firm takes the location of competing firms into account, although it assumes that competing firms maintain their current position. Firms in the all-maxcov and all-hunter model locate at similar distance to the population centre. The main exception is in the market with two firms. In this case the *maxcov* firms locate at the same distance as *aggregator* firms. In the all-maxcov model there is only a slight tendency for firms to locate further away from the population centre as the number of firms increase. On average the *maxcov*-firms locate 0.4-0.5 standard deviations away from the population centre.

![Effective number of firms (ENP) for respectively all-sticker, all-aggregator, all-hunter and all-maxcov model. Where $\mu=0$ and $n_l/n_r=1$. Bands indicate +/- standard deviation.](Graphics/fig22a.png)

In the models the actual number of firms in the market is an endogenously determined parameter. Our experimental design allows us to investigate the models when there is anywhere from 2 to 12 firms in the market. To analyse the competitive environment we use a measure called *effective number of firms* (ENP). The ENP takes the relative market shares of the firms into account. The ENP tells how many firms would be in the market if they all had identical shares of the market. If the actual number of firms and the effective number of firms is the same (thin 45 degree line in figure _[##]_), then the firms in the market split the market evenly. If the effective number of firms is less than the actual number, then one or several of the firms will have a disproportionate share of the market.

The effective number of firms is low in the all-sticker model, ranging from around 1.5 and up to 4.5. The initial position of firms gives some firms a clear advantage over the other firms in the market. And since *sticker* firms do not relocate the uneven concentration of customers persists.

In the last three models the market is fairly evenly split among the firms. This is the result of firms with identical decision rules competing among themselves. Since all firms use the same decision rule, no one firm has a long-run advantage over its competitors. And thus the firms end up with approximately the same long-run share of the market. With many firms in the market it is increasingly harder to maintain the perfectly even split among the firms. And so we observe that the ENP is slightly below the actual number of firms in the all-hunter, all-aggregator and all-maxcov model when there are many firms in the market.

In the all-aggregator model with many firms the effective number of firms is slightly lower than the all-hunter and all-maxcov model. The reason for this is that with many firms the centre of the distribution easily overcrowds. *Aggregator*-firms locate to please their current customer base. And so overcrowding leads the firms to locate on different orbits around the centre. Firms located on the inner orbits attract a larger share of the consumers than the firms located on the orbits further away from the centre. And the unequal market share of firms reduces the *effective number of firms* (ENP).

![Mean representation for respectively all-sticker, all-aggregator, all-hunter and all-maxcov model. Where $\mu=0$ and $n_l/n_r=1$. Bands indicate +/- standard deviation.](Graphics/fig23a.png)

The mean representation measures the satisfaction of consumers. This social welfare measure calculates the average utility of all consumers. The utility of the consumer increases when the distance to the closest firm decreases. From earlier we known that the all-aggregator model will result in the location of firms that constitute a *Centroidal Voronoi Tessellation* (CVT). The CVT minimises the average distance to all customers and therefore maximises our social welfare measure. The all-aggregator model provide a benchmark, since the location of firms is socially optimal.

In both the all-hunter and all-maxcov model where firms aim to maximise their market share, they manage to achieve almost the same mean representation as in the all-aggregator model, where firms actively aim to please their customer base. And this despite *hunter* and *maxcov*-firms locating closer to the population centre than *aggregator*-firms. We also see that as the number of firms in the market increases the mean representation converges towards the social optimal level. Unsurprisingly the all-sticker model scores lowest on our social welfare measure.


## 4.2 Asymmetric and multimodal population distribution

In the section above we got a sense of the different models and how firms react when using different decision rules. Our results have so far assumed a symmetric unimodal distribution of consumers, with no disagreement over the average ideal point along any of the two dimensions. There was a single peak in the distribution where the density of consumers was greater than any other point, and the peak corresponded to the mean ideal point of all consumers. We observed that firms chose to locate at a distance to mean ideal point of consumers. The literature review showed that different distributions of consumers have had significant impact on the results of previous competitive location models. We now want to investigate how firms locate when there is not a single peak in the distribution? How the location dynamics of firms change when the subpopulations disagree over the mean ideal point? And to what extend our results so far generalise to other distributions, such as the asymmetric and multimodal distributions? 

We continue to investigate models where all firms use the same decision rule. Firms are competing against other firms using the same decision rule. Firms using the *sticker*-rule do not relocate, and thus executing the all-sticker model with an asymmetric consumer distribution would not provide further insights. Thus we leave the *sticker*-firms out of this subsection. 

In the following models there are three free parameters; The number of firms in the market $N$ which takes integer values between 2 and 12. The polarisation of the subpopulations $\mu$ which can take any value between 0 and 1.5. And finally the relative size of the subpopulation $n_l/n_r$ which takes any value between 1 and 2. To parametrise our models we use the Monte Carlo parameterisation method. For each run of the model the parameter values are uniformly random drawn from their respective ranges. We execute many *runs* of the models to map out the entire parameter space. For each run we obtain a mean estimate of our summary variables. In the following figures each dot represents the estimate from one run. We present the results from the different decision rules in separate panels. We use three bands to summarise the results from different degrees of polarisation among the subpopulations. The first band summarises the results from the runs where there is a low degree of polarisation ($\mu \le 0.5$). We know from earlier, that this implies, that the distribution of consumers contain a single peak, and that the degree of asymmetry depends on the relative size of the subpopulation. The second band is for a medium degree of polarisation ($0.5 < \mu < 1$). And the last band is for a high degree of polarisation ($\mu \ge 1$). In this range we know that the distribution is bimodal and that the peaks of the distribution almost coincide with the mean ideal points of the two subpopulations. In addition the mean ideal point of all consumers lies in the low density area in between the two peaks.

![Mean eccentricity for respectively (a) all-aggregator, (b) all-hunter, and (c) all-maxcov model. Where $\mu \in [0, 1.5]$ and $n_l/n_r \in [1, 2]$.](Graphics/temp_mcp_meaneccentricity.png)

Firms using the *hunter*-rule still locate closer to the mean ideal point of consumers than the firms using the *aggregator*-rule for any degree of polarisation. However the differences in proximity between *hunter*-firms and *aggregator*-firms is much less pronounced in markets with a high degree of polarisation and many firms. Here the mean eccentricity is approximately 1.2-1.4 for both decision rules.

In the highly polarised setting we see significant differences between the market with 4 or more *hunter*-firms and then the market with 2 or 3 *hunter*-firms. For one we see that the distance to the mean ideal point of consumers increases swiftly when going from two to three and from three to four firms. While going beyond four firms in the market has negligible effect on the average distance to the population centre. This happens because firms separate when there is four or more firms in the market. In these cases we typically see that firms split into two crowds. Each crowd locates close one of the peaks of the consumer distribution function. The number of firms in each crowd is roughly proportional to the relative size of the subpopulation. There is little competition between firms from different crowds, while the firms in each crowd compete fiercely with one another for the customers in the respective subpopulation. In the symmetric all-hunter model with four or more firms in the market, we observed that firms locate 0.4–0.6 standard deviations away from the peak of the distribution. Similar behaviour is observed in the models with a high degree of polarisation, however here we have two peaks rather than one. And the firms tend to locate around a peak, rather than in between the two peaks. See an example of this split in a market with five firms in figure _[##]_. Each individual *hunter* firm experiences a short-run loss when it moves away from a peak. This discourages the firm from switching between the crowds. Thus the composition of the crowd is fairly stable, and the firm sees no long-run advantage in locating between subpopulations and close to the mean ideal point of all consumers. On the other hand with two or three *hunter*-firms in the market, the firms tend to move in unity[^dancing]. Two *hunter* firms tend to locate in between the two subpopulations. Thus they locate close to the average ideal point of all customers, but simultaneously they locate in an area with a low density of consumers. Later we show that this has great impact on the average utility of consumers. With two firms and little to no polarisation, all decision rules show that the firms locate close within 0.6 standard deviation of the mean ideal point of all consumers. However only *hunter*-firms continue to locate like this when the polarisation among the subpopulation increases. This effect shows the interplay between decision rule and the distribution of consumers.

[^dancing]: Because *hunter* firms cannot leapfrog to the perimeter, but move with constant speed, we don’t observe the *dancing equilibrium* described Eaton and Lipsey (1975) in the market with three *hunter*-firms. Instead the three firms move in unity and the location of the unit bounces back and forth between the two peaks of the distribution.

Laver and Sergenti (2011, chapter 5) discovered the change when going from 2-3 *hunter* firms and into the realm of four or more *hunter* firms. Yet they seem unaware of an earlier and related discovery by Eaton and Lipsey (1975). Eaton and Lipsey (1975) also analyse asymmetric distributions admittedly in a slightly different setting, namely the bounded one-dimensional space (line market). They show analytically that an equilibrium only exists if the number of firms is less or equal to twice the number of peaks in the density distribution, i.e. $N \le 2M$ where $M$ is the number of peaks in the consumer density function. They find that when the number of firms is exactly twice the number of peaks then the firms locate in pairs around the quantiles of the distribution. While with fewer firms (than twice the number of peaks) there is some leeway as to how firms locate. Both the pairing of firms in groups of two and the $2M$ limit stems from the single dimensionality of the space. In a one-dimensional line market the only available option is which side of a given point you locate on (left or right). Using this and equilibrium conditions Eaton and Lipsey (1975) show the limit of $N \le 2M$. In the two-dimensional market firms can locate 360 degrees around a given point, and thus firms need not pair in twos. This is what we observe in the all-hunter model where firms crowd together although not necessarily in pairs of two. Additionally in two-dimensional space the number of peaks does not create an upper limit on the number of firms in the crowd -- once again because firms can locate all the way around a given point. But the number of peaks does seem to influence how firms locate. There is a single peak in the model with a symmetric distribution, and two peaks with highly polarised subpopulations. Only when the number of firms is equal or greater than the number of peaks do the *hunter* firms form crowds around the peaks of the distributions. When the number of firms is less than the number of peaks, then there is some leeway as to how firms locate and thus we see that *hunter* firms locate between the peaks of distribution.

The symmetric distribution showed that *maxcov* and *hunter* firms locate at similar distance to the population centre, except with two firms in the market. We see similar pattern with the asymmetric distribution of customers. The *maxcov* and *hunter* firms locate a similar distance to the population centre irrespectively of the polarisation of the subpopulations. The exception is when there are only a few firms in the market. With the *maxcov* decision rule there is no abrupt change when going from 2-3 firms and to 4 or more firms, as is the case with the *hunter* decision rule. *Maxcov*-firms separate in two crowds even in the case with low or no polarisation of the subpopulations. Two *maxcov* firms will not agglomerate at the average ideal point of all customers, but instead locate at a distance to the centre. This contrasts starkly with the two *hunter* firms that agglomerate around the population centre.

![Effective number of firms (ENP) for respectively (a) all-aggregator, (b) all-hunter, and (c) all-maxcov model. Where $\mu \in [0, 1.5]$ and $n_l/n_r \in [1, 2]$.](Graphics/temp_mcp_enp.png)

The asymmetric distribution reiterates the conclusions from the symmetric distribution regarding the effective number of firms (ENP). Both the model with *aggregator* and *hunter* firms show that the market is relatively even split among the firms in the market. When there are many firms and a low degree of polarisation then the ENP is slightly lower in the *aggregator* model than the *hunter* model. As mentioned when discussing the symmetric model, with many firms in the market the area around the single peak easily overcrowds, and thus *aggregator* firms locate at different orbits around the peak. This gave rise to the slightly lower ENP in the *aggregator* model. When the degree of polarisation increases the density of consumers is dispersed across a larger area, which leads to less overcrowding. Consequently *aggregator* firms are no longer forced to locate at different orbits, which implies that the market is more evenly split among firms. This is why the difference in ENP completely disappears as the polarisation of the subpopulations increase.

The market is also relatively even split among the firms in the *maxcov* model. In the market with many firms and a high degree of polarisation the ENP is slightly lower. As earlier noted the firms split into two crowds in the *maxcov* model. However in the *maxcov* model the number of firms in each crowd is not necessarily proportional to the relative size of the subpopulations. Often a few firms manages to capture one-half of the market and this results in the lower ENP. The ENP would be 3.6 if a single firm out of 12 firms captured half the market[^ENPcalculation]. However with 12 firms in the market we observe an ENP around 10. This tells us that a single firm is unable to capture and maintain half the market by itself in the long-run -- it has to be a group of firms.

[^ENPcalculation]: With N=12 and the market split in two halves the ENP is $\frac {(0.5+0.5)^2}{\left(\frac{0.5}{11}\right)^2 \times 11 + 0.5^2} = 3.6$ when 1 firm has 50% of market alone and the 11 other firms share the remaining 50% equally. 

![Mean representation for respectively (a) all-aggregator, (b) all-hunter, and (c) all-maxcov model. Where $\mu \in [0, 1.5]$ and $n_l/n_r \in [1, 2]$.](Graphics/temp_mcp_meanrepresentation.png)

In *aggregator* model where the distribution of consumers is asymmetric, the location of firms still constitute a CVT. And thus this model maximises our social welfare measure -- the mean representation. Once again we can use the *aggregator* model as a benchmark. The difference between the mean representation in the *aggregator* model and the *maxcov* model is minuscule.

In the *hunter* model we see that the asymmetric distribution of consumers give rise to significant changes when going from 2-3 firms and to 4 or more firms. This is particularly pronounced in the models with a high degree of polarisation. With two or three *hunter* firms the mean representation is around -2, while with four or more firms the mean representation is between -0.5 and -0.2. As earlier noted this is the result of *hunter* firms locating in between the centres of the subpopulations when there are 2-3 firms in the market. Although the firms locate close to the average ideal point of all customers, they also locate in an area with a low density of consumers. Because firms locate far from densely populated areas it significantly reduces the average utility of customers. On the other hand firms separating into crowds that locate around the centres of the subpopulation, when there are four or more firms in the market. Laver and Sergenti (2011, chapter 5, p. 102) refer to this as the *“sea change”* in mean representation when reaching four or more firms. The effect is a result of a bimodal distribution of consumers.

We are now at the point where we have an understanding of the baseline decision rules; *sticker*, *aggregator*, *hunter* and *maxcov*. The first three rules rely on heuristics, while the last rule deliberately and directly tries to maximises the market share of the firm. We know how firms, that use these rules, choose to locate -- both when the distribution of consumers is symmetric and when it is asymmetric. We know which type of competitive environment arises from the location behaviour of the firms. And we know how this behaviour affects the overall welfare of consumers. The following section looks at how firms locate when they take the predicted location of competing firms into considerations.