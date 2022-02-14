# Ridesharing in Chicago, IL:
## Exploring community- and trip-level factors influencing willingness to pool

Valeria Balza</br>
University of Chicago</br>
vbalza@uchicago.edu</br>
</br>
Michelle Orden</br>
University of Chicago</br>
morden@uchicago.edu</br>
</br>
## Abstract
The emergence of ridesourcing providers such as Uber and Lyft have prompted
numerous questions around urban mobility, the gig economy, and environmental
sustainability—among other topics. While recent research focuses on the benefits
and limitations of ridesharing, we explore the factors affecting customers’ willingness
to share rides with other customers (i.e., ridesplitting). In particular, we
integrate ridesourcing trip data featuring cost, time and spatial variables with socioeconomic
and demographic data for Chicago, IL and train Lasso Regression and
Random Forest models to predict customers’ willingness to share rides with other
customers. After accounting for multicollinearity in our data, we find that trip-level
factors—namely cost and distance—and community area-level factors—namely
percentage of white population and median income—are among the top features
affecting customers’ willingness to split rides. The identified patterns can help
the city’s policymakers identify community areas with the greatest potential to
promote ridesplitting as the debate on ridesourcing behavior evolves.
</br>
## Introduction
The emergence of ridesourcing providers such as Uber and Lyft have prompted numerous questions
around urban mobility, the gig economy, and environmental sustainability—among other topics.
While some argue such services provide first- and last-mile solutions to transit, others suggest the
access to and use of ridesourcing services have been geographically and socially uneven (Jin et al.,
2019, Rayle et al., 2016; Shaheen and Cohen, 2018; Su and Wang, 2019; Tarabay and Abou-Zeid
2019; Yan et al., 2019). Several studies, for instance, reveal demand for ridesourcing is concentrated in
medium and large urban areas with younger, more educated, and wealthier populations—highlighting
technological and financial barriers among low-income groups (Goodspeed et al., 2019; Grahn et al.,
2019; King, Conway, and Salon, 2020; Spurlock et al., 2019; Young and Farber, 2019).
</br>

Recent research also points to the environmental effects of ridesourcing, noting ridesplitting—in
which customers share rides with other customers heading in the same direction—can mitigate traffic
congestion, reduce fuel consumption and greenhouse gas emissions, as well as curb parking demand
(Wang and Yang, 2019; Cramer and Krueger, 2016; Tirachini and Gomez-Lobo, 2019; Xue et al.
2018). Still, a parallel body of research demonstrates ridesourcing providers have introduced more
idle vehicles on the road, increased traffic congestion, and contributed to air and noise pollution (Rayle
et al., 2016; Wei at al., 2017; Wenzel et al. 2019). Despite increasing evidence on the positive and
negative effects of ridesourcing, limited research exists characterizing the factors affecting customers’
willingness to share/pool rides with other customers. This characterization is important to better
understand how the benefits and costs of ridesourcing are spatially distributed across cities.
We leverage data containing time, cost, and location features for ridesourcing trips for the city of
Chicago and integrate it with community area-level socioeconomic and demographic variables. We
then train two classification algorithms—Lasso Regression and Random Forest models—to predict a
customer’s willingness to share their ride with another customer.</br>
</br>
Specifically, given a new rider’s pickup and drop-off community area and the demographic and
socioeconomic information associated with said community areas, what is the predicted outcome
for whether the rider authorizes a shared ride? Further, what trip- and community-level features
associated with a given ride contribute to whether or not a rider agrees to a pooled trip? Exploring
such questions will allow us to see if and how ridesplitting behavior varies with socioeconomic and
demographic variables related to a given community area—providing additional context to the debate
on ridesourcing.</br>
</br>
See https://github.com/morden35/ridesharing_ml/blob/master/balza_orden.pdf for the full report.
