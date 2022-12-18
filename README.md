# iOS_Admin
IOS 앱 제작 SWIFT프로그래밍 실무_주말

2022-12-18 ~ 2023-02-11

연락처 : kennysy@naver.com

    // 아무곳이나 눌러 softkeyboard 지우기
    override func touchesBegan(_ touches: Set<UITouch>, with event: UIEvent?) {
        self.view.endEditing(true)
    }
