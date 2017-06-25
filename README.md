# CryptoTest
Selenium test for verifying https://www.cryptocompare.com/mining/calculator/btc to correct Bitcoin profit per month calculation.
Generates random unit, hashing power, power consumption and cost per KW/h. Gets current bitcoin calculation rate from web form.

# Requirements
 - Java 1.8
 - Mozilla Firefox version up to 54.0
 - Maven (https://maven.apache.org/guides/getting-started/windows-prerequisites.html)
 - Add maven home path to environment variable M3_HOME
 
# Quick start
 - Download repo to any folder
 - Switch to it from command line
 - Execute command "mvn clean test" (without quotes)
