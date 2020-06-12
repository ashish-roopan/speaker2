## Voice Cloning - Neural TTS

### Please listen to the 3 audio samples. 

<table border="0" width="20%" style="font-size:16px">
  <tbody>
  <tr><th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
    Speaker Ground Truth</th></tr>
    
  <tr>
  <td>
  <audio controls="" preload="none" style="height:30px">
<source src="https://sachp1.github.io/speaker2/will_smith_orig.mp3" type="audio/mpeg">audio not supported</audio>
    </td></tr><br><br>
    <tr>
    <th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
      Wavenet vocoder</th></tr>
  <tr>
  <td>
  <audio controls="" preload="none" style="height:30px">
<source src="https://sachp1.github.io/speaker2/will_smith.mp3" type="audio/mpeg">audio not supported</audio>
    </td></tr>
  
  <tr>
    <th bgcolor="#3cb371" style="white-space:nowrap;height:30px;min-width: 240px">
  WAVEGLOW vocoder</th></tr>
 
  <tr>
  <td>
  <audio controls="" preload="none" style="height:30px">
 <source src="https://sachp1.github.io/speaker1/steve_jobs.mp3" type="audio/mpeg">audio not supported</audio>
</td></tr>
 </tbody>
 </table>

<form id="fs-frm" name="survey-form-test" accept-charset="utf-8" action="https://formspree.io/sachinprakash.itis@gmail.com" method="post">
  <fieldset id="fs-frm-inputs">
    <label for="email-address">Email Address</label>
    <input type="email" name="_replyto" id="email-address" placeholder="email@domain.tld" required="">
      
    <fieldset id="fs-frm-selects">
      <label for="timely">1. How well does Wavenet resemble Ground truth.</label>
      <select name="timely" id="timely" required="">
        <option value="Choose" selected="" disabled="">Choose</option>
        <option value="1">Excellent</option>
        <option value="3">Good</option>
        <option value="5">Fair</option>
        <option value="7">Poor</option>
        <option value="9">Bad</option>
      </select>
      <label for="timely">2. How would you rate the speech synthesized using Wavenet (Clarity).</label>
      <select name="quality" id="quality" required="">
        <option value="Choose" selected="" disabled="">Choose</option>
        <option value="1">Excellent</option>
        <option value="3">Good</option>
        <option value="5">Fair</option>
        <option value="7">Poor</option>
        <option value="9">Bad</option>
      </select>
    </fieldset>
    
    <input type="hidden" name="_subject" id="email-subject" value="Survey Responses">
  </fieldset>
  <input type="submit" value="Send Responses">
</form>

### Support or Contact
Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
  
