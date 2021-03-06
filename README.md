Results for the 2015 Scientific Python Survey
---------------------------------------------

This repository is a companion to [this blog post](http://astrofrog.github.io/blog/2015/05/09/2015-survey-results/).

The results so far are contained in the ``results.json`` file in JSON format.
This file will be updated as the results of the survey are processed and
anonymized. The file contains a list of entries, where each entry is a response in the survey. At the moment, this contains 781 responses (there were a few more responses, but these had issues and will be added manually very soon). 

In version 1 (released 9th May 2015), each entry contains:

* ``experience``: how long the respondent has been using Python

* ``fields``: a list of fields that the respondent works in

* ``installations``: a list of dictionaries, where each dictionary
  corresponds to a single installation, which then gives the operating system
  and Python version (and in future, this will give the NumPy, SciPy, and
  Matplotlib versions). The list gives the primary installation first.

* ``why_not_python3``: a list of reasons as to why the respondent is not using Python 3 (if that is the case)

Note that for several of the fields, one of the options is 'Other'.
Respondents were able to provide free-form text descriptions in these cases,
but these data need to first be cleaned up and anonymized before they can be
added here.

### Version history

9 May 2015: Initial version

9 May 2015: Updated to include fields of research parsed from the 'Other' field

### Additional notes

The following fields of research were not present from the original form but
were parsed from the 'Other' field:

* Computer Science
* Mathematics
* Neuroscience
* Biology/Bioinformatics
* Engineering
* Machine Learning
* Linguistics
* Economics
* Psychology







