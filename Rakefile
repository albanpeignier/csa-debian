require 'rubygems'

require 'debian/build'
include Debian::Build

require 'debian/build/config'

namespace "package" do
  Package.new(:"csa") do |t|
    t.version = '0.4.100106'
    t.debian_increment = 1

    t.source_provider = DebianTarballProvider.new
  end
end


require 'debian/build/tasks'

