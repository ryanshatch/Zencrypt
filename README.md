<!--
****************************************************************************************
Title: Zencrypt CLI Readme.md    *******************************************************
Developed by: Ryan Hatch         *******************************************************
Dev Date: Aug 10th 2022          *******************************************************
Last Updated: July 1 2024        *******************************************************
Version: 2.2.6                   *******************************************************
****************************************************************************************
-->

<!DOCTYPE html>
<html>
  <body>
    <hr>
    <h1 align="center">Zencrypt</h1>
    <br>
    <p align="center">
      <strong>Hash and Cipher Command Line Interface:</strong>
<!--       <br>
      <strong>By: Ryan Hatch</strong> -->
      <br>
    </p>
    <p align="center">
      <a href="#introduction">Introduction</a> • <a href="#features">Features</a> • <a href="#installation">Installation</a> • <a href="#usage">Usage</a> • <a href="#examples">Examples</a> • <a href="#contributing">Contributing</a> • <a href="#disclaimer">Disclaimer</a> • <a href="#license">License</a> • <a href="#contact">Contact</a>
    </p>
    <hr>
    <p align="center">
      <strong>How to Use PGP Encryption:</strong>
<!--       <br>
      <strong>By: Ryan Hatch</strong> -->
      <br>
    </p>
    <p align="center">
      <a href="#intro">Intro</a> • <a href="#key-concepts">Key Concepts</a> • <a href="#setting-up">Setting Up</a> • <a href="#encrypting-messages">Encrypting Messages</a> • <a href="#decrypting-messages">Decrypting Messages</a> • <a href="#key-management">Key Management</a>
    <hr>
    <p align="center">
<!--       <br> -->
      <strong>By: Ryan Hatch</strong>
    <p align="center"> &copy; 2023 Ryan Hatch <br> All Rights Reserved. </p>
    <h2 id="introduction">Introduction</h2>
    <p> This project provides a command-line interface for managing hashes and encryption for input text. It includes both a Python and a Java implementation along with a lite version in C++.</p>
    <ul>
    <li><h4>The <code>Zencrypt CLI</code> contains the full Zencrypt program that can provide functionality for hashing, encrypting text, encrypting files, along with full handling of PGP encryption.</h4></li>
    <li><h4>The <code>Zencrypt GUI</code> is a basic form of Zencrypt V2 with the same functionalities and shortcut commands, but with a GUI.</h4></li>
    <li><h4>The <code>Java version</code> is a clone copy of Zencrypt v3 with the inability to handle PGP encryption. All other functions remain the same.</h4></li>
    <li><h4>The <code>C++ version</code> only allows basic hashing and encryption functions.</h4>
    </ul></li>
    <h2 id="features">Features</h2>
    <ul>
      <li>
        <strong>Generate and verify hashes</strong> with optional salt.
      </li>
      <li>
        <strong>Encrypt and decrypt text.</strong>
