# tobiasvandyk.github.io

The VLSI VS1053 DSP is connected to a Raspberry Pi Pico (RP2040), a Teensy3.x and 4.x, and an ATmega328 (Arduino Uno), as a Music Effects Box, SDCard Music Player and a Midi Synth.

<p class="header">
  <a href="https://github.com/TobiasVanDyk/Pico-MCU-from-Raspberry-Pi/tree/main/Vs1053Pico">1. VS1053 SDCard Music Player using a Raspberry Pi Pico</a> <br /> 
  <a href="https://github.com/TobiasVanDyk/Audio-Effects-Preamp-VS1053b">2. VS1053 Audio Effects Preamp using an ATMega328</a> <br /> 
  <a href="https://github.com/TobiasVanDyk/VS1053-Micro-Midi-Synthesizer">3. VS1053 Midi Synth using an ATMega328</a> <br /> 
  <a href="https://github.com/TobiasVanDyk/VS1053B-Teensy-36-and-41-Music-Effects">4. VS1053 Audio Effects Preamp using a Teensy 3.x and 4.x</a> <br /> 
  <a href="https://github.com/TobiasVanDyk/VS1053B-Teensy36-Teensy41-SDCard-Music-Player">5. VS1053 SDCard Music Player using a Teensy 3.x and 4.x</a> <br /> 
</p>

Search my GitHub:
  <input type="text" id="searchbox" onchange="search();">
  <a href="https://google.com"  id="searcher" class="button">search</a>
  <script>
    function search() {
      let url = 'https://github.com/search?q=user%3ATobiasVanDyk+';
      let term = document.getElementById('searchbox').value;
      url += term;
      url += "&type=code";
      let mySearchLink = document.getElementById("searcher");
      mySearchLink.href = url;
      mySearchLink.target = "_blank";
      mySearchLink.click();
     
    }
  </script>
