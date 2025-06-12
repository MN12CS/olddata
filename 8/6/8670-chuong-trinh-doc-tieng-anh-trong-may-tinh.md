---
title: "Chương trình đọc tiếng Anh trong máy tính"
date: 2025-06-12T11:25:02Z
slug: chuong-trinh-doc-tieng-anh-trong-may-tinh
draft: false
---

## Chương trình đọc tiếng Anh trong máy tính

## assassin64

1. Lời tựa:


Càng ngày, tiếng Anh càng trở nên quan trọng đối với công việc cũng như việc học tập của chúng ta. Nhất là khi lên học đại học, bạn phải sử dụng tiếng Anh nhiều trong việc học hằng ngày... Có 4 kỹ năng cơ bản để học tiếng Anh: nghe - nói - đọc - viết... Và kỹ năng nói cũng là một kỹ năng khó, cần phải luyện tập nhiều.
Thông thường thì bạn sẽ luyện nói cùng bạn bè và cùng với sự giúp đỡ của thầy cô. Nhưng không phải thầy cô lúc nào cũng ở bên bạn để giúp bạn luyện nói, và bạn bè thì không thể kiểm chứng là đúng hay sai được. Có nhiều phần mềm cung cấp khả năng đọc tiếng Anh như LacViet MTD EVA, Talkit. Nhưng không phải ai trong chúng ta cũng có chúng. Vậy phải làm thế nào? Chỉ với vài bước đơn giản, bạn sẽ tự tạo cho mình một chương trình phát âm tiếng Anh gọn nhẹ nhưng tiện dụng.




2. Cách làm
- Mở Notepad (Start -> All Programs -> Accessories -> Notepad) và đánh đoạn code sau:



	Mã:
	Option Explicit
Const MyTitle = "English speech"
Dim MsgRet, EngString, OrgString
OrgString = "What is your name?"
Do While MsgRet <> vbNo
	EngString = InputBox("Enter your English sentence:", MyTitle, OrgString)
	Select Case EngString
	Case ""
		MsgBox "Oh no, you must type an English sentence", vbExclamation+vbOkOnly, MyTitle
	Case Else
		OrgString = EngString
		CreateObject("SAPI.SpVoice").Speak(EngString)
		MsgRet = MsgBox("Do you want to continue?", vbYesNo+vbQuestion, MyTitle)
	End Select
Loop

Plain code:


Option Explicit
Const MyTitle = "English speech"
Dim MsgRet, EngString, OrgString
OrgString = "What is your name?"
Do While MsgRet <> vbNo
	EngString = InputBox("Enter your English sentence:", MyTitle, OrgString)
	Select Case EngString
	Case ""
		MsgBox "Oh no, you must type an English sentence", vbExclamation+vbOkOnly, MyTitle
	Case Else
		OrgString = EngString
		CreateObject("SAPI.SpVoice").Speak(EngString)
		MsgRet = MsgBox("Do you want to continue?", vbYesNo+vbQuestion, MyTitle)
	End Select
	
Loop







- Lưu file với tên "engspeech.vbs". Chú ý phải bỏ trong ngoặc nháy ("") để tránh bị lưu với định dạng *.txt





- Double-click file vừa tạo và cùng thưởng thức 





CHÚC CÁC BẠN THÀNH CÔNG