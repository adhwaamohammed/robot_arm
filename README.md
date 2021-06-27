# robot_arm

<!DOCTYPE html>
<html>
<head>
<h1 style="background-color:DodgerBlue;">.</h1>

<meta name="viewport" content="width=device-width, initial-scale=1">
<style>

.slidecontainer {
  width: 50%;
  
}

.slider {
  -webkit-appearance: none;
  width: 100%;
  height: 10px;
  border-radius: 5px;
  background: #d3d3d3;
  outline: none;
  opacity: 0.7;
  -webkit-transition: .2s;
  transition: opacity .2s;
}

.slider:hover {
  opacity: 1;
}
<h1>center</h1>
.slider::-webkit-slider-thumb {
  -webkit-appearance: none;
  appearance: none;
  width: 23px;
  height: 24px;
  border: 0;
  background: url('contrasticon.png');
  cursor: pointer;
}

.slider::-moz-range-thumb {
  width: 23px;
  height: 24px;
  border: 0;
  background: url('contrasticon.png');
  cursor: pointer; 
}

</style>
</head>
<body>

 
<center/> <h1>محرك 1 </h1>
<div class="slidecontainer">
  <input type="range" min="0" max="180" value="50" class="slider" id="myRange">
  <p>Value: <span id="demo"></span></p>
</div> 

<h1>محرك2 </h1>
<div class="slidecontainer">
  <input type="range" min="0" max="180" value="90" class="slider" id="myRange">
  <p>Value: <span id="demo"></span></p>
</div> 

<h1>محرك3 </h1>
<div class="slidecontainer">
  <input type="range" min="0" max="180" value="90" class="slider" id="myRange">
  <p>Value: <span id="demo"></span></p>
</div> 

<h1>محرك4 </h1>
<div class="slidecontainer">
  <input type="range" min="0" max="180" value="90" class="slider" id="myRange">
  <p>Value: <span id="demo"></span></p>
</div> 

<h1>محرك5 </h1>
<div class="slidecontainer">
  <input type="range" min="0" max="180" value="90" class="slider" id="myRange">
  <p>Value: <span id="demo"></span></p>
</div> 

<h1>محرك6 </h1>
<div class="slidecontainer">
  <input type="range" min="0" max="180" value="80" class="slider" id="myRange">
  <p>Value: <span id="demo"></span></p>
</div> 
</body>
</html>

<style>
.container {
  height: 200px;
  position: relative;
  border: 10px ;
}

.vertical-left {
  margin: 0;
  position: absolute;
  top: -3%;
  -ms-transform: translateY(-100%);
  transform: translateY(-150%);
}
</style>

<div class="container">
  <div class="vertical-left">
        <button>تشغيل</button>
  <div class="vertical-left">
    <button>حفظ</button>

  </div>
</div>
<!DOCTYPE html>
<html>
<body>


<h1 style="background-color:DodgerBlue;">.</h1>
