### 台灣美麗樂-串接金流流程圖(中國信託CTBC)
                    
```seq
App->前台:  傳送ＭemberID 
Note right of 前台: Invoice 產生token,post Request
前台->電子發票:  
Note right of 前台: 回傳token (InvoiceResult)
電子發票-->>前台: 
Note right of 前台: InvoiceResult 驗證token\nResponse Ｙ/ N
前台->電子發票:  
```