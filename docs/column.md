# column chart
This is a vertical bar chart.

## demo
https://officeofperformancemanagement.github.io/charts/v0/column.html?url=https://www.chattadata.org/resource/nvdi-c4tt.json&data=posted_speed&label=street&limit=10&filter_key=pedestrian_involved&filter_value=Yes


## required params
| name | example | description |
| ---- | ------- | ----------- |
| url  | https://www.example.org/resource/abcd-1234.json | url returning a JSON array |
| data | period_net_activity | key to data values for each array item |
| label | accounting_period_name | name to display for each item |
| data_type | currency | type of data values |
| group | true | group all data values with matching label (like a histogram) |

## optional params
| name | example | description |
| ---- | ------- | ----------- |
| color | %23F8F8F8 | url-escaped color of text in vertical bars |
| currency | USD | if data_type is currency, set this or it defaults to USD. Euros is EUR. |
| order | accounting_period_start_date | key to order by, -key_name reverses it |
| order_data_type | date | data type of ordering field: valid values are "number", "currency", "date" |
| limit | 12 | total number of column to display |
| title | State Sales Tax | title of the chart |
| subtitle | Last 12 Months | subtitle of the chart |
| filter_key | pedestrian_involved | item key to filter on |
| filter_value | Yes | value of item property/key to filter on |

<img width="776" alt="Screenshot 2024-02-28 at 10 50 41 PM" src="https://github.com/officeofperformancemanagement/charts/assets/4313463/61e266c2-7604-485f-8a8a-8e870fc718cb">
