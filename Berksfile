source 'https://api.berkshelf.com'

metadata

group :runit do
  cookbook 'yum-epel', '~> 1.0'
  cookbook 'runit'
end

group :test do
  cookbook 'java', '< 1.40'
  cookbook 'apt', '< 4.0'
end
