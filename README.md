# Nunis Running Analytics
An analytics solution that generates opinionated visualizations from historical running data, leveraging an array of cloud native technologies in Google Cloud. Opinions are my own.

This is the master repo for the project. The [Release Notes](release-notes.md) bind the numerous other bespoke repos that implement components of the solution. This is a work in progress and not fully functional - start there for the latest.

The latest conceptual diagram of what I'm working towards is below:

![Nunis Running Analytics](diagrams/Nunis%20Running%20Analytics%20-%20Concept%20Diagram%20-%201.0%20-%20Initial%20Concept.png)


## Background and Problem Statement
I've been tracking my runs since the day I acquired my first smartphone, which was an iPhone 4 in 2011. I started with [Endomondo](https://www.endomondo.com/), but over the years, alternated between this and [Strava](https://www.strava.com/), using [Tapiriik](https://tapiriik.com/) to sync my runs between the services so that no matter what I used to track a run, both services had a complete copy of my historical running data. Data mobility is important to me, and I'm currently all-in on Strava because of [their open API](https://developers.strava.com/).

The statistics features of these platforms are okay, but basic. They've never provided insight that's important to me. I've built my own makeshift solutions in Google Sheets, which require me to manually enter my running data into a table. The upkeep is categorically toil, and sheet charting isn't very exciting. There has to be a better way.

With the ubiquity of public cloud computing (and the resulting democratization of cutting edge technologies as a service), there is now a much better way!


## Vision and Objectives
The vision for Nunis is to create a world where I'm no longer manually entering my running data into a table, and have more meaningful analytics at my fingertips. Since I've worked exclusively with Google Cloud as a services partner for the last 2+ years of my professional career, I'm also using this exercise as an opportunity to flex some skills that I already have, and to dig deeper into some areas that I haven't had the opportunity to explore.

Tactical objectives are to apply best practices for modern, cloud native application development. This includes, but isn't limited to:
- Creation of a NoOps environment through the use of serverless and elastic services.
- Automated, repeatable deployability; the entire solution can be torn down and recreated at will.
- Trunk based development into a single environment, to maximize feature velocity and the tension to have working code at all times.

Most importantly, this is a demonstration that public cloud services have evolved IT to the point that a single individual with the knowledge and persistence can build across the full stack of a solution. Infrastructure, app dev, data, analytics - nothing is off limits.


## License
GPL 3.0 - See [LICENSE](LICENSE) for more information.
