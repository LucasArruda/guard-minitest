guard :minitest do
  watch(%r{^spec/(.*)_spec\.rb})
  watch(%r{^lib/(.*/)?([^/]+)\.rb}) { |m| "test/#{m[1]}test_#{m[2]}.rb" }
  watch(%r{^spec/spec_helper\.rb})  { 'spec' }
end
