# zend-mail

[![Build Status](https://secure.travis-ci.org/zendframework/zend-mail.svg?branch=master)](https://secure.travis-ci.org/zendframework/zend-mail)
[![Coverage Status](https://coveralls.io/repos/zendframework/zend-mail/badge.svg?branch=master)](https://coveralls.io/r/zendframework/zend-mail?branch=master)

`Zend\Mail` provides generalized functionality to compose and send both text and
MIME-compliant multipart email messages. Mail can be sent with `Zend\Mail` via
the `Mail\Transport\Sendmail`, `Mail\Transport\Smtp` or the `Mail\Transport\File`
transport. Of course, you can also implement your own transport by implementing
the `Mail\Transport\TransportInterface`.

- File issues at https://github.com/zendframework/zend-mail/issues
- Documentation is at https://zendframework.github.io/zend-mail/

Fork that includes verify_peer, verify_peer_name and allow_self_signed for Zend Mail to use self signed certificates with PHP 5.6 onwards.
