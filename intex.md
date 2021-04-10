
<html>
<head>
<meta charset="utf-8" />

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@1,500&display=swap" rel="stylesheet">    
<link href="https://fonts.googleapis.com/css2?family=Sofia&display=swap" rel="stylesheet">
<link rel="stylesheet" href="styles.css">

</head>
<body>
<div class="container">
<div class="navigator">
<div class="left">
<div class="linknavi">
<a href="intex.html">HOME</a>
</div>
<div class="linknavi">
<a href="about.html">ABOUT</a>
</div>
</div>
<div class="right">
<div class="brand">
JAIRAM SU
</div>

</div>   

</div>
<div class="totalitem">
<div class="items">

<div class="single">

<div class="backimage" style="background-image: url(images/abstract-bright-bokeh-light-on-260nw-1662740479.jpg);"></div>
<div class="imgtext">
<div class="logo"><img src="images/kisspng-money-organization-consultant-curriculum-vitae-bio-5b0a1adec4feb5.6640365615273888948069.png"></div>
<div class="subtitle">BIO DATA</div>
</div>

</div>
<div class="single">
<div class="backimage" style="background-image: url(images/abstract-bright-bokeh-light-on-260nw-1662740479.jpg);"></div>
<div class="imgtext">
<div class="logo"><img src="Saved Pictures/kisspng-graduation-ceremony-square-academic-cap-student-sc-graduation-5ab9157e2c3485.5851822715220791021811.png"></div>
<div class="subtitle">COLLEGE</div>
</div>
</div>
<div class="single">
<div class="backimage" style="background-image: url(images/abstract-bright-bokeh-light-on-260nw-1662740479.jpg);"></div>
<div class="imgtext">
<div class="logo"><img src="Saved Pictures/kisspng-classroom-computer-icons-training-class-room-5abf42f5477d65.1832305615224839572928.png"></div>
<div class="subtitle">SCHOOL(12th & 10th)</div>
</div>
</div>
<div class="single">
<div class="backimage" style="background-image: url(images/abstract-bright-bokeh-light-on-260nw-1662740479.jpg);"></div>
<div class="imgtext">
<div class="logo"><img src="Saved Pictures/kisspng-computer-icons-icon-design-symbol-hobbies-5b20e848983d38.3426612315288832726236.png"></div>
<div class="subtitle">HOBBIES</div>
</div>
</div>
<div class="single">
<div class="backimage" style="background-image: url(images/abstract-bright-bokeh-light-on-260nw-1662740479.jpg);"></div>
<div class="imgtext">
<div class="logo"><img src="images/award.png"></div>
<div class="subtitle">ACHEIVEMENTS</div>
</div>
</div>
<div class="single">
<div class="backimage" style="background-image: url(images/abstract-bright-bokeh-light-on-260nw-1662740479.jpg);"></div>
<div class="imgtext">
<div class="logo"><img src="Saved Pictures/kisspng-rsum-curriculum-vitae-template-moto-highway-ra-resume-5b20f1098b9a26.0422724315288855135718.png"></div>
<div class="subtitle">RESUME</div>
</div>
</div>
</div>
</div>
</div>
</body>
<script>
const totalItem=document.querySelectorAll('.single')
totalItem.forEach(Single =>{
Single.addEventListener('mouseover',() =>{
console.log(Single.childNodes[1].classList);
Single.childNodes[1].classList.add('darkimg');
})
Single.addEventListener('mouseout',() =>{
console.log(Single.childNodes[1].classList);
Single.childNodes[1].classList.remove('darkimg');
})
})

</script>
</html>
