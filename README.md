<div align="center">
  <img src="./assets/logo.png" width="55%"/>
  <hr>
  <p>CmCode2Img is a text to image conversion tool.</p>
</div>
<div>
  <h2>Installation and Startup</h2>
  <h3>Dependencies</h3>
  <p>
    Some dependencies will be needed before starting the script. Check that the <code>AWK</code> command and the <code>SED</code> command are on your machine.
  </p>

  ```bash
  # Install on Linux Users
  sudo apt-get install libncurses5-dev libncursesw5-dev bc
  # Instal on Termux Users
  apt-get install ncurses-utils bc
  ```

  <h3>Installation</h3>
  <p>
    After installing the dependencies, clone the repository, go to the repository folder and give the necessary permissions for it to run successfully.
  </p>

  ```bash
  $ chmod +x CmCode2Img
  # To run
  $ ./CmCode2Img
  ```
  
  <h4>
    Command parameters
  </h4>
  
  - <b>-f</b>:
    - Sets a new font.
    ```bash
    $ CmCode2Img -f SansSerif.ttf
    ```
    > **Attention**
    > 
    > The font will need to be inside the `.fonts` folder.
  - <b>-o</b> 
    - Starts converting code to image.
    ```bash
    $ CmCode2Img file.ext -o imageName
    ```
  - <b>--help</b>
    - Displays script help.
</div>
<hr>
<div align="center">  
  <p>
    This project is licensed under the <a href="LICENSE">MIT</a> license.
  </p>
  <p>
    Coded by <a href="https://github.com/Ahosall">AthenaD3V</a>
  </p>
  <p>
    Readme by <a href="https://github.com/Ahosall">Ahosall</a> 🤍
  </p>
</div>
