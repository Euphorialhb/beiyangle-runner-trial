# 蓓养乐沙友试用跟踪

GitHub Pages 托管独立表单，Supabase 托管数据。参与者无需离开页面。

支持登记、续填码、D1–D7每日记录、基线和一周追踪，以及组织者汇总和CSV导出。

config.js 仅含 Supabase 公开 publishable key；后台数据表放在不公开的schema中，只通过校验续填码的接口访问。管理员口令不在网页文件中。

页面：https://euphorialhb.github.io/beiyangle-runner-trial/

开发源文件和数据库schema保存在本地项目 output/native-form。
