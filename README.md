# [Stolen Bicycle Registry](http://stolen-bicycle-registry.herokuapp.com)

Stolen Bicycle Registry is an online database that tracks stolen bicycles. This is an overhaul on the original. As a capstone project for the Epicodus program, we worked as a team of 6 students __directly with the client__ to bring this project to life. Our team had regular check-ins to make sure everyone was on the same page, we worked in pairs and rotated daily to make sure everyone worked together and was well versed in the entire code base. Our client was __very happy__ with the site design and ease of use, but ultimately chose a different route by merging his site with another existing site and combining their databases.

![alt text](https://github.com/Kowser/Ruby_on_Rails_Portfolio/blob/master/stolen_bicycle_registry/screenshots.png "Stolen Bicycle Registry screenshots")

Read below for the dependencies.


## For SEARCH functionality

1. This search feature ONLY works in PostgreSQL.
2. Do not use 'rake rspec', but use 'rspec'.
3. In psql run: `CREATE EXTENSION pg_trgm;`.
4. Run: `rake textacular:install_trigram RAILS_ENV=test` this may tell you it exists.
5. See the [Textacular readme](https://github.com/textacular/textacular#usage) for more information.


## For Phantom JS testing

1. Visit [PhantomJS](http://phantomjs.org/download.html) and install it.
2. Or, in OSX, run this command: `brew install phantomjs`.


## Authors

##### Corbin Dahl
  * [Github](http://github.com/corbindarras)

##### Dan Griffin
  * [Github](http://github.com/dangoldgriff)

##### Niccoli Hersey
  * [Github](http://github.com/niccoli)

##### Abby Ihrig
  * [Github](http://github.com/abbysmalls)

##### Michal Kaszubowski
  * [Github](http://github.com/Kowser)

##### Braden O'Guinn
  * [Github](http://github.com/broguinn)
  * [Twitter](http://twitter.com/broguinn)


## Copyright and License

##### [(The MIT License)](http://opensource.org/licenses/MIT)


Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the 'Software'), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
