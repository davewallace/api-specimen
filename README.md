# git@github.com:davewallace/api-specimen.git
A set of API calls to various services, for convenience.

# Setup

In most cases:
1. run `npm install`
2. load up index.html in a browser

##js-googlemaps

After initial installation on Windows 10, I needed to navigate into 
`/node_modules/google-maps` and run `npm install` again, after that, the sample
file loads with its required dependencies.

# Style guide

I encourage leaving a trail of URLs used to reference or inform your sample
embedded in code comments. Yes, some may rot or become out of date over time,
but even some useful reference links to your implementation might be of help to
someone else, even if only for a short time.

Each sample should have its own dependency specification and build requirements,
platform agnostic where possible and noted otherwise.

## Embedded samples

Within a given sample directory, it is acceptable to contain only a README.md
file, within which a sample URL would be supplied. For example the
`js-googlemaps` directory contains only a README file contain a link to a
more relevant sample; https://github.com/google/google-api-nodejs-client.git

An embedded sample's contents, having been included from an external source,
must be contained within a `embed` directory inside the sample directory, eg;
`/js-googlemaps/embed/`.

# Contributions

In case there's a better workflow with simplicity in mind, let's have a master
branch with feature branches for new samples. When the samples get agreement
between folk, they're into master.

