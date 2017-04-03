# api documentation for  [stripe (v4.17.0)](https://github.com/stripe/stripe-node)  [![npm package](https://img.shields.io/npm/v/npmdoc-stripe.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-stripe) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-stripe.svg)](https://travis-ci.org/npmdoc/node-npmdoc-stripe)
#### Stripe API wrapper

[![NPM](https://nodei.co/npm/stripe.png?downloads=true)](https://www.npmjs.com/package/stripe)

[![apidoc](https://npmdoc.github.io/node-npmdoc-stripe/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-stripe_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-stripe/build..beta..travis-ci.org/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-stripe/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-stripe/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Stripe",
        "email": "support@stripe.com",
        "url": "https://stripe.com/"
    },
    "bugs": {
        "url": "https://github.com/stripe/stripe-node/issues"
    },
    "bugs:": "https://github.com/stripe/stripe-node/issues",
    "contributors": [
        {
            "name": "Ask Bjørn Hansen",
            "email": "ask@develooper.com",
            "url": "http://www.askask.com/"
        },
        {
            "name": "Michelle Bu",
            "email": "michelle@stripe.com"
        },
        {
            "name": "Alex Sexton",
            "email": "alex@stripe.com"
        },
        {
            "name": "James Padolsey"
        }
    ],
    "dependencies": {
        "bluebird": "^2.10.2",
        "lodash.isplainobject": "^4.0.6",
        "object-assign": "^4.1.0",
        "qs": "~6.0.4"
    },
    "description": "Stripe API wrapper",
    "devDependencies": {
        "chai": "~1.10.0",
        "chai-as-promised": "~4.1.1",
        "jscs": "^2.3.5",
        "mocha": "~2.1.0",
        "stripe-javascript-style": "^1.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "b9a909f481a44a197e6a61427f33d7bcfc4802da",
        "tarball": "https://registry.npmjs.org/stripe/-/stripe-4.17.0.tgz"
    },
    "engines": {
        "node": ">= v0.10.0"
    },
    "gitHead": "56945e423b8b9c85740f4af8946e81a39b28d775",
    "homepage": "https://github.com/stripe/stripe-node",
    "keywords": [
        "stripe",
        "payment processing",
        "credit cards",
        "api"
    ],
    "license": "MIT",
    "main": "lib/stripe.js",
    "maintainers": [
        {
            "name": "bkrausz",
            "email": "briankrausz@gmail.com"
        },
        {
            "name": "brandur",
            "email": "brandur@mutelight.org"
        },
        {
            "name": "cupcait",
            "email": "caitlin@stripe.com"
        },
        {
            "name": "kjc",
            "email": "kjc@stripe.com"
        },
        {
            "name": "michelle",
            "email": "michelle@michellebu.com"
        },
        {
            "name": "slexaxton",
            "email": "alexsexton@gmail.com"
        },
        {
            "name": "stripe",
            "email": "frontend-contact+npm@stripe.com"
        }
    ],
    "name": "stripe",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/stripe/stripe-node.git"
    },
    "scripts": {
        "lint": "jscs .",
        "mocha": "mocha",
        "test": "npm run lint && mocha"
    },
    "version": "4.17.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module stripe](#apidoc.module.stripe)
1.  [function <span class="apidocSignatureSpan">stripe.</span>Error (raw)](#apidoc.element.stripe.Error)
1.  [function <span class="apidocSignatureSpan">stripe.</span>Stripe (key, version)](#apidoc.element.stripe.Stripe)
1.  [function <span class="apidocSignatureSpan">stripe.</span>StripeResource (stripe, urlData)](#apidoc.element.stripe.StripeResource)
1.  [function <span class="apidocSignatureSpan">stripe.</span>resources.Account ()](#apidoc.element.stripe.resources.Account)
1.  [function <span class="apidocSignatureSpan">stripe.</span>resources.ApplePayDomains ()](#apidoc.element.stripe.resources.ApplePayDomains)
1.  [function <span class="apidocSignatureSpan">stripe.</span>resources.ApplicationFeeRefunds ()](#apidoc.element.stripe.resources.ApplicationFeeRefunds)
1.  [function <span class="apidocSignatureSpan">stripe.</span>resources.ApplicationFees ()](#apidoc.element.stripe.resources.ApplicationFees)
1.  [function <span class="apidocSignatureSpan">stripe.</span>resources.Balance ()](#apidoc.element.stripe.resources.Balance)
1.  [function <span class="apidocSignatureSpan">stripe.</span>resources.BitcoinReceivers ()](#apidoc.element.stripe.resources.BitcoinReceivers)
1.  [function <span class="apidocSignatureSpan">stripe.</span>resources.ChargeRefunds ()](#apidoc.element.stripe.resources.ChargeRefunds)
1.  [function <span class="apidocSignatureSpan">stripe.</span>resources.Charges ()](#apidoc.element.stripe.resources.Charges)
1.  [function <span class="apidocSignatureSpan">stripe.</span>resources.CountrySpecs ()](#apidoc.element.stripe.resources.CountrySpecs)
1.  [function <span class="apidocSignatureSpan">stripe.</span>resources.Coupons ()](#apidoc.element.stripe.resources.Coupons)
1.  [function <span class="apidocSignatureSpan">stripe.</span>resources.CustomerCards ()](#apidoc.element.stripe.resources.CustomerCards)
1.  [function <span class="apidocSignatureSpan">stripe.</span>resources.CustomerSubscriptions ()](#apidoc.element.stripe.resources.CustomerSubscriptions)
1.  [function <span class="apidocSignatureSpan">stripe.</span>resources.Customers ()](#apidoc.element.stripe.resources.Customers)
1.  [function <span class="apidocSignatureSpan">stripe.</span>resources.Disputes ()](#apidoc.element.stripe.resources.Disputes)
1.  [function <span class="apidocSignatureSpan">stripe.</span>resources.Events ()](#apidoc.element.stripe.resources.Events)
1.  [function <span class="apidocSignatureSpan">stripe.</span>resources.FileUploads ()](#apidoc.element.stripe.resources.FileUploads)
1.  [function <span class="apidocSignatureSpan">stripe.</span>resources.InvoiceItems ()](#apidoc.element.stripe.resources.InvoiceItems)
1.  [function <span class="apidocSignatureSpan">stripe.</span>resources.Invoices ()](#apidoc.element.stripe.resources.Invoices)
1.  [function <span class="apidocSignatureSpan">stripe.</span>resources.OrderReturns ()](#apidoc.element.stripe.resources.OrderReturns)
1.  [function <span class="apidocSignatureSpan">stripe.</span>resources.Orders ()](#apidoc.element.stripe.resources.Orders)
1.  [function <span class="apidocSignatureSpan">stripe.</span>resources.Payouts ()](#apidoc.element.stripe.resources.Payouts)
1.  [function <span class="apidocSignatureSpan">stripe.</span>resources.Plans ()](#apidoc.element.stripe.resources.Plans)
1.  [function <span class="apidocSignatureSpan">stripe.</span>resources.Products ()](#apidoc.element.stripe.resources.Products)
1.  [function <span class="apidocSignatureSpan">stripe.</span>resources.RecipientCards ()](#apidoc.element.stripe.resources.RecipientCards)
1.  [function <span class="apidocSignatureSpan">stripe.</span>resources.Recipients ()](#apidoc.element.stripe.resources.Recipients)
1.  [function <span class="apidocSignatureSpan">stripe.</span>resources.Refunds ()](#apidoc.element.stripe.resources.Refunds)
1.  [function <span class="apidocSignatureSpan">stripe.</span>resources.Skus ()](#apidoc.element.stripe.resources.Skus)
1.  [function <span class="apidocSignatureSpan">stripe.</span>resources.Sources ()](#apidoc.element.stripe.resources.Sources)
1.  [function <span class="apidocSignatureSpan">stripe.</span>resources.SubscriptionItems ()](#apidoc.element.stripe.resources.SubscriptionItems)
1.  [function <span class="apidocSignatureSpan">stripe.</span>resources.Subscriptions ()](#apidoc.element.stripe.resources.Subscriptions)
1.  [function <span class="apidocSignatureSpan">stripe.</span>resources.ThreeDSecure ()](#apidoc.element.stripe.resources.ThreeDSecure)
1.  [function <span class="apidocSignatureSpan">stripe.</span>resources.Tokens ()](#apidoc.element.stripe.resources.Tokens)
1.  [function <span class="apidocSignatureSpan">stripe.</span>resources.TransferReversals ()](#apidoc.element.stripe.resources.TransferReversals)
1.  [function <span class="apidocSignatureSpan">stripe.</span>resources.Transfers ()](#apidoc.element.stripe.resources.Transfers)
1.  number <span class="apidocSignatureSpan">stripe.</span>DEFAULT_TIMEOUT
1.  object <span class="apidocSignatureSpan">stripe.</span>DEFAULT_API_VERSION
1.  object <span class="apidocSignatureSpan">stripe.</span>Error.prototype
1.  object <span class="apidocSignatureSpan">stripe.</span>StripeResource.BASIC_METHODS
1.  object <span class="apidocSignatureSpan">stripe.</span>StripeResource.prototype
1.  object <span class="apidocSignatureSpan">stripe.</span>USER_AGENT
1.  object <span class="apidocSignatureSpan">stripe.</span>USER_AGENT_SERIALIZED
1.  object <span class="apidocSignatureSpan">stripe.</span>resources
1.  object <span class="apidocSignatureSpan">stripe.</span>resources.Account.prototype
1.  object <span class="apidocSignatureSpan">stripe.</span>resources.ApplicationFees.prototype
1.  object <span class="apidocSignatureSpan">stripe.</span>resources.Balance.prototype
1.  object <span class="apidocSignatureSpan">stripe.</span>resources.BitcoinReceivers.prototype
1.  object <span class="apidocSignatureSpan">stripe.</span>resources.Charges.prototype
1.  object <span class="apidocSignatureSpan">stripe.</span>resources.CustomerSubscriptions.prototype
1.  object <span class="apidocSignatureSpan">stripe.</span>resources.Customers.prototype
1.  object <span class="apidocSignatureSpan">stripe.</span>resources.Disputes.prototype
1.  object <span class="apidocSignatureSpan">stripe.</span>resources.FileUploads.prototype
1.  object <span class="apidocSignatureSpan">stripe.</span>resources.Invoices.prototype
1.  object <span class="apidocSignatureSpan">stripe.</span>resources.Orders.prototype
1.  object <span class="apidocSignatureSpan">stripe.</span>resources.Payouts.prototype
1.  object <span class="apidocSignatureSpan">stripe.</span>resources.Products.prototype
1.  object <span class="apidocSignatureSpan">stripe.</span>resources.Recipients.prototype
1.  object <span class="apidocSignatureSpan">stripe.</span>resources.Skus.prototype
1.  object <span class="apidocSignatureSpan">stripe.</span>resources.Sources.prototype
1.  object <span class="apidocSignatureSpan">stripe.</span>resources.Subscriptions.prototype
1.  object <span class="apidocSignatureSpan">stripe.</span>resources.Transfers.prototype
1.  object <span class="apidocSignatureSpan">stripe.</span>utils
1.  string <span class="apidocSignatureSpan">stripe.</span>DEFAULT_BASE_PATH
1.  string <span class="apidocSignatureSpan">stripe.</span>DEFAULT_HOST
1.  string <span class="apidocSignatureSpan">stripe.</span>DEFAULT_PORT
1.  string <span class="apidocSignatureSpan">stripe.</span>PACKAGE_VERSION

#### [module stripe.Error](#apidoc.module.stripe.Error)
1.  [function <span class="apidocSignatureSpan">stripe.</span>Error (raw)](#apidoc.element.stripe.Error.Error)
1.  [function <span class="apidocSignatureSpan">stripe.Error.</span>StripeAPIError ()](#apidoc.element.stripe.Error.StripeAPIError)
1.  [function <span class="apidocSignatureSpan">stripe.Error.</span>StripeAuthenticationError ()](#apidoc.element.stripe.Error.StripeAuthenticationError)
1.  [function <span class="apidocSignatureSpan">stripe.Error.</span>StripeCardError ()](#apidoc.element.stripe.Error.StripeCardError)
1.  [function <span class="apidocSignatureSpan">stripe.Error.</span>StripeConnectionError ()](#apidoc.element.stripe.Error.StripeConnectionError)
1.  [function <span class="apidocSignatureSpan">stripe.Error.</span>StripeError ()](#apidoc.element.stripe.Error.StripeError)
1.  [function <span class="apidocSignatureSpan">stripe.Error.</span>StripeInvalidRequestError ()](#apidoc.element.stripe.Error.StripeInvalidRequestError)
1.  [function <span class="apidocSignatureSpan">stripe.Error.</span>StripePermissionError ()](#apidoc.element.stripe.Error.StripePermissionError)
1.  [function <span class="apidocSignatureSpan">stripe.Error.</span>StripeRateLimitError ()](#apidoc.element.stripe.Error.StripeRateLimitError)
1.  [function <span class="apidocSignatureSpan">stripe.Error.</span>extend (sub)](#apidoc.element.stripe.Error.extend)

#### [module stripe.Error.prototype](#apidoc.module.stripe.Error.prototype)
1.  [function <span class="apidocSignatureSpan">stripe.Error.prototype.</span>populate (type, message)](#apidoc.element.stripe.Error.prototype.populate)
1.  string <span class="apidocSignatureSpan">stripe.Error.prototype.</span>type

#### [module stripe.StripeResource](#apidoc.module.stripe.StripeResource)
1.  [function <span class="apidocSignatureSpan">stripe.</span>StripeResource (stripe, urlData)](#apidoc.element.stripe.StripeResource.StripeResource)
1.  [function <span class="apidocSignatureSpan">stripe.StripeResource.</span>extend (sub)](#apidoc.element.stripe.StripeResource.extend)
1.  [function <span class="apidocSignatureSpan">stripe.StripeResource.</span>method (spec)](#apidoc.element.stripe.StripeResource.method)
1.  object <span class="apidocSignatureSpan">stripe.StripeResource.</span>BASIC_METHODS

#### [module stripe.StripeResource.BASIC_METHODS](#apidoc.module.stripe.StripeResource.BASIC_METHODS)
1.  [function <span class="apidocSignatureSpan">stripe.StripeResource.BASIC_METHODS.</span>create ()](#apidoc.element.stripe.StripeResource.BASIC_METHODS.create)
1.  [function <span class="apidocSignatureSpan">stripe.StripeResource.BASIC_METHODS.</span>del ()](#apidoc.element.stripe.StripeResource.BASIC_METHODS.del)
1.  [function <span class="apidocSignatureSpan">stripe.StripeResource.BASIC_METHODS.</span>getMetadata (id, auth, cb)](#apidoc.element.stripe.StripeResource.BASIC_METHODS.getMetadata)
1.  [function <span class="apidocSignatureSpan">stripe.StripeResource.BASIC_METHODS.</span>list ()](#apidoc.element.stripe.StripeResource.BASIC_METHODS.list)
1.  [function <span class="apidocSignatureSpan">stripe.StripeResource.BASIC_METHODS.</span>retrieve ()](#apidoc.element.stripe.StripeResource.BASIC_METHODS.retrieve)
1.  [function <span class="apidocSignatureSpan">stripe.StripeResource.BASIC_METHODS.</span>setMetadata (id, key, value, auth, cb)](#apidoc.element.stripe.StripeResource.BASIC_METHODS.setMetadata)
1.  [function <span class="apidocSignatureSpan">stripe.StripeResource.BASIC_METHODS.</span>update ()](#apidoc.element.stripe.StripeResource.BASIC_METHODS.update)

#### [module stripe.StripeResource.prototype](#apidoc.module.stripe.StripeResource.prototype)
1.  [function <span class="apidocSignatureSpan">stripe.StripeResource.prototype.</span>_errorHandler (req, callback)](#apidoc.element.stripe.StripeResource.prototype._errorHandler)
1.  [function <span class="apidocSignatureSpan">stripe.StripeResource.prototype.</span>_request (method, path, data, auth, options, callback)](#apidoc.element.stripe.StripeResource.prototype._request)
1.  [function <span class="apidocSignatureSpan">stripe.StripeResource.prototype.</span>_responseHandler (req, callback)](#apidoc.element.stripe.StripeResource.prototype._responseHandler)
1.  [function <span class="apidocSignatureSpan">stripe.StripeResource.prototype.</span>_timeoutHandler (timeout, req, callback)](#apidoc.element.stripe.StripeResource.prototype._timeoutHandler)
1.  [function <span class="apidocSignatureSpan">stripe.StripeResource.prototype.</span>createFullPath (commandPath, urlData)](#apidoc.element.stripe.StripeResource.prototype.createFullPath)
1.  [function <span class="apidocSignatureSpan">stripe.StripeResource.prototype.</span>createUrlData ()](#apidoc.element.stripe.StripeResource.prototype.createUrlData)
1.  [function <span class="apidocSignatureSpan">stripe.StripeResource.prototype.</span>initialize ()](#apidoc.element.stripe.StripeResource.prototype.initialize)
1.  [function <span class="apidocSignatureSpan">stripe.StripeResource.prototype.</span>wrapTimeout (promise, callback)](#apidoc.element.stripe.StripeResource.prototype.wrapTimeout)
1.  object <span class="apidocSignatureSpan">stripe.StripeResource.prototype.</span>overrideHost
1.  object <span class="apidocSignatureSpan">stripe.StripeResource.prototype.</span>requestDataProcessor
1.  string <span class="apidocSignatureSpan">stripe.StripeResource.prototype.</span>path

#### [module stripe.resources](#apidoc.module.stripe.resources)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Account ()](#apidoc.element.stripe.resources.Account)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Accounts ()](#apidoc.element.stripe.resources.Accounts)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>ApplePayDomains ()](#apidoc.element.stripe.resources.ApplePayDomains)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>ApplicationFeeRefunds ()](#apidoc.element.stripe.resources.ApplicationFeeRefunds)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>ApplicationFees ()](#apidoc.element.stripe.resources.ApplicationFees)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Balance ()](#apidoc.element.stripe.resources.Balance)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>BitcoinReceivers ()](#apidoc.element.stripe.resources.BitcoinReceivers)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>ChargeRefunds ()](#apidoc.element.stripe.resources.ChargeRefunds)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Charges ()](#apidoc.element.stripe.resources.Charges)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>CountrySpecs ()](#apidoc.element.stripe.resources.CountrySpecs)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Coupons ()](#apidoc.element.stripe.resources.Coupons)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>CustomerCards ()](#apidoc.element.stripe.resources.CustomerCards)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>CustomerSubscriptions ()](#apidoc.element.stripe.resources.CustomerSubscriptions)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Customers ()](#apidoc.element.stripe.resources.Customers)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Disputes ()](#apidoc.element.stripe.resources.Disputes)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Events ()](#apidoc.element.stripe.resources.Events)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>FileUploads ()](#apidoc.element.stripe.resources.FileUploads)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>InvoiceItems ()](#apidoc.element.stripe.resources.InvoiceItems)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Invoices ()](#apidoc.element.stripe.resources.Invoices)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>OrderReturns ()](#apidoc.element.stripe.resources.OrderReturns)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Orders ()](#apidoc.element.stripe.resources.Orders)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Payouts ()](#apidoc.element.stripe.resources.Payouts)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Plans ()](#apidoc.element.stripe.resources.Plans)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Products ()](#apidoc.element.stripe.resources.Products)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>RecipientCards ()](#apidoc.element.stripe.resources.RecipientCards)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Recipients ()](#apidoc.element.stripe.resources.Recipients)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Refunds ()](#apidoc.element.stripe.resources.Refunds)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Skus ()](#apidoc.element.stripe.resources.Skus)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Sources ()](#apidoc.element.stripe.resources.Sources)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>SubscriptionItems ()](#apidoc.element.stripe.resources.SubscriptionItems)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Subscriptions ()](#apidoc.element.stripe.resources.Subscriptions)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>ThreeDSecure ()](#apidoc.element.stripe.resources.ThreeDSecure)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Tokens ()](#apidoc.element.stripe.resources.Tokens)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>TransferReversals ()](#apidoc.element.stripe.resources.TransferReversals)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Transfers ()](#apidoc.element.stripe.resources.Transfers)

#### [module stripe.resources.Account](#apidoc.module.stripe.resources.Account)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Account ()](#apidoc.element.stripe.resources.Account.Account)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Account.</span>extend (sub)](#apidoc.element.stripe.resources.Account.extend)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Account.</span>method (spec)](#apidoc.element.stripe.resources.Account.method)
1.  object <span class="apidocSignatureSpan">stripe.resources.Account.</span>BASIC_METHODS

#### [module stripe.resources.Account.prototype](#apidoc.module.stripe.resources.Account.prototype)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Account.prototype.</span>create ()](#apidoc.element.stripe.resources.Account.prototype.create)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Account.prototype.</span>createExternalAccount ()](#apidoc.element.stripe.resources.Account.prototype.createExternalAccount)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Account.prototype.</span>del ()](#apidoc.element.stripe.resources.Account.prototype.del)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Account.prototype.</span>deleteExternalAccount ()](#apidoc.element.stripe.resources.Account.prototype.deleteExternalAccount)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Account.prototype.</span>list ()](#apidoc.element.stripe.resources.Account.prototype.list)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Account.prototype.</span>listExternalAccounts ()](#apidoc.element.stripe.resources.Account.prototype.listExternalAccounts)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Account.prototype.</span>reject ()](#apidoc.element.stripe.resources.Account.prototype.reject)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Account.prototype.</span>retrieve (id)](#apidoc.element.stripe.resources.Account.prototype.retrieve)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Account.prototype.</span>retrieveExternalAccount ()](#apidoc.element.stripe.resources.Account.prototype.retrieveExternalAccount)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Account.prototype.</span>update ()](#apidoc.element.stripe.resources.Account.prototype.update)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Account.prototype.</span>updateExternalAccount ()](#apidoc.element.stripe.resources.Account.prototype.updateExternalAccount)

#### [module stripe.resources.ApplePayDomains](#apidoc.module.stripe.resources.ApplePayDomains)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>ApplePayDomains ()](#apidoc.element.stripe.resources.ApplePayDomains.ApplePayDomains)
1.  [function <span class="apidocSignatureSpan">stripe.resources.ApplePayDomains.</span>extend (sub)](#apidoc.element.stripe.resources.ApplePayDomains.extend)
1.  [function <span class="apidocSignatureSpan">stripe.resources.ApplePayDomains.</span>method (spec)](#apidoc.element.stripe.resources.ApplePayDomains.method)
1.  object <span class="apidocSignatureSpan">stripe.resources.ApplePayDomains.</span>BASIC_METHODS

#### [module stripe.resources.ApplicationFeeRefunds](#apidoc.module.stripe.resources.ApplicationFeeRefunds)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>ApplicationFeeRefunds ()](#apidoc.element.stripe.resources.ApplicationFeeRefunds.ApplicationFeeRefunds)
1.  [function <span class="apidocSignatureSpan">stripe.resources.ApplicationFeeRefunds.</span>extend (sub)](#apidoc.element.stripe.resources.ApplicationFeeRefunds.extend)
1.  [function <span class="apidocSignatureSpan">stripe.resources.ApplicationFeeRefunds.</span>method (spec)](#apidoc.element.stripe.resources.ApplicationFeeRefunds.method)
1.  object <span class="apidocSignatureSpan">stripe.resources.ApplicationFeeRefunds.</span>BASIC_METHODS

#### [module stripe.resources.ApplicationFees](#apidoc.module.stripe.resources.ApplicationFees)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>ApplicationFees ()](#apidoc.element.stripe.resources.ApplicationFees.ApplicationFees)
1.  [function <span class="apidocSignatureSpan">stripe.resources.ApplicationFees.</span>extend (sub)](#apidoc.element.stripe.resources.ApplicationFees.extend)
1.  [function <span class="apidocSignatureSpan">stripe.resources.ApplicationFees.</span>method (spec)](#apidoc.element.stripe.resources.ApplicationFees.method)
1.  object <span class="apidocSignatureSpan">stripe.resources.ApplicationFees.</span>BASIC_METHODS

#### [module stripe.resources.ApplicationFees.prototype](#apidoc.module.stripe.resources.ApplicationFees.prototype)
1.  [function <span class="apidocSignatureSpan">stripe.resources.ApplicationFees.prototype.</span>createRefund ()](#apidoc.element.stripe.resources.ApplicationFees.prototype.createRefund)
1.  [function <span class="apidocSignatureSpan">stripe.resources.ApplicationFees.prototype.</span>listRefunds ()](#apidoc.element.stripe.resources.ApplicationFees.prototype.listRefunds)
1.  [function <span class="apidocSignatureSpan">stripe.resources.ApplicationFees.prototype.</span>refund ()](#apidoc.element.stripe.resources.ApplicationFees.prototype.refund)
1.  [function <span class="apidocSignatureSpan">stripe.resources.ApplicationFees.prototype.</span>retrieveRefund ()](#apidoc.element.stripe.resources.ApplicationFees.prototype.retrieveRefund)
1.  [function <span class="apidocSignatureSpan">stripe.resources.ApplicationFees.prototype.</span>updateRefund ()](#apidoc.element.stripe.resources.ApplicationFees.prototype.updateRefund)
1.  object <span class="apidocSignatureSpan">stripe.resources.ApplicationFees.prototype.</span>includeBasic
1.  string <span class="apidocSignatureSpan">stripe.resources.ApplicationFees.prototype.</span>path

#### [module stripe.resources.Balance](#apidoc.module.stripe.resources.Balance)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Balance ()](#apidoc.element.stripe.resources.Balance.Balance)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Balance.</span>extend (sub)](#apidoc.element.stripe.resources.Balance.extend)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Balance.</span>method (spec)](#apidoc.element.stripe.resources.Balance.method)
1.  object <span class="apidocSignatureSpan">stripe.resources.Balance.</span>BASIC_METHODS

#### [module stripe.resources.Balance.prototype](#apidoc.module.stripe.resources.Balance.prototype)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Balance.prototype.</span>listTransactions ()](#apidoc.element.stripe.resources.Balance.prototype.listTransactions)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Balance.prototype.</span>retrieve ()](#apidoc.element.stripe.resources.Balance.prototype.retrieve)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Balance.prototype.</span>retrieveTransaction ()](#apidoc.element.stripe.resources.Balance.prototype.retrieveTransaction)
1.  string <span class="apidocSignatureSpan">stripe.resources.Balance.prototype.</span>path

#### [module stripe.resources.BitcoinReceivers](#apidoc.module.stripe.resources.BitcoinReceivers)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>BitcoinReceivers ()](#apidoc.element.stripe.resources.BitcoinReceivers.BitcoinReceivers)
1.  [function <span class="apidocSignatureSpan">stripe.resources.BitcoinReceivers.</span>extend (sub)](#apidoc.element.stripe.resources.BitcoinReceivers.extend)
1.  [function <span class="apidocSignatureSpan">stripe.resources.BitcoinReceivers.</span>method (spec)](#apidoc.element.stripe.resources.BitcoinReceivers.method)
1.  object <span class="apidocSignatureSpan">stripe.resources.BitcoinReceivers.</span>BASIC_METHODS

#### [module stripe.resources.BitcoinReceivers.prototype](#apidoc.module.stripe.resources.BitcoinReceivers.prototype)
1.  [function <span class="apidocSignatureSpan">stripe.resources.BitcoinReceivers.prototype.</span>listTransactions ()](#apidoc.element.stripe.resources.BitcoinReceivers.prototype.listTransactions)
1.  object <span class="apidocSignatureSpan">stripe.resources.BitcoinReceivers.prototype.</span>includeBasic
1.  string <span class="apidocSignatureSpan">stripe.resources.BitcoinReceivers.prototype.</span>path

#### [module stripe.resources.ChargeRefunds](#apidoc.module.stripe.resources.ChargeRefunds)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>ChargeRefunds ()](#apidoc.element.stripe.resources.ChargeRefunds.ChargeRefunds)
1.  [function <span class="apidocSignatureSpan">stripe.resources.ChargeRefunds.</span>extend (sub)](#apidoc.element.stripe.resources.ChargeRefunds.extend)
1.  [function <span class="apidocSignatureSpan">stripe.resources.ChargeRefunds.</span>method (spec)](#apidoc.element.stripe.resources.ChargeRefunds.method)
1.  object <span class="apidocSignatureSpan">stripe.resources.ChargeRefunds.</span>BASIC_METHODS

#### [module stripe.resources.Charges](#apidoc.module.stripe.resources.Charges)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Charges ()](#apidoc.element.stripe.resources.Charges.Charges)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Charges.</span>extend (sub)](#apidoc.element.stripe.resources.Charges.extend)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Charges.</span>method (spec)](#apidoc.element.stripe.resources.Charges.method)
1.  object <span class="apidocSignatureSpan">stripe.resources.Charges.</span>BASIC_METHODS

#### [module stripe.resources.Charges.prototype](#apidoc.module.stripe.resources.Charges.prototype)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Charges.prototype.</span>capture ()](#apidoc.element.stripe.resources.Charges.prototype.capture)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Charges.prototype.</span>closeDispute ()](#apidoc.element.stripe.resources.Charges.prototype.closeDispute)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Charges.prototype.</span>createRefund ()](#apidoc.element.stripe.resources.Charges.prototype.createRefund)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Charges.prototype.</span>listRefunds ()](#apidoc.element.stripe.resources.Charges.prototype.listRefunds)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Charges.prototype.</span>markAsFraudulent (chargeId)](#apidoc.element.stripe.resources.Charges.prototype.markAsFraudulent)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Charges.prototype.</span>markAsSafe (chargeId)](#apidoc.element.stripe.resources.Charges.prototype.markAsSafe)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Charges.prototype.</span>refund ()](#apidoc.element.stripe.resources.Charges.prototype.refund)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Charges.prototype.</span>retrieveRefund ()](#apidoc.element.stripe.resources.Charges.prototype.retrieveRefund)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Charges.prototype.</span>updateDispute ()](#apidoc.element.stripe.resources.Charges.prototype.updateDispute)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Charges.prototype.</span>updateRefund ()](#apidoc.element.stripe.resources.Charges.prototype.updateRefund)
1.  object <span class="apidocSignatureSpan">stripe.resources.Charges.prototype.</span>includeBasic
1.  string <span class="apidocSignatureSpan">stripe.resources.Charges.prototype.</span>path

#### [module stripe.resources.CountrySpecs](#apidoc.module.stripe.resources.CountrySpecs)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>CountrySpecs ()](#apidoc.element.stripe.resources.CountrySpecs.CountrySpecs)
1.  [function <span class="apidocSignatureSpan">stripe.resources.CountrySpecs.</span>extend (sub)](#apidoc.element.stripe.resources.CountrySpecs.extend)
1.  [function <span class="apidocSignatureSpan">stripe.resources.CountrySpecs.</span>method (spec)](#apidoc.element.stripe.resources.CountrySpecs.method)
1.  object <span class="apidocSignatureSpan">stripe.resources.CountrySpecs.</span>BASIC_METHODS

#### [module stripe.resources.Coupons](#apidoc.module.stripe.resources.Coupons)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Coupons ()](#apidoc.element.stripe.resources.Coupons.Coupons)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Coupons.</span>extend (sub)](#apidoc.element.stripe.resources.Coupons.extend)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Coupons.</span>method (spec)](#apidoc.element.stripe.resources.Coupons.method)
1.  object <span class="apidocSignatureSpan">stripe.resources.Coupons.</span>BASIC_METHODS

#### [module stripe.resources.CustomerCards](#apidoc.module.stripe.resources.CustomerCards)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>CustomerCards ()](#apidoc.element.stripe.resources.CustomerCards.CustomerCards)
1.  [function <span class="apidocSignatureSpan">stripe.resources.CustomerCards.</span>extend (sub)](#apidoc.element.stripe.resources.CustomerCards.extend)
1.  [function <span class="apidocSignatureSpan">stripe.resources.CustomerCards.</span>method (spec)](#apidoc.element.stripe.resources.CustomerCards.method)
1.  object <span class="apidocSignatureSpan">stripe.resources.CustomerCards.</span>BASIC_METHODS

#### [module stripe.resources.CustomerSubscriptions](#apidoc.module.stripe.resources.CustomerSubscriptions)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>CustomerSubscriptions ()](#apidoc.element.stripe.resources.CustomerSubscriptions.CustomerSubscriptions)
1.  [function <span class="apidocSignatureSpan">stripe.resources.CustomerSubscriptions.</span>extend (sub)](#apidoc.element.stripe.resources.CustomerSubscriptions.extend)
1.  [function <span class="apidocSignatureSpan">stripe.resources.CustomerSubscriptions.</span>method (spec)](#apidoc.element.stripe.resources.CustomerSubscriptions.method)
1.  object <span class="apidocSignatureSpan">stripe.resources.CustomerSubscriptions.</span>BASIC_METHODS

#### [module stripe.resources.CustomerSubscriptions.prototype](#apidoc.module.stripe.resources.CustomerSubscriptions.prototype)
1.  [function <span class="apidocSignatureSpan">stripe.resources.CustomerSubscriptions.prototype.</span>deleteDiscount ()](#apidoc.element.stripe.resources.CustomerSubscriptions.prototype.deleteDiscount)
1.  object <span class="apidocSignatureSpan">stripe.resources.CustomerSubscriptions.prototype.</span>includeBasic
1.  string <span class="apidocSignatureSpan">stripe.resources.CustomerSubscriptions.prototype.</span>path

#### [module stripe.resources.Customers](#apidoc.module.stripe.resources.Customers)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Customers ()](#apidoc.element.stripe.resources.Customers.Customers)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Customers.</span>extend (sub)](#apidoc.element.stripe.resources.Customers.extend)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Customers.</span>method (spec)](#apidoc.element.stripe.resources.Customers.method)
1.  object <span class="apidocSignatureSpan">stripe.resources.Customers.</span>BASIC_METHODS

#### [module stripe.resources.Customers.prototype](#apidoc.module.stripe.resources.Customers.prototype)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>_legacyCancelSubscription ()](#apidoc.element.stripe.resources.Customers.prototype._legacyCancelSubscription)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>_legacyUpdateSubscription ()](#apidoc.element.stripe.resources.Customers.prototype._legacyUpdateSubscription)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>_newstyleCancelSubscription ()](#apidoc.element.stripe.resources.Customers.prototype._newstyleCancelSubscription)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>_newstyleUpdateSubscription ()](#apidoc.element.stripe.resources.Customers.prototype._newstyleUpdateSubscription)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>cancelSubscription (customerId, subscriptionId)](#apidoc.element.stripe.resources.Customers.prototype.cancelSubscription)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>createCard ()](#apidoc.element.stripe.resources.Customers.prototype.createCard)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>createSource ()](#apidoc.element.stripe.resources.Customers.prototype.createSource)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>createSubscription ()](#apidoc.element.stripe.resources.Customers.prototype.createSubscription)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>deleteCard ()](#apidoc.element.stripe.resources.Customers.prototype.deleteCard)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>deleteDiscount ()](#apidoc.element.stripe.resources.Customers.prototype.deleteDiscount)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>deleteSource ()](#apidoc.element.stripe.resources.Customers.prototype.deleteSource)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>deleteSubscriptionDiscount ()](#apidoc.element.stripe.resources.Customers.prototype.deleteSubscriptionDiscount)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>listCards ()](#apidoc.element.stripe.resources.Customers.prototype.listCards)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>listSources ()](#apidoc.element.stripe.resources.Customers.prototype.listSources)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>listSubscriptions ()](#apidoc.element.stripe.resources.Customers.prototype.listSubscriptions)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>retrieveCard ()](#apidoc.element.stripe.resources.Customers.prototype.retrieveCard)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>retrieveSource ()](#apidoc.element.stripe.resources.Customers.prototype.retrieveSource)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>retrieveSubscription ()](#apidoc.element.stripe.resources.Customers.prototype.retrieveSubscription)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>updateCard ()](#apidoc.element.stripe.resources.Customers.prototype.updateCard)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>updateSource ()](#apidoc.element.stripe.resources.Customers.prototype.updateSource)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>updateSubscription (customerId, subscriptionId)](#apidoc.element.stripe.resources.Customers.prototype.updateSubscription)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>verifySource ()](#apidoc.element.stripe.resources.Customers.prototype.verifySource)
1.  object <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>includeBasic
1.  string <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>path

#### [module stripe.resources.Disputes](#apidoc.module.stripe.resources.Disputes)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Disputes ()](#apidoc.element.stripe.resources.Disputes.Disputes)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Disputes.</span>extend (sub)](#apidoc.element.stripe.resources.Disputes.extend)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Disputes.</span>method (spec)](#apidoc.element.stripe.resources.Disputes.method)
1.  object <span class="apidocSignatureSpan">stripe.resources.Disputes.</span>BASIC_METHODS

#### [module stripe.resources.Disputes.prototype](#apidoc.module.stripe.resources.Disputes.prototype)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Disputes.prototype.</span>close ()](#apidoc.element.stripe.resources.Disputes.prototype.close)
1.  object <span class="apidocSignatureSpan">stripe.resources.Disputes.prototype.</span>includeBasic
1.  string <span class="apidocSignatureSpan">stripe.resources.Disputes.prototype.</span>path

#### [module stripe.resources.Events](#apidoc.module.stripe.resources.Events)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Events ()](#apidoc.element.stripe.resources.Events.Events)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Events.</span>extend (sub)](#apidoc.element.stripe.resources.Events.extend)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Events.</span>method (spec)](#apidoc.element.stripe.resources.Events.method)
1.  object <span class="apidocSignatureSpan">stripe.resources.Events.</span>BASIC_METHODS

#### [module stripe.resources.FileUploads](#apidoc.module.stripe.resources.FileUploads)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>FileUploads ()](#apidoc.element.stripe.resources.FileUploads.FileUploads)
1.  [function <span class="apidocSignatureSpan">stripe.resources.FileUploads.</span>extend (sub)](#apidoc.element.stripe.resources.FileUploads.extend)
1.  [function <span class="apidocSignatureSpan">stripe.resources.FileUploads.</span>method (spec)](#apidoc.element.stripe.resources.FileUploads.method)
1.  object <span class="apidocSignatureSpan">stripe.resources.FileUploads.</span>BASIC_METHODS

#### [module stripe.resources.FileUploads.prototype](#apidoc.module.stripe.resources.FileUploads.prototype)
1.  [function <span class="apidocSignatureSpan">stripe.resources.FileUploads.prototype.</span>create ()](#apidoc.element.stripe.resources.FileUploads.prototype.create)
1.  [function <span class="apidocSignatureSpan">stripe.resources.FileUploads.prototype.</span>requestDataProcessor (method, data, headers)](#apidoc.element.stripe.resources.FileUploads.prototype.requestDataProcessor)
1.  object <span class="apidocSignatureSpan">stripe.resources.FileUploads.prototype.</span>includeBasic
1.  string <span class="apidocSignatureSpan">stripe.resources.FileUploads.prototype.</span>overrideHost
1.  string <span class="apidocSignatureSpan">stripe.resources.FileUploads.prototype.</span>path

#### [module stripe.resources.InvoiceItems](#apidoc.module.stripe.resources.InvoiceItems)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>InvoiceItems ()](#apidoc.element.stripe.resources.InvoiceItems.InvoiceItems)
1.  [function <span class="apidocSignatureSpan">stripe.resources.InvoiceItems.</span>extend (sub)](#apidoc.element.stripe.resources.InvoiceItems.extend)
1.  [function <span class="apidocSignatureSpan">stripe.resources.InvoiceItems.</span>method (spec)](#apidoc.element.stripe.resources.InvoiceItems.method)
1.  object <span class="apidocSignatureSpan">stripe.resources.InvoiceItems.</span>BASIC_METHODS

#### [module stripe.resources.Invoices](#apidoc.module.stripe.resources.Invoices)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Invoices ()](#apidoc.element.stripe.resources.Invoices.Invoices)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Invoices.</span>extend (sub)](#apidoc.element.stripe.resources.Invoices.extend)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Invoices.</span>method (spec)](#apidoc.element.stripe.resources.Invoices.method)
1.  object <span class="apidocSignatureSpan">stripe.resources.Invoices.</span>BASIC_METHODS

#### [module stripe.resources.Invoices.prototype](#apidoc.module.stripe.resources.Invoices.prototype)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Invoices.prototype.</span>pay ()](#apidoc.element.stripe.resources.Invoices.prototype.pay)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Invoices.prototype.</span>retrieveLines ()](#apidoc.element.stripe.resources.Invoices.prototype.retrieveLines)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Invoices.prototype.</span>retrieveUpcoming ()](#apidoc.element.stripe.resources.Invoices.prototype.retrieveUpcoming)
1.  object <span class="apidocSignatureSpan">stripe.resources.Invoices.prototype.</span>includeBasic
1.  string <span class="apidocSignatureSpan">stripe.resources.Invoices.prototype.</span>path

#### [module stripe.resources.OrderReturns](#apidoc.module.stripe.resources.OrderReturns)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>OrderReturns ()](#apidoc.element.stripe.resources.OrderReturns.OrderReturns)
1.  [function <span class="apidocSignatureSpan">stripe.resources.OrderReturns.</span>extend (sub)](#apidoc.element.stripe.resources.OrderReturns.extend)
1.  [function <span class="apidocSignatureSpan">stripe.resources.OrderReturns.</span>method (spec)](#apidoc.element.stripe.resources.OrderReturns.method)
1.  object <span class="apidocSignatureSpan">stripe.resources.OrderReturns.</span>BASIC_METHODS

#### [module stripe.resources.Orders](#apidoc.module.stripe.resources.Orders)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Orders ()](#apidoc.element.stripe.resources.Orders.Orders)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Orders.</span>extend (sub)](#apidoc.element.stripe.resources.Orders.extend)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Orders.</span>method (spec)](#apidoc.element.stripe.resources.Orders.method)
1.  object <span class="apidocSignatureSpan">stripe.resources.Orders.</span>BASIC_METHODS

#### [module stripe.resources.Orders.prototype](#apidoc.module.stripe.resources.Orders.prototype)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Orders.prototype.</span>create ()](#apidoc.element.stripe.resources.Orders.prototype.create)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Orders.prototype.</span>pay ()](#apidoc.element.stripe.resources.Orders.prototype.pay)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Orders.prototype.</span>returnOrder ()](#apidoc.element.stripe.resources.Orders.prototype.returnOrder)
1.  object <span class="apidocSignatureSpan">stripe.resources.Orders.prototype.</span>includeBasic
1.  string <span class="apidocSignatureSpan">stripe.resources.Orders.prototype.</span>path

#### [module stripe.resources.Payouts](#apidoc.module.stripe.resources.Payouts)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Payouts ()](#apidoc.element.stripe.resources.Payouts.Payouts)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Payouts.</span>extend (sub)](#apidoc.element.stripe.resources.Payouts.extend)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Payouts.</span>method (spec)](#apidoc.element.stripe.resources.Payouts.method)
1.  object <span class="apidocSignatureSpan">stripe.resources.Payouts.</span>BASIC_METHODS

#### [module stripe.resources.Payouts.prototype](#apidoc.module.stripe.resources.Payouts.prototype)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Payouts.prototype.</span>cancel ()](#apidoc.element.stripe.resources.Payouts.prototype.cancel)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Payouts.prototype.</span>listTransactions ()](#apidoc.element.stripe.resources.Payouts.prototype.listTransactions)
1.  object <span class="apidocSignatureSpan">stripe.resources.Payouts.prototype.</span>includeBasic
1.  string <span class="apidocSignatureSpan">stripe.resources.Payouts.prototype.</span>path

#### [module stripe.resources.Plans](#apidoc.module.stripe.resources.Plans)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Plans ()](#apidoc.element.stripe.resources.Plans.Plans)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Plans.</span>extend (sub)](#apidoc.element.stripe.resources.Plans.extend)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Plans.</span>method (spec)](#apidoc.element.stripe.resources.Plans.method)
1.  object <span class="apidocSignatureSpan">stripe.resources.Plans.</span>BASIC_METHODS

#### [module stripe.resources.Products](#apidoc.module.stripe.resources.Products)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Products ()](#apidoc.element.stripe.resources.Products.Products)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Products.</span>extend (sub)](#apidoc.element.stripe.resources.Products.extend)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Products.</span>method (spec)](#apidoc.element.stripe.resources.Products.method)
1.  object <span class="apidocSignatureSpan">stripe.resources.Products.</span>BASIC_METHODS

#### [module stripe.resources.Products.prototype](#apidoc.module.stripe.resources.Products.prototype)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Products.prototype.</span>create ()](#apidoc.element.stripe.resources.Products.prototype.create)
1.  object <span class="apidocSignatureSpan">stripe.resources.Products.prototype.</span>includeBasic
1.  string <span class="apidocSignatureSpan">stripe.resources.Products.prototype.</span>path

#### [module stripe.resources.RecipientCards](#apidoc.module.stripe.resources.RecipientCards)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>RecipientCards ()](#apidoc.element.stripe.resources.RecipientCards.RecipientCards)
1.  [function <span class="apidocSignatureSpan">stripe.resources.RecipientCards.</span>extend (sub)](#apidoc.element.stripe.resources.RecipientCards.extend)
1.  [function <span class="apidocSignatureSpan">stripe.resources.RecipientCards.</span>method (spec)](#apidoc.element.stripe.resources.RecipientCards.method)
1.  object <span class="apidocSignatureSpan">stripe.resources.RecipientCards.</span>BASIC_METHODS

#### [module stripe.resources.Recipients](#apidoc.module.stripe.resources.Recipients)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Recipients ()](#apidoc.element.stripe.resources.Recipients.Recipients)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Recipients.</span>extend (sub)](#apidoc.element.stripe.resources.Recipients.extend)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Recipients.</span>method (spec)](#apidoc.element.stripe.resources.Recipients.method)
1.  object <span class="apidocSignatureSpan">stripe.resources.Recipients.</span>BASIC_METHODS

#### [module stripe.resources.Recipients.prototype](#apidoc.module.stripe.resources.Recipients.prototype)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Recipients.prototype.</span>createCard ()](#apidoc.element.stripe.resources.Recipients.prototype.createCard)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Recipients.prototype.</span>deleteCard ()](#apidoc.element.stripe.resources.Recipients.prototype.deleteCard)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Recipients.prototype.</span>listCards ()](#apidoc.element.stripe.resources.Recipients.prototype.listCards)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Recipients.prototype.</span>retrieveCard ()](#apidoc.element.stripe.resources.Recipients.prototype.retrieveCard)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Recipients.prototype.</span>updateCard ()](#apidoc.element.stripe.resources.Recipients.prototype.updateCard)
1.  object <span class="apidocSignatureSpan">stripe.resources.Recipients.prototype.</span>includeBasic
1.  string <span class="apidocSignatureSpan">stripe.resources.Recipients.prototype.</span>path

#### [module stripe.resources.Refunds](#apidoc.module.stripe.resources.Refunds)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Refunds ()](#apidoc.element.stripe.resources.Refunds.Refunds)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Refunds.</span>extend (sub)](#apidoc.element.stripe.resources.Refunds.extend)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Refunds.</span>method (spec)](#apidoc.element.stripe.resources.Refunds.method)
1.  object <span class="apidocSignatureSpan">stripe.resources.Refunds.</span>BASIC_METHODS

#### [module stripe.resources.Skus](#apidoc.module.stripe.resources.Skus)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Skus ()](#apidoc.element.stripe.resources.Skus.Skus)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Skus.</span>extend (sub)](#apidoc.element.stripe.resources.Skus.extend)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Skus.</span>method (spec)](#apidoc.element.stripe.resources.Skus.method)
1.  object <span class="apidocSignatureSpan">stripe.resources.Skus.</span>BASIC_METHODS

#### [module stripe.resources.Skus.prototype](#apidoc.module.stripe.resources.Skus.prototype)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Skus.prototype.</span>create ()](#apidoc.element.stripe.resources.Skus.prototype.create)
1.  object <span class="apidocSignatureSpan">stripe.resources.Skus.prototype.</span>includeBasic
1.  string <span class="apidocSignatureSpan">stripe.resources.Skus.prototype.</span>path

#### [module stripe.resources.Sources](#apidoc.module.stripe.resources.Sources)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Sources ()](#apidoc.element.stripe.resources.Sources.Sources)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Sources.</span>extend (sub)](#apidoc.element.stripe.resources.Sources.extend)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Sources.</span>method (spec)](#apidoc.element.stripe.resources.Sources.method)
1.  object <span class="apidocSignatureSpan">stripe.resources.Sources.</span>BASIC_METHODS

#### [module stripe.resources.Sources.prototype](#apidoc.module.stripe.resources.Sources.prototype)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Sources.prototype.</span>verify ()](#apidoc.element.stripe.resources.Sources.prototype.verify)
1.  object <span class="apidocSignatureSpan">stripe.resources.Sources.prototype.</span>includeBasic
1.  string <span class="apidocSignatureSpan">stripe.resources.Sources.prototype.</span>path

#### [module stripe.resources.SubscriptionItems](#apidoc.module.stripe.resources.SubscriptionItems)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>SubscriptionItems ()](#apidoc.element.stripe.resources.SubscriptionItems.SubscriptionItems)
1.  [function <span class="apidocSignatureSpan">stripe.resources.SubscriptionItems.</span>extend (sub)](#apidoc.element.stripe.resources.SubscriptionItems.extend)
1.  [function <span class="apidocSignatureSpan">stripe.resources.SubscriptionItems.</span>method (spec)](#apidoc.element.stripe.resources.SubscriptionItems.method)
1.  object <span class="apidocSignatureSpan">stripe.resources.SubscriptionItems.</span>BASIC_METHODS

#### [module stripe.resources.Subscriptions](#apidoc.module.stripe.resources.Subscriptions)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Subscriptions ()](#apidoc.element.stripe.resources.Subscriptions.Subscriptions)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Subscriptions.</span>extend (sub)](#apidoc.element.stripe.resources.Subscriptions.extend)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Subscriptions.</span>method (spec)](#apidoc.element.stripe.resources.Subscriptions.method)
1.  object <span class="apidocSignatureSpan">stripe.resources.Subscriptions.</span>BASIC_METHODS

#### [module stripe.resources.Subscriptions.prototype](#apidoc.module.stripe.resources.Subscriptions.prototype)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Subscriptions.prototype.</span>create ()](#apidoc.element.stripe.resources.Subscriptions.prototype.create)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Subscriptions.prototype.</span>deleteDiscount ()](#apidoc.element.stripe.resources.Subscriptions.prototype.deleteDiscount)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Subscriptions.prototype.</span>update ()](#apidoc.element.stripe.resources.Subscriptions.prototype.update)
1.  object <span class="apidocSignatureSpan">stripe.resources.Subscriptions.prototype.</span>includeBasic
1.  string <span class="apidocSignatureSpan">stripe.resources.Subscriptions.prototype.</span>path

#### [module stripe.resources.ThreeDSecure](#apidoc.module.stripe.resources.ThreeDSecure)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>ThreeDSecure ()](#apidoc.element.stripe.resources.ThreeDSecure.ThreeDSecure)
1.  [function <span class="apidocSignatureSpan">stripe.resources.ThreeDSecure.</span>extend (sub)](#apidoc.element.stripe.resources.ThreeDSecure.extend)
1.  [function <span class="apidocSignatureSpan">stripe.resources.ThreeDSecure.</span>method (spec)](#apidoc.element.stripe.resources.ThreeDSecure.method)
1.  object <span class="apidocSignatureSpan">stripe.resources.ThreeDSecure.</span>BASIC_METHODS

#### [module stripe.resources.Tokens](#apidoc.module.stripe.resources.Tokens)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Tokens ()](#apidoc.element.stripe.resources.Tokens.Tokens)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Tokens.</span>extend (sub)](#apidoc.element.stripe.resources.Tokens.extend)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Tokens.</span>method (spec)](#apidoc.element.stripe.resources.Tokens.method)
1.  object <span class="apidocSignatureSpan">stripe.resources.Tokens.</span>BASIC_METHODS

#### [module stripe.resources.TransferReversals](#apidoc.module.stripe.resources.TransferReversals)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>TransferReversals ()](#apidoc.element.stripe.resources.TransferReversals.TransferReversals)
1.  [function <span class="apidocSignatureSpan">stripe.resources.TransferReversals.</span>extend (sub)](#apidoc.element.stripe.resources.TransferReversals.extend)
1.  [function <span class="apidocSignatureSpan">stripe.resources.TransferReversals.</span>method (spec)](#apidoc.element.stripe.resources.TransferReversals.method)
1.  object <span class="apidocSignatureSpan">stripe.resources.TransferReversals.</span>BASIC_METHODS

#### [module stripe.resources.Transfers](#apidoc.module.stripe.resources.Transfers)
1.  [function <span class="apidocSignatureSpan">stripe.resources.</span>Transfers ()](#apidoc.element.stripe.resources.Transfers.Transfers)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Transfers.</span>extend (sub)](#apidoc.element.stripe.resources.Transfers.extend)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Transfers.</span>method (spec)](#apidoc.element.stripe.resources.Transfers.method)
1.  object <span class="apidocSignatureSpan">stripe.resources.Transfers.</span>BASIC_METHODS

#### [module stripe.resources.Transfers.prototype](#apidoc.module.stripe.resources.Transfers.prototype)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Transfers.prototype.</span>cancel ()](#apidoc.element.stripe.resources.Transfers.prototype.cancel)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Transfers.prototype.</span>createReversal ()](#apidoc.element.stripe.resources.Transfers.prototype.createReversal)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Transfers.prototype.</span>listReversals ()](#apidoc.element.stripe.resources.Transfers.prototype.listReversals)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Transfers.prototype.</span>listTransactions ()](#apidoc.element.stripe.resources.Transfers.prototype.listTransactions)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Transfers.prototype.</span>retrieveReversal ()](#apidoc.element.stripe.resources.Transfers.prototype.retrieveReversal)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Transfers.prototype.</span>reverse ()](#apidoc.element.stripe.resources.Transfers.prototype.reverse)
1.  [function <span class="apidocSignatureSpan">stripe.resources.Transfers.prototype.</span>updateReversal ()](#apidoc.element.stripe.resources.Transfers.prototype.updateReversal)
1.  object <span class="apidocSignatureSpan">stripe.resources.Transfers.prototype.</span>includeBasic
1.  string <span class="apidocSignatureSpan">stripe.resources.Transfers.prototype.</span>path

#### [module stripe.utils](#apidoc.module.stripe.utils)
1.  [function <span class="apidocSignatureSpan">stripe.utils.</span>arrayToObject (arr)](#apidoc.element.stripe.utils.arrayToObject)
1.  [function <span class="apidocSignatureSpan">stripe.utils.</span>getDataFromArgs (args)](#apidoc.element.stripe.utils.getDataFromArgs)
1.  [function <span class="apidocSignatureSpan">stripe.utils.</span>getOptionsFromArgs (args)](#apidoc.element.stripe.utils.getOptionsFromArgs)
1.  [function <span class="apidocSignatureSpan">stripe.utils.</span>isAuthKey (key)](#apidoc.element.stripe.utils.isAuthKey)
1.  [function <span class="apidocSignatureSpan">stripe.utils.</span>isOptionsHash (o)](#apidoc.element.stripe.utils.isOptionsHash)
1.  [function <span class="apidocSignatureSpan">stripe.utils.</span>makeURLInterpolator (str)](#apidoc.element.stripe.utils.makeURLInterpolator)
1.  [function <span class="apidocSignatureSpan">stripe.utils.</span>protoExtend (sub)](#apidoc.element.stripe.utils.protoExtend)
1.  [function <span class="apidocSignatureSpan">stripe.utils.</span>stringifyRequestData (data)](#apidoc.element.stripe.utils.stringifyRequestData)



# <a name="apidoc.module.stripe"></a>[module stripe](#apidoc.module.stripe)

#### <a name="apidoc.element.stripe.Error"></a>[function <span class="apidocSignatureSpan">stripe.</span>Error (raw)](#apidoc.element.stripe.Error)
- description and source-code
```javascript
function _Error(raw) {
  this.populate.apply(this, arguments);
  this.stack = (new Error(this.message)).stack;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.Stripe"></a>[function <span class="apidocSignatureSpan">stripe.</span>Stripe (key, version)](#apidoc.element.stripe.Stripe)
- description and source-code
```javascript
function Stripe(key, version) {
  if (!(this instanceof Stripe)) {
    return new Stripe(key, version);
  }

  this._api = {
    auth: null,
    host: Stripe.DEFAULT_HOST,
    port: Stripe.DEFAULT_PORT,
    basePath: Stripe.DEFAULT_BASE_PATH,
    version: Stripe.DEFAULT_API_VERSION,
    timeout: Stripe.DEFAULT_TIMEOUT,
    agent: null,
    dev: false,
  };

  this._prepResources();
  this.setApiKey(key);
  this.setApiVersion(version);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.StripeResource"></a>[function <span class="apidocSignatureSpan">stripe.</span>StripeResource (stripe, urlData)](#apidoc.element.stripe.StripeResource)
- description and source-code
```javascript
function StripeResource(stripe, urlData) {
  this._stripe = stripe;
  this._urlData = urlData || {};

  this.basePath = utils.makeURLInterpolator(stripe.getApiField('basePath'));
  this.path = utils.makeURLInterpolator(this.path);

  if (this.includeBasic) {
    this.includeBasic.forEach(function(methodName) {
      this[methodName] = StripeResource.BASIC_METHODS[methodName];
    }, this);
  }

  this.initialize.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Account"></a>[function <span class="apidocSignatureSpan">stripe.</span>resources.Account ()](#apidoc.element.stripe.resources.Account)
- description and source-code
```javascript
resources.Account = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.ApplePayDomains"></a>[function <span class="apidocSignatureSpan">stripe.</span>resources.ApplePayDomains ()](#apidoc.element.stripe.resources.ApplePayDomains)
- description and source-code
```javascript
resources.ApplePayDomains = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.ApplicationFeeRefunds"></a>[function <span class="apidocSignatureSpan">stripe.</span>resources.ApplicationFeeRefunds ()](#apidoc.element.stripe.resources.ApplicationFeeRefunds)
- description and source-code
```javascript
resources.ApplicationFeeRefunds = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.ApplicationFees"></a>[function <span class="apidocSignatureSpan">stripe.</span>resources.ApplicationFees ()](#apidoc.element.stripe.resources.ApplicationFees)
- description and source-code
```javascript
resources.ApplicationFees = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Balance"></a>[function <span class="apidocSignatureSpan">stripe.</span>resources.Balance ()](#apidoc.element.stripe.resources.Balance)
- description and source-code
```javascript
resources.Balance = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.BitcoinReceivers"></a>[function <span class="apidocSignatureSpan">stripe.</span>resources.BitcoinReceivers ()](#apidoc.element.stripe.resources.BitcoinReceivers)
- description and source-code
```javascript
resources.BitcoinReceivers = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.ChargeRefunds"></a>[function <span class="apidocSignatureSpan">stripe.</span>resources.ChargeRefunds ()](#apidoc.element.stripe.resources.ChargeRefunds)
- description and source-code
```javascript
resources.ChargeRefunds = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Charges"></a>[function <span class="apidocSignatureSpan">stripe.</span>resources.Charges ()](#apidoc.element.stripe.resources.Charges)
- description and source-code
```javascript
resources.Charges = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.CountrySpecs"></a>[function <span class="apidocSignatureSpan">stripe.</span>resources.CountrySpecs ()](#apidoc.element.stripe.resources.CountrySpecs)
- description and source-code
```javascript
resources.CountrySpecs = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Coupons"></a>[function <span class="apidocSignatureSpan">stripe.</span>resources.Coupons ()](#apidoc.element.stripe.resources.Coupons)
- description and source-code
```javascript
resources.Coupons = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.CustomerCards"></a>[function <span class="apidocSignatureSpan">stripe.</span>resources.CustomerCards ()](#apidoc.element.stripe.resources.CustomerCards)
- description and source-code
```javascript
resources.CustomerCards = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.CustomerSubscriptions"></a>[function <span class="apidocSignatureSpan">stripe.</span>resources.CustomerSubscriptions ()](#apidoc.element.stripe.resources.CustomerSubscriptions)
- description and source-code
```javascript
resources.CustomerSubscriptions = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Customers"></a>[function <span class="apidocSignatureSpan">stripe.</span>resources.Customers ()](#apidoc.element.stripe.resources.Customers)
- description and source-code
```javascript
resources.Customers = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Disputes"></a>[function <span class="apidocSignatureSpan">stripe.</span>resources.Disputes ()](#apidoc.element.stripe.resources.Disputes)
- description and source-code
```javascript
resources.Disputes = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Events"></a>[function <span class="apidocSignatureSpan">stripe.</span>resources.Events ()](#apidoc.element.stripe.resources.Events)
- description and source-code
```javascript
resources.Events = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.FileUploads"></a>[function <span class="apidocSignatureSpan">stripe.</span>resources.FileUploads ()](#apidoc.element.stripe.resources.FileUploads)
- description and source-code
```javascript
resources.FileUploads = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.InvoiceItems"></a>[function <span class="apidocSignatureSpan">stripe.</span>resources.InvoiceItems ()](#apidoc.element.stripe.resources.InvoiceItems)
- description and source-code
```javascript
resources.InvoiceItems = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Invoices"></a>[function <span class="apidocSignatureSpan">stripe.</span>resources.Invoices ()](#apidoc.element.stripe.resources.Invoices)
- description and source-code
```javascript
resources.Invoices = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.OrderReturns"></a>[function <span class="apidocSignatureSpan">stripe.</span>resources.OrderReturns ()](#apidoc.element.stripe.resources.OrderReturns)
- description and source-code
```javascript
resources.OrderReturns = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Orders"></a>[function <span class="apidocSignatureSpan">stripe.</span>resources.Orders ()](#apidoc.element.stripe.resources.Orders)
- description and source-code
```javascript
resources.Orders = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Payouts"></a>[function <span class="apidocSignatureSpan">stripe.</span>resources.Payouts ()](#apidoc.element.stripe.resources.Payouts)
- description and source-code
```javascript
resources.Payouts = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Plans"></a>[function <span class="apidocSignatureSpan">stripe.</span>resources.Plans ()](#apidoc.element.stripe.resources.Plans)
- description and source-code
```javascript
resources.Plans = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Products"></a>[function <span class="apidocSignatureSpan">stripe.</span>resources.Products ()](#apidoc.element.stripe.resources.Products)
- description and source-code
```javascript
resources.Products = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.RecipientCards"></a>[function <span class="apidocSignatureSpan">stripe.</span>resources.RecipientCards ()](#apidoc.element.stripe.resources.RecipientCards)
- description and source-code
```javascript
resources.RecipientCards = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Recipients"></a>[function <span class="apidocSignatureSpan">stripe.</span>resources.Recipients ()](#apidoc.element.stripe.resources.Recipients)
- description and source-code
```javascript
resources.Recipients = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Refunds"></a>[function <span class="apidocSignatureSpan">stripe.</span>resources.Refunds ()](#apidoc.element.stripe.resources.Refunds)
- description and source-code
```javascript
resources.Refunds = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Skus"></a>[function <span class="apidocSignatureSpan">stripe.</span>resources.Skus ()](#apidoc.element.stripe.resources.Skus)
- description and source-code
```javascript
resources.Skus = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Sources"></a>[function <span class="apidocSignatureSpan">stripe.</span>resources.Sources ()](#apidoc.element.stripe.resources.Sources)
- description and source-code
```javascript
resources.Sources = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.SubscriptionItems"></a>[function <span class="apidocSignatureSpan">stripe.</span>resources.SubscriptionItems ()](#apidoc.element.stripe.resources.SubscriptionItems)
- description and source-code
```javascript
resources.SubscriptionItems = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Subscriptions"></a>[function <span class="apidocSignatureSpan">stripe.</span>resources.Subscriptions ()](#apidoc.element.stripe.resources.Subscriptions)
- description and source-code
```javascript
resources.Subscriptions = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.ThreeDSecure"></a>[function <span class="apidocSignatureSpan">stripe.</span>resources.ThreeDSecure ()](#apidoc.element.stripe.resources.ThreeDSecure)
- description and source-code
```javascript
resources.ThreeDSecure = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Tokens"></a>[function <span class="apidocSignatureSpan">stripe.</span>resources.Tokens ()](#apidoc.element.stripe.resources.Tokens)
- description and source-code
```javascript
resources.Tokens = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.TransferReversals"></a>[function <span class="apidocSignatureSpan">stripe.</span>resources.TransferReversals ()](#apidoc.element.stripe.resources.TransferReversals)
- description and source-code
```javascript
resources.TransferReversals = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Transfers"></a>[function <span class="apidocSignatureSpan">stripe.</span>resources.Transfers ()](#apidoc.element.stripe.resources.Transfers)
- description and source-code
```javascript
resources.Transfers = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.Error"></a>[module stripe.Error](#apidoc.module.stripe.Error)

#### <a name="apidoc.element.stripe.Error.Error"></a>[function <span class="apidocSignatureSpan">stripe.</span>Error (raw)](#apidoc.element.stripe.Error.Error)
- description and source-code
```javascript
function _Error(raw) {
  this.populate.apply(this, arguments);
  this.stack = (new Error(this.message)).stack;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.Error.StripeAPIError"></a>[function <span class="apidocSignatureSpan">stripe.Error.</span>StripeAPIError ()](#apidoc.element.stripe.Error.StripeAPIError)
- description and source-code
```javascript
StripeAPIError = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
...
StripeError.generate = function(rawStripeError) {
  switch (rawStripeError.type) {
    case 'card_error':
      return new _Error.StripeCardError(rawStripeError);
    case 'invalid_request_error':
      return new _Error.StripeInvalidRequestError(rawStripeError);
    case 'api_error':
      return new _Error.StripeAPIError(rawStripeError);
  }
  return new _Error('Generic', 'Unknown Error');
};

// Specific Stripe Error types:
_Error.StripeCardError = StripeError.extend({type: 'StripeCardError'});
_Error.StripeInvalidRequestError = StripeError.extend({type: 'StripeInvalidRequestError'});
...
```

#### <a name="apidoc.element.stripe.Error.StripeAuthenticationError"></a>[function <span class="apidocSignatureSpan">stripe.Error.</span>StripeAuthenticationError ()](#apidoc.element.stripe.Error.StripeAuthenticationError)
- description and source-code
```javascript
StripeAuthenticationError = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.Error.StripeCardError"></a>[function <span class="apidocSignatureSpan">stripe.Error.</span>StripeCardError ()](#apidoc.element.stripe.Error.StripeCardError)
- description and source-code
```javascript
StripeCardError = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
...

/**
 * Helper factory which takes raw stripe errors and outputs wrapping instances
 */
StripeError.generate = function(rawStripeError) {
  switch (rawStripeError.type) {
    case 'card_error':
      return new _Error.StripeCardError(rawStripeError);
    case 'invalid_request_error':
      return new _Error.StripeInvalidRequestError(rawStripeError);
    case 'api_error':
      return new _Error.StripeAPIError(rawStripeError);
  }
  return new _Error('Generic', 'Unknown Error');
};
...
```

#### <a name="apidoc.element.stripe.Error.StripeConnectionError"></a>[function <span class="apidocSignatureSpan">stripe.Error.</span>StripeConnectionError ()](#apidoc.element.stripe.Error.StripeConnectionError)
- description and source-code
```javascript
StripeConnectionError = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.Error.StripeError"></a>[function <span class="apidocSignatureSpan">stripe.Error.</span>StripeError ()](#apidoc.element.stripe.Error.StripeError)
- description and source-code
```javascript
StripeError = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.Error.StripeInvalidRequestError"></a>[function <span class="apidocSignatureSpan">stripe.Error.</span>StripeInvalidRequestError ()](#apidoc.element.stripe.Error.StripeInvalidRequestError)
- description and source-code
```javascript
StripeInvalidRequestError = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
...
 * Helper factory which takes raw stripe errors and outputs wrapping instances
 */
StripeError.generate = function(rawStripeError) {
  switch (rawStripeError.type) {
    case 'card_error':
      return new _Error.StripeCardError(rawStripeError);
    case 'invalid_request_error':
      return new _Error.StripeInvalidRequestError(rawStripeError);
    case 'api_error':
      return new _Error.StripeAPIError(rawStripeError);
  }
  return new _Error('Generic', 'Unknown Error');
};

// Specific Stripe Error types:
...
```

#### <a name="apidoc.element.stripe.Error.StripePermissionError"></a>[function <span class="apidocSignatureSpan">stripe.Error.</span>StripePermissionError ()](#apidoc.element.stripe.Error.StripePermissionError)
- description and source-code
```javascript
StripePermissionError = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.Error.StripeRateLimitError"></a>[function <span class="apidocSignatureSpan">stripe.Error.</span>StripeRateLimitError ()](#apidoc.element.stripe.Error.StripeRateLimitError)
- description and source-code
```javascript
StripeRateLimitError = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.Error.extend"></a>[function <span class="apidocSignatureSpan">stripe.Error.</span>extend (sub)](#apidoc.element.stripe.Error.extend)
- description and source-code
```javascript
extend = function (sub) {
  var Super = this;
  var Constructor = hasOwn.call(sub, 'constructor') ? sub.constructor : function() {
    Super.apply(this, arguments);
  };
  Constructor.prototype = Object.create(Super.prototype);
  for (var i in sub) {
    if (hasOwn.call(sub, i)) {
      Constructor.prototype[i] = sub[i];
    }
  }
  for (i in Super) {
    if (hasOwn.call(Super, i)) {
      Constructor[i] = Super[i];
    }
  }
  return Constructor;
}
```
- example usage
```shell
...

_Error.extend = utils.protoExtend;

/**
 * Create subclass of internal Error klass
 * (Specifically for errors returned from Stripe's REST API)
 */
var StripeError = _Error.StripeError = _Error.extend({
  type: 'StripeError',
  populate: function(raw) {
// Move from prototype def (so it appears in stringified obj)
this.type = this.type;

this.stack = (new Error(raw.message)).stack;
this.rawType = raw.type;
...
```



# <a name="apidoc.module.stripe.Error.prototype"></a>[module stripe.Error.prototype](#apidoc.module.stripe.Error.prototype)

#### <a name="apidoc.element.stripe.Error.prototype.populate"></a>[function <span class="apidocSignatureSpan">stripe.Error.prototype.</span>populate (type, message)](#apidoc.element.stripe.Error.prototype.populate)
- description and source-code
```javascript
populate = function (type, message) {
  this.type = type;
  this.message = message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.StripeResource"></a>[module stripe.StripeResource](#apidoc.module.stripe.StripeResource)

#### <a name="apidoc.element.stripe.StripeResource.StripeResource"></a>[function <span class="apidocSignatureSpan">stripe.</span>StripeResource (stripe, urlData)](#apidoc.element.stripe.StripeResource.StripeResource)
- description and source-code
```javascript
function StripeResource(stripe, urlData) {
  this._stripe = stripe;
  this._urlData = urlData || {};

  this.basePath = utils.makeURLInterpolator(stripe.getApiField('basePath'));
  this.path = utils.makeURLInterpolator(this.path);

  if (this.includeBasic) {
    this.includeBasic.forEach(function(methodName) {
      this[methodName] = StripeResource.BASIC_METHODS[methodName];
    }, this);
  }

  this.initialize.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.StripeResource.extend"></a>[function <span class="apidocSignatureSpan">stripe.StripeResource.</span>extend (sub)](#apidoc.element.stripe.StripeResource.extend)
- description and source-code
```javascript
extend = function (sub) {
  var Super = this;
  var Constructor = hasOwn.call(sub, 'constructor') ? sub.constructor : function() {
    Super.apply(this, arguments);
  };
  Constructor.prototype = Object.create(Super.prototype);
  for (var i in sub) {
    if (hasOwn.call(sub, i)) {
      Constructor.prototype[i] = sub[i];
    }
  }
  for (i in Super) {
    if (hasOwn.call(Super, i)) {
      Constructor[i] = Super[i];
    }
  }
  return Constructor;
}
```
- example usage
```shell
...

_Error.extend = utils.protoExtend;

/**
 * Create subclass of internal Error klass
 * (Specifically for errors returned from Stripe's REST API)
 */
var StripeError = _Error.StripeError = _Error.extend({
  type: 'StripeError',
  populate: function(raw) {
// Move from prototype def (so it appears in stringified obj)
this.type = this.type;

this.stack = (new Error(raw.message)).stack;
this.rawType = raw.type;
...
```

#### <a name="apidoc.element.stripe.StripeResource.method"></a>[function <span class="apidocSignatureSpan">stripe.StripeResource.</span>method (spec)](#apidoc.element.stripe.StripeResource.method)
- description and source-code
```javascript
function stripeMethod(spec) {
  var commandPath = typeof spec.path == 'function' ? spec.path
                  : utils.makeURLInterpolator(spec.path || '');
  var requestMethod = (spec.method || 'GET').toUpperCase();
  var urlParams = spec.urlParams || [];
  var encode = spec.encode || function(data) {return data;};

  return function() {
    var self = this;
    var args = [].slice.call(arguments);

    var callback = typeof args[args.length - 1] == 'function' && args.pop();
    var urlData = this.createUrlData();

    return this.wrapTimeout(new Promise((function(resolve, reject) {
      for (var i = 0, l = urlParams.length; i < l; ++i) {
        // Note that we shift the args array after every iteration so this just
        // grabs the "next" argument for use as a URL parameter.
        var arg = args[0];

        var param = urlParams[i];

        var isOptional = OPTIONAL_REGEX.test(param);
        param = param.replace(OPTIONAL_REGEX, '');

        if (!arg) {
          if (isOptional) {
            urlData[param] = '';
            continue;
          }

          var err = new Error(
            'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
            ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
          );
          reject(err);
          return;
        }

        urlData[param] = args.shift();
      }

      var data = encode(utils.getDataFromArgs(args));
      var opts = utils.getOptionsFromArgs(args);

      if (args.length) {
        var err = new Error(
          'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
          'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      var requestPath = this.createFullPath(commandPath, urlData);
      function requestCallback(err, response) {
        if (err) {
          reject(err);
        } else {
          resolve(
            spec.transformResponseData ?
              spec.transformResponseData(response) :
              response
          );
        }
      };

      var options = {headers: objectAssign(opts.headers, spec.headers)};
      self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
    }).bind(this)), callback);
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.StripeResource.BASIC_METHODS"></a>[module stripe.StripeResource.BASIC_METHODS](#apidoc.module.stripe.StripeResource.BASIC_METHODS)

#### <a name="apidoc.element.stripe.StripeResource.BASIC_METHODS.create"></a>[function <span class="apidocSignatureSpan">stripe.StripeResource.BASIC_METHODS.</span>create ()](#apidoc.element.stripe.StripeResource.BASIC_METHODS.create)
- description and source-code
```javascript
create = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
...
The package needs to be configured with your account's secret key which is
available in your [Stripe Dashboard][api-keys]. Require it with the key's
value:

''' js
var stripe = require('stripe')('sk_test_...');

stripe.customers.create(
  { email: 'customer@example.com' },
  function(err, customer) {
    err; // null if no error occurred
    customer; // the created customer object
  }
);
'''
...
```

#### <a name="apidoc.element.stripe.StripeResource.BASIC_METHODS.del"></a>[function <span class="apidocSignatureSpan">stripe.StripeResource.BASIC_METHODS.</span>del ()](#apidoc.element.stripe.StripeResource.BASIC_METHODS.del)
- description and source-code
```javascript
del = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.StripeResource.BASIC_METHODS.getMetadata"></a>[function <span class="apidocSignatureSpan">stripe.StripeResource.BASIC_METHODS.</span>getMetadata (id, auth, cb)](#apidoc.element.stripe.StripeResource.BASIC_METHODS.getMetadata)
- description and source-code
```javascript
getMetadata = function (id, auth, cb) {
  if (!cb && typeof auth == 'function') {
    cb = auth;
    auth = null;
  }

  var urlData = this.createUrlData();
  var path = this.createFullPath('/' + id, urlData);

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    this._request('GET', path, {}, auth, {}, function(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(response.metadata);
      }
    });
  }).bind(this)), cb);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.StripeResource.BASIC_METHODS.list"></a>[function <span class="apidocSignatureSpan">stripe.StripeResource.BASIC_METHODS.</span>list ()](#apidoc.element.stripe.StripeResource.BASIC_METHODS.list)
- description and source-code
```javascript
list = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.StripeResource.BASIC_METHODS.retrieve"></a>[function <span class="apidocSignatureSpan">stripe.StripeResource.BASIC_METHODS.</span>retrieve ()](#apidoc.element.stripe.StripeResource.BASIC_METHODS.retrieve)
- description and source-code
```javascript
retrieve = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
...
### Configuring For Connect

A per-request 'Stripe-Account' header for use with [Stripe Connect][connect]
can be added to any method:

''' js
// Retrieve the balance for a connected account:
stripe.balance.retrieve({
  stripe_account: "acct_foo"
}).then(function(balance) {
  // The balance object for the connected account
}).catch(function(err) {
  // Error
});
'''
...
```

#### <a name="apidoc.element.stripe.StripeResource.BASIC_METHODS.setMetadata"></a>[function <span class="apidocSignatureSpan">stripe.StripeResource.BASIC_METHODS.</span>setMetadata (id, key, value, auth, cb)](#apidoc.element.stripe.StripeResource.BASIC_METHODS.setMetadata)
- description and source-code
```javascript
setMetadata = function (id, key, value, auth, cb) {
  var self = this;
  var data = key;
  var isObject = isPlainObject(key);
  // We assume null for an empty object
  var isNull = data === null || (isObject && !Object.keys(data).length);

  // Allow optional passing of auth & cb:
  if ((isNull || isObject) && typeof value == 'string') {
    auth = value;
  } else if (typeof auth != 'string') {
    if (!cb && typeof auth == 'function') {
      cb = auth;
    }
    auth = null;
  }

  var urlData = this.createUrlData();
  var path = this.createFullPath('/' + id, urlData);

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    if (isNull) {
      // Reset metadata:
      sendMetadata(null, auth);
    } else if (!isObject) {
      // Set individual metadata property:
      var metadata = {};
      metadata[key] = value;
      sendMetadata(metadata, auth);
    } else {
      // Set entire metadata object after resetting it:
      this._request('POST', path, {
        metadata: null,
      }, auth, {}, function(err, response) {
        if (err) {
          return reject(err);
        }
        sendMetadata(data, auth);
      });
    }

    function sendMetadata(metadata, auth) {
      self._request('POST', path, {
        metadata: metadata,
      }, auth, {}, function(err, response) {
        if (err) {
          reject(err);
        } else {
          resolve(response.metadata);
        }
      });
    }
  }).bind(this)), cb);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.StripeResource.BASIC_METHODS.update"></a>[function <span class="apidocSignatureSpan">stripe.StripeResource.BASIC_METHODS.</span>update ()](#apidoc.element.stripe.StripeResource.BASIC_METHODS.update)
- description and source-code
```javascript
update = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.StripeResource.prototype"></a>[module stripe.StripeResource.prototype](#apidoc.module.stripe.StripeResource.prototype)

#### <a name="apidoc.element.stripe.StripeResource.prototype._errorHandler"></a>[function <span class="apidocSignatureSpan">stripe.StripeResource.prototype.</span>_errorHandler (req, callback)](#apidoc.element.stripe.StripeResource.prototype._errorHandler)
- description and source-code
```javascript
_errorHandler = function (req, callback) {
  var self = this;
  return function(error) {
    if (req._isAborted) {
      // already handled
      return;
    }
    callback.call(
      self,
      new Error.StripeConnectionError({
        message: 'An error occurred with our connection to Stripe',
        detail: error,
      }),
      null
    );
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.StripeResource.prototype._request"></a>[function <span class="apidocSignatureSpan">stripe.StripeResource.prototype.</span>_request (method, path, data, auth, options, callback)](#apidoc.element.stripe.StripeResource.prototype._request)
- description and source-code
```javascript
_request = function (method, path, data, auth, options, callback) {
  var self = this;
  var requestData;

  if (self.requestDataProcessor) {
    requestData = self.requestDataProcessor(method, data, options.headers);
  } else {
    requestData = utils.stringifyRequestData(data || {});
  }

  var apiVersion = this._stripe.getApiField('version');

  var headers = {
    // Use specified auth token or use default from this stripe instance:
    'Authorization': auth ?
      'Basic ' + new Buffer(auth + ':').toString('base64') :
      this._stripe.getApiField('auth'),
    'Accept': 'application/json',
    'Content-Type': 'application/x-www-form-urlencoded',
    'Content-Length': requestData.length,
    'User-Agent': 'Stripe/v1 NodeBindings/' + this._stripe.getConstant('PACKAGE_VERSION'),
  };

  if (apiVersion) {
    headers['Stripe-Version'] = apiVersion;
  }

  // Grab client-user-agent before making the request:
  this._stripe.getClientUserAgent(function(cua) {
    headers['X-Stripe-Client-User-Agent'] = cua;

    if (options.headers) {
      objectAssign(headers, options.headers);
    }

    makeRequest();
  });

  function makeRequest() {
    var timeout = self._stripe.getApiField('timeout');
    var isInsecureConnection = self._stripe.getApiField('protocol') == 'http';

    var host = self.overrideHost || self._stripe.getApiField('host');

    var req = (
      isInsecureConnection ? http : https
    ).request({
      host: host,
      port: self._stripe.getApiField('port'),
      path: path,
      method: method,
      agent: self._stripe.getApiField('agent'),
      headers: headers,
      ciphers: 'DEFAULT:!aNULL:!eNULL:!LOW:!EXPORT:!SSLv2:!MD5',
    });

    req.setTimeout(timeout, self._timeoutHandler(timeout, req, callback));
    req.on('response', self._responseHandler(req, callback));
    req.on('error', self._errorHandler(req, callback));

    req.on('socket', function(socket) {
      socket.on((isInsecureConnection ? 'connect' : 'secureConnect'), function() {
        // Send payload; we're safe:
        req.write(requestData);
        req.end();
      });
    });
  }
}
```
- example usage
```shell
...
              spec.transformResponseData(response) :
              response
          );
        }
      };

      var options = {headers: objectAssign(opts.headers, spec.headers)};
      self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
    }).bind(this)), callback);
  };
};

module.exports = stripeMethod;
...
```

#### <a name="apidoc.element.stripe.StripeResource.prototype._responseHandler"></a>[function <span class="apidocSignatureSpan">stripe.StripeResource.prototype.</span>_responseHandler (req, callback)](#apidoc.element.stripe.StripeResource.prototype._responseHandler)
- description and source-code
```javascript
_responseHandler = function (req, callback) {
  var self = this;
  return function(res) {
    var response = '';

    res.setEncoding('utf8');
    res.on('data', function(chunk) {
      response += chunk;
    });
    res.on('end', function() {
      var headers = res.headers || {};

      try {
        response = JSON.parse(response);

        // For convenience, make Request-Id easily accessible on
        // lastResponse.
        res.requestId = headers['request-id'];

        if (response.error) {
          var err;

          // These are now available on the top-level resource's
          // lastResponse, but we keep them here too for backwards
          // compatibility.
          response.error.statusCode = res.statusCode;
          response.error.requestId = res.requestId;

          if (res.statusCode === 401) {
            err = new Error.StripeAuthenticationError(response.error);
          } else if (res.statusCode === 403) {
            err = new Error.StripePermissionError(response.error);
          } else if (res.statusCode === 429) {
            err = new Error.StripeRateLimitError(response.error);
          } else {
            err = Error.StripeError.generate(response.error);
          }
          return callback.call(self, err, null);
        }
      } catch (e) {
        return callback.call(
          self,
          new Error.StripeAPIError({
            message: 'Invalid JSON received from the Stripe API',
            response: response,
            exception: e,
            requestId: headers['request-id'],
          }),
          null
        );
      }
      // Expose res object
      Object.defineProperty(response, 'lastResponse', {
        enumerable: false,
        writable: false,
        value: res,
      });
      callback.call(self, null, response);
    });
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.StripeResource.prototype._timeoutHandler"></a>[function <span class="apidocSignatureSpan">stripe.StripeResource.prototype.</span>_timeoutHandler (timeout, req, callback)](#apidoc.element.stripe.StripeResource.prototype._timeoutHandler)
- description and source-code
```javascript
_timeoutHandler = function (timeout, req, callback) {
  var self = this;
  return function() {
    var timeoutErr = new Error('ETIMEDOUT');
    timeoutErr.code = 'ETIMEDOUT';

    req._isAborted = true;
    req.abort();

    callback.call(
      self,
      new Error.StripeConnectionError({
        message: 'Request aborted due to timeout being reached (' + timeout + 'ms)',
        detail: timeoutErr,
      }),
      null
    );
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.StripeResource.prototype.createFullPath"></a>[function <span class="apidocSignatureSpan">stripe.StripeResource.prototype.</span>createFullPath (commandPath, urlData)](#apidoc.element.stripe.StripeResource.prototype.createFullPath)
- description and source-code
```javascript
createFullPath = function (commandPath, urlData) {
  return path.join(
    this.basePath(urlData),
    this.path(urlData),
    typeof commandPath == 'function' ?
      commandPath(urlData) : commandPath
  ).replace(/\\/g, '/'); // ugly workaround for Windows
}
```
- example usage
```shell
...
    'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
    ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
  );
  reject(err);
  return;
}

var requestPath = this.createFullPath(commandPath, urlData);
function requestCallback(err, response) {
  if (err) {
    reject(err);
  } else {
    resolve(
      spec.transformResponseData ?
        spec.transformResponseData(response) :
...
```

#### <a name="apidoc.element.stripe.StripeResource.prototype.createUrlData"></a>[function <span class="apidocSignatureSpan">stripe.StripeResource.prototype.</span>createUrlData ()](#apidoc.element.stripe.StripeResource.prototype.createUrlData)
- description and source-code
```javascript
createUrlData = function () {
  var urlData = {};
  // Merge in baseData
  for (var i in this._urlData) {
    if (hasOwn.call(this._urlData, i)) {
      urlData[i] = this._urlData[i];
    }
  }
  return urlData;
}
```
- example usage
```shell
...
  var encode = spec.encode || function(data) {return data;};

  return function() {
var self = this;
var args = [].slice.call(arguments);

var callback = typeof args[args.length - 1] == 'function' && args.pop();
var urlData = this.createUrlData();

return this.wrapTimeout(new Promise((function(resolve, reject) {
  for (var i = 0, l = urlParams.length; i < l; ++i) {
    // Note that we shift the args array after every iteration so this just
    // grabs the "next" argument for use as a URL parameter.
    var arg = args[0];
...
```

#### <a name="apidoc.element.stripe.StripeResource.prototype.initialize"></a>[function <span class="apidocSignatureSpan">stripe.StripeResource.prototype.</span>initialize ()](#apidoc.element.stripe.StripeResource.prototype.initialize)
- description and source-code
```javascript
initialize = function () {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.StripeResource.prototype.wrapTimeout"></a>[function <span class="apidocSignatureSpan">stripe.StripeResource.prototype.</span>wrapTimeout (promise, callback)](#apidoc.element.stripe.StripeResource.prototype.wrapTimeout)
- description and source-code
```javascript
wrapTimeout = function (promise, callback) {
  if (callback) {
    // Ensure callback is called outside of promise stack.
    return promise.then(function(res) {
      setTimeout(function() { callback(null, res) }, 0);
    }, function(err) {
      setTimeout(function() { callback(err, null); }, 0);
    });
  }

  return promise;
}
```
- example usage
```shell
...
  return function() {
    var self = this;
    var args = [].slice.call(arguments);

    var callback = typeof args[args.length - 1] == 'function' && args.pop();
    var urlData = this.createUrlData();

    return this.wrapTimeout(new Promise((function(resolve, reject) {
      for (var i = 0, l = urlParams.length; i < l; ++i) {
// Note that we shift the args array after every iteration so this just
// grabs the "next" argument for use as a URL parameter.
var arg = args[0];

var param = urlParams[i];
...
```



# <a name="apidoc.module.stripe.resources"></a>[module stripe.resources](#apidoc.module.stripe.resources)

#### <a name="apidoc.element.stripe.resources.Account"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Account ()](#apidoc.element.stripe.resources.Account)
- description and source-code
```javascript
Account = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Accounts"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Accounts ()](#apidoc.element.stripe.resources.Accounts)
- description and source-code
```javascript
Accounts = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.ApplePayDomains"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>ApplePayDomains ()](#apidoc.element.stripe.resources.ApplePayDomains)
- description and source-code
```javascript
ApplePayDomains = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.ApplicationFeeRefunds"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>ApplicationFeeRefunds ()](#apidoc.element.stripe.resources.ApplicationFeeRefunds)
- description and source-code
```javascript
ApplicationFeeRefunds = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.ApplicationFees"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>ApplicationFees ()](#apidoc.element.stripe.resources.ApplicationFees)
- description and source-code
```javascript
ApplicationFees = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Balance"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Balance ()](#apidoc.element.stripe.resources.Balance)
- description and source-code
```javascript
Balance = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.BitcoinReceivers"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>BitcoinReceivers ()](#apidoc.element.stripe.resources.BitcoinReceivers)
- description and source-code
```javascript
BitcoinReceivers = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.ChargeRefunds"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>ChargeRefunds ()](#apidoc.element.stripe.resources.ChargeRefunds)
- description and source-code
```javascript
ChargeRefunds = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Charges"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Charges ()](#apidoc.element.stripe.resources.Charges)
- description and source-code
```javascript
Charges = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.CountrySpecs"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>CountrySpecs ()](#apidoc.element.stripe.resources.CountrySpecs)
- description and source-code
```javascript
CountrySpecs = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Coupons"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Coupons ()](#apidoc.element.stripe.resources.Coupons)
- description and source-code
```javascript
Coupons = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.CustomerCards"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>CustomerCards ()](#apidoc.element.stripe.resources.CustomerCards)
- description and source-code
```javascript
CustomerCards = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.CustomerSubscriptions"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>CustomerSubscriptions ()](#apidoc.element.stripe.resources.CustomerSubscriptions)
- description and source-code
```javascript
CustomerSubscriptions = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Customers"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Customers ()](#apidoc.element.stripe.resources.Customers)
- description and source-code
```javascript
Customers = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Disputes"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Disputes ()](#apidoc.element.stripe.resources.Disputes)
- description and source-code
```javascript
Disputes = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Events"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Events ()](#apidoc.element.stripe.resources.Events)
- description and source-code
```javascript
Events = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.FileUploads"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>FileUploads ()](#apidoc.element.stripe.resources.FileUploads)
- description and source-code
```javascript
FileUploads = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.InvoiceItems"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>InvoiceItems ()](#apidoc.element.stripe.resources.InvoiceItems)
- description and source-code
```javascript
InvoiceItems = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Invoices"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Invoices ()](#apidoc.element.stripe.resources.Invoices)
- description and source-code
```javascript
Invoices = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.OrderReturns"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>OrderReturns ()](#apidoc.element.stripe.resources.OrderReturns)
- description and source-code
```javascript
OrderReturns = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Orders"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Orders ()](#apidoc.element.stripe.resources.Orders)
- description and source-code
```javascript
Orders = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Payouts"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Payouts ()](#apidoc.element.stripe.resources.Payouts)
- description and source-code
```javascript
Payouts = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Plans"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Plans ()](#apidoc.element.stripe.resources.Plans)
- description and source-code
```javascript
Plans = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Products"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Products ()](#apidoc.element.stripe.resources.Products)
- description and source-code
```javascript
Products = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.RecipientCards"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>RecipientCards ()](#apidoc.element.stripe.resources.RecipientCards)
- description and source-code
```javascript
RecipientCards = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Recipients"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Recipients ()](#apidoc.element.stripe.resources.Recipients)
- description and source-code
```javascript
Recipients = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Refunds"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Refunds ()](#apidoc.element.stripe.resources.Refunds)
- description and source-code
```javascript
Refunds = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Skus"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Skus ()](#apidoc.element.stripe.resources.Skus)
- description and source-code
```javascript
Skus = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Sources"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Sources ()](#apidoc.element.stripe.resources.Sources)
- description and source-code
```javascript
Sources = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.SubscriptionItems"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>SubscriptionItems ()](#apidoc.element.stripe.resources.SubscriptionItems)
- description and source-code
```javascript
SubscriptionItems = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Subscriptions"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Subscriptions ()](#apidoc.element.stripe.resources.Subscriptions)
- description and source-code
```javascript
Subscriptions = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.ThreeDSecure"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>ThreeDSecure ()](#apidoc.element.stripe.resources.ThreeDSecure)
- description and source-code
```javascript
ThreeDSecure = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Tokens"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Tokens ()](#apidoc.element.stripe.resources.Tokens)
- description and source-code
```javascript
Tokens = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.TransferReversals"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>TransferReversals ()](#apidoc.element.stripe.resources.TransferReversals)
- description and source-code
```javascript
TransferReversals = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Transfers"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Transfers ()](#apidoc.element.stripe.resources.Transfers)
- description and source-code
```javascript
Transfers = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.Account"></a>[module stripe.resources.Account](#apidoc.module.stripe.resources.Account)

#### <a name="apidoc.element.stripe.resources.Account.Account"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Account ()](#apidoc.element.stripe.resources.Account.Account)
- description and source-code
```javascript
Account = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Account.extend"></a>[function <span class="apidocSignatureSpan">stripe.resources.Account.</span>extend (sub)](#apidoc.element.stripe.resources.Account.extend)
- description and source-code
```javascript
extend = function (sub) {
  var Super = this;
  var Constructor = hasOwn.call(sub, 'constructor') ? sub.constructor : function() {
    Super.apply(this, arguments);
  };
  Constructor.prototype = Object.create(Super.prototype);
  for (var i in sub) {
    if (hasOwn.call(sub, i)) {
      Constructor.prototype[i] = sub[i];
    }
  }
  for (i in Super) {
    if (hasOwn.call(Super, i)) {
      Constructor[i] = Super[i];
    }
  }
  return Constructor;
}
```
- example usage
```shell
...

_Error.extend = utils.protoExtend;

/**
 * Create subclass of internal Error klass
 * (Specifically for errors returned from Stripe's REST API)
 */
var StripeError = _Error.StripeError = _Error.extend({
  type: 'StripeError',
  populate: function(raw) {
// Move from prototype def (so it appears in stringified obj)
this.type = this.type;

this.stack = (new Error(raw.message)).stack;
this.rawType = raw.type;
...
```

#### <a name="apidoc.element.stripe.resources.Account.method"></a>[function <span class="apidocSignatureSpan">stripe.resources.Account.</span>method (spec)](#apidoc.element.stripe.resources.Account.method)
- description and source-code
```javascript
function stripeMethod(spec) {
  var commandPath = typeof spec.path == 'function' ? spec.path
                  : utils.makeURLInterpolator(spec.path || '');
  var requestMethod = (spec.method || 'GET').toUpperCase();
  var urlParams = spec.urlParams || [];
  var encode = spec.encode || function(data) {return data;};

  return function() {
    var self = this;
    var args = [].slice.call(arguments);

    var callback = typeof args[args.length - 1] == 'function' && args.pop();
    var urlData = this.createUrlData();

    return this.wrapTimeout(new Promise((function(resolve, reject) {
      for (var i = 0, l = urlParams.length; i < l; ++i) {
        // Note that we shift the args array after every iteration so this just
        // grabs the "next" argument for use as a URL parameter.
        var arg = args[0];

        var param = urlParams[i];

        var isOptional = OPTIONAL_REGEX.test(param);
        param = param.replace(OPTIONAL_REGEX, '');

        if (!arg) {
          if (isOptional) {
            urlData[param] = '';
            continue;
          }

          var err = new Error(
            'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
            ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
          );
          reject(err);
          return;
        }

        urlData[param] = args.shift();
      }

      var data = encode(utils.getDataFromArgs(args));
      var opts = utils.getOptionsFromArgs(args);

      if (args.length) {
        var err = new Error(
          'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
          'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      var requestPath = this.createFullPath(commandPath, urlData);
      function requestCallback(err, response) {
        if (err) {
          reject(err);
        } else {
          resolve(
            spec.transformResponseData ?
              spec.transformResponseData(response) :
              response
          );
        }
      };

      var options = {headers: objectAssign(opts.headers, spec.headers)};
      self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
    }).bind(this)), callback);
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.Account.prototype"></a>[module stripe.resources.Account.prototype](#apidoc.module.stripe.resources.Account.prototype)

#### <a name="apidoc.element.stripe.resources.Account.prototype.create"></a>[function <span class="apidocSignatureSpan">stripe.resources.Account.prototype.</span>create ()](#apidoc.element.stripe.resources.Account.prototype.create)
- description and source-code
```javascript
create = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
...
The package needs to be configured with your account's secret key which is
available in your [Stripe Dashboard][api-keys]. Require it with the key's
value:

''' js
var stripe = require('stripe')('sk_test_...');

stripe.customers.create(
  { email: 'customer@example.com' },
  function(err, customer) {
    err; // null if no error occurred
    customer; // the created customer object
  }
);
'''
...
```

#### <a name="apidoc.element.stripe.resources.Account.prototype.createExternalAccount"></a>[function <span class="apidocSignatureSpan">stripe.resources.Account.prototype.</span>createExternalAccount ()](#apidoc.element.stripe.resources.Account.prototype.createExternalAccount)
- description and source-code
```javascript
createExternalAccount = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Account.prototype.del"></a>[function <span class="apidocSignatureSpan">stripe.resources.Account.prototype.</span>del ()](#apidoc.element.stripe.resources.Account.prototype.del)
- description and source-code
```javascript
del = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Account.prototype.deleteExternalAccount"></a>[function <span class="apidocSignatureSpan">stripe.resources.Account.prototype.</span>deleteExternalAccount ()](#apidoc.element.stripe.resources.Account.prototype.deleteExternalAccount)
- description and source-code
```javascript
deleteExternalAccount = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Account.prototype.list"></a>[function <span class="apidocSignatureSpan">stripe.resources.Account.prototype.</span>list ()](#apidoc.element.stripe.resources.Account.prototype.list)
- description and source-code
```javascript
list = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Account.prototype.listExternalAccounts"></a>[function <span class="apidocSignatureSpan">stripe.resources.Account.prototype.</span>listExternalAccounts ()](#apidoc.element.stripe.resources.Account.prototype.listExternalAccounts)
- description and source-code
```javascript
listExternalAccounts = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Account.prototype.reject"></a>[function <span class="apidocSignatureSpan">stripe.resources.Account.prototype.</span>reject ()](#apidoc.element.stripe.resources.Account.prototype.reject)
- description and source-code
```javascript
reject = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Account.prototype.retrieve"></a>[function <span class="apidocSignatureSpan">stripe.resources.Account.prototype.</span>retrieve (id)](#apidoc.element.stripe.resources.Account.prototype.retrieve)
- description and source-code
```javascript
retrieve = function (id) {
  // No longer allow an api key to be passed as the first string to this function due to ambiguity between
  // old account ids and api keys. To request the account for an api key, send null as the id
  if (typeof id === 'string') {
    return stripeMethod({
      method: 'GET',
      path: 'accounts/{id}',
      urlParams: ['id'],
    }).apply(this, arguments);
  } else {
    if (id === null || id === undefined) {
      // Remove id as stripeMethod would complain of unexpected argument
      [].shift.apply(arguments);
    }
    return stripeMethod({
      method: 'GET',
      path: 'account',
    }).apply(this, arguments);
  }
}
```
- example usage
```shell
...
### Configuring For Connect

A per-request 'Stripe-Account' header for use with [Stripe Connect][connect]
can be added to any method:

''' js
// Retrieve the balance for a connected account:
stripe.balance.retrieve({
  stripe_account: "acct_foo"
}).then(function(balance) {
  // The balance object for the connected account
}).catch(function(err) {
  // Error
});
'''
...
```

#### <a name="apidoc.element.stripe.resources.Account.prototype.retrieveExternalAccount"></a>[function <span class="apidocSignatureSpan">stripe.resources.Account.prototype.</span>retrieveExternalAccount ()](#apidoc.element.stripe.resources.Account.prototype.retrieveExternalAccount)
- description and source-code
```javascript
retrieveExternalAccount = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Account.prototype.update"></a>[function <span class="apidocSignatureSpan">stripe.resources.Account.prototype.</span>update ()](#apidoc.element.stripe.resources.Account.prototype.update)
- description and source-code
```javascript
update = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Account.prototype.updateExternalAccount"></a>[function <span class="apidocSignatureSpan">stripe.resources.Account.prototype.</span>updateExternalAccount ()](#apidoc.element.stripe.resources.Account.prototype.updateExternalAccount)
- description and source-code
```javascript
updateExternalAccount = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.ApplePayDomains"></a>[module stripe.resources.ApplePayDomains](#apidoc.module.stripe.resources.ApplePayDomains)

#### <a name="apidoc.element.stripe.resources.ApplePayDomains.ApplePayDomains"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>ApplePayDomains ()](#apidoc.element.stripe.resources.ApplePayDomains.ApplePayDomains)
- description and source-code
```javascript
ApplePayDomains = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.ApplePayDomains.extend"></a>[function <span class="apidocSignatureSpan">stripe.resources.ApplePayDomains.</span>extend (sub)](#apidoc.element.stripe.resources.ApplePayDomains.extend)
- description and source-code
```javascript
extend = function (sub) {
  var Super = this;
  var Constructor = hasOwn.call(sub, 'constructor') ? sub.constructor : function() {
    Super.apply(this, arguments);
  };
  Constructor.prototype = Object.create(Super.prototype);
  for (var i in sub) {
    if (hasOwn.call(sub, i)) {
      Constructor.prototype[i] = sub[i];
    }
  }
  for (i in Super) {
    if (hasOwn.call(Super, i)) {
      Constructor[i] = Super[i];
    }
  }
  return Constructor;
}
```
- example usage
```shell
...

_Error.extend = utils.protoExtend;

/**
 * Create subclass of internal Error klass
 * (Specifically for errors returned from Stripe's REST API)
 */
var StripeError = _Error.StripeError = _Error.extend({
  type: 'StripeError',
  populate: function(raw) {
// Move from prototype def (so it appears in stringified obj)
this.type = this.type;

this.stack = (new Error(raw.message)).stack;
this.rawType = raw.type;
...
```

#### <a name="apidoc.element.stripe.resources.ApplePayDomains.method"></a>[function <span class="apidocSignatureSpan">stripe.resources.ApplePayDomains.</span>method (spec)](#apidoc.element.stripe.resources.ApplePayDomains.method)
- description and source-code
```javascript
function stripeMethod(spec) {
  var commandPath = typeof spec.path == 'function' ? spec.path
                  : utils.makeURLInterpolator(spec.path || '');
  var requestMethod = (spec.method || 'GET').toUpperCase();
  var urlParams = spec.urlParams || [];
  var encode = spec.encode || function(data) {return data;};

  return function() {
    var self = this;
    var args = [].slice.call(arguments);

    var callback = typeof args[args.length - 1] == 'function' && args.pop();
    var urlData = this.createUrlData();

    return this.wrapTimeout(new Promise((function(resolve, reject) {
      for (var i = 0, l = urlParams.length; i < l; ++i) {
        // Note that we shift the args array after every iteration so this just
        // grabs the "next" argument for use as a URL parameter.
        var arg = args[0];

        var param = urlParams[i];

        var isOptional = OPTIONAL_REGEX.test(param);
        param = param.replace(OPTIONAL_REGEX, '');

        if (!arg) {
          if (isOptional) {
            urlData[param] = '';
            continue;
          }

          var err = new Error(
            'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
            ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
          );
          reject(err);
          return;
        }

        urlData[param] = args.shift();
      }

      var data = encode(utils.getDataFromArgs(args));
      var opts = utils.getOptionsFromArgs(args);

      if (args.length) {
        var err = new Error(
          'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
          'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      var requestPath = this.createFullPath(commandPath, urlData);
      function requestCallback(err, response) {
        if (err) {
          reject(err);
        } else {
          resolve(
            spec.transformResponseData ?
              spec.transformResponseData(response) :
              response
          );
        }
      };

      var options = {headers: objectAssign(opts.headers, spec.headers)};
      self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
    }).bind(this)), callback);
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.ApplicationFeeRefunds"></a>[module stripe.resources.ApplicationFeeRefunds](#apidoc.module.stripe.resources.ApplicationFeeRefunds)

#### <a name="apidoc.element.stripe.resources.ApplicationFeeRefunds.ApplicationFeeRefunds"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>ApplicationFeeRefunds ()](#apidoc.element.stripe.resources.ApplicationFeeRefunds.ApplicationFeeRefunds)
- description and source-code
```javascript
ApplicationFeeRefunds = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.ApplicationFeeRefunds.extend"></a>[function <span class="apidocSignatureSpan">stripe.resources.ApplicationFeeRefunds.</span>extend (sub)](#apidoc.element.stripe.resources.ApplicationFeeRefunds.extend)
- description and source-code
```javascript
extend = function (sub) {
  var Super = this;
  var Constructor = hasOwn.call(sub, 'constructor') ? sub.constructor : function() {
    Super.apply(this, arguments);
  };
  Constructor.prototype = Object.create(Super.prototype);
  for (var i in sub) {
    if (hasOwn.call(sub, i)) {
      Constructor.prototype[i] = sub[i];
    }
  }
  for (i in Super) {
    if (hasOwn.call(Super, i)) {
      Constructor[i] = Super[i];
    }
  }
  return Constructor;
}
```
- example usage
```shell
...

_Error.extend = utils.protoExtend;

/**
 * Create subclass of internal Error klass
 * (Specifically for errors returned from Stripe's REST API)
 */
var StripeError = _Error.StripeError = _Error.extend({
  type: 'StripeError',
  populate: function(raw) {
// Move from prototype def (so it appears in stringified obj)
this.type = this.type;

this.stack = (new Error(raw.message)).stack;
this.rawType = raw.type;
...
```

#### <a name="apidoc.element.stripe.resources.ApplicationFeeRefunds.method"></a>[function <span class="apidocSignatureSpan">stripe.resources.ApplicationFeeRefunds.</span>method (spec)](#apidoc.element.stripe.resources.ApplicationFeeRefunds.method)
- description and source-code
```javascript
function stripeMethod(spec) {
  var commandPath = typeof spec.path == 'function' ? spec.path
                  : utils.makeURLInterpolator(spec.path || '');
  var requestMethod = (spec.method || 'GET').toUpperCase();
  var urlParams = spec.urlParams || [];
  var encode = spec.encode || function(data) {return data;};

  return function() {
    var self = this;
    var args = [].slice.call(arguments);

    var callback = typeof args[args.length - 1] == 'function' && args.pop();
    var urlData = this.createUrlData();

    return this.wrapTimeout(new Promise((function(resolve, reject) {
      for (var i = 0, l = urlParams.length; i < l; ++i) {
        // Note that we shift the args array after every iteration so this just
        // grabs the "next" argument for use as a URL parameter.
        var arg = args[0];

        var param = urlParams[i];

        var isOptional = OPTIONAL_REGEX.test(param);
        param = param.replace(OPTIONAL_REGEX, '');

        if (!arg) {
          if (isOptional) {
            urlData[param] = '';
            continue;
          }

          var err = new Error(
            'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
            ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
          );
          reject(err);
          return;
        }

        urlData[param] = args.shift();
      }

      var data = encode(utils.getDataFromArgs(args));
      var opts = utils.getOptionsFromArgs(args);

      if (args.length) {
        var err = new Error(
          'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
          'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      var requestPath = this.createFullPath(commandPath, urlData);
      function requestCallback(err, response) {
        if (err) {
          reject(err);
        } else {
          resolve(
            spec.transformResponseData ?
              spec.transformResponseData(response) :
              response
          );
        }
      };

      var options = {headers: objectAssign(opts.headers, spec.headers)};
      self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
    }).bind(this)), callback);
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.ApplicationFees"></a>[module stripe.resources.ApplicationFees](#apidoc.module.stripe.resources.ApplicationFees)

#### <a name="apidoc.element.stripe.resources.ApplicationFees.ApplicationFees"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>ApplicationFees ()](#apidoc.element.stripe.resources.ApplicationFees.ApplicationFees)
- description and source-code
```javascript
ApplicationFees = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.ApplicationFees.extend"></a>[function <span class="apidocSignatureSpan">stripe.resources.ApplicationFees.</span>extend (sub)](#apidoc.element.stripe.resources.ApplicationFees.extend)
- description and source-code
```javascript
extend = function (sub) {
  var Super = this;
  var Constructor = hasOwn.call(sub, 'constructor') ? sub.constructor : function() {
    Super.apply(this, arguments);
  };
  Constructor.prototype = Object.create(Super.prototype);
  for (var i in sub) {
    if (hasOwn.call(sub, i)) {
      Constructor.prototype[i] = sub[i];
    }
  }
  for (i in Super) {
    if (hasOwn.call(Super, i)) {
      Constructor[i] = Super[i];
    }
  }
  return Constructor;
}
```
- example usage
```shell
...

_Error.extend = utils.protoExtend;

/**
 * Create subclass of internal Error klass
 * (Specifically for errors returned from Stripe's REST API)
 */
var StripeError = _Error.StripeError = _Error.extend({
  type: 'StripeError',
  populate: function(raw) {
// Move from prototype def (so it appears in stringified obj)
this.type = this.type;

this.stack = (new Error(raw.message)).stack;
this.rawType = raw.type;
...
```

#### <a name="apidoc.element.stripe.resources.ApplicationFees.method"></a>[function <span class="apidocSignatureSpan">stripe.resources.ApplicationFees.</span>method (spec)](#apidoc.element.stripe.resources.ApplicationFees.method)
- description and source-code
```javascript
function stripeMethod(spec) {
  var commandPath = typeof spec.path == 'function' ? spec.path
                  : utils.makeURLInterpolator(spec.path || '');
  var requestMethod = (spec.method || 'GET').toUpperCase();
  var urlParams = spec.urlParams || [];
  var encode = spec.encode || function(data) {return data;};

  return function() {
    var self = this;
    var args = [].slice.call(arguments);

    var callback = typeof args[args.length - 1] == 'function' && args.pop();
    var urlData = this.createUrlData();

    return this.wrapTimeout(new Promise((function(resolve, reject) {
      for (var i = 0, l = urlParams.length; i < l; ++i) {
        // Note that we shift the args array after every iteration so this just
        // grabs the "next" argument for use as a URL parameter.
        var arg = args[0];

        var param = urlParams[i];

        var isOptional = OPTIONAL_REGEX.test(param);
        param = param.replace(OPTIONAL_REGEX, '');

        if (!arg) {
          if (isOptional) {
            urlData[param] = '';
            continue;
          }

          var err = new Error(
            'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
            ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
          );
          reject(err);
          return;
        }

        urlData[param] = args.shift();
      }

      var data = encode(utils.getDataFromArgs(args));
      var opts = utils.getOptionsFromArgs(args);

      if (args.length) {
        var err = new Error(
          'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
          'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      var requestPath = this.createFullPath(commandPath, urlData);
      function requestCallback(err, response) {
        if (err) {
          reject(err);
        } else {
          resolve(
            spec.transformResponseData ?
              spec.transformResponseData(response) :
              response
          );
        }
      };

      var options = {headers: objectAssign(opts.headers, spec.headers)};
      self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
    }).bind(this)), callback);
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.ApplicationFees.prototype"></a>[module stripe.resources.ApplicationFees.prototype](#apidoc.module.stripe.resources.ApplicationFees.prototype)

#### <a name="apidoc.element.stripe.resources.ApplicationFees.prototype.createRefund"></a>[function <span class="apidocSignatureSpan">stripe.resources.ApplicationFees.prototype.</span>createRefund ()](#apidoc.element.stripe.resources.ApplicationFees.prototype.createRefund)
- description and source-code
```javascript
createRefund = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.ApplicationFees.prototype.listRefunds"></a>[function <span class="apidocSignatureSpan">stripe.resources.ApplicationFees.prototype.</span>listRefunds ()](#apidoc.element.stripe.resources.ApplicationFees.prototype.listRefunds)
- description and source-code
```javascript
listRefunds = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.ApplicationFees.prototype.refund"></a>[function <span class="apidocSignatureSpan">stripe.resources.ApplicationFees.prototype.</span>refund ()](#apidoc.element.stripe.resources.ApplicationFees.prototype.refund)
- description and source-code
```javascript
refund = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.ApplicationFees.prototype.retrieveRefund"></a>[function <span class="apidocSignatureSpan">stripe.resources.ApplicationFees.prototype.</span>retrieveRefund ()](#apidoc.element.stripe.resources.ApplicationFees.prototype.retrieveRefund)
- description and source-code
```javascript
retrieveRefund = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.ApplicationFees.prototype.updateRefund"></a>[function <span class="apidocSignatureSpan">stripe.resources.ApplicationFees.prototype.</span>updateRefund ()](#apidoc.element.stripe.resources.ApplicationFees.prototype.updateRefund)
- description and source-code
```javascript
updateRefund = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.Balance"></a>[module stripe.resources.Balance](#apidoc.module.stripe.resources.Balance)

#### <a name="apidoc.element.stripe.resources.Balance.Balance"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Balance ()](#apidoc.element.stripe.resources.Balance.Balance)
- description and source-code
```javascript
Balance = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Balance.extend"></a>[function <span class="apidocSignatureSpan">stripe.resources.Balance.</span>extend (sub)](#apidoc.element.stripe.resources.Balance.extend)
- description and source-code
```javascript
extend = function (sub) {
  var Super = this;
  var Constructor = hasOwn.call(sub, 'constructor') ? sub.constructor : function() {
    Super.apply(this, arguments);
  };
  Constructor.prototype = Object.create(Super.prototype);
  for (var i in sub) {
    if (hasOwn.call(sub, i)) {
      Constructor.prototype[i] = sub[i];
    }
  }
  for (i in Super) {
    if (hasOwn.call(Super, i)) {
      Constructor[i] = Super[i];
    }
  }
  return Constructor;
}
```
- example usage
```shell
...

_Error.extend = utils.protoExtend;

/**
 * Create subclass of internal Error klass
 * (Specifically for errors returned from Stripe's REST API)
 */
var StripeError = _Error.StripeError = _Error.extend({
  type: 'StripeError',
  populate: function(raw) {
// Move from prototype def (so it appears in stringified obj)
this.type = this.type;

this.stack = (new Error(raw.message)).stack;
this.rawType = raw.type;
...
```

#### <a name="apidoc.element.stripe.resources.Balance.method"></a>[function <span class="apidocSignatureSpan">stripe.resources.Balance.</span>method (spec)](#apidoc.element.stripe.resources.Balance.method)
- description and source-code
```javascript
function stripeMethod(spec) {
  var commandPath = typeof spec.path == 'function' ? spec.path
                  : utils.makeURLInterpolator(spec.path || '');
  var requestMethod = (spec.method || 'GET').toUpperCase();
  var urlParams = spec.urlParams || [];
  var encode = spec.encode || function(data) {return data;};

  return function() {
    var self = this;
    var args = [].slice.call(arguments);

    var callback = typeof args[args.length - 1] == 'function' && args.pop();
    var urlData = this.createUrlData();

    return this.wrapTimeout(new Promise((function(resolve, reject) {
      for (var i = 0, l = urlParams.length; i < l; ++i) {
        // Note that we shift the args array after every iteration so this just
        // grabs the "next" argument for use as a URL parameter.
        var arg = args[0];

        var param = urlParams[i];

        var isOptional = OPTIONAL_REGEX.test(param);
        param = param.replace(OPTIONAL_REGEX, '');

        if (!arg) {
          if (isOptional) {
            urlData[param] = '';
            continue;
          }

          var err = new Error(
            'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
            ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
          );
          reject(err);
          return;
        }

        urlData[param] = args.shift();
      }

      var data = encode(utils.getDataFromArgs(args));
      var opts = utils.getOptionsFromArgs(args);

      if (args.length) {
        var err = new Error(
          'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
          'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      var requestPath = this.createFullPath(commandPath, urlData);
      function requestCallback(err, response) {
        if (err) {
          reject(err);
        } else {
          resolve(
            spec.transformResponseData ?
              spec.transformResponseData(response) :
              response
          );
        }
      };

      var options = {headers: objectAssign(opts.headers, spec.headers)};
      self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
    }).bind(this)), callback);
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.Balance.prototype"></a>[module stripe.resources.Balance.prototype](#apidoc.module.stripe.resources.Balance.prototype)

#### <a name="apidoc.element.stripe.resources.Balance.prototype.listTransactions"></a>[function <span class="apidocSignatureSpan">stripe.resources.Balance.prototype.</span>listTransactions ()](#apidoc.element.stripe.resources.Balance.prototype.listTransactions)
- description and source-code
```javascript
listTransactions = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Balance.prototype.retrieve"></a>[function <span class="apidocSignatureSpan">stripe.resources.Balance.prototype.</span>retrieve ()](#apidoc.element.stripe.resources.Balance.prototype.retrieve)
- description and source-code
```javascript
retrieve = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
...
### Configuring For Connect

A per-request 'Stripe-Account' header for use with [Stripe Connect][connect]
can be added to any method:

''' js
// Retrieve the balance for a connected account:
stripe.balance.retrieve({
  stripe_account: "acct_foo"
}).then(function(balance) {
  // The balance object for the connected account
}).catch(function(err) {
  // Error
});
'''
...
```

#### <a name="apidoc.element.stripe.resources.Balance.prototype.retrieveTransaction"></a>[function <span class="apidocSignatureSpan">stripe.resources.Balance.prototype.</span>retrieveTransaction ()](#apidoc.element.stripe.resources.Balance.prototype.retrieveTransaction)
- description and source-code
```javascript
retrieveTransaction = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.BitcoinReceivers"></a>[module stripe.resources.BitcoinReceivers](#apidoc.module.stripe.resources.BitcoinReceivers)

#### <a name="apidoc.element.stripe.resources.BitcoinReceivers.BitcoinReceivers"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>BitcoinReceivers ()](#apidoc.element.stripe.resources.BitcoinReceivers.BitcoinReceivers)
- description and source-code
```javascript
BitcoinReceivers = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.BitcoinReceivers.extend"></a>[function <span class="apidocSignatureSpan">stripe.resources.BitcoinReceivers.</span>extend (sub)](#apidoc.element.stripe.resources.BitcoinReceivers.extend)
- description and source-code
```javascript
extend = function (sub) {
  var Super = this;
  var Constructor = hasOwn.call(sub, 'constructor') ? sub.constructor : function() {
    Super.apply(this, arguments);
  };
  Constructor.prototype = Object.create(Super.prototype);
  for (var i in sub) {
    if (hasOwn.call(sub, i)) {
      Constructor.prototype[i] = sub[i];
    }
  }
  for (i in Super) {
    if (hasOwn.call(Super, i)) {
      Constructor[i] = Super[i];
    }
  }
  return Constructor;
}
```
- example usage
```shell
...

_Error.extend = utils.protoExtend;

/**
 * Create subclass of internal Error klass
 * (Specifically for errors returned from Stripe's REST API)
 */
var StripeError = _Error.StripeError = _Error.extend({
  type: 'StripeError',
  populate: function(raw) {
// Move from prototype def (so it appears in stringified obj)
this.type = this.type;

this.stack = (new Error(raw.message)).stack;
this.rawType = raw.type;
...
```

#### <a name="apidoc.element.stripe.resources.BitcoinReceivers.method"></a>[function <span class="apidocSignatureSpan">stripe.resources.BitcoinReceivers.</span>method (spec)](#apidoc.element.stripe.resources.BitcoinReceivers.method)
- description and source-code
```javascript
function stripeMethod(spec) {
  var commandPath = typeof spec.path == 'function' ? spec.path
                  : utils.makeURLInterpolator(spec.path || '');
  var requestMethod = (spec.method || 'GET').toUpperCase();
  var urlParams = spec.urlParams || [];
  var encode = spec.encode || function(data) {return data;};

  return function() {
    var self = this;
    var args = [].slice.call(arguments);

    var callback = typeof args[args.length - 1] == 'function' && args.pop();
    var urlData = this.createUrlData();

    return this.wrapTimeout(new Promise((function(resolve, reject) {
      for (var i = 0, l = urlParams.length; i < l; ++i) {
        // Note that we shift the args array after every iteration so this just
        // grabs the "next" argument for use as a URL parameter.
        var arg = args[0];

        var param = urlParams[i];

        var isOptional = OPTIONAL_REGEX.test(param);
        param = param.replace(OPTIONAL_REGEX, '');

        if (!arg) {
          if (isOptional) {
            urlData[param] = '';
            continue;
          }

          var err = new Error(
            'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
            ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
          );
          reject(err);
          return;
        }

        urlData[param] = args.shift();
      }

      var data = encode(utils.getDataFromArgs(args));
      var opts = utils.getOptionsFromArgs(args);

      if (args.length) {
        var err = new Error(
          'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
          'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      var requestPath = this.createFullPath(commandPath, urlData);
      function requestCallback(err, response) {
        if (err) {
          reject(err);
        } else {
          resolve(
            spec.transformResponseData ?
              spec.transformResponseData(response) :
              response
          );
        }
      };

      var options = {headers: objectAssign(opts.headers, spec.headers)};
      self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
    }).bind(this)), callback);
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.BitcoinReceivers.prototype"></a>[module stripe.resources.BitcoinReceivers.prototype](#apidoc.module.stripe.resources.BitcoinReceivers.prototype)

#### <a name="apidoc.element.stripe.resources.BitcoinReceivers.prototype.listTransactions"></a>[function <span class="apidocSignatureSpan">stripe.resources.BitcoinReceivers.prototype.</span>listTransactions ()](#apidoc.element.stripe.resources.BitcoinReceivers.prototype.listTransactions)
- description and source-code
```javascript
listTransactions = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.ChargeRefunds"></a>[module stripe.resources.ChargeRefunds](#apidoc.module.stripe.resources.ChargeRefunds)

#### <a name="apidoc.element.stripe.resources.ChargeRefunds.ChargeRefunds"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>ChargeRefunds ()](#apidoc.element.stripe.resources.ChargeRefunds.ChargeRefunds)
- description and source-code
```javascript
ChargeRefunds = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.ChargeRefunds.extend"></a>[function <span class="apidocSignatureSpan">stripe.resources.ChargeRefunds.</span>extend (sub)](#apidoc.element.stripe.resources.ChargeRefunds.extend)
- description and source-code
```javascript
extend = function (sub) {
  var Super = this;
  var Constructor = hasOwn.call(sub, 'constructor') ? sub.constructor : function() {
    Super.apply(this, arguments);
  };
  Constructor.prototype = Object.create(Super.prototype);
  for (var i in sub) {
    if (hasOwn.call(sub, i)) {
      Constructor.prototype[i] = sub[i];
    }
  }
  for (i in Super) {
    if (hasOwn.call(Super, i)) {
      Constructor[i] = Super[i];
    }
  }
  return Constructor;
}
```
- example usage
```shell
...

_Error.extend = utils.protoExtend;

/**
 * Create subclass of internal Error klass
 * (Specifically for errors returned from Stripe's REST API)
 */
var StripeError = _Error.StripeError = _Error.extend({
  type: 'StripeError',
  populate: function(raw) {
// Move from prototype def (so it appears in stringified obj)
this.type = this.type;

this.stack = (new Error(raw.message)).stack;
this.rawType = raw.type;
...
```

#### <a name="apidoc.element.stripe.resources.ChargeRefunds.method"></a>[function <span class="apidocSignatureSpan">stripe.resources.ChargeRefunds.</span>method (spec)](#apidoc.element.stripe.resources.ChargeRefunds.method)
- description and source-code
```javascript
function stripeMethod(spec) {
  var commandPath = typeof spec.path == 'function' ? spec.path
                  : utils.makeURLInterpolator(spec.path || '');
  var requestMethod = (spec.method || 'GET').toUpperCase();
  var urlParams = spec.urlParams || [];
  var encode = spec.encode || function(data) {return data;};

  return function() {
    var self = this;
    var args = [].slice.call(arguments);

    var callback = typeof args[args.length - 1] == 'function' && args.pop();
    var urlData = this.createUrlData();

    return this.wrapTimeout(new Promise((function(resolve, reject) {
      for (var i = 0, l = urlParams.length; i < l; ++i) {
        // Note that we shift the args array after every iteration so this just
        // grabs the "next" argument for use as a URL parameter.
        var arg = args[0];

        var param = urlParams[i];

        var isOptional = OPTIONAL_REGEX.test(param);
        param = param.replace(OPTIONAL_REGEX, '');

        if (!arg) {
          if (isOptional) {
            urlData[param] = '';
            continue;
          }

          var err = new Error(
            'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
            ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
          );
          reject(err);
          return;
        }

        urlData[param] = args.shift();
      }

      var data = encode(utils.getDataFromArgs(args));
      var opts = utils.getOptionsFromArgs(args);

      if (args.length) {
        var err = new Error(
          'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
          'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      var requestPath = this.createFullPath(commandPath, urlData);
      function requestCallback(err, response) {
        if (err) {
          reject(err);
        } else {
          resolve(
            spec.transformResponseData ?
              spec.transformResponseData(response) :
              response
          );
        }
      };

      var options = {headers: objectAssign(opts.headers, spec.headers)};
      self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
    }).bind(this)), callback);
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.Charges"></a>[module stripe.resources.Charges](#apidoc.module.stripe.resources.Charges)

#### <a name="apidoc.element.stripe.resources.Charges.Charges"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Charges ()](#apidoc.element.stripe.resources.Charges.Charges)
- description and source-code
```javascript
Charges = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Charges.extend"></a>[function <span class="apidocSignatureSpan">stripe.resources.Charges.</span>extend (sub)](#apidoc.element.stripe.resources.Charges.extend)
- description and source-code
```javascript
extend = function (sub) {
  var Super = this;
  var Constructor = hasOwn.call(sub, 'constructor') ? sub.constructor : function() {
    Super.apply(this, arguments);
  };
  Constructor.prototype = Object.create(Super.prototype);
  for (var i in sub) {
    if (hasOwn.call(sub, i)) {
      Constructor.prototype[i] = sub[i];
    }
  }
  for (i in Super) {
    if (hasOwn.call(Super, i)) {
      Constructor[i] = Super[i];
    }
  }
  return Constructor;
}
```
- example usage
```shell
...

_Error.extend = utils.protoExtend;

/**
 * Create subclass of internal Error klass
 * (Specifically for errors returned from Stripe's REST API)
 */
var StripeError = _Error.StripeError = _Error.extend({
  type: 'StripeError',
  populate: function(raw) {
// Move from prototype def (so it appears in stringified obj)
this.type = this.type;

this.stack = (new Error(raw.message)).stack;
this.rawType = raw.type;
...
```

#### <a name="apidoc.element.stripe.resources.Charges.method"></a>[function <span class="apidocSignatureSpan">stripe.resources.Charges.</span>method (spec)](#apidoc.element.stripe.resources.Charges.method)
- description and source-code
```javascript
function stripeMethod(spec) {
  var commandPath = typeof spec.path == 'function' ? spec.path
                  : utils.makeURLInterpolator(spec.path || '');
  var requestMethod = (spec.method || 'GET').toUpperCase();
  var urlParams = spec.urlParams || [];
  var encode = spec.encode || function(data) {return data;};

  return function() {
    var self = this;
    var args = [].slice.call(arguments);

    var callback = typeof args[args.length - 1] == 'function' && args.pop();
    var urlData = this.createUrlData();

    return this.wrapTimeout(new Promise((function(resolve, reject) {
      for (var i = 0, l = urlParams.length; i < l; ++i) {
        // Note that we shift the args array after every iteration so this just
        // grabs the "next" argument for use as a URL parameter.
        var arg = args[0];

        var param = urlParams[i];

        var isOptional = OPTIONAL_REGEX.test(param);
        param = param.replace(OPTIONAL_REGEX, '');

        if (!arg) {
          if (isOptional) {
            urlData[param] = '';
            continue;
          }

          var err = new Error(
            'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
            ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
          );
          reject(err);
          return;
        }

        urlData[param] = args.shift();
      }

      var data = encode(utils.getDataFromArgs(args));
      var opts = utils.getOptionsFromArgs(args);

      if (args.length) {
        var err = new Error(
          'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
          'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      var requestPath = this.createFullPath(commandPath, urlData);
      function requestCallback(err, response) {
        if (err) {
          reject(err);
        } else {
          resolve(
            spec.transformResponseData ?
              spec.transformResponseData(response) :
              response
          );
        }
      };

      var options = {headers: objectAssign(opts.headers, spec.headers)};
      self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
    }).bind(this)), callback);
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.Charges.prototype"></a>[module stripe.resources.Charges.prototype](#apidoc.module.stripe.resources.Charges.prototype)

#### <a name="apidoc.element.stripe.resources.Charges.prototype.capture"></a>[function <span class="apidocSignatureSpan">stripe.resources.Charges.prototype.</span>capture ()](#apidoc.element.stripe.resources.Charges.prototype.capture)
- description and source-code
```javascript
capture = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Charges.prototype.closeDispute"></a>[function <span class="apidocSignatureSpan">stripe.resources.Charges.prototype.</span>closeDispute ()](#apidoc.element.stripe.resources.Charges.prototype.closeDispute)
- description and source-code
```javascript
closeDispute = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Charges.prototype.createRefund"></a>[function <span class="apidocSignatureSpan">stripe.resources.Charges.prototype.</span>createRefund ()](#apidoc.element.stripe.resources.Charges.prototype.createRefund)
- description and source-code
```javascript
createRefund = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Charges.prototype.listRefunds"></a>[function <span class="apidocSignatureSpan">stripe.resources.Charges.prototype.</span>listRefunds ()](#apidoc.element.stripe.resources.Charges.prototype.listRefunds)
- description and source-code
```javascript
listRefunds = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Charges.prototype.markAsFraudulent"></a>[function <span class="apidocSignatureSpan">stripe.resources.Charges.prototype.</span>markAsFraudulent (chargeId)](#apidoc.element.stripe.resources.Charges.prototype.markAsFraudulent)
- description and source-code
```javascript
markAsFraudulent = function (chargeId) {
  return this.update(chargeId, {'fraud_details': {'user_report': 'fraudulent'}})
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Charges.prototype.markAsSafe"></a>[function <span class="apidocSignatureSpan">stripe.resources.Charges.prototype.</span>markAsSafe (chargeId)](#apidoc.element.stripe.resources.Charges.prototype.markAsSafe)
- description and source-code
```javascript
markAsSafe = function (chargeId) {
  return this.update(chargeId, {'fraud_details': {'user_report': 'safe'}})
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Charges.prototype.refund"></a>[function <span class="apidocSignatureSpan">stripe.resources.Charges.prototype.</span>refund ()](#apidoc.element.stripe.resources.Charges.prototype.refund)
- description and source-code
```javascript
refund = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Charges.prototype.retrieveRefund"></a>[function <span class="apidocSignatureSpan">stripe.resources.Charges.prototype.</span>retrieveRefund ()](#apidoc.element.stripe.resources.Charges.prototype.retrieveRefund)
- description and source-code
```javascript
retrieveRefund = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Charges.prototype.updateDispute"></a>[function <span class="apidocSignatureSpan">stripe.resources.Charges.prototype.</span>updateDispute ()](#apidoc.element.stripe.resources.Charges.prototype.updateDispute)
- description and source-code
```javascript
updateDispute = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Charges.prototype.updateRefund"></a>[function <span class="apidocSignatureSpan">stripe.resources.Charges.prototype.</span>updateRefund ()](#apidoc.element.stripe.resources.Charges.prototype.updateRefund)
- description and source-code
```javascript
updateRefund = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.CountrySpecs"></a>[module stripe.resources.CountrySpecs](#apidoc.module.stripe.resources.CountrySpecs)

#### <a name="apidoc.element.stripe.resources.CountrySpecs.CountrySpecs"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>CountrySpecs ()](#apidoc.element.stripe.resources.CountrySpecs.CountrySpecs)
- description and source-code
```javascript
CountrySpecs = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.CountrySpecs.extend"></a>[function <span class="apidocSignatureSpan">stripe.resources.CountrySpecs.</span>extend (sub)](#apidoc.element.stripe.resources.CountrySpecs.extend)
- description and source-code
```javascript
extend = function (sub) {
  var Super = this;
  var Constructor = hasOwn.call(sub, 'constructor') ? sub.constructor : function() {
    Super.apply(this, arguments);
  };
  Constructor.prototype = Object.create(Super.prototype);
  for (var i in sub) {
    if (hasOwn.call(sub, i)) {
      Constructor.prototype[i] = sub[i];
    }
  }
  for (i in Super) {
    if (hasOwn.call(Super, i)) {
      Constructor[i] = Super[i];
    }
  }
  return Constructor;
}
```
- example usage
```shell
...

_Error.extend = utils.protoExtend;

/**
 * Create subclass of internal Error klass
 * (Specifically for errors returned from Stripe's REST API)
 */
var StripeError = _Error.StripeError = _Error.extend({
  type: 'StripeError',
  populate: function(raw) {
// Move from prototype def (so it appears in stringified obj)
this.type = this.type;

this.stack = (new Error(raw.message)).stack;
this.rawType = raw.type;
...
```

#### <a name="apidoc.element.stripe.resources.CountrySpecs.method"></a>[function <span class="apidocSignatureSpan">stripe.resources.CountrySpecs.</span>method (spec)](#apidoc.element.stripe.resources.CountrySpecs.method)
- description and source-code
```javascript
function stripeMethod(spec) {
  var commandPath = typeof spec.path == 'function' ? spec.path
                  : utils.makeURLInterpolator(spec.path || '');
  var requestMethod = (spec.method || 'GET').toUpperCase();
  var urlParams = spec.urlParams || [];
  var encode = spec.encode || function(data) {return data;};

  return function() {
    var self = this;
    var args = [].slice.call(arguments);

    var callback = typeof args[args.length - 1] == 'function' && args.pop();
    var urlData = this.createUrlData();

    return this.wrapTimeout(new Promise((function(resolve, reject) {
      for (var i = 0, l = urlParams.length; i < l; ++i) {
        // Note that we shift the args array after every iteration so this just
        // grabs the "next" argument for use as a URL parameter.
        var arg = args[0];

        var param = urlParams[i];

        var isOptional = OPTIONAL_REGEX.test(param);
        param = param.replace(OPTIONAL_REGEX, '');

        if (!arg) {
          if (isOptional) {
            urlData[param] = '';
            continue;
          }

          var err = new Error(
            'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
            ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
          );
          reject(err);
          return;
        }

        urlData[param] = args.shift();
      }

      var data = encode(utils.getDataFromArgs(args));
      var opts = utils.getOptionsFromArgs(args);

      if (args.length) {
        var err = new Error(
          'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
          'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      var requestPath = this.createFullPath(commandPath, urlData);
      function requestCallback(err, response) {
        if (err) {
          reject(err);
        } else {
          resolve(
            spec.transformResponseData ?
              spec.transformResponseData(response) :
              response
          );
        }
      };

      var options = {headers: objectAssign(opts.headers, spec.headers)};
      self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
    }).bind(this)), callback);
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.Coupons"></a>[module stripe.resources.Coupons](#apidoc.module.stripe.resources.Coupons)

#### <a name="apidoc.element.stripe.resources.Coupons.Coupons"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Coupons ()](#apidoc.element.stripe.resources.Coupons.Coupons)
- description and source-code
```javascript
Coupons = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Coupons.extend"></a>[function <span class="apidocSignatureSpan">stripe.resources.Coupons.</span>extend (sub)](#apidoc.element.stripe.resources.Coupons.extend)
- description and source-code
```javascript
extend = function (sub) {
  var Super = this;
  var Constructor = hasOwn.call(sub, 'constructor') ? sub.constructor : function() {
    Super.apply(this, arguments);
  };
  Constructor.prototype = Object.create(Super.prototype);
  for (var i in sub) {
    if (hasOwn.call(sub, i)) {
      Constructor.prototype[i] = sub[i];
    }
  }
  for (i in Super) {
    if (hasOwn.call(Super, i)) {
      Constructor[i] = Super[i];
    }
  }
  return Constructor;
}
```
- example usage
```shell
...

_Error.extend = utils.protoExtend;

/**
 * Create subclass of internal Error klass
 * (Specifically for errors returned from Stripe's REST API)
 */
var StripeError = _Error.StripeError = _Error.extend({
  type: 'StripeError',
  populate: function(raw) {
// Move from prototype def (so it appears in stringified obj)
this.type = this.type;

this.stack = (new Error(raw.message)).stack;
this.rawType = raw.type;
...
```

#### <a name="apidoc.element.stripe.resources.Coupons.method"></a>[function <span class="apidocSignatureSpan">stripe.resources.Coupons.</span>method (spec)](#apidoc.element.stripe.resources.Coupons.method)
- description and source-code
```javascript
function stripeMethod(spec) {
  var commandPath = typeof spec.path == 'function' ? spec.path
                  : utils.makeURLInterpolator(spec.path || '');
  var requestMethod = (spec.method || 'GET').toUpperCase();
  var urlParams = spec.urlParams || [];
  var encode = spec.encode || function(data) {return data;};

  return function() {
    var self = this;
    var args = [].slice.call(arguments);

    var callback = typeof args[args.length - 1] == 'function' && args.pop();
    var urlData = this.createUrlData();

    return this.wrapTimeout(new Promise((function(resolve, reject) {
      for (var i = 0, l = urlParams.length; i < l; ++i) {
        // Note that we shift the args array after every iteration so this just
        // grabs the "next" argument for use as a URL parameter.
        var arg = args[0];

        var param = urlParams[i];

        var isOptional = OPTIONAL_REGEX.test(param);
        param = param.replace(OPTIONAL_REGEX, '');

        if (!arg) {
          if (isOptional) {
            urlData[param] = '';
            continue;
          }

          var err = new Error(
            'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
            ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
          );
          reject(err);
          return;
        }

        urlData[param] = args.shift();
      }

      var data = encode(utils.getDataFromArgs(args));
      var opts = utils.getOptionsFromArgs(args);

      if (args.length) {
        var err = new Error(
          'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
          'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      var requestPath = this.createFullPath(commandPath, urlData);
      function requestCallback(err, response) {
        if (err) {
          reject(err);
        } else {
          resolve(
            spec.transformResponseData ?
              spec.transformResponseData(response) :
              response
          );
        }
      };

      var options = {headers: objectAssign(opts.headers, spec.headers)};
      self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
    }).bind(this)), callback);
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.CustomerCards"></a>[module stripe.resources.CustomerCards](#apidoc.module.stripe.resources.CustomerCards)

#### <a name="apidoc.element.stripe.resources.CustomerCards.CustomerCards"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>CustomerCards ()](#apidoc.element.stripe.resources.CustomerCards.CustomerCards)
- description and source-code
```javascript
CustomerCards = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.CustomerCards.extend"></a>[function <span class="apidocSignatureSpan">stripe.resources.CustomerCards.</span>extend (sub)](#apidoc.element.stripe.resources.CustomerCards.extend)
- description and source-code
```javascript
extend = function (sub) {
  var Super = this;
  var Constructor = hasOwn.call(sub, 'constructor') ? sub.constructor : function() {
    Super.apply(this, arguments);
  };
  Constructor.prototype = Object.create(Super.prototype);
  for (var i in sub) {
    if (hasOwn.call(sub, i)) {
      Constructor.prototype[i] = sub[i];
    }
  }
  for (i in Super) {
    if (hasOwn.call(Super, i)) {
      Constructor[i] = Super[i];
    }
  }
  return Constructor;
}
```
- example usage
```shell
...

_Error.extend = utils.protoExtend;

/**
 * Create subclass of internal Error klass
 * (Specifically for errors returned from Stripe's REST API)
 */
var StripeError = _Error.StripeError = _Error.extend({
  type: 'StripeError',
  populate: function(raw) {
// Move from prototype def (so it appears in stringified obj)
this.type = this.type;

this.stack = (new Error(raw.message)).stack;
this.rawType = raw.type;
...
```

#### <a name="apidoc.element.stripe.resources.CustomerCards.method"></a>[function <span class="apidocSignatureSpan">stripe.resources.CustomerCards.</span>method (spec)](#apidoc.element.stripe.resources.CustomerCards.method)
- description and source-code
```javascript
function stripeMethod(spec) {
  var commandPath = typeof spec.path == 'function' ? spec.path
                  : utils.makeURLInterpolator(spec.path || '');
  var requestMethod = (spec.method || 'GET').toUpperCase();
  var urlParams = spec.urlParams || [];
  var encode = spec.encode || function(data) {return data;};

  return function() {
    var self = this;
    var args = [].slice.call(arguments);

    var callback = typeof args[args.length - 1] == 'function' && args.pop();
    var urlData = this.createUrlData();

    return this.wrapTimeout(new Promise((function(resolve, reject) {
      for (var i = 0, l = urlParams.length; i < l; ++i) {
        // Note that we shift the args array after every iteration so this just
        // grabs the "next" argument for use as a URL parameter.
        var arg = args[0];

        var param = urlParams[i];

        var isOptional = OPTIONAL_REGEX.test(param);
        param = param.replace(OPTIONAL_REGEX, '');

        if (!arg) {
          if (isOptional) {
            urlData[param] = '';
            continue;
          }

          var err = new Error(
            'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
            ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
          );
          reject(err);
          return;
        }

        urlData[param] = args.shift();
      }

      var data = encode(utils.getDataFromArgs(args));
      var opts = utils.getOptionsFromArgs(args);

      if (args.length) {
        var err = new Error(
          'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
          'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      var requestPath = this.createFullPath(commandPath, urlData);
      function requestCallback(err, response) {
        if (err) {
          reject(err);
        } else {
          resolve(
            spec.transformResponseData ?
              spec.transformResponseData(response) :
              response
          );
        }
      };

      var options = {headers: objectAssign(opts.headers, spec.headers)};
      self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
    }).bind(this)), callback);
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.CustomerSubscriptions"></a>[module stripe.resources.CustomerSubscriptions](#apidoc.module.stripe.resources.CustomerSubscriptions)

#### <a name="apidoc.element.stripe.resources.CustomerSubscriptions.CustomerSubscriptions"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>CustomerSubscriptions ()](#apidoc.element.stripe.resources.CustomerSubscriptions.CustomerSubscriptions)
- description and source-code
```javascript
CustomerSubscriptions = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.CustomerSubscriptions.extend"></a>[function <span class="apidocSignatureSpan">stripe.resources.CustomerSubscriptions.</span>extend (sub)](#apidoc.element.stripe.resources.CustomerSubscriptions.extend)
- description and source-code
```javascript
extend = function (sub) {
  var Super = this;
  var Constructor = hasOwn.call(sub, 'constructor') ? sub.constructor : function() {
    Super.apply(this, arguments);
  };
  Constructor.prototype = Object.create(Super.prototype);
  for (var i in sub) {
    if (hasOwn.call(sub, i)) {
      Constructor.prototype[i] = sub[i];
    }
  }
  for (i in Super) {
    if (hasOwn.call(Super, i)) {
      Constructor[i] = Super[i];
    }
  }
  return Constructor;
}
```
- example usage
```shell
...

_Error.extend = utils.protoExtend;

/**
 * Create subclass of internal Error klass
 * (Specifically for errors returned from Stripe's REST API)
 */
var StripeError = _Error.StripeError = _Error.extend({
  type: 'StripeError',
  populate: function(raw) {
// Move from prototype def (so it appears in stringified obj)
this.type = this.type;

this.stack = (new Error(raw.message)).stack;
this.rawType = raw.type;
...
```

#### <a name="apidoc.element.stripe.resources.CustomerSubscriptions.method"></a>[function <span class="apidocSignatureSpan">stripe.resources.CustomerSubscriptions.</span>method (spec)](#apidoc.element.stripe.resources.CustomerSubscriptions.method)
- description and source-code
```javascript
function stripeMethod(spec) {
  var commandPath = typeof spec.path == 'function' ? spec.path
                  : utils.makeURLInterpolator(spec.path || '');
  var requestMethod = (spec.method || 'GET').toUpperCase();
  var urlParams = spec.urlParams || [];
  var encode = spec.encode || function(data) {return data;};

  return function() {
    var self = this;
    var args = [].slice.call(arguments);

    var callback = typeof args[args.length - 1] == 'function' && args.pop();
    var urlData = this.createUrlData();

    return this.wrapTimeout(new Promise((function(resolve, reject) {
      for (var i = 0, l = urlParams.length; i < l; ++i) {
        // Note that we shift the args array after every iteration so this just
        // grabs the "next" argument for use as a URL parameter.
        var arg = args[0];

        var param = urlParams[i];

        var isOptional = OPTIONAL_REGEX.test(param);
        param = param.replace(OPTIONAL_REGEX, '');

        if (!arg) {
          if (isOptional) {
            urlData[param] = '';
            continue;
          }

          var err = new Error(
            'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
            ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
          );
          reject(err);
          return;
        }

        urlData[param] = args.shift();
      }

      var data = encode(utils.getDataFromArgs(args));
      var opts = utils.getOptionsFromArgs(args);

      if (args.length) {
        var err = new Error(
          'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
          'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      var requestPath = this.createFullPath(commandPath, urlData);
      function requestCallback(err, response) {
        if (err) {
          reject(err);
        } else {
          resolve(
            spec.transformResponseData ?
              spec.transformResponseData(response) :
              response
          );
        }
      };

      var options = {headers: objectAssign(opts.headers, spec.headers)};
      self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
    }).bind(this)), callback);
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.CustomerSubscriptions.prototype"></a>[module stripe.resources.CustomerSubscriptions.prototype](#apidoc.module.stripe.resources.CustomerSubscriptions.prototype)

#### <a name="apidoc.element.stripe.resources.CustomerSubscriptions.prototype.deleteDiscount"></a>[function <span class="apidocSignatureSpan">stripe.resources.CustomerSubscriptions.prototype.</span>deleteDiscount ()](#apidoc.element.stripe.resources.CustomerSubscriptions.prototype.deleteDiscount)
- description and source-code
```javascript
deleteDiscount = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.Customers"></a>[module stripe.resources.Customers](#apidoc.module.stripe.resources.Customers)

#### <a name="apidoc.element.stripe.resources.Customers.Customers"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Customers ()](#apidoc.element.stripe.resources.Customers.Customers)
- description and source-code
```javascript
Customers = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Customers.extend"></a>[function <span class="apidocSignatureSpan">stripe.resources.Customers.</span>extend (sub)](#apidoc.element.stripe.resources.Customers.extend)
- description and source-code
```javascript
extend = function (sub) {
  var Super = this;
  var Constructor = hasOwn.call(sub, 'constructor') ? sub.constructor : function() {
    Super.apply(this, arguments);
  };
  Constructor.prototype = Object.create(Super.prototype);
  for (var i in sub) {
    if (hasOwn.call(sub, i)) {
      Constructor.prototype[i] = sub[i];
    }
  }
  for (i in Super) {
    if (hasOwn.call(Super, i)) {
      Constructor[i] = Super[i];
    }
  }
  return Constructor;
}
```
- example usage
```shell
...

_Error.extend = utils.protoExtend;

/**
 * Create subclass of internal Error klass
 * (Specifically for errors returned from Stripe's REST API)
 */
var StripeError = _Error.StripeError = _Error.extend({
  type: 'StripeError',
  populate: function(raw) {
// Move from prototype def (so it appears in stringified obj)
this.type = this.type;

this.stack = (new Error(raw.message)).stack;
this.rawType = raw.type;
...
```

#### <a name="apidoc.element.stripe.resources.Customers.method"></a>[function <span class="apidocSignatureSpan">stripe.resources.Customers.</span>method (spec)](#apidoc.element.stripe.resources.Customers.method)
- description and source-code
```javascript
function stripeMethod(spec) {
  var commandPath = typeof spec.path == 'function' ? spec.path
                  : utils.makeURLInterpolator(spec.path || '');
  var requestMethod = (spec.method || 'GET').toUpperCase();
  var urlParams = spec.urlParams || [];
  var encode = spec.encode || function(data) {return data;};

  return function() {
    var self = this;
    var args = [].slice.call(arguments);

    var callback = typeof args[args.length - 1] == 'function' && args.pop();
    var urlData = this.createUrlData();

    return this.wrapTimeout(new Promise((function(resolve, reject) {
      for (var i = 0, l = urlParams.length; i < l; ++i) {
        // Note that we shift the args array after every iteration so this just
        // grabs the "next" argument for use as a URL parameter.
        var arg = args[0];

        var param = urlParams[i];

        var isOptional = OPTIONAL_REGEX.test(param);
        param = param.replace(OPTIONAL_REGEX, '');

        if (!arg) {
          if (isOptional) {
            urlData[param] = '';
            continue;
          }

          var err = new Error(
            'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
            ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
          );
          reject(err);
          return;
        }

        urlData[param] = args.shift();
      }

      var data = encode(utils.getDataFromArgs(args));
      var opts = utils.getOptionsFromArgs(args);

      if (args.length) {
        var err = new Error(
          'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
          'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      var requestPath = this.createFullPath(commandPath, urlData);
      function requestCallback(err, response) {
        if (err) {
          reject(err);
        } else {
          resolve(
            spec.transformResponseData ?
              spec.transformResponseData(response) :
              response
          );
        }
      };

      var options = {headers: objectAssign(opts.headers, spec.headers)};
      self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
    }).bind(this)), callback);
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.Customers.prototype"></a>[module stripe.resources.Customers.prototype](#apidoc.module.stripe.resources.Customers.prototype)

#### <a name="apidoc.element.stripe.resources.Customers.prototype._legacyCancelSubscription"></a>[function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>_legacyCancelSubscription ()](#apidoc.element.stripe.resources.Customers.prototype._legacyCancelSubscription)
- description and source-code
```javascript
_legacyCancelSubscription = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Customers.prototype._legacyUpdateSubscription"></a>[function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>_legacyUpdateSubscription ()](#apidoc.element.stripe.resources.Customers.prototype._legacyUpdateSubscription)
- description and source-code
```javascript
_legacyUpdateSubscription = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Customers.prototype._newstyleCancelSubscription"></a>[function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>_newstyleCancelSubscription ()](#apidoc.element.stripe.resources.Customers.prototype._newstyleCancelSubscription)
- description and source-code
```javascript
_newstyleCancelSubscription = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Customers.prototype._newstyleUpdateSubscription"></a>[function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>_newstyleUpdateSubscription ()](#apidoc.element.stripe.resources.Customers.prototype._newstyleUpdateSubscription)
- description and source-code
```javascript
_newstyleUpdateSubscription = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Customers.prototype.cancelSubscription"></a>[function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>cancelSubscription (customerId, subscriptionId)](#apidoc.element.stripe.resources.Customers.prototype.cancelSubscription)
- description and source-code
```javascript
cancelSubscription = function (customerId, subscriptionId) {
  // This is a hack, but it lets us maximize our overloading.
  // Precarious assumption: If it's not an auth key it _could_ be a sub id:
  if (typeof subscriptionId == 'string' && !utils.isAuthKey(subscriptionId)) {
    return this._newstyleCancelSubscription.apply(this, arguments);
  } else {
    return this._legacyCancelSubscription.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Customers.prototype.createCard"></a>[function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>createCard ()](#apidoc.element.stripe.resources.Customers.prototype.createCard)
- description and source-code
```javascript
createCard = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Customers.prototype.createSource"></a>[function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>createSource ()](#apidoc.element.stripe.resources.Customers.prototype.createSource)
- description and source-code
```javascript
createSource = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
...
callback:

''' js
// Create a new customer and then a new charge for that customer:
stripe.customers.create({
email: 'foo-customer@example.com'
}).then(function(customer){
return stripe.customers.createSource(customer.id, {
  source: {
     object: 'card',
     exp_month: 10,
     exp_year: 2018,
     number: '4242 4242 4242 4242',
     cvc: 100
  }
...
```

#### <a name="apidoc.element.stripe.resources.Customers.prototype.createSubscription"></a>[function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>createSubscription ()](#apidoc.element.stripe.resources.Customers.prototype.createSubscription)
- description and source-code
```javascript
createSubscription = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Customers.prototype.deleteCard"></a>[function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>deleteCard ()](#apidoc.element.stripe.resources.Customers.prototype.deleteCard)
- description and source-code
```javascript
deleteCard = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Customers.prototype.deleteDiscount"></a>[function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>deleteDiscount ()](#apidoc.element.stripe.resources.Customers.prototype.deleteDiscount)
- description and source-code
```javascript
deleteDiscount = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Customers.prototype.deleteSource"></a>[function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>deleteSource ()](#apidoc.element.stripe.resources.Customers.prototype.deleteSource)
- description and source-code
```javascript
deleteSource = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Customers.prototype.deleteSubscriptionDiscount"></a>[function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>deleteSubscriptionDiscount ()](#apidoc.element.stripe.resources.Customers.prototype.deleteSubscriptionDiscount)
- description and source-code
```javascript
deleteSubscriptionDiscount = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Customers.prototype.listCards"></a>[function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>listCards ()](#apidoc.element.stripe.resources.Customers.prototype.listCards)
- description and source-code
```javascript
listCards = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Customers.prototype.listSources"></a>[function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>listSources ()](#apidoc.element.stripe.resources.Customers.prototype.listSources)
- description and source-code
```javascript
listSources = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Customers.prototype.listSubscriptions"></a>[function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>listSubscriptions ()](#apidoc.element.stripe.resources.Customers.prototype.listSubscriptions)
- description and source-code
```javascript
listSubscriptions = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Customers.prototype.retrieveCard"></a>[function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>retrieveCard ()](#apidoc.element.stripe.resources.Customers.prototype.retrieveCard)
- description and source-code
```javascript
retrieveCard = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Customers.prototype.retrieveSource"></a>[function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>retrieveSource ()](#apidoc.element.stripe.resources.Customers.prototype.retrieveSource)
- description and source-code
```javascript
retrieveSource = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Customers.prototype.retrieveSubscription"></a>[function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>retrieveSubscription ()](#apidoc.element.stripe.resources.Customers.prototype.retrieveSubscription)
- description and source-code
```javascript
retrieveSubscription = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Customers.prototype.updateCard"></a>[function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>updateCard ()](#apidoc.element.stripe.resources.Customers.prototype.updateCard)
- description and source-code
```javascript
updateCard = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Customers.prototype.updateSource"></a>[function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>updateSource ()](#apidoc.element.stripe.resources.Customers.prototype.updateSource)
- description and source-code
```javascript
updateSource = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Customers.prototype.updateSubscription"></a>[function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>updateSubscription (customerId, subscriptionId)](#apidoc.element.stripe.resources.Customers.prototype.updateSubscription)
- description and source-code
```javascript
updateSubscription = function (customerId, subscriptionId) {
  if (typeof subscriptionId == 'string') {
    return this._newstyleUpdateSubscription.apply(this, arguments);
  } else {
    return this._legacyUpdateSubscription.apply(this, arguments);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Customers.prototype.verifySource"></a>[function <span class="apidocSignatureSpan">stripe.resources.Customers.prototype.</span>verifySource ()](#apidoc.element.stripe.resources.Customers.prototype.verifySource)
- description and source-code
```javascript
verifySource = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.Disputes"></a>[module stripe.resources.Disputes](#apidoc.module.stripe.resources.Disputes)

#### <a name="apidoc.element.stripe.resources.Disputes.Disputes"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Disputes ()](#apidoc.element.stripe.resources.Disputes.Disputes)
- description and source-code
```javascript
Disputes = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Disputes.extend"></a>[function <span class="apidocSignatureSpan">stripe.resources.Disputes.</span>extend (sub)](#apidoc.element.stripe.resources.Disputes.extend)
- description and source-code
```javascript
extend = function (sub) {
  var Super = this;
  var Constructor = hasOwn.call(sub, 'constructor') ? sub.constructor : function() {
    Super.apply(this, arguments);
  };
  Constructor.prototype = Object.create(Super.prototype);
  for (var i in sub) {
    if (hasOwn.call(sub, i)) {
      Constructor.prototype[i] = sub[i];
    }
  }
  for (i in Super) {
    if (hasOwn.call(Super, i)) {
      Constructor[i] = Super[i];
    }
  }
  return Constructor;
}
```
- example usage
```shell
...

_Error.extend = utils.protoExtend;

/**
 * Create subclass of internal Error klass
 * (Specifically for errors returned from Stripe's REST API)
 */
var StripeError = _Error.StripeError = _Error.extend({
  type: 'StripeError',
  populate: function(raw) {
// Move from prototype def (so it appears in stringified obj)
this.type = this.type;

this.stack = (new Error(raw.message)).stack;
this.rawType = raw.type;
...
```

#### <a name="apidoc.element.stripe.resources.Disputes.method"></a>[function <span class="apidocSignatureSpan">stripe.resources.Disputes.</span>method (spec)](#apidoc.element.stripe.resources.Disputes.method)
- description and source-code
```javascript
function stripeMethod(spec) {
  var commandPath = typeof spec.path == 'function' ? spec.path
                  : utils.makeURLInterpolator(spec.path || '');
  var requestMethod = (spec.method || 'GET').toUpperCase();
  var urlParams = spec.urlParams || [];
  var encode = spec.encode || function(data) {return data;};

  return function() {
    var self = this;
    var args = [].slice.call(arguments);

    var callback = typeof args[args.length - 1] == 'function' && args.pop();
    var urlData = this.createUrlData();

    return this.wrapTimeout(new Promise((function(resolve, reject) {
      for (var i = 0, l = urlParams.length; i < l; ++i) {
        // Note that we shift the args array after every iteration so this just
        // grabs the "next" argument for use as a URL parameter.
        var arg = args[0];

        var param = urlParams[i];

        var isOptional = OPTIONAL_REGEX.test(param);
        param = param.replace(OPTIONAL_REGEX, '');

        if (!arg) {
          if (isOptional) {
            urlData[param] = '';
            continue;
          }

          var err = new Error(
            'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
            ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
          );
          reject(err);
          return;
        }

        urlData[param] = args.shift();
      }

      var data = encode(utils.getDataFromArgs(args));
      var opts = utils.getOptionsFromArgs(args);

      if (args.length) {
        var err = new Error(
          'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
          'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      var requestPath = this.createFullPath(commandPath, urlData);
      function requestCallback(err, response) {
        if (err) {
          reject(err);
        } else {
          resolve(
            spec.transformResponseData ?
              spec.transformResponseData(response) :
              response
          );
        }
      };

      var options = {headers: objectAssign(opts.headers, spec.headers)};
      self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
    }).bind(this)), callback);
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.Disputes.prototype"></a>[module stripe.resources.Disputes.prototype](#apidoc.module.stripe.resources.Disputes.prototype)

#### <a name="apidoc.element.stripe.resources.Disputes.prototype.close"></a>[function <span class="apidocSignatureSpan">stripe.resources.Disputes.prototype.</span>close ()](#apidoc.element.stripe.resources.Disputes.prototype.close)
- description and source-code
```javascript
close = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.Events"></a>[module stripe.resources.Events](#apidoc.module.stripe.resources.Events)

#### <a name="apidoc.element.stripe.resources.Events.Events"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Events ()](#apidoc.element.stripe.resources.Events.Events)
- description and source-code
```javascript
Events = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Events.extend"></a>[function <span class="apidocSignatureSpan">stripe.resources.Events.</span>extend (sub)](#apidoc.element.stripe.resources.Events.extend)
- description and source-code
```javascript
extend = function (sub) {
  var Super = this;
  var Constructor = hasOwn.call(sub, 'constructor') ? sub.constructor : function() {
    Super.apply(this, arguments);
  };
  Constructor.prototype = Object.create(Super.prototype);
  for (var i in sub) {
    if (hasOwn.call(sub, i)) {
      Constructor.prototype[i] = sub[i];
    }
  }
  for (i in Super) {
    if (hasOwn.call(Super, i)) {
      Constructor[i] = Super[i];
    }
  }
  return Constructor;
}
```
- example usage
```shell
...

_Error.extend = utils.protoExtend;

/**
 * Create subclass of internal Error klass
 * (Specifically for errors returned from Stripe's REST API)
 */
var StripeError = _Error.StripeError = _Error.extend({
  type: 'StripeError',
  populate: function(raw) {
// Move from prototype def (so it appears in stringified obj)
this.type = this.type;

this.stack = (new Error(raw.message)).stack;
this.rawType = raw.type;
...
```

#### <a name="apidoc.element.stripe.resources.Events.method"></a>[function <span class="apidocSignatureSpan">stripe.resources.Events.</span>method (spec)](#apidoc.element.stripe.resources.Events.method)
- description and source-code
```javascript
function stripeMethod(spec) {
  var commandPath = typeof spec.path == 'function' ? spec.path
                  : utils.makeURLInterpolator(spec.path || '');
  var requestMethod = (spec.method || 'GET').toUpperCase();
  var urlParams = spec.urlParams || [];
  var encode = spec.encode || function(data) {return data;};

  return function() {
    var self = this;
    var args = [].slice.call(arguments);

    var callback = typeof args[args.length - 1] == 'function' && args.pop();
    var urlData = this.createUrlData();

    return this.wrapTimeout(new Promise((function(resolve, reject) {
      for (var i = 0, l = urlParams.length; i < l; ++i) {
        // Note that we shift the args array after every iteration so this just
        // grabs the "next" argument for use as a URL parameter.
        var arg = args[0];

        var param = urlParams[i];

        var isOptional = OPTIONAL_REGEX.test(param);
        param = param.replace(OPTIONAL_REGEX, '');

        if (!arg) {
          if (isOptional) {
            urlData[param] = '';
            continue;
          }

          var err = new Error(
            'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
            ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
          );
          reject(err);
          return;
        }

        urlData[param] = args.shift();
      }

      var data = encode(utils.getDataFromArgs(args));
      var opts = utils.getOptionsFromArgs(args);

      if (args.length) {
        var err = new Error(
          'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
          'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      var requestPath = this.createFullPath(commandPath, urlData);
      function requestCallback(err, response) {
        if (err) {
          reject(err);
        } else {
          resolve(
            spec.transformResponseData ?
              spec.transformResponseData(response) :
              response
          );
        }
      };

      var options = {headers: objectAssign(opts.headers, spec.headers)};
      self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
    }).bind(this)), callback);
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.FileUploads"></a>[module stripe.resources.FileUploads](#apidoc.module.stripe.resources.FileUploads)

#### <a name="apidoc.element.stripe.resources.FileUploads.FileUploads"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>FileUploads ()](#apidoc.element.stripe.resources.FileUploads.FileUploads)
- description and source-code
```javascript
FileUploads = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.FileUploads.extend"></a>[function <span class="apidocSignatureSpan">stripe.resources.FileUploads.</span>extend (sub)](#apidoc.element.stripe.resources.FileUploads.extend)
- description and source-code
```javascript
extend = function (sub) {
  var Super = this;
  var Constructor = hasOwn.call(sub, 'constructor') ? sub.constructor : function() {
    Super.apply(this, arguments);
  };
  Constructor.prototype = Object.create(Super.prototype);
  for (var i in sub) {
    if (hasOwn.call(sub, i)) {
      Constructor.prototype[i] = sub[i];
    }
  }
  for (i in Super) {
    if (hasOwn.call(Super, i)) {
      Constructor[i] = Super[i];
    }
  }
  return Constructor;
}
```
- example usage
```shell
...

_Error.extend = utils.protoExtend;

/**
 * Create subclass of internal Error klass
 * (Specifically for errors returned from Stripe's REST API)
 */
var StripeError = _Error.StripeError = _Error.extend({
  type: 'StripeError',
  populate: function(raw) {
// Move from prototype def (so it appears in stringified obj)
this.type = this.type;

this.stack = (new Error(raw.message)).stack;
this.rawType = raw.type;
...
```

#### <a name="apidoc.element.stripe.resources.FileUploads.method"></a>[function <span class="apidocSignatureSpan">stripe.resources.FileUploads.</span>method (spec)](#apidoc.element.stripe.resources.FileUploads.method)
- description and source-code
```javascript
function stripeMethod(spec) {
  var commandPath = typeof spec.path == 'function' ? spec.path
                  : utils.makeURLInterpolator(spec.path || '');
  var requestMethod = (spec.method || 'GET').toUpperCase();
  var urlParams = spec.urlParams || [];
  var encode = spec.encode || function(data) {return data;};

  return function() {
    var self = this;
    var args = [].slice.call(arguments);

    var callback = typeof args[args.length - 1] == 'function' && args.pop();
    var urlData = this.createUrlData();

    return this.wrapTimeout(new Promise((function(resolve, reject) {
      for (var i = 0, l = urlParams.length; i < l; ++i) {
        // Note that we shift the args array after every iteration so this just
        // grabs the "next" argument for use as a URL parameter.
        var arg = args[0];

        var param = urlParams[i];

        var isOptional = OPTIONAL_REGEX.test(param);
        param = param.replace(OPTIONAL_REGEX, '');

        if (!arg) {
          if (isOptional) {
            urlData[param] = '';
            continue;
          }

          var err = new Error(
            'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
            ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
          );
          reject(err);
          return;
        }

        urlData[param] = args.shift();
      }

      var data = encode(utils.getDataFromArgs(args));
      var opts = utils.getOptionsFromArgs(args);

      if (args.length) {
        var err = new Error(
          'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
          'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      var requestPath = this.createFullPath(commandPath, urlData);
      function requestCallback(err, response) {
        if (err) {
          reject(err);
        } else {
          resolve(
            spec.transformResponseData ?
              spec.transformResponseData(response) :
              response
          );
        }
      };

      var options = {headers: objectAssign(opts.headers, spec.headers)};
      self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
    }).bind(this)), callback);
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.FileUploads.prototype"></a>[module stripe.resources.FileUploads.prototype](#apidoc.module.stripe.resources.FileUploads.prototype)

#### <a name="apidoc.element.stripe.resources.FileUploads.prototype.create"></a>[function <span class="apidocSignatureSpan">stripe.resources.FileUploads.prototype.</span>create ()](#apidoc.element.stripe.resources.FileUploads.prototype.create)
- description and source-code
```javascript
create = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
...
The package needs to be configured with your account's secret key which is
available in your [Stripe Dashboard][api-keys]. Require it with the key's
value:

''' js
var stripe = require('stripe')('sk_test_...');

stripe.customers.create(
  { email: 'customer@example.com' },
  function(err, customer) {
    err; // null if no error occurred
    customer; // the created customer object
  }
);
'''
...
```

#### <a name="apidoc.element.stripe.resources.FileUploads.prototype.requestDataProcessor"></a>[function <span class="apidocSignatureSpan">stripe.resources.FileUploads.prototype.</span>requestDataProcessor (method, data, headers)](#apidoc.element.stripe.resources.FileUploads.prototype.requestDataProcessor)
- description and source-code
```javascript
requestDataProcessor = function (method, data, headers) {
  data = data || {};

  if (method === 'POST') {
    return multipartDataGenerator(method, data, headers);
  } else {
    return utils.stringifyRequestData(data);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.InvoiceItems"></a>[module stripe.resources.InvoiceItems](#apidoc.module.stripe.resources.InvoiceItems)

#### <a name="apidoc.element.stripe.resources.InvoiceItems.InvoiceItems"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>InvoiceItems ()](#apidoc.element.stripe.resources.InvoiceItems.InvoiceItems)
- description and source-code
```javascript
InvoiceItems = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.InvoiceItems.extend"></a>[function <span class="apidocSignatureSpan">stripe.resources.InvoiceItems.</span>extend (sub)](#apidoc.element.stripe.resources.InvoiceItems.extend)
- description and source-code
```javascript
extend = function (sub) {
  var Super = this;
  var Constructor = hasOwn.call(sub, 'constructor') ? sub.constructor : function() {
    Super.apply(this, arguments);
  };
  Constructor.prototype = Object.create(Super.prototype);
  for (var i in sub) {
    if (hasOwn.call(sub, i)) {
      Constructor.prototype[i] = sub[i];
    }
  }
  for (i in Super) {
    if (hasOwn.call(Super, i)) {
      Constructor[i] = Super[i];
    }
  }
  return Constructor;
}
```
- example usage
```shell
...

_Error.extend = utils.protoExtend;

/**
 * Create subclass of internal Error klass
 * (Specifically for errors returned from Stripe's REST API)
 */
var StripeError = _Error.StripeError = _Error.extend({
  type: 'StripeError',
  populate: function(raw) {
// Move from prototype def (so it appears in stringified obj)
this.type = this.type;

this.stack = (new Error(raw.message)).stack;
this.rawType = raw.type;
...
```

#### <a name="apidoc.element.stripe.resources.InvoiceItems.method"></a>[function <span class="apidocSignatureSpan">stripe.resources.InvoiceItems.</span>method (spec)](#apidoc.element.stripe.resources.InvoiceItems.method)
- description and source-code
```javascript
function stripeMethod(spec) {
  var commandPath = typeof spec.path == 'function' ? spec.path
                  : utils.makeURLInterpolator(spec.path || '');
  var requestMethod = (spec.method || 'GET').toUpperCase();
  var urlParams = spec.urlParams || [];
  var encode = spec.encode || function(data) {return data;};

  return function() {
    var self = this;
    var args = [].slice.call(arguments);

    var callback = typeof args[args.length - 1] == 'function' && args.pop();
    var urlData = this.createUrlData();

    return this.wrapTimeout(new Promise((function(resolve, reject) {
      for (var i = 0, l = urlParams.length; i < l; ++i) {
        // Note that we shift the args array after every iteration so this just
        // grabs the "next" argument for use as a URL parameter.
        var arg = args[0];

        var param = urlParams[i];

        var isOptional = OPTIONAL_REGEX.test(param);
        param = param.replace(OPTIONAL_REGEX, '');

        if (!arg) {
          if (isOptional) {
            urlData[param] = '';
            continue;
          }

          var err = new Error(
            'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
            ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
          );
          reject(err);
          return;
        }

        urlData[param] = args.shift();
      }

      var data = encode(utils.getDataFromArgs(args));
      var opts = utils.getOptionsFromArgs(args);

      if (args.length) {
        var err = new Error(
          'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
          'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      var requestPath = this.createFullPath(commandPath, urlData);
      function requestCallback(err, response) {
        if (err) {
          reject(err);
        } else {
          resolve(
            spec.transformResponseData ?
              spec.transformResponseData(response) :
              response
          );
        }
      };

      var options = {headers: objectAssign(opts.headers, spec.headers)};
      self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
    }).bind(this)), callback);
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.Invoices"></a>[module stripe.resources.Invoices](#apidoc.module.stripe.resources.Invoices)

#### <a name="apidoc.element.stripe.resources.Invoices.Invoices"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Invoices ()](#apidoc.element.stripe.resources.Invoices.Invoices)
- description and source-code
```javascript
Invoices = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Invoices.extend"></a>[function <span class="apidocSignatureSpan">stripe.resources.Invoices.</span>extend (sub)](#apidoc.element.stripe.resources.Invoices.extend)
- description and source-code
```javascript
extend = function (sub) {
  var Super = this;
  var Constructor = hasOwn.call(sub, 'constructor') ? sub.constructor : function() {
    Super.apply(this, arguments);
  };
  Constructor.prototype = Object.create(Super.prototype);
  for (var i in sub) {
    if (hasOwn.call(sub, i)) {
      Constructor.prototype[i] = sub[i];
    }
  }
  for (i in Super) {
    if (hasOwn.call(Super, i)) {
      Constructor[i] = Super[i];
    }
  }
  return Constructor;
}
```
- example usage
```shell
...

_Error.extend = utils.protoExtend;

/**
 * Create subclass of internal Error klass
 * (Specifically for errors returned from Stripe's REST API)
 */
var StripeError = _Error.StripeError = _Error.extend({
  type: 'StripeError',
  populate: function(raw) {
// Move from prototype def (so it appears in stringified obj)
this.type = this.type;

this.stack = (new Error(raw.message)).stack;
this.rawType = raw.type;
...
```

#### <a name="apidoc.element.stripe.resources.Invoices.method"></a>[function <span class="apidocSignatureSpan">stripe.resources.Invoices.</span>method (spec)](#apidoc.element.stripe.resources.Invoices.method)
- description and source-code
```javascript
function stripeMethod(spec) {
  var commandPath = typeof spec.path == 'function' ? spec.path
                  : utils.makeURLInterpolator(spec.path || '');
  var requestMethod = (spec.method || 'GET').toUpperCase();
  var urlParams = spec.urlParams || [];
  var encode = spec.encode || function(data) {return data;};

  return function() {
    var self = this;
    var args = [].slice.call(arguments);

    var callback = typeof args[args.length - 1] == 'function' && args.pop();
    var urlData = this.createUrlData();

    return this.wrapTimeout(new Promise((function(resolve, reject) {
      for (var i = 0, l = urlParams.length; i < l; ++i) {
        // Note that we shift the args array after every iteration so this just
        // grabs the "next" argument for use as a URL parameter.
        var arg = args[0];

        var param = urlParams[i];

        var isOptional = OPTIONAL_REGEX.test(param);
        param = param.replace(OPTIONAL_REGEX, '');

        if (!arg) {
          if (isOptional) {
            urlData[param] = '';
            continue;
          }

          var err = new Error(
            'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
            ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
          );
          reject(err);
          return;
        }

        urlData[param] = args.shift();
      }

      var data = encode(utils.getDataFromArgs(args));
      var opts = utils.getOptionsFromArgs(args);

      if (args.length) {
        var err = new Error(
          'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
          'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      var requestPath = this.createFullPath(commandPath, urlData);
      function requestCallback(err, response) {
        if (err) {
          reject(err);
        } else {
          resolve(
            spec.transformResponseData ?
              spec.transformResponseData(response) :
              response
          );
        }
      };

      var options = {headers: objectAssign(opts.headers, spec.headers)};
      self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
    }).bind(this)), callback);
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.Invoices.prototype"></a>[module stripe.resources.Invoices.prototype](#apidoc.module.stripe.resources.Invoices.prototype)

#### <a name="apidoc.element.stripe.resources.Invoices.prototype.pay"></a>[function <span class="apidocSignatureSpan">stripe.resources.Invoices.prototype.</span>pay ()](#apidoc.element.stripe.resources.Invoices.prototype.pay)
- description and source-code
```javascript
pay = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Invoices.prototype.retrieveLines"></a>[function <span class="apidocSignatureSpan">stripe.resources.Invoices.prototype.</span>retrieveLines ()](#apidoc.element.stripe.resources.Invoices.prototype.retrieveLines)
- description and source-code
```javascript
retrieveLines = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Invoices.prototype.retrieveUpcoming"></a>[function <span class="apidocSignatureSpan">stripe.resources.Invoices.prototype.</span>retrieveUpcoming ()](#apidoc.element.stripe.resources.Invoices.prototype.retrieveUpcoming)
- description and source-code
```javascript
retrieveUpcoming = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.OrderReturns"></a>[module stripe.resources.OrderReturns](#apidoc.module.stripe.resources.OrderReturns)

#### <a name="apidoc.element.stripe.resources.OrderReturns.OrderReturns"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>OrderReturns ()](#apidoc.element.stripe.resources.OrderReturns.OrderReturns)
- description and source-code
```javascript
OrderReturns = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.OrderReturns.extend"></a>[function <span class="apidocSignatureSpan">stripe.resources.OrderReturns.</span>extend (sub)](#apidoc.element.stripe.resources.OrderReturns.extend)
- description and source-code
```javascript
extend = function (sub) {
  var Super = this;
  var Constructor = hasOwn.call(sub, 'constructor') ? sub.constructor : function() {
    Super.apply(this, arguments);
  };
  Constructor.prototype = Object.create(Super.prototype);
  for (var i in sub) {
    if (hasOwn.call(sub, i)) {
      Constructor.prototype[i] = sub[i];
    }
  }
  for (i in Super) {
    if (hasOwn.call(Super, i)) {
      Constructor[i] = Super[i];
    }
  }
  return Constructor;
}
```
- example usage
```shell
...

_Error.extend = utils.protoExtend;

/**
 * Create subclass of internal Error klass
 * (Specifically for errors returned from Stripe's REST API)
 */
var StripeError = _Error.StripeError = _Error.extend({
  type: 'StripeError',
  populate: function(raw) {
// Move from prototype def (so it appears in stringified obj)
this.type = this.type;

this.stack = (new Error(raw.message)).stack;
this.rawType = raw.type;
...
```

#### <a name="apidoc.element.stripe.resources.OrderReturns.method"></a>[function <span class="apidocSignatureSpan">stripe.resources.OrderReturns.</span>method (spec)](#apidoc.element.stripe.resources.OrderReturns.method)
- description and source-code
```javascript
function stripeMethod(spec) {
  var commandPath = typeof spec.path == 'function' ? spec.path
                  : utils.makeURLInterpolator(spec.path || '');
  var requestMethod = (spec.method || 'GET').toUpperCase();
  var urlParams = spec.urlParams || [];
  var encode = spec.encode || function(data) {return data;};

  return function() {
    var self = this;
    var args = [].slice.call(arguments);

    var callback = typeof args[args.length - 1] == 'function' && args.pop();
    var urlData = this.createUrlData();

    return this.wrapTimeout(new Promise((function(resolve, reject) {
      for (var i = 0, l = urlParams.length; i < l; ++i) {
        // Note that we shift the args array after every iteration so this just
        // grabs the "next" argument for use as a URL parameter.
        var arg = args[0];

        var param = urlParams[i];

        var isOptional = OPTIONAL_REGEX.test(param);
        param = param.replace(OPTIONAL_REGEX, '');

        if (!arg) {
          if (isOptional) {
            urlData[param] = '';
            continue;
          }

          var err = new Error(
            'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
            ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
          );
          reject(err);
          return;
        }

        urlData[param] = args.shift();
      }

      var data = encode(utils.getDataFromArgs(args));
      var opts = utils.getOptionsFromArgs(args);

      if (args.length) {
        var err = new Error(
          'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
          'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      var requestPath = this.createFullPath(commandPath, urlData);
      function requestCallback(err, response) {
        if (err) {
          reject(err);
        } else {
          resolve(
            spec.transformResponseData ?
              spec.transformResponseData(response) :
              response
          );
        }
      };

      var options = {headers: objectAssign(opts.headers, spec.headers)};
      self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
    }).bind(this)), callback);
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.Orders"></a>[module stripe.resources.Orders](#apidoc.module.stripe.resources.Orders)

#### <a name="apidoc.element.stripe.resources.Orders.Orders"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Orders ()](#apidoc.element.stripe.resources.Orders.Orders)
- description and source-code
```javascript
Orders = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Orders.extend"></a>[function <span class="apidocSignatureSpan">stripe.resources.Orders.</span>extend (sub)](#apidoc.element.stripe.resources.Orders.extend)
- description and source-code
```javascript
extend = function (sub) {
  var Super = this;
  var Constructor = hasOwn.call(sub, 'constructor') ? sub.constructor : function() {
    Super.apply(this, arguments);
  };
  Constructor.prototype = Object.create(Super.prototype);
  for (var i in sub) {
    if (hasOwn.call(sub, i)) {
      Constructor.prototype[i] = sub[i];
    }
  }
  for (i in Super) {
    if (hasOwn.call(Super, i)) {
      Constructor[i] = Super[i];
    }
  }
  return Constructor;
}
```
- example usage
```shell
...

_Error.extend = utils.protoExtend;

/**
 * Create subclass of internal Error klass
 * (Specifically for errors returned from Stripe's REST API)
 */
var StripeError = _Error.StripeError = _Error.extend({
  type: 'StripeError',
  populate: function(raw) {
// Move from prototype def (so it appears in stringified obj)
this.type = this.type;

this.stack = (new Error(raw.message)).stack;
this.rawType = raw.type;
...
```

#### <a name="apidoc.element.stripe.resources.Orders.method"></a>[function <span class="apidocSignatureSpan">stripe.resources.Orders.</span>method (spec)](#apidoc.element.stripe.resources.Orders.method)
- description and source-code
```javascript
function stripeMethod(spec) {
  var commandPath = typeof spec.path == 'function' ? spec.path
                  : utils.makeURLInterpolator(spec.path || '');
  var requestMethod = (spec.method || 'GET').toUpperCase();
  var urlParams = spec.urlParams || [];
  var encode = spec.encode || function(data) {return data;};

  return function() {
    var self = this;
    var args = [].slice.call(arguments);

    var callback = typeof args[args.length - 1] == 'function' && args.pop();
    var urlData = this.createUrlData();

    return this.wrapTimeout(new Promise((function(resolve, reject) {
      for (var i = 0, l = urlParams.length; i < l; ++i) {
        // Note that we shift the args array after every iteration so this just
        // grabs the "next" argument for use as a URL parameter.
        var arg = args[0];

        var param = urlParams[i];

        var isOptional = OPTIONAL_REGEX.test(param);
        param = param.replace(OPTIONAL_REGEX, '');

        if (!arg) {
          if (isOptional) {
            urlData[param] = '';
            continue;
          }

          var err = new Error(
            'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
            ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
          );
          reject(err);
          return;
        }

        urlData[param] = args.shift();
      }

      var data = encode(utils.getDataFromArgs(args));
      var opts = utils.getOptionsFromArgs(args);

      if (args.length) {
        var err = new Error(
          'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
          'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      var requestPath = this.createFullPath(commandPath, urlData);
      function requestCallback(err, response) {
        if (err) {
          reject(err);
        } else {
          resolve(
            spec.transformResponseData ?
              spec.transformResponseData(response) :
              response
          );
        }
      };

      var options = {headers: objectAssign(opts.headers, spec.headers)};
      self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
    }).bind(this)), callback);
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.Orders.prototype"></a>[module stripe.resources.Orders.prototype](#apidoc.module.stripe.resources.Orders.prototype)

#### <a name="apidoc.element.stripe.resources.Orders.prototype.create"></a>[function <span class="apidocSignatureSpan">stripe.resources.Orders.prototype.</span>create ()](#apidoc.element.stripe.resources.Orders.prototype.create)
- description and source-code
```javascript
create = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
...
The package needs to be configured with your account's secret key which is
available in your [Stripe Dashboard][api-keys]. Require it with the key's
value:

''' js
var stripe = require('stripe')('sk_test_...');

stripe.customers.create(
  { email: 'customer@example.com' },
  function(err, customer) {
    err; // null if no error occurred
    customer; // the created customer object
  }
);
'''
...
```

#### <a name="apidoc.element.stripe.resources.Orders.prototype.pay"></a>[function <span class="apidocSignatureSpan">stripe.resources.Orders.prototype.</span>pay ()](#apidoc.element.stripe.resources.Orders.prototype.pay)
- description and source-code
```javascript
pay = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Orders.prototype.returnOrder"></a>[function <span class="apidocSignatureSpan">stripe.resources.Orders.prototype.</span>returnOrder ()](#apidoc.element.stripe.resources.Orders.prototype.returnOrder)
- description and source-code
```javascript
returnOrder = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.Payouts"></a>[module stripe.resources.Payouts](#apidoc.module.stripe.resources.Payouts)

#### <a name="apidoc.element.stripe.resources.Payouts.Payouts"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Payouts ()](#apidoc.element.stripe.resources.Payouts.Payouts)
- description and source-code
```javascript
Payouts = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Payouts.extend"></a>[function <span class="apidocSignatureSpan">stripe.resources.Payouts.</span>extend (sub)](#apidoc.element.stripe.resources.Payouts.extend)
- description and source-code
```javascript
extend = function (sub) {
  var Super = this;
  var Constructor = hasOwn.call(sub, 'constructor') ? sub.constructor : function() {
    Super.apply(this, arguments);
  };
  Constructor.prototype = Object.create(Super.prototype);
  for (var i in sub) {
    if (hasOwn.call(sub, i)) {
      Constructor.prototype[i] = sub[i];
    }
  }
  for (i in Super) {
    if (hasOwn.call(Super, i)) {
      Constructor[i] = Super[i];
    }
  }
  return Constructor;
}
```
- example usage
```shell
...

_Error.extend = utils.protoExtend;

/**
 * Create subclass of internal Error klass
 * (Specifically for errors returned from Stripe's REST API)
 */
var StripeError = _Error.StripeError = _Error.extend({
  type: 'StripeError',
  populate: function(raw) {
// Move from prototype def (so it appears in stringified obj)
this.type = this.type;

this.stack = (new Error(raw.message)).stack;
this.rawType = raw.type;
...
```

#### <a name="apidoc.element.stripe.resources.Payouts.method"></a>[function <span class="apidocSignatureSpan">stripe.resources.Payouts.</span>method (spec)](#apidoc.element.stripe.resources.Payouts.method)
- description and source-code
```javascript
function stripeMethod(spec) {
  var commandPath = typeof spec.path == 'function' ? spec.path
                  : utils.makeURLInterpolator(spec.path || '');
  var requestMethod = (spec.method || 'GET').toUpperCase();
  var urlParams = spec.urlParams || [];
  var encode = spec.encode || function(data) {return data;};

  return function() {
    var self = this;
    var args = [].slice.call(arguments);

    var callback = typeof args[args.length - 1] == 'function' && args.pop();
    var urlData = this.createUrlData();

    return this.wrapTimeout(new Promise((function(resolve, reject) {
      for (var i = 0, l = urlParams.length; i < l; ++i) {
        // Note that we shift the args array after every iteration so this just
        // grabs the "next" argument for use as a URL parameter.
        var arg = args[0];

        var param = urlParams[i];

        var isOptional = OPTIONAL_REGEX.test(param);
        param = param.replace(OPTIONAL_REGEX, '');

        if (!arg) {
          if (isOptional) {
            urlData[param] = '';
            continue;
          }

          var err = new Error(
            'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
            ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
          );
          reject(err);
          return;
        }

        urlData[param] = args.shift();
      }

      var data = encode(utils.getDataFromArgs(args));
      var opts = utils.getOptionsFromArgs(args);

      if (args.length) {
        var err = new Error(
          'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
          'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      var requestPath = this.createFullPath(commandPath, urlData);
      function requestCallback(err, response) {
        if (err) {
          reject(err);
        } else {
          resolve(
            spec.transformResponseData ?
              spec.transformResponseData(response) :
              response
          );
        }
      };

      var options = {headers: objectAssign(opts.headers, spec.headers)};
      self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
    }).bind(this)), callback);
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.Payouts.prototype"></a>[module stripe.resources.Payouts.prototype](#apidoc.module.stripe.resources.Payouts.prototype)

#### <a name="apidoc.element.stripe.resources.Payouts.prototype.cancel"></a>[function <span class="apidocSignatureSpan">stripe.resources.Payouts.prototype.</span>cancel ()](#apidoc.element.stripe.resources.Payouts.prototype.cancel)
- description and source-code
```javascript
cancel = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Payouts.prototype.listTransactions"></a>[function <span class="apidocSignatureSpan">stripe.resources.Payouts.prototype.</span>listTransactions ()](#apidoc.element.stripe.resources.Payouts.prototype.listTransactions)
- description and source-code
```javascript
listTransactions = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.Plans"></a>[module stripe.resources.Plans](#apidoc.module.stripe.resources.Plans)

#### <a name="apidoc.element.stripe.resources.Plans.Plans"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Plans ()](#apidoc.element.stripe.resources.Plans.Plans)
- description and source-code
```javascript
Plans = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Plans.extend"></a>[function <span class="apidocSignatureSpan">stripe.resources.Plans.</span>extend (sub)](#apidoc.element.stripe.resources.Plans.extend)
- description and source-code
```javascript
extend = function (sub) {
  var Super = this;
  var Constructor = hasOwn.call(sub, 'constructor') ? sub.constructor : function() {
    Super.apply(this, arguments);
  };
  Constructor.prototype = Object.create(Super.prototype);
  for (var i in sub) {
    if (hasOwn.call(sub, i)) {
      Constructor.prototype[i] = sub[i];
    }
  }
  for (i in Super) {
    if (hasOwn.call(Super, i)) {
      Constructor[i] = Super[i];
    }
  }
  return Constructor;
}
```
- example usage
```shell
...

_Error.extend = utils.protoExtend;

/**
 * Create subclass of internal Error klass
 * (Specifically for errors returned from Stripe's REST API)
 */
var StripeError = _Error.StripeError = _Error.extend({
  type: 'StripeError',
  populate: function(raw) {
// Move from prototype def (so it appears in stringified obj)
this.type = this.type;

this.stack = (new Error(raw.message)).stack;
this.rawType = raw.type;
...
```

#### <a name="apidoc.element.stripe.resources.Plans.method"></a>[function <span class="apidocSignatureSpan">stripe.resources.Plans.</span>method (spec)](#apidoc.element.stripe.resources.Plans.method)
- description and source-code
```javascript
function stripeMethod(spec) {
  var commandPath = typeof spec.path == 'function' ? spec.path
                  : utils.makeURLInterpolator(spec.path || '');
  var requestMethod = (spec.method || 'GET').toUpperCase();
  var urlParams = spec.urlParams || [];
  var encode = spec.encode || function(data) {return data;};

  return function() {
    var self = this;
    var args = [].slice.call(arguments);

    var callback = typeof args[args.length - 1] == 'function' && args.pop();
    var urlData = this.createUrlData();

    return this.wrapTimeout(new Promise((function(resolve, reject) {
      for (var i = 0, l = urlParams.length; i < l; ++i) {
        // Note that we shift the args array after every iteration so this just
        // grabs the "next" argument for use as a URL parameter.
        var arg = args[0];

        var param = urlParams[i];

        var isOptional = OPTIONAL_REGEX.test(param);
        param = param.replace(OPTIONAL_REGEX, '');

        if (!arg) {
          if (isOptional) {
            urlData[param] = '';
            continue;
          }

          var err = new Error(
            'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
            ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
          );
          reject(err);
          return;
        }

        urlData[param] = args.shift();
      }

      var data = encode(utils.getDataFromArgs(args));
      var opts = utils.getOptionsFromArgs(args);

      if (args.length) {
        var err = new Error(
          'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
          'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      var requestPath = this.createFullPath(commandPath, urlData);
      function requestCallback(err, response) {
        if (err) {
          reject(err);
        } else {
          resolve(
            spec.transformResponseData ?
              spec.transformResponseData(response) :
              response
          );
        }
      };

      var options = {headers: objectAssign(opts.headers, spec.headers)};
      self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
    }).bind(this)), callback);
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.Products"></a>[module stripe.resources.Products](#apidoc.module.stripe.resources.Products)

#### <a name="apidoc.element.stripe.resources.Products.Products"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Products ()](#apidoc.element.stripe.resources.Products.Products)
- description and source-code
```javascript
Products = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Products.extend"></a>[function <span class="apidocSignatureSpan">stripe.resources.Products.</span>extend (sub)](#apidoc.element.stripe.resources.Products.extend)
- description and source-code
```javascript
extend = function (sub) {
  var Super = this;
  var Constructor = hasOwn.call(sub, 'constructor') ? sub.constructor : function() {
    Super.apply(this, arguments);
  };
  Constructor.prototype = Object.create(Super.prototype);
  for (var i in sub) {
    if (hasOwn.call(sub, i)) {
      Constructor.prototype[i] = sub[i];
    }
  }
  for (i in Super) {
    if (hasOwn.call(Super, i)) {
      Constructor[i] = Super[i];
    }
  }
  return Constructor;
}
```
- example usage
```shell
...

_Error.extend = utils.protoExtend;

/**
 * Create subclass of internal Error klass
 * (Specifically for errors returned from Stripe's REST API)
 */
var StripeError = _Error.StripeError = _Error.extend({
  type: 'StripeError',
  populate: function(raw) {
// Move from prototype def (so it appears in stringified obj)
this.type = this.type;

this.stack = (new Error(raw.message)).stack;
this.rawType = raw.type;
...
```

#### <a name="apidoc.element.stripe.resources.Products.method"></a>[function <span class="apidocSignatureSpan">stripe.resources.Products.</span>method (spec)](#apidoc.element.stripe.resources.Products.method)
- description and source-code
```javascript
function stripeMethod(spec) {
  var commandPath = typeof spec.path == 'function' ? spec.path
                  : utils.makeURLInterpolator(spec.path || '');
  var requestMethod = (spec.method || 'GET').toUpperCase();
  var urlParams = spec.urlParams || [];
  var encode = spec.encode || function(data) {return data;};

  return function() {
    var self = this;
    var args = [].slice.call(arguments);

    var callback = typeof args[args.length - 1] == 'function' && args.pop();
    var urlData = this.createUrlData();

    return this.wrapTimeout(new Promise((function(resolve, reject) {
      for (var i = 0, l = urlParams.length; i < l; ++i) {
        // Note that we shift the args array after every iteration so this just
        // grabs the "next" argument for use as a URL parameter.
        var arg = args[0];

        var param = urlParams[i];

        var isOptional = OPTIONAL_REGEX.test(param);
        param = param.replace(OPTIONAL_REGEX, '');

        if (!arg) {
          if (isOptional) {
            urlData[param] = '';
            continue;
          }

          var err = new Error(
            'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
            ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
          );
          reject(err);
          return;
        }

        urlData[param] = args.shift();
      }

      var data = encode(utils.getDataFromArgs(args));
      var opts = utils.getOptionsFromArgs(args);

      if (args.length) {
        var err = new Error(
          'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
          'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      var requestPath = this.createFullPath(commandPath, urlData);
      function requestCallback(err, response) {
        if (err) {
          reject(err);
        } else {
          resolve(
            spec.transformResponseData ?
              spec.transformResponseData(response) :
              response
          );
        }
      };

      var options = {headers: objectAssign(opts.headers, spec.headers)};
      self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
    }).bind(this)), callback);
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.Products.prototype"></a>[module stripe.resources.Products.prototype](#apidoc.module.stripe.resources.Products.prototype)

#### <a name="apidoc.element.stripe.resources.Products.prototype.create"></a>[function <span class="apidocSignatureSpan">stripe.resources.Products.prototype.</span>create ()](#apidoc.element.stripe.resources.Products.prototype.create)
- description and source-code
```javascript
create = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
...
The package needs to be configured with your account's secret key which is
available in your [Stripe Dashboard][api-keys]. Require it with the key's
value:

''' js
var stripe = require('stripe')('sk_test_...');

stripe.customers.create(
  { email: 'customer@example.com' },
  function(err, customer) {
    err; // null if no error occurred
    customer; // the created customer object
  }
);
'''
...
```



# <a name="apidoc.module.stripe.resources.RecipientCards"></a>[module stripe.resources.RecipientCards](#apidoc.module.stripe.resources.RecipientCards)

#### <a name="apidoc.element.stripe.resources.RecipientCards.RecipientCards"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>RecipientCards ()](#apidoc.element.stripe.resources.RecipientCards.RecipientCards)
- description and source-code
```javascript
RecipientCards = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.RecipientCards.extend"></a>[function <span class="apidocSignatureSpan">stripe.resources.RecipientCards.</span>extend (sub)](#apidoc.element.stripe.resources.RecipientCards.extend)
- description and source-code
```javascript
extend = function (sub) {
  var Super = this;
  var Constructor = hasOwn.call(sub, 'constructor') ? sub.constructor : function() {
    Super.apply(this, arguments);
  };
  Constructor.prototype = Object.create(Super.prototype);
  for (var i in sub) {
    if (hasOwn.call(sub, i)) {
      Constructor.prototype[i] = sub[i];
    }
  }
  for (i in Super) {
    if (hasOwn.call(Super, i)) {
      Constructor[i] = Super[i];
    }
  }
  return Constructor;
}
```
- example usage
```shell
...

_Error.extend = utils.protoExtend;

/**
 * Create subclass of internal Error klass
 * (Specifically for errors returned from Stripe's REST API)
 */
var StripeError = _Error.StripeError = _Error.extend({
  type: 'StripeError',
  populate: function(raw) {
// Move from prototype def (so it appears in stringified obj)
this.type = this.type;

this.stack = (new Error(raw.message)).stack;
this.rawType = raw.type;
...
```

#### <a name="apidoc.element.stripe.resources.RecipientCards.method"></a>[function <span class="apidocSignatureSpan">stripe.resources.RecipientCards.</span>method (spec)](#apidoc.element.stripe.resources.RecipientCards.method)
- description and source-code
```javascript
function stripeMethod(spec) {
  var commandPath = typeof spec.path == 'function' ? spec.path
                  : utils.makeURLInterpolator(spec.path || '');
  var requestMethod = (spec.method || 'GET').toUpperCase();
  var urlParams = spec.urlParams || [];
  var encode = spec.encode || function(data) {return data;};

  return function() {
    var self = this;
    var args = [].slice.call(arguments);

    var callback = typeof args[args.length - 1] == 'function' && args.pop();
    var urlData = this.createUrlData();

    return this.wrapTimeout(new Promise((function(resolve, reject) {
      for (var i = 0, l = urlParams.length; i < l; ++i) {
        // Note that we shift the args array after every iteration so this just
        // grabs the "next" argument for use as a URL parameter.
        var arg = args[0];

        var param = urlParams[i];

        var isOptional = OPTIONAL_REGEX.test(param);
        param = param.replace(OPTIONAL_REGEX, '');

        if (!arg) {
          if (isOptional) {
            urlData[param] = '';
            continue;
          }

          var err = new Error(
            'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
            ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
          );
          reject(err);
          return;
        }

        urlData[param] = args.shift();
      }

      var data = encode(utils.getDataFromArgs(args));
      var opts = utils.getOptionsFromArgs(args);

      if (args.length) {
        var err = new Error(
          'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
          'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      var requestPath = this.createFullPath(commandPath, urlData);
      function requestCallback(err, response) {
        if (err) {
          reject(err);
        } else {
          resolve(
            spec.transformResponseData ?
              spec.transformResponseData(response) :
              response
          );
        }
      };

      var options = {headers: objectAssign(opts.headers, spec.headers)};
      self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
    }).bind(this)), callback);
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.Recipients"></a>[module stripe.resources.Recipients](#apidoc.module.stripe.resources.Recipients)

#### <a name="apidoc.element.stripe.resources.Recipients.Recipients"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Recipients ()](#apidoc.element.stripe.resources.Recipients.Recipients)
- description and source-code
```javascript
Recipients = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Recipients.extend"></a>[function <span class="apidocSignatureSpan">stripe.resources.Recipients.</span>extend (sub)](#apidoc.element.stripe.resources.Recipients.extend)
- description and source-code
```javascript
extend = function (sub) {
  var Super = this;
  var Constructor = hasOwn.call(sub, 'constructor') ? sub.constructor : function() {
    Super.apply(this, arguments);
  };
  Constructor.prototype = Object.create(Super.prototype);
  for (var i in sub) {
    if (hasOwn.call(sub, i)) {
      Constructor.prototype[i] = sub[i];
    }
  }
  for (i in Super) {
    if (hasOwn.call(Super, i)) {
      Constructor[i] = Super[i];
    }
  }
  return Constructor;
}
```
- example usage
```shell
...

_Error.extend = utils.protoExtend;

/**
 * Create subclass of internal Error klass
 * (Specifically for errors returned from Stripe's REST API)
 */
var StripeError = _Error.StripeError = _Error.extend({
  type: 'StripeError',
  populate: function(raw) {
// Move from prototype def (so it appears in stringified obj)
this.type = this.type;

this.stack = (new Error(raw.message)).stack;
this.rawType = raw.type;
...
```

#### <a name="apidoc.element.stripe.resources.Recipients.method"></a>[function <span class="apidocSignatureSpan">stripe.resources.Recipients.</span>method (spec)](#apidoc.element.stripe.resources.Recipients.method)
- description and source-code
```javascript
function stripeMethod(spec) {
  var commandPath = typeof spec.path == 'function' ? spec.path
                  : utils.makeURLInterpolator(spec.path || '');
  var requestMethod = (spec.method || 'GET').toUpperCase();
  var urlParams = spec.urlParams || [];
  var encode = spec.encode || function(data) {return data;};

  return function() {
    var self = this;
    var args = [].slice.call(arguments);

    var callback = typeof args[args.length - 1] == 'function' && args.pop();
    var urlData = this.createUrlData();

    return this.wrapTimeout(new Promise((function(resolve, reject) {
      for (var i = 0, l = urlParams.length; i < l; ++i) {
        // Note that we shift the args array after every iteration so this just
        // grabs the "next" argument for use as a URL parameter.
        var arg = args[0];

        var param = urlParams[i];

        var isOptional = OPTIONAL_REGEX.test(param);
        param = param.replace(OPTIONAL_REGEX, '');

        if (!arg) {
          if (isOptional) {
            urlData[param] = '';
            continue;
          }

          var err = new Error(
            'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
            ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
          );
          reject(err);
          return;
        }

        urlData[param] = args.shift();
      }

      var data = encode(utils.getDataFromArgs(args));
      var opts = utils.getOptionsFromArgs(args);

      if (args.length) {
        var err = new Error(
          'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
          'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      var requestPath = this.createFullPath(commandPath, urlData);
      function requestCallback(err, response) {
        if (err) {
          reject(err);
        } else {
          resolve(
            spec.transformResponseData ?
              spec.transformResponseData(response) :
              response
          );
        }
      };

      var options = {headers: objectAssign(opts.headers, spec.headers)};
      self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
    }).bind(this)), callback);
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.Recipients.prototype"></a>[module stripe.resources.Recipients.prototype](#apidoc.module.stripe.resources.Recipients.prototype)

#### <a name="apidoc.element.stripe.resources.Recipients.prototype.createCard"></a>[function <span class="apidocSignatureSpan">stripe.resources.Recipients.prototype.</span>createCard ()](#apidoc.element.stripe.resources.Recipients.prototype.createCard)
- description and source-code
```javascript
createCard = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Recipients.prototype.deleteCard"></a>[function <span class="apidocSignatureSpan">stripe.resources.Recipients.prototype.</span>deleteCard ()](#apidoc.element.stripe.resources.Recipients.prototype.deleteCard)
- description and source-code
```javascript
deleteCard = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Recipients.prototype.listCards"></a>[function <span class="apidocSignatureSpan">stripe.resources.Recipients.prototype.</span>listCards ()](#apidoc.element.stripe.resources.Recipients.prototype.listCards)
- description and source-code
```javascript
listCards = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Recipients.prototype.retrieveCard"></a>[function <span class="apidocSignatureSpan">stripe.resources.Recipients.prototype.</span>retrieveCard ()](#apidoc.element.stripe.resources.Recipients.prototype.retrieveCard)
- description and source-code
```javascript
retrieveCard = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Recipients.prototype.updateCard"></a>[function <span class="apidocSignatureSpan">stripe.resources.Recipients.prototype.</span>updateCard ()](#apidoc.element.stripe.resources.Recipients.prototype.updateCard)
- description and source-code
```javascript
updateCard = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.Refunds"></a>[module stripe.resources.Refunds](#apidoc.module.stripe.resources.Refunds)

#### <a name="apidoc.element.stripe.resources.Refunds.Refunds"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Refunds ()](#apidoc.element.stripe.resources.Refunds.Refunds)
- description and source-code
```javascript
Refunds = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Refunds.extend"></a>[function <span class="apidocSignatureSpan">stripe.resources.Refunds.</span>extend (sub)](#apidoc.element.stripe.resources.Refunds.extend)
- description and source-code
```javascript
extend = function (sub) {
  var Super = this;
  var Constructor = hasOwn.call(sub, 'constructor') ? sub.constructor : function() {
    Super.apply(this, arguments);
  };
  Constructor.prototype = Object.create(Super.prototype);
  for (var i in sub) {
    if (hasOwn.call(sub, i)) {
      Constructor.prototype[i] = sub[i];
    }
  }
  for (i in Super) {
    if (hasOwn.call(Super, i)) {
      Constructor[i] = Super[i];
    }
  }
  return Constructor;
}
```
- example usage
```shell
...

_Error.extend = utils.protoExtend;

/**
 * Create subclass of internal Error klass
 * (Specifically for errors returned from Stripe's REST API)
 */
var StripeError = _Error.StripeError = _Error.extend({
  type: 'StripeError',
  populate: function(raw) {
// Move from prototype def (so it appears in stringified obj)
this.type = this.type;

this.stack = (new Error(raw.message)).stack;
this.rawType = raw.type;
...
```

#### <a name="apidoc.element.stripe.resources.Refunds.method"></a>[function <span class="apidocSignatureSpan">stripe.resources.Refunds.</span>method (spec)](#apidoc.element.stripe.resources.Refunds.method)
- description and source-code
```javascript
function stripeMethod(spec) {
  var commandPath = typeof spec.path == 'function' ? spec.path
                  : utils.makeURLInterpolator(spec.path || '');
  var requestMethod = (spec.method || 'GET').toUpperCase();
  var urlParams = spec.urlParams || [];
  var encode = spec.encode || function(data) {return data;};

  return function() {
    var self = this;
    var args = [].slice.call(arguments);

    var callback = typeof args[args.length - 1] == 'function' && args.pop();
    var urlData = this.createUrlData();

    return this.wrapTimeout(new Promise((function(resolve, reject) {
      for (var i = 0, l = urlParams.length; i < l; ++i) {
        // Note that we shift the args array after every iteration so this just
        // grabs the "next" argument for use as a URL parameter.
        var arg = args[0];

        var param = urlParams[i];

        var isOptional = OPTIONAL_REGEX.test(param);
        param = param.replace(OPTIONAL_REGEX, '');

        if (!arg) {
          if (isOptional) {
            urlData[param] = '';
            continue;
          }

          var err = new Error(
            'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
            ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
          );
          reject(err);
          return;
        }

        urlData[param] = args.shift();
      }

      var data = encode(utils.getDataFromArgs(args));
      var opts = utils.getOptionsFromArgs(args);

      if (args.length) {
        var err = new Error(
          'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
          'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      var requestPath = this.createFullPath(commandPath, urlData);
      function requestCallback(err, response) {
        if (err) {
          reject(err);
        } else {
          resolve(
            spec.transformResponseData ?
              spec.transformResponseData(response) :
              response
          );
        }
      };

      var options = {headers: objectAssign(opts.headers, spec.headers)};
      self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
    }).bind(this)), callback);
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.Skus"></a>[module stripe.resources.Skus](#apidoc.module.stripe.resources.Skus)

#### <a name="apidoc.element.stripe.resources.Skus.Skus"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Skus ()](#apidoc.element.stripe.resources.Skus.Skus)
- description and source-code
```javascript
Skus = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Skus.extend"></a>[function <span class="apidocSignatureSpan">stripe.resources.Skus.</span>extend (sub)](#apidoc.element.stripe.resources.Skus.extend)
- description and source-code
```javascript
extend = function (sub) {
  var Super = this;
  var Constructor = hasOwn.call(sub, 'constructor') ? sub.constructor : function() {
    Super.apply(this, arguments);
  };
  Constructor.prototype = Object.create(Super.prototype);
  for (var i in sub) {
    if (hasOwn.call(sub, i)) {
      Constructor.prototype[i] = sub[i];
    }
  }
  for (i in Super) {
    if (hasOwn.call(Super, i)) {
      Constructor[i] = Super[i];
    }
  }
  return Constructor;
}
```
- example usage
```shell
...

_Error.extend = utils.protoExtend;

/**
 * Create subclass of internal Error klass
 * (Specifically for errors returned from Stripe's REST API)
 */
var StripeError = _Error.StripeError = _Error.extend({
  type: 'StripeError',
  populate: function(raw) {
// Move from prototype def (so it appears in stringified obj)
this.type = this.type;

this.stack = (new Error(raw.message)).stack;
this.rawType = raw.type;
...
```

#### <a name="apidoc.element.stripe.resources.Skus.method"></a>[function <span class="apidocSignatureSpan">stripe.resources.Skus.</span>method (spec)](#apidoc.element.stripe.resources.Skus.method)
- description and source-code
```javascript
function stripeMethod(spec) {
  var commandPath = typeof spec.path == 'function' ? spec.path
                  : utils.makeURLInterpolator(spec.path || '');
  var requestMethod = (spec.method || 'GET').toUpperCase();
  var urlParams = spec.urlParams || [];
  var encode = spec.encode || function(data) {return data;};

  return function() {
    var self = this;
    var args = [].slice.call(arguments);

    var callback = typeof args[args.length - 1] == 'function' && args.pop();
    var urlData = this.createUrlData();

    return this.wrapTimeout(new Promise((function(resolve, reject) {
      for (var i = 0, l = urlParams.length; i < l; ++i) {
        // Note that we shift the args array after every iteration so this just
        // grabs the "next" argument for use as a URL parameter.
        var arg = args[0];

        var param = urlParams[i];

        var isOptional = OPTIONAL_REGEX.test(param);
        param = param.replace(OPTIONAL_REGEX, '');

        if (!arg) {
          if (isOptional) {
            urlData[param] = '';
            continue;
          }

          var err = new Error(
            'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
            ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
          );
          reject(err);
          return;
        }

        urlData[param] = args.shift();
      }

      var data = encode(utils.getDataFromArgs(args));
      var opts = utils.getOptionsFromArgs(args);

      if (args.length) {
        var err = new Error(
          'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
          'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      var requestPath = this.createFullPath(commandPath, urlData);
      function requestCallback(err, response) {
        if (err) {
          reject(err);
        } else {
          resolve(
            spec.transformResponseData ?
              spec.transformResponseData(response) :
              response
          );
        }
      };

      var options = {headers: objectAssign(opts.headers, spec.headers)};
      self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
    }).bind(this)), callback);
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.Skus.prototype"></a>[module stripe.resources.Skus.prototype](#apidoc.module.stripe.resources.Skus.prototype)

#### <a name="apidoc.element.stripe.resources.Skus.prototype.create"></a>[function <span class="apidocSignatureSpan">stripe.resources.Skus.prototype.</span>create ()](#apidoc.element.stripe.resources.Skus.prototype.create)
- description and source-code
```javascript
create = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
...
The package needs to be configured with your account's secret key which is
available in your [Stripe Dashboard][api-keys]. Require it with the key's
value:

''' js
var stripe = require('stripe')('sk_test_...');

stripe.customers.create(
  { email: 'customer@example.com' },
  function(err, customer) {
    err; // null if no error occurred
    customer; // the created customer object
  }
);
'''
...
```



# <a name="apidoc.module.stripe.resources.Sources"></a>[module stripe.resources.Sources](#apidoc.module.stripe.resources.Sources)

#### <a name="apidoc.element.stripe.resources.Sources.Sources"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Sources ()](#apidoc.element.stripe.resources.Sources.Sources)
- description and source-code
```javascript
Sources = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Sources.extend"></a>[function <span class="apidocSignatureSpan">stripe.resources.Sources.</span>extend (sub)](#apidoc.element.stripe.resources.Sources.extend)
- description and source-code
```javascript
extend = function (sub) {
  var Super = this;
  var Constructor = hasOwn.call(sub, 'constructor') ? sub.constructor : function() {
    Super.apply(this, arguments);
  };
  Constructor.prototype = Object.create(Super.prototype);
  for (var i in sub) {
    if (hasOwn.call(sub, i)) {
      Constructor.prototype[i] = sub[i];
    }
  }
  for (i in Super) {
    if (hasOwn.call(Super, i)) {
      Constructor[i] = Super[i];
    }
  }
  return Constructor;
}
```
- example usage
```shell
...

_Error.extend = utils.protoExtend;

/**
 * Create subclass of internal Error klass
 * (Specifically for errors returned from Stripe's REST API)
 */
var StripeError = _Error.StripeError = _Error.extend({
  type: 'StripeError',
  populate: function(raw) {
// Move from prototype def (so it appears in stringified obj)
this.type = this.type;

this.stack = (new Error(raw.message)).stack;
this.rawType = raw.type;
...
```

#### <a name="apidoc.element.stripe.resources.Sources.method"></a>[function <span class="apidocSignatureSpan">stripe.resources.Sources.</span>method (spec)](#apidoc.element.stripe.resources.Sources.method)
- description and source-code
```javascript
function stripeMethod(spec) {
  var commandPath = typeof spec.path == 'function' ? spec.path
                  : utils.makeURLInterpolator(spec.path || '');
  var requestMethod = (spec.method || 'GET').toUpperCase();
  var urlParams = spec.urlParams || [];
  var encode = spec.encode || function(data) {return data;};

  return function() {
    var self = this;
    var args = [].slice.call(arguments);

    var callback = typeof args[args.length - 1] == 'function' && args.pop();
    var urlData = this.createUrlData();

    return this.wrapTimeout(new Promise((function(resolve, reject) {
      for (var i = 0, l = urlParams.length; i < l; ++i) {
        // Note that we shift the args array after every iteration so this just
        // grabs the "next" argument for use as a URL parameter.
        var arg = args[0];

        var param = urlParams[i];

        var isOptional = OPTIONAL_REGEX.test(param);
        param = param.replace(OPTIONAL_REGEX, '');

        if (!arg) {
          if (isOptional) {
            urlData[param] = '';
            continue;
          }

          var err = new Error(
            'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
            ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
          );
          reject(err);
          return;
        }

        urlData[param] = args.shift();
      }

      var data = encode(utils.getDataFromArgs(args));
      var opts = utils.getOptionsFromArgs(args);

      if (args.length) {
        var err = new Error(
          'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
          'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      var requestPath = this.createFullPath(commandPath, urlData);
      function requestCallback(err, response) {
        if (err) {
          reject(err);
        } else {
          resolve(
            spec.transformResponseData ?
              spec.transformResponseData(response) :
              response
          );
        }
      };

      var options = {headers: objectAssign(opts.headers, spec.headers)};
      self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
    }).bind(this)), callback);
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.Sources.prototype"></a>[module stripe.resources.Sources.prototype](#apidoc.module.stripe.resources.Sources.prototype)

#### <a name="apidoc.element.stripe.resources.Sources.prototype.verify"></a>[function <span class="apidocSignatureSpan">stripe.resources.Sources.prototype.</span>verify ()](#apidoc.element.stripe.resources.Sources.prototype.verify)
- description and source-code
```javascript
verify = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.SubscriptionItems"></a>[module stripe.resources.SubscriptionItems](#apidoc.module.stripe.resources.SubscriptionItems)

#### <a name="apidoc.element.stripe.resources.SubscriptionItems.SubscriptionItems"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>SubscriptionItems ()](#apidoc.element.stripe.resources.SubscriptionItems.SubscriptionItems)
- description and source-code
```javascript
SubscriptionItems = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.SubscriptionItems.extend"></a>[function <span class="apidocSignatureSpan">stripe.resources.SubscriptionItems.</span>extend (sub)](#apidoc.element.stripe.resources.SubscriptionItems.extend)
- description and source-code
```javascript
extend = function (sub) {
  var Super = this;
  var Constructor = hasOwn.call(sub, 'constructor') ? sub.constructor : function() {
    Super.apply(this, arguments);
  };
  Constructor.prototype = Object.create(Super.prototype);
  for (var i in sub) {
    if (hasOwn.call(sub, i)) {
      Constructor.prototype[i] = sub[i];
    }
  }
  for (i in Super) {
    if (hasOwn.call(Super, i)) {
      Constructor[i] = Super[i];
    }
  }
  return Constructor;
}
```
- example usage
```shell
...

_Error.extend = utils.protoExtend;

/**
 * Create subclass of internal Error klass
 * (Specifically for errors returned from Stripe's REST API)
 */
var StripeError = _Error.StripeError = _Error.extend({
  type: 'StripeError',
  populate: function(raw) {
// Move from prototype def (so it appears in stringified obj)
this.type = this.type;

this.stack = (new Error(raw.message)).stack;
this.rawType = raw.type;
...
```

#### <a name="apidoc.element.stripe.resources.SubscriptionItems.method"></a>[function <span class="apidocSignatureSpan">stripe.resources.SubscriptionItems.</span>method (spec)](#apidoc.element.stripe.resources.SubscriptionItems.method)
- description and source-code
```javascript
function stripeMethod(spec) {
  var commandPath = typeof spec.path == 'function' ? spec.path
                  : utils.makeURLInterpolator(spec.path || '');
  var requestMethod = (spec.method || 'GET').toUpperCase();
  var urlParams = spec.urlParams || [];
  var encode = spec.encode || function(data) {return data;};

  return function() {
    var self = this;
    var args = [].slice.call(arguments);

    var callback = typeof args[args.length - 1] == 'function' && args.pop();
    var urlData = this.createUrlData();

    return this.wrapTimeout(new Promise((function(resolve, reject) {
      for (var i = 0, l = urlParams.length; i < l; ++i) {
        // Note that we shift the args array after every iteration so this just
        // grabs the "next" argument for use as a URL parameter.
        var arg = args[0];

        var param = urlParams[i];

        var isOptional = OPTIONAL_REGEX.test(param);
        param = param.replace(OPTIONAL_REGEX, '');

        if (!arg) {
          if (isOptional) {
            urlData[param] = '';
            continue;
          }

          var err = new Error(
            'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
            ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
          );
          reject(err);
          return;
        }

        urlData[param] = args.shift();
      }

      var data = encode(utils.getDataFromArgs(args));
      var opts = utils.getOptionsFromArgs(args);

      if (args.length) {
        var err = new Error(
          'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
          'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      var requestPath = this.createFullPath(commandPath, urlData);
      function requestCallback(err, response) {
        if (err) {
          reject(err);
        } else {
          resolve(
            spec.transformResponseData ?
              spec.transformResponseData(response) :
              response
          );
        }
      };

      var options = {headers: objectAssign(opts.headers, spec.headers)};
      self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
    }).bind(this)), callback);
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.Subscriptions"></a>[module stripe.resources.Subscriptions](#apidoc.module.stripe.resources.Subscriptions)

#### <a name="apidoc.element.stripe.resources.Subscriptions.Subscriptions"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Subscriptions ()](#apidoc.element.stripe.resources.Subscriptions.Subscriptions)
- description and source-code
```javascript
Subscriptions = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Subscriptions.extend"></a>[function <span class="apidocSignatureSpan">stripe.resources.Subscriptions.</span>extend (sub)](#apidoc.element.stripe.resources.Subscriptions.extend)
- description and source-code
```javascript
extend = function (sub) {
  var Super = this;
  var Constructor = hasOwn.call(sub, 'constructor') ? sub.constructor : function() {
    Super.apply(this, arguments);
  };
  Constructor.prototype = Object.create(Super.prototype);
  for (var i in sub) {
    if (hasOwn.call(sub, i)) {
      Constructor.prototype[i] = sub[i];
    }
  }
  for (i in Super) {
    if (hasOwn.call(Super, i)) {
      Constructor[i] = Super[i];
    }
  }
  return Constructor;
}
```
- example usage
```shell
...

_Error.extend = utils.protoExtend;

/**
 * Create subclass of internal Error klass
 * (Specifically for errors returned from Stripe's REST API)
 */
var StripeError = _Error.StripeError = _Error.extend({
  type: 'StripeError',
  populate: function(raw) {
// Move from prototype def (so it appears in stringified obj)
this.type = this.type;

this.stack = (new Error(raw.message)).stack;
this.rawType = raw.type;
...
```

#### <a name="apidoc.element.stripe.resources.Subscriptions.method"></a>[function <span class="apidocSignatureSpan">stripe.resources.Subscriptions.</span>method (spec)](#apidoc.element.stripe.resources.Subscriptions.method)
- description and source-code
```javascript
function stripeMethod(spec) {
  var commandPath = typeof spec.path == 'function' ? spec.path
                  : utils.makeURLInterpolator(spec.path || '');
  var requestMethod = (spec.method || 'GET').toUpperCase();
  var urlParams = spec.urlParams || [];
  var encode = spec.encode || function(data) {return data;};

  return function() {
    var self = this;
    var args = [].slice.call(arguments);

    var callback = typeof args[args.length - 1] == 'function' && args.pop();
    var urlData = this.createUrlData();

    return this.wrapTimeout(new Promise((function(resolve, reject) {
      for (var i = 0, l = urlParams.length; i < l; ++i) {
        // Note that we shift the args array after every iteration so this just
        // grabs the "next" argument for use as a URL parameter.
        var arg = args[0];

        var param = urlParams[i];

        var isOptional = OPTIONAL_REGEX.test(param);
        param = param.replace(OPTIONAL_REGEX, '');

        if (!arg) {
          if (isOptional) {
            urlData[param] = '';
            continue;
          }

          var err = new Error(
            'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
            ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
          );
          reject(err);
          return;
        }

        urlData[param] = args.shift();
      }

      var data = encode(utils.getDataFromArgs(args));
      var opts = utils.getOptionsFromArgs(args);

      if (args.length) {
        var err = new Error(
          'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
          'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      var requestPath = this.createFullPath(commandPath, urlData);
      function requestCallback(err, response) {
        if (err) {
          reject(err);
        } else {
          resolve(
            spec.transformResponseData ?
              spec.transformResponseData(response) :
              response
          );
        }
      };

      var options = {headers: objectAssign(opts.headers, spec.headers)};
      self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
    }).bind(this)), callback);
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.Subscriptions.prototype"></a>[module stripe.resources.Subscriptions.prototype](#apidoc.module.stripe.resources.Subscriptions.prototype)

#### <a name="apidoc.element.stripe.resources.Subscriptions.prototype.create"></a>[function <span class="apidocSignatureSpan">stripe.resources.Subscriptions.prototype.</span>create ()](#apidoc.element.stripe.resources.Subscriptions.prototype.create)
- description and source-code
```javascript
create = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
...
The package needs to be configured with your account's secret key which is
available in your [Stripe Dashboard][api-keys]. Require it with the key's
value:

''' js
var stripe = require('stripe')('sk_test_...');

stripe.customers.create(
  { email: 'customer@example.com' },
  function(err, customer) {
    err; // null if no error occurred
    customer; // the created customer object
  }
);
'''
...
```

#### <a name="apidoc.element.stripe.resources.Subscriptions.prototype.deleteDiscount"></a>[function <span class="apidocSignatureSpan">stripe.resources.Subscriptions.prototype.</span>deleteDiscount ()](#apidoc.element.stripe.resources.Subscriptions.prototype.deleteDiscount)
- description and source-code
```javascript
deleteDiscount = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Subscriptions.prototype.update"></a>[function <span class="apidocSignatureSpan">stripe.resources.Subscriptions.prototype.</span>update ()](#apidoc.element.stripe.resources.Subscriptions.prototype.update)
- description and source-code
```javascript
update = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.ThreeDSecure"></a>[module stripe.resources.ThreeDSecure](#apidoc.module.stripe.resources.ThreeDSecure)

#### <a name="apidoc.element.stripe.resources.ThreeDSecure.ThreeDSecure"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>ThreeDSecure ()](#apidoc.element.stripe.resources.ThreeDSecure.ThreeDSecure)
- description and source-code
```javascript
ThreeDSecure = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.ThreeDSecure.extend"></a>[function <span class="apidocSignatureSpan">stripe.resources.ThreeDSecure.</span>extend (sub)](#apidoc.element.stripe.resources.ThreeDSecure.extend)
- description and source-code
```javascript
extend = function (sub) {
  var Super = this;
  var Constructor = hasOwn.call(sub, 'constructor') ? sub.constructor : function() {
    Super.apply(this, arguments);
  };
  Constructor.prototype = Object.create(Super.prototype);
  for (var i in sub) {
    if (hasOwn.call(sub, i)) {
      Constructor.prototype[i] = sub[i];
    }
  }
  for (i in Super) {
    if (hasOwn.call(Super, i)) {
      Constructor[i] = Super[i];
    }
  }
  return Constructor;
}
```
- example usage
```shell
...

_Error.extend = utils.protoExtend;

/**
 * Create subclass of internal Error klass
 * (Specifically for errors returned from Stripe's REST API)
 */
var StripeError = _Error.StripeError = _Error.extend({
  type: 'StripeError',
  populate: function(raw) {
// Move from prototype def (so it appears in stringified obj)
this.type = this.type;

this.stack = (new Error(raw.message)).stack;
this.rawType = raw.type;
...
```

#### <a name="apidoc.element.stripe.resources.ThreeDSecure.method"></a>[function <span class="apidocSignatureSpan">stripe.resources.ThreeDSecure.</span>method (spec)](#apidoc.element.stripe.resources.ThreeDSecure.method)
- description and source-code
```javascript
function stripeMethod(spec) {
  var commandPath = typeof spec.path == 'function' ? spec.path
                  : utils.makeURLInterpolator(spec.path || '');
  var requestMethod = (spec.method || 'GET').toUpperCase();
  var urlParams = spec.urlParams || [];
  var encode = spec.encode || function(data) {return data;};

  return function() {
    var self = this;
    var args = [].slice.call(arguments);

    var callback = typeof args[args.length - 1] == 'function' && args.pop();
    var urlData = this.createUrlData();

    return this.wrapTimeout(new Promise((function(resolve, reject) {
      for (var i = 0, l = urlParams.length; i < l; ++i) {
        // Note that we shift the args array after every iteration so this just
        // grabs the "next" argument for use as a URL parameter.
        var arg = args[0];

        var param = urlParams[i];

        var isOptional = OPTIONAL_REGEX.test(param);
        param = param.replace(OPTIONAL_REGEX, '');

        if (!arg) {
          if (isOptional) {
            urlData[param] = '';
            continue;
          }

          var err = new Error(
            'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
            ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
          );
          reject(err);
          return;
        }

        urlData[param] = args.shift();
      }

      var data = encode(utils.getDataFromArgs(args));
      var opts = utils.getOptionsFromArgs(args);

      if (args.length) {
        var err = new Error(
          'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
          'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      var requestPath = this.createFullPath(commandPath, urlData);
      function requestCallback(err, response) {
        if (err) {
          reject(err);
        } else {
          resolve(
            spec.transformResponseData ?
              spec.transformResponseData(response) :
              response
          );
        }
      };

      var options = {headers: objectAssign(opts.headers, spec.headers)};
      self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
    }).bind(this)), callback);
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.Tokens"></a>[module stripe.resources.Tokens](#apidoc.module.stripe.resources.Tokens)

#### <a name="apidoc.element.stripe.resources.Tokens.Tokens"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Tokens ()](#apidoc.element.stripe.resources.Tokens.Tokens)
- description and source-code
```javascript
Tokens = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Tokens.extend"></a>[function <span class="apidocSignatureSpan">stripe.resources.Tokens.</span>extend (sub)](#apidoc.element.stripe.resources.Tokens.extend)
- description and source-code
```javascript
extend = function (sub) {
  var Super = this;
  var Constructor = hasOwn.call(sub, 'constructor') ? sub.constructor : function() {
    Super.apply(this, arguments);
  };
  Constructor.prototype = Object.create(Super.prototype);
  for (var i in sub) {
    if (hasOwn.call(sub, i)) {
      Constructor.prototype[i] = sub[i];
    }
  }
  for (i in Super) {
    if (hasOwn.call(Super, i)) {
      Constructor[i] = Super[i];
    }
  }
  return Constructor;
}
```
- example usage
```shell
...

_Error.extend = utils.protoExtend;

/**
 * Create subclass of internal Error klass
 * (Specifically for errors returned from Stripe's REST API)
 */
var StripeError = _Error.StripeError = _Error.extend({
  type: 'StripeError',
  populate: function(raw) {
// Move from prototype def (so it appears in stringified obj)
this.type = this.type;

this.stack = (new Error(raw.message)).stack;
this.rawType = raw.type;
...
```

#### <a name="apidoc.element.stripe.resources.Tokens.method"></a>[function <span class="apidocSignatureSpan">stripe.resources.Tokens.</span>method (spec)](#apidoc.element.stripe.resources.Tokens.method)
- description and source-code
```javascript
function stripeMethod(spec) {
  var commandPath = typeof spec.path == 'function' ? spec.path
                  : utils.makeURLInterpolator(spec.path || '');
  var requestMethod = (spec.method || 'GET').toUpperCase();
  var urlParams = spec.urlParams || [];
  var encode = spec.encode || function(data) {return data;};

  return function() {
    var self = this;
    var args = [].slice.call(arguments);

    var callback = typeof args[args.length - 1] == 'function' && args.pop();
    var urlData = this.createUrlData();

    return this.wrapTimeout(new Promise((function(resolve, reject) {
      for (var i = 0, l = urlParams.length; i < l; ++i) {
        // Note that we shift the args array after every iteration so this just
        // grabs the "next" argument for use as a URL parameter.
        var arg = args[0];

        var param = urlParams[i];

        var isOptional = OPTIONAL_REGEX.test(param);
        param = param.replace(OPTIONAL_REGEX, '');

        if (!arg) {
          if (isOptional) {
            urlData[param] = '';
            continue;
          }

          var err = new Error(
            'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
            ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
          );
          reject(err);
          return;
        }

        urlData[param] = args.shift();
      }

      var data = encode(utils.getDataFromArgs(args));
      var opts = utils.getOptionsFromArgs(args);

      if (args.length) {
        var err = new Error(
          'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
          'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      var requestPath = this.createFullPath(commandPath, urlData);
      function requestCallback(err, response) {
        if (err) {
          reject(err);
        } else {
          resolve(
            spec.transformResponseData ?
              spec.transformResponseData(response) :
              response
          );
        }
      };

      var options = {headers: objectAssign(opts.headers, spec.headers)};
      self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
    }).bind(this)), callback);
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.TransferReversals"></a>[module stripe.resources.TransferReversals](#apidoc.module.stripe.resources.TransferReversals)

#### <a name="apidoc.element.stripe.resources.TransferReversals.TransferReversals"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>TransferReversals ()](#apidoc.element.stripe.resources.TransferReversals.TransferReversals)
- description and source-code
```javascript
TransferReversals = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.TransferReversals.extend"></a>[function <span class="apidocSignatureSpan">stripe.resources.TransferReversals.</span>extend (sub)](#apidoc.element.stripe.resources.TransferReversals.extend)
- description and source-code
```javascript
extend = function (sub) {
  var Super = this;
  var Constructor = hasOwn.call(sub, 'constructor') ? sub.constructor : function() {
    Super.apply(this, arguments);
  };
  Constructor.prototype = Object.create(Super.prototype);
  for (var i in sub) {
    if (hasOwn.call(sub, i)) {
      Constructor.prototype[i] = sub[i];
    }
  }
  for (i in Super) {
    if (hasOwn.call(Super, i)) {
      Constructor[i] = Super[i];
    }
  }
  return Constructor;
}
```
- example usage
```shell
...

_Error.extend = utils.protoExtend;

/**
 * Create subclass of internal Error klass
 * (Specifically for errors returned from Stripe's REST API)
 */
var StripeError = _Error.StripeError = _Error.extend({
  type: 'StripeError',
  populate: function(raw) {
// Move from prototype def (so it appears in stringified obj)
this.type = this.type;

this.stack = (new Error(raw.message)).stack;
this.rawType = raw.type;
...
```

#### <a name="apidoc.element.stripe.resources.TransferReversals.method"></a>[function <span class="apidocSignatureSpan">stripe.resources.TransferReversals.</span>method (spec)](#apidoc.element.stripe.resources.TransferReversals.method)
- description and source-code
```javascript
function stripeMethod(spec) {
  var commandPath = typeof spec.path == 'function' ? spec.path
                  : utils.makeURLInterpolator(spec.path || '');
  var requestMethod = (spec.method || 'GET').toUpperCase();
  var urlParams = spec.urlParams || [];
  var encode = spec.encode || function(data) {return data;};

  return function() {
    var self = this;
    var args = [].slice.call(arguments);

    var callback = typeof args[args.length - 1] == 'function' && args.pop();
    var urlData = this.createUrlData();

    return this.wrapTimeout(new Promise((function(resolve, reject) {
      for (var i = 0, l = urlParams.length; i < l; ++i) {
        // Note that we shift the args array after every iteration so this just
        // grabs the "next" argument for use as a URL parameter.
        var arg = args[0];

        var param = urlParams[i];

        var isOptional = OPTIONAL_REGEX.test(param);
        param = param.replace(OPTIONAL_REGEX, '');

        if (!arg) {
          if (isOptional) {
            urlData[param] = '';
            continue;
          }

          var err = new Error(
            'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
            ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
          );
          reject(err);
          return;
        }

        urlData[param] = args.shift();
      }

      var data = encode(utils.getDataFromArgs(args));
      var opts = utils.getOptionsFromArgs(args);

      if (args.length) {
        var err = new Error(
          'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
          'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      var requestPath = this.createFullPath(commandPath, urlData);
      function requestCallback(err, response) {
        if (err) {
          reject(err);
        } else {
          resolve(
            spec.transformResponseData ?
              spec.transformResponseData(response) :
              response
          );
        }
      };

      var options = {headers: objectAssign(opts.headers, spec.headers)};
      self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
    }).bind(this)), callback);
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.Transfers"></a>[module stripe.resources.Transfers](#apidoc.module.stripe.resources.Transfers)

#### <a name="apidoc.element.stripe.resources.Transfers.Transfers"></a>[function <span class="apidocSignatureSpan">stripe.resources.</span>Transfers ()](#apidoc.element.stripe.resources.Transfers.Transfers)
- description and source-code
```javascript
Transfers = function () {
  Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Transfers.extend"></a>[function <span class="apidocSignatureSpan">stripe.resources.Transfers.</span>extend (sub)](#apidoc.element.stripe.resources.Transfers.extend)
- description and source-code
```javascript
extend = function (sub) {
  var Super = this;
  var Constructor = hasOwn.call(sub, 'constructor') ? sub.constructor : function() {
    Super.apply(this, arguments);
  };
  Constructor.prototype = Object.create(Super.prototype);
  for (var i in sub) {
    if (hasOwn.call(sub, i)) {
      Constructor.prototype[i] = sub[i];
    }
  }
  for (i in Super) {
    if (hasOwn.call(Super, i)) {
      Constructor[i] = Super[i];
    }
  }
  return Constructor;
}
```
- example usage
```shell
...

_Error.extend = utils.protoExtend;

/**
 * Create subclass of internal Error klass
 * (Specifically for errors returned from Stripe's REST API)
 */
var StripeError = _Error.StripeError = _Error.extend({
  type: 'StripeError',
  populate: function(raw) {
// Move from prototype def (so it appears in stringified obj)
this.type = this.type;

this.stack = (new Error(raw.message)).stack;
this.rawType = raw.type;
...
```

#### <a name="apidoc.element.stripe.resources.Transfers.method"></a>[function <span class="apidocSignatureSpan">stripe.resources.Transfers.</span>method (spec)](#apidoc.element.stripe.resources.Transfers.method)
- description and source-code
```javascript
function stripeMethod(spec) {
  var commandPath = typeof spec.path == 'function' ? spec.path
                  : utils.makeURLInterpolator(spec.path || '');
  var requestMethod = (spec.method || 'GET').toUpperCase();
  var urlParams = spec.urlParams || [];
  var encode = spec.encode || function(data) {return data;};

  return function() {
    var self = this;
    var args = [].slice.call(arguments);

    var callback = typeof args[args.length - 1] == 'function' && args.pop();
    var urlData = this.createUrlData();

    return this.wrapTimeout(new Promise((function(resolve, reject) {
      for (var i = 0, l = urlParams.length; i < l; ++i) {
        // Note that we shift the args array after every iteration so this just
        // grabs the "next" argument for use as a URL parameter.
        var arg = args[0];

        var param = urlParams[i];

        var isOptional = OPTIONAL_REGEX.test(param);
        param = param.replace(OPTIONAL_REGEX, '');

        if (!arg) {
          if (isOptional) {
            urlData[param] = '';
            continue;
          }

          var err = new Error(
            'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
            ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
          );
          reject(err);
          return;
        }

        urlData[param] = args.shift();
      }

      var data = encode(utils.getDataFromArgs(args));
      var opts = utils.getOptionsFromArgs(args);

      if (args.length) {
        var err = new Error(
          'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
          'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      var requestPath = this.createFullPath(commandPath, urlData);
      function requestCallback(err, response) {
        if (err) {
          reject(err);
        } else {
          resolve(
            spec.transformResponseData ?
              spec.transformResponseData(response) :
              response
          );
        }
      };

      var options = {headers: objectAssign(opts.headers, spec.headers)};
      self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
    }).bind(this)), callback);
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.resources.Transfers.prototype"></a>[module stripe.resources.Transfers.prototype](#apidoc.module.stripe.resources.Transfers.prototype)

#### <a name="apidoc.element.stripe.resources.Transfers.prototype.cancel"></a>[function <span class="apidocSignatureSpan">stripe.resources.Transfers.prototype.</span>cancel ()](#apidoc.element.stripe.resources.Transfers.prototype.cancel)
- description and source-code
```javascript
cancel = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Transfers.prototype.createReversal"></a>[function <span class="apidocSignatureSpan">stripe.resources.Transfers.prototype.</span>createReversal ()](#apidoc.element.stripe.resources.Transfers.prototype.createReversal)
- description and source-code
```javascript
createReversal = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Transfers.prototype.listReversals"></a>[function <span class="apidocSignatureSpan">stripe.resources.Transfers.prototype.</span>listReversals ()](#apidoc.element.stripe.resources.Transfers.prototype.listReversals)
- description and source-code
```javascript
listReversals = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Transfers.prototype.listTransactions"></a>[function <span class="apidocSignatureSpan">stripe.resources.Transfers.prototype.</span>listTransactions ()](#apidoc.element.stripe.resources.Transfers.prototype.listTransactions)
- description and source-code
```javascript
listTransactions = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Transfers.prototype.retrieveReversal"></a>[function <span class="apidocSignatureSpan">stripe.resources.Transfers.prototype.</span>retrieveReversal ()](#apidoc.element.stripe.resources.Transfers.prototype.retrieveReversal)
- description and source-code
```javascript
retrieveReversal = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Transfers.prototype.reverse"></a>[function <span class="apidocSignatureSpan">stripe.resources.Transfers.prototype.</span>reverse ()](#apidoc.element.stripe.resources.Transfers.prototype.reverse)
- description and source-code
```javascript
reverse = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.resources.Transfers.prototype.updateReversal"></a>[function <span class="apidocSignatureSpan">stripe.resources.Transfers.prototype.</span>updateReversal ()](#apidoc.element.stripe.resources.Transfers.prototype.updateReversal)
- description and source-code
```javascript
updateReversal = function () {
  var self = this;
  var args = [].slice.call(arguments);

  var callback = typeof args[args.length - 1] == 'function' && args.pop();
  var urlData = this.createUrlData();

  return this.wrapTimeout(new Promise((function(resolve, reject) {
    for (var i = 0, l = urlParams.length; i < l; ++i) {
      // Note that we shift the args array after every iteration so this just
      // grabs the "next" argument for use as a URL parameter.
      var arg = args[0];

      var param = urlParams[i];

      var isOptional = OPTIONAL_REGEX.test(param);
      param = param.replace(OPTIONAL_REGEX, '');

      if (!arg) {
        if (isOptional) {
          urlData[param] = '';
          continue;
        }

        var err = new Error(
          'Stripe: Argument "' + urlParams[i] + '" required, but got: ' + arg +
          ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
        );
        reject(err);
        return;
      }

      urlData[param] = args.shift();
    }

    var data = encode(utils.getDataFromArgs(args));
    var opts = utils.getOptionsFromArgs(args);

    if (args.length) {
      var err = new Error(
        'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
        'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
        ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
      );
      reject(err);
      return;
    }

    var requestPath = this.createFullPath(commandPath, urlData);
    function requestCallback(err, response) {
      if (err) {
        reject(err);
      } else {
        resolve(
          spec.transformResponseData ?
            spec.transformResponseData(response) :
            response
        );
      }
    };

    var options = {headers: objectAssign(opts.headers, spec.headers)};
    self._request(requestMethod, requestPath, data, opts.auth, options, requestCallback);
  }).bind(this)), callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stripe.utils"></a>[module stripe.utils](#apidoc.module.stripe.utils)

#### <a name="apidoc.element.stripe.utils.arrayToObject"></a>[function <span class="apidocSignatureSpan">stripe.utils.</span>arrayToObject (arr)](#apidoc.element.stripe.utils.arrayToObject)
- description and source-code
```javascript
arrayToObject = function (arr) {
  if (Array.isArray(arr)) {
    var obj = {};
    arr.map(function(item, i) {
      obj[i.toString()] = item;
    });
    return obj;
  }
  return arr;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.utils.getDataFromArgs"></a>[function <span class="apidocSignatureSpan">stripe.utils.</span>getDataFromArgs (args)](#apidoc.element.stripe.utils.getDataFromArgs)
- description and source-code
```javascript
getDataFromArgs = function (args) {
  if (args.length > 0) {
    if (isPlainObject(args[0]) && !utils.isOptionsHash(args[0])) {
      return args.shift();
    }
  }
  return {};
}
```
- example usage
```shell
...
    reject(err);
    return;
  }

  urlData[param] = args.shift();
}

var data = encode(utils.getDataFromArgs(args));
var opts = utils.getOptionsFromArgs(args);

if (args.length) {
  var err = new Error(
    'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
    'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
    ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
...
```

#### <a name="apidoc.element.stripe.utils.getOptionsFromArgs"></a>[function <span class="apidocSignatureSpan">stripe.utils.</span>getOptionsFromArgs (args)](#apidoc.element.stripe.utils.getOptionsFromArgs)
- description and source-code
```javascript
getOptionsFromArgs = function (args) {
  var opts = {
    auth: null,
    headers: {},
  }
  if (args.length > 0) {
    var arg = args[args.length - 1];
    if (utils.isAuthKey(arg)) {
      opts.auth = args.pop();
    } else if (utils.isOptionsHash(arg)) {
      var params = args.pop();
      if (params.api_key) {
        opts.auth = params.api_key;
      }
      if (params.idempotency_key) {
        opts.headers['Idempotency-Key'] = params.idempotency_key;
      }
      if (params.stripe_account) {
        opts.headers['Stripe-Account'] = params.stripe_account;
      }
    }
  }
  return opts;
}
```
- example usage
```shell
...
    return;
  }

  urlData[param] = args.shift();
}

var data = encode(utils.getDataFromArgs(args));
var opts = utils.getOptionsFromArgs(args);

if (args.length) {
  var err = new Error(
    'Stripe: Unknown arguments (' + args + '). Did you mean to pass an options ' +
    'object? See https://github.com/stripe/stripe-node/wiki/Passing-Options.' +
    ' (on API request to ' + requestMethod + ' ' + commandPath + ')'
  );
...
```

#### <a name="apidoc.element.stripe.utils.isAuthKey"></a>[function <span class="apidocSignatureSpan">stripe.utils.</span>isAuthKey (key)](#apidoc.element.stripe.utils.isAuthKey)
- description and source-code
```javascript
isAuthKey = function (key) {
  return typeof key == 'string' && /^(?:[a-z]{2}_)?[A-z0-9]{32}$/.test(key);
}
```
- example usage
```shell
...
  getOptionsFromArgs: function(args) {
var opts = {
  auth: null,
  headers: {},
}
if (args.length > 0) {
  var arg = args[args.length - 1];
  if (utils.isAuthKey(arg)) {
    opts.auth = args.pop();
  } else if (utils.isOptionsHash(arg)) {
    var params = args.pop();
    if (params.api_key) {
      opts.auth = params.api_key;
    }
    if (params.idempotency_key) {
...
```

#### <a name="apidoc.element.stripe.utils.isOptionsHash"></a>[function <span class="apidocSignatureSpan">stripe.utils.</span>isOptionsHash (o)](#apidoc.element.stripe.utils.isOptionsHash)
- description and source-code
```javascript
isOptionsHash = function (o) {
  return isPlainObject(o) && ['api_key', 'idempotency_key', 'stripe_account'].some(function(key) {
    return o.hasOwnProperty(key);
  });
}
```
- example usage
```shell
...
}()),

/**
 * Return the data argument from a list of arguments
 */
getDataFromArgs: function(args) {
  if (args.length > 0) {
    if (isPlainObject(args[0]) && !utils.isOptionsHash(args[0])) {
      return args.shift();
    }
  }
  return {};
},

/**
...
```

#### <a name="apidoc.element.stripe.utils.makeURLInterpolator"></a>[function <span class="apidocSignatureSpan">stripe.utils.</span>makeURLInterpolator (str)](#apidoc.element.stripe.utils.makeURLInterpolator)
- description and source-code
```javascript
function makeURLInterpolator(str) {
  var cleanString = str.replace(/["\n\r\u2028\u2029]/g, function($0) {
    return rc[$0];
  });
  return function(outputs) {
    return cleanString.replace(/\{([\s\S]+?)\}/g, function($0, $1) {
      return encodeURIComponent(outputs[$1] || '');
    });
  };
}
```
- example usage
```shell
...
 *  optionally passed through a hash (Object) as the penultimate argument
 *  (preceding the also-optional callback argument
* @param [spec.encode] Function for mutating input parameters to a method.
 *  Usefully for applying transforms to data on a per-method basis.
 */
function stripeMethod(spec) {
var commandPath = typeof spec.path == 'function' ? spec.path
                : utils.makeURLInterpolator(spec.path || '');
var requestMethod = (spec.method || 'GET').toUpperCase();
var urlParams = spec.urlParams || [];
var encode = spec.encode || function(data) {return data;};

return function() {
  var self = this;
  var args = [].slice.call(arguments);
...
```

#### <a name="apidoc.element.stripe.utils.protoExtend"></a>[function <span class="apidocSignatureSpan">stripe.utils.</span>protoExtend (sub)](#apidoc.element.stripe.utils.protoExtend)
- description and source-code
```javascript
protoExtend = function (sub) {
  var Super = this;
  var Constructor = hasOwn.call(sub, 'constructor') ? sub.constructor : function() {
    Super.apply(this, arguments);
  };
  Constructor.prototype = Object.create(Super.prototype);
  for (var i in sub) {
    if (hasOwn.call(sub, i)) {
      Constructor.prototype[i] = sub[i];
    }
  }
  for (i in Super) {
    if (hasOwn.call(Super, i)) {
      Constructor[i] = Super[i];
    }
  }
  return Constructor;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stripe.utils.stringifyRequestData"></a>[function <span class="apidocSignatureSpan">stripe.utils.</span>stringifyRequestData (data)](#apidoc.element.stripe.utils.stringifyRequestData)
- description and source-code
```javascript
stringifyRequestData = function (data) {
  return qs.stringify(data, {arrayFormat: 'brackets'});
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
