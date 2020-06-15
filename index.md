###### Please enter your email ID and rate the generated audio files
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
  <form id="fs-frm" name="survey-form-test" accept-charset="utf-8" action="https://formspree.io/sachinprakash313@gmail.com" method="post">
    <fieldset id="fs-frm-inputs" style="border:0px solid black;">
      <label for="email-address">Email Address</label>
      <input type="email" name="_replyto" id="email-address" placeholder="email@domain.com" required=""><br><br>
      <p>Listen to the original audio files of 20 different speakers and provide feedback on the synthesized waveforms produced using wavenet and WAVEGLOW vocoders</p>
  <div class='grrp'>
    <h3>Speaker1</h3>
        <table border="0" width="20%" style="font-size:16px">
          <tbody><tr><th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
          Speaker Ground Truth</th></tr>
          <tr><td><audio controls="" preload="none" style="height:30px">
          <source src="https://sachp1.github.io/speaker2/will_smith_orig.mp3" type="audio/mpeg">audio not supported</audio>
          </td></tr></tbody></table>
          <table style="width:100%; font-size:12px; text-align: left;">
          <tbody><tr>
          <th>Sentence</th>
          <th>"An intelligent city is an urban area that uses different types of electronic internet of things sensors"</th>
          </tr>
          </tbody></table> <br>
          <table border="0" width="20%" style="font-size:16px">
              <tbody>
                <tr>
                <th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
                  Wavenet vocoder</th></tr>
              <tr>
              <td>
              <audio controls="" preload="none" style="height:30px"><source src="https://sachp1.github.io/speaker2/wnsamples/will_smith.mp3" type="audio/mpeg">audio not supported</audio>
                </td></tr>
              </tbody></table>
              <label for="sim_n">How well does Wavenet resemble Ground truth</label>
              <select name="sim_n" id="sim_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_n">How would you rate the speech Quality (clarity)</label>
              <select name="speech_n" id="speech_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_n">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_n" id="synth_n" required="">
                <option value="" selected disabled>Choose</option>
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
                  <source src="https://sachp1.github.io/speaker2/wgsamples/will_smith.mp3" type="audio/mpeg">audio not supported</audio>
                  </td></tr>
              </tbody>
            </table>
              <label for="sim_g">How well does WAVEGLOW resemble Ground truth</label>
              <select name="sim_g" id="sim_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_g">How would you rate the speech Quality (clarity)</label>
              <select name="speech_g" id="speech_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_g">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_g" id="synth_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
    </div>
    <br><br>
  <div class='grrp'>
    <h3>Speaker2</h3>
        <table border="0" width="20%" style="font-size:16px">
          <tbody><tr><th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
          Speaker Ground Truth</th></tr>
          <tr><td><audio controls="" preload="none" style="height:30px">
          <source src="https://sachp1.github.io/speaker2/ogsamples/benedict_cumberbatch.mp3" type="audio/mpeg">audio not supported</audio>
          </td></tr></tbody></table>
          <table style="width:100%; font-size:12px; text-align: left;">
          <tbody><tr>
          <th>Sentence</th>
          <th>"An intelligent city is an urban area that uses different types of electronic internet of things sensors"</th>
          </tr>
          </tbody></table><br>
          <table border="0" width="20%" style="font-size:16px">
              <tbody>
                <tr>
                <th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
                  Wavenet vocoder</th></tr>
              <tr>
              <td>
              <audio controls="" preload="none" style="height:30px"><source src="https://sachp1.github.io/speaker2/wnsamples/benedict_cumberbatch.mp3" type="audio/mpeg">audio not supported</audio>
                </td></tr>
              </tbody></table>
              <label for="sim_n">How well does Wavenet resemble Ground truth</label>
              <select name="sim_n" id="sim_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_n">How would you rate the speech Quality (clarity)</label>
              <select name="speech_n" id="speech_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_n">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_n" id="synth_n" required="">
                <option value="" selected disabled>Choose</option>
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
                  <source src="https://sachp1.github.io/speaker2/wgsamples/benedict_cumberbatch.mp3" type="audio/mpeg">audio not supported</audio>
                  </td></tr>
              </tbody>
            </table>
              <label for="sim_g">How well does WAVEGLOW resemble Ground truth</label>
              <select name="sim_g" id="sim_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_g">How would you rate the speech Quality (clarity)</label>
              <select name="speech_g" id="speech_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_g">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_g" id="synth_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
    </div>
    <br>
  <div class='grrp'>
    <h3>Speaker3</h3>
        <table border="0" width="20%" style="font-size:16px">
          <tbody><tr><th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
          Speaker Ground Truth</th></tr>
          <tr><td><audio controls="" preload="none" style="height:30px">
          <source src="https://sachp1.github.io/speaker2/ogsamples/bill_gates.mp3" type="audio/mpeg">audio not supported</audio>
          </td></tr></tbody></table>
          <table style="width:100%; font-size:12px; text-align: left;">
          <tbody><tr>
          <th>Sentence</th>
          <th>"An intelligent city is an urban area that uses different types of electronic internet of things sensors"</th>
          </tr>
          </tbody></table><br>
          <table border="0" width="20%" style="font-size:16px">
              <tbody>
                <tr>
                <th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
                  Wavenet vocoder</th></tr>
              <tr>
              <td>
              <audio controls="" preload="none" style="height:30px"><source src="https://sachp1.github.io/speaker2/wnsamples/bill_gates.mp3" type="audio/mpeg">audio not supported</audio>
                </td></tr>
              </tbody></table>
              <label for="sim_n">How well does Wavenet resemble Ground truth</label>
              <select name="sim_n" id="sim_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_n">How would you rate the speech Quality (clarity)</label>
              <select name="speech_n" id="speech_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_n">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_n" id="synth_n" required="">
                <option value="" selected disabled>Choose</option>
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
                  <source src="https://sachp1.github.io/speaker2/wgsamples/bill_gates.mp3" type="audio/mpeg">audio not supported</audio>
                  </td></tr>
              </tbody>
            </table>
              <label for="sim_g">How well does WAVEGLOW resemble Ground truth</label>
              <select name="sim_g" id="sim_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_g">How would you rate the speech Quality (clarity)</label>
              <select name="speech_g" id="speech_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_g">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_g" id="synth_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
    </div>
    <br>
  <div class='grrp'>
    <h3>Speaker4</h3>
        <table border="0" width="20%" style="font-size:16px">
          <tbody><tr><th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
          Speaker Ground Truth</th></tr>
          <tr><td><audio controls="" preload="none" style="height:30px">
          <source src="https://sachp1.github.io/speaker2/ogsamples/daniel_radcliffe.mp3" type="audio/mpeg">audio not supported</audio>
          </td></tr></tbody></table>
          <table style="width:100%; font-size:12px; text-align: left;">
          <tbody><tr>
          <th>Sentence</th>
          <th>"An intelligent city is an urban area that uses different types of electronic internet of things sensors"</th>
          </tr>
          </tbody></table><br>
          <table border="0" width="20%" style="font-size:16px">
              <tbody>
                <tr>
                <th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
                  Wavenet vocoder</th></tr>
              <tr>
              <td>
              <audio controls="" preload="none" style="height:30px"><source src="https://sachp1.github.io/speaker2/wnsamples/daniel_radcliffe.mp3" type="audio/mpeg">audio not supported</audio>
                </td></tr>
              </tbody></table>
              <label for="sim_n">How well does Wavenet resemble Ground truth</label>
              <select name="sim_n" id="sim_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_n">How would you rate the speech Quality (clarity)</label>
              <select name="speech_n" id="speech_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_n">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_n" id="synth_n" required="">
                <option value="" selected disabled>Choose</option>
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
                  <source src="https://sachp1.github.io/speaker2/wgsamples/daniel_radcliffe.mp3" type="audio/mpeg">audio not supported</audio>
                  </td></tr>
              </tbody>
            </table>
              <label for="sim_g">How well does WAVEGLOW resemble Ground truth</label>
              <select name="sim_g" id="sim_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_g">How would you rate the speech Quality (clarity)</label>
              <select name="speech_g" id="speech_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_g">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_g" id="synth_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
    </div>
    <br>  
  <div class='grrp'>
    <h3>Speaker5</h3>
        <table border="0" width="20%" style="font-size:16px">
          <tbody><tr><th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
          Speaker Ground Truth</th></tr>
          <tr><td><audio controls="" preload="none" style="height:30px">
          <source src="https://sachp1.github.io/speaker2/ogsamples/ellis.mp3" type="audio/mpeg">audio not supported</audio>
          </td></tr></tbody></table>
          <table style="width:100%; font-size:12px; text-align: left;">
          <tbody><tr>
          <th>Sentence</th>
          <th>"An intelligent city is an urban area that uses different types of electronic internet of things sensors"</th>
          </tr>
          </tbody></table><br>
          <table border="0" width="20%" style="font-size:16px">
              <tbody>
                <tr>
                <th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
                  Wavenet vocoder</th></tr>
              <tr>
              <td>
              <audio controls="" preload="none" style="height:30px"><source src="https://sachp1.github.io/speaker2/wnsamples/ellis.mp3" type="audio/mpeg">audio not supported</audio>
                </td></tr>
              </tbody></table>
              <label for="sim_n">How well does Wavenet resemble Ground truth</label>
              <select name="sim_n" id="sim_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_n">How would you rate the speech Quality (clarity)</label>
              <select name="speech_n" id="speech_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_n">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_n" id="synth_n" required="">
                <option value="" selected disabled>Choose</option>
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
                  <source src="https://sachp1.github.io/speaker2/wgsamples/ellis.mp3" type="audio/mpeg">audio not supported</audio>
                  </td></tr>
              </tbody>
            </table>
              <label for="sim_g">How well does WAVEGLOW resemble Ground truth</label>
              <select name="sim_g" id="sim_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_g">How would you rate the speech Quality (clarity)</label>
              <select name="speech_g" id="speech_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_g">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_g" id="synth_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
    </div>
    <br>
  <div class='grrp'>
    <h3>Speaker6</h3>
        <table border="0" width="20%" style="font-size:16px">
          <tbody><tr><th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
          Speaker Ground Truth</th></tr>
          <tr><td><audio controls="" preload="none" style="height:30px">
          <source src="https://sachp1.github.io/speaker2/ogsamples/james_cordon.mp3" type="audio/mpeg">audio not supported</audio>
          </td></tr></tbody></table>
          <table style="width:100%; font-size:12px; text-align: left;">
          <tbody><tr>
          <th>Sentence</th>
          <th>"An intelligent city is an urban area that uses different types of electronic internet of things sensors"</th>
          </tr>
          </tbody></table><br>
          <table border="0" width="20%" style="font-size:16px">
              <tbody>
                <tr>
                <th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
                  Wavenet vocoder</th></tr>
              <tr>
              <td>
              <audio controls="" preload="none" style="height:30px"><source src="https://sachp1.github.io/speaker2/wnsamples/james_cordon.mp3" type="audio/mpeg">audio not supported</audio>
                </td></tr>
              </tbody></table>
              <label for="sim_n">How well does Wavenet resemble Ground truth</label>
              <select name="sim_n" id="sim_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_n">How would you rate the speech Quality (clarity)</label>
              <select name="speech_n" id="speech_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_n">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_n" id="synth_n" required="">
                <option value="" selected disabled>Choose</option>
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
                  <source src="https://sachp1.github.io/speaker2/wgsamples/james_cordon.mp3" type="audio/mpeg">audio not supported</audio>
                  </td></tr>
              </tbody>
            </table>
              <label for="sim_g">How well does WAVEGLOW resemble Ground truth</label>
              <select name="sim_g" id="sim_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_g">How would you rate the speech Quality (clarity)</label>
              <select name="speech_g" id="speech_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_g">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_g" id="synth_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
    </div>
    <br>
  <div class='grrp'>
    <h3>Speaker7</h3>
        <table border="0" width="20%" style="font-size:16px">
          <tbody><tr><th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
          Speaker Ground Truth</th></tr>
          <tr><td><audio controls="" preload="none" style="height:30px">
          <source src="https://sachp1.github.io/speaker2/ogsamples/joaquin.mp3" type="audio/mpeg">audio not supported</audio>
          </td></tr></tbody></table>
          <table style="width:100%; font-size:12px; text-align: left;">
          <tbody><tr>
          <th>Sentence</th>
          <th>"An intelligent city is an urban area that uses different types of electronic internet of things sensors"</th>
          </tr>
          </tbody></table><br>
          <table border="0" width="20%" style="font-size:16px">
              <tbody>
                <tr>
                <th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
                  Wavenet vocoder</th></tr>
              <tr>
              <td>
              <audio controls="" preload="none" style="height:30px"><source src="https://sachp1.github.io/speaker2/wnsamples/joaquin.mp3" type="audio/mpeg">audio not supported</audio>
                </td></tr>
              </tbody></table>
              <label for="sim_n">How well does Wavenet resemble Ground truth</label>
              <select name="sim_n" id="sim_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_n">How would you rate the speech Quality (clarity)</label>
              <select name="speech_n" id="speech_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_n">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_n" id="synth_n" required="">
                <option value="" selected disabled>Choose</option>
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
                  <source src="https://sachp1.github.io/speaker2/wgsamples/joaquin.mp3" type="audio/mpeg">audio not supported</audio>
                  </td></tr>
              </tbody>
            </table>
              <label for="sim_g">How well does WAVEGLOW resemble Ground truth</label>
              <select name="sim_g" id="sim_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_g">How would you rate the speech Quality (clarity)</label>
              <select name="speech_g" id="speech_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_g">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_g" id="synth_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
    </div>
    <br>
  <div class='grrp'>
    <h3>Speaker8</h3>
        <table border="0" width="20%" style="font-size:16px">
          <tbody><tr><th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
          Speaker Ground Truth</th></tr>
          <tr><td><audio controls="" preload="none" style="height:30px">
          <source src="https://sachp1.github.io/speaker2/ogsamples/morgan_freeman.mp3" type="audio/mpeg">audio not supported</audio>
          </td></tr></tbody></table>
          <table style="width:100%; font-size:12px; text-align: left;">
          <tbody><tr>
          <th>Sentence</th>
          <th>"An intelligent city is an urban area that uses different types of electronic internet of things sensors"</th>
          </tr>
          </tbody></table><br>
          <table border="0" width="20%" style="font-size:16px">
              <tbody>
                <tr>
                <th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
                  Wavenet vocoder</th></tr>
              <tr>
              <td>
              <audio controls="" preload="none" style="height:30px"><source src="https://sachp1.github.io/speaker2/wnsamples/morgan_freeman.mp3" type="audio/mpeg">audio not supported</audio>
                </td></tr>
              </tbody></table>
              <label for="sim_n">How well does Wavenet resemble Ground truth</label>
              <select name="sim_n" id="sim_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_n">How would you rate the speech Quality (clarity)</label>
              <select name="speech_n" id="speech_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_n">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_n" id="synth_n" required="">
                <option value="" selected disabled>Choose</option>
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
                  <source src="https://sachp1.github.io/speaker2/wgsamples/morgan_freeman.mp3" type="audio/mpeg">audio not supported</audio>
                  </td></tr>
              </tbody>
            </table>
              <label for="sim_g">How well does WAVEGLOW resemble Ground truth</label>
              <select name="sim_g" id="sim_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_g">How would you rate the speech Quality (clarity)</label>
              <select name="speech_g" id="speech_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_g">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_g" id="synth_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
    </div>
    <br>
  <div class='grrp'>
    <h3>Speaker9</h3>
        <table border="0" width="20%" style="font-size:16px">
          <tbody><tr><th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
          Speaker Ground Truth</th></tr>
          <tr><td><audio controls="" preload="none" style="height:30px">
          <source src="https://sachp1.github.io/speaker2/ogsamples/neil_degrasse_tyson.mp3" type="audio/mpeg">audio not supported</audio>
          </td></tr></tbody></table>
          <table style="width:100%; font-size:12px; text-align: left;">
          <tbody><tr>
          <th>Sentence</th>
          <th>"An intelligent city is an urban area that uses different types of electronic internet of things sensors"</th>
          </tr>
          </tbody></table><br>
          <table border="0" width="20%" style="font-size:16px">
              <tbody>
                <tr>
                <th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
                  Wavenet vocoder</th></tr>
              <tr>
              <td>
              <audio controls="" preload="none" style="height:30px"><source src="https://sachp1.github.io/speaker2/wnsamples/neil_degrasse_tyson.mp3" type="audio/mpeg">audio not supported</audio>
                </td></tr>
              </tbody></table>
              <label for="sim_n">How well does Wavenet resemble Ground truth</label>
              <select name="sim_n" id="sim_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_n">How would you rate the speech Quality (clarity)</label>
              <select name="speech_n" id="speech_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_n">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_n" id="synth_n" required="">
                <option value="" selected disabled>Choose</option>
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
                  <source src="https://sachp1.github.io/speaker2/wgsamples/neil_degrasse_tyson.mp3" type="audio/mpeg">audio not supported</audio>
                  </td></tr>
              </tbody>
            </table>
              <label for="sim_g">How well does WAVEGLOW resemble Ground truth</label>
              <select name="sim_g" id="sim_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_g">How would you rate the speech Quality (clarity)</label>
              <select name="speech_g" id="speech_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_g">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_g" id="synth_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
    </div>
    <br>
  <div class='grrp'>
    <h3>Speaker10</h3>
        <table border="0" width="20%" style="font-size:16px">
          <tbody><tr><th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
          Speaker Ground Truth</th></tr>
          <tr><td><audio controls="" preload="none" style="height:30px">
          <source src="https://sachp1.github.io/speaker2/ogsamples/satya_nadella.mp3" type="audio/mpeg">audio not supported</audio>
          </td></tr></tbody></table>
          <table style="width:100%; font-size:12px; text-align: left;">
          <tbody><tr>
          <th>Sentence</th>
          <th>"An intelligent city is an urban area that uses different types of electronic internet of things sensors"</th>
          </tr>
          </tbody></table><br>
          <table border="0" width="20%" style="font-size:16px">
              <tbody>
                <tr>
                <th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
                  Wavenet vocoder</th></tr>
              <tr>
              <td>
              <audio controls="" preload="none" style="height:30px"><source src="https://sachp1.github.io/speaker2/wnsamples/satya_nadella.mp3" type="audio/mpeg">audio not supported</audio>
                </td></tr>
              </tbody></table>
              <label for="sim_n">How well does Wavenet resemble Ground truth</label>
              <select name="sim_n" id="sim_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_n">How would you rate the speech Quality (clarity)</label>
              <select name="speech_n" id="speech_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_n">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_n" id="synth_n" required="">
                <option value="" selected disabled>Choose</option>
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
                  <source src="https://sachp1.github.io/speaker2/wgsamples/satya_nadella.mp3" type="audio/mpeg">audio not supported</audio>
                  </td></tr>
              </tbody>
            </table>
              <label for="sim_g">How well does WAVEGLOW resemble Ground truth</label>
              <select name="sim_g" id="sim_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_g">How would you rate the speech Quality (clarity)</label>
              <select name="speech_g" id="speech_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_g">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_g" id="synth_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
    </div>
    <br>  <div class='grrp'>
    <h3>Speaker11</h3>
        <table border="0" width="20%" style="font-size:16px">
          <tbody><tr><th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
          Speaker Ground Truth</th></tr>
          <tr><td><audio controls="" preload="none" style="height:30px">
          <source src="https://sachp1.github.io/speaker2/ogsamples/speaker2.mp3" type="audio/mpeg">audio not supported</audio>
          </td></tr></tbody></table>
          <table style="width:100%; font-size:12px; text-align: left;">
          <tbody><tr>
          <th>Sentence</th>
          <th>"An intelligent city is an urban area that uses different types of electronic internet of things sensors"</th>
          </tr>
          </tbody></table><br>
          <table border="0" width="20%" style="font-size:16px">
              <tbody>
                <tr>
                <th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
                  Wavenet vocoder</th></tr>
              <tr>
              <td>
              <audio controls="" preload="none" style="height:30px"><source src="https://sachp1.github.io/speaker2/wnsamples/speaker2.mp3" type="audio/mpeg">audio not supported</audio>
                </td></tr>
              </tbody></table>
              <label for="sim_n">How well does Wavenet resemble Ground truth</label>
              <select name="sim_n" id="sim_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_n">How would you rate the speech Quality (clarity)</label>
              <select name="speech_n" id="speech_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_n">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_n" id="synth_n" required="">
                <option value="" selected disabled>Choose</option>
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
                  <source src="https://sachp1.github.io/speaker2/wgsamples/speaker2.mp3" type="audio/mpeg">audio not supported</audio>
                  </td></tr>
              </tbody>
            </table>
              <label for="sim_g">How well does WAVEGLOW resemble Ground truth</label>
              <select name="sim_g" id="sim_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_g">How would you rate the speech Quality (clarity)</label>
              <select name="speech_g" id="speech_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_g">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_g" id="synth_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
    </div>
    <br>
    <div class='grrp'>
    <h3>Speaker12</h3>
        <table border="0" width="20%" style="font-size:16px">
          <tbody><tr><th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
          Speaker Ground Truth</th></tr>
          <tr><td><audio controls="" preload="none" style="height:30px">
          <source src="https://sachp1.github.io/speaker2/ogsamples/speaker3.mp3" type="audio/mpeg">audio not supported</audio>
          </td></tr></tbody></table>
          <table style="width:100%; font-size:12px; text-align: left;">
          <tbody><tr>
          <th>Sentence</th>
          <th>"An intelligent city is an urban area that uses different types of electronic internet of things sensors"</th>
          </tr>
          </tbody></table><br>
          <table border="0" width="20%" style="font-size:16px">
              <tbody>
                <tr>
                <th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
                  Wavenet vocoder</th></tr>
              <tr>
              <td>
              <audio controls="" preload="none" style="height:30px"><source src="https://sachp1.github.io/speaker2/wnsamples/speaker3.mp3" type="audio/mpeg">audio not supported</audio>
                </td></tr>
              </tbody></table>
              <label for="sim_n">How well does Wavenet resemble Ground truth</label>
              <select name="sim_n" id="sim_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_n">How would you rate the speech Quality (clarity)</label>
              <select name="speech_n" id="speech_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_n">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_n" id="synth_n" required="">
                <option value="" selected disabled>Choose</option>
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
                  <source src="https://sachp1.github.io/speaker2/wgsamples/speaker3.mp3" type="audio/mpeg">audio not supported</audio>
                  </td></tr>
              </tbody>
            </table>
              <label for="sim_g">How well does WAVEGLOW resemble Ground truth</label>
              <select name="sim_g" id="sim_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_g">How would you rate the speech Quality (clarity)</label>
              <select name="speech_g" id="speech_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_g">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_g" id="synth_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
    </div>
    <br>
    <div class='grrp'>
    <h3>Speaker13</h3>
        <table border="0" width="20%" style="font-size:16px">
          <tbody><tr><th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
          Speaker Ground Truth</th></tr>
          <tr><td><audio controls="" preload="none" style="height:30px">
          <source src="https://sachp1.github.io/speaker2/ogsamples/speaker4.mp3" type="audio/mpeg">audio not supported</audio>
          </td></tr></tbody></table>
          <table style="width:100%; font-size:12px; text-align: left;">
          <tbody><tr>
          <th>Sentence</th>
          <th>"An intelligent city is an urban area that uses different types of electronic internet of things sensors"</th>
          </tr>
          </tbody></table><br>
          <table border="0" width="20%" style="font-size:16px">
              <tbody>
                <tr>
                <th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
                  Wavenet vocoder</th></tr>
              <tr>
              <td>
              <audio controls="" preload="none" style="height:30px"><source src="https://sachp1.github.io/speaker2/wnsamples/speaker4.mp3" type="audio/mpeg">audio not supported</audio>
                </td></tr>
              </tbody></table>
              <label for="sim_n">How well does Wavenet resemble Ground truth</label>
              <select name="sim_n" id="sim_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_n">How would you rate the speech Quality (clarity)</label>
              <select name="speech_n" id="speech_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_n">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_n" id="synth_n" required="">
                <option value="" selected disabled>Choose</option>
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
                  <source src="https://sachp1.github.io/speaker2/wgsamples/speaker4.mp3" type="audio/mpeg">audio not supported</audio>
                  </td></tr>
              </tbody>
            </table>
              <label for="sim_g">How well does WAVEGLOW resemble Ground truth</label>
              <select name="sim_g" id="sim_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_g">How would you rate the speech Quality (clarity)</label>
              <select name="speech_g" id="speech_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_g">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_g" id="synth_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
    </div>
    <br>
    <div class='grrp'>
    <h3>Speaker14</h3>
        <table border="0" width="20%" style="font-size:16px">
          <tbody><tr><th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
          Speaker Ground Truth</th></tr>
          <tr><td><audio controls="" preload="none" style="height:30px">
          <source src="https://sachp1.github.io/speaker2/ogsamples/speaker5.mp3" type="audio/mpeg">audio not supported</audio>
          </td></tr></tbody></table>
          <table style="width:100%; font-size:12px; text-align: left;">
          <tbody><tr>
          <th>Sentence</th>
          <th>"An intelligent city is an urban area that uses different types of electronic internet of things sensors"</th>
          </tr>
          </tbody></table><br>
          <table border="0" width="20%" style="font-size:16px">
              <tbody>
                <tr>
                <th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
                  Wavenet vocoder</th></tr>
              <tr>
              <td>
              <audio controls="" preload="none" style="height:30px"><source src="https://sachp1.github.io/speaker2/wnsamples/speaker5.mp3" type="audio/mpeg">audio not supported</audio>
                </td></tr>
              </tbody></table>
              <label for="sim_n">How well does Wavenet resemble Ground truth</label>
              <select name="sim_n" id="sim_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_n">How would you rate the speech Quality (clarity)</label>
              <select name="speech_n" id="speech_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_n">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_n" id="synth_n" required="">
                <option value="" selected disabled>Choose</option>
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
                  <source src="https://sachp1.github.io/speaker2/wgsamples/speaker5.mp3" type="audio/mpeg">audio not supported</audio>
                  </td></tr>
              </tbody>
            </table>
              <label for="sim_g">How well does WAVEGLOW resemble Ground truth</label>
              <select name="sim_g" id="sim_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_g">How would you rate the speech Quality (clarity)</label>
              <select name="speech_g" id="speech_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_g">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_g" id="synth_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
    </div>
    <br>
    <div class='grrp'>
    <h3>Speaker15</h3>
        <table border="0" width="20%" style="font-size:16px">
          <tbody><tr><th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
          Speaker Ground Truth</th></tr>
          <tr><td><audio controls="" preload="none" style="height:30px">
          <source src="https://sachp1.github.io/speaker2/ogsamples/speaker6.mp3" type="audio/mpeg">audio not supported</audio>
          </td></tr></tbody></table>
          <table style="width:100%; font-size:12px; text-align: left;">
          <tbody><tr>
          <th>Sentence</th>
          <th>"An intelligent city is an urban area that uses different types of electronic internet of things sensors"</th>
          </tr>
          </tbody></table><br>
          <table border="0" width="20%" style="font-size:16px">
              <tbody>
                <tr>
                <th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
                  Wavenet vocoder</th></tr>
              <tr>
              <td>
              <audio controls="" preload="none" style="height:30px"><source src="https://sachp1.github.io/speaker2/wnsamples/speaker6.mp3" type="audio/mpeg">audio not supported</audio>
                </td></tr>
              </tbody></table>
              <label for="sim_n">How well does Wavenet resemble Ground truth</label>
              <select name="sim_n" id="sim_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_n">How would you rate the speech Quality (clarity)</label>
              <select name="speech_n" id="speech_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_n">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_n" id="synth_n" required="">
                <option value="" selected disabled>Choose</option>
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
                  <source src="https://sachp1.github.io/speaker2/wgsamples/speaker6.mp3" type="audio/mpeg">audio not supported</audio>
                  </td></tr>
              </tbody>
            </table>
              <label for="sim_g">How well does WAVEGLOW resemble Ground truth</label>
              <select name="sim_g" id="sim_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_g">How would you rate the speech Quality (clarity)</label>
              <select name="speech_g" id="speech_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_g">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_g" id="synth_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
    </div>
    <br>
    <div class='grrp'>
    <h3>Speaker16</h3>
        <table border="0" width="20%" style="font-size:16px">
          <tbody><tr><th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
          Speaker Ground Truth</th></tr>
          <tr><td><audio controls="" preload="none" style="height:30px">
          <source src="https://sachp1.github.io/speaker2/ogsamples/speaker7.mp3" type="audio/mpeg">audio not supported</audio>
          </td></tr></tbody></table>
          <table style="width:100%; font-size:12px; text-align: left;">
          <tbody><tr>
          <th>Sentence</th>
          <th>"An intelligent city is an urban area that uses different types of electronic internet of things sensors"</th>
          </tr>
          </tbody></table><br>
          <table border="0" width="20%" style="font-size:16px">
              <tbody>
                <tr>
                <th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
                  Wavenet vocoder</th></tr>
              <tr>
              <td>
              <audio controls="" preload="none" style="height:30px"><source src="https://sachp1.github.io/speaker2/wnsamples/speaker7.mp3" type="audio/mpeg">audio not supported</audio>
                </td></tr>
              </tbody></table>
              <label for="sim_n">How well does Wavenet resemble Ground truth</label>
              <select name="sim_n" id="sim_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_n">How would you rate the speech Quality (clarity)</label>
              <select name="speech_n" id="speech_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_n">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_n" id="synth_n" required="">
                <option value="" selected disabled>Choose</option>
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
                  <source src="https://sachp1.github.io/speaker2/wgsamples/speaker7.mp3" type="audio/mpeg">audio not supported</audio>
                  </td></tr>
              </tbody>
            </table>
              <label for="sim_g">How well does WAVEGLOW resemble Ground truth</label>
              <select name="sim_g" id="sim_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_g">How would you rate the speech Quality (clarity)</label>
              <select name="speech_g" id="speech_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_g">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_g" id="synth_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
    </div>
    <br>
    <div class='grrp'>
    <h3>Speaker17</h3>
        <table border="0" width="20%" style="font-size:16px">
          <tbody><tr><th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
          Speaker Ground Truth</th></tr>
          <tr><td><audio controls="" preload="none" style="height:30px">
          <source src="https://sachp1.github.io/speaker2/ogsamples/speaker8.mp3" type="audio/mpeg">audio not supported</audio>
          </td></tr></tbody></table>
          <table style="width:100%; font-size:12px; text-align: left;">
          <tbody><tr>
          <th>Sentence</th>
          <th>"An intelligent city is an urban area that uses different types of electronic internet of things sensors"</th>
          </tr>
          </tbody></table><br>
          <table border="0" width="20%" style="font-size:16px">
              <tbody>
                <tr>
                <th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
                  Wavenet vocoder</th></tr>
              <tr>
              <td>
              <audio controls="" preload="none" style="height:30px"><source src="https://sachp1.github.io/speaker2/wnsamples/speaker8.mp3" type="audio/mpeg">audio not supported</audio>
                </td></tr>
              </tbody></table>
              <label for="sim_n">How well does Wavenet resemble Ground truth</label>
              <select name="sim_n" id="sim_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_n">How would you rate the speech Quality (clarity)</label>
              <select name="speech_n" id="speech_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_n">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_n" id="synth_n" required="">
                <option value="" selected disabled>Choose</option>
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
                  <source src="https://sachp1.github.io/speaker2/wgsamples/speaker8.mp3" type="audio/mpeg">audio not supported</audio>
                  </td></tr>
              </tbody>
            </table>
              <label for="sim_g">How well does WAVEGLOW resemble Ground truth</label>
              <select name="sim_g" id="sim_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_g">How would you rate the speech Quality (clarity)</label>
              <select name="speech_g" id="speech_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_g">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_g" id="synth_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
    </div>
    <br>
    <div class='grrp'>
    <h3>Speaker18</h3>
        <table border="0" width="20%" style="font-size:16px">
          <tbody><tr><th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
          Speaker Ground Truth</th></tr>
          <tr><td><audio controls="" preload="none" style="height:30px">
          <source src="https://sachp1.github.io/speaker2/ogsamples/kate.mp3" type="audio/mpeg">audio not supported</audio>
          </td></tr></tbody></table>
          <table style="width:100%; font-size:12px; text-align: left;">
          <tbody><tr>
          <th>Sentence</th>
          <th>"An intelligent city is an urban area that uses different types of electronic internet of things sensors"</th>
          </tr>
          </tbody></table><br>
          <table border="0" width="20%" style="font-size:16px">
              <tbody>
                <tr>
                <th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
                  Wavenet vocoder</th></tr>
              <tr>
              <td>
              <audio controls="" preload="none" style="height:30px"><source src="https://sachp1.github.io/speaker2/wnsamples/kate.mp3" type="audio/mpeg">audio not supported</audio>
                </td></tr>
              </tbody></table>
              <label for="sim_n">How well does Wavenet resemble Ground truth</label>
              <select name="sim_n" id="sim_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_n">How would you rate the speech Quality (clarity)</label>
              <select name="speech_n" id="speech_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_n">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_n" id="synth_n" required="">
                <option value="" selected disabled>Choose</option>
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
                  <source src="https://sachp1.github.io/speaker2/wgsamples/kate.mp3" type="audio/mpeg">audio not supported</audio>
                  </td></tr>
              </tbody>
            </table>
              <label for="sim_g">How well does WAVEGLOW resemble Ground truth</label>
              <select name="sim_g" id="sim_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_g">How would you rate the speech Quality (clarity)</label>
              <select name="speech_g" id="speech_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_g">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_g" id="synth_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
    </div>
    <br>
    <div class='grrp'>
    <h3>Speaker19</h3>
        <table border="0" width="20%" style="font-size:16px">
          <tbody><tr><th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
          Speaker Ground Truth</th></tr>
          <tr><td><audio controls="" preload="none" style="height:30px">
          <source src="https://sachp1.github.io/speaker2/ogsamples/sasi_tharoor.mp3" type="audio/mpeg">audio not supported</audio>
          </td></tr></tbody></table>
          <table style="width:100%; font-size:12px; text-align: left;">
          <tbody><tr>
          <th>Sentence</th>
          <th>"An intelligent city is an urban area that uses different types of electronic internet of things sensors"</th>
          </tr>
          </tbody></table><br>
          <table border="0" width="20%" style="font-size:16px">
              <tbody>
                <tr>
                <th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
                  Wavenet vocoder</th></tr>
              <tr>
              <td>
              <audio controls="" preload="none" style="height:30px"><source src="https://sachp1.github.io/speaker2/wnsamples/sasi_tharoor.mp3" type="audio/mpeg">audio not supported</audio>
                </td></tr>
              </tbody></table>
              <label for="sim_n">How well does Wavenet resemble Ground truth</label>
              <select name="sim_n" id="sim_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_n">How would you rate the speech Quality (clarity)</label>
              <select name="speech_n" id="speech_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_n">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_n" id="synth_n" required="">
                <option value="" selected disabled>Choose</option>
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
                  <source src="https://sachp1.github.io/speaker2/wgsamples/sasi_tharoor.mp3" type="audio/mpeg">audio not supported</audio>
                  </td></tr>
              </tbody>
            </table>
              <label for="sim_g">How well does WAVEGLOW resemble Ground truth</label>
              <select name="sim_g" id="sim_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_g">How would you rate the speech Quality (clarity)</label>
              <select name="speech_g" id="speech_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_g">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_g" id="synth_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
    </div>
    <br>
    <div class='grrp'>
    <h3>Speaker20</h3>
        <table border="0" width="20%" style="font-size:16px">
          <tbody><tr><th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
          Speaker Ground Truth</th></tr>
          <tr><td><audio controls="" preload="none" style="height:30px">
          <source src="https://sachp1.github.io/speaker2/ogsamples/trudeau.mp3" type="audio/mpeg">audio not supported</audio>
          </td></tr></tbody></table>
          <table style="width:100%; font-size:12px; text-align: left;">
          <tbody><tr>
          <th>Sentence</th>
          <th>"An intelligent city is an urban area that uses different types of electronic internet of things sensors"</th>
          </tr>
          </tbody></table><br>
          <table border="0" width="20%" style="font-size:16px">
              <tbody>
                <tr>
                <th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
                  Wavenet vocoder</th></tr>
              <tr>
              <td>
              <audio controls="" preload="none" style="height:30px"><source src="https://sachp1.github.io/speaker2/wnsamples/trudeau.mp3" type="audio/mpeg">audio not supported</audio>
                </td></tr>
              </tbody></table>
              <label for="sim_n">How well does Wavenet resemble Ground truth</label>
              <select name="sim_n" id="sim_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_n">How would you rate the speech Quality (clarity)</label>
              <select name="speech_n" id="speech_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_n">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_n" id="synth_n" required="">
                <option value="" selected disabled>Choose</option>
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
                  <source src="https://sachp1.github.io/speaker2/wgsamples/trudeau.mp3" type="audio/mpeg">audio not supported</audio>
                  </td></tr>
              </tbody>
            </table>
              <label for="sim_g">How well does WAVEGLOW resemble Ground truth</label>
              <select name="sim_g" id="sim_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_g">How would you rate the speech Quality (clarity)</label>
              <select name="speech_g" id="speech_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_g">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_g" id="synth_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
    </div>
    <br>
    <div class='grrp'>
    <h3>Speaker21</h3>
        <table border="0" width="20%" style="font-size:16px">
          <tbody><tr><th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
          Speaker Ground Truth</th></tr>
          <tr><td><audio controls="" preload="none" style="height:30px">
          <source src="https://sachp1.github.io/speaker2/ogsamples/steve_jobs.mp3" type="audio/mpeg">audio not supported</audio>
          </td></tr></tbody></table>
          <table style="width:100%; font-size:12px; text-align: left;">
          <tbody><tr>
          <th>Sentence</th>
          <th>"An intelligent city is an urban area that uses different types of electronic internet of things sensors"</th>
          </tr>
          </tbody></table><br>
          <table border="0" width="20%" style="font-size:16px">
              <tbody>
                <tr>
                <th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
                  Wavenet vocoder</th></tr>
              <tr>
              <td>
              <audio controls="" preload="none" style="height:30px"><source src="https://sachp1.github.io/speaker2/wnsamples/steve_jobs.mp3" type="audio/mpeg">audio not supported</audio>
                </td></tr>
              </tbody></table>
              <label for="sim_n">How well does Wavenet resemble Ground truth</label>
              <select name="sim_n" id="sim_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_n">How would you rate the speech Quality (clarity)</label>
              <select name="speech_n" id="speech_n" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_n">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_n" id="synth_n" required="">
                <option value="" selected disabled>Choose</option>
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
                  <source src="https://sachp1.github.io/speaker2/wgsamples/steve_jobs.mp3" type="audio/mpeg">audio not supported</audio>
                  </td></tr>
              </tbody>
            </table>
              <label for="sim_g">How well does WAVEGLOW resemble Ground truth</label>
              <select name="sim_g" id="sim_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
      <label for="speech_g">How would you rate the speech Quality (clarity)</label>
              <select name="speech_g" id="speech_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
     <label for="synth_g">How would you rate the synthesized audio (is the sentence fully reconstructed)<br></label>
              <select name="synth_g" id="synth_g" required="">
                <option value="" selected disabled>Choose</option>
                <option value="5">Excellent</option>
                <option value="4">Very Good</option>
                <option value="3">Good</option>
                <option value="2">Fair</option>
                <option value="1">Poor</option>
              </select><br>
    </div>
    <br>
  <button type="submit">Send Responses</button>
