# [Internet Equity Initiative](https://internetequity.uchicago.edu) 
([Github])(https://github.com/internet-equity/)

## About

The [Internet Equity Initiative](https://internetequity.uchicago.edu) at the
University of Chicago aims to realize equitable, resilient, and sustainable
Internet solutions that benefit all communities As society increasingly relies
on the Internet for work, education, health care, recreation, and many other
aspects of daily life, the prevalent and persistent inequity in people’s
ability to access, adopt, and use the Internet is more evident than ever.
Stakeholders who are making decisions about where and how to direct these
investments need better information along the following three dimensions:

1. Measurement techniques and datasets that directly address unknown questions
   and evaluate the effectiveness of different interventions;
2. Data-driven collaborations with communities that are underserved by current
   Internet infrastructure to develop and test different options for
   infrastructure investments, the effectiveness of which can depend critically
   on the specific characteristics and needs found in different communities;
3. Better data and analysis about how Internet connectivity relates to the social
   and individual conditions that contribute to whether and how the Internet
   actually improves people’s lived experience.

Read more [here](https://internetequity.uchicago.edu/about/the-initiative).

## Mission Statement

Our mission at the Internet Equity Initiative is to create equitable,
resilient, and sustainable Internet solutions that benefit all communities. We
believe that everyone should have equal access to the Internet, and we work to
close the "digital divide" by taking a data-oriented approach and developing
partnerships with underserved communities. Our goal is to develop new and
innovative approaches to Internet measurement, gathering data at multiple
levels and granularities, to better understand the challenges and
opportunities in different contexts. We also aim to collaborate with
communities to identify their specific needs and preferences, co-create
solutions, and evaluate the effectiveness of different interventions. Through
these partnerships, we strive to ensure that our work is responsive,
inclusive, and relevant to the diverse populations we serve.

## Code

One of the aims of the project is to make it easy for stakeholders to gather
samples of Internet connectivity across a geographic area (e.g., a city,
region, state). 

### About the Code 

This [organization](https://github.com/internet-equity/) maintains code for
the **Netrics** system, which is a set of tools for collecting and analyzing
Internet connectivity using deployed vantage points. We have developed the
software to run on single-board computers, such as a Raspberry Pi, but it can
run on any endpoint. Netrics contains a number of built-in tests, including:
   * Three different Internet speed tests (Ookla, NDT, iperf)
   * DNS lookup latency
   * Ping latency
   * Latency under load / operational latency / "responsiveness"

### Repositories

The software is designed to be extensible, making it easy for others to add
new tests. The main repositories are:
   * [Client](https://github.com/internet-equity/nm-exp-active-netrics)
   * [Scheduler](https://github.com/internet-equity/netrics)
   * [Dashboard](https://github.com/internet-equity/netrics-dash)
   * Backend (private for security reasons; available on request)


## Data

The initiative collects data from a variety of sources. We currently release
data from our deployments quarterly:
   * [Deployment Data](https://github.com/internet-equity/netrics-data)

## People

The initiative is led by Professors [Nick
Feamster](https://people.cs.uchicago.edu/~feamster/) and [Nicole
Marwell](https://crownschool.uchicago.edu/directory/nicole-p-marwell) at the
University of Chicago. Alexis Schrubbe is the executive director. The full
team is listed [here](https://internetequity.uchicago.edu/about/team).

## Citation

If you use this code or data, please cite the following paper, the Netrics
code, and the Internet Equity Initiative website:

```
@inproceedings{feamster2022benchmarks,
   url = { https://tprcweb.com/ },
   pages = { 1--10 },
   address = { Washington, DC },
   month = { sep },
   year = { 2022 },
   booktitle = { Conference on Communications, Information, and Internet Policy (TPRC) },
   title = { Benchmarks or Equity? A New Approach to Measuring Internet Performance },
   author = { Nick Feamster and Nicole Marwell },
}
```

## Funding

We gratefully acknowledge support from the National Science Foundation (NSF)
and data.org.

## License

All code is released under an Apache 2.0 License. Data is released under
Creative Commons Attribution 4.0 International (CC BY-SA 4.0) license, as below.

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img
alt="Creative Commons License" style="border-width:0"
src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span
xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Netrics Data</span>
by <a xmlns:cc="http://creativecommons.org/ns#"
href="https://internetequity.uchicago.edu/" property="cc:attributionName"
rel="cc:attributionURL">Internet Equity Initiative</a> is licensed under a <a
rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative
Commons Attribution-ShareAlike 4.0 International License</a>.


