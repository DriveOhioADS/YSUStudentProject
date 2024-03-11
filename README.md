# YSUStudentProject

A project partnership with the Youngstown State University Data Mine.

## Data

We assume users of these notebooks have properly setup AWS database access.

To speed things up, we often save queried data by groupMetadataID as .csv files in a ``./data`` folder, sorted by topic (i.e. chassis, best_pose). Once a query is ran, appropriate folders will be created automatically.

Many notebooks will first attempt to use these .csv files, preventing repeat queries to save time. If the data does not yet exist locally, a query will follow and data will be saved for future use.

__NOTE: Chassis queries take time, often 5+ minutes.__

## Spring '23 Team Members

- Jay Kerns (Instructor)
- Emmanuel Asamanyuah
- Chris Bluhm
- Vincent Hepola (TA)
- Felix Kina
- Anthony Micco
- Nicholas Winsen
- Tyler Wood
