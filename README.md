# moment
webshop specializing in web application. it will be created with help monolit structure

## Project Structure
cmd/  # entry points to program
    app/  # main function for run app
        main.go

internal/  # main part of app
    users/  # processing users
        entity.go  # business entities (models)
        usecase.go  # business scenario processing
        repo.go  # abstraction of data access
        handler.go  # processing http requests

pkg/  # auxiliary tools
    logger.go  # logging for found errors

go.mod  # settings go module

## Contributing
not needed, because project is my learning. but you can it pulling use command:
git clone https://github.com/dimasic-cloud/moment.git
then develop your own project, base on my project.

## LICENSE
GNU AFFERO GENERAL PUBLIC LICENSE
entire license is located in LICENSE file

## author
github - dimasic-cloud 
username in telegram - @lostcra 
my channels in telegram - @golangdist and @live_golangdist  # first associated with my path as programmist, second associated with my live without code

## Thanks

thank you, who read it