# Saturation with data granular

Dataset: Sleep Summary - Sleep Health

Data: "saturation"

Data Sources: Apple Health

## Frame dataset

![descarga (9)](https://github.com/SalvatoreCordano/DataStructure/assets/147050219/13e06d2f-35a2-433b-a539-837a08c51fc7)

```Json
{
  "version": 2,
  "data_structure": "sleep_summary",
  "client_uuid": "c66feb51-ed5b-44d3-9565-fdbc4317fb12",
  "user_id": "65dda4dd9cc12d66a3b9d4a9",
  "sleep_health": {
    "summary": {
      "sleep_summary": {
        "duration": {
          "sleep_start_datetime_string": "2024-02-23T17:47:30.000000+02:00",
          "sleep_end_datetime_string": "2024-02-24T01:28:42.364000+02:00",
          "sleep_date_string": "2024-02-24T00:00:00.000000Z",
          "sleep_duration_seconds_int": 22050,
          "time_in_bed_seconds_int": 49812,
          "light_sleep_duration_seconds_int": 14130,
          "rem_sleep_duration_seconds_int": 5250,
          "deep_sleep_duration_seconds_int": 2670,
          "time_to_fall_asleep_seconds_int": 0,
          "time_awake_during_sleep_seconds_int": 1500
        },
        ...
        "saturation_granular_data_array": [
            {
              "interval_duration_seconds_float": null,
              "saturation_percentage_int": 93,
              "datetime_string": "2024-02-23 18:45:27.487000+02:00"
            },
            {
              "interval_duration_seconds_float": null,
              "saturation_percentage_int": 94,
              "datetime_string": "2024-02-23 18:45:52.862000+02:00"
            },
            {
              "interval_duration_seconds_float": null,
              "saturation_percentage_int": 93,
              "datetime_string": "2024-02-23 19:58:34.096000+02:00"
            },
            {
              "interval_duration_seconds_float": null,
              "saturation_percentage_int": 94,
              "datetime_string": "2024-02-23 20:57:41.814000+02:00"
            },
            {
              "interval_duration_seconds_float": null,
              "saturation_percentage_int": 94,
              "datetime_string": "2024-02-23 21:27:42.652000+02:00"
            },
            {
              "interval_duration_seconds_float": null,
              "saturation_percentage_int": 94,
              "datetime_string": "2024-02-23 21:57:43.497000+02:00"
            },
            {
              "interval_duration_seconds_float": null,
              "saturation_percentage_int": 91,
              "datetime_string": "2024-02-23 22:30:56.744000+02:00"
            },
            {
              "interval_duration_seconds_float": null,
              "saturation_percentage_int": 94,
              "datetime_string": "2024-02-23 23:36:35.587000+02:00"
            },
            {
              "interval_duration_seconds_float": null,
              "saturation_percentage_int": 95,
              "datetime_string": "2024-02-24 00:34:50.687000+02:00"
            },
            {
              "interval_duration_seconds_float": null,
              "saturation_percentage_int": 94,
              "datetime_string": "2024-02-24 01:04:51.421000+02:00"
            }
          ]
```
