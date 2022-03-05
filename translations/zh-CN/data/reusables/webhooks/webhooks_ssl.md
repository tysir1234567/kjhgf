如果您的“有效负载 URL”是一个安全站点 (HTTPS)，您可以选择配置 SSL 验证设置。 如果您的“有效负载 URL”不安全 (HTTP)，GitHub 不会显示此选项。 默认情况下，GitHub 在传递 web 挂钩有效负载时验证网站的 SSL 证书。 SSL 验证有助于确保将挂钩有效负载安全地传递到 URL 端点。 您可以选择禁用 SSL，但我们建议保留**Enable SSL verification（启用 SSL 验证）**的选中状态。