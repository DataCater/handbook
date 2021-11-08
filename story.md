# How it began

We founded DataCater in 2020 to help companies to
efficiently connect their growing amount of data silos.
Having a strong background in software development and data engineering, our founders knew the pains of developing, observing, and operating data pipelines.

# Why it began

In practice, we observed that many data teams face the following
challenges and pains:

* **Building data pipelines takes too much time**: Data teams
  spend days to weeks on building a single data pipeline. This is way too
  much time considering the huge demand for data pipelines from the
  business side of data-driven organizations.
* **Prepared data are almost always outdated:**
  Traditionally, data pipelines are batch-based. They are executed at
fixed intervals, for instance, each night at 3 am. This leaves the
prepared data in data sinks almost always out of sync with the data sources and
prevents decision-makers to use recent data.
* **Shipping data pipelines to production is hard:**
  While building data pipelines takes a lot of time, shipping them to
production is even harder. As a consequence, many data projects end up
as proof-of-concepts, which never make it to production. Without a
production deployment, data projects cannot provide value to the
business.
* **Data pipelines lack transparency and observability:**
  It is still very hard to observe the performance of data pipelines
and get meaningful insights into data being processed.

# How we fix it

At DataCater, we aim to fix moving, transforming, and working with data.
We want to allow data teams to unlock the full value of their data,
faster.
To this end, we take a very opinionated approach on how to build data pipelines.

## Interactive data work is natural and time-efficient

Working interactively with data feels most natural to humans. Spreadsheets are
the de-facto standard interface to data, being used by more than 750M people each day.
However, we do not only favor to instantly see the
impact of changes in a *what you see is what you get* manner but it
saves a lot of time, too. Manually building data transformations as code, manually executing the code,
and manually investigating the transformed data in a target system takes plenty of
time and is strongly outperformed by an interactive pipeline designer,
which can preview the effect of transformations while
building them.

As a consequence, DataCater provides [interactive means](https://www.youtube.com/watch?v=R2lI-ahYEqM) to working with
streaming data pipelines. By working on data samples, users can
instantly the impact of their filters and transformations. Once they're
happy with the results, they can ship the pipeline to production as
easily as possible with DataCater's one-click deployments!

## Streaming data changes keeps data sinks up-to-date

In the last years, we could witness the emergence of efficient and powerful technologies in the area of stream processing.
While batch data pipelines transfer entire data sets at fixed intervals,
streaming data pipelines operate like a continuous flow and sync data changes from data sources to data sinks
in real-time, often being paired with change data capture connectors.

At DataCater, we consider batch to be a subset of streaming. While a
streaming data pipeline can be *filled* with data by a batch connector,
it is not working the other way around.
We envision that streaming will become the de-facto
standard for data pipelines within the next years.

Although stream processing has advanced a lot in the last couple of
years, it is still not accessible to developers and data teams.
We will fix that!

## One-click deployments allow to ship data pipelines within minutes

The implementation of a data pipeline boils down to software code, which needs to be deployed
to production using a CI/CD approach.

However, most data teams have a hard time shipping their data pipelines,
since they use tools that prevent straightforward deployments.
It's still a very common setup that data scientists perform data
wrangling and pre-processing in Python notebooks. Once they finished the implementation,
data engineers take care of *translating* the Python notebooks to
production-grade code.
This is a very time-inefficient and error-prone process.

At DataCater, we take a very opinionated approach to structuring data pipelines.
This allows us to automate the *translation* of data
pipelines, which have been developed with our interactive pipeline
designer, to production-grade container images.
Any member of a data team can deploy their data pipelines to
production by clicking one button, removing all manual and repetitive
work from the deployment process and allowing data engineers to focus on
tasks of higher value. Hooray!

## Native integration into cloud platforms allows for full observability

Data pipelines often lack observability and transparency. It is very
hard for data teams to get meaningful insights into their data pipelines and
the data flowing through them.

At the same time, cloud platforms become the new standard in computing. Oftentimes, data or analytics
is the first mover when migrating to cloud platforms, because it becomes
increasingly cost-inefficient for companies to host data services on
their premises.

In contrast to traditional data pipeline platforms, DataCater no longer
tries to integrate with the plethora of different environments available
for on-premise installations, but strictly focuses on private and public
clouds. This enables DataCater to provide native integrations into cloud-native services for compute,
monitoring, logging, etc., and maximize the observability of
the managed data pipelines.

# Where we go from here?
Our mission is to make stream processing available to a bigger audience. But DataCater will not stop there. We will use that baseline to
enhance the tooling of the ML/AI lifecycle. Our goal is to make the work of data teams fun again and help them provide value to
organizations by easing deployments to production. 

Vertically, we will offer more ML-focused transformations, e.g., one-hot encoding,
monitoring drifts in your data over time, and other feature generation tasks like clustering.
Our customers will focus on getting value from their data and providing more value to their customers / to the world.

Horizontally, we will take more opinionated approaches to how data is collected and prepared for ML/AI models.
DataCater will offer tools for automatically re-training and serving ML models, based on data criteria such as drift in features or
score over time. Instead of retraining on a schedule.

We are on a journey to make DataCater an essential tool for all data teams. We want to
relieve the brightest people from cumbersome and repetitive work, so they can focus on tackling the hard problems that our world faces today.
