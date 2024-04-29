# Distance with data granular

Dataset: Activity Event - Physical Health

Data: "distance"

Data Sources: Garmin

## Frame dataset

![descarga (12)](https://github.com/SalvatoreCordano/DataStructure/assets/147050219/d0343e12-307d-4575-96a3-2e0af9c54f3b)

```Json
{
  "version": 2,
  "data_structure": "activity_event",
  "client_uuid": "addfd6fe-decf-44b2-a934-be4240339e9c",
  "user_id": "65f26c48281a306e70eda988",
  "physical_health": {
    "events": {
      "activity_event": [
        {
          "metadata": {
            "datetime_string": "2024-03-13T17:12:44.000000-07:00",
            "user_id_string": "65f26c48281a306e70eda988",
            "sources_of_data_array": [
              "Garmin"
            ],
            "was_the_user_under_physical_activity_bool": true
          },
          "activity": {
            "activity_start_datetime_string": "2024-03-13T17:12:44.000000-07:00",
            "activity_end_datetime_string": "2024-03-13T20:16:27.000000-07:00",
            "activity_duration_seconds_int": 11023,
            "activity_type_name_string": "Mountain Biking",
            ...
          },
          ...
          "distance": {
            "steps_int": null,
            "steps_granular_data_array": [],
            "walked_distance_meters_float": null,
            "traveled_distance_meters_float": 18657.5,
            "traveled_distance_granular_data_array": [
              {
                "traveled_distance_meters_float": 83.33000183105469,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:13:26.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 133.89999389648438,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:14:01.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 170.72000122070312,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:14:30.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 217.35000610351562,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:15:06.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 327.5199890136719,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:15:47.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 423.1199951171875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:16:17.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 752.4199829101562,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:17:10.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 947.4199829101562,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:17:45.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 1262.47998046875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:18:46.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 1470.010009765625,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:19:30.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 1672.5999755859375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:20:04.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 1989.0899658203125,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:20:51.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 2189.820068359375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:21:30.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 2547.919921875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:22:29.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 2966.050048828125,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:23:30.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 3214.6201171875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:24:10.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 3361.719970703125,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:24:46.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 3440.159912109375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:25:25.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 3537.4599609375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:25:58.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 3714.7900390625,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:26:45.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 3738.659912109375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:27:34.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 3943.139892578125,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:28:33.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 4146.10986328125,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:29:12.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 4310.0400390625,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:29:42.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 4380.33984375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:30:08.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 4537.2998046875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:30:36.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 4606.8701171875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:31:17.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 4646.0400390625,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:31:55.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 4646.0400390625,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:34:19.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 4701.8701171875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:36:07.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 4815.16015625,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:36:40.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 4915.31005859375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:37:10.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 4947.0400390625,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:38:06.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 4976.080078125,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:38:53.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 5021.56982421875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:40:51.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 5128.419921875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:41:18.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 5225.83984375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:41:44.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 5288.89013671875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:42:10.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 5342.830078125,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:42:36.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 5370.2099609375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:43:17.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 5445.759765625,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:43:52.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 5512.81982421875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:44:29.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 5563.81005859375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:45:03.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 5606.8701171875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:45:30.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 5644.740234375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:46:14.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 5649.919921875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:48:30.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 5779.97998046875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:49:41.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 5868.1298828125,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:50:13.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 5933.25,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:50:50.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 6047.5498046875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:51:35.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 6199.18994140625,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:52:13.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 6282.06005859375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:52:39.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 6330.490234375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:53:50.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 6427.0,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:54:27.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 6469.68017578125,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:54:53.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 6494.9599609375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:55:28.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 6542.2001953125,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:56:13.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 6566.1298828125,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:57:09.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 6620.10986328125,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:58:57.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 6695.33984375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:59:28.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 6743.64013671875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:59:55.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 6793.06982421875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:00:21.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 6839.60009765625,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:00:49.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 6874.2900390625,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:01:15.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 6960.669921875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:01:59.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 7007.16015625,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:02:25.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 7041.240234375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:02:51.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 7082.10009765625,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:03:17.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 7121.0,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:03:46.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 7151.14013671875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:04:12.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 7180.72998046875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:04:59.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 7209.89013671875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:07:07.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 7265.0,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:07:37.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 7302.39990234375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:08:03.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 7339.02978515625,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:08:29.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 7387.35986328125,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:09:04.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 7432.7900390625,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:09:30.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 7499.72021484375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:10:01.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 7648.10986328125,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:10:43.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 7800.5,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:11:17.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 7912.52978515625,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:11:52.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 8000.22021484375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:12:25.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 8035.43994140625,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:14:15.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 8203.509765625,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:14:48.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 8427.1396484375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:15:35.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 8503.3095703125,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:16:44.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 8658.099609375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:17:18.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 8820.51953125,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:17:50.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 9002.2900390625,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:18:30.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 9244.0595703125,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:19:14.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 9402.83984375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:19:46.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 9516.73046875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:20:15.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 9589.0595703125,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:20:41.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 9728.7099609375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:21:22.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 9895.7001953125,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:22:03.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 10059.8798828125,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:22:41.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 10251.599609375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:23:18.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 10403.2197265625,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:23:50.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 10580.509765625,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:24:25.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 10696.419921875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:24:54.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 10765.349609375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:25:22.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 11025.240234375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:26:21.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 11254.169921875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:27:03.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 11427.51953125,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:27:35.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 11644.25,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:28:13.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 11809.650390625,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:28:51.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 12040.2802734375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:29:42.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 12165.0400390625,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:30:12.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 12258.3203125,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:30:50.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 12769.900390625,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:32:22.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 13118.599609375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:33:09.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 13697.919921875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:34:31.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 13879.1396484375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:35:04.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14039.1904296875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:35:41.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14060.1904296875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:36:37.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14067.7099609375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:38:30.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14067.7099609375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:40:22.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14069.7900390625,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:42:06.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14072.3603515625,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:46:14.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14076.9501953125,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:50:33.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14079.6396484375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:53:45.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14081.75,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:57:30.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14137.9599609375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:58:53.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14147.0595703125,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:01:22.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14163.26953125,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:01:53.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14185.2099609375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:02:31.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14227.6201171875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:03:15.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14244.7001953125,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:03:55.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14384.25,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:04:51.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14413.9404296875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:06:07.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14472.9404296875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:06:49.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14535.6904296875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:07:50.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14542.990234375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:09:14.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14551.759765625,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:10:48.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14561.740234375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:13:13.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14565.240234375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:15:55.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14569.0595703125,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:18:10.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14599.8203125,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:19:55.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14613.3896484375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:22:31.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14617.75,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:24:39.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14619.58984375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:27:53.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14625.990234375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:30:44.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14632.2998046875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:33:24.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14642.7197265625,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:36:23.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14648.669921875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:39:28.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14658.9501953125,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:41:01.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14667.2900390625,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:41:59.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14672.4404296875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:44:22.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14683.3203125,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:46:05.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14687.990234375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:47:53.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14693.26953125,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:49:32.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14699.26953125,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:51:21.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14707.1103515625,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:52:27.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14714.240234375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:53:22.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14731.7197265625,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:55:45.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14814.4404296875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:56:19.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 14891.849609375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:56:52.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 15117.8798828125,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:57:47.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 15463.23046875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:59:03.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 15857.1904296875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:00:28.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 16230.16015625,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:01:43.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 16417.919921875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:02:25.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 16619.30078125,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:03:19.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 16768.490234375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:03:58.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 16900.16015625,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:04:34.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 17037.470703125,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:05:15.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 17115.529296875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:05:41.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 17174.2890625,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:06:07.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 17228.94921875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:06:33.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 17257.5,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:07:29.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 17262.419921875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:09:29.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 17520.240234375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:10:11.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 17763.919921875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:10:45.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 18001.19921875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:11:21.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 18196.560546875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:11:51.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 18453.609375,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:12:25.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 18632.26953125,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:12:56.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 18644.5703125,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:14:52.000000-07:00"
              },
              {
                "traveled_distance_meters_float": 18656.529296875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:16:16.000000-07:00"
              }
            ],
          },
```
