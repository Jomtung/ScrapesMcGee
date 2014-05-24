Pytyhon Scraper
===============

Largely patterned after the class from Udacity on how to build a web crawler in python, this scraper is 
a basic design meant to pull all text out of a web page and separate the link text from the other text.  Instead of
continuing onto the next page, this scraper is a module designed to test one page at a time.  This part will be a function
that the main web crawler uses.

Once the separation between link and text occurs, then a scoring pattern would emerge and be linked to a relative 
data structure used for storing the unstructured text.  Once the data structure is applied and the text stored
we may re evaluate the raw string patterns for data and meta data matching patterns that perform various metrics to 
correlate the raw patterns with common use cases.

The second paragraph is more of a computation check after the data has been stored.  The computation check may be useful for
a number or reasons, including pre audit validations, data intregrity and quality assurance, business and scientific metric
standardization applications, complex rating synchronization, and a number of other gold standard methods for 
checking/evaluating/optimizing data instead of looking at the source link from a time machine laptop and reworking the
entire process.  It seems complicated but is a robustness required for any production application.  However, this part should
only be an interface to the general computation check engine.  Requires a simple computation engine to be built or
building in parallel.
