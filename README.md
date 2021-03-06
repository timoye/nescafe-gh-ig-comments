# Nescafe GH #NESCAFÉOneSong Instagram Competition Comments
This Repo contains comments pulled from the  [nescafe_gh Instagram Post](https://www.instagram.com/p/CCxjYoHpxPP/)

It was scrapped using [drawrowfly/instagram-scraper](https://github.com/drawrowfly/instagram-scraper)

The [data_all.json](https://github.com/timoye/nescafe-gh-ig-comments/blob/master/data_all.json) file contains all the comments in JSON format

[The Instagram post](https://www.instagram.com/p/CCxjYoHpxPP/) was made and people were asked to vote by commenting the contestant of their choice. And only one Vote Per Instagram Account will count.
 
 An object in the collection looks like this
 ```json
{
     "id": "17843735915314416",
     "text": "Nessa",
     "created_at": 1595721182,
     "did_report_as_spam": false,
     "owner": {
       "id": "10923467320",
       "is_verified": false,
       "profile_pic_url": "https://scontent-ort2-1.cdninstagram.com/v/t51.2885-19/s150x150/50676812_319384725356340_6150837795771383808_n.jpg?_nc_ht=scontent-ort2-1.cdninstagram.com&_nc_ohc=APmJpyNnVX4AX-2oS6o&oh=c918da4771b5601bf116d16d6c271072&oe=5F446632",
       "username": "_____bou.jiee"
     },
     "likes": 0,
     "comments": 0
   }
 ```
 
If Nescafe GH is to do a filter using each contestant name,
they will use

| Contestant  | Keyword |
| ------------- | ------------- |
| Kobi Newton  | kobi  |
| Nessa  | nessa  |
| Spooky the maniac  | spooky  |
| Young Nik Gram  | young  |
| Gidochi  | gidochi  |

## Note

Only one vote counts per instagram username

Developers, pull and do a count using any language of your choice to determine the winner.

[@nescafe_gh](https://www.instagram.com/nescafe_gh/) needs to explain how they came about their numbers

## My Results

This is what I got using Laravel Collection filter. I will also share that code snippet

 ```json
{
"all_comments": 15318,
"real_users_count": 4377,
"all_youngnik_comments": 1538,
"all_gidochi_comments": 5356,
"all_kobi_newton_comments": 2682,
"all_spookythemaniac_comments": 2925,
"all_nessa_comments": 2115,
"youngnik": 1289,
"gidochi": 938,
"kobi_newton": 686,
"spookythemaniac": 691,
"nessa": 321
} 
```
I would really want people to do this analysis, I may be wrong

JSON file of all comments is here [data_all.json](https://github.com/timoye/nescafe-gh-ig-comments/blob/master/data_all.json)
