
begin
  require 'bones'
rescue LoadError
  abort '### Please install the "bones" gem ###'
end

task :default => 'spec:run'
task 'gem:release' => 'spec:run'

Bones {
  name  'mm-nested-attributes'
  authors  'Toni Tuominen'
  email    'toni@piranhadigital.fi'
  url      'http://github.com/tjtuom/mm-nested-attributes'

  ignore_file '.gitignore'

  depend_on 'mongo_mapper', '0.8.2'

  depend_on 'rspec', :development => true
}

