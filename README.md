# SYNOPSIS

    enable 'RequestHeaders',
        set => ['Accept-Encoding' => 'identity'],
        unset => ['Authorization'];

# DESCRIPTION

This middleware allows the modification of HTTP request headers. For instance,
util for use with [Plack::App::Proxy](https://metacpan.org/pod/Plack::App::Proxy).

# SEE ALSO

[Plack::Middleware::Headers](https://metacpan.org/pod/Plack::Middleware::Headers), [Plack::Middleware](https://metacpan.org/pod/Plack::Middleware),  [Plack::Builder](https://metacpan.org/pod/Plack::Builder)

[![Build Status](https://travis-ci.org/wreis/Plack-Middleware-RequestHeaders.svg?branch=master)](https://travis-ci.org/wreis/Plack-Middleware-RequestHeaders)

[![Coverage Status](https://coveralls.io/repos/github/wreis/Plack-Middleware-RequestHeaders/badge.svg?branch=master)](https://coveralls.io/github/wreis/Plack-Middleware-RequestHeaders?branch=master)
