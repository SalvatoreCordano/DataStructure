# Position with data granular

Dataset: Activity Event - Physical Health

Data: "Position"

Data Sources: Garmin

## Frame dataset

![image](https://github.com/SalvatoreCordano/DataStructure/assets/147050219/e9482138-9530-4e21-958f-831cf7be3715)

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
          "position": {
            "position_start_object": {
              "lat_deg_float": 33.58916292898357,
              "lng_deg_float": -112.03194882720709
            },
            "position_centroid_object": {
              "lat_deg_float": null,
              "lng_deg_float": null
            },
            "position_end_object": {
              "lat_deg_float": null,
              "lng_deg_float": null
            },
            "position_granular_data_array": [
              {
                "lat_deg_float": 33.58943793922663,
                "lng_deg_float": -112.03207128681242,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:13:26.000000-07:00"
              },
              {
                "lat_deg_float": 33.58934766612947,
                "lng_deg_float": -112.03213574364781,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:14:01.000000-07:00"
              },
              {
                "lat_deg_float": 33.58946140855551,
                "lng_deg_float": -112.03224554657936,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:14:30.000000-07:00"
              },
              {
                "lat_deg_float": 33.58950507827103,
                "lng_deg_float": -112.03220087103546,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:15:06.000000-07:00"
              },
              {
                "lat_deg_float": 33.58888490125537,
                "lng_deg_float": -112.03273823484778,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:15:47.000000-07:00"
              },
              {
                "lat_deg_float": 33.588048135861754,
                "lng_deg_float": -112.03260504640639,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:16:17.000000-07:00"
              },
              {
                "lat_deg_float": 33.58670317567885,
                "lng_deg_float": -112.03058970160782,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:17:10.000000-07:00"
              },
              {
                "lat_deg_float": 33.584945406764746,
                "lng_deg_float": -112.03059498220682,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:17:45.000000-07:00"
              },
              {
                "lat_deg_float": 33.58210536651313,
                "lng_deg_float": -112.03061082400382,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:18:46.000000-07:00"
              },
              {
                "lat_deg_float": 33.58041691593826,
                "lng_deg_float": -112.03030496835709,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:19:30.000000-07:00"
              },
              {
                "lat_deg_float": 33.579347217455506,
                "lng_deg_float": -112.02889756299555,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:20:04.000000-07:00"
              },
              {
                "lat_deg_float": 33.57855764217675,
                "lng_deg_float": -112.02633907087147,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:20:51.000000-07:00"
              },
              {
                "lat_deg_float": 33.57734888792038,
                "lng_deg_float": -112.02624301426113,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:21:30.000000-07:00"
              },
              {
                "lat_deg_float": 33.574120849370956,
                "lng_deg_float": -112.02625818550587,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:22:29.000000-07:00"
              },
              {
                "lat_deg_float": 33.572021685540676,
                "lng_deg_float": -112.02411216683686,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:23:30.000000-07:00"
              },
              {
                "lat_deg_float": 33.57318190857768,
                "lng_deg_float": -112.02183136716485,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:24:10.000000-07:00"
              },
              {
                "lat_deg_float": 33.57381960377097,
                "lng_deg_float": -112.02052085660398,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:24:46.000000-07:00"
              },
              {
                "lat_deg_float": 33.57375975698233,
                "lng_deg_float": -112.02032547444105,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:25:25.000000-07:00"
              },
              {
                "lat_deg_float": 33.57314477674663,
                "lng_deg_float": -112.01976086944342,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:25:58.000000-07:00"
              },
              {
                "lat_deg_float": 33.57368549332023,
                "lng_deg_float": -112.01796337030828,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:26:45.000000-07:00"
              },
              {
                "lat_deg_float": 33.57370016165078,
                "lng_deg_float": -112.01802564784884,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:27:34.000000-07:00"
              },
              {
                "lat_deg_float": 33.572997422888875,
                "lng_deg_float": -112.02006060630083,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:28:33.000000-07:00"
              },
              {
                "lat_deg_float": 33.572004586458206,
                "lng_deg_float": -112.02169205993414,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:29:12.000000-07:00"
              },
              {
                "lat_deg_float": 33.57061704620719,
                "lng_deg_float": -112.0220876019448,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:29:42.000000-07:00"
              },
              {
                "lat_deg_float": 33.57052082195878,
                "lng_deg_float": -112.02281347475946,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:30:08.000000-07:00"
              },
              {
                "lat_deg_float": 33.569455901160836,
                "lng_deg_float": -112.02357647940516,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:30:36.000000-07:00"
              },
              {
                "lat_deg_float": 33.56921575963497,
                "lng_deg_float": -112.0229975413531,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:31:17.000000-07:00"
              },
              {
                "lat_deg_float": 33.56895198114216,
                "lng_deg_float": -112.02276821248233,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:31:55.000000-07:00"
              },
              {
                "lat_deg_float": 33.56895198114216,
                "lng_deg_float": -112.02276821248233,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:34:19.000000-07:00"
              },
              {
                "lat_deg_float": 33.56883195228875,
                "lng_deg_float": -112.02220369130373,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:36:07.000000-07:00"
              },
              {
                "lat_deg_float": 33.568416461348534,
                "lng_deg_float": -112.0212897285819,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:36:40.000000-07:00"
              },
              {
                "lat_deg_float": 33.56774523854256,
                "lng_deg_float": -112.02145979739726,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:37:10.000000-07:00"
              },
              {
                "lat_deg_float": 33.567528147250414,
                "lng_deg_float": -112.02165928669274,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:38:06.000000-07:00"
              },
              {
                "lat_deg_float": 33.56737266294658,
                "lng_deg_float": -112.02190923504531,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:38:53.000000-07:00"
              },
              {
                "lat_deg_float": 33.56703587807715,
                "lng_deg_float": -112.02218541875482,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:40:51.000000-07:00"
              },
              {
                "lat_deg_float": 33.56608746573329,
                "lng_deg_float": -112.0222535636276,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:41:18.000000-07:00"
              },
              {
                "lat_deg_float": 33.56521817855537,
                "lng_deg_float": -112.02211802825332,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:41:44.000000-07:00"
              },
              {
                "lat_deg_float": 33.564689783379436,
                "lng_deg_float": -112.02193253673613,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:42:10.000000-07:00"
              },
              {
                "lat_deg_float": 33.56426004320383,
                "lng_deg_float": -112.02167068608105,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:42:36.000000-07:00"
              },
              {
                "lat_deg_float": 33.56403490528464,
                "lng_deg_float": -112.02165744267404,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:43:17.000000-07:00"
              },
              {
                "lat_deg_float": 33.56393457390368,
                "lng_deg_float": -112.02204024419188,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:43:52.000000-07:00"
              },
              {
                "lat_deg_float": 33.56387447565794,
                "lng_deg_float": -112.02221626415849,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:44:29.000000-07:00"
              },
              {
                "lat_deg_float": 33.56351883150637,
                "lng_deg_float": -112.02188526280224,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:45:03.000000-07:00"
              },
              {
                "lat_deg_float": 33.56343191117048,
                "lng_deg_float": -112.02150790952146,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:45:30.000000-07:00"
              },
              {
                "lat_deg_float": 33.56321255676448,
                "lng_deg_float": -112.02162290923297,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:46:14.000000-07:00"
              },
              {
                "lat_deg_float": 33.56322403997183,
                "lng_deg_float": -112.02167705632746,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:48:30.000000-07:00"
              },
              {
                "lat_deg_float": 33.5627715010196,
                "lng_deg_float": -112.022865107283,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:49:41.000000-07:00"
              },
              {
                "lat_deg_float": 33.562961015850306,
                "lng_deg_float": -112.02344345860183,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:50:13.000000-07:00"
              },
              {
                "lat_deg_float": 33.563113398849964,
                "lng_deg_float": -112.02391544356942,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:50:50.000000-07:00"
              },
              {
                "lat_deg_float": 33.56314533390105,
                "lng_deg_float": -112.02418542467058,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:51:35.000000-07:00"
              },
              {
                "lat_deg_float": 33.56212073005736,
                "lng_deg_float": -112.0248078648001,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:52:13.000000-07:00"
              },
              {
                "lat_deg_float": 33.5616403631866,
                "lng_deg_float": -112.02492638491094,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:52:39.000000-07:00"
              },
              {
                "lat_deg_float": 33.56122948229313,
                "lng_deg_float": -112.02495488338172,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:53:50.000000-07:00"
              },
              {
                "lat_deg_float": 33.56050134636462,
                "lng_deg_float": -112.02439857646823,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:54:27.000000-07:00"
              },
              {
                "lat_deg_float": 33.5602586902678,
                "lng_deg_float": -112.02406346797943,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:54:53.000000-07:00"
              },
              {
                "lat_deg_float": 33.56009876355529,
                "lng_deg_float": -112.02388300560415,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:55:28.000000-07:00"
              },
              {
                "lat_deg_float": 33.55970313772559,
                "lng_deg_float": -112.02384193427861,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:56:13.000000-07:00"
              },
              {
                "lat_deg_float": 33.55952141806483,
                "lng_deg_float": -112.0238149445504,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:57:09.000000-07:00"
              },
              {
                "lat_deg_float": 33.55905613861978,
                "lng_deg_float": -112.02384646050632,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:58:57.000000-07:00"
              },
              {
                "lat_deg_float": 33.55849212035537,
                "lng_deg_float": -112.0241534896195,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:59:28.000000-07:00"
              },
              {
                "lat_deg_float": 33.55824384838343,
                "lng_deg_float": -112.02373095788062,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T17:59:55.000000-07:00"
              },
              {
                "lat_deg_float": 33.55794260278344,
                "lng_deg_float": -112.02334203757346,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:00:21.000000-07:00"
              },
              {
                "lat_deg_float": 33.557734647765756,
                "lng_deg_float": -112.02291212975979,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:00:49.000000-07:00"
              },
              {
                "lat_deg_float": 33.55761562474072,
                "lng_deg_float": -112.02258431352675,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:01:15.000000-07:00"
              },
              {
                "lat_deg_float": 33.557738084346056,
                "lng_deg_float": -112.02169482596219,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:01:59.000000-07:00"
              },
              {
                "lat_deg_float": 33.55800278484821,
                "lng_deg_float": -112.02131043188274,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:02:25.000000-07:00"
              },
              {
                "lat_deg_float": 33.55819573625922,
                "lng_deg_float": -112.02102703973651,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:02:51.000000-07:00"
              },
              {
                "lat_deg_float": 33.55852237902582,
                "lng_deg_float": -112.02086635865271,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:03:17.000000-07:00"
              },
              {
                "lat_deg_float": 33.55869303457439,
                "lng_deg_float": -112.02068296261132,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:03:46.000000-07:00"
              },
              {
                "lat_deg_float": 33.55844627134502,
                "lng_deg_float": -112.02057818882167,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:04:12.000000-07:00"
              },
              {
                "lat_deg_float": 33.558200430125,
                "lng_deg_float": -112.02047794125974,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:04:59.000000-07:00"
              },
              {
                "lat_deg_float": 33.55796640738845,
                "lng_deg_float": -112.02034123241901,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:07:07.000000-07:00"
              },
              {
                "lat_deg_float": 33.557740934193134,
                "lng_deg_float": -112.0200536493212,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:07:37.000000-07:00"
              },
              {
                "lat_deg_float": 33.557573882862926,
                "lng_deg_float": -112.01995155774057,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:08:03.000000-07:00"
              },
              {
                "lat_deg_float": 33.55737179517746,
                "lng_deg_float": -112.02026261016726,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:08:29.000000-07:00"
              },
              {
                "lat_deg_float": 33.557135090231895,
                "lng_deg_float": -112.02033704146743,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:09:04.000000-07:00"
              },
              {
                "lat_deg_float": 33.55715059675276,
                "lng_deg_float": -112.01985097490251,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:09:30.000000-07:00"
              },
              {
                "lat_deg_float": 33.55736014433205,
                "lng_deg_float": -112.01919442042708,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:10:01.000000-07:00"
              },
              {
                "lat_deg_float": 33.55708890594542,
                "lng_deg_float": -112.01779288239777,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:10:43.000000-07:00"
              },
              {
                "lat_deg_float": 33.55679822154343,
                "lng_deg_float": -112.01622747816145,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:11:17.000000-07:00"
              },
              {
                "lat_deg_float": 33.55705236084759,
                "lng_deg_float": -112.0151371601969,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:11:52.000000-07:00"
              },
              {
                "lat_deg_float": 33.55717867612839,
                "lng_deg_float": -112.01428472064435,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:12:25.000000-07:00"
              },
              {
                "lat_deg_float": 33.557421416044235,
                "lng_deg_float": -112.01406519860029,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:14:15.000000-07:00"
              },
              {
                "lat_deg_float": 33.55818685144186,
                "lng_deg_float": -112.0127023011446,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:14:48.000000-07:00"
              },
              {
                "lat_deg_float": 33.558758832514286,
                "lng_deg_float": -112.01047187671065,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:15:35.000000-07:00"
              },
              {
                "lat_deg_float": 33.559002075344324,
                "lng_deg_float": -112.0097166672349,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:16:44.000000-07:00"
              },
              {
                "lat_deg_float": 33.55912587605417,
                "lng_deg_float": -112.0081846229732,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:17:18.000000-07:00"
              },
              {
                "lat_deg_float": 33.55945000424981,
                "lng_deg_float": -112.0066597033292,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:17:50.000000-07:00"
              },
              {
                "lat_deg_float": 33.560347370803356,
                "lng_deg_float": -112.00510821305215,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:18:30.000000-07:00"
              },
              {
                "lat_deg_float": 33.56138991191983,
                "lng_deg_float": -112.00288499705493,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:19:14.000000-07:00"
              },
              {
                "lat_deg_float": 33.56251962482929,
                "lng_deg_float": -112.0019268617034,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:19:46.000000-07:00"
              },
              {
                "lat_deg_float": 33.56253186240792,
                "lng_deg_float": -112.00096554122865,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:20:15.000000-07:00"
              },
              {
                "lat_deg_float": 33.56226682662964,
                "lng_deg_float": -112.00027353130281,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:20:41.000000-07:00"
              },
              {
                "lat_deg_float": 33.56252976693213,
                "lng_deg_float": -111.99883569963276,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:21:22.000000-07:00"
              },
              {
                "lat_deg_float": 33.562812991440296,
                "lng_deg_float": -111.99709896929562,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:22:03.000000-07:00"
              },
              {
                "lat_deg_float": 33.56398184783757,
                "lng_deg_float": -111.99724389240146,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:22:41.000000-07:00"
              },
              {
                "lat_deg_float": 33.56561975553632,
                "lng_deg_float": -111.99765276163816,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:23:18.000000-07:00"
              },
              {
                "lat_deg_float": 33.56656079180539,
                "lng_deg_float": -111.99839673936367,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:23:50.000000-07:00"
              },
              {
                "lat_deg_float": 33.56778983026743,
                "lng_deg_float": -111.99725269339979,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:24:25.000000-07:00"
              },
              {
                "lat_deg_float": 33.568106750026345,
                "lng_deg_float": -111.99789382517338,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:24:54.000000-07:00"
              },
              {
                "lat_deg_float": 33.56814648024738,
                "lng_deg_float": -111.998569406569,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:25:22.000000-07:00"
              },
              {
                "lat_deg_float": 33.56818797066808,
                "lng_deg_float": -112.0013169106096,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:26:21.000000-07:00"
              },
              {
                "lat_deg_float": 33.568199621513486,
                "lng_deg_float": -112.00372628867626,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:27:03.000000-07:00"
              },
              {
                "lat_deg_float": 33.56810708530247,
                "lng_deg_float": -112.00511827133596,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:27:35.000000-07:00"
              },
              {
                "lat_deg_float": 33.56810314580798,
                "lng_deg_float": -112.00742228887975,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:28:13.000000-07:00"
              },
              {
                "lat_deg_float": 33.56770500540733,
                "lng_deg_float": -112.00910210609436,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:28:51.000000-07:00"
              },
              {
                "lat_deg_float": 33.567422619089484,
                "lng_deg_float": -112.01146664097905,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:29:42.000000-07:00"
              },
              {
                "lat_deg_float": 33.56711843982339,
                "lng_deg_float": -112.01270272023976,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:30:12.000000-07:00"
              },
              {
                "lat_deg_float": 33.56777566485107,
                "lng_deg_float": -112.01293758116663,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:30:50.000000-07:00"
              },
              {
                "lat_deg_float": 33.57238537631929,
                "lng_deg_float": -112.01290648430586,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:32:22.000000-07:00"
              },
              {
                "lat_deg_float": 33.575526494532824,
                "lng_deg_float": -112.0128716994077,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:33:09.000000-07:00"
              },
              {
                "lat_deg_float": 33.580746157094836,
                "lng_deg_float": -112.01299281790853,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:34:31.000000-07:00"
              },
              {
                "lat_deg_float": 33.582325894385576,
                "lng_deg_float": -112.01339900493622,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:35:04.000000-07:00"
              },
              {
                "lat_deg_float": 33.58374352566898,
                "lng_deg_float": -112.01336899772286,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:35:41.000000-07:00"
              },
              {
                "lat_deg_float": 33.583902614191175,
                "lng_deg_float": -112.01334066689014,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:36:37.000000-07:00"
              },
              {
                "lat_deg_float": 33.58395164832473,
                "lng_deg_float": -112.01328593306243,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:38:30.000000-07:00"
              },
              {
                "lat_deg_float": 33.58395164832473,
                "lng_deg_float": -112.01328593306243,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:40:22.000000-07:00"
              },
              {
                "lat_deg_float": 33.58396011404693,
                "lng_deg_float": -112.01327721588314,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:42:06.000000-07:00"
              },
              {
                "lat_deg_float": 33.58397671021521,
                "lng_deg_float": -112.0133000984788,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:46:14.000000-07:00"
              },
              {
                "lat_deg_float": 33.5839877743274,
                "lng_deg_float": -112.01327755115926,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:50:33.000000-07:00"
              },
              {
                "lat_deg_float": 33.58399330638349,
                "lng_deg_float": -112.01324905268848,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:53:45.000000-07:00"
              },
              {
                "lat_deg_float": 33.5840049572289,
                "lng_deg_float": -112.0132462028414,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:57:30.000000-07:00"
              },
              {
                "lat_deg_float": 33.58392524532974,
                "lng_deg_float": -112.01344795525074,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T18:58:53.000000-07:00"
              },
              {
                "lat_deg_float": 33.583909990265965,
                "lng_deg_float": -112.01342197135091,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:01:22.000000-07:00"
              },
              {
                "lat_deg_float": 33.58394477516413,
                "lng_deg_float": -112.01346329413354,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:01:53.000000-07:00"
              },
              {
                "lat_deg_float": 33.584068827331066,
                "lng_deg_float": -112.013586089015,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:02:31.000000-07:00"
              },
              {
                "lat_deg_float": 33.58398299664259,
                "lng_deg_float": -112.01314964331686,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:03:15.000000-07:00"
              },
              {
                "lat_deg_float": 33.58399506658316,
                "lng_deg_float": -112.0131962466985,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:03:55.000000-07:00"
              },
              {
                "lat_deg_float": 33.58403840102255,
                "lng_deg_float": -112.01306540518999,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:06:07.000000-07:00"
              },
              {
                "lat_deg_float": 33.58411090448499,
                "lng_deg_float": -112.01299332082272,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:06:49.000000-07:00"
              },
              {
                "lat_deg_float": 33.58399213291705,
                "lng_deg_float": -112.01337771490216,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:07:50.000000-07:00"
              },
              {
                "lat_deg_float": 33.58403873629868,
                "lng_deg_float": -112.01331627555192,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:09:14.000000-07:00"
              },
              {
                "lat_deg_float": 33.584073688834906,
                "lng_deg_float": -112.01329029165208,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:10:48.000000-07:00"
              },
              {
                "lat_deg_float": 33.58408114872873,
                "lng_deg_float": -112.01321301050484,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:13:13.000000-07:00"
              },
              {
                "lat_deg_float": 33.58409573324025,
                "lng_deg_float": -112.01318426057696,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:15:55.000000-07:00"
              },
              {
                "lat_deg_float": 33.58408517204225,
                "lng_deg_float": -112.01317470520735,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:18:10.000000-07:00"
              },
              {
                "lat_deg_float": 33.58398023061454,
                "lng_deg_float": -112.01307915151119,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:19:55.000000-07:00"
              },
              {
                "lat_deg_float": 33.584008226171136,
                "lng_deg_float": -112.01314277015626,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:22:31.000000-07:00"
              },
              {
                "lat_deg_float": 33.584011159837246,
                "lng_deg_float": -112.01316892169416,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:24:39.000000-07:00"
              },
              {
                "lat_deg_float": 33.583998419344425,
                "lng_deg_float": -112.01316305436194,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:27:53.000000-07:00"
              },
              {
                "lat_deg_float": 33.5839909594506,
                "lng_deg_float": -112.01317395083606,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:30:44.000000-07:00"
              },
              {
                "lat_deg_float": 33.58406849205494,
                "lng_deg_float": -112.01330227777362,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:33:24.000000-07:00"
              },
              {
                "lat_deg_float": 33.584057008847594,
                "lng_deg_float": -112.01327034272254,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:36:23.000000-07:00"
              },
              {
                "lat_deg_float": 33.58406765386462,
                "lng_deg_float": -112.01323899440467,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:39:28.000000-07:00"
              },
              {
                "lat_deg_float": 33.58405248261988,
                "lng_deg_float": -112.01322625391185,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:41:01.000000-07:00"
              },
              {
                "lat_deg_float": 33.584032617509365,
                "lng_deg_float": -112.01319658197463,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:41:59.000000-07:00"
              },
              {
                "lat_deg_float": 33.584017446264625,
                "lng_deg_float": -112.01318694278598,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:44:22.000000-07:00"
              },
              {
                "lat_deg_float": 33.5840810649097,
                "lng_deg_float": -112.01315903104842,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:46:05.000000-07:00"
              },
              {
                "lat_deg_float": 33.58407184481621,
                "lng_deg_float": -112.01324176043272,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:47:53.000000-07:00"
              },
              {
                "lat_deg_float": 33.584054661914706,
                "lng_deg_float": -112.01323145069182,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:49:32.000000-07:00"
              },
              {
                "lat_deg_float": 33.58405089005828,
                "lng_deg_float": -112.01321309432387,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:51:21.000000-07:00"
              },
              {
                "lat_deg_float": 33.58404083177447,
                "lng_deg_float": -112.013202868402,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:52:27.000000-07:00"
              },
              {
                "lat_deg_float": 33.58401828445494,
                "lng_deg_float": -112.01319708488882,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:53:22.000000-07:00"
              },
              {
                "lat_deg_float": 33.583896830677986,
                "lng_deg_float": -112.01331971213222,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:55:45.000000-07:00"
              },
              {
                "lat_deg_float": 33.583732545375824,
                "lng_deg_float": -112.01415387913585,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:56:19.000000-07:00"
              },
              {
                "lat_deg_float": 33.58308303169906,
                "lng_deg_float": -112.01430869288743,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:56:52.000000-07:00"
              },
              {
                "lat_deg_float": 33.58251758851111,
                "lng_deg_float": -112.01625203713775,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:57:47.000000-07:00"
              },
              {
                "lat_deg_float": 33.5824713204056,
                "lng_deg_float": -112.01997209340334,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T19:59:03.000000-07:00"
              },
              {
                "lat_deg_float": 33.58243787661195,
                "lng_deg_float": -112.02421702444553,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:00:28.000000-07:00"
              },
              {
                "lat_deg_float": 33.58234601095319,
                "lng_deg_float": -112.02823388390243,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:01:43.000000-07:00"
              },
              {
                "lat_deg_float": 33.58232748694718,
                "lng_deg_float": -112.03025819733739,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:02:25.000000-07:00"
              },
              {
                "lat_deg_float": 33.582259342074394,
                "lng_deg_float": -112.03242600895464,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:03:19.000000-07:00"
              },
              {
                "lat_deg_float": 33.582241823896766,
                "lng_deg_float": -112.0340308919549,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:03:58.000000-07:00"
              },
              {
                "lat_deg_float": 33.58225816860795,
                "lng_deg_float": -112.03544894233346,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:04:34.000000-07:00"
              },
              {
                "lat_deg_float": 33.58222003094852,
                "lng_deg_float": -112.03692751005292,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:05:15.000000-07:00"
              },
              {
                "lat_deg_float": 33.58226319774985,
                "lng_deg_float": -112.03776863403618,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:05:41.000000-07:00"
              },
              {
                "lat_deg_float": 33.58224777504802,
                "lng_deg_float": -112.03839275054634,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:06:07.000000-07:00"
              },
              {
                "lat_deg_float": 33.58230602927506,
                "lng_deg_float": -112.03897747211158,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:06:33.000000-07:00"
              },
              {
                "lat_deg_float": 33.582326313480735,
                "lng_deg_float": -112.03928366303444,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:07:29.000000-07:00"
              },
              {
                "lat_deg_float": 33.582353135570884,
                "lng_deg_float": -112.03930721618235,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:09:29.000000-07:00"
              },
              {
                "lat_deg_float": 33.58463670127094,
                "lng_deg_float": -112.03937401995063,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:10:11.000000-07:00"
              },
              {
                "lat_deg_float": 33.58471683226526,
                "lng_deg_float": -112.0371412485838,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:10:45.000000-07:00"
              },
              {
                "lat_deg_float": 33.58639983460307,
                "lng_deg_float": -112.03576292842627,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:11:21.000000-07:00"
              },
              {
                "lat_deg_float": 33.5876933299005,
                "lng_deg_float": -112.03448393382132,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:11:51.000000-07:00"
              },
              {
                "lat_deg_float": 33.589467192068696,
                "lng_deg_float": -112.03347626142204,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:12:25.000000-07:00"
              },
              {
                "lat_deg_float": 33.58943743631244,
                "lng_deg_float": -112.03214739449322,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:12:56.000000-07:00"
              },
              {
                "lat_deg_float": 33.589399214833975,
                "lng_deg_float": -112.03216097317636,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:14:52.000000-07:00"
              },
              {
                "lat_deg_float": 33.58939276076853,
                "lng_deg_float": -112.0321658346802,
                "interval_duration_seconds_float": 60.0,
                "datetime_string": "2024-03-13T20:16:16.000000-07:00"
              }
            ],
            "position_polyline_map_data_summary_string": null
          },
```
