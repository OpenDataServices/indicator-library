.. _pcWCT:

Indicator: Women's Participation In Training
=================

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

This indicator is defined using JSON Schema. The schema `pcWomenCompletingTraining2.json </_static/measures/pcWomenCompletingTraining2.json>`_ can be used to validate this indicator.


 
.. jsonschema:: ../../schema/measures/pcWomenCompletingTraining2.json
    :include: code,value

Indicator calculation
--------------------

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


