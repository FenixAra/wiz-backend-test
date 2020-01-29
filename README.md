# Wiz Backend test

Given a list of ports, create a schedule engine for which handles all shipping schedules. Each shipping schedule has a list of ports to visit in order and the date (start and end). Example schedules:
      Ports                                 start               end
1. Chennai -> Kolkata                     8-Aug-2019         17-Aug-2019
2. Chennai -> Visakhapatnam -> Kolkata    11-Oct-2019        22-Oct-2019
3. Kolkata -> Mumbai                      22-Aug-2019        30-Aug-2019

It should provide the following features:
1. Create a schedule
2. Update a schedule
3. Get list of schedules given from port, to port and date. It can a combination two schedules as well. If to port is part of the schedule then it should also be included.

Examples:

If the from port is Chennai and Mumbai
It should list *schedule 1 + schedule 3* and *schedule 2+schedule 3*

If the from port is Chennai and Visakhapatnam
It should list *Schedule 2*.


List of ports:
https://docs.google.com/spreadsheets/d/10TXO_dTlUe3-c96mLlziTPuuDjoklFMLYkghX__P3w8/edit?usp=sharing



