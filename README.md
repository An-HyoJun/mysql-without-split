# MySQL without Page Split

- MySQL 5.7.24
- TPC-C Order-Line 페이지들의 split을 막기 위해, 페이지의 free space 크기를 증가시킴
  - Default: 6.25%
  - Tuning: 10 ~ 15%
- Order-Line tablespace ID 자동으로 setting
