# Breathing with data granular

Dataset: Sleep Summary - Sleep Health

Data: "breathing"

Data Sources: Garmin

## Frame dataset

![image](https://github.com/SalvatoreCordano/DataStructure/assets/147050219/a73ed570-5627-45b4-9462-38b3b6239db3)


```Json
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
        "breathing": {
          "breaths_minimum_per_min_int": 16,
          "breaths_avg_per_min_int": 18,
          "breaths_maximum_per_min_int": 23,
          "breathing_granular_data_array": [
            {
              "breaths_per_min_int": 17,
              "datetime_string": "2024-02-24 01:20:03.567000+02:00"
            },
            {
              "breaths_per_min_int": 17,
              "datetime_string": "2024-02-24 01:10:32.949000+02:00"
            },
            {
              "breaths_per_min_int": 18,
              "datetime_string": "2024-02-24 01:01:32.368000+02:00"
            },
            {
              "breaths_per_min_int": 20,
              "datetime_string": "2024-02-24 00:45:31.346000+02:00"
            },
            {
              "breaths_per_min_int": 20,
              "datetime_string": "2024-02-24 00:43:01.189000+02:00"
            },
            {
              "breaths_per_min_int": 17,
              "datetime_string": "2024-02-24 00:26:00.131000+02:00"
            },
            {
              "breaths_per_min_int": 19,
              "datetime_string": "2024-02-24 00:18:59.702000+02:00"
            },
            {
              "breaths_per_min_int": 18,
              "datetime_string": "2024-02-24 00:12:29.306000+02:00"
            },
            {
              "breaths_per_min_int": 17,
              "datetime_string": "2024-02-23 23:59:58.534000+02:00"
            },
            {
              "breaths_per_min_int": 17,
              "datetime_string": "2024-02-23 23:44:27.601000+02:00"
            },
            {
              "breaths_per_min_int": 16,
              "datetime_string": "2024-02-23 23:38:57.269000+02:00"
            },
            {
              "breaths_per_min_int": 17,
              "datetime_string": "2024-02-23 23:28:26.624000+02:00"
            },
            {
              "breaths_per_min_int": 16,
              "datetime_string": "2024-02-23 23:23:56.343000+02:00"
            },
            {
              "breaths_per_min_int": 20,
              "datetime_string": "2024-02-23 23:07:25.294000+02:00"
            },
            {
              "breaths_per_min_int": 17,
              "datetime_string": "2024-02-23 23:02:55.010000+02:00"
            },
            {
              "breaths_per_min_int": 16,
              "datetime_string": "2024-02-23 22:53:54.451000+02:00"
            },
            {
              "breaths_per_min_int": 19,
              "datetime_string": "2024-02-23 22:42:53.800000+02:00"
            },
            {
              "breaths_per_min_int": 17,
              "datetime_string": "2024-02-23 22:26:22.842000+02:00"
            },
            {
              "breaths_per_min_int": 18,
              "datetime_string": "2024-02-23 22:15:22.214000+02:00"
            },
            {
              "breaths_per_min_int": 17,
              "datetime_string": "2024-02-23 22:12:22.040000+02:00"
            },
            {
              "breaths_per_min_int": 17,
              "datetime_string": "2024-02-23 21:59:21.132000+02:00"
            },
            {
              "breaths_per_min_int": 18,
              "datetime_string": "2024-02-23 21:52:20.786000+02:00"
            },
            {
              "breaths_per_min_int": 17,
              "datetime_string": "2024-02-23 21:37:19.841000+02:00"
            },
            {
              "breaths_per_min_int": 17,
              "datetime_string": "2024-02-23 21:24:49.032000+02:00"
            },
            {
              "breaths_per_min_int": 21,
              "datetime_string": "2024-02-23 21:20:48.773000+02:00"
            },
            {
              "breaths_per_min_int": 17,
              "datetime_string": "2024-02-23 21:05:17.775000+02:00"
            },
            {
              "breaths_per_min_int": 18,
              "datetime_string": "2024-02-23 21:03:17.646000+02:00"
            },
            {
              "breaths_per_min_int": 17,
              "datetime_string": "2024-02-23 20:50:46.843000+02:00"
            },
            {
              "breaths_per_min_int": 18,
              "datetime_string": "2024-02-23 20:42:46.334000+02:00"
            },
            {
              "breaths_per_min_int": 19,
              "datetime_string": "2024-02-23 20:29:45.513000+02:00"
            },
            {
              "breaths_per_min_int": 19,
              "datetime_string": "2024-02-23 20:17:44.763000+02:00"
            },
            {
              "breaths_per_min_int": 20,
              "datetime_string": "2024-02-23 20:07:44.168000+02:00"
            },
            {
              "breaths_per_min_int": 21,
              "datetime_string": "2024-02-23 20:00:13.721000+02:00"
            },
            {
              "breaths_per_min_int": 20,
              "datetime_string": "2024-02-23 19:45:12.792000+02:00"
            },
            {
              "breaths_per_min_int": 18,
              "datetime_string": "2024-02-23 19:41:42.575000+02:00"
            },
            {
              "breaths_per_min_int": 20,
              "datetime_string": "2024-02-23 19:28:11.737000+02:00"
            },
            {
              "breaths_per_min_int": 20,
              "datetime_string": "2024-02-23 19:22:11.364000+02:00"
            },
            {
              "breaths_per_min_int": 21,
              "datetime_string": "2024-02-23 19:11:40.713000+02:00"
            },
            {
              "breaths_per_min_int": 20,
              "datetime_string": "2024-02-23 18:58:39.912000+02:00"
            },
            {
              "breaths_per_min_int": 23,
              "datetime_string": "2024-02-23 18:50:09.391000+02:00"
            }
          ],
```
