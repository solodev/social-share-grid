# social-share-grid
Social share online is fairly standard. A majority of websites have the ability to share content to your respective social network. This functionality usually comes in the form of a few small buttons in the website's navigation or a few icons under a breadcrumb. And while that approach has already proven to be successful we've decided to take it a step further. If your business is trying to gain a traction on social media, perhaps you want to add a social share grid to your homepage. Doing so gives social share more prominence, explains what content site visitors can expect from each respective channel, and also provides your standard social share functionaltity.

## Tutorial

For detailed instructions, view Solodev's [How to Add a Social Share Grid to your Website](https://www.solodev.com/blog/web-design/how-to-add-a-social-share-grid-to-your-website.stml) article.

## Demo

Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/v9dxsp21/).

## HTML

The social share grid contains the following basic HTML markup.

```
<section class="text-center">
  <div class="container">
    <h2>Let's Connect</h2>
    <p>We're everywhere on the web.</p>
    <div class="ct-tabs-outer">
      <div class="row text-center">
        <div class="col-xs-6 col-sm-3">
          <div class="item" data-tab="Twitter">
            <div class="visible">
              <div class="inner"><i class="fa fa-twitter" aria-hidden="true"></i>
              </div>
            </div>
            <div class="item_title">
              <h2>Twitter</h2>
            </div>
            <div class="item_content">
              <p>An online news and social networking service</p>
            </div>
          </div>
        </div>
        <div class="col-xs-6 col-sm-3">
          <div class="item" data-tab="Facebook">
            <div class="visible">
              <div class="inner"><i class="fa fa-facebook" aria-hidden="true"></i>
              </div>
            </div>
            <div class="item_title">
              <h2>Facebook</h2>
            </div>
            <div class="item_content">
              <p>Online social media and social networking service</p>
            </div>
          </div>
        </div>
        <div class="col-xs-6 col-sm-3">
          <div class="item" data-tab="LinkedIn">
            <div class="visible">
              <div class="inner"><i class="fa fa-linkedin" aria-hidden="true"></i>
              </div>
            </div>
            <div class="item_title">
              <h2>LinkedIn</h2>
            </div>
            <div class="item_content">
              <p>A networking tool to find connections</p>
            </div>
          </div>
        </div>
        <div class="col-xs-6 col-sm-3">
          <div class="item" data-tab="Medium">
            <div class="visible">
              <div class="inner"><i class="fa fa-medium" aria-hidden="true"></i>
              </div>
            </div>
            <div class="item_title">
              <h2>Medium</h2>
            </div>
            <div class="item_content">
              <p>Medium is an online publishing platform</p>
            </div>
          </div>
        </div>
      </div>
      <div class="row text-center">
        <div class="col-xs-6 col-sm-3">
          <div class="item" data-tab="Tumblr">
            <div class="visible">
              <div class="inner"><i class="fa fa-tumblr" aria-hidden="true"></i>
              </div>
            </div>
            <div class="item_title">
              <h2>Tumblr</h2>
            </div>
            <div class="item_content">
              <p>Tumblr is a microblogging and social networking website</p>
            </div>
          </div>
        </div>
        <div class="col-xs-6 col-sm-3">
          <div class="item" data-tab="Google Plus">
            <div class="visible">
              <div class="inner"><i class="fa fa-google-plus" aria-hidden="true"></i>
              </div>
            </div>
            <div class="item_title">
              <h2>Google Plus</h2>
            </div>
            <div class="item_content">
              <p>Making sharing on the web more like sharing in real life</p>
            </div>
          </div>
        </div>
        <div class="col-xs-6 col-sm-3">
          <div class="item" data-tab="Reddit">
            <div class="visible">
              <div class="inner"><i class="fa fa-reddit-alien" aria-hidden="true"></i>
              </div>
            </div>
            <div class="item_title">
              <h2>Reddit</h2>
            </div>
            <div class="item_content">
              <p>Social news aggregation, web content rating, and discussion website</p>
            </div>
          </div>
        </div>
        <div class="col-xs-6 col-sm-3">
          <div class="item" data-tab="StumbleUpon">
            <div class="visible">
              <div class="inner"><i class="fa fa-stumbleupon" aria-hidden="true"></i>
              </div>
            </div>
            <div class="item_title">
              <h2>StumbleUpon</h2>
            </div>
            <div class="item_content">
              <p>Discovery engine that finds and recommends web content to its users</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
```
## CSS

All required CSS can be found in social-share-grid.css

## External Includes

This tutorial contains the following third party resources.

```
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" rel="stylesheet">
<link href="social-share-grid.css" rel="stylesheet">
<link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
```
