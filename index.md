---
layout: cover
---
<body>
     <section class="intro">
          <div class="inner">
               <div class="content">
                    <img src="{{ site.baseurl }}/img/BIB-logo.svg" alt="Blue Iris Books">

                    <h4>Good books. Great designs.</h4>


               </div>
               <div class="content pad-top">
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