<!--       </li> -->
      <!-- <li><strong>Verify hashes.</strong></li> -->
      <li>
        <strong>Encrypt and decrypt files.</strong>
      </li>
      <li>
        <strong>PGP Encryption</strong>
      </li>
    </ul>
    <h2 id="installation">Installation</h2>
    <p> To install Zencrypt, you will need to follow these steps: </p>
    <ol>
      <li>Clone the repository or download the source code with the command:<br><code>git clone https://github.com/ryanshatch/Zencrypt.git</code>. </li>
      <li>Navigate to the <code>Python CLI</code> or to the <code>Java CLI</code> directory. </li>
      <li>Install the required dependencies with the command: <code>pip install -r requirements.txt</code>. </li>
    </ol>
    <h2 id="usage">Usage</h2>
    <h3>Binary v3.0</h3>
    <p> 1. After installing the required dependencies, you can run the binary executable: <code>zencrypt.exe</code>
      <br> 2. Select whether you want to <code>hash, encrypt text, or parse files</code> and then follow the on screen instructions. <br>
      <br>To exit the program, simply enter <code>exit</code>.
    </p>
    <h2></h2>
    <h3>Java Version</h3>
    <p> 1. After installing the required dependencies, you can now compile and run the Java program with the commands: <code>javac Zencrypt.java</code> and <code>java Zencrypt</code>
      <br /> 2. Select whether you want to <code>hash, encrypt text, or parse files</code> and then simply just follow the on screen instructions. <br>
      <br>To exit the program, simply enter <code>exit</code>
    </p>
    <p align="center">
      <br>
      <br>
      <strong> Alternatively, you can avoid installing the dependancies by using the provided executable to run the binaries: <code>zencryptCLI.exe</code>
      </strong>
      <br />
      </strong>
      </br>
    </p>
    <h2 id="examples">Examples</h2><br><hr>
    <h3 align="center">Hashing:</h3><h2></h2>
    <center>
      <img alt="Hashing Example" src="https://github.com/ryanshatch/Zencrypt/blob/main/Images/zencrypthash.png" style="width: 100%; height: 100%;" />
    </center><br><hr>
    <h3 align="center">Cipher:</h3><h2></h2>
    <center>
      <img alt="Cipher Example" src="https://github.com/ryanshatch/Zencrypt/blob/main/Images/zencrypt.PNG" style="width: 100%; height: 100%;" />
    </center><br><hr>
    <h3 align="center">Encrypting Parsed Files:</h3><h2></h2>
    <center>
      <img alt="Cipher Example" src="https://github.com/ryanshatch/Zencrypt/blob/main/Images/encrypt.PNG" style="width: 100%; height: 50%;" />
    </center><br><hr>
        <h3 align="center">PGP Encryption:</h3><h2></h2>
    <center>
      <img alt="Cipher Example" src="https://github.com/ryanshatch/Zencrypt/blob/main/Images/pgpencryption.PNG" style="width: 100%; height: 50%;" />
    </center><br><hr>
    </p>
<!--     <hr><br> -->
    <h1 align="center" id="How To Use PGP Encryption">How To Use PGP Encryption:</h1><hr>
    </p>
    <p align="center">
    <h2 id="intro"><strong>Intro</strong></h2>
    <p> This guide provides an overview of how to use PGP (Pretty Good Privacy) encryption for securing digital communications. It covers the basics of PGP, including key concepts, setting up, encrypting and decrypting messages, and best practices for key management.
    <br>
    PGP encryption is a powerful tool for securing your digital communications. It's important to understand the basics of public and private keys and to follow best practices for key management and message encryption/decryption. </p>
    <p> Remember, the strength of PGP encryption lies in the proper handling of your keys. Keep your private key secure and only share your public key with trusted contacts.
    </p>
    </p>
        <h3 id="key-concepts">Key Concepts</h3>
    <ul>
      <li>
        <strong>Understanding Public and Private Keys.</strong>
      </li>
      <li>
        <strong>How PGP encryption works.</strong>
      </li>
      <li>
        <strong>Importance of key management.</strong>
      </li>
    </ul>
    <h3 id="setting-up">Setting Up</h3>
    <p> To get started with PGP encryption, follow these steps: </p>
    <ol>
      <li>Select a PGP software.</li>
      <li>Generate your key pair.</li>
      <li>Share your public key.</li>
      <li>Secure your private key.</li>
    </ol>
    <h3 id="encrypting-messages">Encrypting Messages</h3>
    <p> To encrypt a message using PGP, follow these steps: </p>
    <ol>
      <li>Write your message.</li>
      <li>Encrypt the message using the recipient's public key.</li>
      <li>Send the encrypted message.</li>
    </ol>
    <h3 id="decrypting-messages">Decrypting Messages</h3>
    <p> To decrypt a received PGP message, follow these steps: </p>
    <ol>
      <li>Receive the encrypted message.</li>
      <li>Decrypt the message using your private key.</li>
      <li>Read the decrypted message.</li>
    </ol>
    <h3 id="key-management">Key Management</h3>
    <p> Key management is crucial for maintaining the security of your PGP encryption. Follow these best practices: </p>
    <ol>
      <li>Keep your private key secure.</li>
      <li>Regularly update and manage your key pair.</li>
      <li>Use strong passwords for your private key.</li>
    </ol>
    <hr>
