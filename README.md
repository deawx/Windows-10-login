# Windows-10-login
Html css Js login windows 10


for jalali date time add code in script

   <script>
      moment.updateLocale('fa', {
        weekdaysMin : ["یک شنبه", "دو شنبه", "سه شنبه", "چهار شنبه", "پنج شنبه", "جمعه", "شنبه"]
      });
      var DateMoment = moment();
      var dDisplayMoment = document.getElementById('dispalyDate');
      dDisplayMoment.innerHTML = DateMoment.format('dd jYYYY/jM/jD')
   </script>
