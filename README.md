# Quizzler
Quizz App

Created in Android Studio 3.2.1, run on Nexus 4 Android Emulator

This is a simple Quizz App, inspired by the awesome “Quiz Up” game. Category: Educational Apps.

Screen Captured on Android Emulator.

<!DOCTYPE html>
<html>
<head>
<style>
* {
    box-sizing: border-box;
}

.column {
    float: left;
    width: 50%;
    padding: 5px;
}

/* Clearfix (clear floats) */
.row::after {
    content: "";
    clear: both;
    display: table;
}
</style>
</head>
<body>

<h2>Images Side by Side</h2>
<p>How to create side-by-side images with the CSS float property:</p>

<div class="row">
  <div>
    <img src="https://github.com/kelvinator07/Quizzler/blob/master/Screenshot_2018-10-26-12-22-58.png" style="width:100%; float: left; width: 50%; padding: 5px;">
  </div>
  <div class="column">
    <img src="https://github.com/kelvinator07/Quizzler/blob/master/Screenshot_2018-10-26-12-23-44.png" style="width:100%; float: left; width: 50%; padding: 5px;">
  </div>
</div>

</body>
</html>

