# Speed with data granular

Dataset: Activity Event - Physical Health

Data: "movement"

Data Sources: Garmin

## Frame dataset

![descarga (14)](https://github.com/SalvatoreCordano/DataStructure/assets/147050219/931391b9-520f-4a68-bfca-98d963b7ad87)

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
          "movement": {
            "speed_normalized_meters_per_second_float": null,
            "speed_avg_meters_per_second_float": 1.693,
            "speed_maximum_meters_per_second_float": 9.928,
            "speed_granular_data_array": [
              {
                "speed_meters_per_second_float": 1.1480000019073486,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:13:26.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 0.9610000252723694,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:14:01.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 1.305999994277954,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:14:30.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 2.2209999561309814,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:15:06.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 3.499000072479248,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:15:47.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 2.8459999561309814,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:16:17.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 6.261000156402588,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:17:10.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 5.636000156402588,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:17:45.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 5.271999835968018,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:18:46.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 5.570000171661377,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:19:30.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 7.193999767303467,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:20:04.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 6.745999813079834,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:20:51.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 5.906000137329102,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:21:30.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 5.896999835968018,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:22:29.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 6.979000091552734,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:23:30.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 5.860000133514404,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:24:10.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 2.2860000133514404,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:24:46.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 1.1380000114440918,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:25:25.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 2.865000009536743,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:25:58.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 1.7079999446868896,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:26:45.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 5.513999938964844,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:28:33.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 5.691999912261963,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:29:12.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 4.815000057220459,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:29:42.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 2.6589999198913574,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:30:08.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 1.4839999675750732,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:30:36.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 0.4950000047683716,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:31:17.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 1.7450000047683716,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:36:07.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 3.0789999961853027,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:36:40.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 3.8259999752044678,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:37:10.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 3.1070001125335693,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:40:51.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 4.189000129699707,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:41:18.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 3.322000026702881,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:41:44.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 2.1549999713897705,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:42:10.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 1.996999979019165,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:42:36.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 1.4459999799728394,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:43:17.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 2.8550000190734863,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:43:52.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 1.7640000581741333,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:44:29.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 1.4459999799728394,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:45:03.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 1.753999948501587,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:45:30.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 0.8859999775886536,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:46:14.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 4.179999828338623,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:49:41.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 3.619999885559082,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:50:13.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 0.699999988079071,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:50:50.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 5.52400016784668,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:51:35.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 2.947999954223633,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:52:13.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 2.6029999256134033,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:52:39.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 2.509999990463257,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:53:50.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 1.8940000534057617,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:54:27.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 1.4930000305175781,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:54:53.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 0.8019999861717224,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:55:28.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 1.3339999914169312,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:56:13.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 3.806999921798706,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:58:57.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 1.3619999885559082,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:59:28.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 1.847000002861023,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:59:55.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 2.071000099182129,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:00:21.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 1.4559999704360962,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:00:49.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 1.5119999647140503,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:01:15.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 1.875,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:01:59.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 1.4279999732971191,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:02:25.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 1.409000039100647,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:02:51.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 1.8289999961853027,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:03:17.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 1.5019999742507935,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:03:46.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 1.1480000019073486,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:04:12.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 1.930999994277954,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:07:07.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 1.6890000104904175,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:07:37.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 1.5019999742507935,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:08:03.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 1.4839999675750732,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:08:29.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 1.3899999856948853,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:09:04.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 1.753999948501587,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:09:30.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 2.5380001068115234,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:10:01.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 5.579999923706055,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:10:43.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 2.7809998989105225,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:11:17.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 2.575000047683716,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:11:52.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 1.2319999933242798,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:12:25.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 3.2279999256134033,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:14:15.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 3.6110000610351562,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:14:48.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 6.401000022888184,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:15:35.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 2.63100004196167,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:16:44.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 4.815000057220459,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:17:18.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 4.236000061035156,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:17:50.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 5.206999778747559,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:18:30.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 4.105999946594238,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:19:14.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 5.421000003814697,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:19:46.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 3.9839999675750732,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:20:15.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 2.6029999256134033,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:20:41.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 3.881999969482422,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:21:22.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 3.99399995803833,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:22:03.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 5.5980000495910645,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:22:41.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 4.497000217437744,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:23:18.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 5.458000183105469,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:23:50.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 3.9749999046325684,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:24:25.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 4.7769999504089355,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:24:54.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 2.0810000896453857,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:25:22.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 4.833000183105469,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:26:21.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 5.877999782562256,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:27:03.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 5.000999927520752,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:27:35.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 5.281000137329102,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:28:13.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 4.105999946594238,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:28:51.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 5.589000225067139,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:29:42.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 1.3619999885559082,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:30:12.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 2.4539999961853027,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:30:50.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 7.74399995803833,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:32:22.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 6.586999893188477,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:33:09.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 6.829999923706055,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:34:31.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 3.059999942779541,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:35:04.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 2.9670000076293945,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:35:41.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 0.47600001096725464,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:36:37.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 0.8399999737739563,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:57:30.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 2.6500000953674316,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:01:22.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 0.7739999890327454,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:01:53.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 0.8579999804496765,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:02:31.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 1.4559999704360962,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:03:15.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 0.9610000252723694,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:03:55.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 1.3619999885559082,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:04:51.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 1.5859999656677246,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:06:07.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 2.2109999656677246,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:06:49.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 1.2690000534057617,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:07:50.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 0.6340000033378601,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:09:14.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 0.4569999873638153,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:13:13.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 0.4480000138282776,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:22:31.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 0.5789999961853027,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:41:01.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 0.5690000057220459,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:46:05.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 0.48500001430511475,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:47:53.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 0.5879999995231628,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:49:32.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 0.47600001096725464,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:51:21.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 0.8489999771118164,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:52:27.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 0.625,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:53:22.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 0.9980000257492065,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:55:45.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 2.4730000495910645,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:56:19.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 2.1549999713897705,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:56:52.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 4.61899995803833,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:57:47.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 4.599999904632568,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:59:03.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 4.703000068664551,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:00:28.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 5.076000213623047,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:01:43.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 4.0960001945495605,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:02:25.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 3.806999921798706,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:03:19.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 3.7039999961853027,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:03:58.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 3.2939999103546143,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:04:34.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 3.5739998817443848,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:05:15.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 2.500999927520752,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:05:41.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 2.071000099182129,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:06:07.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 1.8849999904632568,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:06:33.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 1.753999948501587,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:09:29.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 6.6620001792907715,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:10:11.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 5.748000144958496,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:10:45.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 5.271999835968018,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:11:21.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 7.230999946594238,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:11:51.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 7.091000080108643,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:12:25.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 4.451000213623047,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:12:56.000000-07:00"
              },
              {
                "speed_meters_per_second_float": 0.48500001430511475,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:16:16.000000-07:00"
              }
            ],
            "velocity_avg_object": {
              "speed_meters_per_second_float": null,
              "direction_string": null
            },
            "velocity_maximum_object": {
              "speed_meters_per_second_float": null,
              "direction_string": null
            },
            "pace_avg_min_per_km_float": 9.844458,
            "pace_maximum_min_per_km_float": 1.6787536,
            "cadence_avg_rpm_float": null,
            "cadence_maximum_rpm_float": null,
            "cadence_granular_data_array": [],
            "torque_avg_newton_meters_float": null,
            "torque_maximum_newton_meters_float": null,
            "torque_granular_data_array": [],
            "lap_granular_data_array": []
          },
```
