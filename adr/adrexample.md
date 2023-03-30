# Choosing a programming framework for our new Web Application FancyWebAppName

## Context and Problem Statement

[Describe the context and problem statement, e.g., in free form using two to three sentences. You may want to articulate the problem in form of a question.]
Our upcoming new application FancyWebAppName is in the preliminary stages of developments. We require a programming framework that is extensible and will
enable our developers to delivery high quality modern software in a typical cloud environment.

## Decision Drivers <!-- optional -->

Our old monolithic desktop application is beginning to show its age.
Many of our bug fixes are around high coupled architecture.

## Considered Options

ASP.NET, using Razor Pages for Front-End and Entity Framework for Back-end.
Node.js for front-end and back-end.

## Decision Outcome

Chosen option: ASP.NET due to our current development team being strong in C# development.

### Positive Consequences <!-- optional -->

Possibility to move to MVC pattern in future instead of Razor Pages.
Extensibility via NuGet packagaes.

### Negative Consequences <!-- optional -->

Stuck within the .NET ecosystem.

## Pros and Cons of the Options <!-- optional -->

### [option 1]

[example | description | pointer to more information | …] <!-- optional -->

* Good, because our developers are familiar with C#.
* Good, because Razor pages are quick and easy to use and make for prototyping.
* Bad, because we will be stuck within the .NET ecosystem.
<!-- numbers of pros and cons can vary -->

### Node.js

[example | description | pointer to more information | …] <!-- optional -->

* Good, because there is a multitude of sources of information avaiable
* Good, because it is lightweight
* Bad, because our developers may require significant upskilling
<!-- numbers of pros and cons can vary -->


