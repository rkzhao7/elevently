---
title: Contact
layout: base.njk
tags: navItem
---
# {{Contact}}

 <div class="toggle-btn">
        <i class="fa fa-bars"></i>
    </div>
  <header class="header container">
        <div class="circle"></div>

  <section class="contact_area section_gap">
        <div class="container">
            <div class="row">
                <div class="col-lg-3">
                    <div class="contact_info">
                        <div class="info_item">
                            <i class="lnr lnr-home"></i>
                            <h6>NewYork, United States</h6>
                            <p>Brooklyn </p>
                        </div>
                        <div class="info_item">
                            <i class="lnr lnr-phone-handset"></i>
                            <h6><a href="#">+1 (646) 8339 137</a></h6>
                            <p>Mon to Fri</p>
                        </div>
                        <div class="info_item">
                            <i class="lnr lnr-envelope"></i>
                            <h6><a href="#">r382004689@gmail.com</a></h6>
                            <p>Send me your query anytime!</p>
                        </div>
                    </div>
                </div>
                <div class="col-lg-9">
                    <form class="row contact_form" action="contact_process.php" method="post" id="contactForm"
                        novalidate="novalidate">
                        <div class="col-md-6">
                            <div class="form-group">
                                <input type="text" class="form-control" id="name" name="name" placeholder="Enter your name">
                            </div>
                            <div class="form-group">
                                <input type="email" class="form-control" id="email" name="email" placeholder="Enter email address">
                            </div>
                            <div class="form-group">
                                <input type="text" class="form-control" id="subject" name="subject" placeholder="Enter Subject">
                            </div>
                        </div>
                        <div class="col-md-6">
                            <div class="form-group">
                                <textarea class="form-control" name="message" id="message" rows="1" placeholder="Enter Message"></textarea>
                            </div>
                        </div>
                        <div class="col-md-12 text-right">
                            <button type="submit" value="submit" class="primary-btn"><span>Send Message</span></button>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </section>

  <script>
        let togglebtn = document.querySelector('.toggle-btn')
        let navbar = document.querySelector('.navbar')

        togglebtn.addEventListener('click', ()=>{
            navbar.classList.toggle('mobile-nav')
        } )
    </script>