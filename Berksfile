# frozen_string_literal: true
source artifactory: ENV.fetch('ARTIFACTORY_SUPERMARKET_URL','https://artifactory.prod.platform.reancloud.com/artifactory/api/chef/virtual-supermarket') 

metadata

group :integration do
  cookbook 'test', path: 'test/cookbooks/test'
end
