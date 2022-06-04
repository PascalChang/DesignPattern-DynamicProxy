# DesignPattern-DynamicProxy
動態代理練習
同時學習Java AOP，四個檔案分別為
1.Inteface : 定義物件方法，並且提供Proxy物件參考
2.InstanceObject : 實作介面功能
3.ProxyObject : 繼承 InvocationHandler 複寫 invoke 方法，利用 Reflection 來動態呼叫介面方法，並且加入要多實作的功能(例如 : Log, Transaction....等等)
4.Client : 操作 Proxy 物件，呼叫實體方法
