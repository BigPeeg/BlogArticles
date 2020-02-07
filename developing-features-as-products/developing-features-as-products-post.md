When extending an existing product it is often a fraught process. Developing software that runs in the cloud with continuous integration an aspiration for many, so scenario may happen on an hourly, daily or weekly basis. The process traditionally mixes components and modules that have been proven over time with new and updated components that don't have the same depth of hardening. With this disparity there is a risk that these new components will introduce unexpected or undesired behaviour. This article proposes a product development strategy that aims to reduce these risks and enables us to extend products with features that are proven to be stable and fit for purpose.

# Adding New Features Introduces Risk

- New code hasn't been used in production environment

- Testing limited by the imagination and time available to testers

- New code isn't trusted in the same way that existing code is



# Mitigating Risk by Developing Features as Products

[This Wardley Map](https://en.wikipedia.org/wiki/Wardley_map) describes the journey of a Feature from inspiration to integration with the Final Customer.

![Feature To Product Wardley Map](E:\PGRepos\BlogArticles\developing-features-as-products\images\FeatureToProductWardleyMap02.png)

In this chart the x-axis is the measure of trust. Trust builds as a feature builds from _Genesis_ to _Commodity_. It is for the team to agreed the standards of each classification and what is required from a feature is order that it can be promoted to the next classification.

The _Feature_ starts at the base of the graph with no trust, it's just an idea. With a small amount of effort a _Minimum Viable Prototype_ is developed. This proves that the feature is doable and is demonstrable, which lifts the trust that is afforded it. With refinement, the prototype evolves into a _Viable Prototype_ before finally achieving the level of _Product_. 

Timescales are not specified, the duration is entirely dependent on how much resource is allocated which controls how quickly each checkpoint can be achieved.

# Genesis

> When a new feature is born it has no trust

In the begining there is 

No limit on the technology or approaches that can be used



# Minimum Viable Prototype

Developing a MVP enables trust to be developed

Algorithms are proven

New technology learnt

New approaches are verified

# Viable Product

Broader range of users and use cases

Better resilience

Proven with end-users

Adheres to company policy in standards of code and technologies used

Bringing in new technology will take longer to the benefits need demonstrating and infrastructure proven. 

# Launched as a Product

A stand-alone product.

Deployed and maintained as production code.

Used by the potential customer base.
High level of trust built through demonstrable resilience and performance.

Launching to the internet provides an unpredictable traffic load.

Launching to the internet provide unpredictable traffic.

As the product is enhanced to support high traffic level, trust increases with the demonstration of the product's stability under load.

With low confidence in the feature we rely on system tools to gain insight on the performance and health of the feature. As experience is gained on how the feature behaves under load the inclusion of better visualisation builds levels of trust in when the feature is reporting, rather than having to interpret system tools.

# Ready for integration

When high trust is held in all aspects of the feature, it is ready to be added as a features of the live product.

Rather then fresh code being integrated, it is production code that has already be subjected to live consumer traffic.

The only new code involved is the 'piping' required to pull in the feature's components.