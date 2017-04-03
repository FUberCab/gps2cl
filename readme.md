
# Gps2cl

Convert GPS latitude longitude pairs to the closest craigslist domain.

# Quick Start

  npm install gps2cl

# Usage

  var gps = require('gps2cl');
  var latitude = 30.2669;
  var longitude = 97.7428;
  gps.gps2cl(latitude, longitude);
  // returns "austin"


# Accuracy
The output is approximate. The source data is just a list of coordinates, not actual boundaries. The algorithm just finds the minimum euclidean distance between the point in question and the known points. No error checking for points outside the United States.


# Credit

I found the list of Craigslist subdomains on the internet somewhere, but I can't find them now.


