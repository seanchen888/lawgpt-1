# 法律生成文书项目
该项目是一个法律文书自动生成工具，旨在帮助律师、法律机构或个人快速生成标准化的法律文书。

# 功能特点
- 自动生成法律文书：根据用户提供的输入信息，自动生成标准格式的法律文书，如合同、授权书、诉讼状等。
- 自定义模板：支持用户自定义法律文书模板，按照特定格式编写模板，并通过填充关键字段生成具体文书。
- 智能编辑器：提供一个智能化的编辑器界面，方便用户输入信息、选择模板、编辑文书内容等。
- 敏感词过滤：集成敏感词过滤功能，确保生成的文书不包含任何敏感信息。

# 快速开始
## 环境要求
Python 3.8+
安装依赖：pip install -r requirements.txt

## 运行项目
克隆本项目：git clone https://github.com/example/legal-doc-generator.git

进入项目目录：cd legal-doc-generator

启动应用：python app.py

在浏览器中访问：http://localhost:5000

# 使用说明
- 在网页中输入相关信息，如当事人姓名、案由等。
- 选择需要生成的文书类型。
- 根据提示填写其他必要信息。
- 点击生成文书按钮，即可生成标准的法律文书。

# 自定义模板
- 在templates目录下创建一个新的文书模板文件，使用.txt后缀命名。
- 在模板文件中使用占位符表示需要自动填充的字段，例如：{当事人}表示当事人姓名。
- 在应用界面选择自定义模板，并上传对应的模板文件。
- 根据指引填写其他信息并生成文书。

# 注意事项
本工具仅作为法律文书生成的辅助工具，生成的文书可能不符合特定法律要求，请在使用前核对并适当调整。
用户需自行承担使用该工具生成的文书的法律责任。
如遇到问题或有改进建议，请联系开发者。