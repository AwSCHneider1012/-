# -

这是一个基于python开发的上海财经大学抢课脚本，1.0仅支持手动修改cookie，后续可能会增加自动获取cookie的部分。
使用方法：
1. 手动登录上财门户
2. 打开到选课页面
3. 找到想选课程的electLessonIds（6位），注意不是课程代码，每一门课的electLessonIds需要打开这门课的详细页，网址部分有例如：https://eams.sufe.edu.cn/eams/allTeachTaskSearch!info.action?removeBack=1&lesson.id=392851；
4. 'Referer'部分需要替换成你自己的id，也就是打开选课页面时的网址，例如: 'https://eams.sufe.edu.cn/eams/stdElectCourse!defaultPage.action?electionProfile.id=12345'
5. 将想抢的课程electLessonIds粘贴到main函数中的course_ids，最好不要超过三门
6. 主函数中的cookie也需要手动修改，方法：
7. 本脚本只适合在已经手动抢完课后，蹲其他人退课的时候使用
8. 本脚本只用于学习，如果造成任何后果，请自行承担
