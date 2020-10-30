# Power Theft Identification System

### Introduction

> Energy or Electricity theft is the criminal practice of stealing electrical power -Wikipedia

Generally, we can classify electricity loses:
- Technical  Losses
- Non_Techbsl Loses
Technical losses are losses associated with the standard transmission/distribution and transport of electricity. Technical lose is described as usual because it is inevitable, especially as systems are not perfect.

On the other hand, Non-technical losses are principally losses incurred by equipment failure. Lightning, depreciation or neglect could damage Electrical equipment. Another class of non-technical losses could be attributed to misrepresentation of technical information due to error in accounting and record-keeping in technical loss calculation and non-payment of electricity bill by a consumer.

Electricity theft is a global phenomenon, but it is prevalent in developing countries. Whichever way the phenomenon is analysed,  electricity theft leads to loss of revenue, scarce revenue the utility providers need for maintenance and expansion. Power theft is a problem that requires effective solution and resolution and machine learning shines as a veritable tool.

### Statement of Problem
A power sector company wants to trace the consumption of electricity by each consumer and identify if any power theft is happening at the customer's end. Can a power leak or theft be traced to utility customer?

### Data
Data is a critical ingredient in any machine learning soup. Our data is a time series record of load supply and load consumption under a sub-metering system.
Sub-metering is a system that allows a landlord, property management firm, condominium or homeowners association or multi-tenant property to bill tenants for their individual metered utility usage.
Our data dictionary is as follows:


Variable| Data Type|Meaning
--------|-----------|----------
**Customer ID**|Integer/string|Unique stream of numbers that identifies each utility customer
**Date**|datetime|Record of the date which include day month and year
**Time**|time|Record of the time which involve the Hour, Minutes, Seconds and Nano seconds
**Global Active Power**|Float|This is the amount of power that is converted into useful output.It unit of measurement is kilowatts(kW).it is also called actual power or working power.
**Global Reactive Power**|Float|It is the power which flows back and forth the source and load. It is measured in KVA.It is also called useless power
**Voltage**|Float|It is the difference in electricity potential between two points. its expressed as *volts*
**Global Intensity**|Float|Is the power transfered per unit area
**Sub-mettering_1**|Integer|Apartment one sub-meter units of electricity usage. Its often expressed in KWh
**Sub-mettering_2**|Integer|Apartment two sub-meter units of electricity usage. Its often expressed in KWh
**Sub-mettering_3**|Integer|Apartment three sub-meter units of electricity usage. Its often expressed in KWh


 *For details check the master branch for the related Notebook*
