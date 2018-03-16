---
layout: default
title: "Cool Tools"
excerpt: "awesome tools I've used"
toc: true
permalink: /cool-tools/
---
<style>
.initial-content
{
    font-size:0.8em;
    padding-left:35%;
    padding-right:35%
}
H1 {
    font-size: 18px;
    font-weight: bold;
    letter-spacing: 1.4px;
    border-bottom: solid 1px #006600;
    text-transform: uppercase;
}
H2 {
    font-size: 14px;
    font-weight: normal;
    letter-spacing: 1.2px;
}
P, BLOCKQUOTE {
    font-size: 11px;
    line-height: 1.5;
    letter-spacing: .25px;
}
BLOCKQUOTE {
    font-style: italic;
    color: #444444;
    letter-spacing: 1.25px;
    line-height: 1.5;
    background: #EEEEEE;
    padding: 5px;
    margin: auto 15px;
}
A {
    color: #006600;
}
ABBR {
    border-bottom: dotted 1px #006600;
}

</style>
# SQL PERFORMANCE TUNING

_Note - all licensing costs are for general reference only, look at supplier for up to date pricing metrics._

## [Sql Sentry Plan Explorer](https://www.sheldonhull.com/search?q=ants%20performance) $0

Better review of plan adjustments, and allows filtering plans for easier review of the visual diagram. [They made the pro tool free in 2016](http://bit.ly/2qphhW7), making it one of the best options for easily reviewing plan performance changes

## [StatisticsParser](http://bit.ly/2qp2U40) $0

Scalability testing for query changes can be difficult to guage with execution plans and elapsed execution time. Reads/Write summary from setting "statistics io, time on" can help better assess the potential percent increase/decrease in performance better than just using elapsed time.

## [SqlPrompt](http://bit.ly/1QSfMUl) $369

RedGate's premiere sql-server intellisense replacement that works in Visual Studio and SSMS. This has better snippet handling, automatic formatting that is brilliantly implemented, and a great productivity enhancements to help workflow. As a member of the Friends of Red Gate program, I'm a staunch supporter of this fantastic tool.

## [dbForge Event Profiler](https://www.sheldonhull.com/search?q=ants%20performance) $0

A welcome replacement for running Sql Profiler, this tool leverages Extended events, but allows easily working with the results in a nice sortable grid. A few minor bugs on not saving some filters, but for the most part even with those it's a fantastic tool and my favorite trace utility.

## [RedGate ANTS Performance Profiler](http://bit.ly/2uN4gec) $745

A great way to immediately identify what is making an application run slow. Is it the database calls or bit of unoptimized code that is bringing down the internet? This is a great tool to find that out. For a full review, take a look at my article on it by looking at [ANTS Performance Profiler](https://www.sheldonhull.com/search?q=ants%20performance)