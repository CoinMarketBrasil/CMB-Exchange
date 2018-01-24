# CMB - EXchange 

[![Build Status](https://travis-ci.org/txbits/txbits.svg?branch=master)](https://travis-ci.org/txbits/txbits)

An open source crypto currency exchange

https://www.coinmarketbrasil.com.br

## Dev environment setup TL;DR

1. Get `jdk-8`
1. Get postgres 9.3+ running on `localhost` with database name `txbits_testnet`, superuser `user` and password `password`
1. Run `./txbits.sh run`
1. Log in at `http://localhost:9000` as `teste@teste.com` with password `1234567890teste`
1. To run unit tests, create a database named `exchange_test` and run `./exchange.sh test`


## License

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

-----------

Copyright (C) 2017-2018  Rafael Ribeiro & Emily Mils
