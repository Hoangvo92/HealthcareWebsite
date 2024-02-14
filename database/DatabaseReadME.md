*** Install MongoDB community 7.0
    Website Source: https://www.mongodb.com/docs/manual/tutorial/install-mongodb-on-os-x/
    On Mac, open terminal
   -Install Xcode Command-line tools by using the command line
        xcode-select --install

        If you already installed Xcode Command-line tools, ignore this step. Your terminal will ask you to update. 

   -Install Homebrew by writing this command line in your terminal:
       /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

    You press Enter/Return to finish homebrew installation


   -Install Mongodb 7.0:

   brew tap mongodb/brew
   brew update
   brew install mongodb-community@7.0


   **** Mongosh
       Mongosh: mongodb shell
       



