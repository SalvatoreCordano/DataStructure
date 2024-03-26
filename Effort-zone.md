# Effort zone with data granular

Dataset: Activity Event - Physical Health

Data: Heart rate - HR granular data array

Data Sources: Garmin

User: 40 years old

Heart rate max: 180 bpm

## Frame dataset

![descarga (3)](https://github.com/SalvatoreCordano/DataStructure/assets/147050219/dd8493a0-07c3-4f65-b018-548a01b366ff)

```Json
{
  "version": 2,
  "data_structure": "activity_event",
  "client_uuid": "5eed48d8-f73b-4974-b250-9017d561af22",
  "user_id": "65c09a301b8e14c593ce1ab0",
  "physical_health": {
    "events": {
      "activity_event": [
        {
          ...
          "activity": {
            "activity_start_datetime_string": "2024-02-05T08:54:28.000000+01:00",
            "activity_end_datetime_string": "2024-02-05T09:19:46.000000+01:00",
            ...
          },
          ...,
          "heart_rate": {
            "hr_granular_data_array": [
              {
                "hr_bpm_int": 92,
                "datetime_string": "2024-02-05T08:54:28.000000+01:00"
              },
              {
                "hr_bpm_int": 86,
                "datetime_string": "2024-02-05T08:55:29.000000+01:00"
              },
              {
                "hr_bpm_int": 99,
                "datetime_string": "2024-02-05T08:56:30.000000+01:00"
              },
              {
                "hr_bpm_int": 103,
                "datetime_string": "2024-02-05T08:57:31.000000+01:00"
              },
              {
                "hr_bpm_int": 110,
                "datetime_string": "2024-02-05T08:58:32.000000+01:00"
              },
              {
                "hr_bpm_int": 123,
                "datetime_string": "2024-02-05T08:59:33.000000+01:00"
              },
              {
                "hr_bpm_int": 143,
                "datetime_string": "2024-02-05T09:00:34.000000+01:00"
              },
              {
                "hr_bpm_int": 148,
                "datetime_string": "2024-02-05T09:01:35.000000+01:00"
              },
              {
                "hr_bpm_int": 154,
                "datetime_string": "2024-02-05T09:02:36.000000+01:00"
              },
              {
                "hr_bpm_int": 165,
                "datetime_string": "2024-02-05T09:03:37.000000+01:00"
              },
              {
                "hr_bpm_int": 170,
                "datetime_string": "2024-02-05T09:04:38.000000+01:00"
              },
              {
                "hr_bpm_int": 160,
                "datetime_string": "2024-02-05T09:05:39.000000+01:00"
              },
              {
                "hr_bpm_int": 145,
                "datetime_string": "2024-02-05T09:06:40.000000+01:00"
              },
              {
                "hr_bpm_int": 130,
                "datetime_string": "2024-02-05T09:07:41.000000+01:00"
              },
              {
                "hr_bpm_int": 114,
                "datetime_string": "2024-02-05T09:08:42.000000+01:00"
              },
              {
                "hr_bpm_int": 124,
                "datetime_string": "2024-02-05T09:09:43.000000+01:00"
              },
              {
                "hr_bpm_int": 107,
                "datetime_string": "2024-02-05T09:10:44.000000+01:00"
              },
              {
                "hr_bpm_int": 110,
                "datetime_string": "2024-02-05T09:11:45.000000+01:00"
              },
              {
                "hr_bpm_int": 108,
                "datetime_string": "2024-02-05T09:12:46.000000+01:00"
              },
              {
                "hr_bpm_int": 105,
                "datetime_string": "2024-02-05T09:13:47.000000+01:00"
              },
              {
                "hr_bpm_int": 102,
                "datetime_string": "2024-02-05T09:14:48.000000+01:00"
              },
              {
                "hr_bpm_int": 99,
                "datetime_string": "2024-02-05T09:15:49.000000+01:00"
              },
              {
                "hr_bpm_int": 104,
                "datetime_string": "2024-02-05T09:16:50.000000+01:00"
              },
              {
                "hr_bpm_int": 99,
                "datetime_string": "2024-02-05T09:17:51.000000+01:00"
              },
              {
                "hr_bpm_int": 102,
                "datetime_string": "2024-02-05T09:18:52.000000+01:00"
              },
            ],
          },
          ...,
        },
      ],
    },
  },
}

```
