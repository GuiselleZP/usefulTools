# Programs or packets installed on my Kali Linux

1. **Vim text editor**
	
	It was installed using the comand:

	```
	sudo apt-get install vim
	```

	It was customized by following the steps in the following article [click
	here](https://juncotic.com/vim-plugins-mejorando-favorito/), installing
	the **Vundle** plugin manager.

1. **Build-esscential**

	Is a metapackage (a package that installs many other packages, like g++ and
	gcc: the GNU C & C++ compilers). It's required if you want to compile 
	anything from source, and if you want to work with almost any programming 
	language.

	It was installed using the command:
	```
	sudo apt-get install build-esscential
	```
1. **Python3**
	
	It was installed using the command:
	```
	sudo apt-get install python3
	```
1. **Node.js**

	Node.js is a server-side Javascript environment, based on events. Node.js 
	runs javascript using the V8 engine, developed by Google for the use of its
	Chrome browser. Taking advantage of the V8 engine allows Node.js to provide
	a server-side runtime environment that compiles and executes javascript at 
	incredible speeds.

	It installed it following the steps in the following article ([click
	here](https://ourcodeworld.com/articles/read/410/how-to-install-node-js-in-kali-linux))
	
1. **Turtl App**

	Turtl is a private place to keep your notes, bookmarks, passwords, ideas, 
	dream logs, photos, documents and anything else you want kept safe. Turtl's 
	easy tagging and filtering make it ideal for organization and research 
	whether for personal or professional projects.

	Turtl takes your password from when you sign up and uses it to create a 
	cryptographic key. It uses this key to encrypt your data before storing it 
	anywhere on your device or on our servers. Neither your password nor your 
	key are ever stored anywhere. This means that only you and those you choose 
	to share with can read your data.
	
	I downloaded the compressed file with the extension 'ta.bz2' from the 
	official Turtl page ([click here](https://turtlapp.com/)), the unzipped it
	using the command:
	```
	tar -xjvf compresedFileName.tar.bz2
	```
	This generates a folder, wich in my case had the name '/turtl-linux64'. I
	accessed the folder and ran the installer 'install.sh' with the command:
	```
	./install.sh
	```
	The 'install.sh' can be excecuted in the following ways:
	-	./install.sh '-->' installs Turtl globally (super user rights needed)
    -	./install.sh local '-->' installs Turtl for the current user
    -	./install.sh uninstall '-->' removes Turtl globally and locally (for 
		removing it globally super user rights are required)


	1. **gconf-gsettings-backend**
		The application use the package 'libgconf-2-4', which was used for the 
		GNOME configuration database system (shared libraries), but it was not 
		available, so I installed 'gconf-gsettings-backend' which replaced it.

		It was installed using the command:
		```
		sudo apt-get install gconf-gsettings-backend

		```
1. **Telegram Desktop**

	Is a cloud-based instant messaging and voice over IP service. Users can
	send messages and exchange photos, videos, stickers, audio and files of any
	type.
	
	Telegram's cleint-side code is open-source software but the source code for
	recent versions is not always inmmediately published, whereas its 
	server-side code is closed-source and proprietary.

	Messages and media in Telegram are encrypted when stored on its servers,
	and the client-server communication is also encrypted. The service provides
	end-to-end encryption for voice calls, and optional end-to-end encrypted
	"secret" chats between two online users, yet not for groups or channels.

	It was installed using the command:
	```
	sudo apt install telegram-desktop
	```

1. **MongoDB**

	MongoDB is a NoSQL database system geared towards open-source documents.
	
	Instead of saving the data in table, as it is done in relational databases,
	MongoDB saves BSON data structures (a specification similar to JSON) with a
	dynamic sheme, making the integration of the data in certaing applications
	easier and faster.

	I installed it following the instructions of the oficial website.
	[Click here](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-debian/)
1. **Eclipse**

	[Click here](https://instatecno.com/instalar-eclipse-linux-espanol/)

1. **Megabasterd**

	[Click here](https://jcreparaciones.blogspot.com/2018/04/megabasterdmulti38-para-linux-y-windows.html)

1. **Pandoc**

	[Click here](https://stackoverflow.com/questions/17630486/how-to-convert-from-a-markdown-file-to-pdf)

1. **Evince**

	[Click here](http://elinuxbook.com/install-evince-linux-pdf-viewer-in-ubuntu-16-04-a-document-viewer-for-linux/)
