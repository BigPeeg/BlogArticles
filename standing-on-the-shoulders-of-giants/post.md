When extending an existing product it is often a fraught process. Developing software that runs in the cloud with continuous integration an aspiration for many, so scenario may happen on an hourly, daily or weekly basis. The process traditionally mixes components and modules that have been proven over time with new and updated components that don't have the same depth of hardening. With this disparity there is a risk that these new components will introduce unexpected or undesired behaviour. To confound the situation further these updates are usually being added to add new features, but how can be sure these are the right features at this time for our target users? This article proposes a product development strategy that aims to reduce these risks and extends products with features that are proven to be desirable to the target market.

# Prioritising Features

[Glasswall Solutions](https://glasswallsolutions.com/) offers an [email product](https://glasswallsolutions.com/filetrust-for-email/) that delivers attachments that you can trust. We have a growing customer base and plans to extend the features that our _FileTrust for Email_ product offers. As with any growing company we have more ideas than available resources to implement them. We therefore need to 'work smart' to ensure that the resources that are allocated are working on the right features.

![Live Glasswall File Trust for Email Dashboard](E:\PGRepos\BlogArticles\standing-on-the-shoulders-of-giants\Images\gw_dashboard.jpg)

## Types of Features

Historically products are developed against a roadmap of features. Noriaki Kano [identified an approach that categorised features](https://en.wikipedia.org/wiki/Kano_model) into 

* Threshold features
* Linear features
* Exciters and delighters

Threshold features are those that must be present in the product for it to be successful. They are the _must have_ features that will block purchasers from even considering the product if they are not there. For an email product, the ability to deliver emails, reliably in a secure and timely manner would fall into this category.

Linear features are those that add add more value in sheer volume, _the more the better_. If may be that the number of different file types that are handled, the speed at which data is processed or the long the 'mean time between failure' that drives up the value, depending on the customer.

Exciters and delighters are features that often get a "hey that's neat" response from users. They add value with the presence, but their omission won't reduce the value of the product. If an administrator gets a notification that there has been a sharp increase in the number of emails that look suspect are arriving into the company, that may get a "hey that's neat" response.

## Selecting Features

Whilst we can all think of examples that will fit into each of the classifications it is difficult to select the ones that people will actually pay for. Customer questionnaires or interviews, market research or 'gut feel' have all been used in the past by many companies in an attempt to build a feature roadmap for their product that adds commercial value at every turn. The problem is that customers are busy, and the answers that they give in the calm and considered environment of an interview may not be the answer that they would give in the midst of an incident or when they have to pull out the company credit card. This goes the same for market research too. The 'gut feel' approach relies too much on the experiences of the gut's owner to be accurate. Unless they are as experienced as their potential customers in that customer's domain, they are unlikely to be aligned.

If we were to base our decisions on the purchasing history of our customers, that would be a more accurate indicator on which features they are interested in. If customers were buying services and finding them useful then the revenue of those services could be used as an indicator to guide the prioritisation of work. This is the approach that we are adopting to identify which features to concentrate our development efforts on.

## Evidence Based Decisions

[Wardley Map Here]

In this chart the x-axis is the measure of trust. It builds from _None_ to _High_ as it goes from _Minimum viable Prototype_ through _Viable Product_ and then to _Product_. On the y-axis are the phases of development through which functionality travels. The _Feature_ starts at the base of the axis with no trust, it's just an idea. With a small amount of effort a _Minimum Viable Prototype_ is developed. This proves that the feature is doable and is demonstrable, which lifts the trust that is afforded it. With some refinement, the prototype evolves into a _Viable Prototype_ before finally achieving the level of _Product_. 

With this process we've developed a feature to the level of _Product_ with very little resource, but we have a utility that is available for purchase.



