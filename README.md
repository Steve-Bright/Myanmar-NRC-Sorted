This is not the original repository. I have forked this repository, so that I can create the json file that is useful for my own projects, right now. If you want to check the original repository, please proceed towards this link: https://github.com/htetoozin/Myanmar-NRC


The following are the files
nrc.json (This is the original file from the original repository)
nrc-sorted.json (This is my inserted json file where the json are sorted according to the nrc_code)
nrc-code-grouped.json (This is another inserted json file of mine, where nrc_code are separated as a corresponding key. 


EXAMPLE 
========
nrc.json
--------

```json
{
  "data":[
    {
        "id":"1",
        "name_en":"AhGaYa",
        "name_mm":"(အဂယ) အင်ဂျန်းယန်",
        "nrc_code":"1",
        "created_at":"2019-01-31 20:03:05",
        "updated_at":"2019-01-31 20:03:24"
     },
    {
        "id":"171",
        "name_en":"KaSaNa",
        "name_mm":"(ကဆန) ကျောက်ဆည်",
        "nrc_code":"9",
        "created_at":"2019-01-31 20:03:06",
        "updated_at":"2019-01-31 20:03:24"
     }, {
        "id":"424",
        "name_en":"KhAaHsa",
        "name_mm":"(ခအဇ) ချမ်းအေးသာစံ",
        "nrc_code":"9",
        "created_at":"2020-12-21 22:39:30",
        "updated_at":"2020-12-21 22:39:30"
     },
     {
        "id":"426",
        "name_en":"TaTaHta",
        "name_mm":"တတထ (တံတား)",
        "nrc_code":"12",
        "created_at":"2020-12-31 21:30:10",
        "updated_at":"2020-12-31 21:30:10"
     }
  ]
}
```
Here, in the original file, even though the nrc_codes are sorted at the start of the file, the code restarts from the id: 356. So, I fixed it in nrc-sorted.json. So, id will not make sense here. 

nrc-code-grouped.json
-----

```json
{
  "data": {
    "1": [
      {
        "name_en": "AhGaYa",
        "name_mm": "(အဂယ) အင်ဂျန်းယန်",
        "created_at": "2019-01-31 20:03:05",
        "updated_at": "2019-01-31 20:03:24"
      },
      {
        "name_en": "BaMaNa",
        "name_mm": "(ဗမန) ဗန်းမော်",
        "created_at": "2019-01-31 20:03:05",
        "updated_at": "2019-01-31 20:03:24"
      }
      ],
    "6": [
      {
        "name_en": "HtaWaNa",
        "name_mm": "(ထဝန) ထားဝယ်",
        "created_at": "2019-01-31 20:03:05",
        "updated_at": "2019-01-31 20:03:24"
      },
      {
        "name_en": "KaThaNa",
        "name_mm": "(ကသန) ကော့သောင်း",
        "created_at": "2019-01-31 20:03:05",
        "updated_at": "2019-01-31 20:03:24"
      },
    ], 
    "12": [
    {
        "name_en": "LaThaNa",
        "name_mm": "(လသန) လသာ",
        "created_at": "2019-01-31 20:03:06",
        "updated_at": "2019-01-31 20:03:06"
      },
      {
        "name_en": "MaGaTa",
        "name_mm": "(မဂတ) မင်္ဂလာတောင်ညွှန့်",
        "created_at": "2019-01-31 20:03:06",
        "updated_at": "2019-01-31 20:03:24"
      }
    ]
```
Hope you will find this file userful.
