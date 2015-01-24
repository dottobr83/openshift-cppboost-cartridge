# OpenShift c++ with boost Cartridge

A simple c++ with boost cartridge with a http server application as example in template. The cartridge is based on https://github.com/openshift-cartridges/openshift-cpp-cartridge/ and the template code is from one of the boost examples http://www.boost.org/doc/libs/1_57_0/doc/html/boost_asio/examples/cpp03_examples.html#boost_asio.examples.cpp03_examples.http_server .

To install this cartridge on OpenShift: 

	rhc app create cmake https://raw.githubusercontent.com/luan-cestari/openshift-cppboost-cartridge/master/metadata/manifest.yml
	
This command will then clone the code to your local machine.  You can then update the code, git add, git commit, and git push.  
The code will be compiled on the server and run!

Any question, concerns, or issues? Use the issue tracker on this github repository.  
Want to add something cool to this cartridge?  Fork it and submit a Pull Request.

The project LICENSE file is in the root diretory and we are using GPL3.
