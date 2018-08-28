# AndroidToolsUtils
使用步骤
1.在build.gradlet添加
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
2. 在项目build.gradlet添加
implementation 'com.github.parry-li:AndroidToolsUtils:-SNAPSHOT'
