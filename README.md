﻿# XmlRPC

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/72ed394545f947dca0620204fd223627)](https://app.codacy.com/app/LordVeovis/xmlrpc?utm_source=github.com&utm_medium=referral&utm_content=LordVeovis/xmlrpc&utm_campaign=badger)
[![Build Status](https://gitlab.kveer.fr/veovis/xmlrpc/badges/master/build.svg)](https://github.com/LordVeovis/xmlrpc)
[![Nuget Downloads](https://img.shields.io/nuget/dt/XmlRPC.svg)](https://www.nuget.org/packages/XmlRPC/)

This repository contains a .net library for consuming XML-RPC web services. It is a port of the Charles Cook's library mainly for .NET Core 2.x but target the netstandard 2.0, so it can also be used on the full .NET Framework 4.6.1+.

## How to use

As a port, very few changes have been done but the API is still the same. The documentation on the orignal projet remains valid: http://xml-rpc.net/

## Improvements

* Can/Should we use Roslyn to generate the proxy implementation of the IXmlRpcProxy interface instead of using System.Reflection?

## Legal and Licensing

This library is licensed under the [MIT license][].

[MIT license]: https://github.com/PowerShell/PowerShell/tree/master/LICENSE.txt
