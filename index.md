## Hello! I am SukHeon Kang

---

### Portfolio

---

#### Research Interest 
Now I am studying mechanical engineering.
I haven't decided which field to enter, but I'm looking for various fields. For now, I am interested in Nano Technology, Artificial Intelligence, Natural Language and Programming.
<img src="images/aabb.gif"/>

---

#### Education
KAIST, M.S., [Graduate school of MECH](https://me.kaist.ac.kr/main/main.html), Mar 2022(Expected) -

HANYANG University, B.S., [Mechanical Engineering](http://me.hanyang.ac.kr/), Mar 2018 - Present

||<span style="color:rgb(38, 124, 185)">GPA</span>|<span style="color:rgb(38, 124, 185)">Rank</span>|<span style="color:rgb(38, 124, 185)">Score</span>|
|----|----|----|----|
|Cumulative|4.3|3/215|97.7|

---

#### Awards and Experiences
Hanyang academic best award, Mar 2021(Expected)

National science and engineering scholarship, Aug 2020

Fourth industrial revolution program Completion, Jun 2020

Hanyang academic excellence award, Mar 2019

Samsung dream class Math-tutor program Completion, Jan 2019

Hanyang abroad student tutoring Dynamics-tutor program Completion, Jul 2020

Hanyang abroad student tutoring Mechanics of Materials-tutor program Completion, Mar 2021(Expected)

Hanyang abroad student tutoring Thermodynamics-tutor program Completion, Mar 2021(Expected)

---

#### Personal
I like to sing in choir. so I'm in charge of the bass part of my university choir club GLEE!
<br>
come visit [GLEE](https://www.youtube.com/channel/UCd3RBgdgh2xeIMHPRJBOFDw) Choir Club!

I also like to collect shoes!
<br>
come visit my [Shoes Instagram](https://www.instagram.com/honey__ksh/)

My energy comes from meeting new people and having new experiences!!

---

#### Contact
SukHeon Kang
<br>
ksh8048(at)hanyang.ac.kr or tjrgjs8048(at)naver.com
<br>
4th year, B.S.
<br>
HANYANG UNIV
<br>
Seoul, Republic of Korea

---

#### Contact easily through below!
Everything is welcome:)
<br>
<input type="text" name="name" placeholder="성함을 입력해주세요">
<br>
<input type="text" name="email" placeholder="메일 주소를 입력해주세요">
<br>
<input type="text" name="phone" placeholder="연락처를 입력해주세요 (생략 가능)">
<br>
<textarea name="message" rows="5" placeholder="내용을 입력해주세요 "></textarea>
<br>
<input type="button" name="submit" class="btn white" value="메일보내기"/>

<script type= "text/javascript" src="https://cdn.jsdelivr.net/npm/emailjs-com@2/dist/email.min.js">
</script>
<script type="text/javascript">
	
	$(document).ready(function() {
		emailjs.init("user_W8k3o3ocIJ3fuVK8YTRFe");		
        
        $('input[name=submit]').click(function(){       	 
          
          var templateParams = {	
                name: $('input[name=name]').val(),
                phone: $('input[name=phone]').val(), 
                email : $('input[name=email]').val(),
                message : $('textarea[name=message]').val()
           				};
                    
                	
         emailjs.sendForm('service_sr7iwuc', 'template_0r0a8mh', templateParams)
         	    .then(function(response) {
         	       console.log('SUCCESS!', response.status, response.text);
         	    }, function(error) {
         	       console.log('FAILED...', error);
         	    });
         	       


        });
        
	  });
    

	</script>
(Last Update: 1/15/2021)

