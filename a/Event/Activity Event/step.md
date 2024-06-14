# Step with data granular

Dataset: Activity Event - Physical Health

Data: "step"

Data Sources: Garmin

## Frame dataset

![descarga (13)](https://github.com/SalvatoreCordano/DataStructure/assets/147050219/b1956893-10e4-46b6-8d94-0b540c4c93c1)


```Json
{
  "version": 2,
  "data_structure": "activity_event",
  "client_uuid": "5f2642d2-07fe-4688-b836-9bbe2faeb13b",
  "user_id": "65fa032c281a306e70394d32",
  "physical_health": {
    "events": {
      "activity_event": [
        {
          "metadata": {
            "datetime_string": "2024-03-19T14:54:02.000000-06:00",
            "user_id_string": "65fa032c281a306e70394d32",
            "sources_of_data_array": [
              "Garmin"
            ],
            "was_the_user_under_physical_activity_bool": true
          },
          "activity": {
            "activity_start_datetime_string": "2024-03-19T14:54:02.000000-06:00",
            "activity_end_datetime_string": "2024-03-19T15:24:38.000000-06:00",
            "activity_duration_seconds_int": 1836,
            "activity_type_name_string": "Running",
            ...
          },
          ...
          "distance": {
            "steps_int": 5106,
            "steps_granular_data_array": [
              {
                "steps_int": 84,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-19T14:54:37.000000-06:00"
              },
              {
                "steps_int": 85,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-19T14:55:20.000000-06:00"
              },
              {
                "steps_int": 86,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-19T14:56:06.000000-06:00"
              },
              {
                "steps_int": 85,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-19T14:57:04.000000-06:00"
              },
              {
                "steps_int": 85,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-19T14:58:09.000000-06:00"
              },
              {
                "steps_int": 85,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-19T14:58:56.000000-06:00"
              },
              {
                "steps_int": 85,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-19T15:00:02.000000-06:00"
              },
              {
                "steps_int": 84,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-19T15:01:00.000000-06:00"
              },
              {
                "steps_int": 84,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-19T15:01:51.000000-06:00"
              },
              {
                "steps_int": 84,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-19T15:03:01.000000-06:00"
              },
              {
                "steps_int": 84,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-19T15:04:12.000000-06:00"
              },
              {
                "steps_int": 85,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-19T15:05:16.000000-06:00"
              },
              {
                "steps_int": 82,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-19T15:06:15.000000-06:00"
              },
              {
                "steps_int": 83,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-19T15:07:27.000000-06:00"
              },
              {
                "steps_int": 84,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-19T15:08:37.000000-06:00"
              },
              {
                "steps_int": 82,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-19T15:09:43.000000-06:00"
              },
              {
                "steps_int": 85,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-19T15:10:55.000000-06:00"
              },
              {
                "steps_int": 85,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-19T15:12:06.000000-06:00"
              },
              {
                "steps_int": 83,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-19T15:13:15.000000-06:00"
              },
              {
                "steps_int": 84,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-19T15:14:06.000000-06:00"
              },
              {
                "steps_int": 85,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-19T15:15:15.000000-06:00"
              },
              {
                "steps_int": 84,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-19T15:16:20.000000-06:00"
              },
              {
                "steps_int": 84,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-19T15:17:24.000000-06:00"
              },
              {
                "steps_int": 84,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-19T15:18:29.000000-06:00"
              },
              {
                "steps_int": 84,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-19T15:19:41.000000-06:00"
              },
              {
                "steps_int": 84,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-19T15:20:53.000000-06:00"
              },
              {
                "steps_int": 83,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-19T15:22:05.000000-06:00"
              },
              {
                "steps_int": 82,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-19T15:23:14.000000-06:00"
              },
              {
                "steps_int": 84,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-19T15:24:24.000000-06:00"
              }
            ],
```
