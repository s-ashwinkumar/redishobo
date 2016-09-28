A simple vagrant configuration to create a box running redis.

## Setup

1. Install [Vagrant](http://www.vagrantup.com/)
1. Install [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
1. Clone the project locally: `git clone git@github.com:s-ashwinkumar/redishobo.git vagrant-redis`
1. Move into the project directory: `cd vagrant-redis`  
1. Provision the virtual machine using Vagrant: `vagrant up`
1. Make sure you have the Redis CLI installed: `brew install redis` (Mac)
1. Test the connection to verify everything is working: `redis-cli -p 6379` (or any other cluster port)

You should now have a redis server running locally at `127.0.0.1:6379`.


## Credits

Thanks to Jason Punyon for this vagrant file https://github.com/JasonPunyon/redishobo . This is just a fork of his version that I decided to utilize to my needs.
