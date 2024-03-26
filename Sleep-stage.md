# Sleep stage with data non strutured

Dataset: Sleep summary - Sleep Health

Data: "non_structured_data_array"

User: 40 years old

Data Sources: Fitbit

Sleep time: 6 hours 16 mins

Sleep cycles: 4 (There are four entrances and exits in REM sleep)

## Frame dataset

![descarga (4)](https://github.com/SalvatoreCordano/DataStructure/assets/147050219/467dcf5f-0ccf-46d4-a5f5-4668935e3e52)

```Json
{
  "data_structure": "sleep_summary",
  "version": 2,
  "user_id": "6550be7613da7c2bc58ecab8",
  "client_uuid": "8cbc1353-190f-487c-8497-c7fdba1d0248",
  "sleep_health": {
    "summary": {
      "sleep_summary": {
        ...,
        "duration": {
          "sleep_start_datetime_string": "2023-11-11T00:24:30.000",
          "sleep_end_datetime_string": "2023-11-11T06:22:30.000",
          "sleep_date_string": "2023-11-11",
          "sleep_duration_seconds_int": 19140,
          "time_in_bed_seconds_int": 21480,
          "light_sleep_duration_seconds_int": 11340,
          "rem_sleep_duration_seconds_int": 3840,
          "deep_sleep_duration_seconds_int": 3960,
          "time_to_fall_asleep_seconds_int": 0,
          "time_awake_during_sleep_seconds_int": 2340
        },
        ...,
        "non_structured_data_array": [
          {
            "dateOfSleep": "2023-11-11",
            "duration": 21480000,
            "efficiency": 97,
            "endTime": "2023-11-11T06:22:30.000",
            "infoCode": 0,
            "isMainSleep": true,
            "levels": {
              "data": [
                {
                  "dateTime": "2023-11-11T00:24:30.000",
                  "level": "wake",
                  "seconds": 30
                },
                {
                  "dateTime": "2023-11-11T00:25:00.000",
                  "level": "light",
                  "seconds": 1320
                },
                {
                  "dateTime": "2023-11-11T00:47:00.000",
                  "level": "deep",
                  "seconds": 1050
                },
                {
                  "dateTime": "2023-11-11T01:04:30.000",
                  "level": "light",
                  "seconds": 1050
                },
                {
                  "dateTime": "2023-11-11T01:22:00.000",
                  "level": "rem",
                  "seconds": 270
                },
                {
                  "dateTime": "2023-11-11T01:26:30.000",
                  "level": "light",
                  "seconds": 30
                },
                {
                  "dateTime": "2023-11-11T01:27:00.000",
                  "level": "rem",
                  "seconds": 270
                },
                {
                  "dateTime": "2023-11-11T01:31:30.000",
                  "level": "light",
                  "seconds": 1440
                },
                {
                  "dateTime": "2023-11-11T01:55:30.000",
                  "level": "deep",
                  "seconds": 1950
                },
                {
                  "dateTime": "2023-11-11T02:28:00.000",
                  "level": "light",
                  "seconds": 360
                },
                {
                  "dateTime": "2023-11-11T02:34:00.000",
                  "level": "rem",
                  "seconds": 270
                },
                {
                  "dateTime": "2023-11-11T02:38:30.000",
                  "level": "light",
                  "seconds": 30
                },
                {
                  "dateTime": "2023-11-11T02:39:00.000",
                  "level": "wake",
                  "seconds": 300
                },
                {
                  "dateTime": "2023-11-11T02:44:00.000",
                  "level": "light",
                  "seconds": 3480
                },
                {
                  "dateTime": "2023-11-11T03:42:00.000",
                  "level": "deep",
                  "seconds": 660
                },
                {
                  "dateTime": "2023-11-11T03:53:00.000",
                  "level": "light",
                  "seconds": 270
                },
                {
                  "dateTime": "2023-11-11T03:57:30.000",
                  "level": "rem",
                  "seconds": 2340
                },
                {
                  "dateTime": "2023-11-11T04:36:30.000",
                  "level": "light",
                  "seconds": 540
                },
                {
                  "dateTime": "2023-11-11T04:45:30.000",
                  "level": "rem",
                  "seconds": 420
                },
                {
                  "dateTime": "2023-11-11T04:52:30.000",
                  "level": "light",
                  "seconds": 3360
                },
                {
                  "dateTime": "2023-11-11T05:48:30.000",
                  "level": "deep",
                  "seconds": 480
                },
                {
                  "dateTime": "2023-11-11T05:56:30.000",
                  "level": "light",
                  "seconds": 210
                },
                {
                  "dateTime": "2023-11-11T06:00:00.000",
                  "level": "rem",
                  "seconds": 390
                },
                {
                  "dateTime": "2023-11-11T06:06:30.000",
                  "level": "wake",
                  "seconds": 630
                },
                {
                  "dateTime": "2023-11-11T06:17:00.000",
                  "level": "light",
                  "seconds": 120
                },
                {
                  "dateTime": "2023-11-11T06:19:00.000",
                  "level": "wake",
                  "seconds": 210
                }
              ],
            }
          }
        ]
      }
    }
  }
}
