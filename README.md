# AET Interview Questionnaire - ETL

The Chinook data model represents a digital media store, including tables for artists, albums, media tracks, invoices, and customers.

Media-related data was created using real data from an Apple iTunes library.
Customer and employee information was created using fictitious names and addresses that can be located on Google maps, and other well formatted data (phone, fax, email, etc.)
Sales information was auto generated using random data for a four year period.

The Chinook sample database includes:

- 11 tables
- A variety of indexes, primary and foreign key constraints
- The addition of new 'TrackMediaType' table. This transformation involves combining information from two separate tables (tracks and media_types) into a single result set.
