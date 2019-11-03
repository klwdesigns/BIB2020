---
layout: cover
---
<body>
     <section class="intro">
          <div class="inner">
               <div class="container">
                    <img src="{{ site.baseurl }}/img/BIB-logo-white.svg" alt="Blue Iris Books">

                    <h5>Good books. Great designs.</h5>


               </div>
               <div class="container pad-top">
                    <hr>
                    <nav class="">
                         {% for link in site.data.navigation %}
                         <a class="nav-item" href="{{ link.url }}">{{ link.title }}</a>
                         {% endfor %}
                    </nav>

               </div>

          </div>

     </section>


</body>
