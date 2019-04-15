# flasky
Flask Web


### Flask-Migrate

*使用flask-migrate管理数据库模式变化的步骤：*
1. 对模型类作必要的修改
2. 执行flask db migrate命令，自动创建一个迁移脚本
3. 检查自动生成的脚本，根据对模型的实际改动进行调整
4. 把迁移脚本纳入版本控制
5. 执行flask db upgrade命令，把迁移应用到数据库中