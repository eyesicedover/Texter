# Texter

.Net MVC app for sending and checking sent Twilio API messages.

## Getting Started

Clone this [repository](https://github.com/eyesicedover/Texter). Create a file in the Models folder called EnvironmentVariables.cs. Put in the following code:

```
using System;
using System.Collections.Generic;
using System.Linq;
using System.Threading.Tasks;

namespace Texter.Models
{
    public class EnvironmentVariables
    {
        public static string AccountSID = "xxxxxxxxxxxxxxxxx";
        public static string AuthToken = "xxxxxxxxxxxxxxxxx";
    }
}
```

Replace the xxx strings with the information from your Twilio Account SID and AuthToken data.

### Prerequisites

* Visual Studio Community 2017, or another IDE
* Twilio Account. Sign up [here](https://www.twilio.com/console).

## Specs

1. User can check the texts sent with their Twilio API account.
a. User clicks on "Check messages sent"
b. A page appears showing all the messages they have sent with some relevant data.

2a. User can send a text using their Twilio API account.
a. User clicks on "Send Message".
b. A page appears showing a form to take in the phone number it will be sent to, the number it will be sent from, and the message to be sent.

2b. User fills in form and submits it.
a. User enters a phone number for sender and receiver, as well as a message. They submit the form.
b. The page redirects to the Index and the message is sent.

## Built With

* Visual Studio Community 2017
* Twilio API

## Authors

**Stephanie Faber** - [eyesicedover](https://github.com/eyesicedover)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
