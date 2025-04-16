# Q4-Project
playSound("creepy-whale-song-323612.mp3", false);
setProperty("image1", "image", "https://i.guim.co.uk/img/media/3ccc8cd668c4d930b947642ae64dd32e58305fa9/58_0_3384_2031/master/3384.jpg?width=620&dpr=1&s=none&crop=none");
setProperty("textbox", "text", "Welcome to choose your own pathway!");
setProperty("Textbox2", "text", "Click the continue button to play.");
setProperty("button1", "text", "Continue");
onEvent("button1", "click", function( ) {
  setScreen("screen2");
});
setProperty("Slide2textbox1", "text", "Choose your character");
onEvent("button2", "click", function( ) {
  setScreen("screen3");
  playSound("sound://category_male_voiceover/ready_male.mp3", false);
});
onEvent("button3", "click", function( ) {
  setScreen("screen3");
  playSound("sound://category_female_voiceover/ready_female.mp3", false);
});
onEvent("button4", "click", function( ) {
  setScreen("screen4");
});
