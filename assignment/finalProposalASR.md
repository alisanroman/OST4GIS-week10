# Identifying Community Development Financing Gaps

A proposal by Alexandra San Roman the final project for CPLN 692 - Open Source Tools for GIS, Spring 2019.

## Problem / Question

Community development financing has a storied history. Beginning with the of banks in the 1970s and the passage of the Community Reinvestment Act (CRA) in 1977. The CRA sought to address discrimination in loans made to individuals and businesses from low and moderate income neighborhoods. The Act mandates that all banking institutions that receive Federal Deposit Insurance Corporation (FDIC) insurance be evaluated by Federal banking agencies to determine if the bank offers credit in all communities in which they are chartered to do business.

Federal regulations dictate agency conduct in evaluating a bank's compliance in five performance areas, comprising twelve assessment factors. This examination culminates in a rating and a written report that becomes part of the supervisory record for that bank.

An institution's CRA compliance record is taken into account by the banking regulatory agencies when the institution seeks to expand through merger, acquisition or branching. The law does not mandate any other penalties for non-compliance with the CRA.

This application will identify the banks across the nation that have a history of failing their CRA compliance tests. It will also show the CDFIs providing services within the bank's chartered areas and suggest an asset allocation from the bank to the CDFI.

Ultimately, this application will optimize community development investments by connecting capital to high-performing CDFIs, who in turn improve the lives of low-wealth individuals in communities across America.

## The data

This application will combine several sources.
1. Bank locations and CRA ratings over time ([from FFEIC](https://www.ffiec.gov/craratings/Rtg_spec.html)).
2. CDFI locations and basic data ([from the CDFI Fund at the Treasury](https://www.cdfifund.gov/Documents/Forms/DataReleases.aspx?SortField=CDFI_x0020_Publish_x0020_Year&SortDir=Desc&Order=4)).
3. TIGER shapefiles for connecting services areas across both institutions.

## Technologies used

*Still figuring this one out*

Which technologies covered in class (or discovered on your own!) do you
plan to use? How do you anticipate using each of these technologies?

Review the APIs/online examples of leaflet, turf, jQuery, underscore (or
any library not explicitly covered in class) for functions/uses which
you'd like to explore. Briefly describe how you might use them.

## Design spec

#### User experience

At a high level, this tool will be used by banks and CDFIs to connect for the mutually-beneficial purpose of improving the CRA rating and increasing investment capacity. I don't know of any website/application examples in the wild to which I can compare to my final. 

#### Layouts and visual design

So far, we've built all our applications with a side bar for
representing non-map content and navigation. This is not the only
successful design. Extra content could be displayed in a top bar,
through modals, through side bars on both sides, and any combination of
these as well as a number not mentioned. Try to describe your
application's visual layout. Conceptually (no need for extensive CSS
here), what will this design require?

## Anticipated difficulties

Thinking about weaknesses can be useful. What do you anticipate being
most difficult about this project? How will you attempt to cope with
these difficulties? For example, asynchronous behavior (ajax, events)
are hard to use and think about. Global variables are a strategy for
coping with that difficulty by breaking data out of the asynchronous
context.

## Missing pieces

We've only managed to scratch the surface of the available technologies
by which you could construct an application. What use-cases haven't we covered
that you think would be useful? What technologies not covered seem exciting to
you (you don't necessarily have to fully understand what they're for,
this is a chance for you to get our help interpreting a technology's
purpose/usage).
