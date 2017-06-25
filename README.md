# CustomNavigationBarTest

스테이터스 바 컬러 교체
1) info.plist 에서 View Controller-based status bar appearence = no 추가
2) 델리게이트 didfinished 에  UIApplication.shared.statusBarStyle = .lightContent 추가
