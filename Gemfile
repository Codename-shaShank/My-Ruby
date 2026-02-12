source "https://rubygems.org"

# ---- Core infra / k2web-style gems (slightly old versions on purpose) ----
gem "sinatra",     "~> 2.0.0"    # Web framework (needed for app.rb)
gem "redis",       "~> 4.0.0"    # Redis client (k2web uses Redis)
gem "aws-sdk-s3",  "~> 1.90.0"   # S3 client
gem "grape",       "~> 1.1.0"    # API framework (k2web uses Grape)
gem "rack",        "~> 2.0.0"    # Rack (web server interface)
gem "faraday",     "~> 1.0.0"    # HTTP client library

# ---- Dev / test tooling ----
group :development, :test do
  gem "rspec",   "~> 3.9.0"
end
