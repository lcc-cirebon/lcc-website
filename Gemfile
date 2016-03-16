source "https://rubygems.org"

# grab semua dependencies yang diperlukan gh-pages, termasuk jekyll.
#  harap cek Gemfile.lock, terdapat banyak jekyll gems terinstall.
gem "github-pages"
# TODO: Cek apakah gems di atas bekerja pada gh-pages?

group :test, :development do
  gem "html-proofer" # run `htmlproof ./_site` untuk html validasi
  gem 'jekyll-compose' # dev secara lokal
end
