# assignment2-aredla
Mark down
## Vineetha Aredla 
## Salar Jung Museum
  Exhibits which are must see in the museum are **clocks**,Quran collections,Japanese artifacts,Porcelian artifacts,**Samurai swords**,Sculptures,**coins**

---

## Airports near to museum
 Airport near to museum is hyderabad airport and directions to it are

1. Take bus to AC guards
2. Take walk to Lakadi-ka-pul
3. Take subway to osmania university
4. Then take the walk to salar jung museum

## List of other locations around the museum

* Bongiri port
* Srirangapur  temple
* Srisailam temple
* Surendrapuri
* Yadigirigutta temple
* Ananthagiri hills
* Medak fort

**[About Me](AboutMe.md)**

---

## Four cities which you must visit in USA
  This table says about the city in three coloumns.The first column describes about the name of a city.
The second column describes about the important location to visit in the city. The third column
describes about the the amount of time to spend visiting the important location



| Name of city | Important location in the city | Amount of time |
| :---:          | :---:                        | :---: |
|Chicago         |Architecture river cruise     |1 hour|
|New Orlean      |Jakson square                 |3 hours|
|Seattle         |Pike place market             |2 hours|
|San Diego       |Beach                         |3 hours|

---
### Quotes by famous personalities



>When the going gets tough the tough gets going
by  *Joe Kennedy*



>Strive not to be sucess,but rather to be of value
by *Albert Einstien*
---
>English Time to Seconds[for more details](https://css-tricks.com/snippets/php/)

```

function time2seconds($time) {

 preg_match_all('/(\d+ [a-z]+)/', $time, $matches);
 
 $matches = $matches[0];

 $formats = array();

 foreach ($matches as $format) {
   preg_match('/(\d+)\s?([a-z]+)/', $format, $f);
   $time = $f[1];
   $type = $f[2];
   $formats[$type] = $time;
 }

 $output = array(
     'years' => 0,
     'months' => 0,
     'days' => 0,
     'hours' => 0,
     'minutes' => 0,
     'seconds' => 0
 );

 foreach ($formats as $format => $time) {
   if( $time == 0 )
     continue;

   switch ($format) {
     case 'year' :
     case 'years' :
       $output['years'] = $time * 12 * 30 * 24 * 60 * 60;
     break;
     case 'month' :
     case 'months' :
       $output['months'] = $time * 30 * 24 * 60 * 60;
     break;

     case 'day' :
     case 'days' :
       $output['days'] = $time * 24 * 60 * 60;
     break;

     case 'hour' :
     case 'hours' :
       $output['hours'] = $time * 60 * 60;
     break;

     case 'minute' :
     case 'minutes' :
       $output['minutes'] = $time * 60;
     break;

     case 'second' :
     case 'seconds' :
       $output['seconds'] = $time;
     break;
   }

 }

 return $output['years'] + $output['months'] + $output['days'] + $output['hours'] + $output['minutes'] + $output['seconds'];
}

```

