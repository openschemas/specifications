# OpenSchema Specifications

Hi friend! These are the openschemas specifications that render at 
[https://openschemas.github.io/specifications](https://openschemas.github.io/specifications)

[![CircleCI](https://circleci.com/gh/openschemas/specifications.svg?style=svg)](https://circleci.com/gh/openschemas/specifications)

![https://github.com/openschemas/spec-template/raw/master/img/hexagon_square_small.png](https://github.com/openschemas/spec-template/raw/master/img/hexagon_square_small.png)

## How to Contribute

Note that we are currently 
The [validator](https://github.com/openschemas/openschemas-python) provided by openschemas-python
is used to test your submissions in continuous integration 
(the [CircleCI link above](https://circleci.com/gh/openschemas/specifications)).
This means that submissions are validated before any pull request is merged. Gotta catch those bugs! :bug:
Instructions below still hold true:

 - To **contribute a new specification**, use the [spec-template](https://www.github.com/openschemas/spec-template)
as a template! If you would like to see a fully connected, working example of this template, please
see the [spec-container](https://www.github.com/openschemas/spec-container) repository. 
You will just need to fork the template repository, generate some text (tsv) files, 
and then connect to continuous integration to do the work for you. The resulting 
content generated by the continuous integration, specifically the *.html file, can then contributed here.
 - To **update a specification**, you have two choices. You can either find the repository it is maintained 
in (for example, the Container* namespace is maintained in 
[spec-container](https://www.github.com/openschemas/spec-container) and then 
re-generate the updated files, and pull request here... OR you **could** just update
the file here. If you have no preference the first is recommended, as we would want changes 
to be represented in the base development location where the *.html file with frontend matter was
programatically generated.

Have any questions, or want to contribute? 
Please don't hesitate to [reach out](https://www.github.com/openschemas/specifications/issues).
