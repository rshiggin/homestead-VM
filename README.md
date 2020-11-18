## Laravel's Homestead VM adapted for local development instance of PKP's OJS 3.2
  * https://github.com/pkp/ojs
  * https://pkp.sfu.ca/ojs/

### Requirements     
  * VirtualBox     
  * Vagrant     
  * Laravel Homestead 
  * https://laravel.com/docs/8.x/homestead     

### Build environment
    folders:     
        - map: ~/code/ojs1    
          to: /home/vagrant/code    

    sites:     
      - map: ojs3.2.dev    
        to: /home/vagrant/code/public    
        type: apache    
        php: "7.3"    

