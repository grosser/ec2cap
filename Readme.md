    cap env:server:start    # start server (and remember address for further commands)
    cap env:server:stop     # stop server
    cap env:server:stop_all # stop all servers
    cap env:setup           # setup normal deployment stuff like ruby / nginx etc

    cap env:install_basics
    cap env:install_bundler
    cap env:install_nginx
    cap env:install_node
    cap env:install_ruby
