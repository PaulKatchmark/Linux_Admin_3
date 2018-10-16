#my cool vagrant files, they don't work....please fix. There are 4 errors.
Vagrnt.configure("2") do |config|

	 config.vm.define "box" do |box1|

         	 box1.vm.box="ubuntu/trusty64"
        	 box1.vm.network :forwarded_port, guest: 22, host: 10122, id: "ssh"
   end

  	config.vm.define "box2" do |box2|
       	  box2.vm.box="debian/jessie64" 
         	  box2.vm.network :forwarded_port, guest: 22, host: 10123, id: "sh"
 	   end


