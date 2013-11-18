Simplicvity
================================
Basic CV. Written with Twitter Bootstrap 3, Grunt, Bower, LESS.

### Install and compile

 1. Install grunt-cli, bower: ``npm install grunt-cli bower``
 2. Install all packages: ``npm install && bower install``
 3. Run build task: ``grunt``
 4. Your CV ready in /dist

### Nginx
Basic nginx config for CV

    server {
      listen   80;
    
      server_name theaqua.im;
    
      root /web/domains/theaqua.im/dist;
      index index.html;
    }
