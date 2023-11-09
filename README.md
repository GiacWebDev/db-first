used cars - dealer
===

| id                        | INT - AUTO INCREMENT, NOT NULL - PRIMARY KEY

| model                     | VARCHAR (20) - NOT NULL
 
| brand                     | VARCHAR (15) - NOT NULL

| production_year           | YEAR - NOT NULL

| mileage                   | DOUBLE (7,3) - NOT NULL

| price                     | DECIMAL (10,2) - NULL

| color                     | VARCHAR (20) - NULL

| fuel_type                 | VARCHAR (20) - NULL

| transmission              | VARCHAR (20) - NULL

| listing_date              | DATE - NULL

| average_consumption       | DECIMAL (5,2) - NULL

| seats                     | SMALLINT - NOT NULL

| owners_count              | SMALLINT - NULL

| condition                 | VARCHAR (50) - NOT NULL - DEFAULT ('BUONO STATO')

| lenght                    | DOUBLE (6,3) - NULL

| width                     | DOUBLE (7,4) - NULL

| power                     | SMALLINT - NOT NULL

| available                 | CHAR (1) - NOT NULL - DEFAULT ('1')
