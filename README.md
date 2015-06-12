# UKBankHolidayMySQL
MySQL table with data for UK Bank Holidays between 2005 - 2030


## Table Design

| column            | info  |
| ----------------- |:-------------:|
| date              | Y-m-d |
| timestamp         | timestamp at midnight GMT |
| timestamp_end     | timestamp 23:59:59 GMT |
| uk_holiday        | boolean |
| next_business_day | Y-m-d of next business day (not weekend or UK Bank Holiday) |
| weekend           | boolean |
| year              |  |
| quarter           |  |
| month             |  |
| week              |  |
| day               |  |
| day_of_year       |  |
| day_of_week       | 0 = Sunday, 6 = Saturday |
 
