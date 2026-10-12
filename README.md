Google地圖菜單selector
`div[aria-roledescription="carousel"] button[aria-label^="菜單·"] img`

看有幾個API KEY
https://console.cloud.google.com/apis/credentials?authuser=1

```text
免費試用狀態：抵免額剩餘 $9,510.00，試用期還有 81 天。只要升級為功能完整的帳戶，即可使用所有 Google Cloud 功能，不受任何限制。剩餘的抵免額仍能使用，用盡後會按照用量收費。
```
改用AI Studio，並在免費的專案下建立API Key
https://aistudio.google.com/apikey?authuser=1

如果不在免費的專案下建立API KEY
```text
Gemini 錯誤：Your prepayment credits are depleted. Please go to AI Studio at https://ai.studio/projects to manage your project and billing. Learn more at https://ai.google.dev/gemini-api/docs/billing#prepay.
```
- nearby-scan 這個專案有綁帳單，所以 Gemini 會被當成「預付制」，要先在 AI Studio 儲值才能用。目前預付額度是 0 最少要儲值 $5
- 建議改用免費額度，不用花錢。 剛才的匯入畫面裡，SecureX（securex-1751537470211）旁邊標著「Free tier」，代表它沒綁帳單，可以直接用 Gemini 的免費額度