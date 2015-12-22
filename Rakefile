require "date"

module JekyllBuild
  def project_root
    File.dirname(__FILE__)
  end

  def build_path
    File.expand_path("../build", project_root)
  end

  def current_build
    @current_build ||= DateTime.now.strftime("%Y%m%d%H%M%S")
  end
  
  def current_build_path
    File.join(build_path, current_build)
  end

  def current_path
    File.expand_path("../current", project_root)
  end
end

include JekyllBuild

desc "Generate jekyll site"
task generate: [:build_directory, :build, :unlink, :link] do
  puts "done!"
end

task :build_directory do
  FileUtils.mkdir_p current_build_path
end

task :build do
  system "jekyll build --destination #{current_build_path}"
end

task :unlink do
  FileUtils.rm_rf current_path
end

task :link do
  puts "building..."
  FileUtils.symlink current_build_path, current_path
end
