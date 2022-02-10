task :build do
  sh <<-EOS
charites --provider mapbox build style.yml docs/style.json
  EOS
end

task :host do
  sh <<-EOS
budo -d docs
  EOS
end


