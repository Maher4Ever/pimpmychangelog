# A sample Guardfile
# More info at https://github.com/guard/guard#readme

guard 'rspec', :version => 2 do
  watch('^spec/(.*)_spec.rb')
  watch('^lib/pimpmychangelog/(.*)\.rb') { |m| "spec/#{m[1]}_spec.rb" }
end
