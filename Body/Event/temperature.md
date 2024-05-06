# Temperature with data granular

Dataset: Temperature Event - Body Health

Data: "temperature_celsius_float"

Data Sources: Garmin

## Frame dataset

![descarga (26)](https://github.com/SalvatoreCordano/DataStructure/assets/147050219/cc6abfd7-c74d-4577-b873-28319b2d5dba)

```Json
{
  "client_uuid": "demoClientUUID",
  "user_id": "demoUserId",
  "version": 2,
  "document_version": 1,
  "auto_detected": false,
  "data_structure": "temperature_event",
  "body_health": {
    "events": {
      "temperature_event": [
        {
          "non_structured_data_array": [
            {}
          ],
          "metadata": {
            "datetime_string": "2023-12-29T21:07:14.402999Z",
            "sources_of_data_array": [
              "Polar"
            ],
            "user_id_string": "demoUserId",
            "was_the_user_under_physical_activity_bool": true
          },
          "temperature": {
            "temperature_avg_object": {
              "temperature_celcius_float": 0,
              "measurement_type_string": "string"
            },
            "temperature_maximum_object": {
              "temperature_celcius_float": 0,
              "measurement_type_string": "string"
            },
            "temperature_minimum_object": {
              "temperature_celcius_float": 0,
              "measurement_type_string": "string"
            },
            "temperature_delta_object": {
              "temperature_celcius_float": 0,
              "measurement_type_string": "string"
            },
            "temperature_granular_data_array": [
              {
                "datetime_string": "2024-04-25T12:01:00.000000Z",
                "temperature_celsius_float": 36.74,
                "measurement_type_string": "normal"
              },
              {
                "datetime_string": "2024-04-25T12:30:53.333333Z",
                "temperature_celsius_float": 36.6,
                "measurement_type_string": "normal"
              },
              {
                "datetime_string": "2024-04-25T13:00:46.666666Z",
                "temperature_celsius_float": 36.76,
                "measurement_type_string": "normal"
              },
              {
                "datetime_string": "2024-04-25T13:30:40.000000Z",
                "temperature_celsius_float": 36.72,
                "measurement_type_string": "normal"
              },
              {
                "datetime_string": "2024-04-25T14:00:33.333333Z",
                "temperature_celsius_float": 36.46,
                "measurement_type_string": "normal"
              },
              {
                "datetime_string": "2024-04-25T14:30:26.666666Z",
                "temperature_celsius_float": 36.47,
                "measurement_type_string": "normal"
              },
              {
                "datetime_string": "2024-04-25T15:00:20.000000Z",
                "temperature_celsius_float": 36.27,
                "measurement_type_string": "normal"
              },
              {
                "datetime_string": "2024-04-25T15:30:13.333333Z",
                "temperature_celsius_float": 37.01,
                "measurement_type_string": "normal"
              },
              {
                "datetime_string": "2024-04-25T16:00:06.666666Z",
                "temperature_celsius_float": 37.01,
                "measurement_type_string": "normal"
              },
              {
                "datetime_string": "2024-04-25T16:30:00.000000Z",
                "temperature_celsius_float": 36.74,
                "measurement_type_string": "normal"
              }
            ]
          }
        }
      ]
    }
  }
}
```
