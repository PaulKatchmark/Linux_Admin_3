#my cool vagrant files, they don't work....please fix. There are 4 errors.
Vagrant.configure("2") do |config|

	 config.vm.define "box1" do |box1|

         	 box1.vm.box="ubuntu/trusty64"
        	 box1.vm.network :forwarded_port, guest: 22, host: 10122, id: "ssh"
   end

  	config.vm.define "box2" do |box2|
       	  box2.vm.box="debian/jessie64" 
         	  box2.vm.network :forwarded_port, guest: 22, host: 10123, id: "ssh"
 	   end
end

#add an "a" for vagrant on line 2
#add an "box1" instead of "box" on line 4
#add an "s" for ssh on line 12
#add "end" on line 14

#I have made the changes for you!
