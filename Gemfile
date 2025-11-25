# frozen_string_literal: true
source "https://rubygems.org"

# Chirpy 主题官方推荐的依赖
gem "jekyll"
gem "jekyll-theme-chirpy", "~> 6.7" # 确保版本号与您的主题配置一致

# 保持与 GitHub Pages 兼容的插件列表（虽然我们用 Actions 自行构建，但保留配置）
group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-remote-theme" # 远程主题插件，用于加载 Chirpy
end

# 如果需要本地调试，添加以下 gem
group :development do
  gem "webrick", "~> 1.7"
end
