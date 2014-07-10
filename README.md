vagrant-mongobox
================

A simple little Vagrant box for running MongoDB

1. Install VirtualBox 4.0.

2. Do this. In a terminal:

   ```
   gem install vagrant
   git clone --recursive https://github.com/bobthecow/vagrant-mongobox.git mongobox
   cd mongobox
   vagrant up
   ```

   That last line might take a minute. Go get yourself a sandwich. I went with a lobster roll from Luke’s.

3. Connect to your new dedicated MongoDB virtual machine on localhost port 27018:

   ```
   mongo --port 27018
   ```

4. Profit!
