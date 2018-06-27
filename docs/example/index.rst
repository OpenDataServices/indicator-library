.. _pcWCT:

Indicator: Women's Participation In Training
============================================

.. list-table::
    :header-rows: 0
    :stub-columns: 1
    :widths: 1 3

    * - Indicator Name
      - Women’s Participation in Training 
    * - Indicator ID/Code   
      - Number X.X
    * - Element/ Theme  
      - Social/ Gender
    * - Description 
      - Women attending and completing trainings 
    * - Metric  
      - % of participants that complete trainings who are women
    * - Unit
      - Expressed as percent of total people attending
    * - Report Frequency or Timing 
      - Annually, can be updated as needed
    * - Disaggregation  
      - Data could be disaggregated by regional or municipality level to reduce naming duplications and to determine potential target or focal areas
    * - Benchmarking    
      - UN SDG—5. Gender Equality https://www.un.org/sustainabledevelopment/gender-equality/
    * - Performance Standard   
      - A value of 0.5 indicates that the gender gap is zero or close to zero (gender equity).
    * - Limitations 
      - Would detail any limitations of the synthesized approach



Indicator definition
--------------------

This indicator is defined using JSON Schema. The schema `pcWomenCompletingTraining2.json <../_static/measures/pcWomenCompletingTraining2.json>`_ can be used to validate this indicator.


 
.. jsonschema:: ../../schema/measures/pcWomenCompletingTraining2.json
    :include: code,value

Indicator calculation
---------------------

This indicator builds on two other metrics: 

* nPWT - Training: Female participants
* nTPART - Training: Total Participants
 
If the bullets above are hyperlinks, you can navigate to find more information on collecting these metrics. 

.. jsonschema:: ../../schema/measures/pcWomenCompletingTraining2.json
    :include: numerator,denominator 

Dimensions
----------

.. jsonschema:: ../../schema/measures/pcWomenCompletingTraining2.json
    :include: dimensions

Attributes
----------

.. jsonschema:: ../../schema/measures/pcWomenCompletingTraining2.json
    :include: attributes


Examples
--------

JSON Representation
+++++++++++++++++++

This data can be represented in JSON in the following structure.

.. jsoninclude:: ../../schema/measures/pcWomenCompletingTraining2.json
   :jsonpointer: /example

Tabular representation
++++++++++++++++++++++

This data can be represented in tabular form with the following structure. 

.. jsoninclude-flat:: ../../schema/measures/pcWomenCompletingTraining2.json
    :jsonpointer: /example
    :recursive:
    :ignore_path: /example/metrics/0/

Data entry form (Experimental)
++++++++++++++++++++++++++++++

We can generate example data entry forms using the JSON Schema. 

This is a `static example <http://jeremydorn.com/json-editor/?schema=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&value=N4Igxg9gJgpiBcIAOYDqBhAKiANCAbgIYA2ArnPAAwB0AzHgHakC2MAToQC4RsKiSwEIBgAVU2PETIVaAXzywGEZgEsGXHn3DQKwzCICCAJQkES5BAEZK8kFBWsGAZxURnWpO1dQAyp0JsnEK4yF7QAKIMUMF4AOYwELEcSAAWKmDoEPjshPFasE5gbCpInK4MQgCqDCqcMFAABADSarFQyiGxhABeMHXsWoUpMKxC8W6ErE4hKoplAGYq7NPwANogAEwAbLQArJZbAOwgALqytp7F0H4BnAAiXLoblJaHALQvH5Yhl96RUA86kJnpYABxfL4gWxcTjFABGpDqK1ATggpDYYF0PnR2QAniFUejMZhcZ4hDAnGVmI8obIgAAA&theme=bootstrap2&iconlib=fontawesome4&object_layout=normal&show_errors=interaction>`_

