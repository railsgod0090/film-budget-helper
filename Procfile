web: bundle exec puma -t 5:5 -p ${PORT:-3000} -e ${RACK_ENV:-production}
release: bundle exec rake db:migrate 