<!--     <br> -->
    <h2 align="center" id="contributing">Contributing</h2>
    <ol>
      <p align="center">
        <strong>Please reach out to me to verify and validate your ideas and contributions before continuing any further. Although contributions may be welcome, it will be discussed first. <br>
          <br> After reaching out to me, please follow these steps: </strong>
        <br>
        <li>Fork the repository.</li>
        <li>Create a new branch with the command: <code>git checkout -b feature-branch</code>.
        <li>Make your changes.</li>
        <li>Commit your changes with the command: <code>git commit -am 'Add new feature'</code>.
        <li>Push to the branch with the command: <code>git push origin feature-branch</code>.
        <li>Create a new Pull Request.</li>
    </ol>
<!--     <h1></h1> -->
    <hr>
    <h1 align="center" id="disclaimer">DISCLAIMER!</h1>
    <p align="center">
      <strong>
        <=>
          <=>
            <=>
              <=>
                <=>
                  <=>
                    <=>
                      <=>
                        <=>
                          <=>
                            <=>
                              <=>
                                <=>
                                  <=>
                                    <=>
                                      <=>
                                        <=>
                                          <=>
                                            <=>
                                              <=>
                                                <=>
                                                  <=>
                                                    <=>
                                                      <=>
                                                        <=>
                                                          <=>
                                                            <!-- <=><=><=><=> -->
      </strong>
      </br>
      <!-- <p align="center"><strong><=><=><=></strong></br></p> -->
    <p align="center">
      <strong>
        <strong><b><i>This script is provided for educational and demonstration purposes only. <br>Use it responsibly and please adhere to all applicable laws and regulations. </strong></i></b>
      </strong>
      </br>
    </p>
    <strong>This script is provided for educational and demonstration purposes only. Use it responsibly and adhere to all applicable laws and regulations.</strong></br></p>
    <p align="center">
      <strong>
        <strong><b><i>I am absolutely immune from any responsibility in regaurds to any damages or loss of data caused by the <br>use, abuse, or misuse of this software. </strong></i></b>
      </strong>
      </br>
      <!-- <p align="center"><strong><=><=><=></strong></br></p> -->
    <p align="center">
      <strong>
        <=>
          <=>
            <=>
              <=>
                <=>
                  <=>
                    <=>
                      <=>
                        <=>
                          <=>
                            <=>
                              <=>
                                <=>
                                  <=>
                                    <=>
                                      <=>
                                        <=>
                                          <=>
                                            <=>
                                              <=>
                                                <=>
                                                  <=>
                                                    <=>
                                                      <=>
                                                        <=>
                                                          <=>
                                                            <!-- <=><=><=><=> -->
      </strong>
      </br>
    </p><hr>
    <h2 align="center" id="liscense">Liscense</h2>
    <p> This software is the property of the copyright holder and is protected by copyright laws. All rights are reserved. The copyright holder grants no implied or express license for the use, copying, modification, distribution, or reproduction of this software, in whole or in part, without the prior written permission of the copyright holder. </p>
    <p> Any unauthorized use, copying, modification, distribution, or reproduction of this software, in whole or in part, is strictly prohibited and constitutes a violation of copyright law. Such unauthorized use may result in civil and/or criminal penalties, including but not limited to legal action and monetary damages. </p>
    <p> To obtain permission for any use, copying, modification, distribution, or reproduction of this software, please contact the copyright holder at the following address: <code>ryan@rshatch.com</code>
    </p>
    </p>
    <br>
    <p align="center">
      <strong>
        <code>By using this software, you acknowledge that you have read and understood the terms of this license and agree to comply with all applicable copyright laws. <br>Failure to abide by the terms of this license may subject you to legal consequences. </code>
      </strong>
    </p>
  </body>
</html><hr>
<h2 align="center" id="contact">Contact</h2>
<p align="center">For any inquiries or suggestions, please contact me at <a href="mailto:ryan@rshatch.com">ryan@rshatch.com</a>.
</body>
</html>
