web: bundle exec puma -t 5:5 -p ${PORT:-3000} -e ${RACK_ENV:-development}

web: bundle exec rails s -p $PORT
console: bundle exec rails console

 echo "RACK_ENV=development" >>.env
$ echo "PORT=3000" >> .env