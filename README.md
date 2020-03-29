#  Srilanka district map component for vuejs

Srilanka District map component for vue.js

![preview](https://repository-images.githubusercontent.com/250916948/fb017f80-71ff-11ea-875a-d0f01120573d)

## Installation

  `npm i vue-lkmap --save`


 ## Usage
```
 import slmap from 'vue-slmap'

 Vue.component('sl-map', slmap)

// or
new Vue({
  el: 'body',
  components: { slmap }
})

```

```
<sl-map

 :color="'#514E48'" 
 :hoverColor="'#000'"
 :strokeColor="'#fff'"
 :activeColor="'red'"

 :districts="['1','2','3','4','5','6','7','8','7','8','7','8','7','8','7','8','7','8']" 
 
 >

 </sl-map>
```
## Use this order to pass districts values
```
Districts order

1.  Ampara
2.  Anuradhapura
3.  Badulla
4.  Batticaloa
5.  Colombo
6.  Galle
7.  Gampaha
8.  Hambantota
9.  Jaffna
10. Kalutara
11. Kandy
12. Kegalle
13. Kilinochchi
14. Kurunegala
15. Mannar
16. Matale
17. Matara
18. Monaragala
19. Mullaitivu
20. Nuwara Eliya
21. Polonnaruwa
22. Puttalam
23. Ratnapura
24. Trincomalee
25. Vavuniya


