# Charlie on the MTA

*"He may ride forever 'neath the streets of Boston..."*

Suppose we have a subway system with the following lines and stops:

* **Red Line**
  * Alewife
  * Davis
  * Porter
  * Harvard
  * Central
  * Kendall/MIT
  * Park Street
  * South Station
* **Green Line**
  * Haymarket
  * Government Center
  * Park Street
  * Boylston
  * Arlington
  * Copley
* **Orange Line**
  * North Station
  * Haymarket
  * Park Street
  * State Street
  * Downtown Crossing
  * Chinatown
  * Tufts Medical Center

All lines intersect at **Park Street**, but not at any other stops. Unlike in real life, the "Haymarket" on the Green Line and the "Haymarket" on the Orange Line are two separate, unconnected stops.

Given this subway system, write a Ruby program that prompts the user for an "origin" stop and a "destination" stop, and tells them the number of stops they would have to make on that journey. For instance, traveling from Central to Copley would be 5 stops.

## Instructions

Refer to the instructions in the [Guess the Number homework](https://github.com/ga-wdi-boston/wdi_1_ruby_hw_number_guess) for the general steps involved in completing and turning in assignments.

## Grading

* **(2)** Program has the subway system defined with appropriate data structures
* **(1)** Program can find the distance between two stops on the same line
* **(2)** Program can find the distance between two stops on different lines
* **(1)** Program gives the correct distance in edge cases (e.g. route starts and ends at the same stop, route starts or ends at Park Street)
* **(1)** Stops and lines can be added, removed, or rearranged in your code without making any changes to the route-finding logic (within reason &ndash; every line must intersect at a single common stop)
* **(1)** Repository has several logical commits with descriptive messages
* **(2)** Code uses correct indentation/style and descriptive variable names

## Bonuses

* **(1)** Add methods to your madness! We haven't fully covered defining your own methods yet, and technically none are required for this assignment. However, you might have noticed some places in your code that are doing the same thing multiple times, but with slightly different data. Introduce a method or two to resolve this duplication.

### Additional Reading

* [Charlie on the MTA](http://en.wikipedia.org/wiki/M.T.A.)
