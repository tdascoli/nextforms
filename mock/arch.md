# architecture


[data::json, csv, xls(x)   ]
              |
              V
[mapper::data to answers   ]  ->  [mapper::data to forms   ]
              |                                 |
              V                                 |
[answers                   ]                    |
              A                                 |
              |                                 |
[questions                 ]                    |
              A                                 |
              |                                 |
[forms::json               ]  <-----------------+
              |
              V
[forms::presentation       ]