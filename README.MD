## How to use the Amazon AWS SDK for Textract with PHP 8.1 ##

First, review my [notes for using Textract with PHP 7.2](https://github.com/fullStackOasis/php-aws-textract-pdf/). Everything is pretty much the same when you use 8.1. The exception is that your PHP libraries will be for AWS SDK PHP 8.1. The code sample looks different too. You can find it in this demo - textract_demo_async.php.

When you run the code from the command line, this is what you should see:

```
php textract_demo_async.php
The promise was fulfilled.Line: The AWS CLI is updated frequently with support for new services and commands.
Word: The
Word: AWS
Word: CLI
Word: is
Word: updated
Word: frequently
Word: with
Word: support
Word: for
Word: new
Word: services
Word: and
Word: commands.
```

The code above extracts text from a local jpg file. That file has been committed into this repo. It's named aws_cli_text_document.jpg.

That's it! Feel free to email me with any questions at fullstackdev@fullstackoasis.com.

References:

[1] <a href="https://stackoverflow.com/questions/49806405/cannot-read-credentials-from-aws-credentials-php-script-call-aws-sdk">Stackoverflow question about AWS Credentials</a>