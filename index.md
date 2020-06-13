## Voice Cloning - Neural TTS
<head>
    <link rel="stylesheet" href="w3.css">
    <title>Voice cloning MOS</title>
    <style>
         h1 {
            text-align: center;
            margin: 20px;
       	    }
	h3{
	  text-align: center;
	  text-justify: inter-word;
	}
	h6{
 	 text-align: justify;
  	text-justify: inter-word;
	}
	.grrp{
	text-align: center;
	padding: 10px;
	margin: 10px;
	border: 1px solid #c6c6c6;
		}
	.grrp1{
	text-align: center;
	padding: 10px;
	margin: 10px;
		}
    </style>
</head>
<body>
<div class="grrp1">
  <form id="fs-frm" name="survey-form-test" accept-charset="utf-8" action="https://formspree.io/sachinprakash.itis@gmail.com" method="post">
    <fieldset id="fs-frm-inputs" style="border:0px solid black;">
      <label for="email-address">Email Address</label>
      <input type="email" name="_replyto" id="email-address" placeholder="email@domain.com" required=""><br><br>
      <h6>Please listen the the audio below anf asibfaiubfi aebfiauebfiaebfiaebfi</h6>
      <div class='grrp'>
	<h3>Speaker1</h3>
        <table border="0" width="20%" style="font-size:16px">
          <tbody><tr><th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
          Speaker Ground Truth</th></tr>
          <tr><td><audio controls="" preload="none" style="height:30px">
          <source src="https://sachp1.github.io/speaker2/will_smith_orig.mp3" type="audio/mpeg">audio not supported</audio>
          </td></tr></tbody></table>
          <h6>Listen to the synthesized audio and chose a rating</h6>
          <table border="0" width="20%" style="font-size:16px">
              <tbody>
                <tr>
                <th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
                  Wavenet vocoder</th></tr>
              <tr>
              <td>
              <audio controls="" preload="none" style="height:30px"><source src="https://sachp1.github.io/speaker2/will_smith.mp3" type="audio/mpeg">audio not supported</audio>
                </td></tr>
              </tbody></table>
              <label for="n_1">1. How well does Wavenet resemble Ground truth.</label>
              <select name="n_1" id="n_1_1" required="">
                <option value="Choose" selected="" disabled="">Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
		  <label for="n_1">1. How well does Wavenet resemble Ground truth.</label>
              <select name="n_1" id="n_1_2" required="">
                <option value="Choose" selected="" disabled="">Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
		 <label for="n_1">1. How well does Wavenet resemble Ground truth.</label>
              <select name="n_1" id="n_1_3" required="">
                <option value="Choose" selected="" disabled="">Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
	  <table border="0" width="20%" style="font-size:16px">
            <tbody>
              <tr>
                <th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">WAVEGLOW vocoder</th></tr>
              <tr>
                <td><audio controls="" preload="none" style="height:30px">
                  <source src="https://sachp1.github.io/speaker1/steve_jobs.mp3" type="audio/mpeg">audio not supported</audio>
                  </td></tr>
              </tbody>
            </table>
              <label for="g_1">1. How well does Wavenet resemble Ground truth.</label>
              <select name="g_1" id="g_1_1" required="">
                <option value="Choose" selected="" disabled="">Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
		  <label for="g_2">1. How well does Wavenet resemble Ground truth.</label>
              <select name="g_1" id="g_1_2" required="">
                <option value="Choose" selected="" disabled="">Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
		 <label for="g_1">1. How well does Wavenet resemble Ground truth.</label>
              <select name="g_1" id="g_1_3" required="">
                <option value="Choose" selected="" disabled="">Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
   	</div><br><br>
	<div class='grrp'>
	<h3>Speaker2</h3>
        <table border="0" width="20%" style="font-size:16px">
          <tbody><tr><th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
          Speaker Ground Truth</th></tr>
          <tr><td><audio controls="" preload="none" style="height:30px">
          <source src="https://sachp1.github.io/speaker2/will_smith_orig.mp3" type="audio/mpeg">audio not supported</audio>
          </td></tr></tbody></table>
          <h6>Listen to the synthesized audio and chose a rating</h6>
          <table border="0" width="20%" style="font-size:16px">
              <tbody>
                <tr>
                <th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
                  Wavenet vocoder</th></tr>
              <tr>
              <td>
              <audio controls="" preload="none" style="height:30px"><source src="https://sachp1.github.io/speaker2/will_smith.mp3" type="audio/mpeg">audio not supported</audio>
                </td></tr>
              </tbody></table>
              <label for="n_2">1. How well does Wavenet resemble Ground truth.</label>
              <select name="n_2" id="n_2_1" required="">
                <option value="Choose" selected="" disabled="">Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
		  <label for="n_2">1. How well does Wavenet resemble Ground truth.</label>
              <select name="n_2" id="n_2_2" required="">
                <option value="Choose" selected="" disabled="">Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
		 <label for="n_2">1. How well does Wavenet resemble Ground truth.</label>
              <select name="n_2" id="n_2_3" required="">
                <option value="Choose" selected="" disabled="">Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
	  <table border="0" width="20%" style="font-size:16px">
            <tbody>
              <tr>
                <th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">WAVEGLOW vocoder</th></tr>
              <tr>
                <td><audio controls="" preload="none" style="height:30px">
                  <source src="https://sachp1.github.io/speaker1/steve_jobs.mp3" type="audio/mpeg">audio not supported</audio>
                  </td></tr>
              </tbody>
            </table>
              <label for="g_2">1. How well does Wavenet resemble Ground truth.</label>
              <select name="g_2" id="g_2_1" required="">
                <option value="Choose" selected="" disabled="">Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
		  <label for="g_2">1. How well does Wavenet resemble Ground truth.</label>
              <select name="g_2" id="g_2_2" required="">
                <option value="Choose" selected="" disabled="">Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
		 <label for="g_2">1. How well does Wavenet resemble Ground truth.</label>
              <select name="g_2" id="g_2_3" required>
                <option value="">Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
   	</div>
	    <button type="submit">Send Responses</button>

